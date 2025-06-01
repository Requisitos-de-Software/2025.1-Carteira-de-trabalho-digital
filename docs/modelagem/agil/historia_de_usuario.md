# Documento de Estórias de Usuário

## Funções dos autores

| Nome                                                | Função                                                                                                                                      | 
|-----------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| [João Pedro Costa](https://github.com/johnaopedro)  | Criação do documento; Adaptação do template das historias no md; Adição das histórias de usuário de 19 a 25; Adição das referências         | 
| [João Igor](https://github.com/JoaoPC10)            | Criação das Histórias de Usuário: 3, 4, 5, 6, 7 e 9                                                                                         |
| [Julia Gabriela](https://github.com/JuliaGabP)      | Revisão geral; Criação de 6 histórias de usuário                                                                                            | 
| [Gabriel Flores](https://github.com/Gabrielfcoelho) | Criação das histórias de usuário 20 até a 25                                                                                                |
| [Ryan Salles](https://github.com/RA-Salles)         | Elaboração das histórias de usuário 26 a 31, Entrevista com PO para validação, Elaboração Inicial da Tabela X para rastreabilidade, Revisão |                                                                                        |
| [Amanda Cruz](https://github.com/mandicrz)         | Criação das Histórias de Usuário 32, 33, 34, 35, 36 e 37                       |                                                                                          


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

As estórias foram validadas com a presença de um usuário, que ajudou a definir as prioridades e 
necessidade de implementação no aplicativo. Os participantes da entrevista são apresentados por meio
da Tabela 1.

<center>
<b>Tabela 1:</b> Participantes da reunião 
</center>

| Participante      | Função                          |
| :--------:        | :-----------------------------: |
| Davi G. A. Pierre | Usuário/ Project Owner          |
| Julia Paulino     | Desenvolvedor/Secretário        |
| João Pedro Costa  | Desenvolvedora                  |
| Ryan Salles       | Desenvolvedor/Entrevistador     |

<center>
<b>Autor(es):</b> 
</center>

A reunião foi realizada e gravada via **Microsoft Teams**.

<iframe width="560" height="315" src="https://www.youtube.com/embed/mSUJdqnPAb4?si=2k0uWOnWp9peWcgL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

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

## 5. Modelo de Estória de Usuário

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

## 6. Estórias de Usuário

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

---

### História EU_20 – Cadastro de Agricultores Familiares

**Autor**: [Gabriel Flores](https://github.com/Gabrielfcoelho)

|Campo|Descrição|
|------|---------|
|**ID**|EU_20|
|**Título**|Cadastro de Agricultores Familiares|
|**Objetivo**|Eu, como agricultor familiar, desejo cadastrar minhas informações no sistema para acessar benefícios específicos e garantir minha inclusão em programas sociais.|
|**Perfil(s)**|Agricultores familiares|
|**Critérios de Aceite**|- O sistema deve permitir o cadastro de agricultores familiares.<br>- Deve validar os dados obrigatórios do agricultor.<br>- O usuário deve receber confirmação do cadastro.|
|**Prioridade**|Alta|
|**Rastreabilidade**|[RF04](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**|Sim|

---

### História EU_21 – Processamento de Dados

**Autor**: [Gabriel Flores](https://github.com/Gabrielfcoelho)

|Campo|Descrição|
|------|---------|
|**ID**|EU_21|
|**Título**|Processamento de Dados|
|**Objetivo**|Eu, como usuário, desejo que meus dados sejam processados corretamente para garantir a atualização e integridade das informações no sistema.|
|**Perfil(s)**|Usuários do CadÚnico|
|**Critérios de Aceite**|- O sistema deve processar os dados inseridos de forma automática.<br>- Garantir a integridade e atualização das informações.<br>- Notificar o usuário em caso de erro no processamento.|
|**Prioridade**|Alta|
|**Rastreabilidade**|[RF06](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**|Sim|

---

### História EU_22 – Correção de Inconsistências

**Autor**: [Gabriel Flores](https://github.com/Gabrielfcoelho)

|Campo|Descrição|
|------|---------|
|**ID**|EU_22|
|**Título**|Correção de Inconsistências|
|**Objetivo**|Eu, como usuário, desejo corrigir inconsistências nos meus dados para garantir que meu cadastro esteja correto e atualizado.|
|**Perfil(s)**|Usuários do CadÚnico|
|**Critérios de Aceite**|- O sistema deve identificar e informar inconsistências nos dados.<br>- Permitir ao usuário corrigir as informações.<br>- Confirmar a correção e atualizar o cadastro.|
|**Prioridade**|Alta|
|**Rastreabilidade**|[RF07](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**|Sim|

---

### História EU_23 – Localizar Postos de Atendimento

**Autor**: [Gabriel Flores](https://github.com/Gabrielfcoelho)

|Campo|Descrição|
|------|---------|
|**ID**|EU_23|
|**Título**|Localizar Postos de Atendimento|
|**Objetivo**|Eu, como usuário, desejo localizar os postos de atendimento mais próximos para facilitar meu acesso aos serviços do CadÚnico.|
|**Perfil(s)**|Usuários do CadÚnico|
|**Critérios de Aceite**|- O sistema deve exibir postos de atendimento próximos com base na localização do usuário.<br>- Permitir busca por município ou endereço.<br>- Exibir informações de contato e horários de funcionamento.|
|**Prioridade**|Média|
|**Rastreabilidade**|[RF16](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**|Sim|

---

### História EU_24 – Notificação de Pendências ou Atualizações

**Autor**: [Gabriel Flores](https://github.com/Gabrielfcoelho)

|Campo|Descrição|
|------|---------|
|**ID**|EU_24|
|**Título**|Notificação de Pendências ou Atualizações|
|**Objetivo**|Eu, como usuário, desejo ser notificado sobre pendências ou atualizações no meu cadastro para manter meus dados sempre regulares.|
|**Perfil(s)**|Usuários do CadÚnico|
|**Critérios de Aceite**|- O sistema deve notificar o usuário sobre pendências ou atualizações necessárias.<br>- Permitir visualização detalhada da pendência.<br>- Orientar o usuário sobre como regularizar a situação.|
|**Prioridade**|Alta|
|**Rastreabilidade**|[RF27](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**|Não|

---

### História EU_25 – Upload de Documentos

**Autor**: [Gabriel Flores](https://github.com/Gabrielfcoelho)

|Campo|Descrição|
|------|---------|
|**ID**|EU_25|
|**Título**|Upload de Documentos|
|**Objetivo**|Eu, como usuário, desejo enviar documentos digitalizados pelo aplicativo para complementar ou atualizar meu cadastro sem precisar ir presencialmente ao posto de atendimento.|
|**Perfil(s)**|Usuários do CadÚnico|
|**Critérios de Aceite**|- O sistema deve permitir upload de documentos em formatos aceitos.<br>- Validar tipo e tamanho dos arquivos.<br>- Confirmar o envio e associar ao cadastro do usuário.|
|**Prioridade**|Alta|
|**Rastreabilidade**|[RF29](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**|Não|

---

### História EU_26 - Chatbot

**Autor**: [Ryan Salles](https://github.com/RA-Salles)

|Campo                  |Descrição                                                                                                                                                                                |
|-----------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**ID**                 | EU_26                                                                                                                                                                                   |
|**Título**             | Chatbot                                                                                                                                                                                 |
|**Objetivo**           | "Eu, como usuário, gostaria de acessar um chatbot para responder dúvidas frequentes de forma rápida e efetiva"                                                                          |
|**Perfil(s)**          | Usuário do CadÚnicov                                                                                                                                         |
|**Critérios de Aceite**| - O usuário consegue acessar o sistema <br> - O chatbot é capaz de entender perguntas em linguagem natural<br> - O chatbot é capaz de responder as dúvidas mais frequentes dos usuários |
|**Prioridade**         | A DEFINIR                                                                                                                                                                               |
|**Rastreabilidade**    |[RF26](../../elicitacao/requisitos_elicitados.md)                                                                                                                                        |
|**Implementado**       | Não                                                                                                                                                                                     |

---

### História EU_27 - Chat de Atendimento

**Autor**: [Ryan Salles](https://github.com/RA-Salles)

|Campo|Descrição|
|------|---------|
|**ID**                 | EU_27                                                                                                                                                                                                                        |
|**Título**             | Chat de atendimento                                                                                                                                                                                                          |
|**Objetivo**           | "Eu, como usuário, gostaria de uma linha de acesso direto a um atendente cuja experiência e capacidades técnicas para resolver rapidamente problemas, requisições, dúvidas e dificuldades sem a necessidade de ir a um CRAS" |
|**Perfil(s)**          | Usuário do CádÚnico                                                                                                                                                                                                          |
|**Critérios de Aceite**| - O usuário consegue acessar o sistema <br> - O atendente é capaz de receber e enviar mensagens em tempo real <br> - O usuário é capaz de receber e enviar mensagens em tempo real                                           |
|**Prioridade**         | A DEFINIR                                                                                                                                                                                                                    |
|**Rastreabilidade**    |[RF34](../../elicitacao/requisitos_elicitados.md)                                                                                                                                                                             |
|**Implementado**       | Não                                                                                                                                                                                                                          |
---

### História EU_28 - Tutoriais Interativos

**Autor**: [Ryan Salles](https://github.com/RA-Salles)

|Campo|Descrição|
|------|---------|
|**ID**                 |EU_28                                                                                                                                                                                                                                  |
|**Título**             | Tutoriais Interativos                                                                                                                                                                                                                 |
|**Objetivo**           | "Eu, como usuário novo, gostaria de ser guiado pelo aplicativo de forma automática na forma de um tutorial interativo para conhecer as funções e operações disponíveis no aplicativo e facilitar meu aprendizado e uso da ferramenta" | 
|**Perfil(s)**          | Usuário novo do CadÚnico                                                                                                                                                                                                              |
|**Critérios de Aceite**| - O tutorial é oferecido ao usuário quando ele entra no aplicativo pela primeira vez <br> - O tutorial explica e exemplifica o uso das principais funcionalidades e operações do aplicativo                                           |
|**Prioridade**         | A DEFINIR                                                                                                                                                                                                                             |
|**Rastreabilidade**    |[RF35](../../elicitacao/requisitos_elicitados.md)                                                                                                                                                                                      |
|**Implementado**       | Não                                                                                                                                                                                                                                   |

---

### História EU_29 - Assistência por voz

**Autor**: [Ryan Salles](https://github.com/RA-Salles)

|Campo|Descrição|
|------|---------|
|**ID**                 | EU_29 |
|**Título**             | Assistência por voz |
|**Objetivo**           | "Eu, como usuário, gostaria de ser capaz de controlar o aplicativo por voz para que possa acessar as funcionalidades sem a necessidade de ver a tela" |
|**Perfil(s)**          | Usuário com baixa ou nenhuma visibilidade|
|**Critérios de Aceite**| - O aplicativo deve ser capaz de reconhecer a voz do usuário <br> - O aplicativo deve ser capaz de realizar operações a partir de comandos por voz <br> - O aplicativo, mediante boa pronúncia e um microfone funcionando segundo especificação do fabricante do dispositivo, possuir taxa de acerto do comando pronunciado de no mínimo 95% |
|**Prioridade**         | Alta |
|**Rastreabilidade**    |[RF37](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**       | Não |

---

### História EU_30 - Filtragem de Benefícios

**Autor**: [Ryan Salles](https://github.com/RA-Salles)

|Campo|Descrição|
|------|---------|
|**ID**                 |EU_30|
|**Título**             | |
|**Objetivo**           ||
|**Perfil(s)**          ||
|**Critérios de Aceite**||
|**Prioridade**         ||
|**Rastreabilidade**    |[RF23](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**       | Não |

---

### História EU_31 - Notificações Personalizadas

**Autor**: [Ryan Salles](https://github.com/RA-Salles)

|Campo|Descrição|
|------|---------|
|**ID**                 | EU_31 |
|**Título**             | Notificações personalizadas |
|**Objetivo**           | "Eu, como usuário, gostaria de receber notificações personalizadas segundo meu perfil de usuário para me manter atualizado sobre minha situação específica "|
|**Perfil(s)**          | Usuário |
|**Critérios de Aceite**| - O aplicativo deve ser capaz de enviar notificações <br> - O aplicativo deve possuir forma de configuração de notificações <br> - O sistema de notificação deve ser capaz de ser desativado|
|**Prioridade**         | Baixa |
|**Rastreabilidade**    |[RF09](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**       | Não |

---

### História EU_32 - Coleta de Dados via Formulários

<center>
    <b>Figura X:</b> EU_32 - Coleta de Dados via Formulários
</center>

|Campo|Descrição|
|------|---------|
|**ID**                 | EU_32 |
|**Título**             | Coleta de Dados via Formulários |
|**Objetivo**           | "Eu, como Usuário, quero usar formulários no aplicativo para conseguir registrar facilmente todos os dados importantes sobre domicílios, famílias, pessoas, suas ligações com programas sociais e informações de quem vive na rua, para que o aplicativo tenha dados sempre corretos e atualizados." |
|**Perfil(s)**          | Usuário |
|**Critérios de Aceite**| - O aplicativo deve oferecer formulários principais e suplementares para o cadastro.<br>- O sistema deve permitir o registro completo de informações de domicílios, famílias e indivíduos. <br>- O sistema deve permitir o registro da vinculação a programas sociais e de dados específicos sobre pessoas em situação de rua. |
|**Prioridade**         | A definir |
|**Rastreabilidade**    |[RF10](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**       | Sim |

<center>
    <b>Autor(es):</b>
    <a href="https://github.com/mandicrz" target="_blank">Amanda Cruz</a>
</center>

---

### História EU_33 - Atualização dos Dados Familiares

<center>
    <b>Figura X:</b> EU_33 - Atualização dos Dados Familiares
</center>

|Campo|Descrição|
|------|---------|
|**ID**                 | EU_33 |
|**Título**             | Atualização dos Dados Familiares |
|**Objetivo**           | "Eu, como Usuário, quero poder atualizar facilmente os dados cadastrais da minha família para que estejam de acordo e possamos manter o nosso acesso a programas e benefícios sociais." |
|**Perfil(s)**          | Usuário responsável da família |
|**Critérios de Aceite**| - O sistema deve permitir a edição das informações pessoais dos membros da família.<br>- O sistema deve permitir a alteração dos dados de endereço e renda da família.<br>- O sistema deve salvar as modificações e confirmar que os dados da família foram atualizados. |
|**Prioridade**         | A definir |
|**Rastreabilidade**    |[RF05](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**       | Sim |

<center>
    <b>Autor(es):</b>
    <a href="https://github.com/mandicrz" target="_blank">Amanda Cruz</a>
</center>

---

### História EU_34 - Importação Automática de Dados do CNIS

<center>
    <b>Figura X:</b> EU_34 - Importação Automática de Dados do CNIS
</center>

|Campo|Descrição|
|------|---------|
|**ID**                 | EU_34 |
|**Título**             | Importação Automática de Dados do CNIS |
|**Objetivo**           | "Eu, como Usuário, quero que o sistema busque e importe automaticamente os dados de vínculos empregatícios e contribuições diretamente do CNIS, para que o processo de cadastro seja mais rápido, com informações mais precisas e menos sujeito a erros de digitação." |
|**Perfil(s)**          | Usuário |
|**Critérios de Aceite**| - O sistema deve ter a capacidade de se conectar ao CNIS para consultar dados de um cidadão (com as devidas autorizações). <br>- O sistema deve importar e exibir de forma clara para os dados retornados pelo CNIS. <br>- O sistema deve permitir que o usuário utilize os dados importados do CNIS para preencher ou validar as informações. | 
|**Prioridade**         | A definir |
|**Rastreabilidade**    |[RF18](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**       | Sim |

<center>
    <b>Autor(es):</b>
    <a href="https://github.com/mandicrz" target="_blank">Amanda Cruz</a>
</center>

---

### História EU_35 - Suporte com Vídeos Explicativos

<center>
    <b>Figura X:</b> EU_35 - Suporte com Vídeos Explicativos
</center>

|Campo|Descrição|
|------|---------|
|**ID**                 | EU_35 |
|**Título**             | Suporte com Vídeos Explicativos |
|**Objetivo**           | "Eu, como Usuário, quero poder assistir a vídeos dentro do aplicativo que expliquem as principais funcionalidades e processos, para que eu consiga entender melhor como usar o sistema e ganhar mais confiança." |
|**Perfil(s)**          | Usuário novo ou com dificuldades digitais |
|**Critérios de Aceite**| - O aplicativo deve possuir uma área ou links contextuais para acesso a vídeos explicativos. <br>- Os vídeos devem abordar o uso das funcionalidades mais importantes ou que geram mais dúvidas. <br>- Os vídeos devem ter linguagem simples, ser curtos e de fácil compreensão.|
|**Prioridade**         | A definir |
|**Rastreabilidade**    |[RF36](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**       | Não |

<center>
    <b>Autor(es):</b>
    <a href="https://github.com/mandicrz" target="_blank">Amanda Cruz</a>
</center>

---

### História EU_36 - Conteúdo MEI Personalizado por Setor e Região

<center>
    <b>Figura X:</b> EU_36 - Conteúdo MEI Personalizado por Setor e Região
</center>

|Campo|Descrição|
|------|---------|
|**ID**                 | EU_36 |
|**Título**             | Conteúdo MEI Personalizado por Setor e Região |
|**Objetivo**           | "Eu, como Usuário MEI, quero que os conteúdos e informações da seção MEI do sistema sejam adaptados ao meu setor de atividade e à minha região, para que eu possa encontrar facilmente orientações e recursos que sejam verdadeiramente relevantes para o meu negócio." |
|**Perfil(s)**          | Usuário MEI |
|**Critérios de Aceite**| - O sistema deve identificar o setor de atuação e a região do Usuário MEI a partir dos seus dados cadastrais.<br>- O sistema deve exibir conteúdos na seção MEI que sejam especificamente relevantes para o setor de atuação e região geográfica do usuário." | 
|**Prioridade**         | A definir |
|**Rastreabilidade**    |[RF13](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**       | Não |

<center>
    <b>Autor(es):</b>
    <a href="https://github.com/mandicrz" target="_blank">Amanda Cruz</a>
</center>

---

### História EU_37 - Integração com Sistemas MEI

<center>
    <b>Figura X:</b> EU_37 - Integração com Sistemas MEI
</center>

|Campo|Descrição|
|------|---------|
|**ID**                 | EU_37 |
|**Título**             | Integração com Sistemas MEI |
|**Objetivo**           | "Eu, como Usuário MEI, quero que o sistema possa trocar informações de forma segura e padronizada com outros sistemas relevantes para Microempreendedores Individuais, para simplificar meus processos, evitar redigitação e manter minhas informações consistentes entre as plataformas." |
|**Perfil(s)**          | Usuário MEI |
|**Critérios de Aceite**| - O sistema deve ser capaz de se comunicar com sistemas externos designados para MEIs. <br>- O sistema deve permitir o envio e/ou recebimento de dados específicos de MEIs de/para esses sistemas externos. <br>- A troca de dados com os sistemas MEI deve ser realizada de forma segura. | 
|**Prioridade**         | A definir |
|**Rastreabilidade**    |[RF40](../../elicitacao/requisitos_elicitados.md)|
|**Implementado**       | Não |

<center>
    <b>Autor(es):</b>
    <a href="https://github.com/mandicrz" target="_blank">Amanda Cruz</a>
</center>

---

## Rastreabilidade

A Tabela X apresenta a rastreabilidade geral das histórias de usuário para os requisitos elicitados e cenários utilizados para elaboração e compreensão dos critérios de aceitação.

<center>
    <b>Tabela X:</b> Rastreabilidade de relacionamento EU-REQ-CN
</center>

| Estória de Usuário  | Requisito | Cenário      |
| :-----------------: | :-------: | :-----:      |          
| **EU_01**           | RF23      | CN07         |
| **EU_02**           | RF20      | CN02         |
| **EU_03**           | RF02      | CN03         |
| EU_04               | RF24      | CN04         |
| **EU_05**           | RF16      | CN05         |
| **EU_06**           | RF38      | CN09         |
| EU_07               | RF39      | -            |
| **EU_08**           | RF38      | CN09         |
| EU_09               | RF25      | -            |
| EU_10               | RF24      | CN01         |
| EU_11               | RF22      | -            |
| **EU_12**           | RF20      | -            |
| EU_13               | RF11      | CN13, CN10   |
| EU_14               | RF12      | CN11         |
| EU_15               | RF26      | CN08         |
| EU_16               | RF30      | CN14         |
| EU_17               | RF01      | -            |
| **EU_18**           | RF02      | CN03         |
| EU_19               | RF03      | -            |
| EU_20               | RF04      | -            |
| EU_21               | RF06      | CN06         |
| EU_22               | RF07      | -            |
| **EU_23**           | RF16      | CN05         |
| EU_24               | RF27      | -            |
| EU_25               | RF29      | CN16         |
| EU_26               | RF26      | CN08         |
| EU_27               | RF34      | -            |
| EU_28               | RF35      | CN15         |
| EU_29               | RF37      | -            |
| **EU_30**           | RF23      | CN07         |
| EU_31               | RF09      | -            |
| EU_32               | RF10      | -            |
| EU_33               | RF05      | -            |
| EU_34               | RF18      | -            |
| EU_35               | RF36      | -            |
| EU_36               | RF13      | CN12         |
| EU_37               | RF40      | CN13         |


UTILIZADAS: 01, 02, 03, 04, 05, 06, 07, 09, 10, 11, 12, 13, 16, 18, 20, 23, 24, 25, 26, 27, 29, 30, 34, 35, 36, 37, 38, 39, 40

DUPLICATAS:
- 01-30
- 02-12
- 03-18
- 05-23
- 06-08

MELHORAR: 
- 01 a 06 -> inserir criterios de aceite mais específicos, inserir prioridade.
- 07 a 12 -> inserir objetivo de realizar operação na estória, 

<center>
    <b>Autor(es):</b>
    <a href= "https://github.com/mandicrz" target="_blank"> Amanda Cruz </a>, <a href= "" target="_blank"> Julia Paulino </a>, <a href= "https://github.com/Gabrielfcoelho" target="_blank"> Gabriel Flores </a>, <a href= "https://github.com/johnaopedro" target="_blank"> João Pedro </a>, <a href= "https://github.com/JoaoPC10" target="_blank"> João Igor </a>, <a href= "https://github.com/RA-Salles" target="_blank"> Ryan Salles </a> 
</center>

## Referências

> COORDENAÇÃO GERAL DE TECNOLOGIA DA INFORMAÇÃO - CGTI. EU_xxx_Titulo_da_Estoria_de_Usuario: template para especificação de histórias de usuário. [S.l.]: CGTI, 2018. 5 p. Disponível em: <a href="../../../assets/modelagem/US/template_historia_de_usuario.pdf" target="_blank">História de Usuário</a>. Acesso em: 22 de maio 2025.

> PRESSMAN, Roger S.; MAXIM, Bruce R.. Engenharia de software: uma abordagem profissional. 8 Porto Alegre: AMGH, 2016, p. 73. Acesso em: 28 de maio 2025.

## Histórico de Versão

| Versão |    Data    |        Descrição                                                       |                   Autor                             |                   Revisor                          |
| :----: | :--------: | :----------------------:                                               | :----------------------------------------:          | :-----------------------------------------:        |
|  1.0   | 22/05/2025 |   Criação do Documento                                                 | [João Pedro Costa](https://github.com/johnaopedro)  | [Julia Gabriela](https://github.com/JuliaGabP)     |
|  1.1   | 22/05/2025 | Adaptação do template das histórias de usuário e adição de referências | [João Pedro Costa](https://github.com/johnaopedro)  | [Julia Gabriela](https://github.com/JuliaGabP)     |
|  1.2   | 26/05/2025 | Adição das Histórias de Usuário                                        | [João Igor](https://github.com/JoaoPC10)            | [Julia Gabriela](https://github.com/JuliaGabP)     |
|  1.3   | 28/05/2025 | Adição de Historias de Usuário de 19 a 25                              | [João Pedro Costa](https://github.com/johnaopedro)  | [Julia Gabriela](https://github.com/JuliaGabP)     |
|  1.4   | 29/05/2025 | Adição de 6 Histórias de Usuário, correção dos IDs                     | [Julia Gabriela](https://github.com/JuliaGabP)      | [João Pedro Costa](https://github.com/johnaopedro) |
|  1.5   | 29/05/2025 | Adição da histórias de usuário 20 até 25                               | [Gabriel Flores](https://github.com/Gabrielfcoelho) | [João Pedro Costa](https://github.com/johnaopedro) |
|  1.6   | 01/06/2025 | Adição da histórias de usuário 32 a 37                                 | [Amanda Cruz](https://github.com/mandicrz) | [Ryan Salles](https://github.com/RA-Salles) |
