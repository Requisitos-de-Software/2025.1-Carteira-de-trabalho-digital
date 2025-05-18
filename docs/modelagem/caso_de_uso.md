# Casos de Uso

## Introdução
Os casos de uso são uma técnica de modelagem que representa uma sequência de interações entre um sistema e um ator(es) externo, culminando em um resultado valioso para o ator. Os nomes dos casos de uso devem ser sempre estruturados como um verbo seguido de um objeto. É importante selecionar nomes fortes e descritivos para deixar evidente, pelo nome, que o caso de uso entregará algo valioso para algum usuário.

## Metodologia

O diagrama de casos de uso é uma representação visual da interação de atores com o sistema e visa facilitar o entendimento de como se dará o uso por parte dos atores primários e como os atores secundários se relacionam às funcionalidades que o sistema apresenta. A Tabela 1 apresenta os elementos presentes no diagrama de caso de uso e suas funcionalidades. 

<font size="3"><p style="text-align: center"><b>Tabela 1</b>: Elementos do diagrama de casos de uso</p></font>

| Nome                 | Função                                                            | Elemento
|----------------------|----------------------------------------------------------------   |:-------: |
| Ator                 | Determina algo ou alguém que interagirá com o sistema             | - |
| Elipse (Caso de Uso) | Determina os casos de uso dentro do sistema                       | - |
| Retângulo (Sistema)  | Determina limites do sistema                                      | - |
| Flecha (Relações)    | Determina relações entre os casos de uso ou atores e casos de uso | - |


<!---
We really need to add these images someway somehow. We could use the bilheteria digital model. I hope it works fine.

-l0c.

-->

## Casos de Uso

As tabelas enumeradas como UC01 a UC13 apresentam a especificação de cada caso de uso. 

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

| UC04 | Conferir informações sobre benefícios|
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

| UC05 | Verificar postos de atendimento |
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

| UC06 | Cadastrar família |
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

| UC07 | Filtrar Benefícios Sociais |
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

| UC08 | Acessar chatbot |
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

## [#UC09] Modo Escuro

| UC09 | Ativar modo escuro |
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

## [#UC10] - Indicação de MEI no momento do cadastro

| UC10 | Indicação de MEI no momento do cadastro |
|------------------|----------|
| **Descrição**    | Permite que o usuário informe, durante o processo de cadastro no CadÚnico, que é um Microempreendedor Individual (MEI). |
| **Ator**         | Usuário em processo de cadastro |
| **Pré-condições**| Usuário acessando o app e iniciando novo cadastro |
| **Ação**         | Indicação da condição de MEI durante o cadastro |
| **Fluxo principal** | 1. O usuário inicia o cadastro no app CadÚnico<br>2. Preenche dados pessoais<br>3. Marca a opção “Sou MEI”<br>4. Finaliza o cadastro |
| **Fluxo alternativo** | O usuário ignora a opção → sistema registra como não MEI |
| **Fluxo de exceção** | Dados inconclusivos → sistema alerta para verificação posterior |
| **Pós-condições** | A condição de MEI é registrada no perfil do usuário |
| **Data de Criação** | 16/05/2025 |
| **Rastreabilidade** | [RF11](https://github.com/Requisitos-de-Software/2025.1-Cadastro-Unico/blob/main/docs/elicitacao/requisitos_elicitados.md) |

<font size="2"><p style="text-align: center"><b>Autor: <a href="https://github.com/johnaopedro">João Pedro</a></b></p></font>

---

## [#UC11] - Acesso a informações sobre MEI

| UC11 | Acesso a informações sobre MEI |
|------------------|----------|
| **Descrição**    | Permite que usuários MEI consultem conteúdos informativos sobre microempreendedorismo no app CadÚnico. |
| **Ator**         | Usuário com perfil MEI |
| **Pré-condições**| Usuário logado com perfil registrado como MEI |
| **Ação**         | Consulta de informações sobre MEI |
| **Fluxo principal** | 1. O usuário acessa a seção “MEI” no app<br>2. Visualiza temas como obrigações, benefícios, formalização, linhas de crédito<br>3. Acessa conteúdos de interesse, com links e orientações |
| **Fluxo alternativo** | Perfil não registrado como MEI → sistema exibe convite para formalização |
| **Fluxo de exceção** | Conteúdo indisponível → sistema exibe mensagem informativa |
| **Pós-condições** | O usuário adquire conhecimento sobre seus direitos e deveres como MEI |
| **Data de Criação** | 16/05/2025 |
| **Rastreabilidade** | [RF12](https://github.com/Requisitos-de-Software/2025.1-Cadastro-Unico/blob/main/docs/elicitacao/requisitos_elicitados.md) |

<font size="2"><p style="text-align: center"><b>Autor: <a href="https://github.com/johnaopedro">João Pedro</a></b></p></font>

---

## [#UC12] - Personalização de conteúdos da seção MEI

| UC12            | Personalização de conteúdos da seção MEI |
|------------------|----------|
| **Descrição**    | Permite que o sistema personalize os conteúdos exibidos na seção MEI com base no setor de atuação e localização do usuário. |
| **Ator**         | Usuário MEI cadastrado |
| **Pré-condições**| Usuário logado com setor de atuação e município informados |
| **Ação**         | Personalização automática de conteúdos |
| **Fluxo principal** | 1. O usuário acessa a seção “MEI”<br>2. O sistema identifica setor e região<br>3. Exibe conteúdos segmentados (editais, obrigações, notícias)<br>4. Permite interação com os conteúdos |
| **Fluxo alternativo** | Setor não informado → sistema solicita preenchimento complementar |
| **Fluxo de exceção** | Localização não disponível → sistema utiliza município do cadastro |
| **Pós-condições** | O usuário visualiza conteúdos relevantes ao seu perfil |
| **Data de Criação** | 16/05/2025 |
| **Rastreabilidade** | [RF13](https://github.com/Requisitos-de-Software/2025.1-Cadastro-Unico/blob/main/docs/elicitacao/requisitos_elicitados.md) |

<font size="2"><p style="text-align: center"><b>Autor: <a href="https://github.com/johnaopedro">João Pedro</a></b></p></font>

---

## [#UC13] - Consulta e sincronização automática com a base de dados do MEI

| UC13           | Consulta e sincronização automática com a base de dados do MEI |
|------------------|----------|
| **Descrição**    | Permite que o CadÚnico sincronize dados MEI com a Receita Federal automaticamente |
| **Ator**         | Sistema do CadÚnico |
| **Pré-condições**| Usuário com CNPJ MEI ativo vinculado ao CPF no CadÚnico |
| **Ação**         | Sincronização automática de dados |
| **Fluxo principal** | 1. Sistema realiza integração periódica com Receita Federal<br>2. Identifica usuários com CNPJ MEI<br>3. Recupera dados do MEI (status, atividade, débitos)<br>4. Atualiza o perfil do usuário no app<br>5. Notifica o usuário sobre atualizações |
| **Fluxo alternativo** | Dados inconsistentes CPF/CNPJ → alerta técnico para revisão |
| **Fluxo de exceção** | Falha de conexão com Receita → tentativa armazenada e reagendada |
| **Pós-condições** | Perfil MEI atualizado automaticamente no CadÚnico |
| **Data de Criação** | 16/05/2025 |
| **Rastreabilidade** | [RNF10](https://github.com/Requisitos-de-Software/2025.1-Cadastro-Unico/blob/main/docs/elicitacao/requisitos_elicitados.md) |

<font size="2"><p style="text-align: center"><b>Autor: <a href="https://github.com/johnaopedro">João Pedro</a></b></p></font>

## Tabela de Rastreabilidade UC-CEN-RF

A tabela de rastrabilidade é apresentada por meio da Tabela 3, que contêm informações de rastreabilidade do caso de uso apresentado e sua relação com o(s) respectivo(s) cenário(s) e requisito(s) funcional(ais).

<center> <b>Tabela 3:</b> </center>

| Caso de Uso UC | Cenário CN | Requisito Funcional RF |
| :------------: | :--------: | :--------------------: |
| UC01           | CN01       | RF24                   |
| UC02           | CN02       | RF05                   |
| UC03           | CN03       | RF02                   |
| UC04           | CN04       | RF24                   |
| UC05           | CN05       | RF16                   |
| UC06           | CN06       | RF06                   |
| UC07           | CN07       | RF23                   |
| UC08           | CN08       | RF26                   |
| UC09           | CN09       | RF38                   |
| UC10           | CN10       | RF11                   |
| UC11           | CN11       | RF12                   |
| UC12           | CN12       | RF13                   |
| UC13           | CN13       | RF10                   |


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
| 1.0 | 16/05/2025 | Criação da pagina e adição de casos de uso 10, 11, 12, 13 | [João Pedro Costa](https://github.com/johnaopedro) |  [Ryan Salles](https://github.com/RA-Salles) |
| 1.1 | 16/05/2025 | Adicionando referencias sobre o tema e imagens| [João Pedro Costa](https://github.com/johnaopedro) |  [Ryan Salles](https://github.com/RA-Salles) |
| 1.2 | 16/05/2025 | Adicionando 5 casos de uso | [Julia Gabriela](https://github.com/JuliaGabP) |  [Ryan Salles](https://github.com/RA-Salles) |
| 1.3 | 17/05/2025 | Adicionando casos de uso 4 e 5 | [Ryan Salles](https://github.com/RA-Salles) | [João Pedro Costa](https://github.com/johnaopedro) |
| 1.4 | 17/05/2025 | Adicionando casos de uso 8 e 9 | [Ryan Salles](https://github.com/RA-Salles) | [João Pedro Costa](https://github.com/johnaopedro) |
| 1.4 | 17/05/2025 | Consertando tabela e casos de uso |[João Pedro Costa](https://github.com/johnaopedro) |[Ryan Salles](https://github.com/RA-Salles) | 