# Documento de Histórias de Usuário

## Funções dos autores

| Nome                 | Função                                                            | 
|----------------------|----------------------------------------------------------------   |
|[João Pedro Costa](https://github.com/johnaopedro)|Criação do documento; Adaptação do template das historias; Adição das referências| 
|[Julia Gabriela](https://github.com/JuliaGabP)|Revisão geral| 
<center>
    Autor(es): 
    <a href="https://github.com/JuliaGabP" target="_blank">Julia Gabriela</a>
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
| **Objetivo** | Descrição clara do propósito da história | Sim |
| **Perfil(s)** | Usuários que utilizarão a funcionalidade | Sim |
| **Fluxo de Negócio** | Representação visual do processo | Não |
| **Protótipo** | Esboço da interface ou comportamento | Não |
| **Especificação do Protótipo** | Detalhamento dos campos e componentes | Não |
| **Sistemas/Histórias Relacionadas** | Dependências e integrações | Não |
| **Critérios de Aceite** | Cenários de teste e validação | Sim |
| **Prioridade** | Alta, Média ou Baixa | Sim |
| **Estimativa** | Story Points ou horas | Sim |
| **Sprint** | Sprint de desenvolvimento planejada | Não |
| **Status** | Backlog, Em Desenvolvimento, Concluída | Sim |

## 6. Histórias de Usuário

### EU_001 - Gerenciar Status de Servidor no Quadro de Acesso

#### 1. DESCRIÇÃO

**Objetivo:** Permitir que administradores ativem e inativem servidores no quadro de acesso do sistema, mantendo histórico das alterações com justificativas.

**Perfil(s):** Administrador do Sistema

#### 2. FLUXO DE NEGÓCIO

```
[Administrador] → [Acessar Quadro de Acesso] → [Selecionar Servidor] → [Escolher Ação] → [Inativar/Ativar] → [Inserir Justificativa] → [Confirmar] → [Sistema Atualiza Status]
```

#### 3. PROTÓTIPO

*Interface com lista de servidores, botões de ação e modal de justificativa*

#### 3.1 ESPECIFICAÇÃO DO PROTÓTIPO

| Campo | Descrição |
|-------|-----------|
| Lista de Servidores | Tabela com nome, matrícula, status atual e ações disponíveis |
| Botão Inativar | Disponível apenas para servidores ativos |
| Botão Ativar | Disponível apenas para servidores inativos |
| Campo Justificativa | Campo de texto obrigatório para informar motivo da alteração |
| Botão Confirmar | Executa a ação após validação dos campos |
| Mensagem de Sucesso | Feedback visual da operação realizada |

#### 4. SISTEMAS E/OU HISTÓRIAS IMPACTADAS E/OU RELACIONADAS

- EU_002 - Consultar Histórico de Alterações
- EU_003 - Relatório de Servidores por Status
- Sistema de Auditoria - Log de Operações

#### 5. CRITÉRIOS DE ACEITE

**Cenário 01: Inativar Servidor Quadro Acesso (Administrador)**
- **Descrição:** Dado que necessita inativar registro de servidor ao quadro de acesso  
- **Quando:** em "Quadro de Acesso"  
- **E** seleciona registro de candidato que deseja inativar  
- **E** aciona opção de inativação  
- **Então** o sistema apresenta campo de justificativa  
- **Então** informa justificativa de inativação e aciona opção de confirmação  
- **Então** o sistema apresenta o registro como inativo e a mensagem "Servidor Inativado com sucesso."

**Cenário 02: Ativar Servidor Inativo no Quadro Acesso (Administrador)**
- **Descrição:** Dado que necessita ativar registro de servidor inativo no quadro de acesso  
- **Quando:** em "Quadro de Acesso"  
- **E** seleciona registro de candidato que deseja ativar  
- **E** aciona opção de ativação  
- **Então** o sistema apresenta campo de justificativa  
- **Então** informa justificativa de ativação e aciona opção de confirmação  
- **Então** o sistema apresenta o registro como ativo e a mensagem "Servidor Ativado com sucesso."

**Cenário 03: Validação Campo Obrigatório - Justificativa**
- **Descrição:** Dado que necessita ativar/inativar registro de servidor no quadro de acesso  
- **Quando:** em "Quadro de Acesso"  
- **E** seleciona registro de candidato que deseja ativar/inativar  
- **E** aciona opção de ativação/inativação  
- **Então** o sistema apresenta campo de justificativa  
- **Então** não informa justificativa de ativação/inativação e aciona opção de confirmação  
- **Então** o sistema apresenta mensagem "O campo justificativa não foi preenchido."

---

### EU_002 - Gerenciar Idiomas do Candidato

#### 1. DESCRIÇÃO

**Objetivo:** Permitir que usuários incluam, consultem e alterem informações sobre idiomas dos candidatos no sistema.

**Perfil(s):** Operador do Sistema, Gestor de RH

#### 2. FLUXO DE NEGÓCIO

```
[Usuário] → [Acessar Dados do Candidato] → [Seção Idiomas] → [Incluir/Consultar/Alterar] → [Selecionar Idiomas] → [Salvar] → [Sistema Confirma Operação]
```

#### 3. PROTÓTIPO

*Interface com seleção múltipla de idiomas conforme portaria nº 147 do MAPA*

#### 3.1 ESPECIFICAÇÃO DO PROTÓTIPO

| Campo | Descrição |
|-------|-----------|
| Incluir Idioma | Título da seção para adicionar novos idiomas |
| Lista de Idiomas | Seleção múltipla com opções: Espanhol, Francês, Japonês, Russo, Mandarim e Árabe |
| Campo Obrigatório | Pelo menos um idioma deve ser selecionado |
| Botão Salvar | Confirma a inclusão/alteração dos idiomas |

#### 4. SISTEMAS E/OU HISTÓRIAS IMPACTADAS E/OU RELACIONADAS

- EU_007 - Consultar Idiomas do Candidato
- EU_009 - Alterar Idiomas do Candidato  
- EU_011 - Anexar Documentos

#### 5. CRITÉRIOS DE ACEITE

**Cenário 01: Incluir Idiomas com Sucesso**
- **Descrição:** Dado que preciso incluir idiomas para um candidato
- **Quando** acesso a seção de idiomas do candidato
- **E** seleciono um ou mais idiomas da lista disponível
- **E** aciono o botão salvar
- **Então** o sistema registra os idiomas selecionados
- **E** apresenta mensagem "Idiomas incluídos com sucesso"

**Cenário 02: Validação de Seleção Obrigatória**
- **Descrição:** Dado que preciso incluir idiomas para um candidato
- **Quando** acesso a seção de idiomas do candidato
- **E** não seleciono nenhum idioma
- **E** aciono o botão salvar
- **Então** o sistema apresenta mensagem "Selecione pelo menos um idioma"

---
## Referências

> COORDENAÇÃO GERAL DE TECNOLOGIA DA INFORMAÇÃO - CGTI. EU_xxx_Titulo_da_Estoria_de_Usuario: template para especificação de histórias de usuário. [S.l.]: CGTI, 2018. 5 p. Disponível em: <a href="../../../assets/modelagem/US/template_historia_de_usuario.pdf" target="_blank">História de Usuário</a>. Acesso em: 22 de maio 2025.

## Histórico de Versão

| Versão |    Data    |        Descrição         |                   Autor                    |                   Revisor                   |
| :----: | :--------: | :----------------------: | :----------------------------------------: | :-----------------------------------------: |
|  1.0   | 22/05/2025 |   Criação do Documento   | [João Pedro Costa](https://github.com/johnaopedro) | [Julia Gabriela](https://github.com/JuliaGabP) |
|  1.1   | 22/05/2025 | Adaptação do template das histórias de usuário   | [João Pedro Costa](https://github.com/johnaopedro) | [Julia Gabriela](https://github.com/JuliaGabP) |