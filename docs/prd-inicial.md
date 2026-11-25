# PRD --- ImobiPro

**Tipo de produto:** SaaS de gestão imobiliária e patrimonial\
**Público principal:** corretores de imóveis autônomos\
**Idioma inicial:** português (Brasil)\
**Versão do documento:** 1.0\
**Escopo:** primeira versão comercial (V1)

------------------------------------------------------------------------

## 1. Visão geral

O ImobiPro é um SaaS destinado a corretores de imóveis autônomos que
precisam organizar sua carteira imobiliária, administrar proprietários e
imóveis, apresentar ofertas publicamente, acompanhar interessados e
facilitar a preparação de contratos de compra e venda ou locação.

A plataforma terá duas áreas principais:

1.  **Painel privado de gestão:** utilizado pelo corretor para
    administrar imóveis, proprietários, interessados, contratos,
    histórico, relatórios e assinatura do SaaS.
2.  **Vitrine pública:** página exclusiva de cada corretor para divulgar
    os imóveis disponíveis e receber contatos de interessados.

Também haverá um portal privado e somente para consulta dos
proprietários que receberem convite do corretor.

O produto deverá oferecer uma experiência administrativa profissional e
eficiente, enquanto a vitrine pública deverá priorizar fotografias,
informações relevantes dos imóveis e facilidade de contato.

O ImobiPro será multiusuário no contexto do SaaS, mas cada corretor terá
um ambiente de dados independente. A V1 não contempla equipes ou
compartilhamento de carteira entre corretores.

## 2. Problema que o projeto resolve

Corretores autônomos frequentemente precisam controlar imóveis,
proprietários, valores, fotografias, interessados e documentos em
ferramentas separadas, planilhas, conversas e arquivos.

Essa fragmentação dificulta a organização da carteira, a consulta do
patrimônio vinculado a cada proprietário, a divulgação dos imóveis e o
acompanhamento das negociações.

O ImobiPro centraliza essas atividades em um único lugar, oferecendo:

-   Organização dos imóveis e proprietários.
-   Visão patrimonial por proprietário e da carteira completa.
-   Divulgação dos imóveis em uma vitrine pública.
-   Captação e acompanhamento de interessados.
-   Preparação de contratos de venda e locação.
-   Histórico de alterações e movimentações.
-   Indicadores e relatórios gerenciais.

## 3. Público-alvo

### 3.1 Corretor autônomo

Usuário principal e responsável pela gestão da própria carteira.

Poderá cadastrar e administrar imóveis, proprietários e interessados,
gerenciar a divulgação pública, preparar contratos, consultar relatórios
e administrar seu plano.

### 3.2 Proprietário de imóvel

Usuário convidado opcionalmente pelo corretor.

Poderá acessar um portal próprio para consultar exclusivamente os
imóveis aos quais está vinculado. Não poderá editar, cadastrar ou
excluir informações.

### 3.3 Visitante da vitrine pública

Pessoa sem necessidade de autenticação que acessa a vitrine de um
corretor para pesquisar imóveis, consultar detalhes e entrar em contato
por WhatsApp ou formulário de interesse.

**Fora do público operacional da V1:** imobiliárias com equipes,
corretores colaboradores e usuários que compartilham uma carteira de
imóveis.

## 4. Objetivo da primeira versão

Entregar uma plataforma funcional para que um corretor autônomo consiga:

1.  Criar sua conta e acessar seu painel.
2.  Cadastrar proprietários e imóveis.
3.  Vincular um ou vários proprietários a um imóvel e vários imóveis a
    um proprietário.
4.  Armazenar e gerenciar fotografias.
5.  Controlar separadamente a disponibilidade para venda e locação.
6.  Divulgar imóveis em uma vitrine pública exclusiva.
7.  Receber e administrar interessados.
8.  Gerar modelos e documentos PDF de contratos.
9.  Convidar proprietários para consulta de seus imóveis.
10. Acompanhar o patrimônio, o histórico e os indicadores da carteira.
11. Consultar e exportar relatórios.
12. Utilizar o plano gratuito ou contratar um plano pago, conforme as
    regras comerciais definidas.

## 5. Funcionalidades da V1

### 5.1 Essenciais

-   Cadastro, autenticação e recuperação de acesso do corretor.
-   Cadastro e gestão de proprietários.
-   Convite opcional de proprietários por e-mail.
-   Portal de consulta dos proprietários.
-   Cadastro, edição, consulta, arquivamento e exclusão controlada de
    imóveis.
-   Relacionamento de múltiplos proprietários com múltiplos imóveis.
-   Upload, ordenação e gerenciamento de fotografias.
-   Finalidade do imóvel: venda, aluguel ou ambos.
-   Status independentes para venda e aluguel.
-   Vitrine pública individual por corretor.
-   Pesquisa e filtros na vitrine.
-   Página de detalhes do imóvel.
-   Contato por WhatsApp e formulário de interesse.
-   CRM básico de interessados.
-   Modelos de contratos de compra e venda e locação.
-   Preenchimento de contratos com dados disponíveis e geração de PDF.
-   Dashboard com indicadores clicáveis.
-   Histórico de alterações e movimentações dos imóveis.
-   Notificações no painel e por e-mail.
-   Relatórios gerenciais e exportação em PDF e Excel.
-   Plano gratuito e plano pago, com limites e permissões.
-   Layout responsivo para smartphones, tablets e desktops.
-   Isolamento dos dados por corretor e controle de acesso por perfil.

### 5.2 Desejáveis dentro da V1, conforme capacidade

-   Filtros adicionais por tipo de imóvel, bairro, cidade e faixa de
    preço.
-   Ordenação da vitrine por preço e data de cadastro.
-   Busca por código de identificação do imóvel.
-   Filtros e pesquisa nas listagens administrativas.
-   Preferências de notificações.
-   Visualização do histórico de alterações em formato de linha do
    tempo.

### 5.3 Não implementar no momento 

-   Domínio próprio para a vitrine do corretor.
-   Integração com plataformas de assinatura digital.
-   Integração com provedor de pagamentos escolhido posteriormente, caso
    não seja definida durante a preparação comercial.
-   Planos adicionais e cobrança anual.
-   Gestão de equipes e colaboradores.
-   Compartilhamento de carteiras entre corretores.
-   Aplicativo mobile nativo.
-   Integração com WhatsApp para notificações automatizadas.
-   Personalizações avançadas da vitrine.

## 6. Fora do escopo da V1

-   Gestão de imobiliárias com múltiplos corretores.
-   Compartilhamento de imóveis entre contas de corretores.
-   Assinatura digital nativa de contratos.
-   Integração com plataformas externas de assinatura digital.
-   Domínio próprio por corretor.
-   Aplicativo mobile nativo.
-   Automação de mensagens pelo WhatsApp.
-   Marketplace ou portal público agregador de imóveis de vários
    corretores.
-   Gestão financeira completa de receitas, comissões, repasses e fluxo
    de caixa.
-   Contabilidade ou emissão fiscal.
-   Negociação e fechamento jurídico automatizados.
-   Avaliação automática de imóveis.
-   Inteligência artificial para precificação ou atendimento.
-   Definição definitiva de preços e limites numéricos dos planos nesta
    etapa.

## 7. Regras de negócio

### 7.1 Contas e isolamento

-   Cada corretor terá um ambiente independente.
-   Um corretor só poderá consultar e administrar os próprios dados.
-   Não haverá compartilhamento de carteiras entre corretores na V1.
-   Proprietários convidados terão acesso somente aos imóveis vinculados
    a eles e às informações autorizadas para consulta.
-   Visitantes públicos não precisarão de conta para consultar a
    vitrine.
-   A vitrine pública deverá exibir somente dados autorizados para
    divulgação.
-   Contratos, documentos, dados de interessados e informações privadas
    não poderão ser expostos publicamente.
-   A autorização deverá ser aplicada no acesso aos dados, e não somente
    ocultando elementos da interface.

### 7.2 Proprietários e imóveis

-   Um corretor poderá cadastrar vários proprietários.
-   Um proprietário poderá possuir vários imóveis.
-   Um imóvel poderá ter um ou vários proprietários.
-   O relacionamento entre imóveis e proprietários deverá permitir
    consultar os dois sentidos.
-   O cadastro do proprietário não dependerá da criação de uma conta de
    acesso.
-   O convite ao portal do proprietário será opcional.
-   Cada proprietário convidado terá suas próprias credenciais.
-   Um imóvel poderá ser consultado por todos os proprietários
    vinculados que tenham acesso concedido.
-   Informações pessoais dos proprietários não serão exibidas na vitrine
    pública.

### 7.3 Finalidade e disponibilidade

-   A finalidade de um imóvel poderá ser venda, aluguel ou ambos.
-   A finalidade será diferente do status comercial.
-   Os status de venda e aluguel serão independentes.
-   Um imóvel anunciado para venda e aluguel poderá estar disponível em
    uma modalidade e indisponível na outra.
-   Os status de cada modalidade deverão controlar a exibição do imóvel
    nos filtros e resultados da vitrine.
-   Um imóvel alugado não deverá aparecer como disponível para locação.
-   Um imóvel vendido não deverá aparecer como disponível para venda.
-   O status geral de arquivamento deverá retirar o imóvel das listagens
    operacionais e da vitrine, conforme as regras de arquivamento.
-   Os status comerciais propostos são: disponível, reservado, em
    negociação, alugado, vendido e inativo. A aplicação deverá respeitar
    as diferenças entre os status de venda e de aluguel; estados
    incompatíveis com uma modalidade não deverão ser oferecidos para
    ela.

### 7.4 Cadastro do imóvel

O imóvel deverá permitir registrar, conforme aplicável:

-   Título.
-   Código de identificação.
-   Tipo de imóvel.
-   Descrição.
-   Finalidade.
-   Valores de venda e aluguel, quando aplicáveis.
-   Condomínio.
-   IPTU.
-   Estado.
-   Cidade.
-   Bairro.
-   Endereço.
-   Área.
-   Quantidade de quartos.
-   Quantidade de banheiros.
-   Quantidade de vagas.
-   Informação sobre imóvel mobiliado.
-   Características e infraestrutura, como piscina, varanda, elevador e
    churrasqueira.
-   Fotografias.
-   Proprietário ou proprietários vinculados.
-   Status de venda e status de aluguel.

Valores de venda e aluguel deverão ser armazenados e exibidos
separadamente. Um imóvel com ambas as finalidades poderá ter ambos os
valores.

### 7.5 Fotografias e arquivos

-   Um imóvel poderá possuir várias fotografias.
-   O corretor poderá adicionar, remover e ordenar fotografias.
-   A vitrine deverá utilizar as imagens autorizadas para divulgação.
-   Arquivos privados, contratos e documentos não deverão ser acessíveis
    por URLs públicas irrestritas.
-   O sistema deverá respeitar os limites de armazenamento do plano.

### 7.6 Vitrine pública

-   Cada corretor terá um endereço exclusivo no domínio principal do
    ImobiPro.
-   A vitrine exibirá somente os imóveis daquele corretor que estiverem
    autorizados e disponíveis para a modalidade pesquisada.
-   A vitrine permitirá filtrar por venda, aluguel ou ambos.
-   Os cards deverão apresentar, no mínimo, imagem, bairro, valor
    aplicável e informações resumidas.
-   A página individual deverá apresentar detalhes e galeria de imagens.
-   O visitante poderá iniciar contato pelo WhatsApp ou enviar
    formulário de interesse.
-   O endereço público da vitrine deverá ser compartilhável.
-   O domínio próprio ficará fora da V1.

### 7.7 Interessados e CRM

-   O corretor poderá cadastrar interessados manualmente.
-   Formulários públicos deverão gerar registros de interessados
    associados ao corretor e ao imóvel de interesse.
-   O interessado deverá conter, no mínimo, nome e telefone; mensagem
    será opcional.
-   O corretor poderá consultar, editar e arquivar interessados.
-   O interessado poderá ser vinculado a um ou mais imóveis, conforme a
    evolução do atendimento.
-   O CRM deverá oferecer os status: novo, em atendimento, visita
    agendada, em negociação, convertido e perdido.
-   O corretor poderá registrar observações de atendimento.
-   Os interessados serão privados do corretor responsável.

### 7.8 Contratos

-   O sistema oferecerá modelos de compra e venda e de locação.
-   O corretor poderá baixar modelos para preenchimento manual.
-   O corretor poderá selecionar um imóvel e o tipo de operação para
    iniciar a geração de um contrato.
-   Os dados disponíveis do imóvel e dos proprietários vinculados
    poderão preencher campos do documento.
-   O corretor deverá informar os dados do comprador ou locatário e
    completar os campos necessários.
-   O sistema deverá permitir revisar os dados antes de gerar o PDF.
-   O documento gerado poderá ser baixado e impresso.
-   O histórico do imóvel deverá registrar a geração do contrato.
-   Os documentos deverão ser privados e acessíveis somente a usuários
    autorizados.
-   A geração do documento não representa assinatura digital nem
    validação jurídica.
-   Os modelos deverão ser revisáveis por profissional jurídico antes de
    serem utilizados em operações reais.
-   A V1 não terá assinatura digital nativa nem integração externa para
    assinatura.

### 7.9 Dashboard e patrimônio

O dashboard deverá apresentar:

-   Quantidade total de imóveis cadastrados.
-   Quantidade de imóveis disponíveis.
-   Quantidade de imóveis alugados.
-   Quantidade de imóveis vendidos.
-   Valor total do patrimônio cadastrado.
-   Valores anunciados para venda na carteira.
-   Valores anunciados para aluguel na carteira.
-   Quantidade de imóveis por proprietário.

Os indicadores deverão ser clicáveis e abrir listagens com os filtros
correspondentes.

As métricas financeiras deverão ser claramente identificadas: - **Valor
patrimonial cadastrado:** soma dos valores patrimoniais informados para
os imóveis, sem confundir com receita. - **Valor potencial de venda:**
soma dos valores anunciados para venda dos imóveis elegíveis. - **Valor
potencial de aluguel:** soma dos valores mensais anunciados para aluguel
dos imóveis elegíveis.

O sistema deverá evitar somar valores de venda e aluguel em uma única
métrica financeira.

### 7.10 Histórico

-   O sistema deverá registrar alterações relevantes nos imóveis.
-   Deverão ser registrados valores anteriores e novos valores de venda
    e aluguel.
-   Deverão ser registradas mudanças de status por modalidade.
-   Deverão ser registradas movimentações relevantes, como aluguel e
    venda.
-   Deverão ser registradas gerações de contratos.
-   Os registros deverão conter data e hora e identificação do usuário
    responsável.
-   O histórico deverá ser consultável e não poderá ser sobrescrito ou
    apagado por operações comuns.
-   A política de retenção e eventual exclusão por obrigação legal
    deverá ser definida na implementação e nas políticas do produto.

### 7.11 Notificações

As notificações da V1 estarão disponíveis no painel e por e-mail para
eventos relevantes:

-   Novo interessado.
-   Proprietário aceitou convite.
-   Contrato gerado.
-   Alteração de status de imóvel.
-   Limite de plano próximo de ser atingido.
-   Assinatura próxima do vencimento.

As notificações deverão respeitar as permissões e preferências de cada
usuário. Eventos e destinatários deverão ser definidos de forma
consistente para evitar envio de informações privadas a usuários não
autorizados.

### 7.12 Planos e assinaturas

-   O produto terá um plano gratuito e um plano pago na primeira versão
    comercial.
-   O plano gratuito terá limites de utilização.
-   O plano pago terá limites ampliados e acesso a recursos adicionais.
-   Os limites numéricos e preços serão configuráveis posteriormente.
-   O sistema deverá controlar o plano associado a cada corretor.
-   O sistema deverá controlar o estado da assinatura: ativa, pendente,
    vencida ou cancelada.
-   O sistema deverá registrar histórico de pagamentos e vencimentos
    quando houver integração de cobrança.
-   O cancelamento deverá ser possível.
-   O acesso aos recursos deverá respeitar o plano vigente.
-   O provedor de pagamento será escolhido posteriormente.
-   A política exata de acesso após inadimplência deverá ser definida
    antes da ativação comercial.

### 7.13 Arquivamento e exclusão

-   Imóveis, proprietários e interessados poderão ser arquivados.
-   Registros arquivados deixarão de aparecer nas listagens principais.
-   Registros arquivados deverão permanecer consultáveis por uma área
    específica.
-   A exclusão definitiva dependerá da existência de vínculos,
    contratos, histórico ou obrigações que impeçam a remoção.
-   O sistema deverá impedir exclusões que comprometam a integridade dos
    dados ou a rastreabilidade de documentos.
-   A interface deverá explicar por que uma exclusão não pode ser
    realizada.

### 7.14 Responsividade e experiência

-   Todas as áreas da aplicação deverão ser responsivas.
-   A aplicação deverá funcionar em smartphones, tablets, notebooks e
    desktops.
-   Cards, formulários, galerias, dashboards, tabelas e navegação
    deverão adaptar-se a diferentes larguras de tela.
-   A experiência móvel deverá permitir executar as principais tarefas
    sem depender de interações exclusivas de desktop.

## 8. Fluxos principais

### Fluxo 1 --- Cadastro e acesso do corretor

1.  O corretor acessa o ImobiPro.
2.  Informa nome, e-mail, telefone e senha.
3.  O sistema envia a verificação de e-mail.
4.  O corretor confirma o endereço.
5.  O corretor realiza login.
6.  O sistema abre o painel correspondente à sua conta.

### Fluxo 2 --- Cadastro de proprietário

1.  O corretor acessa a área de proprietários.
2.  Seleciona cadastrar proprietário.
3.  Informa os dados necessários.
4.  Salva o cadastro.
5.  O proprietário passa a fazer parte da carteira do corretor.
6.  Opcionalmente, o corretor solicita o envio de convite por e-mail.

### Fluxo 3 --- Convite e acesso do proprietário

1.  O corretor solicita o convite.
2.  O sistema envia um e-mail com link seguro.
3.  O proprietário acessa o convite.
4.  Cria sua senha e conclui o acesso.
5.  O sistema associa a conta aos registros de proprietário corretos.
6.  O proprietário acessa seu portal e consulta somente os imóveis
    vinculados.

### Fluxo 4 --- Cadastro de imóvel e coproprietários

1.  O corretor acessa a área de imóveis.
2.  Seleciona cadastrar imóvel.
3.  Preenche identificação, descrição, localização, características e
    valores.
4.  Define se o imóvel será anunciado para venda, aluguel ou ambos.
5.  Seleciona um ou vários proprietários já cadastrados.
6.  Informa os status comerciais aplicáveis.
7.  Adiciona e organiza fotografias.
8.  Salva o imóvel.
9.  O imóvel fica disponível no painel e, se autorizado e elegível, na
    vitrine pública.

### Fluxo 5 --- Atualização da disponibilidade

1.  O corretor acessa os detalhes do imóvel.
2.  Seleciona a modalidade de venda ou aluguel.
3.  Atualiza o status daquela modalidade.
4.  O sistema registra a alteração no histórico.
5.  A vitrine atualiza a elegibilidade do imóvel para aquela modalidade.
6.  A outra modalidade permanece com seu status independente.

### Fluxo 6 --- Consulta da vitrine pública

1.  O visitante acessa o endereço exclusivo do corretor.
2.  Visualiza os imóveis divulgados.
3.  Filtra por venda, aluguel ou ambos.
4.  Refina a busca conforme os filtros disponíveis.
5.  Abre a página de detalhes de um imóvel.
6.  Escolhe entrar em contato por WhatsApp ou formulário.

### Fluxo 7 --- Contato por WhatsApp

1.  O visitante seleciona o botão de WhatsApp no imóvel.
2.  O sistema abre uma conversa com o número de contato do corretor.
3.  A mensagem inicial identifica o imóvel de interesse.
4.  O visitante envia a mensagem pelo WhatsApp.

### Fluxo 8 --- Formulário de interesse

1.  O visitante abre o formulário do imóvel.
2.  Informa nome e telefone e, opcionalmente, uma mensagem.
3.  Envia o formulário.
4.  O sistema registra o interessado associado ao corretor e ao imóvel.
5.  O corretor recebe uma notificação no painel e por e-mail.
6.  O corretor acompanha o atendimento no CRM.

### Fluxo 9 --- Gestão de interessado

1.  O corretor acessa o CRM.
2.  Consulta os interessados recebidos ou cadastrados manualmente.
3.  Abre um registro.
4.  Consulta o imóvel relacionado e os dados de contato.
5.  Registra observações.
6.  Atualiza o status do atendimento.
7.  Consulta os registros conforme filtros e situação.

### Fluxo 10 --- Geração de contrato

1.  O corretor acessa a área de contratos.
2.  Seleciona compra e venda ou locação.
3.  Seleciona o imóvel.
4.  O sistema apresenta os dados disponíveis do imóvel e proprietários.
5.  O corretor informa os dados do comprador ou locatário.
6.  Completa e revisa os campos obrigatórios.
7.  Confirma a geração.
8.  O sistema gera o PDF e registra o evento no histórico.
9.  O corretor baixa ou imprime o documento.

### Fluxo 11 --- Dashboard e relatórios

1.  O corretor acessa o dashboard.
2.  Visualiza os indicadores da carteira.
3.  Seleciona um indicador.
4.  O sistema abre a listagem com filtros correspondentes.
5.  O corretor acessa relatórios por proprietário, situação, patrimônio,
    interessados ou contratos.
6.  Seleciona os filtros desejados.
7.  Exporta o relatório em PDF ou Excel, quando aplicável.

### Fluxo 12 --- Assinatura e limites do plano

1.  O corretor consulta seu plano atual.
2.  Visualiza limites e recursos disponíveis.
3.  Escolhe o plano pago, quando desejar.
4.  O sistema inicia o fluxo de assinatura conforme o provedor definido
    posteriormente.
5.  O estado da assinatura é atualizado após confirmação confiável do
    pagamento.
6.  O sistema aplica os limites e permissões do plano vigente.

## 9. Critérios gerais de aceite

-   O corretor consegue criar conta, verificar e-mail, entrar e
    recuperar senha.
-   Um corretor não consegue consultar ou alterar dados pertencentes a
    outro corretor.
-   O corretor consegue cadastrar, editar, consultar e arquivar
    proprietários.
-   O corretor consegue cadastrar imóveis com os campos definidos.
-   Um imóvel pode ter vários proprietários.
-   Um proprietário pode estar vinculado a vários imóveis.
-   O corretor consegue convidar um proprietário sem que o convite seja
    obrigatório para concluir o cadastro.
-   O proprietário convidado consegue acessar somente os imóveis aos
    quais está vinculado.
-   O proprietário não consegue editar ou excluir dados.
-   O corretor consegue adicionar, remover e ordenar fotografias.
-   O imóvel pode ter finalidade de venda, aluguel ou ambas.
-   O status de venda é independente do status de aluguel.
-   Um imóvel alugado não aparece como disponível para locação.
-   Um imóvel vendido não aparece como disponível para venda.
-   A vitrine pública exibe apenas imóveis autorizados e elegíveis.
-   A vitrine permite filtrar imóveis por venda e aluguel.
-   O visitante consegue consultar detalhes e fotografias do imóvel.
-   O visitante consegue iniciar contato por WhatsApp.
-   O formulário de interesse cria um registro associado ao corretor e
    ao imóvel.
-   O corretor consegue cadastrar interessados manualmente.
-   O CRM permite acompanhar os status definidos.
-   O corretor consegue gerar contratos de compra e venda e de locação
    em PDF.
-   O contrato utiliza dados disponíveis e permite completar os dados do
    interessado.
-   O sistema registra a geração de contratos no histórico.
-   O dashboard apresenta os indicadores definidos.
-   Os indicadores clicáveis abrem listagens coerentes com o indicador
    selecionado.
-   Os relatórios permitem consultar imóveis por proprietário.
-   Os relatórios podem ser exportados em PDF e Excel.
-   O histórico registra alterações relevantes com data, hora e
    responsável.
-   As notificações aparecem no painel e são enviadas por e-mail
    conforme os eventos definidos.
-   O sistema aplica os limites do plano associado ao corretor.
-   O layout permanece utilizável em smartphones, tablets e desktops.
-   A exclusão definitiva não compromete contratos, vínculos ou
    histórico que precisem ser preservados.

## 10. Stack definida

A stack informada e aprovada para o projeto é:

-   **Aplicação web:** Next.js. 16+.
-   **Backend:** recursos de backend integrados ao Next.js.
-   **Linguagem:** TypeScript.
-   **Autenticação:** Supabase Auth.
-   **Banco de dados:** Supabase com PostgreSQL.
-   **Armazenamento:** Supabase Storage.
-   **Estilização:** TailwindCSS.
-   **Dados assíncronos e requisições HTTP:** TanStack Query.

### Serviços externos ainda não definidos

-   Provedor de cobrança recorrente.
-   Serviço de envio de e-mails transacionais, caso não seja definido o
    serviço apropriado durante o planejamento técnico.
-   Provedor de assinatura digital, reservado para versão futura.

## 11. Justificativa da stack

A stack escolhida permite desenvolver uma aplicação web única com
funcionalidades de interface e backend integradas ao Next.js.

O Supabase oferece autenticação, banco relacional PostgreSQL e
armazenamento de arquivos, atendendo às necessidades centrais de contas,
relacionamentos entre imóveis e proprietários, fotografias e documentos.

O TypeScript ajuda a manter consistência entre as diferentes áreas do
produto. O TailwindCSS permite construir interfaces responsivas. O
TanStack Query será utilizado para gerenciar dados assíncronos e
requisições HTTP no cliente, conforme a estratégia de carregamento
definida durante a implementação.

A stack é proporcional à V1 e evita a necessidade de separar serviços em
múltiplas aplicações sem uma necessidade comprovada.

## 12. Fases de construção

A ordem abaixo organiza as dependências funcionais. A arquitetura
interna e as decisões técnicas detalhadas deverão ser planejadas na
ferramenta de codificação antes da implementação de cada spec.

### Fase 1 --- Base do produto e autenticação

**Objetivo:** disponibilizar a base de acesso e os perfis iniciais.

Specs: - Spec 01 --- Base visual e navegação da aplicação. - Spec 02 ---
Cadastro, login e recuperação de acesso do corretor. - Spec 03 ---
Perfil do corretor e isolamento da conta.

### Fase 2 --- Proprietários e relacionamentos patrimoniais

**Objetivo:** permitir organizar os proprietários e preparar o acesso
opcional ao portal.

Specs: - Spec 04 --- Cadastro e gestão de proprietários. - Spec 05 ---
Convite e portal de consulta do proprietário.

### Fase 3 --- Cadastro e gestão de imóveis

**Objetivo:** construir o núcleo da carteira imobiliária.

Specs: - Spec 06 --- Cadastro e edição de imóveis. - Spec 07 ---
Relacionamento de imóveis e coproprietários. - Spec 08 --- Galeria e
armazenamento de imagens. - Spec 09 --- Finalidade e status
independentes de venda e aluguel. - Spec 10 --- Histórico de
movimentações dos imóveis.

### Fase 4 --- Vitrine pública e captação

**Objetivo:** divulgar os imóveis e receber contatos.

Specs: - Spec 11 --- Vitrine pública exclusiva do corretor. - Spec 12
--- Pesquisa, filtros e detalhes do imóvel. - Spec 13 --- Contato por
WhatsApp e formulário de interesse.

### Fase 5 --- CRM e contratos

**Objetivo:** permitir acompanhar interessados e preparar documentos.

Specs: - Spec 14 --- CRM e gestão de interessados. - Spec 15 --- Modelos
e geração de contratos em PDF.

### Fase 6 --- Gestão patrimonial e relatórios

**Objetivo:** oferecer visão gerencial da carteira.

Specs: - Spec 16 --- Dashboard e indicadores clicáveis. - Spec 17 ---
Relatórios gerenciais e exportações.

### Fase 7 --- Planos, notificações e preparação comercial

**Objetivo:** preparar o produto para operação comercial.

Specs: - Spec 18 --- Notificações no painel e por e-mail. - Spec 19 ---
Planos, limites e controle de assinatura.

### Fase 8 --- Qualidade e preparação para lançamento

**Objetivo:** validar segurança, responsividade e integridade dos fluxos
da V1.

Specs: - Spec 20 --- Arquivamento, exclusão controlada e integridade dos
registros. - Spec 21 --- Validação de responsividade, permissões e
fluxos completos.

## 13. Specs funcionais detalhadas

### Spec 01 --- Base visual e navegação da aplicação

**Fase:** 1 --- Base do produto e autenticação

**Objetivo:** estabelecer a experiência visual e a navegação principal
do ImobiPro.

**Descrição:** A aplicação deverá oferecer uma área privada de gestão
com identidade profissional e navegação clara. A vitrine pública terá
uma identidade visual moderna, elegante e focada nas fotografias. As
duas áreas deverão compartilhar a identidade da marca, mas poderão ter
composições distintas.

**Regras de negócio relacionadas:** - A aplicação deverá ser
responsiva. - A área privada e a pública terão objetivos e navegações
diferentes. - A navegação privada deverá respeitar o perfil autenticado.

**Fluxo do usuário:** 1. O usuário acessa a aplicação. 2. Visualiza a
página de entrada ou autenticação. 3. Após autenticação, acessa a área
privada correspondente ao seu perfil. 4. O corretor navega pelas áreas
de gestão.

**Critérios de aceite:** - A navegação principal apresenta as áreas
previstas para o perfil. - O painel é utilizável em desktop e
dispositivos móveis. - A vitrine e o painel apresentam experiências
visuais adequadas aos seus objetivos. - Estados vazios, carregamento e
erro possuem apresentação compreensível.

**Dependências:** nenhuma.

**Fora do escopo desta spec:** - Implementação das funcionalidades de
cadastro. - Definição de arquitetura interna. - Personalização avançada
da vitrine.

### Spec 02 --- Cadastro, login e recuperação de acesso do corretor

**Fase:** 1 --- Base do produto e autenticação

**Objetivo:** permitir que o corretor crie e acesse sua conta com
segurança.

**Descrição:** O corretor deverá cadastrar nome, e-mail, telefone e
senha. O acesso será feito por e-mail e senha. O sistema deverá oferecer
verificação de e-mail e recuperação de senha por e-mail.

**Regras de negócio relacionadas:** - Cada conta de corretor deverá ser
única. - A verificação de e-mail deverá ser concluída conforme a
política de acesso definida. - A autenticação será realizada pelo
Supabase Auth.

**Fluxo do usuário:** 1. O corretor abre o cadastro. 2. Informa os dados
solicitados. 3. Recebe e confirma o e-mail. 4. Realiza login. 5. Caso
esqueça a senha, solicita recuperação por e-mail. 6. Define uma nova
senha pelo fluxo seguro.

**Critérios de aceite:** - O corretor consegue criar uma conta com os
campos definidos. - O sistema trata e-mails já cadastrados. - O corretor
consegue verificar o e-mail. - O corretor consegue entrar e sair da
conta. - O corretor consegue solicitar e concluir a recuperação de
senha. - Mensagens de erro e sucesso são claras.

**Dependências:** Spec 01.

**Fora do escopo desta spec:** - Login social. - Autenticação
multifator, salvo decisão posterior. - Gestão de equipe.

### Spec 03 --- Perfil do corretor e isolamento da conta

**Fase:** 1 --- Base do produto e autenticação

**Objetivo:** garantir que cada corretor tenha um ambiente independente.

**Descrição:** Os registros de gestão deverão pertencer a um corretor. O
sistema deverá assegurar que as consultas e ações privadas sejam
limitadas aos dados do próprio corretor.

**Regras de negócio relacionadas:** - Não há compartilhamento de
carteira na V1. - O isolamento deverá ser aplicado na camada de acesso
aos dados. - Dados privados não poderão ser acessados apenas por
alteração de identificadores ou URLs. - O perfil do corretor deverá
identificar o proprietário da carteira.

**Fluxo do usuário:** 1. O corretor autentica. 2. O sistema identifica a
conta. 3. O corretor acessa seus dados. 4. Tentativas de acesso a dados
de outra conta são negadas.

**Critérios de aceite:** - Um corretor não consulta dados de outro. - Um
corretor não altera ou exclui dados de outro. - A restrição é aplicada
também a acessos diretos e requisições não realizadas pela interface. -
Os dados apresentados correspondem à conta autenticada.

**Dependências:** Spec 02.

**Fora do escopo desta spec:** - Compartilhamento de dados. - Perfis de
colaboradores. - Administração interna do SaaS.

### Spec 04 --- Cadastro e gestão de proprietários

**Fase:** 2 --- Proprietários e relacionamentos patrimoniais

**Objetivo:** permitir que o corretor mantenha uma carteira organizada
de proprietários.

**Descrição:** O corretor poderá cadastrar, consultar, editar e arquivar
proprietários. O cadastro não exigirá que o proprietário tenha uma conta
de acesso.

**Regras de negócio relacionadas:** - Um corretor poderá cadastrar
vários proprietários. - Um proprietário pertencerá à carteira do
corretor que o cadastrou. - O cadastro do proprietário não exige
convite. - Dados pessoais não serão publicados na vitrine.

**Fluxo do usuário:** 1. O corretor abre a área de proprietários. 2.
Cadastra os dados do proprietário. 3. Salva o registro. 4. Consulta,
edita ou arquiva o proprietário quando necessário.

**Critérios de aceite:** - O corretor consegue cadastrar um
proprietário. - O corretor consegue consultar e editar seus dados. - O
proprietário aparece na carteira do corretor. - O cadastro não exige
e-mail de acesso ou senha. - Dados de proprietários de outros corretores
não são acessíveis.

**Dependências:** Specs 02 e 03.

**Fora do escopo desta spec:** - Portal do proprietário. - Assinatura
eletrônica de documentos. - Compartilhamento de proprietário entre
corretores.

### Spec 05 --- Convite e portal de consulta do proprietário

**Fase:** 2 --- Proprietários e relacionamentos patrimoniais

**Objetivo:** permitir que o corretor conceda acesso opcional ao
proprietário para consulta dos seus imóveis.

**Descrição:** O corretor poderá enviar convite por e-mail a um
proprietário cadastrado. O convidado criará sua própria senha e terá
acesso a um portal de consulta, sem permissões de edição.

**Regras de negócio relacionadas:** - O convite é opcional. - O acesso
deverá ser vinculado ao registro correto do proprietário. - Um
proprietário poderá consultar todos os imóveis aos quais está
vinculado. - Se houver coproprietários convidados, cada um terá seu
próprio acesso. - O proprietário não poderá editar ou excluir dados. - O
proprietário não poderá visualizar imóveis de terceiros.

**Fluxo do usuário:** 1. O corretor abre o cadastro do proprietário. 2.
Solicita o envio do convite. 3. O proprietário recebe o e-mail. 4.
Acessa o link e cria sua senha. 5. Conclui o acesso. 6. Visualiza seus
imóveis no portal.

**Critérios de aceite:** - O corretor consegue convidar um proprietário
cadastrado. - O convite é enviado ao endereço informado. - O
proprietário consegue concluir a criação de senha. - O proprietário
visualiza somente os imóveis vinculados. - O proprietário não consegue
editar ou excluir registros. - O proprietário consegue recuperar sua
senha por e-mail. - Um convite não permite assumir o acesso de outro
proprietário.

**Dependências:** Specs 02, 03 e 04.

**Fora do escopo desta spec:** - Edição de imóveis pelo proprietário. -
Compartilhamento de carteira. - Portal público do proprietário.

### Spec 06 --- Cadastro e edição de imóveis

**Fase:** 3 --- Cadastro e gestão de imóveis

**Objetivo:** permitir que o corretor cadastre e mantenha as informações
completas dos imóveis.

**Descrição:** O cadastro deverá contemplar identificação, descrição,
tipo, finalidade, valores, localização, características, infraestrutura
e situação comercial.

**Regras de negócio relacionadas:** - O imóvel pertence à carteira de um
corretor. - Código de identificação deverá permitir distinguir os
imóveis da carteira. - Valores de venda e aluguel serão independentes. -
Os campos de valor deverão respeitar a finalidade selecionada. - O
imóvel poderá ser associado a um ou mais proprietários por meio da Spec
07.

**Fluxo do usuário:** 1. O corretor abre o cadastro de imóvel. 2.
Informa título, código e tipo. 3. Preenche descrição, localização e
características. 4. Informa valores aplicáveis. 5. Define a finalidade.
6. Salva o imóvel. 7. Consulta ou edita as informações posteriormente.

**Critérios de aceite:** - O corretor consegue cadastrar um imóvel. - O
sistema permite informar os campos definidos na seção 7.4. - O sistema
valida campos obrigatórios e valores inválidos. - O corretor consegue
editar os dados. - Os dados permanecem associados à carteira correta. -
O cadastro pode ser consultado em uma listagem.

**Dependências:** Specs 03 e 04.

**Fora do escopo desta spec:** - Gestão de imagens. - Vitrine pública. -
Geração de contratos. - Avaliação automática de preço.

### Spec 07 --- Relacionamento de imóveis e coproprietários

**Fase:** 3 --- Cadastro e gestão de imóveis

**Objetivo:** permitir relacionamentos de um para muitos e de muitos
para muitos entre proprietários e imóveis.

**Descrição:** O corretor poderá associar vários proprietários a um
imóvel e vários imóveis a um proprietário. Deverá ser possível consultar
os imóveis de um proprietário e os proprietários de um imóvel.

**Regras de negócio relacionadas:** - Um imóvel poderá ter um ou vários
proprietários. - Um proprietário poderá possuir vários imóveis. - Os
vínculos deverão permanecer dentro da carteira do corretor. - A remoção
de um vínculo não deverá apagar o imóvel nem o proprietário. - O portal
de cada proprietário deverá respeitar os vínculos ativos.

**Fluxo do usuário:** 1. O corretor abre um imóvel. 2. Seleciona um ou
mais proprietários cadastrados. 3. Salva os vínculos. 4. Consulta os
proprietários associados ao imóvel. 5. Abre um proprietário e consulta
os imóveis vinculados.

**Critérios de aceite:** - Um imóvel aceita múltiplos proprietários. -
Um proprietário aceita múltiplos imóveis. - O corretor consegue
adicionar e remover vínculos. - O sistema impede vínculos entre
registros de carteiras diferentes. - O portal do proprietário reflete
somente os vínculos autorizados.

**Dependências:** Specs 04 e 06.

**Fora do escopo desta spec:** - Rateio financeiro automático de
patrimônio. - Definição automática de percentuais de propriedade. -
Gestão de inventário ou sucessão.

### Spec 08 --- Galeria e armazenamento de imagens

**Fase:** 3 --- Cadastro e gestão de imóveis

**Objetivo:** permitir a apresentação visual dos imóveis por meio de
várias fotografias.

**Descrição:** O corretor poderá enviar, remover e ordenar fotografias
associadas a um imóvel. As imagens autorizadas poderão ser utilizadas na
vitrine pública.

**Regras de negócio relacionadas:** - As imagens pertencem ao imóvel e à
carteira do corretor. - O armazenamento deverá respeitar os limites do
plano. - Imagens de um corretor não poderão ser acessadas indevidamente
por outro. - O corretor deverá poder definir a ordem de apresentação.

**Fluxo do usuário:** 1. O corretor abre um imóvel. 2. Adiciona
fotografias. 3. Organiza a ordem. 4. Remove imagens quando necessário.
5. Consulta a galeria no painel e na apresentação pública.

**Critérios de aceite:** - O corretor consegue enviar várias imagens. -
O sistema informa falhas de envio. - O corretor consegue ordenar e
remover imagens. - A imagem de destaque é identificável. - As imagens
respeitam os limites do plano. - A vitrine apresenta as imagens
autorizadas.

**Dependências:** Specs 03 e 06.

**Fora do escopo desta spec:** - Edição avançada de fotografias. - Tour
virtual. - Vídeos e transmissões ao vivo.

### Spec 09 --- Finalidade e status independentes de venda e aluguel

**Fase:** 3 --- Cadastro e gestão de imóveis

**Objetivo:** controlar separadamente a comercialização do imóvel para
venda e locação.

**Descrição:** O corretor poderá definir finalidade de venda, aluguel ou
ambos. Quando ambas forem selecionadas, o sistema manterá um status
independente para cada modalidade.

**Regras de negócio relacionadas:** - Finalidade não é status. - Venda e
aluguel terão estados independentes. - A atualização de uma modalidade
não deverá alterar automaticamente a outra. - Um imóvel alugado não será
apresentado como disponível para aluguel. - Um imóvel vendido não será
apresentado como disponível para venda. - A modalidade deverá ter
estados compatíveis com sua operação.

**Fluxo do usuário:** 1. O corretor seleciona a finalidade do imóvel. 2.
Informa os valores aplicáveis. 3. Define o status de venda e/ou aluguel.
4. Atualiza um dos status quando houver mudança. 5. Consulta o reflexo
da mudança na carteira e na vitrine.

**Critérios de aceite:** - O imóvel pode ter finalidade de venda,
aluguel ou ambas. - Os status de venda e aluguel são independentes. -
Alterar o status de aluguel não altera o status de venda. - Alterar o
status de venda não altera o status de aluguel. - Os filtros públicos
respeitam o status da modalidade. - Estados incompatíveis com a
finalidade não são oferecidos.

**Dependências:** Specs 06 e 07.

**Fora do escopo desta spec:** - Gestão de contratos de locação
ativos. - Controle de pagamentos de aluguel. - Gestão de repasses ao
proprietário.

### Spec 10 --- Histórico de movimentações dos imóveis

**Fase:** 3 --- Cadastro e gestão de imóveis

**Objetivo:** preservar a rastreabilidade das principais mudanças
realizadas em cada imóvel.

**Descrição:** O sistema deverá manter histórico de alterações de
valores, status, movimentações de venda e locação e geração de
contratos.

**Regras de negócio relacionadas:** - Os registros terão data, hora e
responsável. - Alterações relevantes deverão preservar o valor anterior
e o novo valor quando aplicável. - O histórico não poderá ser
sobrescrito por operações comuns. - O histórico deverá respeitar o
isolamento da carteira.

**Fluxo do usuário:** 1. O corretor realiza uma alteração relevante. 2.
O sistema registra o evento. 3. O corretor abre o histórico do imóvel.
4. Consulta as movimentações em ordem cronológica.

**Critérios de aceite:** - Alterações de preço são registradas. -
Alterações de status por modalidade são registradas. - Movimentações
relevantes são registradas. - Geração de contrato é registrada. - Cada
evento apresenta data, hora e responsável. - O corretor consegue
consultar o histórico. - Operações comuns não permitem apagar ou
sobrescrever registros históricos.

**Dependências:** Specs 03, 06, 07 e 09.

**Fora do escopo desta spec:** - Auditoria de todos os eventos técnicos
da aplicação. - Relatórios de auditoria avançados. - Restauração
automática de versões anteriores.

### Spec 11 --- Vitrine pública exclusiva do corretor

**Fase:** 4 --- Vitrine pública e captação

**Objetivo:** disponibilizar uma página pública para divulgação dos
imóveis de cada corretor.

**Descrição:** Cada corretor terá uma URL exclusiva no domínio principal
do ImobiPro. A página apresentará sua carteira de imóveis autorizados
para divulgação.

**Regras de negócio relacionadas:** - A URL será exclusiva por
corretor. - A vitrine exibirá somente dados públicos autorizados. - Não
serão exibidos dados pessoais dos proprietários. - Imóveis arquivados ou
indisponíveis para a modalidade não serão apresentados como
disponíveis. - Domínio próprio não fará parte da V1.

**Fluxo do usuário:** 1. O visitante acessa a URL do corretor. 2.
Visualiza a vitrine. 3. Consulta os imóveis divulgados. 4. Abre um
imóvel para ver detalhes. 5. Entra em contato com o corretor.

**Critérios de aceite:** - Cada corretor possui uma URL exclusiva. - A
vitrine apresenta somente imóveis da carteira correspondente. - Dados
privados não são expostos. - A página funciona em dispositivos móveis e
desktop. - A URL pode ser compartilhada. - A vitrine não exige login
para consulta.

**Dependências:** Specs 03, 06, 08 e 09.

**Fora do escopo desta spec:** - Domínio próprio. - Vitrine agregadora
de vários corretores. - Personalização avançada de marca.

### Spec 12 --- Pesquisa, filtros e detalhes do imóvel

**Fase:** 4 --- Vitrine pública e captação

**Objetivo:** permitir que visitantes encontrem e consultem imóveis na
vitrine.

**Descrição:** A vitrine deverá oferecer filtros de finalidade e
informações relevantes para pesquisa. Cada imóvel terá uma página de
detalhes com fotografias, descrição, localização e valores.

**Regras de negócio relacionadas:** - Os filtros respeitarão finalidade
e status por modalidade. - Valores de venda e aluguel serão exibidos
separadamente. - A vitrine apresentará bairro, valor e imagem nos
cards. - Informações privadas não serão exibidas.

**Fluxo do usuário:** 1. O visitante abre a vitrine. 2. Seleciona venda,
aluguel ou ambos. 3. Aplica filtros disponíveis. 4. Visualiza os cards.
5. Abre um imóvel. 6. Consulta informações e fotografias.

**Critérios de aceite:** - O visitante consegue filtrar por venda e
aluguel. - Os resultados respeitam a disponibilidade da modalidade. - Os
cards exibem imagem, bairro e valor aplicável. - A página de detalhes
apresenta as informações públicas cadastradas. - A galeria permite
visualizar as fotografias. - A experiência é responsiva.

**Dependências:** Specs 09 e 11.

**Fora do escopo desta spec:** - Comparação avançada de imóveis. - Mapa
interativo, salvo decisão posterior. - Recomendação personalizada por
inteligência artificial.

### Spec 13 --- Contato por WhatsApp e formulário de interesse

**Fase:** 4 --- Vitrine pública e captação

**Objetivo:** permitir que visitantes entrem em contato com o corretor a
partir de um imóvel.

**Descrição:** Cada imóvel poderá oferecer contato por WhatsApp e
formulário. O formulário deverá registrar o interessado no painel do
corretor.

**Regras de negócio relacionadas:** - O contato deverá identificar o
imóvel de interesse. - O formulário deverá coletar nome e telefone. - A
mensagem será opcional. - O registro será associado à carteira do
corretor. - Os dados do interessado serão privados.

**Fluxo do usuário:** 1. O visitante abre um imóvel. 2. Escolhe WhatsApp
ou formulário. 3. Se escolher WhatsApp, o sistema abre a conversa com
mensagem identificando o imóvel. 4. Se escolher formulário, informa
nome, telefone e mensagem opcional. 5. Envia o formulário. 6. O sistema
registra o interesse e notifica o corretor.

**Critérios de aceite:** - O botão de WhatsApp utiliza o contato do
corretor correto. - A mensagem inicial identifica o imóvel. - O
formulário valida os campos obrigatórios. - O envio cria um interessado
vinculado ao imóvel e corretor. - O visitante recebe confirmação de
envio. - O corretor recebe notificação. - O formulário possui proteção
adequada contra envios abusivos.

**Dependências:** Specs 11 e 12.

**Fora do escopo desta spec:** - Chat interno. - Automação de
WhatsApp. - Campanhas de marketing.

### Spec 14 --- CRM e gestão de interessados

**Fase:** 5 --- CRM e contratos

**Objetivo:** centralizar os potenciais clientes e acompanhar o
atendimento.

**Descrição:** O corretor poderá consultar interessados recebidos pela
vitrine e cadastrar novos registros manualmente. Poderá editar dados,
vincular imóveis, registrar observações e atualizar status.

**Regras de negócio relacionadas:** - Interessados pertencem à carteira
do corretor. - Os status serão novo, em atendimento, visita agendada, em
negociação, convertido e perdido. - O registro deverá manter associação
com o imóvel quando houver. - O corretor poderá arquivar interessados. -
Dados não serão compartilhados entre corretores.

**Fluxo do usuário:** 1. O corretor abre o CRM. 2. Consulta
interessados. 3. Cadastra um interessado manualmente ou abre um contato
recebido. 4. Consulta seus dados e imóvel relacionado. 5. Registra
observações. 6. Atualiza o status. 7. Consulta o histórico de
atendimento disponível.

**Critérios de aceite:** - O corretor consegue cadastrar interessado
manualmente. - O corretor consegue editar e consultar interessados. - O
corretor consegue associar imóveis. - O corretor consegue atualizar os
status definidos. - O corretor consegue registrar observações. - Os
interessados são isolados por carteira. - O sistema permite
arquivamento.

**Dependências:** Specs 03, 06 e 13.

**Fora do escopo desta spec:** - Automação de vendas. - Distribuição de
leads para equipes. - Funil comercial avançado com múltiplos usuários.

### Spec 15 --- Modelos e geração de contratos em PDF

**Fase:** 5 --- CRM e contratos

**Objetivo:** facilitar a preparação de contratos de compra e venda e
locação.

**Descrição:** O corretor terá acesso a modelos prontos para download e
poderá gerar documentos preenchidos com dados disponíveis do imóvel e
proprietários, completando os dados do comprador ou locatário e demais
campos necessários.

**Regras de negócio relacionadas:** - Haverá modelos para compra e venda
e locação. - O corretor deverá revisar os dados antes de gerar o PDF. -
Os documentos serão privados. - A geração será registrada no histórico
do imóvel. - O documento não será considerado assinado digitalmente. -
Os modelos deverão passar por revisão jurídica antes de uso real.

**Fluxo do usuário:** 1. O corretor seleciona o tipo de contrato. 2.
Seleciona o imóvel. 3. Confere os dados do imóvel e proprietários. 4.
Informa os dados do comprador ou locatário. 5. Completa os campos
necessários. 6. Revisa o documento. 7. Gera e baixa o PDF.

**Critérios de aceite:** - Existem modelos para as duas modalidades. - O
corretor consegue baixar modelos para preenchimento manual. - O sistema
permite iniciar um contrato a partir de um imóvel. - Os dados
disponíveis são apresentados para preenchimento. - O corretor consegue
completar e revisar as informações. - O PDF é gerado e pode ser
baixado. - O documento é acessível somente a usuários autorizados. - A
geração é registrada no histórico.

**Dependências:** Specs 06, 07 e 10.

**Fora do escopo desta spec:** - Assinatura digital. - Integração com
plataformas de assinatura. - Consultoria ou validação jurídica
automatizada. - Registro cartorial.

### Spec 16 --- Dashboard e indicadores clicáveis

**Fase:** 6 --- Gestão patrimonial e relatórios

**Objetivo:** oferecer visão resumida da carteira e permitir navegar dos
indicadores para os registros correspondentes.

**Descrição:** O dashboard apresentará os indicadores definidos para a
carteira do corretor. Cada indicador clicável abrirá uma listagem com os
filtros correspondentes.

**Regras de negócio relacionadas:** - Os dados serão limitados à
carteira do corretor. - Valores patrimoniais não serão confundidos com
receitas. - Valores de venda e aluguel serão exibidos separadamente. - A
quantidade por proprietário deverá considerar os vínculos cadastrados. -
Indicadores deverão ter critérios de cálculo consistentes.

**Fluxo do usuário:** 1. O corretor abre o dashboard. 2. Consulta
quantidades e valores. 3. Seleciona um indicador. 4. O sistema abre a
listagem correspondente. 5. O corretor consulta os imóveis.

**Critérios de aceite:** - O dashboard apresenta total de imóveis. -
Apresenta quantidade de imóveis disponíveis. - Apresenta quantidade de
imóveis alugados. - Apresenta quantidade de imóveis vendidos. -
Apresenta valor patrimonial cadastrado. - Apresenta valores potenciais
de venda e aluguel separadamente. - Apresenta quantidade de imóveis por
proprietário. - Os indicadores clicáveis abrem listagens coerentes. - Os
dados são exclusivos da carteira do corretor.

**Dependências:** Specs 06, 07 e 09.

**Fora do escopo desta spec:** - Previsões financeiras. - Cálculo
automático de valor de mercado. - Gestão contábil e fluxo de caixa.

### Spec 17 --- Relatórios gerenciais e exportações

**Fase:** 6 --- Gestão patrimonial e relatórios

**Objetivo:** permitir consultar e exportar informações gerenciais da
carteira.

**Descrição:** O corretor poderá gerar relatórios de imóveis por
proprietário, situação dos imóveis, patrimônio, interessados e
contratos.

**Regras de negócio relacionadas:** - Os relatórios respeitarão o
isolamento da carteira. - Os filtros deverão refletir os critérios
selecionados. - As exportações deverão apresentar dados coerentes com a
consulta. - Relatórios não deverão expor informações de outros
corretores.

**Fluxo do usuário:** 1. O corretor abre relatórios. 2. Seleciona o tipo
de relatório. 3. Define filtros, como proprietário ou período, quando
aplicável. 4. Consulta os resultados. 5. Exporta em PDF ou Excel.

**Critérios de aceite:** - Existe relatório de imóveis por
proprietário. - O corretor consegue selecionar um proprietário e
consultar seus imóveis. - Existe relatório por situação dos imóveis. -
Existe relatório patrimonial. - Existe relatório de interessados e
conversões. - Existe relatório de contratos gerados. - Os relatórios
podem ser exportados em PDF e Excel. - Os arquivos exportados respeitam
os filtros e permissões.

**Dependências:** Specs 07, 10, 14, 15 e 16.

**Fora do escopo desta spec:** - Business intelligence avançado. -
Previsões e indicadores financeiros complexos. - Integração com
ferramentas externas de BI.

### Spec 18 --- Notificações no painel e por e-mail

**Fase:** 7 --- Planos, notificações e preparação comercial

**Objetivo:** informar o corretor sobre eventos relevantes da operação.

**Descrição:** O sistema deverá exibir notificações no painel e enviar
e-mails para eventos definidos, como novos interessados, aceite de
convite, geração de contrato, mudança de status, limites de plano e
vencimento de assinatura.

**Regras de negócio relacionadas:** - Notificações respeitam o
destinatário correto. - Dados privados não serão enviados a usuários sem
permissão. - Eventos deverão evitar duplicidade indevida. - Preferências
de notificação deverão ser respeitadas quando disponíveis.

**Fluxo do usuário:** 1. Um evento relevante acontece. 2. O sistema
identifica o destinatário. 3. Registra a notificação no painel. 4. Envia
o e-mail correspondente. 5. O usuário consulta a notificação.

**Critérios de aceite:** - Novo interessado gera notificação. - Aceite
de convite gera notificação. - Geração de contrato gera notificação. -
Alteração de status gera notificação. - Limite de plano próximo gera
notificação. - Vencimento próximo gera notificação. - Notificações são
direcionadas ao usuário correto. - Falhas de envio não comprometem o
registro do evento.

**Dependências:** Specs 05, 09, 13, 15 e 19.

**Fora do escopo desta spec:** - Notificações automatizadas por
WhatsApp. - Campanhas de e-mail marketing. - Automação configurável pelo
usuário.

### Spec 19 --- Planos, limites e controle de assinatura

**Fase:** 7 --- Planos, notificações e preparação comercial

**Objetivo:** controlar os planos gratuito e pago e aplicar seus limites
de utilização.

**Descrição:** Cada corretor terá um plano associado. O plano gratuito
terá limites e recursos básicos; o plano pago terá limites ampliados e
recursos adicionais. Preços, limites numéricos e provedor de pagamento
serão definidos posteriormente.

**Regras de negócio relacionadas:** - A V1 comercial terá um plano
gratuito e um plano pago. - Os limites serão aplicados por corretor. - O
sistema deverá controlar assinatura ativa, pendente, vencida e
cancelada. - A mudança de plano deverá atualizar as permissões. - A
confirmação de pagamento deverá vir de uma fonte confiável do provedor
escolhido. - A política de acesso em inadimplência deverá ser definida
antes da ativação comercial.

**Fluxo do usuário:** 1. O corretor consulta o plano atual. 2. Visualiza
limites e recursos. 3. Seleciona o plano pago quando desejar. 4. Segue o
fluxo de contratação disponibilizado. 5. O sistema recebe a confirmação
de assinatura. 6. Atualiza o plano e os limites. 7. O corretor acompanha
o estado da assinatura.

**Critérios de aceite:** - Cada corretor possui um plano identificado. -
O plano gratuito aplica limites configurados. - O plano pago aplica
limites ampliados. - O sistema impede ultrapassar limites sem
autorização. - O sistema registra o estado da assinatura. - O sistema
apresenta vencimento e histórico disponível. - O cancelamento é
refletido no estado da assinatura. - As permissões acompanham o plano
vigente. - O fluxo não considera um pagamento concluído sem confirmação
confiável.

**Dependências:** Specs 02 e 03.

**Fora do escopo desta spec:** - Definição final de preços. - Definição
final dos limites numéricos. - Escolha antecipada do provedor. -
Cobrança anual, salvo decisão comercial posterior. - Gestão contábil.

### Spec 20 --- Arquivamento, exclusão controlada e integridade dos registros

**Fase:** 8 --- Qualidade e preparação para lançamento

**Objetivo:** permitir retirar registros da operação sem comprometer
relacionamentos, contratos e histórico.

**Descrição:** O sistema deverá permitir arquivar imóveis, proprietários
e interessados. A exclusão definitiva deverá ser controlada e impedida
quando houver dependências ou obrigações que exijam preservação.

**Regras de negócio relacionadas:** - Arquivamento não equivale a
exclusão. - Registros arquivados poderão ser consultados em área
própria. - Exclusões não poderão comprometer contratos ou histórico
relevante. - O sistema deverá informar impedimentos de exclusão.

**Fluxo do usuário:** 1. O corretor abre um registro. 2. Escolhe
arquivar ou excluir, quando permitido. 3. O sistema verifica vínculos e
dependências. 4. Se houver impedimento, informa o motivo. 5. Se
permitido, conclui a ação. 6. Registros arquivados permanecem
consultáveis.

**Critérios de aceite:** - O corretor consegue arquivar registros
elegíveis. - Registros arquivados deixam as listagens principais. -
Registros arquivados podem ser consultados. - O sistema impede exclusões
que comprometam dados relacionados. - O sistema explica o motivo do
impedimento. - O histórico e documentos preservados continuam íntegros.

**Dependências:** Specs 04, 06, 07, 10, 14 e 15.

**Fora do escopo desta spec:** - Exclusão em massa sem validação. -
Recuperação de dados após exclusão legalmente definitiva. - Política
jurídica completa de retenção de dados.

### Spec 21 --- Validação de responsividade, permissões e fluxos completos

**Fase:** 8 --- Qualidade e preparação para lançamento

**Objetivo:** validar que os principais fluxos da V1 funcionam de ponta
a ponta, com responsividade e controle de acesso.

**Descrição:** O produto deverá ser validado nos diferentes tamanhos de
tela e nos perfis de corretor, proprietário e visitante público. Também
deverão ser verificadas as permissões, os relacionamentos e a
integridade dos fluxos.

**Regras de negócio relacionadas:** - O isolamento entre corretores é
obrigatório. - O proprietário possui acesso somente de consulta aos
imóveis vinculados. - O visitante acessa apenas informações públicas. -
O painel e a vitrine deverão ser responsivos. - Dados privados e
documentos não poderão ser expostos.

**Fluxo do usuário:** 1. O corretor executa os fluxos de cadastro e
gestão. 2. O proprietário acessa o portal. 3. O visitante consulta a
vitrine e envia interesse. 4. O corretor acompanha o CRM e gera
contrato. 5. O corretor consulta dashboard e relatórios. 6. O sistema é
validado em diferentes tamanhos de tela e permissões.

**Critérios de aceite:** - Os fluxos principais da V1 funcionam de ponta
a ponta. - Não há acesso cruzado entre carteiras de corretores. -
Proprietários não conseguem editar dados. - Visitantes não acessam áreas
privadas. - Contratos e documentos não são públicos. - Formulários,
cards, tabelas, galerias e dashboards funcionam em telas pequenas e
grandes. - Estados de carregamento, erro e ausência de dados são
compreensíveis. - Limites de plano são respeitados. - As principais
regras de negócio possuem validações verificáveis.

**Dependências:** Specs 01 a 20.

**Fora do escopo desta spec:** - Testes de carga em escala não
definida. - Certificações externas. - Auditoria independente de
segurança.

## 14. Ordem recomendada de implementação

A ordem recomendada é:

1.  Spec 01 --- Base visual e navegação da aplicação.
2.  Spec 02 --- Cadastro, login e recuperação de acesso do corretor.
3.  Spec 03 --- Perfil do corretor e isolamento da conta.
4.  Spec 04 --- Cadastro e gestão de proprietários.
5.  Spec 05 --- Convite e portal de consulta do proprietário.
6.  Spec 06 --- Cadastro e edição de imóveis.
7.  Spec 07 --- Relacionamento de imóveis e coproprietários.
8.  Spec 08 --- Galeria e armazenamento de imagens.
9.  Spec 09 --- Finalidade e status independentes de venda e aluguel.
10. Spec 10 --- Histórico de movimentações dos imóveis.
11. Spec 11 --- Vitrine pública exclusiva do corretor.
12. Spec 12 --- Pesquisa, filtros e detalhes do imóvel.
13. Spec 13 --- Contato por WhatsApp e formulário de interesse.
14. Spec 14 --- CRM e gestão de interessados.
15. Spec 15 --- Modelos e geração de contratos em PDF.
16. Spec 16 --- Dashboard e indicadores clicáveis.
17. Spec 17 --- Relatórios gerenciais e exportações.
18. Spec 18 --- Notificações no painel e por e-mail.
19. Spec 19 --- Planos, limites e controle de assinatura.
20. Spec 20 --- Arquivamento, exclusão controlada e integridade dos
    registros.
21. Spec 21 --- Validação de responsividade, permissões e fluxos
    completos.

A ordem deverá ser respeitada para evitar que a ferramenta de
programação implemente funcionalidades sem suas dependências funcionais.
Se uma dependência precisar ser antecipada, isso deverá ser justificado
no planejamento técnico da spec correspondente.

## 15. Prompt para utilizar na ferramenta de codificação

Copie o prompt abaixo para Cursor, Claude Code, Codex, Windsurf ou
ferramenta semelhante, anexando o arquivo deste PRD:

``` text
Você é um agente de desenvolvimento responsável por implementar o projeto ImobiPro com base no PRD fornecido.

REGRAS OBRIGATÓRIAS

1. Leia todo o PRD antes de propor qualquer implementação.
2. Respeite rigorosamente o escopo da V1.
3. Não implemente funcionalidades que estejam fora do escopo.
4. Siga a stack definida no PRD:
   - Next.js
   - Backend integrado ao Next.js
   - TypeScript
   - Supabase Auth
   - Supabase PostgreSQL
   - Supabase Storage
   - TailwindCSS
   - TanStack Query
5. Não implemente todas as specs de uma vez.
6. Trabalhe uma spec por vez, seguindo a ordem recomendada.
7. Antes de codificar cada spec, crie um plano técnico de implementação.
8. No plano técnico, informe:
   - Objetivo da spec.
   - Requisitos funcionais envolvidos.
   - Partes do sistema afetadas.
   - Arquivos que provavelmente precisarão ser criados ou alterados.
   - Decisões técnicas necessárias.
   - Dependências anteriores.
   - Regras de segurança e permissões envolvidas.
   - Riscos, dúvidas e possíveis conflitos com o PRD.
   - Como a implementação será validada.
9. Não tome decisões de produto que contrariem o PRD.
10. Se encontrar uma informação ausente, apresente a dúvida e proponha uma alternativa, identificando claramente o que é suposição.
11. Aguarde minha aprovação antes de implementar.
12. Depois de implementar, explique o que foi feito, quais requisitos foram atendidos e como validar.
13. Não avance automaticamente para a próxima spec sem minha autorização.
14. Não considere concluída uma spec sem validar seus critérios de aceite.
15. Preserve o isolamento de dados entre corretores e as permissões de cada perfil em todas as funcionalidades.
16. Não confie somente na interface para proteger dados. Toda operação de acesso e alteração deve respeitar as permissões aplicáveis.
17. Não exponha documentos, imagens privadas ou informações pessoais indevidamente.
18. Não invente integrações, credenciais, preços, limites de planos ou regras comerciais não definidos.

PROCESSO DE TRABALHO

Primeiro, analise o PRD inteiro e identifique:
- As dependências da primeira spec.
- As dúvidas que impedem sua implementação.
- Os riscos funcionais ou de segurança.
- As decisões técnicas que precisam de aprovação.

Em seguida, crie o plano técnico somente da Spec 01.

Não escreva código ainda.

Aguarde minha aprovação para iniciar a implementação da Spec 01.

Após concluir cada spec:
- Apresente um resumo do que foi implementado.
- Relacione os critérios de aceite e seus resultados.
- Informe eventuais pendências.
- Aguarde autorização para avançar.

PRD:
Utilize integralmente o documento ImobiPro_PRD.md fornecido como contexto.
```

## 16. Premissas e decisões pendentes

Os itens abaixo não devem ser tratados como decisões já tomadas.
Precisam ser definidos antes ou durante o planejamento técnico/comercial
correspondente.

  -----------------------------------------------------------------------
  Item                                Situação
  ----------------------------------- -----------------------------------
  Nome do produto                     Confirmado: ImobiPro

  Público da V1                       Confirmado: corretores autônomos

  Perfis                              Confirmados: corretor, proprietário
                                      e visitante

  Stack                               Confirmada

  Plano gratuito e pago               Confirmado

  Preços dos planos                   Pendente

  Limites numéricos dos planos        Pendente

  Provedor de pagamento               Pendente

  Serviço de e-mail transacional      Pendente

  Modelos jurídicos dos contratos     Precisam ser fornecidos ou
                                      revisados

  Regras de retenção e exclusão de    Precisam ser detalhadas
  dados                               

  Política de acesso após             Pendente
  inadimplência                       

  Domínio próprio                     Futuro

  Assinatura digital                  Futuro

  Gestão de equipes                   Fora da V1
  -----------------------------------------------------------------------

### Recomendações de validação antes do lançamento

-   Validar os modelos de contratos com profissional jurídico.
-   Definir os termos de uso e a política de privacidade.
-   Definir os procedimentos de proteção, retenção e exclusão de dados
    pessoais conforme a legislação aplicável, incluindo a LGPD.
-   Definir preços e limites dos planos.
-   Testar rigorosamente o isolamento de dados entre corretores.
-   Testar os acessos de proprietários com múltiplos imóveis e
    coproprietários.
-   Validar os status independentes de venda e aluguel em todos os
    filtros, indicadores e relatórios.

------------------------------------------------------------------------

**Fim do PRD --- ImobiPro**
