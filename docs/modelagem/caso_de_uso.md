# Casos de Uso

## Introdução
Os casos de uso são uma técnica de modelagem que representa uma sequência de interações entre um sistema e um ator(es) externo, culminando em um resultado valioso para o ator. Os nomes dos casos de uso devem ser sempre estruturados como um verbo seguido de um objeto. É importante selecionar nomes fortes e descritivos para deixar evidente, pelo nome, que o caso de uso entregará algo valioso para algum usuário.

## Metodologia
<font size="3"><p style="text-align: center"><b>Tabela 1</b>: Elementos do diagrama de casos de uso</p></font>

| Nome                 | Função                                                            | Elemento
|----------------------|----------------------------------------------------------------   |:-------: |
| Ator                 | Determina algo ou alguém que interagirá com o sistema             | - |
| Elipse (Caso de Uso) | Determina os casos de uso dentro do sistema                       | - |
| Retângulo (Sistema)  | Determina limites do sistema                                      | - |
| Flecha (Relações)    | Determina relações entre os casos de uso ou atores e casos de uso | - |


## Casos de Uso

## [#UC01] Visualização de Benefícios Ativos

| UC01 | Visualização de Benefícios Ativos |
|------|----------------------------|
| **Descrição** | Permite ao usuário visualizar os benefícios sociais ativos vinculados ao seu cadastro no CadÚnico, como o Bolsa Família. |
| **Ator** | Usuário cadastrado |
| **Pré-condições** | O usuário possui cadastro validado no CadÚnico e está autenticado no aplicativo. |
| **Ação** | O usuário acessa a opção “Meus Benefícios” para verificar seus benefícios ativos. |
| **Fluxo principal** | <ol><li>O usuário acessa o aplicativo do CadÚnico</li><li>Seleciona a opção “Meus Benefícios”</li><li>O sistema busca as informações na base de dados do governo</li><li>É exibida uma lista com nome do programa, status (ativo/suspenso), valor recebido e última atualização</li></ol> |
|**Fluxo de exceção** | <ul><li>Usuário sem benefícios ativos: sistema exibe mensagem informativa</li><li>Falha de comunicação com a base de dados: sistema exibe mensagem de erro</li></ul> |
| **Pós-condições** | O usuário visualiza seus benefícios de forma clara e atualizada. |
| **Data de Criação** | 17/05/2025 |
|****Rastreabilidade** | [RF24] (https://github.com/Requisitos-de-Software/2025.1-Cadastro-Unico/blob/main/docs/elicitacao/requisitos_elicitados.md) |

<font size="2"><p style="text-align: center"><b>Autora: <a href="https://github.com/JuliaGabP">Julia Gabriela</a></b></p></font>

---

## [#UC02] Atualização de Dados Cadastrais

| UC02 | Atualização de Dados Cadastrais |
|------|-------------------------------|
| **Descrição** | Permite ao usuário atualizar seus dados pessoais e residenciais no CadÚnico, como endereço e telefone. |
| **Ator** | Usuário cadastrado |
| **Pré-condições** | O usuário está logado no aplicativo e possui cadastro existente. |
| **Ação** | O usuário acessa a seção “Atualizar Cadastro” para alterar informações residenciais. |
| **Fluxo principal** | <ol><li>Usuário acessa o aplicativo</li><li>Vai até a seção “Atualizar Cadastro”</li><li>Seleciona a opção para alterar dados residenciais</li><li>Atualiza endereço, telefone e contato</li><li>Confirma e envia os dados</li><li>O sistema notifica que os dados serão analisados por um agente público</li></ol> |
| **Fluxo de exceção** | <ul><li>CPF com inconsistência: sistema bloqueia alteração e exibe mensagem</li><li>CEP inválido: sistema solicita correção</li></ul> |
| **Pós-condições** | Os dados são enviados para análise e o usuário é notificado que há uma atualização em processamento. |
| **Data de Criação** | 17/05/2025 |
| **Rastreabilidade** | [RF25](https://github.com/Requisitos-de-Software/2025.1-Cadastro-Unico/blob/main/docs/elicitacao/requisitos_elicitados.md) |

<font size="2"><p style="text-align: center"><b>Autora: <a href="https://github.com/JuliaGabP">Julia Gabriela</a></b></p></font>

---

## [#UC03] Primeiro Cadastro no CadÚnico

| UC03 | Primeiro Cadastro no CadÚnico |
|------|----------------------------|
| **Descrição** | Permite a novos usuários realizar seu primeiro cadastro no CadÚnico através do aplicativo. |
| **Ator** | Novo usuário |
| **Pré-condições** | O usuário possui documentos válidos e acesso à internet. |
| **Ação** | O usuário realiza o primeiro cadastro preenchendo os dados exigidos pelo sistema. |
| **Fluxo principal** | <ol><li>Usuário instala e abre o aplicativo</li><li>Seleciona a opção “Fazer Primeiro Cadastro”</li><li>Preenche dados pessoais: nome, CPF, nascimento, endereço, composição familiar</li><li>Envia a solicitação</li><li>O sistema gera um protocolo e informa que o usuário será contatado para validação</li></ol> |
| **Fluxo de exceção** | <ul><li>CPF já existente: sistema bloqueia e sugere login</li><li>Dados obrigatórios faltando: sistema impede envio e destaca os campos incompletos</li></ul> |
| **Pós-condições** | Um cadastro preliminar é criado e enviado para avaliação por um agente social. |
| **Data de Criação** | 17/05/2025 |
| *8Rastreabilidade** | [RF19](https://github.com/Requisitos-de-Software/2025.1-Cadastro-Unico/blob/main/docs/elicitacao/requisitos_elicitados.md) |

<font size="2"><p style="text-align: center"><b>Autora: <a href="https://github.com/JuliaGabP">Julia Gabriela</a></b></p></font>

---

## [#UC04] Conferir informações sobre benefícios

| UC03 | Conferir informações sobre benefícios|
|------|----------------------------|
| **Descrição** | Permite aos usuários com ou sem autenticação lerem acerca dos possíveis benefícios disponíveis no aplicativo |
| **Ator** | Usuário |
| **Pré-condições** | O usuário possui o aplicativo instalado em seu dispositivo compatível |
| **Ação** | O usuário confere informações sobre os benefícios e informa-se |
| **Fluxo principal** | <ol><li>Usuário instala e abre o aplicativo</li> <li>Seleciona a opção "Programas sociais"</li><li> Sistema lista programas sociais com informações disponíveis</li> <li> Usuário clica na opção desejada </li> <li>Sistema lista as informações disponíveis sobre o programa social escolhido </li> </ul> |
| **Fluxo de exceção** | <ul><li>Erro de interface: Sistema lista informações incorretamente ou de forma ilegível</li><li>Sem conexão em computadores: sistema não inicia</li></ul> |
| **Pós-condições** | O usuário possui informações sobre o programa social escolhido |
| **Data de Criação** | 17/05/2025 |
| **Rastreabilidade** | [RF24](https://github.com/Requisitos-de-Software/2025.1-Cadastro-Unico/blob/main/docs/elicitacao/requisitos_elicitados.md) |

<font size="2"><p style="text-align: center"><b>Autor: <a href="https://github.com/RA-Salles">Ryan Salles</a></b></p></font>

---

## [#UC05] Verificar postos de atendimento

| UC03 | Verificar postos de atendimento |
|------|----------------------------|
| **Descrição** | Permite aos usuários verificar postos de atendimento disponíveis |
| **Atores** | Usuário, Sistema CadÚnico|
| **Pré-condições** | O usuário um dispositivo compatível com o aplicativo e acesso à internet. |
| **Ação** | O usuário confere informações sobre os postos de atendimento disponíveis. |
| **Fluxo principal** | <ol><li>Usuário instala e abre o aplicativo</li><li>Seleciona a opção “Postos de atendimento”</li><li>Preenche dados para requisição de informação: Estado, Município, Tipo Posto</li><li>Envia a solicitação</li><li>O sistema lista os postos disponíveis</li> <li> Usuário lê informações listadas </li></ol> |
| **Fluxo de exceção** | <ul><li> Carregamento infinito: sistema passa um período indeterminado obtendo informações sobre o posto escolhido e demais interações são bloqueadas</li><li>Sem conexão: aplicativo não apresenta opções para requisição em caso de falta de conexão com a internet</li></ul> |
| **Pós-condições** | O sistema  lista informações sobre os postos disponíveis. |
| **Data de Criação** | 17/05/2025 |
| **Rastreabilidade** | [RF16](https://github.com/Requisitos-de-Software/2025.1-Cadastro-Unico/blob/main/docs/elicitacao/requisitos_elicitados.md) |

<font size="2"><p style="text-align: center"><b>Autor: <a href="https://github.com/RA-Salles">Ryan Salles</a></b></p></font>

---


## [#UC06] Cadastrar família

| UC06 | Informações |
|------|-------------|
| **Descrição** | Permite ao responsável familiar registrar sua família no Cadastro Único para acessar benefícios sociais. |
| **Ator** | Responsável familiar |
| **Pré-condições** | Acesso à internet, posse de documentos da família, uso de smartphone ou computador |
| **Ação** | O usuário realiza o cadastro de sua família |
| **Fluxo principal** | <ol><li>O usuário acessa o aplicativo</li><li>Seleciona a opção "Cadastrar Família"</li><li>Insere os dados pessoais e dos membros da família</li><li>Confirma os dados e envia</li><li>Recebe protocolo de envio</li></ol> |
| **Fluxo alternativo** | <ol><li>CPF do responsável já está vinculado</li><li>Usuário é instruído a buscar suporte</li></ol> |
| **Fluxo de exceção** | <ul><li>Erro de conexão</li><li>Dados incompletos ou inválidos</li><li>Aplicativo informa erro e solicita correção</li></ul> |
| **Pós-condições** | Família registrada como grupo familiar no sistema, com cadastro pendente de validação |
| **Data de Criação** | 13/05/2025 |
| **Rastreabilidade** | [RF01](https://github.com/Requisitos-de-Software/2025.1-Cadastro-Unico/blob/main/docs/elicitacao/requisitos_elicitados.md) |

<font size="2"><p style="text-align: center"><b>Autora: <a href="https://github.com/JuliaGabP">Julia Gabriela</a></b></p></font>

---

## [#UC07] Filtrar Benefícios Sociais

| UC07 | Informações |
|------|-------------|
| **Descrição** | Permite ao usuário buscar e filtrar informações sobre benefícios sociais disponíveis de acordo com seu perfil ou interesse. |
| **Ator** | Usuário (autenticado ou não) |
| **Pré-condições** | Acesso ao aplicativo e à internet |
| **Ação** | O usuário realiza filtros para buscar benefícios sociais no aplicativo |
| **Fluxo principal** | <ol><li>O usuário acessa o aplicativo</li><li>Navega até a seção “Benefícios Disponíveis”</li><li>Utiliza filtros como tipo de benefício, região, faixa de renda ou público-alvo</li><li>O sistema retorna os benefícios correspondentes</li><li>O usuário visualiza detalhes dos benefícios</li></ol> |
| **Fluxo alternativo** | <ul><li>O usuário usa filtros pré-definidos com base no perfil (ex: famílias com crianças)</li><li>O sistema mostra resultados priorizados</li></ul> |
| **Fluxo de exceção** | <ul><li>Filtro retorna nenhum benefício</li><li>Erro de conexão impede exibição</li><li>Filtros inválidos ou mal preenchidos</li></ul> |
| **Pós-condições** | O usuário visualiza os benefícios sociais de acordo com os filtros aplicados |
| **Data de Criação** | 13/05/2025 |
| **Rastreabilidade** | [RF23](https://github.com/Requisitos-de-Software/2025.1-Cadastro-Unico/blob/main/docs/elicitacao/requisitos_elicitados.md) |

<font size="2"><p style="text-align: center"><b>Autora: <a href="https://github.com/JuliaGabP">Julia Gabriela</a></b></p></font>

---

## [#UC08] Chatbot

| UC03 | Acessar chatbot |
|------|----------------------------|
| **Descrição** | Permite aos usuários consultar um assiste virtual configurado para responder questões e dúvidas frequentes |
| **Atores** | Usuário, Assistente Virtual|
| **Pré-condições** | O usuário um dispositivo compatível com o aplicativo e acesso à internet. |
| **Ação** | O usuário realiza uma pergunta para o chatbot |
| **Fluxo principal** | <ol><li>Usuário instala e abre o aplicativo</li><li>Usuário aperta no botão de "login" /li><li>Usuário preenche informações de login e envia uma solicitação de autenticação</li><li> Usuário é autenticado pelo gov.br</li><li>Usuário aperta no botão "Assitente Virtual" e é movido para a tela do Assistente Virtual</li> <li> Usuário realiza uma pergunta</li> <li>O Assistente Virtual responde a pergunta</li></ol> |
| **Fluxo de exceção** | <ul><li> Usuário não cadastrado: Usuário não consegue acessar a funcionalidade ao não conseguir passar pelo processo de autenticação</li><li>Sem conexão: aplicativo não realiza login ao não possuir conexão com o sistema gov.br</li> <li> Assistente em manutenção: O assistente virtual está em manutenção e está indisponível </li> <li> Assistente não sabe responder: Assistente Virtual não possui informações suficientes para responder ao usuário </li></ul> |
| **Pós-condições** | O usuário tem sua dúvida esclarecida. |
| **Data de Criação** | 17/05/2025 |
| **Rastreabilidade** | [RF26](https://github.com/Requisitos-de-Software/2025.1-Cadastro-Unico/blob/main/docs/elicitacao/requisitos_elicitados.md) |

<font size="2"><p style="text-align: center"><b>Autor: <a href="https://github.com/RA-Salles">Ryan Salles</a></b></p></font>

---

## [#UC08] Modo Escuro

| UC03 | Ativar modo escuro |
|------|----------------------------|
| **Descrição** | Permite aos usuários ativar um "modo escuro", o qual altera a saturação e luminosidade da interface para uso em ambientes de baixa luminosidade |
| **Atores** | Usuário|
| **Pré-condições** | O usuário um dispositivo compatível com o aplicativo|
| **Ação** | O usuário realiza uma pergunta para o chatbot |
| **Fluxo principal** | <ol><li>Usuário instala e abre o aplicativo</li><li>Usuário aperta no botão de "modo escuro" /li><li>Aplicativo atualiza interface para utilizar cores com menor luminosidade e/ou cores mais frias</li></ol> |
| **Fluxo de exceção** | <ul><li> Cores desagradáveis: O novo esquema de cores torna o usuário mais desconfortável no momento</li><li> Má colocação: Usuário não consegue encontrar o botão "Modo escuro"</li></ul> |
| **Pós-condições** | O usuário se sente mais confortável para utilizar o aplicativo |
| **Data de Criação** | 17/05/2025 |
| **Rastreabilidade** | [RF38](https://github.com/Requisitos-de-Software/2025.1-Cadastro-Unico/blob/main/docs/elicitacao/requisitos_elicitados.md) |

<font size="2"><p style="text-align: center"><b>Autor: <a href="https://github.com/RA-Salles">Ryan Salles</a></b></p></font>

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
| 1.2 | 16/05/2025 | Adicionando 5 casos de uso | [Julia Gabriela](https://github.com/JuliaGabP) |  [Ryan Salles](https://github.com/RA-Salles) |
| 1.3 | 17/05/2025 | Adicionando casos de uso 4 e 5 | [Ryan Salles](https://github.com/RA-Salles) | [João Pedro Costa](https://github.com/johnaopedro) |
| 1.4 | 17/05/2025 | Adicionando casos de uso 8 e 9 | [Ryan Salles](https://github.com/RA-Salles) | [João Pedro Costa](https://github.com/johnaopedro) |