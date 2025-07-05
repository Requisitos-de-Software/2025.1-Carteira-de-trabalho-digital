# Requisitos Elicitados

## Funções dos autores

|  Nome                                              | Função                                                                  | 
|----------------------------------------------------|------------------------------------------------------------------------ |
| [João Pedro Costa](https://github.com/johnaopedro) | Desenvolvimento de tabelas, ajustes e manutenção                        | 
| [Julia Gabriela](https://github.com/JuliaGabP)     | Revisora Geral.                                                         | 
| [Ryan Salles](https://github.com/RA-Salles)        | Criação da página, desenvolvimento de tabelas, ajustes e manutenção     | 
<center>
    Autor(es): 
    <a href="https://github.com/JuliaGabP" target="_blank">Julia Gabriela</a>
</center>

## Introdução

Esse documento visa apresentar todos os requisitos elicitados pelas técnicas de elicitação 
por meio das Tabelas 1 a 4 bem como permitir a rastreabilidade e refatoração dos requisitos 
sem a necessidade de voltar aos documentos de técnicas de elicitação.

Caso os requisitos sejam refatorados, uma nova versão da tabela será gerada e as tabelas
antigas serão mantidas para fins de arquivamento e documentação do desenvolvimento do projeto. 

Legenda:

- RFx : Requisitos Funcionais nºx.
- RNFx: Requisitos Não-Funcionais nºx.
- ISx : Requisito elicitado pela Introspecção
- ADx : Requisito elicitado pela Análise de Documentação
- ENTx: Requisito elicitado pela Entrevista
- QSTx: Requisito elicitado pelp Questionário

<!--
    REFATORANDO OS REQUISITOS - 25062025
        INTRODUÇÃO:
            Por razões de duplicação de requisitos com pequenos detalhes entre eles e dificuldade
            de manter entendimento dos requisitos além de dificuldade de comunicar os requisitos
            elicitados entre clientes e partes interessadas, esse comentário é um registro de como
            a refatoração foi planejada e executada no maior nível de detalhes que me é permitido
            sem ser prolixo. Idealmente. Todavia formal. Também, idealmente.

        Metodologia:
            O procedimento adotado para refatorar esses requisitos será o seguinte:
                1. Agrupamento
                    Requisitos que tratam de funcionalidades parecidas, iguais ou dependentes
                    serão agrupados.
                2. Generalização
                    Os grupos de requisitos gerarão um novo requisito pai, que possuirá a grande 
                    referência dos requisitos.
                3. Especialização
                    Requisitos participantes de um mesmo grupo, se únicos em descrição, serão 
                    especializados em subrequisitos do requisito pai. 
            Em termos práticos, vamos aplicar uma espécie de herança aqui. Caso um requisito tenha
            nomes iguais e descrições diferentes, o nome precisa ser alterado.
        Objetivos gerais:
            Melhorar a rastreabilidade!
            Melhorar e facilitar o entendimento!
        Objetivos específicos:
            -> criar links por todas as partes!
                "Esse problema vai custar um tempo InFeRnAL :>"
            -> Destruir as duplicatas estranhas!
            -> Agrupar os requisitos de uma forma razoável!
            -> Mante exatamente o mesmo número de requisitos ao final (exceto caso eles sejam iguais em nome e descrição)
 -->

## Requisitos Funcionais 

### Primeira Versão

A tabela 1 apresenta a primeira versão dos requisitos elicitados, mantendo suas descrições originais obtidas
utilizando as técnicas de elicitação. A primeira versão foi mantida para fins de arquivamento do desenvolvimento e 
compatibilidade com documentos e artefatos não refatorados.

<center>
    <b>Tabela 1:</b> Requisitos Funcionais Elicitados, Primeira Versão
</center>


| ID                                       | Nome                                        | Descrição                                                                                                                                                                                      | Rastreabilidade                                                                                                 | Implementado |
| :--------------------------------------: | :-----------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------: | :----------: | 
| [RF01](tecnicas/questionario.md)         | Cadastro de Famílias                        | Permitir o cadastro de famílias com renda mensal de até meio salário mínimo por pessoa ou vinculadas a programas sociais                                                                       | [QST01](tecnicas/questionario.md) / [AD01](tecnicas/analise_documentacao.md)                                    | Sim          |
| [RF02](tecnicas/questionario.md)         | Cadastro de Pessoas                         | Registrar informações pessoais, como dados de identificação, documentação, frequência escolar, grau de instrução, entre outros.                                                                | [QST02](tecnicas/questionario.md) / [AD02](tecnicas/analise_documentacao.md)                                    | Sim          |
| [RF03](tecnicas/questionario.md)         | Cadastro de Domicílios                      | Registrar características do domicílio, como tipo de construção, abastecimento de água, iluminação, escoamento sanitário, entre outros.                                                        | [QST03](tecnicas/questionario.md) / [AD03](tecnicas/analise_documentacao.md)                                    | Sim          |
| [RF04](tecnicas/questionario.md)         | Cadastro de Agricultores Familiares         | Registrar informações sobre posse de terra, atividade primária, contratação de mão de obra e composição da renda.                                                                              | [QST04](tecnicas/questionario.md) / [AD04](tecnicas/analise_documentacao.md)                                    | Sim          |
| [RF05](tecnicas/questionario.md)         | Atualização de Dados de família             | Permitir a atualização dos dados das famílias cadastradas.                                                                                                                                     | [QST05](tecnicas/questionario.md) / [AD05](tecnicas/analise_documentacao.md)                                    | Sim          |
| [RF06](tecnicas/questionario.md)         | Processamento de Dados                      | Transmitir os dados coletados para a CAIXA, processá-los e atribuir um Número de Identificação Social (NIS) único para cada pessoa cadastrada.                                                 | [QST06](tecnicas/questionario.md) / [AD06](tecnicas/analise_documentacao.md)                                    | Sim          |
| [RF07](tecnicas/analise_documentacao.md) | Correção de Inconsistências                 | Permitir a correção de inconsistências detectadas no processamento e retransmissão dos dados.                                                                                                  | [AD07](tecnicas/analise_documentacao.md)                                                                        | Sim          |
| [RF08](tecnicas/questionario.md)         | Consulta de Dados                           | Permitir a consulta de dados cadastrais, situação de benefícios e ações de gestão de benefícios por meio do NIS.                                                                               | [QST07](tecnicas/questionario.md) / [IS01](tecnicas/introspecção.md) / [AD08](tecnicas/analise_documentacao.md) | Sim          |
| [RF09](tecnicas/analise_documentacao.md) | Relatórios e Divulgação                     | Gerar relatórios anuais com o perfil das famílias beneficiárias e disponibilizar dados para instituições de pesquisa e órgãos de governo mediante acordos e termos de responsabilidade.        | [AD09](tecnicas/analise_documentacao.md)                                                                        | Sim          |
| [RF10](tecnicas/analise_documentacao.md) | Formulários de Coleta                       | Implementar formulários principais e suplementares para coleta de dados, abrangendo características de domicílios, famílias, pessoas, vinculação a programas e pessoas em situação de rua.     | [AD10](tecnicas/analise_documentacao.md)                                                                        | Sim          |
| [RF11](tecnicas/analise_documentacao.md) | Cadastro MEI                                | Permitir que, ao cadastrar um usuário, o cadastro possa especificar que o usuário é um MEI.                                                                                                    | [AD11](tecnicas/analise_documentacao.md)                                                                        | Não          |
| [RF12](tecnicas/analise_documentacao.md) | Informações MEI                             | Conter seção de informações sobre microempreendedorismo individual.                                                                                                                            | [AD12](tecnicas/analise_documentacao.md)                                                                        | Não          |
| [RF13](tecnicas/analise_documentacao.md) | Personalização MEI                          | Personalização de conteúdos da seção MEI de acordo com o setor de atuação do usuário registrado e/ou região do território brasileiro onde atua.                                                | [AD13](tecnicas/analise_documentacao.md)                                                                        | Não          |
| [RF14](tecnicas/introspecção.md)         | Consultar dados cadastrais                  | Permite ao usuário visualizar seus dados no Cadastro Único.                                                                                                                                    | [IS01](tecnicas/introspecção.md)                                                                                | Sim          |
| [RF15](tecnicas/introspecção.md)         | Pré-cadastrar família                       | Possibilita iniciar um pré-cadastro para uma nova unidade familiar.                                                                                                                            | [IS02](tecnicas/introspecção.md)                                                                                | Sim          |
| [RF16](tecnicas/introspecção.md)         | Localizar postos de atendimento             | Mostra os CRAS mais próximos com base na localização do usuário.                                                                                                                               | [IS03](tecnicas/introspecção.md)                                                                                | Sim          |
| [RF17](tecnicas/introspecção.md)         | Enviar notificações                         | Envia notificações sobre pendências ou atualizações necessárias ao usuário.                                                                                                                    | [IS04](tecnicas/introspecção.md)                                                                                | Sim          |
| [RF18](tecnicas/introspecção.md)         | Integrar com o CNIS                         | Traz dados de vínculos e contribuições automaticamente do CNIS.                                                                                                                                | [IS05](tecnicas/introspecção.md)                                                                                | Sim          |
| [RF19](tecnicas/introspecção.md)         | Cadastro de Usuário                         | O sistema deve permitir o cadastro de novos usuários, coletando informações pessoais como nome, CPF, endereço, e outros dados necessários.                                                     | [IS06](tecnicas/introspecção.md)                                                                                | Sim          |
| [RF20](tecnicas/introspecção.md)         | Atualização de Dados do Usuário             | O sistema deve possibilitar ao usuário atualizar seus dados cadastrais a qualquer momento.                                                                                                     | [IS07](tecnicas/introspecção.md)                                                                                | Sim          |
| [RF21](tecnicas/introspecção.md)         | Consultar Situação Cadastral                | O sistema deve permitir que o usuário consulte o status de seu cadastro e a situação atual do benefício.                                                                                       | [IS08](tecnicas/introspecção.md)                                                                                | Sim          |
| [RF22](tecnicas/introspecção.md)         | Emissão de Comprovante de Cadastro          | O sistema deve possibilitar que o usuário gere e imprima um comprovante de cadastro atualizado.                                                                                                | [IS09](tecnicas/introspecção.md)                                                                                | Sim          |
| [RF23](tecnicas/introspecção.md)         | Filtragem de Benefícios                     | O sistema deve permitir ao usuário visualizar os benefícios aos quais ele pode ter direito com base nos dados cadastrados.                                                                     | [IS10](tecnicas/introspecção.md)                                                                                | Não          |
| [RF24](tecnicas/entrevista.md)           | Consulta de Benefícios                      | Consulta de status de benefícios                                                                                                                                                               | [ENT01](tecnicas/entrevista.md)                                                                                 | Sim          |
| [RF25](tecnicas/entrevista.md)           | Informações Cadastrais                      | Visualização de informações cadastrais                                                                                                                                                         | [ENT02](tecnicas/entrevista.md)                                                                                 | Sim          |
| [RF26](tecnicas/introspecção.md)         | Chatbot de atendimento automatizado         | Implementa um chatbot para atendimento automatizado ao usuário.                                                                                                                                | [IS12](tecnicas/introspecção.md)                                                                                | Não          |
| [RF27](tecnicas/introspecção.md)         | Notificação de pendências ou atualizações   | Envia notificações sobre pendências ou atualizações necessárias ao usuário.                                                                                                                    | [IS13](tecnicas/introspecção.md)                                                                                | Não          |
| [RF28](tecnicas/introspecção.md)         | Simulador de benefícios sociais             | Permite ao usuário simular quais benefícios sociais poderia receber.                                                                                                                           | [IS14](tecnicas/introspecção.md)                                                                                | Não          |
| [RF29](tecnicas/introspecção.md)         | Upload de documentos                        | Permite ao usuário fazer upload de documentos para o sistema.                                                                                                                                  | [IS11](tecnicas/introspecção.md)                                                                                | Não          |
| [RF30](tecnicas/entrevista.md)           | Agendamento de atendimento no CRAS          | Agendamento de atendimentos no CRAS pelo app                                                                                                                                                   | [ENT06](tecnicas/entrevista.md)                                                                                 | Não          |
| [RF31](tecnicas/entrevista.md)           | Notificações Personalizadas                 | Notificações personalizadas (pendências, atualizações, confirmações)                                                                                                                           | [ENT07](tecnicas/entrevista.md)                                                                                 | Não          |
| [RF32](tecnicas/entrevista.md)           | Atualização Cadastral                       | Passo a passo claro para atualização cadastral                                                                                                                                                 | [ENT08](tecnicas/entrevista.md)                                                                                 | Não          |
| [RF33](tecnicas/entrevista.md)           | Simulador de Benefícios                     | Simulador de elegibilidade para benefícios                                                                                                                                                     | [ENT09](tecnicas/entrevista.md)                                                                                 | Não          |
| [RF34](tecnicas/entrevista.md)           | Chat de Atendimento                         | Chat de atendimento ao usuário                                                                                                                                                                 | [ENT10](tecnicas/entrevista.md)                                                                                 | Não          |
| [RF35](tecnicas/entrevista.md)           | Tutoriais Interativos                       | Tutoriais interativos para guiar tarefas críticas                                                                                                                                              | [ENT03](tecnicas/entrevista.md)                                                                                 | Não          |
| [RF36](tecnicas/entrevista.md)           | Vídeos Explicativos                         | Vídeos explicativos dentro do app                                                                                                                                                              | [ENT04](tecnicas/entrevista.md)                                                                                 | Não          |
| [RF37](tecnicas/entrevista.md)           | Assistência por Voz                         | Ferramenta de assistência por voz para usuários necessitados                                                                                                                                   | [ENT05](tecnicas/entrevista.md)                                                                                 | Não          |
| [RF38](tecnicas/introspecção.md)         | Modo escuro                                 | O aplicativo oferece uma opção de modo escuro para melhorar a experiência do usuário em ambientes com pouca luz.                                                                               | [IS15](tecnicas/introspecção.md)                                                                                | Não          |
| [RF39](tecnicas/analise_documentacao.md) | Integração MEI                              | Permitir que o sistema converse com demais sistemas para MEIs                                                                                                                                  | [AD14](tecnicas/analise_documentacao.md)                                                                        | Não          |          
| [RF40](tecnicas/entrevista.md)           | Login via GOV.br                            | Permitir que o usuário entre no sistema utilizando o GOV.br e subsequente integração com o GOV.br                                                                                              | [EU_38](../modelagem/agil/historia_de_usuario.md)                                                               | Sim          |                                                                                                              | Sim          |

<center>
    Autor(es): 
    <a href="https://github.com/RA-Salles" target="_blank">Ryan Salles</a>, 
    <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a>
</center>

### Segunda Versão

A Tabela 2 apresenta a segunda versão dos requisitos elicitados. As seguintes mudanças gerais podem ser observadas:

- As descrições foram atualizadas para melhor refletir a representação dos requisitos funcionais 
como partes do sistema a ser implementado e não necessariamente restrições ao sistema
- Requisitos relacionados a integração do sistema foram movidos para os requisitos não funcionais
- Requisitos tiveram seus links atualizados para permitir melhor rastreabilidade entre os documentos.
- Requisitos com nomes ambíguos todavia descrições únicas tiveram seus nomes atualizados.

As mudanças específicas também foram registradas, todavia mediante referenciação dos requisitos de primeira versão.
São elas:
- O requisito 19 foi apagado por ser uma duplicata do requisito 02.
- Os requisito 33 foi agrupado com o requisito 28 por se tratar da mesma funcionalidade.
Como resultado, o requisito 33 foi excluído.
- Os requisitos 18 e 39 foram movidos para a tabela de requisitos não funcionais
- O requisito 40 foi alterado para se referir apenas a possibilidade de login, todavia não com a integração com os sistemas do
GOV.br
- O requisito 32 possuia um título ambíguo em relação a sua descrição, aparentando estar relacionado com a capacidade de atualização
de dados enquanto, na verdade, se relacionava a capacidade do sistema de prover um guia de como o usuário poderia realizar essa atualização.
Como consequência, o título foi incrementado de "Atualização Cadastral" para "Guia de Atualização Cadastral" e sua descrição foi tornada um 
pouco mais descritiva.

Apesar das mudanças realizadas, foi escolhido manter a referência antiga para simplificar
retrabalhos gerados pelo versionamento desses requisitos e manter a rastreabilidade com as versões
antigas para fácil comparação.

Legenda
- RFX-v2 : Requisito de tipo funcional, Versão 2.
<center>
    <b>Tabela 2:</b> Requisitos Funcionais Elicitados, Segunda Versão
</center>

| ID                                       | Nome                                        | Descrição                                                                                                                                                                                      | Rastreabilidade                                                                                                 | Implementado |
| :--------------------------------------: | :-----------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------: | :----------: | 
| <a id="rf01"></a>    **RF01**            | Cadastro de Famílias                        | Permitir o cadastro de famílias com renda mensal de até meio salário mínimo por pessoa ou vinculadas a programas sociais                                                                       | [QST01](tecnicas/questionario.md) / [AD01](tecnicas/analise_documentacao.md)                                    | Sim          |
| <a id="rf02-v2"></a> **RF02-v2**         | Cadastro de Pessoas                         | Registrar informações pessoais para permitir o cadastro de usuários, os quais são pessoas, como dados de identificação, documentação, frequência escolar, grau de instrução, entre outros.     | [QST02](tecnicas/questionario.md) / [AD02](tecnicas/analise_documentacao.md) / [IS06](tecnicas/introspecção.md) | Sim          |
| <a id="rf03"></a>    **RF03**            | Cadastro de Domicílios                      | Registrar características do domicílio, como tipo de construção, abastecimento de água, iluminação, escoamento sanitário, entre outros.                                                        | [QST03](tecnicas/questionario.md) / [AD03](tecnicas/analise_documentacao.md)                                    | Sim          |
| <a id="rf04"></a>    **RF04**            | Cadastro de Agricultores Familiares         | Registrar informações sobre posse de terra, atividade primária, contratação de mão de obra e composição da renda.                                                                              | [QST04](tecnicas/questionario.md) / [AD04](tecnicas/analise_documentacao.md)                                    | Sim          |
| <a id="rf05"></a>    **RF05**            | Atualização de Dados de família             | Permitir a atualização dos dados das famílias cadastradas.                                                                                                                                     | [QST05](tecnicas/questionario.md) / [AD05](tecnicas/analise_documentacao.md)                                    | Sim          |
| <a id="rf06"></a>    **RF06**            | Processamento de Dados                      | Transmitir os dados coletados para a CAIXA, processá-los e atribuir um Número de Identificação Social (NIS) único para cada pessoa cadastrada.                                                 | [QST06](tecnicas/questionario.md) / [AD06](tecnicas/analise_documentacao.md)                                    | Sim          |
| <a id="rf07"></a>    **RF07**            | Correção de Inconsistências                 | Permitir a correção de inconsistências detectadas no processamento e retransmissão dos dados.                                                                                                  | [AD07](tecnicas/analise_documentacao.md)                                                                        | Sim          |
| <a id="rf08"></a>    **RF08**            | Consulta de Dados                           | Permitir a consulta de dados cadastrais, situação de benefícios e ações de gestão de benefícios por meio do NIS.                                                                               | [QST07](tecnicas/questionario.md) / [IS01](tecnicas/introspecção.md) / [AD08](tecnicas/analise_documentacao.md) | Sim          |
| <a id="rf09"></a>    **RF09**            | Relatórios e Divulgação                     | Gerar relatórios anuais com o perfil das famílias beneficiárias e disponibilizar dados para instituições de pesquisa e órgãos de governo mediante acordos e termos de responsabilidade.        | [AD09](tecnicas/analise_documentacao.md)                                                                        | Sim          |
| <a id="rf10"></a>    **RF10**            | Formulários de Coleta                       | Implementar formulários principais e suplementares para coleta de dados, abrangendo características de domicílios, famílias, pessoas, vinculação a programas e pessoas em situação de rua.     | [AD10](tecnicas/analise_documentacao.md)                                                                        | Sim          |
| <a id="rf11"></a>    **RF11**            | Cadastro MEI                                | Permitir que, ao cadastrar um usuário, o cadastro possa especificar que o usuário é um MEI.                                                                                                    | [AD11](tecnicas/analise_documentacao.md)                                                                        | Não          |
| <a id="rf12"></a>    **RF12**            | Informações MEI                             | Conter seção de informações sobre microempreendedorismo individual.                                                                                                                            | [AD12](tecnicas/analise_documentacao.md)                                                                        | Não          |
| <a id="rf13"></a>    **RF13**            | Personalização MEI                          | Personalização de conteúdos da seção MEI de acordo com o setor de atuação do usuário registrado e/ou região do território brasileiro onde atua.                                                | [AD13](tecnicas/analise_documentacao.md)                                                                        | Não          |
| <a id="rf14"></a>    **RF14**            | Consultar dados cadastrais                  | Permite ao usuário visualizar seus dados no Cadastro Único.                                                                                                                                    | [IS01](tecnicas/introspecção.md)                                                                                | Sim          |
| <a id="rf15"></a>    **RF15**            | Pré-cadastrar família                       | Possibilita iniciar um pré-cadastro para uma nova unidade familiar.                                                                                                                            | [IS02](tecnicas/introspecção.md)                                                                                | Sim          |
| <a id="rf16"></a>    **RF16**            | Localizar postos de atendimento             | Mostra os CRAS mais próximos com base na localização do usuário.                                                                                                                               | [IS03](tecnicas/introspecção.md)                                                                                | Sim          |
| <a id="rf17"></a>    **RF17**            | Enviar notificações                         | Envia notificações sobre pendências ou atualizações necessárias ao usuário.                                                                                                                    | [IS04](tecnicas/introspecção.md)                                                                                | Sim          |
| <a id="rf20"></a>    **RF20**            | Atualização de Dados do Usuário             | O sistema deve possibilitar ao usuário atualizar seus dados cadastrais a qualquer momento.                                                                                                     | [IS07](tecnicas/introspecção.md)                                                                                | Sim          |
| <a id="rf21"></a>    **RF21**            | Consultar Situação Cadastral                | O sistema deve permitir que o usuário consulte o status de seu cadastro e a situação atual do benefício.                                                                                       | [IS08](tecnicas/introspecção.md)                                                                                | Sim          |
| <a id="rf22"></a>    **RF22**            | Emissão de Comprovante de Cadastro          | O sistema deve possibilitar que o usuário gere e imprima um comprovante de cadastro atualizado.                                                                                                | [IS09](tecnicas/introspecção.md)                                                                                | Sim          |
| <a id="rf23"></a>    **RF23**            | Filtragem de Benefícios                     | O sistema deve permitir ao usuário visualizar os benefícios aos quais ele pode ter direito com base nos dados cadastrados.                                                                     | [IS10](tecnicas/introspecção.md)                                                                                | Não          |
| <a id="rf24-v2"></a> **RF24-v2**         | Consulta de status de Benefícios            | Permitir ao usuário a visualização dos benefícios disponíveis para liberação e pendências para liberação dos benefícios.                                                                       | [ENT01](tecnicas/entrevista.md)                                                                                 | Sim          |
| <a id="rf25"></a>    **RF25**            | Informações Cadastrais                      | Visualização de informações cadastrais                                                                                                                                                         | [ENT02](tecnicas/entrevista.md)                                                                                 | Sim          |
| <a id="rf26"></a>    **RF26**            | Chatbot de atendimento automatizado         | Implementa um chatbot para atendimento automatizado ao usuário.                                                                                                                                | [IS12](tecnicas/introspecção.md)                                                                                | Não          |
| <a id="rf27"></a>    **RF27**            | Notificação de pendências ou atualizações   | Envia notificações sobre pendências ou atualizações necessárias ao usuário.                                                                                                                    | [IS13](tecnicas/introspecção.md)                                                                                | Não          |
| <a id="rf28-v2"></a> **RF28-v2**         | Simulador de benefícios sociais             | Permite ao usuário simular quais benefícios sociais poderia receber após processamento do sistema e conclusão de procedimentos burocráticos                                                    | [IS14](tecnicas/introspecção.md)/[ENT09](tecnicas/entrevista.md)                                                                                | Não          |
| <a id="rf29"></a>    **RF29**            | Upload de documentos                        | Permite ao usuário fazer upload de documentos para o sistema.                                                                                                                                  | [IS11](tecnicas/introspecção.md)                                                                                | Não          |
| <a id="rf30"></a>    **RF30**            | Agendamento de atendimento no CRAS          | Agendamento de atendimentos no CRAS pelo app                                                                                                                                                   | [ENT06](tecnicas/entrevista.md)                                                                                 | Não          |
| <a id="rf31"></a>    **RF31**            | Notificações Personalizadas                 | Notificações personalizadas (pendências, atualizações, confirmações)                                                                                                                           | [ENT07](tecnicas/entrevista.md)                                                                                 | Não          |
| <a id="rf32-v2"></a> **RF32-v2**         | Guia de Atualização Cadastral               | O sistema deve conter um guia de como realizar a Atualização Cadastral do Usuário                                                                                                              | [ENT08](tecnicas/entrevista.md)                                                                                 | Não          |
| <a id="rf34"></a>    **RF34**            | Chat de Atendimento                         | Chat de atendimento ao usuário                                                                                                                                                                 | [ENT10](tecnicas/entrevista.md)                                                                                 | Não          |
| <a id="rf35"></a>    **RF35**            | Tutoriais Interativos                       | Tutoriais interativos para guiar tarefas críticas                                                                                                                                              | [ENT03](tecnicas/entrevista.md)                                                                                 | Não          |
| <a id="rf36"></a>    **RF36**            | Vídeos Explicativos                         | Vídeos explicativos dentro do app                                                                                                                                                              | [ENT04](tecnicas/entrevista.md)                                                                                 | Não          |
| <a id="rf37"></a>    **RF37**            | Assistência por Voz                         | Ferramenta de assistência por voz para usuários necessitados                                                                                                                                   | [ENT05](tecnicas/entrevista.md)                                                                                 | Não          |
| <a id="rf38"></a>    **RF38**            | Modo escuro                                 | O aplicativo oferece uma opção de modo escuro para melhorar a experiência do usuário em ambientes com pouca luz.                                                                               | [IS15](tecnicas/introspecção.md)                                                                                | Não          |
| <a id="rf40-v2"></a> **RF40-v2**         | Login                                       | Permitir que o usuário realize o processo de login, no qual ele será reconhecido pelo sistema de acordo com informações previamente cadastradas mediante cpf e senha de acesso                 | [EU_38](../modelagem/agil/historia_de_usuario.md)                                                               | Sim          |                                                                                                              | Sim          |

<center>
    Autor(es): 
    <a href="https://github.com/RA-Salles" target="_blank">Ryan Salles</a>, 
    <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a>
</center>

Após a refatoração dos requisitos e agrupamento de duplicatas, 36 requisitos sobraram.

## Requisitos Não Funcionais

### Primeira Versão
Essa seção apresenta a primeira versão dos requisitos não funcionais elicitados por meio da Tabela 3.

<!--Tip: deacivate word wrap with ALT+Z on VsCode. It helps greatly. Word Wrap f's up them tabbles, every table!!! !!1-->

<center>
    <b>Tabela 3:</b> Requisitos Não Funcionais elicitados, Primeira Versão
</center>

| ID                                        | Nome                                               | Descrição                                                                                                                                                                             | Rastreabilidade                                                                                      | Implementado | 
| :---------------------------------------: | :------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------: | :----------: |
| [RNF01](tecnicas/analise_documentacao.md) | Desempenho                                         | Garantir o processamento dos dados e retorno aos municípios em até 48 horas e resposta rápida nas interações do usuário (até 3 segundos).                                             | [AD15](tecnicas/analise_documentacao.md) / [IS22](tecnicas/introspecção.md)                          | Não          |
| [RNF02](tecnicas/analise_documentacao.md) | Segurança                                          | Garantir a confidencialidade dos dados por meio de termos de responsabilidade e acordos de cooperação técnica, além de implementar mecanismos de autenticação para acesso aos dados.  | [AD16](tecnicas/analise_documentacao.md) / [IS02](tecnicas/introspecção.md)                          | Sim          |
| [RNF03](tecnicas/analise_documentacao.md) | Escalabilidade                                     | Suportar o cadastro e atualização de dados de até 19,5 milhões de famílias.                                                                                                           | [AD17](tecnicas/analise_documentacao.md) / [QST08](tecnicas/questionario.md)                         | Sim          |
| [RNF04](tecnicas/analise_documentacao.md) | Conformidade Legal                                 | Atender às regulamentações definidas pela Senarc e portarias relacionadas.                                                                                                            | [AD18](tecnicas/analise_documentacao.md) / [QST09](tecnicas/questionario.md)                         | Sim          |
| [RNF05](tecnicas/analise_documentacao.md) | Acessibilidade                                     | Garantir que o sistema seja acessível para operadores municipais e estaduais.                                                                                                         | [AD19](tecnicas/analise_documentacao.md) / [QST10](tecnicas/questionario.md)                         | Não          |
| [RNF06](tecnicas/analise_documentacao.md) | Disponibilidade                                    | Garantir que o sistema esteja disponível para uso diário.                                                                                                                             | [AD20](tecnicas/analise_documentacao.md) / [QST11](tecnicas/questionario.md)                         | Sim          |
| [RNF07](tecnicas/analise_documentacao.md) | Compatibilidade com Aplicativo Off-line            | O sistema deve ser compatível com o aplicativo off-line utilizado pelos municípios para coleta e digitação de dados.                                                                  | [AD21](tecnicas/analise_documentacao.md) / [QST12](tecnicas/questionario.md)                         | Não          |
| [RNF08](tecnicas/analise_documentacao.md) | Transmissão via Conectividade Social               | A transmissão de dados deve ser realizada exclusivamente por meio da ferramenta Conectividade Social da CAIXA.                                                                        | [AD22](tecnicas/analise_documentacao.md) / [QST13](tecnicas/questionario.md)                         | Não          |
| [RNF09](tecnicas/analise_documentacao.md) | Acesso Restrito                                    | O acesso à base de dados deve ser restrito a instituições autorizadas e mediante assinatura de termos específicos.                                                                    | [AD23](tecnicas/analise_documentacao.md)                                                             | Sim          |
| [RNF10](tecnicas/introspecção.md)         | Interface intuitiva e amigável                     | O design do aplicativo é simples e de fácil navegação.                                                                                                                                | [IS16](tecnicas/introspecção.md), [ENT11, ENT12](tecnicas/entrevista.md)                             | Sim          |
| [RNF11](tecnicas/introspecção.md)         | Suporte a grande base de usuários                  | Suporta um grande número de acessos simultâneos.                                                                                                                                      | [IS17](tecnicas/introspecção.md)                                                                     | Sim          |
| [RNF12](tecnicas/introspecção.md)         | Integração com sistemas oficiais                   | Integrado com sistemas como o CNIS.                                                                                                                                                   | [IS18](tecnicas/introspecção.md)                                                                     | Sim          |
| [RNF13](tecnicas/introspecção.md)         | Usabilidade                                        | Navegação intuitiva e acessibilidade geral.                                                                                                                                           | [IS19](tecnicas/introspecção.md)                                                                     | Não          |
| [RNF14](tecnicas/introspecção.md)         | Compatibilidade com Dispositivos                   | Compatível com Android e iOS.                                                                                                                                                         | [IS22](tecnicas/introspecção.md)                                                                     | Sim          | 
| [RNF15](tecnicas/introspecção.md)         | Acessibilidade para pessoas com deficiência visual | O aplicativo oferece recursos de acessibilidade para deficientes visuais, como leitores de tela.                                                                                      | [IS25](tecnicas/introspecção.md)                                                                     | Não          |
| [RNF16](tecnicas/introspecção.md)         | Backup e restauração de sessão                     | O aplicativo deve permitir backup e restauração das sessões do usuário, caso haja interrupção ou falha.                                                                               | [IS26](tecnicas/introspecção.md)                                                                     | Não          |
| [RNF17](tecnicas/introspecção.md)         | Alta disponibilidade e recuperação de desastres    | O aplicativo deve ter mecanismos de recuperação de dados e funcionamento em caso de falhas ou desastres.                                                                              | [IS24](tecnicas/introspecção.md)                                                                     | Não          |
| [RNF18](tecnicas/introspecção.md)         | Possibilidade de outros idiomas                    | O aplicativo deve estar disponível em vários idiomas, permitindo maior acessibilidade.                                                                                                | [IS27](tecnicas/introspecção.md)                                                                     | Não          |

<center>
    Autor(es): 
    <a href="https://github.com/RA-Salles" target="_blank">Ryan Salles</a>, 
    <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a>
</center>

### Segunda Versão

Por meio da tabela 4, a segunda versão dos requisitos não funcionais elicitados é apresentada.

Utilizando o mesmo padrão geral e filosofia de versionamento observado para os requisitos funcionais, 
os requisitos não funcionais elicitados também passaram por refatoração e subsequente versionamento onde necessário. 

As mudanças específicas foram as seguintes:
- Título do requisito 5 alterado para melhor refletir sua descrição
- Por possuírem descrições similares, o requisito funcional 18, o qual foi inicialmente 
movido para os requisitos não funcionais, foi mesclado ao requisito não funcional 12.
Como consequência, o requisito não funcional "recém criado" 19 foi excluído por duplicação.
O requisito não funcional 12 também teve sua descrição atualizada para refletir essa mescla.

Legenda
- RNFX-v2: requisito não funcional número X, versão 2.

<center>
    <b>Tabela 4:</b> Requisitos Não Funcionais elicitados, Segunda Versão
</center>

| ID                                        | Nome                                               | Descrição                                                                                                                                                                             | Rastreabilidade                                                                                      | Implementado | 
| :---------------------------------------: | :------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------: | :----------: |
| <a id="rnf01"></a>   **RNF01**            | Desempenho                                         | Garantir o processamento dos dados e retorno aos municípios em até 48 horas e resposta rápida nas interações do usuário (até 3 segundos).                                             | [AD15](tecnicas/analise_documentacao.md) / [IS22](tecnicas/introspecção.md)                          | Não          |
| <a id="rnf02"></a>   **RNF02**            | Segurança                                          | Garantir a confidencialidade dos dados por meio de termos de responsabilidade e acordos de cooperação técnica, além de implementar mecanismos de autenticação para acesso aos dados.  | [AD16](tecnicas/analise_documentacao.md) / [IS02](tecnicas/introspecção.md)                          | Sim          |
| <a id="rnf03"></a>   **RNF03**            | Escalabilidade                                     | Suportar o cadastro e atualização de dados de até 19,5 milhões de famílias.                                                                                                           | [AD17](tecnicas/analise_documentacao.md) / [QST08](tecnicas/questionario.md)                         | Sim          |
| <a id="rnf04"></a>   **RNF04**            | Conformidade Legal                                 | Atender às regulamentações definidas pela Senarc e portarias relacionadas.                                                                                                            | [AD18](tecnicas/analise_documentacao.md) / [QST09](tecnicas/questionario.md)                         | Sim          |
| <a id="rnf05-v2"></a>**RNF05-v2**         | Acessibilidade para operadores                     | Garantir que o sistema seja acessível para operadores municipais e estaduais.                                                                                                         | [AD19](tecnicas/analise_documentacao.md) / [QST10](tecnicas/questionario.md)                         | Não          |
| <a id="rnf06"></a>   **RNF06**            | Disponibilidade                                    | Garantir que o sistema esteja disponível para uso diário.                                                                                                                             | [AD20](tecnicas/analise_documentacao.md) / [QST11](tecnicas/questionario.md)                         | Sim          |
| <a id="rnf07"></a>   **RNF07**            | Compatibilidade com Aplicativo Off-line            | O sistema deve ser compatível com o aplicativo off-line utilizado pelos municípios para coleta e digitação de dados.                                                                  | [AD21](tecnicas/analise_documentacao.md) / [QST12](tecnicas/questionario.md)                         | Não          |
| <a id="rnf08"></a>   **RNF08**            | Transmissão via Conectividade Social               | A transmissão de dados deve ser realizada exclusivamente por meio da ferramenta Conectividade Social da CAIXA.                                                                        | [AD22](tecnicas/analise_documentacao.md) / [QST13](tecnicas/questionario.md)                         | Não          |
| <a id="rnf09"></a>   **RNF09**            | Acesso Restrito                                    | O acesso à base de dados deve ser restrito a instituições autorizadas e mediante assinatura de termos específicos.                                                                    | [AD23](tecnicas/analise_documentacao.md)                                                             | Sim          |
| <a id="rnf10"></a>   **RNF10**            | Interface intuitiva e amigável                     | O design do aplicativo é simples e de fácil navegação.                                                                                                                                | [IS16](tecnicas/introspecção.md), [ENT11, ENT12](tecnicas/entrevista.md)                             | Sim          |
| <a id="rnf11"></a>   **RNF11**            | Suporte a grande base de usuários                  | Garantir que comportamento estável do sistema mediante acesso simultâneo de base de usuários em pico de uso.                                                                          | [IS17](tecnicas/introspecção.md)                                                                     | Sim          |
| <a id="rnf12-v2"></a>**RNF12-v2**         | Integração com sistemas oficiais                   | Integrado com sistemas como o CNIS, trazendo dados de vínculos e contribuições automaticamente.                                                                                       | [IS18](tecnicas/introspecção.md) /  [IS05](tecnicas/introspecção.md)                                 | Sim          |
| <a id="rnf13"></a>   **RNF13**            | Usabilidade                                        | Navegação intuitiva e acessibilidade geral.                                                                                                                                           | [IS19](tecnicas/introspecção.md)                                                                     | Não          |
| <a id="rnf14"></a>   **RNF14**            | Compatibilidade com Dispositivos                   | Compatível com Android e iOS.                                                                                                                                                         | [IS22](tecnicas/introspecção.md)                                                                     | Sim          | 
| <a id="rnf15"></a>   **RNF15**            | Acessibilidade para pessoas com deficiência visual | O aplicativo oferece recursos de acessibilidade para deficientes visuais, como leitores de tela.                                                                                      | [IS25](tecnicas/introspecção.md)                                                                     | Não          |
| <a id="rnf16"></a>   **RNF16**            | Backup e restauração de sessão                     | O aplicativo deve permitir backup e restauração das sessões do usuário, caso haja interrupção ou falha.                                                                               | [IS26](tecnicas/introspecção.md)                                                                     | Não          |
| <a id="rnf17"></a>   **RNF17**            | Alta disponibilidade e recuperação de desastres    | O aplicativo deve ter mecanismos de recuperação de dados e funcionamento em caso de falhas ou desastres.                                                                              | [IS24](tecnicas/introspecção.md)                                                                     | Não          |
| <a id="rnf18"></a>   **RNF18**            | Possibilidade de outros idiomas                    | O aplicativo deve estar disponível em vários idiomas, permitindo maior acessibilidade.                                                                                                | [IS27](tecnicas/introspecção.md)                                                                     | Não          |
| <a id="rnf19"></a>   **RNF19**            | Integração MEI                                     | Permitir que o sistema converse com demais sistemas para MEIs.                                                                                                                        | [AD14](tecnicas/analise_documentacao.md)                                                             | Não          |          
| <a id="rnf20"></a>   **RNF20**            | Integração com o GOV.br                            | Permitir que o sistema realize interface com os sistemas GOV.br para facilidade de autenticação e simplificação do processo de segurança do usuário                                   | [EU_38](../modelagem/agil/historia_de_usuario.md)                                                    | Sim          |                                                                                                              | Sim          |



<center>
    Autor(es): 
    <a href="https://github.com/RA-Salles" target="_blank">Ryan Salles</a>, 
    <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a>
</center>



| Versão  | Data       | Descrição                                                                                                                          | Autor                                              | Revisor                                                                                            |
| :-----: | :--------: | :--------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------: | :------------------------------------------------------------------------------------------------: |           
| 1.0     | 04/05/2025 | Criação do Documento de Requisitos Elicitados                                                                                      | [Ryan Salles](https://github.com/RA-Salles)        | [João Pedro Costa](https://github.com/johnaopedro)                                                 |
| 1.1     | 13/05/2025 | Padronização, formatação e mesclagem com documento de requisitos desejáveis                                                        | [Ryan Salles](https://github.com/RA-Salles)        | [João Pedro Costa](https://github.com/johnaopedro)                                                 |
| 1.2     | 22/05/2025 | Adicionando hyperlinks nos requisitos para direcioná-los as técnicas em que foram elicitados                                       | [João Pedro Costa](https://github.com/johnaopedro) | [Julia Paulino](https://github.com/JuliaGabP)                                                      |
| 1.3     | 27/05/2025 | Formatação de tabelas, inserção de coluna descrição dos requisitos RF01-08 e RNF01-08, adição de tabela de autorias                | [Ryan Salles](https://github.com/RA-Salles)        | [Julia Paulino](https://github.com/JuliaGabP)                                                      |
| 2.0     | 29/05/2025 | Restante das descrições atualizadas. Rastreabilidade melhorada.                                                                    | [Ryan Salles](https://github.com/RA-Salles)        | [João Pedro Costa](https://github.com/johnaopedro), [Julia Paulino](https://github.com/JuliaGabP)  |
| 2.1     | 29/05/2025 | Rastreabilidade melhorada. Alterando nomes de requisitos com conflito de nome                                                      | [Ryan Salles](https://github.com/RA-Salles)        | [João Pedro Costa](https://github.com/johnaopedro), [Julia Paulino](https://github.com/JuliaGabP)  |
| 2.2     | 06/05/2025 | Adicionando RF41. Rastreabilidade dos requisitos do questionário completada! Movendo funções dos autores para antes da introdução. | [Ryan Salles](https://github.com/RA-Salles)        | [João Pedro Costa](https://github.com/johnaopedro)                                                 |                                         
| 2.3     | 02/07/2025 | Melhora de links para rastreabilidade, refatorando requisitos.                                                                     | [Ryan Salles](https://github.com/RA-Salles)        | [João Pedro Costa](https://github.com/johnaopedro)                                                 |
