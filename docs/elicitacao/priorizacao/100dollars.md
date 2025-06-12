# $100

## Introdução

Neste artefato, será aplicada a técnica de priorização de requisitos utilizando os $100 fictícios. Este método permite avaliar quais devem ser implementadas primeiro, garantindo que os recursos sejam distribuídos de forma estratégica, levando em conta as funcionalidades mais críticas para o sucesso do sistema.

## Metodologia

A técnica foi aplicada de forma remota, em dupla, com [Amanda Cruz](), e outro membro do grupo, [Gabriel Flores](), realizando a distribuição dos $100 imaginários entre os requisitos elicitados pela técnica de [Introspecção](../tecnicas/introspecção.md). A atividade foi conduzida de forma colaborativa, onde a Amanda foi responsável por coordenar o processo.

No início da atividade, foi explicado ao participante o objetivo da técnica e como os dólares seriam distribuídos. Cada um, teve a responsabilidade de alocar o dinheiro imaginário entre os requisitos de acordo com sua percepção sobre a importância e o impacto de cada um no sucesso do sistema. Os mesmos receberam valores dependendo da sua prioridade e a distribuição foi feita com o objetivo de refletir as necessidades reais do projeto, focando nas funcionalidades mais essenciais.

Ao final, os que receberam maior alocação de dólares foram classificados como mais prioritários e, dessa forma, selecionamos as funcionalidades que deveriam ser implementadas primeiro no projeto.

## Requisitos Elicitados

Os requisitos elicitados através da Introspecção serão listados abaixo, conforme a Tabela 1, para que seja possível visualizar e realizar o procedimento dos $100. Para fácil entendimento, a leitura pode ser lida conforme a legenda, descrita logo abaixo.

Legenda - Tabela 1:
 
- RFx: Requisitos Funcionais nºx.
- RNFx: Requisitos Não-Funcionais nºx.

<center><b>Tabela 1: </b> Requisitos Elicitados</center>

| Tipo  | Descrição                                                                             | Amanda    |  Gabriel | Preço Total |
|-----  |-------------------------------------------------------------------------              | ------    | ----     | ----        |
| RF01  | Permite ao usuário visualizar seus dados no Cadastro Único.                           | $8        | $5       | $6.5        | 
| RF02  | Possibilita iniciar um pré-cadastro para uma nova unidade familiar.                   | $2        | $3       | $2.5        |
| RF03  | Mostra os CRAS mais próximos com base na localização do usuário.                      | $2        | $3       | $2.5        |
| RF04  | Permite o envio de mensagens importantes ao usuário por meio do app.                  | $6        | $3       | $4.5        |
| RF05  | Traz dados de vínculos e contribuições automaticamente do CNIS.                       | $0        | $3       | $1.5        |
| RF06  | O sistema deve permitir o cadastro de novos usuários, coletando informações pessoais. | $8        | $5       | $6.5        |
| RF07  | O sistema deve possibilitar ao usuário atualizar seus dados cadastrais.               | $7        | $3       | $5          |
| RF08  | Permite verificar o status do cadastro e da situação dos benefícios.                  | $8        | $3       | $5.5        |
| RF09  | Gera um comprovante de cadastro atualizado para o usuário.                            | $4        | $5       | $4.5        |
| RF10  | Permite visualizar benefícios disponíveis com base nos dados cadastrados.             | $6        | $2       | $4.0        |
| RF11  | Implementa um chatbot para atendimento automatizado ao usuário.                       | $1        | 3        | $2          |
| RF12  | Envia notificações sobre pendências ou atualizações necessárias ao usuário.           | $6        | $3       | $4.5        |
| RF13  | Permite ao usuário simular benefícios sociais com base em suas informações.           | $2        | $2       | $2          |
| RF14  | Possibilita o envio de documentos digitalizados para o sistema.                       | $1        | $4       | $2.5        |
| RF15  | Permite marcar atendimentos nos postos de atendimento presencial (CRAS).              | $3        | $4       | $3.5        |
| RNF01 | O design do aplicativo é simples e de fácil navegação.                                | $6        | $4       | $5          |
| RNF02 | Suporta um grande número de acessos simultâneos.                                      | $2        | $4       | $3          |
| RNF03 | Integrado com sistemas como o CNIS.                                                   | $4        | $4       | $4          |
| RNF04 | Navegação intuitiva e acessibilidade geral.                                           | $6        | $4       | $5          |
| RNF05 | Uso de criptografia e proteção de dados sensíveis.                                    | $8        | $5       | $6.5        |
| RNF06 | Resposta rápida nas interações do usuário (até 3 segundos).                           | $2        | $2       | $2          |
| RNF07 | Compatível com Android e iOS.                                                         | $6        | $3       | $4.5        |
| RNF08 | Garantia de 99% de disponibilidade com mínimas interrupções.                          | $4        | $5       | $4.5        |
| RNF09 | Inclusão de leitores de tela e navegação adaptada.                                    | $5        | $6       | $5.5        |
| RNF10 | Operação eficiente em conexões lentas.                                                | $3        | $3       | $3          |
| RNF11 | Disponibilidade do app em múltiplos idiomas.                                          | $0        | $1       | $0.5        |
| RNF12 | Recuperação da sessão em caso de interrupções.                                        | $2        | $2       | $2          |
| RNF13 | Alternativa visual para ambientes com pouca luz.                                      | $1        | $2       | $1.5        |
| RNF14 | Mecanismos para manter o sistema funcional mesmo em situações críticas.               | $3        | $5       | $4          |

<center><b>Autor: </b> Amanda Cruz, 2025</center>

### Análise dos Requisitos Priorizados

A análise da técnica dos $100 revelou que requisitos como RF01, RF06 e RNF05, todos com $6.5, são indispensáveis para o sistema, já que lidam com aspectos centrais como acesso aos dados do Cadastro Único, registro de novos usuários e segurança da informação. Em contrapartida, funcionalidades como suporte a múltiplos idiomas (RNF11, $0.5) e ajustes para ambientes com pouca luz (RNF13, $1.5) receberam baixa prioridade, sugerindo que podem ser adiadas para etapas futuras do desenvolvimento.

Os requisitos intermediários, com valores entre $2.0 e $5.5, formam um grupo essencial para melhorar a experiência do usuário e a eficiência do sistema, mas não são tão urgentes quanto os prioritários. Por exemplo, o envio de notificações (RF12, $4.5) ajuda a manter os usuários informados sobre pendências, enquanto a compatibilidade com Android e iOS (RNF07, $4.5) garante maior alcance. Da mesma forma, a integração com o CNIS (RNF03, $4.0) e a acessibilidade geral (RNF04, $5.0) agregam valor significativo, mas podem ser implementados após as funcionalidades críticas, como a proteção de dados (RNF05), que é muito importante para a confiança no sistema.

## Conclusão

A aplicação da técnica dos $100 revelou-se eficaz para priorizar os requisitos do sistema permitindo uma distribuição clara e estratégica dos recursos. 

## Referências

> WIEGERS, Karl; BEATTY, Joy. Software Requirements. 3. ed. Seattle: Microsoft Press, 2013.

## Histórico de Versão

| Versão |    Data    |      Descrição       |          Autor        |       Revisor       |
| :----: | :--------: | :------------------: | :-------------------: | :-----------------: |
|  1.0   | 04/05/2025 | Criação do Documento | [Amanda Cruz](https://github.com/mandicrz), [Gabriel Flores](https://github.com/Gabrielfcoelho)  | [João Pedro](https://github.com/johnaopedro) |
