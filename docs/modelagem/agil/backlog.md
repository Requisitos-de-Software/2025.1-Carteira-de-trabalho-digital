# Backlog do produto

## Funções dos autores

| Nome | Função |
|-------|---------|
|[Ryan Salles](https://github.com/RA-Salles) | Criação do documento, elaboração de épicos |
|[Gabriel Flores](https://github.com/Gabrielfcoelho) | elaboração dos épicos 3 e 4 |

## Introdução

O backlog do produto é uma técnica de gerência de tarefas de um projeto que visa manter as tarefas organizadas e passíveis de serem concluídas em uma iteração, facilitando a organização, rastreabilidade e entrega contínua de valor às partes interessadas no projeto. O backlog é organizado em temas, épicos, funcionalidades e estórias. 

O backlog é um artefato em constante mudança e pode sofrer alterações de granularidade de funcionalidade e prioridade de uma funcionalidade a fim de manter a capacidade iterativa da equipe que irá executá-lo.

## Metodologia

O backlog apresentado foi desenvolvido a partir dos requisitos elicitados, reunião com o cliente a fim de realizar validação e introspecção por parte dos desenvolvedores.

O backlog é construído a partir da observação de temáticas comuns nas estórias de usuário, que definem os épicos, funcionalidades e agrupam as estórias.

Para fins de construir o backlog, uma reunião à distância com um dos POs foi realizada. Os participantes são apresentados por meio da tabela 1.

<center>
    <b>Tabela 1:<b> Participantes da Reunião com o PO.
</center>

| Nome            | Função                     |
| :-------------: | :------------------------: |
| Lucas M. Arruda | Project Owner/Usuário      |
| João Pedro      | Desenvolvedor/Secretário   |
| Ryan Salles     | Entrevistador/Desenvolvedor|

<center>
    <a href="https://github.com/RA-Salles" target="_blank"> Ryan Salles </a>
</center>


A reunião foi realizada via **Microsoft Teams** no dia 01/06/2025.

<iframe width="560" height="315" src="https://www.youtube.com/embed/T9YJ_fNqxn4?si=XW0fHgTrpbb4Jtso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Backlog 

O backlog foi construído levando em conta as seguintes áreas de uso do software, que correspondem aos épicos: Autenticação, Informação, Requisição, Customização, Acessibilidade, Integração, Segurança. Cada épico possuirá sua própria subseção.

As features e estórias serão apresentadas segundo o modelo da tabela 2.

| Feature | Estórias                 | Prioridade                             |
| :-----: | :---------------------:  | :------------------------------------: |
| FT_XX   | EU_XY <br> EU_XX         | Alta/Média/Baixa <br> Alta/Média/Baixa |

### Temas

Mediante análise das estórias de usuário, foi possível observar os seguintes temas:

- Operações: classifica funcionalidades relacionadas a automação, obtenção de informação e autenticação. Funcionalidades voltadas a tornar o sistema mais eficiente e/ou eficaz.
- Usabilidade: classifica funcionalidades relacionadas a acessibilidade, configuração e maior facilidade de uso. Funcionalidades voltadas a tornar o sistema mais abrangente à população brasileira.

### Épico 1: Autenticação

O Épico 1 trata de aspectos de autenticação do usuário para fins de login e disponibilização de serviços com o mínimo preenchimento de informações adicionais e é apresentado por meio da tabela 3.

<center>
    <b>Tabela 3: </b> Épico 1 - Autenticação
</center>

| Feature                                       | Estórias                                                                                                                                                                         | Prioridade  |
| :-----:                                       | :---------------------------------------------------:                                                                                                                            | :---------: |
| FT_01 - Capacidade de Login                   |  -                                                                                                                                                                               | Alta        |
| FT_02 - Capacidade de Cadastro de Informações | EU_04 -  Cadastro de usuário <br> EU_13 - Registro da condição de MEI no cadastro do usuário <br> EU_17 - Cadastro de Famílias  <br> EU_20 - Cadastro de Agricultores Familiares | Média <br> Alta <br> Alta <br> Alta     |

<center>
    Autor(es): 
    <a href="https://github.com/RA-Salles" target="_blank">Ryan Salles</a>
</center>

### Épico 2: Informação

O Épico 2 trata de aspectos de obtenção de informação por meio do aplicativo, como informações sobre benefícios, status de uso e eligibilidade e ajuda na operação.
Esse Épico é apresentado por meio da tabela 4.

<center>
    <b>Tabela 4: </b> Épico 2 - Informação.
</center>

| Feature                           | Estórias                                                                           | Prioridade                             |
| :-----:                           | :---------------------:                                                            | :------------------------------------: |
| FT_03 - Atualização de Dados      | EU_02 - Alteração de dados cadastrais  <br> EU_05 - Pré-cadastrar família  <br> EU_12 - Atualização de dados <br> EU_33 - Atualização dos Dados Familiares <br> EU_22 - Correção de Inconsistências | Média <br> Média <br> Alta <br> Alta <br> Alta |
| FT_04 - Obtenção de informação    | EU_01 - Filtrar informações sobre benefícios socias <br> EU_03 - Enviar notificações <br> EU_10 - Consulta de benefícios <br> EU_14 - Acesso a conteúdos informativos sobre microempreendedorismo <br> EU_23 - Localizar Postos de Atendimento <br> EU_24 - Notificação de Pendências ou Atualizações  <br> EU_27 - Chat de atendimento <br> EU_36 - Conteúdo MEI Personalizado por Setor e Região | Média<br> Média<br> Alta<br> Média<br> Média<br> Alta<br> Alta<br> Alta                                       |
| FT_05 - Ajuda                     | EU_15 - Chat de Atendimento <br> EU_26 - Chatbot  <br> EU_27 - Chat de atendimento  <br> EU_28 - Tutoriais Interativos  <br> EU_35 - Suporte com Vídeos Explicativos | Média <br>Baixa <br>Alta <br>Média |

<center>
    Autor(es): 
    <a href="https://github.com/RA-Salles" target="_blank">Ryan Salles</a>
</center>

### Épico 3: Requisição
O Épico 3 trata de aspectos de requisições do usuário ao sistema e disponibilização de serviços pelo aplicativo, automatizando funcionalidades que exigiriam 
uma visita pessoal a um CRAS ou outro posto de atendimento. Esse Épico é apresentado por meio da tabela 5.

| Feature              | Estórias                                                                                                         | Prioridade                        |
|----------------------------------------------------|------------------------------------------------------------------------------------------------------------------|-----------------------------------|
| FT_05 - Formulários  | EU_16 - Agendamento no CRAS <br> EU_17 - Cadastro de Famílias <br> EU_18 - Cadastro de Pessoas <br> EU_19 - Cadastro de Domicílios <br> EU_32 - Coleta de Dados via Formulários <br> EU_33 - Atualização de Dados Familiares | Alta <br> Alta <br> Alta <br> Média <br> Alta <br> Alta |

<center>
    Autor(es): 
    <a href="https://github.com/Gabrielfcoelho" target="_blank">Gabriel Flores</a>
</center>

### Épico 4: Customização
O épico 4 organiza estórias e funcionalidades relacionadas à customização do funcionamento do aplicativo para permitir uma maior qualidade de uso. Esse épico é apresentado por meio da tabela 6.

| Feature                | Estórias                                                                                      | Prioridade                |
|------------------------|-----------------------------------------------------------------------------------------------|---------------------------|
| FT_06 - Personalização | EU_07 - Possibilidade de outros idiomas <br> EU_08 - Modo escuro <br> EU_31 - Notificações personalizadas | Baixa <br> Média <br> Baixa |

<center>
    Autor(es): 
    <a href="https://github.com/Gabrielfcoelho" target="_blank">Gabriel Flores</a>
</center>

### Épico 5: Acessibilidade
O épico 5 trata de aspectos de acessibilidade do aplicativo. 
Esse épico é apresentado por meio da tabela 7.

| Feature | Estórias                 | Prioridade                             |
| :-----: | :---------------------: | :------------------------------------: |
| FT_07   | EU_29 - Assistência por voz | Alta |

<center>
    Autor(es): 
    <a href="https://github.com/RA-Salles" target="_blank">Ryan Salles</a>
</center>

### Épico 6: Integração
O Épico 6 agrupa estórias relacionadas a integração do aplicativo com demais sistemas para permitir intercomunicação dos sistemas, permitindo ao aplicativo comunicar com mais de um sistema e repassar informações a outros sistemas senão o principal.
Esse épico é apresentado por meio da tabela 8.

| Feature | Estórias                 | Prioridade                             |
| :-----: | :---------------------: | :------------------------------------: |
| FT_08 - Integração com Sistemas     | EU_37 - Integração com Sistemas MEI <br> EU_21 - Processamento de Dados   | Alta <br> Alta |

<center>
    Autor(es): 
    <a href="https://github.com/RA-Salles" target="_blank">Ryan Salles</a>
</center>

## Referências Bibliográficas

> JAMES, Michael; WALTER, Luke. SCRUM REFERENCE CARD. Disponível em: <https://aprender3.unb.br/pluginfile.php/3096147/mod_resource/content/1/RE%20-%20Aula%2015%20-%20Materiais.zip?forcedownload=1>. Acesso em: 01/06/2025

<center>
<b>Figura 1:</b> Exemplo de backlog
</center>

![exemplo_backlog](../../assets/modelagem/backlog/scrumrefcard.png)

<center>
<b>Fonte: </b> JAMES e WALTER (2017)
</center>



## Histórico de Versão

| Versão  | Data       | Descrição                                           | Autor                                               | Revisor                                              |
| :-----: | :--------: | :-------------------------------------------------: | :-----------------------------------------:         | :-----------------------------------------:          |
| 1.0     | 31/05/2025 | Criação do documento e inserção de informações base | [Ryan Salles](https://github.com/RA-Salles)         | [Gabriel Flores](https://github.com/Gabrielfcoelho)  |
| 1.1     | 01/06/2025 | Elaboração das tabelas dos épicos 3 e 4             | [Gabriel Flores](https://github.com/Gabrielfcoelho) | [Ryan Salles](https://github.com/RA-Salles)          |
| 1.2     | 08/06/2025 | Alocando EU_21 na FT_08 e EU_22 na FT_03            | [Ryan Salles](https://github.com/RA-Salles)         | [João Pedro](https://github.com/johnaopedro)         |
| 1.2     | 04/07/2025 | Arrumando link errado            | [João Igor](https://github.com/JoaoPC10)         | [Gabriel Flores](https://github.com/Gabrielfcoelho)         |