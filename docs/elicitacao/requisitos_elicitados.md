# Requisitos Elicitados

# Introdução

Esse documento visa apresentar todos os requisitos elicitados pelas técnicas de elicitação por meio das Tabelas 1 e 2. 

Legenda:

- RFx: Requisitos Funcionais nºx.
- RNFx: Requisitos Não-Funcionais nºx.

# Requisitos Funcionais 

<center>
    <b>Tabela 1:</b> Requisitos Funcionais Elicitados
</center>

| ID      | Nome                                      | Rastreabilidade                       | Implementado |
| :-----: | :---------------------------------------: | :-----------------------------------: | :----------: | 
| RF01    | Cadastro de Famílias                      | Questionário / Análise de documentos  | Sim |
| RF02    | Cadastro de Pessoas                       | Questionário / Análise de documentos  | Sim |
| RF03    | Cadastro de Domicílios                    | Questionário / Análise de documentos  | Sim |
| RF04    | Cadastro de Agricultores Familiares       | Questionário / Análise de documentos  | Sim |
| RF05    | Atualização de Dados                      | Questionário / Introspecção           | Sim |
| RF06    | Processamento de Dados                    | Questionário / Análise de documentos  | Sim |
| RF07    | Correção de Inconsistências               | Análise de Documentos                 | Sim |
| RF08    | Consulta de Dados                         | Questionário / Introspecção           | Sim |
| RF09    | Relatórios e Divulgação                   | Análise de Documentos                 | Sim |
| RF10    | Formulários de Coleta                     | Análise de Documentos                 | Sim |
| RF11    | Cadastro MEI                              | Análise de Documentos                 | Não |
| RF12    | Informações MEI                           | Análise de Documentos                 | Não |
| RF13    | Personalização MEI                        | Análise de Documentos                 | Não |
| RF14    | Consultar dados cadastrais                | Introspecção                          | Sim |
| RF15    | Pré-cadastrar família                     | Introspecção                          | Sim |
| RF16    | Localizar postos de atendimento           | Introspecção                          | Sim |
| RF17    | Enviar notificações                       | Introspecção                          | Sim |
| RF18    | Integrar com o CNIS                       | Introspecção                          | Sim |
| RF19    | Cadastro de Usuário                       | Introspecção                          | Sim |
| RF20    | Atualização de Dados                      | Introspecção                          | Sim |
| RF21    | Consultar Situação Cadastral              | Introspecção                          | Sim |
| RF22    | Emissão de Comprovante de Cadastro        | Introspecção                          | Sim |
| RF23    | Filtragem de Benefícios                   | Introspecção                          | Não |
| RF24    | Consulta de Benefícios                    | Entrevista                            | Sim |
| RF25    | Informações Cadastrais                    | Entrevista                            | Sim |
| RF26    | Chatbot de atendimento automatizado       | Introspecção                          | Não |
| RF27    | Notificação de pendências ou atualizações | Introspecção                          | Não |
| RF28    | Simulador de benefícios sociais           | Introspecção                          | Não |
| RF29    | Upload de documentos                      | Introspecção                          | Não |
| RF30    | Agendamento de atendimento no CRAS        | Introspecção/Entrevista               | Não |
| RF31    | Notificações Personalizadas               | Entrevista                            | Não |
| RF32    | Atualização Cadastral                     | Entrevista                            | Não |
| RF33    | Simulador de Benefícios                   | Entrevista                            | Não |
| RF34    | Chat de Atendimento                       | Entrevista                            | Não |
| RF35    | Tutoriais Interativos                     | Entrevista                            | Não |
| RF36    | Vídeos Explicativos                       | Entrevista                            | Não |
| RF37    | Assistência por Voz                       | Entrevista                            | Não |
| RF38    | Modo escuro                               | Introspecção                          | Não |

<center>
    Autor(es): 
    <a href="https://github.com/RA-Salles" target="_blank">Ryan Salles</a>, 
    <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a>
</center>

## Requisitos Não Funcionais
Essa seção apresenta os requisitos não funcionais elicitados por meio da Tabela 4.

<center>
    <b>Tabela 2:</b> Requisitos Não Funcionais elicitados
</center>

| ID    | Descrição                                          | Rastreabilidade                      | Implementado | 
|:-----:| :------------------------------------------------: | :----------------------------------: | :----------: |
| RNF01 | Desempenho                                         | Análise de documentos                | Não |
| RNF02 | Segurança                                          | Análise de documentos / Introspecção | Sim |
| RNF03 | Escalabilidade                                     | Análise de documentos                | Sim |
| RNF04 | Conformidade Legal                                 | Análise de documentos                | Sim |
| RNF05 | Acessibilidade                                     | Análise de documentos                | Não |
| RNF06 | Disponibilidade                                    | Análise de documentos / Introspecção | Sim |
| RNF07 | Compatibilidade com Aplicativo Off-line            | Análise de documentos                | Não |
| RNF08 | Transmissão via Conectividade Social               | Análise de documentos                | Não |
| RNF09 | Acesso Restrito                                    | Análise de documentos                | Sim |
| RNF10 | Integração MEI                                     | Análise de documentos                | Não |
| RNF11 | Interface intuitiva e amigável                     | Introspecção, Entrevista             | Sim |
| RNF12 | Suporte a grande base de usuários                  | Introspecção                         | Sim |
| RNF13 | Integração com sistemas oficiais                   | Introspecção                         | Sim |
| RNF14 | Usabilidade                                        | Introspecção                         | Não |
| RNF15 | Compatibilidade com Dispositivos                   | Introspecção                         | Sim | 
| RNF16 | Acessibilidade para pessoas com deficiência visual | Introspecção                         | Não |
| RNF17 | Desempenho otimizado para internet limitada        | Introspecção                         | Não |
| RNF18 | Possibilidade de outros idiomas                    | Introspecção                         | Não |
| RNF19 | Backup e restauração de sessão                     | Introspecção                         | Não |
| RNF20 | Alta disponibilidade e recuperação de desastres    | Introspecção                         | Não |


<center>
    Autor(es): 
    <a href="https://github.com/RA-Salles" target="_blank">Ryan Salles</a>, 
    <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a>
</center>


| Versão  | Data   | Descrição    | Autor          | Revisor |
| :-----: | :----: | :----------: | :------------: | :--------: |
| 1.0     | 04/05/2025 | Criação do Documento de Requisitos Elicitados |  [Ryan Salles](https://github.com/RA-Salles) | [João Pedro Costa](https://github.com/johnaopedro) |
| 1.1     | 13/05/2025 | Padronização, formatação e mesclagem com documento de requisitos desejáveis | [Ryan Salles](https://github.com/RA-Salles) | [João Pedro Costa](https://github.com/johnaopedro) |