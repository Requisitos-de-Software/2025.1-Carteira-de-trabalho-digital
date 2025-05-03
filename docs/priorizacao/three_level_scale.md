# Three-Level Scale
## Introdução

O Three-Level Scale é um método utilizado para priorizar requisitos em projetos de software, classificando-os em três categorias: alta prioridade, prioridade média e baixa prioridade. Esse método, embora seja subjetivo, é eficaz quando os stakeholders concordam sobre os critérios de cada nível. A avaliação é feita com base em duas dimensões principais:

- Importância: Relevância do requisito para os objetivos do negócio.
- Urgência: Necessidade imediata de implementação do requisito.

As categorias são definidas da seguinte forma:

- Alta Prioridade: Requisitos importantes e urgentes, necessários para alcançar os objetivos do negócio na próxima versão. Incluem obrigações contratuais ou requisitos de conformidade que não podem ser adiados.
- Prioridade Média: Requisitos importantes, mas não urgentes, que podem ser adiados para versões futuras sem grandes prejuízos.
- Baixa Prioridade: Requisitos que não são críticos para o negócio e podem ser adiados ou descartados sem impacto significativo.

Requisitos percebidos como urgentes, mas que não são importantes para os objetivos de negócio, devem ser evitados ou removidos, pois não agregam valor suficiente ao produto. Além disso, é recomendável incluir a prioridade de cada requisito como um atributo nos documentos de requisitos para garantir clareza e alinhamento entre os envolvidos.

## Aplicação no App Cadastro Único

No contexto do aplicativo Cadastro Único, o método pode ser aplicado para organizar e priorizar os requisitos de forma eficiente. A seguir, apresentamos os requisitos funcionais e não funcionais identificados, categorizados de acordo com a técnica Three-Level Scale. A partir dos requisitos obtidos pelas tecnicas de elicitação, que são questionário, entrevista e análise de documentos e introspecção, foram definidos os requisitos funcionais e não funcionais do sistema. Os requisitos foram organizados em tabelas, com suas respectivas descrições, rastreabilidade e prioridades.
Os requisitos foram classificados em três níveis de prioridade, com base na importância e urgência de cada um deles. A seguir, apresentamos as tabelas com os requisitos priorizados.

### Requisitos Priorizados

#### Tabela 1: Requisitos Funcionais

| ID      | Nome do Requisito                     | Descrição                                                          | Rastreabilidade                   | Prioridade |
| ------- | ------------------------------------- | ------------------------------------------------------------------ | --------------------------------- | ---------- |
| RF01    | Cadastro de Famílias                  | Cadastro de famílias com renda até meio salário mínimo ou programas sociais. | Questionário / Análise de documentos | Alta       |
| RF02    | Cadastro de Pessoas                   | Registro de identificação, escolaridade etc.                       | Questionário / Análise de documentos | Alta       |
| RF03    | Cadastro de Domicílios                | Registro de tipo de construção, saneamento, etc.                   | Questionário / Análise de documentos | Média      |
| RF04    | Cadastro de Agricultores Familiares   | Registro de posse de terra, renda e trabalho.                      | Questionário / Análise de documentos | Média      |
| RF05    | Atualização de Dados                  | Atualização dos dados cadastrais.                                  | Questionário / Introspecção       | Alta       |
| RF06    | Processamento de Dados                | Envio à CAIXA e geração de NIS.                                    | Questionário / Análise de documentos | Alta       |
| RF07    | Correção de Inconsistências           | Correção e retransmissão de dados.                                 | Análise de Documentos             | Média      |
| RF08    | Consulta de Dados                     | Consulta cadastral e benefícios.                                   | Questionário / Introspecção       | Alta       |
| RF09    | Relatórios e Divulgação               | Geração de relatórios e compartilhamento com órgãos.               | Análise de Documentos             | Média      |
| RF10    | Formulários de Coleta                 | Formulários principais e suplementares.                            | Análise de Documentos             | Alta       |
| RF11    | Cadastro MEI                          | Cadastro de usuário como MEI.                                      | Análise de Documentos             | Alta       |
| RF12    | Informações MEI                       | Seção sobre MEI.                                                   | Análise de Documentos             | Média      |
| RF13    | Personalização MEI                    | Conteúdos personalizados conforme setor e região.                  | Análise de Documentos             | Média      |
| RF14  | Consultar dados cadastrais            | Visualização dos dados do Cadastro Único.                          | Introspecção                      | Alta       |
| RF15  | Pré-cadastrar família                 | Início de pré-cadastro de unidade familiar.                        | Introspecção                      | Alta       |
| RF16  | Localizar postos de atendimento       | Localiza CRAS com base na localização do usuário.                  | Introspecção                      | Média      |
| RF17  | Enviar notificações                   | Envio de mensagens importantes via app.                            | Introspecção                      | Média      |
| RF18  | Integrar com o CNIS                   | Integração automática com CNIS.                                    | Introspecção                      | Alta       |
| RF19  | Cadastro de Usuário                   | Coleta de dados pessoais.                                          | Introspecção                      | Alta       |
| RF20  | Atualização de Dados                  | Atualização dos dados cadastrais.                                  | Introspecção                      | Alta       |
| RF21  | Consultar Situação Cadastral          | Verificação do status do cadastro.                                 | Introspecção                      | Alta       |
| RF22  | Emissão de Comprovante de Cadastro    | Geração de comprovante de cadastro.                                | Introspecção                      | Média      |
| RF23  | Filtragem de Benefícios               | Filtro de benefícios conforme dados cadastrados.                   | Introspecção                      | Média      |
| RF24  | Acessar dados cadastrais              | Permitir ao cidadão acessar seus dados no Cadastro Único.          | Entrevista                        | Alta       |
| RF25  | Atualizar dados                       | Permitir atualização de dados diretamente pelo aplicativo.         | Entrevista                        | Alta       |
| RF26  | Verificar elegibilidade               | Sistema deve informar se a família é elegível a programas sociais. | Entrevista                        | Alta       |
| RF27  | Receber notificações                  | Aplicativo deve notificar sobre pendências e prazos.               | Entrevista                        | Alta       |
| RF28  | Ter acesso offline                    | Parte das funcionalidades deve funcionar offline.                  | Entrevista                        | Média      |
<center>Autor(es): <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a></center>

#### Tabela 2: Requisitos Não Funcionais  
| ID      | Nome do Requisito                     | Descrição                                                          | Rastreabilidade                   | Prioridade |
| ------- | ------------------------------------- | ------------------------------------------------------------------ | --------------------------------- | ---------- |
| RNF01   | Desempenho                            | Processamento de dados em até 48h.                                 | Análise de documentos                | Alta       |
| RNF02   | Segurança                             | Confidencialidade e autenticação.                                  | Análise de documentos / Introspecção | Alta       |
| RNF03   | Escalabilidade                        | Suportar até 19,5 milhões de famílias.                             | Análise de documentos                | Alta       |
| RNF04   | Conformidade Legal                    | Atender portarias e regras da Senarc.                              | Análise de documentos                | Alta       |
| RNF05   | Acessibilidade                        | Acessível para operadores estaduais e municipais.                  | Análise de documentos                | Alta       |
| RNF06   | Disponibilidade                       | Sistema disponível diariamente.                                    | Análise de documentos / Introspecção | Alta       |
| RNF07   | Compatibilidade com Aplicativo Off-line | Compatível com app offline dos municípios.                         | Análise de documentos                | Alta       |
| RNF08   | Transmissão via Conectividade Social  | Uso exclusivo da ferramenta da CAIXA.                              | Análise de documentos                | Alta       |
| RNF09   | Acesso Restrito                       | Acesso restrito a instituições autorizadas.                        | Análise de documentos                | Alta       |
| RNF10   | Integração MEI                        | Comunicação com sistemas voltados ao MEI.                          | Análise de documentos                | Alta       |
| RNF11 | Interface intuitiva e amigável        | Interface simples e de fácil navegação.                            | Introspecção                      | Alta       |
| RNF12 | Suporte a grande base de usuários     | Suporte a muitos acessos simultâneos.                              | Introspecção                      | Alta       |
| RNF13 | Integração com sistemas oficiais      | Integração com sistemas como CNIS.                                 | Introspecção                      | Alta       |
| RNF14 | Usabilidade                           | Navegação intuitiva.                                               | Introspecção                      | Alta       |
| RNF15 | Segurança                             | Criptografia e proteção de dados sensíveis.                        | Introspecção                      | Alta       |
| RNF16 | Performance                           | Respostas em até 3 segundos.                                       | Introspecção                      | Alta       |
| RNF17 | Compatibilidade com Dispositivos      | Compatível com Android e iOS.                                      | Introspecção                      | Alta       |
| RNF18 | Disponibilidade                       | 99% de disponibilidade.                                            | Introspecção                      | Alta       |
| RNF19 | Interface simples                     | Interface intuitiva para idosos e pessoas com baixa escolaridade.  | Entrevista                        | Alta       |
| RNF20 | Navegação por voz                     | Opção de navegação com comandos de voz.                            | Entrevista                        | Média      |
| RNF21 | Tamanho de fonte ajustável            | Tamanho da fonte deve ser ajustável.                               | Entrevista                        | Alta       |
| RNF22 | Ícones ilustrativos                   | Uso de ícones autoexplicativos para facilitar compreensão.         | Entrevista                        | Alta       |
| RNF23 | Compatibilidade com aparelhos antigos | Compatível com dispositivos Android mais antigos.                  | Entrevista                        | Média      |
| RNF24 | Proteção de dados                     | Garantir privacidade e proteção das informações pessoais.          | Entrevista                        | Alta       |
<center>Autor(es): <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a></center>

### Requisitos Desejaveis Priorizados

#### Tabela 3: Requisitos Funcionais  
| ID    | Nome do Requisito                         | Descrição                                                        | Rastreabilidade | Prioridade |
| ----- | ----------------------------------------- | ---------------------------------------------------------------- | --------------- | ---------- |
| RF11  | Chatbot de atendimento automatizado       | Implementa um chatbot para atendimento automatizado ao usuário.  | Entrevista      | Média      |
| RF12  | Notificação de pendências ou atualizações | Envia notificações sobre pendências ou atualizações necessárias. | Entrevista      | Alta       |
| RF13  | Simulador de benefícios sociais           | Permite simular benefícios com base nas informações do usuário.  | Entrevista      | Média      |
| RF14  | Upload de documentos                      | Permite o envio de documentos digitalizados para o sistema.      | Entrevista      | Média      |
| RF15  | Agendamento de atendimento no CRAS        | Permite marcar atendimentos presenciais no CRAS.                 | Entrevista      | Alta       |
<center>Autor(es): <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a></center>

#### Tabela 4: Requisitos Não Funcionais  
| ID    | Nome do Requisito                         | Descrição                                                        | Rastreabilidade | Prioridade |
| ----- | ----------------------------------------- | ---------------------------------------------------------------- | --------------- | ---------- |
| RNF09 | Acessibilidade para deficiência visual    | Leitores de tela e navegação adaptada.                           | Entrevista      | Alta       |
| RNF10 | Desempenho para internet limitada         | Operação eficiente com conexão lenta.                            | Entrevista      | Média      |
| RNF11 | Outros idiomas                            | Disponibilidade do app em múltiplos idiomas.                     | Entrevista      | Baixa      |
| RNF12 | Backup e restauração de sessão            | Recuperação da sessão em caso de falha.                          | Entrevista      | Média      |
| RNF13 | Modo escuro                               | Alternativa visual para ambientes escuros.                       | Entrevista      | Baixa      |
| RNF14 | Alta disponibilidade e recuperação        | Garantia de funcionamento mesmo em desastres.                    | Entrevista      | Alta       |
<center>Autor(es): <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a></center>

### Renomeação de Requisitos

O nome de alguns requisitos foram alterados para melhorar a clareza e torná-los mais precisos quanto à sua funcionalidade ou objetivo. A seguir, são apresentados os requisitos que sofreram alterações em sua nomenclatura:

#### Tabela 5: Nome Original / Nome Novo

| **ID** | **Nome Original** | **Nome Novo** | **Rastreabilidade** | **Origem** |
|--------|-------------------|---------------|---------------------|------------|
| RF05   | Atualização de Dados | Atualização diária de Dados | Questionário / Introspecção | Análise de Documentos |
| RF07   | Correção de Inconsistências | Correção e retransmissão de dados | Análise de Documentos | Análise de Documentos |
| RNF07  | Compatibilidade com Aplicativo Off-line | Funcionalidades Off-line | QST13 | Questionário |
| RF-D01 | Agendamento no CRAS | Agendamento de atendimento no CRAS | Entrevista | Requisitos Desejados |
| RF-D05 | Chat de Atendimento | Chatbot de atendimento automatizado | Entrevista | Requisitos Desejados |
| RNF-D03 | Assistência por Voz | Navegação por voz | Entrevista | Requisitos Desejados |
| RNF05  | Acessibilidade | Acessibilidade para deficiência visual | Entrevista | Análise de Documentos |
| RF24 | Consulta de Benefícios | Acessar dados cadastrais | Entrevista | Entrevista |
| RF26 | Verificar elegibilidade | Sistema deve informar se a família é elegível a programas sociais | Entrevista | Entrevista |
<center>Autor(es): <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a></center>

<br>
Estas mudanças visam facilitar o entendimento dos requisitos, além de tornar mais precisa a descrição das funcionalidades esperadas do sistema.

## Referências

> Three level scale: Setting requirement priorities. In: WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. [S. l.]: Microsoft Press, 2013. cap. 16, p. 319-320. ISBN 0735679665.

## Histórico de Versões

| Versão | Data | Descrição  | Autor        | Revisor |
| :-----: | :----: | :----------: | :------------: | :--------: |
| 1.0    | 28/04/2025 | Criação da página da técnica Three Level Scale| [João Pedro Costa](https://github.com/johnaopedro)                   | [Ryan Salles](https://github.com/RA-Salles) |
| 1.1    | 03/05/2025 | Atualização da aplicação da técnica | [João Pedro Costa](https://github.com/johnaopedro)                   | [Ryan Salles](https://github.com/RA-Salles) |
