# Casos de Uso

## Introdução
Os casos de uso são uma técnica de modelagem que representa uma sequência de interações entre um sistema e um ator(es) externo, culminando em um resultado valioso para o ator. Os nomes dos casos de uso devem ser sempre estruturados como um verbo seguido de um objeto. É importante selecionar nomes fortes e descritivos para deixar evidente, pelo nome, que o caso de uso entregará algo valioso para algum usuário.

## Metodologia
<font size="3"><p style="text-align: center"><b>Tabela 1</b>: Elementos do diagrama de casos de uso</p></font>

| Nome | Função | Elemento
|------|------|:-------:
| Ator | - | -
| Elipse (Caso de Uso) | - | -
| Retângulo (Sistema) | - | -
| Flecha (Relações) | - | -


## Casos de Uso

## [#UC01]Tabela 2: Filtrar Benefícios Sociais

| UC01 | Informações |
|------|-------------|
| **Descrição** | Permite ao responsável familiar registrar sua família no Cadastro Único para acessar benefícios sociais. |
| **Ator** | Responsável familiar |
| **Pré-condições** | Acesso à internet, posse de documentos da família, uso de smartphone ou computador |
| **Ação** | O usuário realiza o cadastro de sua família |
| **Fluxo principal** | <ul><li>O usuário acessa o aplicativo</li><li>Seleciona a opção "Cadastrar Família"</li><li>Insere os dados pessoais e dos membros da família</li><li>Confirma os dados e envia</li><li>Recebe protocolo de envio</li></ul> |
| **Fluxo alternativo** | <ul><li>CPF do responsável já está vinculado</li><li>Usuário é instruído a buscar suporte</li></ul> |
| **Fluxo de exceção** | <ul><li>Erro de conexão</li><li>Dados incompletos ou inválidos</li><li>Aplicativo informa erro e solicita correção</li></ul> |
| **Pós-condições** | Família registrada como grupo familiar no sistema, com cadastro pendente de validação |
| **Data de Criação** | 13/05/2025 |
| **Rastreabilidade** | [RF01](https://github.com/Requisitos-de-Software/2025.1-Cadastro-Unico/blob/main/docs/elicitacao/requisitos_elicitados.md) |

<font size="2"><p style="text-align: center"><b>Autora: <a href="https://github.com/JuliaGabP">Julia Gabriela</a></b></p></font>

---

## [#UC02]Tabela 3: Filtrar Benefícios Sociais

| UC02 | Informações |
|------|-------------|
| **Descrição** | Permite ao usuário buscar e filtrar informações sobre benefícios sociais disponíveis de acordo com seu perfil ou interesse. |
| **Ator** | Usuário (autenticado ou não) |
| **Pré-condições** | Acesso ao aplicativo e à internet |
| **Ação** | O usuário realiza filtros para buscar benefícios sociais no aplicativo |
| **Fluxo principal** | <ul><li>O usuário acessa o aplicativo</li><li>Navega até a seção “Benefícios Disponíveis”</li><li>Utiliza filtros como tipo de benefício, região, faixa de renda ou público-alvo</li><li>O sistema retorna os benefícios correspondentes</li><li>O usuário visualiza detalhes dos benefícios</li></ul> |
| **Fluxo alternativo** | <ul><li>O usuário usa filtros pré-definidos com base no perfil (ex: famílias com crianças)</li><li>O sistema mostra resultados priorizados</li></ul> |
| **Fluxo de exceção** | <ul><li>Filtro retorna nenhum benefício</li><li>Erro de conexão impede exibição</li><li>Filtros inválidos ou mal preenchidos</li></ul> |
| **Pós-condições** | O usuário visualiza os benefícios sociais de acordo com os filtros aplicados |
| **Data de Criação** | 13/05/2025 |
| **Rastreabilidade** | [RF23](https://github.com/Requisitos-de-Software/2025.1-Cadastro-Unico/blob/main/docs/elicitacao/requisitos_elicitados.md) |

<font size="2"><p style="text-align: center"><b>Autora: <a href="https://github.com/JuliaGabP">Julia Gabriela</a></b></p></font>

---

## [#UC10] - Formalização do MEI via aplicativo do CadÚnico

| Campo            | Detalhes |
|------------------|----------|
| **Autor**        | João Pedro Costa |
| **Descrição**    | Permite que o usuário formalize-se como Microempreendedor Individual (MEI) diretamente pelo app do CadÚnico, aproveitando os dados já cadastrados. |
| **Ator**         | Usuário com perfil elegível para formalização |
| **Pré-condições**| Usuário logado com dados atualizados |
| **Ação**         | O usuário solicita formalização como MEI |
| **Fluxo principal** | 1. O usuário acessa o app CadÚnico<br>2. Seleciona "Quero ser MEI"<br>3. O sistema recupera dados e pré-preenche o formulário<br>4. O usuário completa com nome fantasia e atividade<br>5. Informa endereço comercial (se diferente)<br>6. Envia solicitação |
| **Fluxo alternativo** | Dados desatualizados → sistema solicita atualização |
| **Fluxo de exceção** | Falha na conexão durante envio → sistema exibe erro e permite reenviar |
| **Pós-condições** | Solicitação enviada para Receita Federal; usuário acompanha o status pelo app |
| **Data de Criação** | 16/05/2025 |
| **Rastreabilidade** | RF11 |

---

## [#UC11] - Consulta de situação MEI integrada ao CadÚnico

| Campo            | Detalhes |
|------------------|----------|
| **Autor**        | João Pedro Costa |
| **Descrição**    | Permite consultar a situação do CNPJ MEI e obrigações fiscais pelo app CadÚnico |
| **Ator**         | Usuário já formalizado como MEI |
| **Pré-condições**| Usuário logado com CNPJ MEI vinculado ao CPF |
| **Ação**         | Consulta da situação MEI |
| **Fluxo principal** | 1. Usuário acessa o app<br>2. Clica em "Minha Situação MEI"<br>3. Sistema consulta dados na Receita Federal<br>4. Exibe CNPJ, CNAE, status, débitos, DAS<br>5. Fornece orientações em caso de pendências |
| **Fluxo alternativo** | CNPJ inativo → sistema alerta e orienta sobre regularização |
| **Fluxo de exceção** | Falha na consulta → sistema exibe erro temporário |
| **Pós-condições** | Usuário visualiza a situação MEI centralizada no app |
| **Data de Criação** | 16/05/2025 |
| **Rastreabilidade** | RF12 |

---

## [#UC12] - Ajuste de preferências de notificação e acessibilidade

| Campo            | Detalhes |
|------------------|----------|
| **Autor**        | João Pedro Costa |
| **Descrição**    | Permite configurar notificações e acessibilidade no app CadÚnico |
| **Ator**         | Usuário MEI cadastrado |
| **Pré-condições**| Usuário logado no app |
| **Ação**         | Ajuste de preferências |
| **Fluxo principal** | 1. Acessa “Configurações”<br>2. Escolhe canal de notificação (WhatsApp, SMS, e-mail)<br>3. Ativa recursos de acessibilidade (fonte, contraste)<br>4. Salva configurações |
| **Fluxo alternativo** | E-mail ou número inválido → sistema solicita correção |
| **Fluxo de exceção** | Falha nos serviços de envio → app alerta sobre atraso |
| **Pós-condições** | Preferências aplicadas às próximas interações |
| **Data de Criação** | 16/05/2025 |
| **Rastreabilidade** | RF13 |

---

## [#UC13] - Consulta e sincronização automática com a base de dados do MEI

| Campo            | Detalhes |
|------------------|----------|
| **Autor**        | João Pedro Costa |
| **Descrição**    | Permite que o CadÚnico sincronize dados MEI com a Receita Federal automaticamente |
| **Ator**         | Sistema do CadÚnico |
| **Pré-condições**| Usuário com CNPJ MEI ativo vinculado ao CPF no CadÚnico |
| **Ação**         | Sincronização automática de dados |
| **Fluxo principal** | 1. Sistema realiza integração periódica com Receita Federal<br>2. Identifica usuários com CNPJ MEI<br>3. Recupera dados do MEI (status, atividade, débitos)<br>4. Atualiza o perfil do usuário no app<br>5. Notifica o usuário sobre atualizações |
| **Fluxo alternativo** | Dados inconsistentes CPF/CNPJ → alerta técnico para revisão |
| **Fluxo de exceção** | Falha de conexão com Receita → tentativa armazenada e reagendada |
| **Pós-condições** | Perfil MEI atualizado automaticamente no CadÚnico |
| **Data de Criação** | 16/05/2025 |
| **Rastreabilidade** | RF10 |

## Referências

> WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013, p. 144-145.

##### Imagem 1: Casos de Uso
<div style="text-align: center;">
    <img src="../../assets/referencias/introducao_cenario/introducao_cenario_cenario.png" alt="cenarios">
</div>

##### Imagem 2: Casos de Uso

<div style="text-align: center;">
    <img src="../../assets/referencias/introducao_cenario/introducao_cenario_caso_de_uso.png" alt="caso_de_uso">
</div>

## Histórico de Versões

| Versão | Data | Descrição  | Autor        | Revisor |
| :-----: | :----: | :----------: | :------------: | :--------: |
| 1.0 | 16/05/2025 | Criação da pagina e adição de casos de uso | [João Pedro Costa](https://github.com/johnaopedro) |  [Ryan Salles](https://github.com/RA-Salles) |
| 1.1 | 16/05/2025 | Adicionando referencias sobre o tema e imagens| [João Pedro Costa](https://github.com/johnaopedro) |  [Ryan Salles](https://github.com/RA-Salles) |
| 1.2 | 16/05/2025 | Adicionando casos de uso | [Julia Gabriela](https://github.com/JuliaGabP) |  [Ryan Salles](https://github.com/RA-Salles) |
