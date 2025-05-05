# Requisitos desejáveis

Nesta seção, são apresentados os requisitos desejáveis identificados na introspecção e na entrevista. Os requisitos desejáveis são aqueles que não foram identificados como não implementados nas determinadas tecnicas de elicitação.

## Requisitos desejaveis identificados na introspecção:

### Requisitos Funcionais Desejáveis

| RF    | Nome do RF                                | Descrição                                                                 |
|-------|-------------------------------------------|---------------------------------------------------------------------------|
| RF06  | Chatbot de atendimento automatizado       | Implementa um chatbot para atendimento automatizado ao usuário.          |
| RF07  | Notificação de pendências ou atualizações | Envia notificações sobre pendências ou atualizações necessárias ao usuário.|
| RF08  | Simulador de benefícios sociais          | Permite ao usuário simular quais benefícios sociais poderia receber.      |
| RF09  | Upload de documentos                     | Permite ao usuário fazer upload de documentos para o sistema.            |
| RF10  | Agendamento de atendimento no CRAS       | Possibilita o agendamento de atendimento nos postos de CRAS.             |
<center>
    Autor(es): <a href="https://github.com/JuliaGabP" target="_blank">Julia Gabriela</a>
</center>

### Requisitos Não Funcionais Desejáveis

| RNF   | Nome do RNF                              | Descrição                                                                 |
|-------|------------------------------------------|---------------------------------------------------------------------------|
| RNF04 | Acessibilidade para pessoas com deficiência visual | O aplicativo oferece recursos de acessibilidade para deficientes visuais, como leitores de tela. |
| RNF05 | Desempenho otimizado para internet limitada | O aplicativo oferece desempenho otimizado para conexões de internet mais lentas.|
| RNF06 | Possibilidade de outros idiomas          | O aplicativo deve estar disponível em vários idiomas, permitindo maior acessibilidade. |
| RNF07 | Backup e restauração de sessão           | O aplicativo deve permitir backup e restauração das sessões do usuário, caso haja interrupção ou falha.|
| RNF08 | Modo escuro                              | O aplicativo oferece uma opção de modo escuro para melhorar a experiência do usuário em ambientes com pouca luz. |
| RNF09 | Alta disponibilidade e recuperação de desastres | O aplicativo deve ter mecanismos de recuperação de dados e funcionamento em caso de falhas ou desastres. |
<center>
    Autor(es): <a href="https://github.com/JuliaGabP" target="_blank">Julia Gabriela</a>
</center>

## Requisitos desejáveis identificados na entrevista:

### Requisitos Funcionais Desejáveis

| ID       | Nome do Requisito               | Tipo            | Descrição                                      | Trecho original                                                                 |
|----------|---------------------------------|-----------------|------------------------------------------------|---------------------------------------------------------------------------------|
| RF-D01   | Agendamento no CRAS            | Funcional       | Agendamento de atendimentos no CRAS pelo app   | “ausência de funcionalidades … que permitam o agendamento direto … foi apontada como uma limitação importante.” |
| RF-D02   | Notificações Personalizadas    | Funcional       | Notificações personalizadas (pendências, atualizações, confirmações) | “Notificações personalizadas: Informações sobre pendências no cadastro, atualizações de programas sociais e confirmação de agendamentos.” |
| RF-D03   | Atualização Cadastral          | Funcional       | Passo a passo claro para atualização cadastral | “confusão quanto à documentação necessária … ausência de um passo a passo objetivo para realização dessas ações …” |
| RF-D04   | Simulador de Benefícios        | Funcional       | Simulador de elegibilidade para benefícios     | “Simuladores de elegibilidade para benefícios sociais”                          |
| RF-D05   | Chat de Atendimento            | Funcional       | Chat de atendimento ao usuário                 | “chat de atendimento”                                                          |

### Requisitos Não Funcionais Desejáveis

| ID       | Nome do Requisito               | Tipo            | Descrição                                      | Trecho original                                                                 |
|----------|---------------------------------|-----------------|------------------------------------------------|---------------------------------------------------------------------------------|
| RNF-D01  | Tutoriais Interativos          | Não funcional   | Tutoriais interativos para guiar tarefas críticas | “Inclusão de tutoriais interativos, orientações em vídeo e ferramentas de assistência por voz.” |
| RNF-D02  | Vídeos Explicativos            | Não funcional   | Vídeos explicativos dentro do app              | “Inclusão de tutoriais interativos, orientações em vídeo e ferramentas de assistência por voz.” |
| RNF-D03  | Assistência por Voz            | Não funcional   | Ferramenta de assistência por voz para usuários necessitados | “Inclusão de tutoriais interativos, orientações em vídeo e ferramentas de assistência por voz.” |
<center>
    Autor(es): <a href="https://github.com/mandicrz" target="_blank">Amanda Cruz</a>, <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a>, <a href="https://github.com/JuliaGabP" target="_blank">Julia Gabriela</a>
</center>

## Referências

> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021)Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1. Item: 7.5.4, Acesso em: 04/05/2025.

> GOGUEN, Joseph A.; LINDE, Charlotte. Techniques for Requirements Elicitation. In: IEEE International Symposium on Requirements Engineering, 1993. p. 152-164. Acesso em: 04/05/2025.

## Histórico de Versões

| Versão | Data | Descrição  | Autor        | Revisor |
| :-----: | :----: | :----------: | :------------: | :--------: |
| 1.0    | 04/05/2025 | Adicionando requisitos desejáveis e tabelas removidas das outras documentações | [João Pedro Costa](https://github.com/johnaopedro)                   | [Ryan Salles](https://github.com/RA-Salles)                      |