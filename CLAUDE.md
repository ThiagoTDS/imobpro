# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

@AGENTS.md

## Project state

`imobpro` is a freshly bootstrapped `create-next-app` project (single initial commit). There is no domain code yet: `src/app/page.tsx` and the metadata in `src/app/layout.tsx` are still the template placeholders.

## Commands

- `npm run dev`: dev server at http://localhost:3000 (also rewrites the Next.js agent-rules block in `AGENTS.md`)
- `npm run build`: production build (also runs the TypeScript type check)
- `npm run start`: serve the production build

No lint script, ESLint config, or test framework is set up yet. To type-check without building, run `npx tsc --noEmit`.

## Stack and non-default configuration

- **Next.js 16.4 + React 19.3, App Router only**, with sources in `src/app/`. The bundled docs live at `node_modules/next/dist/docs/` (`01-app/` covers the App Router). Read the relevant guide there before using any Next.js API, because this version differs from older training data (see AGENTS.md).
- `next.config.ts` turns on several features that change how code must be written:
  - `cacheComponents: true`: Cache Components / Partial Prerendering. Dynamic data access and the `"use cache"` directive have specific rules, so check the docs before fetching data in server components.
  - `reactCompiler: true` (via `babel-plugin-react-compiler`): manual `useMemo`/`useCallback`/`memo` are generally unnecessary.
  - `partialPrefetching: true` and `experimental.agentFeedback: true`.
  - Tailwind is wired through a Turbopack CSS loader rule (`@tailwindcss/turbopack`) rather than PostCSS. There is no `postcss.config`.
- **Tailwind CSS v4**: configured in CSS, not in a `tailwind.config` file. `src/app/globals.css` uses `@import "tailwindcss"` and `@theme inline` to map the CSS variables (`--background`, `--foreground`, Geist fonts) to utilities. Dark mode follows `prefers-color-scheme`.
- Typed route props are global helpers (for example, `LayoutProps<"/">` in `layout.tsx`), generated into `.next/types`.
- Path alias: `@/*` → `src/*`.

## Regras do projeto

Estas regras devem ser seguidas sempre:

@page-rules/page-rules.mdc
@page-rules/rules.mdc

### Resolução de conflitos (prevalece sobre os arquivos acima)

- **Pastas por página:** use `actions/` e `data-access/` **sem underscore** (conforme `rules.mdc`), e não `_actions/`/`_data-access/` como nos exemplos de `page-rules.mdc`. `_components/` continua com underscore. Nunca coloque `page.tsx` ou `route.ts` dentro de `actions/` ou `data-access/`, porque sem o underscore elas viram segmentos de rota.
- **Stack de dados/auth:** Supabase Auth + Drizzle. `requireAuth()` em `@/lib/session` encapsula a sessão do Supabase, e `db` em `@/db` (schema em `@/db/schema`) é o Drizzle apontando para o Postgres do Supabase. Não use Prisma.
- **Cache Components (`cacheComponents: true`):** o `page.tsx` não deve fazer `await requireAuth()`/`await getData()` no topo sem fronteira de Suspense, porque leitura de cookies/sessão fora de `<Suspense>` quebra o build. Mova a parte dinâmica (auth + data-access) para um componente server async renderizado dentro de `<Suspense>` (ou use `loading.tsx`). Consulte `node_modules/next/dist/docs/` para `"use cache"` e APIs dinâmicas.
- **Versão do Next:** o projeto usa Next.js 16.4 (não 15). Siga a versão instalada e os docs em `node_modules/next/dist/docs/`.
- **Zod 4:** use `z.flattenError(validation.error).fieldErrors` em vez do depreciado `validation.error.flatten()`.
- **Busca de dados no client:** os dados vêm do server via props (`page.tsx` → `content.tsx`), e mutações passam por Server Actions. Não adicione useSWR/React Query sem pedido explícito.
- **React Compiler ativo:** evite `useMemo`/`useCallback`/`memo` manuais, salvo necessidade comprovada.
- **Ainda não existe no projeto:** zod, react-hook-form, shadcn/ui, Radix, Drizzle, Supabase, Jest/RTL e Sentry não estão instalados. A implementação de referência `src/app/(painel)/dashboard/account/` e as pastas `src/components`, `src/lib`, `src/db` etc. também não existem. Instale e crie conforme a necessidade. Estilos ficam no Tailwind v4 via `src/app/globals.css`, não em `/styles`.
