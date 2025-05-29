# Documento de Histórias de Usuário

REQUISITOS JA USADOS: 1,2,3, 4, 5, 6, 7, 11, 12, 20, 22, 24, 26, 27, 29, 30, 25,38, 39

## Funções dos autores

| Nome                 | Função                                                            | 
|----------------------|----------------------------------------------------------------   |
|[João Pedro Costa](https://github.com/johnaopedro)|Criação do documento; Adaptação do template das historias no md; Adição das histórias de usuário de 19 a 25; Adição das referências| 
| [João Igor](https://github.com/JoaoPC10)|Criação das Histórias de Usuário: 3, 4, 5, 6, 7 e 9|
|[Julia Gabriela](https://github.com/JuliaGabP)|Revisão geral; Criação de 6 histórias de usuário| 
<center>
    Autor(es): 
    <a href="https://github.com/johnaopedro" target="_blank">João Pedro Costa</a>
</center>

## 1. Introdução

Este documento tem como finalidade apresentar as Histórias de Usuário (User Stories) desenvolvidas para o sistema, seguindo as diretrizes estabelecidas pela Coordenação Geral de Tecnologia da Informação (CGTI). As histórias de usuário são uma técnica ágil utilizada para capturar requisitos de software de forma simples e centrada no usuário, descrevendo funcionalidades do ponto de vista de quem irá utilizá-las.

O presente documento serve como base para a validação das funcionalidades do sistema, garantindo que as necessidades dos usuários sejam atendidas de forma eficaz e que os critérios de aceite sejam claramente definidos.

## 2. Metodologia

A elaboração das histórias de usuário seguiu as seguintes diretrizes metodológicas:

- Linguagem do usuário: Utilização de terminologia familiar aos usuários finais, evitando jargões técnicos
- Estrutura direta: Emprego de ordem direta nas frases para maior clareza
- Objetividade: Evitar redundâncias e frases negativas no texto
- Colaboração: Desenvolvimento conjunto com o Product Owner e desenvolvedores
- Critérios mensuráveis: Definição de critérios de aceite claros e testáveis

## 3. Objetivo

O objetivo deste documento é:

- Documentar de forma estruturada as necessidades dos usuários do sistema
- Estabelecer critérios claros de aceite para cada funcionalidade
- Facilitar a comunicação entre equipes de desenvolvimento e stakeholders
- Garantir rastreabilidade dos requisitos ao longo do ciclo de desenvolvimento
- Padronizar a especificação de funcionalidades seguindo boas práticas ágeis

## 4. Tabela de Participantes

| Nome | Papel | Responsabilidade | Nome |
|------|-------|------------------|---------|
| [Nome do Product Owner] | Product Owner | Definição e priorização das histórias de usuário | [Nome] |
| [Nome do Gestor de Negócio] | Gestor de Negócio | Levantamento de requisitos e validação | [Nome] |
| [Nome do Analista] | Analista de Sistemas | Especificação técnica e critérios de aceite | [Nome] |
| [Nome do Designer] | Designer UX/UI | Criação de protótipos e interfaces | [Nome] |
| [Nome do Scrum Master] | Scrum Master | Facilitação do processo e remoção de impedimentos | [Nome] |
| [Nome do Tech Lead] | Líder Técnico | Orientação técnica e arquitetura | [Nome] |

## 5. Modelo de História de Usuário

| Campo | Descrição | Obrigatório |
|-------|-----------|-------------|
| **ID** | Identificador único da história (formato: EU_XXX) | Sim |
| **Título** | Nome descritivo da funcionalidade | Sim |
| **Objetivo** | Descrição clara do propósito da história do ponto de vista do usuário | Sim |
| **Perfil(s)** | Usuários que utilizarão a funcionalidade | Sim |
| **Critérios de Aceite** | - xxx - xxx| Sim |
| **Prioridade** | Alta, Média ou Baixa | Sim |
| **Rastreabilidade** | Rastreabilidade do requisito |
| **Implementado** | Se esta ou não |

## 6. Histórias de Usuário

**Autor**: [João Igor](https://github.com/JoaoPC10)
### EU_01 – Filtrar informações sobre benefícios socias

| Campo | Descrição | 
|-------|-----------|
| **ID** | EU_01 | 
| **Título** | Filtrar informações sobre benefícios socias | 
| **Objetivo** | Eu como usuário gostaria de filtrar os serviços prestados, auxiliando minha busca | 
| **Perfil(s)** | Pessoas que desejam se cadastrar ou já são cadastradas no CadÚnico|
| **Critérios de Aceite** | [CN07](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/modelagem/cenarios/) |

---
**Autor**: [João Igor](https://github.com/JoaoPC10)
### EU_02 – Alteração de Dados Cadastrais

| Campo | Descrição | 
|-------|-----------|
| **ID** | EU_02 | 
| **Título** | Alteração de Dados Cadastrais | 
| **Objetivo** | Eu como usuário gostaria de alterar meus dados pessoais durante o uso do aplicativo | 
| **Perfil(s)** | Pessoas cadastradas no CadÚnico|
| **Critérios de Aceite** | [CN02](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/modelagem/cenarios/) |

---
**Autor**: [João Igor](https://github.com/JoaoPC10)
### EU_03 – Realizar Cadastro no Aplicativo

| Campo | Descrição | 
|-------|-----------|
| **ID** | EU_03 | 
| **Título** | Realizar Cadastro no Aplicativo | 
| **Objetivo** | Eu como usuário gostaria de me cadastrar na plaforma sem a necessidade da validação presencial | 
| **Perfil(s)** | Pessoas que desejam se cadastrar no CadÚnico|
| **Critérios de Aceite** | [CN03](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/modelagem/cenarios/) |

---
**Autor**: [João Igor](https://github.com/JoaoPC10)
### EU_04 – Conferir Informações sobre Benefícios

| Campo | Descrição | 
|-------|-----------|
| **ID** | EU_04 | 
| **Título** | Conferir Informações sobre Benefícios | 
| **Objetivo** |Eu como usuário gostaria de consiguir visualizar os benefícios prestados pelo governo | 
| **Perfil(s)** | Pessoas que desejam se cadastrar ou já são cadastradas no CadÚnico|
| **Critérios de Aceite** | [CN04](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/modelagem/cenarios/) |

---
**Autor**: [João Igor](https://github.com/JoaoPC10)
### EU_05 – Verificar Postos de Atendimento

| Campo | Descrição | 
|-------|-----------|
| **ID** | EU_05 | 
| **Título** | Verificar Postos de Atendimento | 
| **Objetivo** | Eu como usuário gostaria de visualizar o local, dia e horário em que os postos de atendimento estão funcionando, para poder ser atendido pessoalmente | 
| **Perfil(s)** | Pessoas que já são cadastradas no CadÚnico|
| **Critérios de Aceite** | [CN05](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/modelagem/cenarios/) |

---

**Autor**: [João Igor](https://github.com/JoaoPC10)
### EU_06 – Dispor de um Modo Escuro

| Campo | Descrição | 
|-------|-----------|
| **ID** | EU_06 | 
| **Título** | Dispor de um Modo Escuro| 
| **Objetivo** |Eu como usuário gostaria de dispor de um Modo Escuro, tornando-o melhor usável em ambientes escuros | 
| **Perfil(s)** | Pessoas que já são cadastradas no CadÚnico|
| **Critérios de Aceite** | [CN09](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/modelagem/cenarios/) |

---

### História EU_07 – Possibilidade de outros idiomas

**Autor**: [Julia Gabriela](https://github.com/JuliaGabP)

|Campo|Descrição|
|------|---------|
|**ID**|EU_07|
|**Título**|Possibilidade de outros idiomas|
|**Objetivo**|Eu, como usuário desejo poder acessar o aplicativo em outro idioma.|
|**Perfil(s)**|Usuários gerais do CadÚnico|
|**Critérios de Aceite**|- . Qualquer usuário deve ser capaz de alterar o idioma do aplicativo, de forma que ele fique conciso <br> Para mais detalhes cheque a introspecção: [IS16](../../modelagem/introspecção.md)|
|**Prioridade**|Baixa|
|**Rastreabilidade**|[RF39](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**|Não|
---

### História EU_08 – Modo escuro

**Autor**: [Julia Gabriela](https://github.com/JuliaGabP)

|Campo|Descrição|
|------|---------|
|**ID**|EU_08|
|**Título**|Modo escuro|
|**Objetivo**|Eu, como usuário desejo poder acessar o aplicativo na forma escura.|
|**Perfil(s)**|Usuários gerais do CadÚnico|
|**Critérios de Aceite**|- . Qualquer usuário deve ser capaz de configurar para seu aplicativo ficar no modo escuro, de forma que o constraste de cores continue com qualidade <br> Para mais detalhes cheque a introspecção: [IS15](../../modelagem/introspecção.md)|
|**Prioridade**|Média|
|**Rastreabilidade**|[RF38](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**|Não|

---


### História EU_09– Visualização de informações cadastrais

**Autor**: [Julia Gabriela](https://github.com/JuliaGabP)

|Campo|Descrição|
|------|---------|
|**ID**|EU_09|
|**Título**|Visualização de informações cadastrais|
|**Objetivo**|Eu, como usuário desejo poder visualizar minhas informações cadastrais|
|**Perfil(s)**|Usuários cadastrados no CadÚnico|
|**Critérios de Aceite**|- . Qualquer usuário deve ser capaz de visualizar suas informações cadastrais <br> Para mais detalhes cheque a entrevista: [ENT2](../../modelagem/entrevista.md)|
|**Prioridade**|Alta|
|**Rastreabilidade**|[RF25](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**|Sim|

---

### História EU_10– Consulta de benefícios

**Autor**: [Julia Gabriela](https://github.com/JuliaGabP)

|Campo|Descrição|
|------|---------|
|**ID**|EU_10|
|**Título**|Consulta de benefícios|
|**Objetivo**|Eu, como usuário desejo consultar a situação do meu benefício|
|**Perfil(s)**|Usuários com benefícios no CadÚnico|
|**Critérios de Aceite**|- . Qualquer usuário deve ser capaz de visualizar as situações de seus benefícios. <br> Para mais detalhes cheque a entrevista: [ENT1](../../modelagem/entrevista.md)|
|**Prioridade**|Alta|
|**Rastreabilidade**|[RF24](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**|Sim|

---

### História EU_11– Emissão de comprovante de cadastro

**Autor**: [Julia Gabriela](https://github.com/JuliaGabP)

|Campo|Descrição|
|------|---------|
|**ID**|EU_11|
|**Título**|Emissão de comprovante de cadastro|
|**Objetivo**|Eu, como usuário desejo poder emitir um comprovante de cadastro no sistema|
|**Perfil(s)**|Usuários cadastrados no CadÚnico|
|**Critérios de Aceite**|- . Qualquer usuário cadastrado deve ser capaz de emitir um comprovante de cadastro no sistema. <br> Para mais detalhes cheque a introspecção: [IS9](../../modelagem/introspecção.md)|
|**Prioridade**|Média|
|**Rastreabilidade**|[RF22](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**|Sim|

---

### História EU_12– Atualização de dados

**Autor**: [Julia Gabriela](https://github.com/JuliaGabP)

|Campo|Descrição|
|------|---------|
|**ID**|EU_12|
|**Título**|Atualização de dados|
|**Objetivo**|Eu, como usuário desejo poder atualizar os meus dados no sistema|
|**Perfil(s)**|Usuários cadastrados no CadÚnico|
|**Critérios de Aceite**|- . Qualquer usuário cadastrado deve ser capaz atualizar seus dados pelo sistema. <br> Para mais detalhes cheque a introspecção: [IS7](../../modelagem/introspecção.md)|
|**Prioridade**|Alta|
|**Rastreabilidade**|[RF20](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**|Sim|

---

### História EU_13 – Cadastro MEI

**Autor**: [João Pedro Costa](https://github.com/johnaopedro)

|Campo|Descrição|
|------|---------|
|**ID**|EU_13|
|**Título**|Registro da condição de MEI no cadastro do usuário|
|**Objetivo**|Eu, como usuário em processo de cadastro no CadÚnico, quero informar que sou Microempreendedor Individual para receber conteúdos e serviços direcionados.|
|**Perfil(s)**|Usuário em processo de cadastro no CadÚnico|
|**Critérios de Aceite**|- Exibir opção "Sou MEI" durante o cadastro.<br>- Permitir marcação da opção.<br>- Armazenar a informação no perfil.<br>- Caso não marque, seguir fluxo normalmente.<br>- Se selecionar "Sou MEI" sem CNPJ válido, solicitar verificação adicional. <br> Para mais detalhes cheque o cenário: [CN10](../../modelagem/cenarios.md)|
|**Prioridade**|Alta|
|**Rastreabilidade**|[RF11](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**|Não|

---

### História EU_14 – Acesso a conteúdos informativos sobre MEI

**Autor**: [João Pedro Costa](https://github.com/johnaopedro)

|Campo|Descrição|
|------|---------|
|**ID**|EU_14|
|**Título**|Acesso a conteúdos informativos sobre microempreendedorismo|
|**Objetivo**|Eu, como usuário MEI autenticado no CadÚnico, quero acessar informações sobre obrigações, direitos e oportunidades para me informar melhor.|
|**Perfil(s)**|Usuário MEI autenticado no CadÚnico|
|**Critérios de Aceite**|- Permitir acesso à seção “MEI”.<br>- Exibir conteúdos organizados por temas.<br>- Navegar entre temas.<br>- Exibir aviso para usuários não MEI.<br>- Informar necessidade de conexão quando offline.<br> Para mais detalhes cheque o cenário: [CN11](../../modelagem/cenarios.md)|
|**Prioridade**|Média|
|**Rastreabilidade**|[RF12](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**|Não|

---

### História EU_15 – Chat de Atendimento

**Autor**: [João Pedro Costa](https://github.com/johnaopedro)

|Campo|Descrição|
|------|---------|
|**ID**|EU_15|
|**Título**|Chat de Atendimento|
|**Objetivo**|Eu, como usuário, quero utilizar um chat de atendimento para receber suporte rápido e tirar dúvidas.|
|**Perfil(s)**|Usuário|
|**Critérios de Aceite**|- O sistema deve disponibilizar um chat para atendimento.<br>- Permitir troca de mensagens em tempo real.<br>- Notificar usuário sobre respostas.<br>- Registrar histórico das conversas.<br>- Disponível em todas as telas do aplicativo.<br> Para mais detalhes cheque o cenário: [CN08](../../modelagem/cenarios.md)|
|**Prioridade**|Média|
|**Rastreabilidade**|[RF26](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**|Não|

---

### História EU_16 – Agendamento no CRAS

**Autor**: [João Pedro Costa](https://github.com/johnaopedro)

|Campo|Descrição|
|------|---------|
|**ID**|EU_16|
|**Título**|Agendamento no CRAS|
|**Objetivo**|Eu, como usuário do CadÚnico, quero realizar o agendamento de atendimento no CRAS para evitar filas e facilitar o processo.|
|**Perfil(s)**|Usuário do CadÚnico|
|**Critérios de Aceite**|- O usuário acessa a opção "Agendamento de Atendimento" dentro do CadÚnico.<br>- O sistema exibe calendário com horários disponíveis.<br>- Usuário escolhe data, horário e local.<br>- Sistema verifica disponibilidade no CRAS.<br>- Confirma agendamento e envia notificação.<br>- Atualiza status do agendamento no perfil do usuário.<br>- Caso horário indisponível, sistema sugere outras opções.<br>- Se sistema do CRAS estiver fora do ar, armazena tentativa para nova sincronização.<br> Para mais detalhes cheque o cenário: [CN14](../../modelagem/cenarios.md)|
|**Prioridade**|Alta|
|**Rastreabilidade**|[RF30](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**|Não|

---

### História EU_17 – Cadastro de Famílias

**Autor**: [João Pedro Costa](https://github.com/johnaopedro)

|Campo|Descrição|
|------|---------|
|**ID**|EU_17|
|**Título**|Cadastro de Famílias|
|**Objetivo**|Eu, como usuário do CadÚnico, quero cadastrar famílias com renda mensal de até meio salário mínimo por pessoa ou vinculadas a programas sociais para garantir o acesso aos benefícios.|
|**Perfil(s)**|Usuário do CadÚnico|
|**Critérios de Aceite**|- O sistema permite cadastro de famílias com renda mensal até meio salário mínimo por pessoa.<br>- Permite cadastro vinculado a programas sociais.<br>- Valida dados obrigatórios de renda e vínculos.<br>- Confirma registro com mensagem de sucesso.<br>- Possibilita consulta e edição posterior do cadastro.|
|**Prioridade**|Alta|
|**Rastreabilidade**|[RF01](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**|Não|

---

### História EU_18 – Cadastro de Pessoas

**Autor**: [João Pedro Costa](https://github.com/johnaopedro)

|Campo|Descrição|
|------|---------|
|**ID**|EU_18|
| **Título**          | Cadastro de Pessoas  |
| **Objetivo**        | Eu, como usuário do CadÚnico, quero registrar informações pessoais, como dados de identificação, documentação, frequência escolar e grau de instrução para compor corretamente o cadastro familiar. |
| **Perfil(s)**       | Usuário do CadÚnico  |
| **Critérios de Aceite** | - Permitir registro dos dados pessoais essenciais.<br>- Validar campos obrigatórios.<br>- Garantir integridade dos dados cadastrados.<br>- Confirmar o cadastro com mensagem de sucesso.<br>- Permitir consulta e edição dos dados pessoais.|
| **Prioridade**      | Alta  |
|**Rastreabilidade**|[RF02](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**|Não|

---

### História EU_19 – Cadastro de Domicílios

**Autor**: [João Pedro Costa](https://github.com/johnaopedro)

|Campo|Descrição|
|------|---------|
|**ID**|EU_19|
|**Título**|Cadastro de Domicílios|
|**Objetivo**|Eu, como usuário, quero registrar características do meu domicílio para que meu perfil tenha informações completas sobre minha residência.|
|**Perfil(s)**|Usuário do CadÚnico|
|**Critérios de Aceite**|- O sistema deve permitir o registro do tipo de construção.<br>- Registrar informações sobre abastecimento de água.<br>- Registrar tipo de iluminação.<br>- Registrar escoamento sanitário.<br>- Validar os dados informados e salvar no perfil.<br> Para mais detalhes cheque o cenário: [CN](../../modelagem/cenarios.md)|
|**Prioridade**|Média|
|**Rastreabilidade**|[RF03](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**|Não|

## Referências

> COORDENAÇÃO GERAL DE TECNOLOGIA DA INFORMAÇÃO - CGTI. EU_xxx_Titulo_da_Estoria_de_Usuario: template para especificação de histórias de usuário. [S.l.]: CGTI, 2018. 5 p. Disponível em: <a href="../../../assets/modelagem/US/template_historia_de_usuario.pdf" target="_blank">História de Usuário</a>. Acesso em: 22 de maio 2025.

> PRESSMAN, Roger S.; MAXIM, Bruce R.. Engenharia de software: uma abordagem profissional. 8 Porto Alegre: AMGH, 2016, p. 73. Acesso em: 28 de maio 2025.

## Histórico de Versão

| Versão |    Data    |        Descrição         |                   Autor                    |                   Revisor                   |
| :----: | :--------: | :----------------------: | :----------------------------------------: | :-----------------------------------------: |
|  1.0   | 22/05/2025 |   Criação do Documento   | [João Pedro Costa](https://github.com/johnaopedro) | [Julia Gabriela](https://github.com/JuliaGabP) |
|  1.1   | 22/05/2025 | Adaptação do template das histórias de usuário e adição de referências   | [João Pedro Costa](https://github.com/johnaopedro) | [Julia Gabriela](https://github.com/JuliaGabP) |
|  1.2   | 26/05/2025 | Adição das Histórias de Usuário  | [João Igor](https://github.com/JoaoPC10) | [Julia Gabriela](https://github.com/JuliaGabP) |
|  1.3   | 28/05/2025 | Adição de Historias de Usuário de 19 a 25 | [João Pedro Costa](https://github.com/johnaopedro) | [Julia Gabriela](https://github.com/JuliaGabP) |
|  1.4   | 29/05/2025 | Adição de 6 Histórias de Usuário, correção dos IDs | [Julia Gabriela](https://github.com/JuliaGabP) | [João Pedro Costa](https://github.com/johnaopedro) |
