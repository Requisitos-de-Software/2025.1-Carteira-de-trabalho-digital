# Inspeção Fagan – Etapa 1

## Funções dos autores

| Nome                                              | Função                                                                  | 
|---------------------------------------------------|-------------------------------------------------------------------------|
|[João Pedro Costa](https://github.com/johnaopedro) |Criação da página; Desenvolvimento da introdução; Criação das tabelas; Criação do template da inspeção pelo metodo de Fagan; Desenvolvimento de todas as inspeções. | 
|[Ryan Salles](https://github.com/RA-Salles)        |Revisão geral.                                                           | 
<center>
    Autor(es): 
    <a href="https://github.com/johnaopedro" target="_blank">João Pedro Costa</a>
</center>

## Introdução

A inspeção Fagan é uma técnica formal de revisão de artefatos desenvolvida por M. E. Fagan na IBM em 1976. É um processo estruturado que pode identificar e eliminar aproximadamente 80% dos defeitos durante o desenvolvimento de software, além de reduzir custos e prazos em cerca de 30%. O processo é composto por seis etapas fundamentais: Planejamento, Visão Geral, Preparação (com checklist), Reunião de Inspeção, Retrabalho e Follow-up.

### Benefícios da Inspeção Fagan

- Redução significativa de defeitos reportados pelos usuários
- Aumento da satisfação do cliente
- Maior produtividade no desenvolvimento
- Melhor cumprimento de cronogramas
- Treinamento cruzado rápido de desenvolvedores e mantenedores
- Melhoria contínua do processo através da remoção de defeitos sistêmicos
- Aprendizado rápido dos autores para evitar criar defeitos
- Construção de equipe mais coesa

## Metodologia

O processo de inspeção Fagan segue uma estrutura rigorosa que visa maximizar a detecção e correção de defeitos. Esta metodologia requer uma definição clara do estado do produto de trabalho a ser inspecionado, com participantes assumindo papéis bem definidos durante todo o processo. É essencial que seja dedicado tempo adequado para a preparação dos inspetores, que utilizam checklists específicos para guiar sua análise. O processo estabelece critérios claros de entrada e saída, garantindo que cada etapa seja concluída adequadamente antes de prosseguir. Toda a inspeção é devidamente documentada, incluindo a coleta de dados relevantes, e são estabelecidos procedimentos claros para o retrabalho e sua verificação.

Para os artefatos de planejamento, nossa inspeção terá um foco especial na verificação da completude e consistência do cronograma, na adequação das ferramentas escolhidas, na clareza da metodologia definida e na viabilidade do planejamento como um todo. Aspectos como a distribuição equilibrada de tarefas, a definição clara de responsabilidades e a adequação dos prazos estabelecidos serão cuidadosamente analisados. Também será dada atenção especial à integração entre diferentes elementos do planejamento, como a relação entre o cronograma e o heatmap de disponibilidade da equipe.

### Processo de Inspeção

O processo de inspeção Fagan é rigorosamente estruturado e requer:
1. Definição clara do estado do produto de trabalho a ser inspecionado
2. Participantes com papéis bem definidos
3. Tempo adequado de preparação para os inspetores
4. Checklists específicos para guiar a inspeção
5. Critérios de entrada e saída bem estabelecidos
6. Documentação apropriada e coleta de dados
7. Procedimentos claros para retrabalho e verificação

---

### **Inspeção Fagan: Artefato 1/7 - `Pagina Inicial`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Título do projeto, imagem do logo do aplicativo, introdução geral, descrição do aplicativo, tabela de apresentação da equipe com links para o GitHub, referências bibliográficas e histórico de versão.
*   **Objetivo Principal:** Servir como a página de entrada (homepage) da documentação do projeto, fornecendo uma visão geral, contextualizando o aplicativo estudado e apresentando a equipe de desenvolvimento.
*   **Materiais Complementares:**
    *   `mkdocs.yml`: Para validar a correta referenciação do `Pagina Inicial` como página principal.
    *   Padrões de Documentação do Projeto: Para verificar a conformidade do histórico de versão e do formato das referências.
    *   Lista oficial de membros da equipe: Para validar nomes e links do GitHub.
*   **Simulação de Participantes:**
    *   **Moderador:** Ryan Salles
    *   **Autor:** João Pedro Costa
    *   **Leitor:** Amanda Cruz
    *   **Inspetor:** Gabriel Flores
*   **Simulação de Agenda:**
    *   **Data:** 21/06/2025
    *   **Horário:** 19:00 - 19:30
    *   **Pauta:** Revisão formal do artefato `Pagina Inicial`.

#### 2. Visão Geral

*   **Resumo Técnico:** A `Pagina Inicial` é o documento raiz da documentação e estrutura-se em Markdown. Ele integra elementos visuais (`<img>`), links externos, uma tabela HTML para apresentar a equipe e seções textuais que contextualizam o projeto. Sua principal função é orientar o leitor sobre o propósito e a autoria do trabalho.
*   **Contexto no Projeto:** Este artefato é a "porta de entrada" para qualquer pessoa que acesse a documentação. Sua clareza, correção e profissionalismo são cruciais, pois estabelecem a primeira impressão sobre a qualidade e a organização de todo o projeto.
*   **Papéis e Responsabilidades:**
    *   **Moderador (Ryan):** Assegurar que a inspeção seja produtiva, mantenha o foco nos defeitos e cumpra a agenda.
    *   **Autor (João Pedro):** Prestar esclarecimentos sobre as escolhas de conteúdo e formato.
    *   **Leitor (Amanda):** Ler o documento em voz alta durante a reunião para identificar problemas de fluidez, erros de digitação e frases ambíguas.
    *   **Inspetor (Gabriel):** Realizar uma análise crítica, focando em defeitos técnicos, violações de padrão e omissões de conteúdo.

#### 3. Checklist de Verificação
- [ ] O título do projeto está correto e padronizado?
- [ ] O logo está visível e com texto alternativo descritivo?
- [ ] A introdução contextualiza adequadamente o projeto?
- [ ] A tabela de equipe está completa, com nomes e links corretos?
- [ ] As referências bibliográficas estão no formato padrão?
- [ ] O histórico de versão está atualizado e padronizado?
- [ ] Não há erros ortográficos ou de digitação?
- [ ] A formatação segue o padrão Markdown?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Defeito Técnico (Inconsistência):** O link na fonte da Figura 1 está quebrado devido a um erro de digitação (`hhttps://...`).
    *   **Defeito de Escrita (Ortografia):** O título da seção de referências contém um erro de digitação: "Referências Bibligráficas". O correto é "Referências Bibliográficas".
    *   **Violação de Padrão (Formatação):** A autoria do documento é apresentada em uma tag `<p align="center">`, enquanto outros artefatos utilizam uma combinação de `<center>` e `<h6>` ou apenas Markdown. Falta um padrão definido.
    *   **Violação de Padrão (Datas):** O formato da data na referência ("30 abr. 2025") é inconsistente com outros documentos que usam o mês por extenso ("12 de Abril de 2025").
    *   **Omissão (Conteúdo):** A descrição do aplicativo é genérica. Faltam detalhes sobre o público-alvo (cidadãos, gestores) e o valor principal que ele entrega, o que ajudaria a contextualizar melhor o estudo de requisitos.
*   **Perguntas Críticas Preparadas:**
    *   "O link da fonte da imagem foi testado antes da submissão do documento?"
    *   "Qual é o padrão de formatação para autoria e legendas que devemos seguir em todo o projeto? Markdown puro ou HTML?"
    *   "A descrição atual do aplicativo é suficiente para que um leitor externo entenda seu propósito central e a relevância do nosso estudo de requisitos?"

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Código fonte/documento marcado com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção do `Pagina Inicial`**
    *   **Data:** 21/06/2025
    *   **Participantes:** Ryan Salles, Gabriel Flores, Amanda Cruz, João Pedro Costa.
    *   **Defeitos Logados:**
        1.  **ID 01-IDX (Técnico):** Link inválido na fonte da Figura 1.
            *   *Observação do Inspetor:* "Defeito de criticidade baixa, mas que afeta diretamente a rastreabilidade da fonte. A correção é trivial."
        2.  **ID 02-IDX (Ortográfico):** Erro de digitação em "Referências Bibliográficas".
            *   *Observação da Leitora:* "O erro foi percebido durante a leitura em voz alta. Reduz a percepção de qualidade do documento."
        3.  **ID 03-IDX (Padronização):** Falta de consistência na formatação de autoria e datas.
            *   *Observação do Moderador:* "Este é um problema recorrente. Fica decidido que o padrão será **Markdown puro** para formatação e datas no formato 'DD de [mês por extenso] de AAAA'."
    *   **Decisões:** O autor (Gabriel Flores) é responsável por aplicar todas as correções. O padrão de formatação e data definido pelo moderador deve ser comunicado a toda a equipe para aplicação nos demais artefatos.

#### 6. Retrabalho

*   **Defeito ID 01-IDX:**
    *   **Correção Proposta:** Alterar `(hhttps://www.gov.br/pt-br/apps/cad)` para `(https://www.gov.br/pt-br/apps/cad)`.
    *   **Impacto da Não Correção:** Perda de credibilidade e impossibilidade de verificação da fonte da imagem.
    *   **Ação:** Autor deve corrigir o hiperlink.
    *   **Reinspeção:** Não necessária.
*   **Defeito ID 02-IDX:**
    *   **Correção Proposta:** Alterar `## Referências Bibligráficas` para `## Referências Bibliográficas`.
    *   **Impacto da Não Correção:** Reduz o profissionalismo e a qualidade percebida do documento.
    *   **Ação:** Autor deve corrigir o título da seção.
    *   **Reinspeção:** Não necessária.
*   **Defeito ID 03-IDX:**
    *   **Correção Proposta:** Substituir tags HTML por Markdown e padronizar a data da referência para "30 de abril de 2025".
    *   **Impacto da Não Correção:** Gera inconsistência visual e estrutural em toda a documentação, dificultando a manutenção automatizada.
    *   **Ação:** Autor deve refatorar a formatação e a data conforme o padrão definido.
    *   **Reinspeção:** Não necessária para este artefato, mas a aplicação do padrão será verificada nos demais.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Caso necessário, uma nova reinspeção será agendada.

*   **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados e categorizados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada e registrada
    - Relatório de inspeção foi finalizado e aprovado pelos participantes

---

### **Inspeção Fagan: Artefato 2/7 - `docs/planejamento/cronograma.md`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Introdução, tabelas de cronograma planejado para 6 entregas (com atividades, prazos, responsáveis e revisores), referências e histórico de versão.
*   **Objetivo Principal:** Documentar e comunicar o plano inicial de atividades do projeto, servindo como guia mestre para a execução e o gerenciamento das tarefas da equipe.
*   **Materiais Complementares:**
    *   Plano de Ensino da disciplina (para validar as datas macro).
    *   `heatmap.md`: Para cruzar informações e avaliar se os prazos são realistas frente à disponibilidade da equipe.
    *   `cronograma_executado.md`: Para análise comparativa posterior.
*   **Simulação de Participantes:**
    *   **Moderador:** João Pedro Costa
    *   **Autora:** Julia Gabriela
    *   **Leitor:** João Igor
    *   **Inspetor:** Ryan Salles
*   **Simulação de Agenda:**
    *   **Data:** 21/06/2025
    *   **Horário:** 19:30 - 20:00
    *   **Pauta:** Revisão formal do artefato `cronograma.md`.

#### 2. Visão Geral

*   **Resumo Técnico:** O documento estrutura o planejamento do projeto em tabelas Markdown. Cada tabela representa uma entrega e detalha as tarefas, os períodos de desenvolvimento/revisão e os membros da equipe alocados. É um artefato gerencial crítico.
*   **Contexto no Projeto:** É a espinha dorsal do planejamento. Erros, omissões ou ambiguidades neste documento têm um impacto direto na produtividade da equipe, podendo causar atrasos, sobrecarga de trabalho e falhas na entrega de artefatos.
*   **Papéis e Responsabilidades:**
    *   **Moderador (João Pedro):** Focar a discussão em pontos críticos, como a clareza das atividades e a distribuição de responsabilidades.
    *   **Autora (Julia):** Justificar as decisões de alocação de prazos e recursos humanos.
    *   **Leitor (João Igor):** Ler as atividades para identificar descrições vagas ou possíveis conflitos de prazo.
    *   **Inspetor (Ryan):** Analisar a lógica do cronograma, a viabilidade dos prazos e a consistência com as boas práticas de gerenciamento.

#### 3. Checklist de Verificação
- [ ] Todas as entregas e atividades estão listadas?
- [ ] Os prazos são realistas e consistentes?
- [ ] Os responsáveis estão claramente definidos (sem uso de "TODOS")?
- [ ] A coluna de revisão está clara quanto ao prazo?
- [ ] O histórico de versão está padronizado?
- [ ] Não há erros de formatação ou uso de HTML?
- [ ] Não há erros ortográficos?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Ambiguidade (Gerencial):** Várias tarefas (ex: "Escolha do aplicativo", "Lista de verificação") são atribuídas a "TODOS". Isso dilui a responsabilidade e torna incerto quem é o ponto focal para a conclusão da tarefa.
    *   **Omissão (Clareza):** A coluna "Revisão" apresenta um período de tempo, mas não define se é o prazo final para o revisor ou o intervalo em que a revisão deve ocorrer. Essa falta de clareza pode gerar desalinhamento.
    *   **Violação de Padrão (Formatação):** Uso de tags `<center>` e `<h6>` para legendas e autoria, o que viola o padrão de "Markdown puro" que deve ser adotado.
    *   **Violação de Padrão (Nomenclatura):** Inconsistência na forma como os nomes dos membros são registrados no histórico de versão (ex: "Ryan" vs. "Ryan Augusto"), o que prejudica a padronização.
    *   **Risco (Gerencial):** A atividade "Brainstorm" listada na Entrega 2 não tem um correspondente no `cronograma_executado.md`. Embora divergências entre planejado e executado sejam normais, o registro de atividades que não geram artefatos tangíveis pode ser simplificado.
*   **Perguntas Críticas Preparadas:**
    *   "Como podemos garantir que uma tarefa atribuída a 'TODOS' seja efetivamente concluída? Não deveríamos definir um 'dono' para cada uma?"
    *   "O que exatamente o 'Período de Revisão' significa? É o prazo final para o revisor entregar a revisão?"
    *   "A carga de trabalho está distribuída de forma equilibrada? Algumas entregas parecem concentrar muitas atividades em poucos membros."

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Código fonte/documento marcado com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção do `cronograma.md`**
    *   **Data:** 21/06/2025
    *   **Participantes:** João Pedro Costa, Julia Gabriela, João Igor, Ryan Salles.
    *   **Defeitos Logados:**
        1.  **ID 01-CRO (Semântico):** Ambiguidade na atribuição de responsabilidades com o uso de "TODOS".
            *   *Observação do Inspetor:* "Esta é uma antiprática em gerenciamento de projetos. É mandatório definir um responsável único (dono da tarefa) para garantir o accountability."
        2.  **ID 02-CRO (Padronização):** Uso de formatação HTML (`<center>`, `<h6>`).
            *   *Observação do Moderador:* "Reitero a decisão da inspeção anterior. Todo o HTML de formatação deve ser removido em favor de Markdown."
        3.  **ID 03-CRO (Padronização):** Inconsistência nos nomes dos membros no histórico de versão.
            *   *Observação do Leitor:* "Padronizar os nomes completos é essencial para a clareza dos registros."
    *   **Decisões:** A autora (Julia Gabriela) é responsável por refatorar a coluna de responsáveis, definindo um líder claro para cada tarefa. As tags HTML serão removidas e os nomes no histórico de versão serão padronizados.

#### 6. Retrabalho

*   **Defeito ID 01-CRO:**
    *   **Correção Proposta:** Substituir "TODOS" pelo nome do membro que será o ponto focal da tarefa. Ex: A atividade "Inspeção" pode ter "Moderador: [Nome]" como responsável.
    *   **Impacto da Não Correção:** Alto risco de a tarefa não ser executada ou ser executada com baixa qualidade devido à difusão de responsabilidade.
    *   **Ação:** Autora deve revisar a coluna "Responsável" para garantir um dono para cada atividade.
    *   **Reinspeção:** Sim, uma nova rodada de inspeção focada na coluna "Responsável" é recomendada.
*   **Defeito ID 02-CRO e ID 03-CRO:**
    *   **Correção Proposta:** Remover tags HTML de formatação e padronizar os nomes no histórico de versão (usar nome completo).
    *   **Impacto da Não Correção:** Documentação com aparência inconsistente e menos profissional.
    *   **Ação:** Autora deve aplicar as correções de padronização.
    *   **Reinspeção:** Não necessária.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Caso necessário, uma nova reinspeção será agendada.

*   **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados e categorizados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada e registrada
    - Relatório de inspeção foi finalizado e aprovado pelos participantes

---

### **Inspeção Fagan: Artefato 3/7 - `docs/planejamento/cronograma_executado.md`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Introdução, tabelas de cronograma executado para 4 entregas (com atividades, prazos reais, responsáveis e revisores), referências e histórico de versão.
*   **Objetivo Principal:** Registrar e documentar o que foi *realmente* executado no projeto, fornecendo uma base para análise de desvios em relação ao planejado e para lições aprendidas.
*   **Materiais Complementares:**
    *   `cronograma.md`: Essencial para a análise comparativa entre o planejado e o executado.
    *   Commits do Git e Pull Requests: Para validar as datas de conclusão e os responsáveis pelas atividades.
*   **Simulação de Participantes:**
    *   **Moderador:** Gabriel Flores
    *   **Autores:** Julia Gabriela, Gabriel Flores, João Igor, João Pedro Costa
    *   **Leitor:** Amanda Cruz
    *   **Inspetor:** Ryan Salles
*   **Simulação de Agenda:**
    *   **Data:** 21/06/2025
    *   **Horário:** 20:00 - 20:30
    *   **Pauta:** Revisão formal do artefato `cronograma_executado.md`.

#### 2. Visão Geral

*   **Resumo Técnico:** Este documento é um espelho do `cronograma.md`, mas reflete a realidade da execução do projeto. Ele utiliza a mesma estrutura de tabelas Markdown para registrar as atividades que foram de fato realizadas, com os prazos e responsáveis correspondentes.
*   **Contexto no Projeto:** É um artefato fundamental para a gestão e a melhoria contínua. Ele permite à equipe entender onde o planejamento falhou ou foi impreciso, analisar a produtividade e gerar insights para futuros projetos ou para as próximas etapas do projeto atual.
*   **Papéis e Responsabilidades:**
    *   **Moderador (Gabriel):** Focar a discussão na veracidade dos dados e na consistência com o `cronograma.md`.
    *   **Autores (Vários):** Justificar os dados apresentados e os desvios em relação ao planejado.
    *   **Leitor (Amanda):** Ler as atividades e datas para facilitar a identificação de inconsistências.
    *   **Inspetor (Ryan):** Realizar a análise crítica comparando o executado com o planejado e com os registros do Git.

#### 3. Checklist de Verificação
- [ ] Todas as atividades executadas estão registradas?
- [ ] As datas refletem a execução real?
- [ ] Os responsáveis estão corretamente identificados?
- [ ] Há análise de desvios após cada entrega?
- [ ] O histórico de versão está padronizado?
- [ ] Não há erros de formatação ou uso de HTML?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Inconsistência (Dados):** Na Entrega 3, a tabela informa que a atividade "Inspeções" teve um período de desenvolvimento de "19/05 a 19/05", mas o período de revisão foi de "14/05 a 14/05". Uma revisão não pode ocorrer antes do desenvolvimento.
    *   **Violação de Padrão (Formatação):** Uso persistente de tags `<center>` e `<h6>`, violando o padrão de "Markdown puro".
    *   **Ambiguidade (Dados):** Na Entrega 1, a atividade "Escolha do aplicativo" continua com "TODOS" como responsável. No executado, deveria ser possível identificar quem liderou ou consolidou a tarefa.
    *   **Omissão (Conteúdo):** O documento não possui uma seção de "Análise de Desvios" ou "Lições Aprendidas", que agregaria um valor imenso ao artefato. Ele apenas lista o que foi feito, sem interpretar os dados.
*   **Perguntas Críticas Preparadas:**
    *   "O dado da data de revisão da Entrega 3 está correto? Como uma revisão pode anteceder o desenvolvimento?"
    *   "No `cronograma_executado`, não deveríamos ser mais específicos sobre os responsáveis, em vez de manter 'TODOS'?"
    *   "Estamos perdendo uma oportunidade ao não incluir uma breve análise dos principais desvios entre o planejado e o executado em cada entrega?"

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Código fonte/documento marcado com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção do `cronograma_executado.md`**
    *   **Data:** 21/06/2025
    *   **Participantes:** Gabriel Flores, Julia Gabriela, João Igor, João Pedro Costa, Amanda Cruz, Ryan Salles.
    *   **Defeitos Logados:**
        1.  **ID 01-CRE (Lógico):** Inconsistência temporal na Entrega 3, com data de revisão anterior à data de desenvolvimento.
            *   *Observação do Inspetor:* "Este é um erro crítico de dados. Invalida a informação daquela linha e demonstra falta de cuidado na revisão do documento."
        2.  **ID 02-CRE (Omissão):** Ausência de uma seção de análise de desvios.
            *   *Observação do Moderador:* "Defeito de processo. O propósito deste documento não é apenas registrar, mas gerar aprendizado. A adição desta seção é fundamental."
        3.  **ID 03-CRE (Padronização):** Persistência no uso de HTML para formatação e ambiguidade no campo "Responsável".
            *   *Observação do Inspetor:* "Os mesmos problemas de padronização do `cronograma.md` estão presentes aqui."
    *   **Decisões:** O erro de data deve ser corrigido imediatamente. A equipe decide adicionar uma nova subseção ao final de cada tabela de entrega, chamada "Análise de Desvios", para breves comentários. Os problemas de padronização devem ser corrigidos.

#### 6. Retrabalho

*   **Defeito ID 01-CRE:**
    *   **Correção Proposta:** Investigar as datas corretas (via Git ou comunicação com a equipe) e corrigir a linha da tabela da Entrega 3.
    *   **Impacto da Não Correção:** Perda total de credibilidade do documento como um registro factual.
    *   **Ação:** Autores responsáveis pela Entrega 3 devem corrigir o dado.
    *   **Reinspeção:** Sim, a linha corrigida deve ser verificada.
*   **Defeito ID 02-CRE:**
    *   **Correção Proposta:** Adicionar, após cada tabela de entrega, uma seção de análise. Ex: `**Análise de Desvios:** A atividade X atrasou devido a Y. A atividade Z foi incluída por não ter sido prevista inicialmente.`
    *   **Impacto da Não Correção:** O projeto perde uma oportunidade valiosa de melhoria contínua e aprendizado organizacional.
    *   **Ação:** Autores devem se reunir para preencher a análise de desvios para cada entrega.
    *   **Reinspeção:** Sim, a nova seção deve ser inspecionada.
*   **Defeito ID 03-CRE:**
    *   **Correção Proposta:** Remover HTML de formatação e substituir "TODOS" por responsáveis específicos.
    *   **Impacto da Não Correção:** Inconsistência e falta de clareza.
    *   **Ação:** Autores devem aplicar as correções de padronização.
    *   **Reinspeção:** Não necessária.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Caso necessário, uma nova reinspeção será agendada.

*   **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados e categorizados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada e registrada
    - Relatório de inspeção foi finalizado e aprovado pelos participantes

---

### **Inspeção Fagan: Artefato 4/7 - `docs/planejamento/ferramentas.md`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Introdução, tabela com logo e descrição de cada ferramenta utilizada (Google Docs, Chrome, Git, GitHub, etc.), referências e histórico de versões.
*   **Objetivo Principal:** Listar e justificar as ferramentas adotadas pela equipe para o desenvolvimento do projeto, servindo como um guia de referência.
*   **Materiais Complementares:** Documentos do projeto para verificar se todas as ferramentas usadas estão listadas.
*   **Simulação de Participantes:**
    *   **Moderador:** Julia Gabriela
    *   **Autor:** João Pedro Costa
    *   **Leitor:** Gabriel Flores
    *   **Inspetor:** João Igor
*   **Simulação de Agenda:**
    *   **Data:** 21/06/2025
    *   **Horário:** 19:00 - 19:30
    *   **Pauta:** Revisão formal do artefato `ferramentas.md`.

#### 2. Visão Geral

*   **Resumo Técnico:** O documento utiliza uma tabela HTML complexa para apresentar o logo e a descrição das ferramentas. Inclui uma introdução com citações acadêmicas para justificar a importância da escolha de ferramentas e seções de referências e histórico de versões.
*   **Contexto no Projeto:** Este artefato ajuda a padronizar o ambiente de trabalho da equipe e serve como documentação para qualquer novo membro ou para avaliadores externos sobre o *stack* tecnológico e gerencial do projeto.
*   **Papéis e Responsabilidades:**
    *   **Moderador (Julia):** Verificar se as descrições das ferramentas são claras e se a lista está completa.
    *   **Autor (João Pedro):** Justificar a escolha das ferramentas e a formatação do documento.
    *   **Leitor (Gabriel):** Ler as descrições para identificar ambiguidades ou jargões excessivos.
    *   **Inspetor (João Igor):** Analisar a consistência dos dados, especialmente no histórico de versões, e a adequação da formatação.

#### 3. Checklist de Verificação
- [ ] Todas as ferramentas utilizadas estão listadas?
- [ ] As descrições das ferramentas são claras?
- [ ] O histórico de versão está correto?
- [ ] A tabela está em Markdown?
- [ ] Não há erros ortográficos?
- [ ] O termo "Referências" está padronizado?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Inconsistência (Conteúdo):** O histórico de versões (Versão 1.0) descreve a "Criação da página do heatmap". Este é um erro claro de copiar/colar, pois o conteúdo do histórico de versões não corresponde ao artefato `ferramentas.md`.
    *   **Violação de Padrão (Formatação):** O documento utiliza uma tabela HTML complexa (`<table>`, `<thead>`, `<tbody>`, `<tr>`, `<td>`) e tags `<font>`, `<p>`, `<div>`. Isso viola drasticamente o padrão de "Markdown puro" e torna a manutenção do arquivo muito difícil.
    *   **Omissão (Conteúdo):** A ferramenta `mkdocs`, essencial para a publicação do site do projeto, não está listada.
    *   **Inconsistência (Nomenclatura):** A seção de referências é seguida por um "Histórico de Versões", enquanto outros documentos usam "Histórico de versão".
*   **Perguntas Críticas Preparadas:**
    *   "A descrição no histórico de versões foi copiada de outro arquivo? Qual é a descrição correta para a criação deste artefato?"
    *   "Por que foi utilizada uma tabela HTML em vez de uma tabela Markdown, que é nativa e mais fácil de manter?"
    *   "Esquecemos de listar alguma ferramenta importante, como o `mkdocs`?"

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Código fonte/documento marcado com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção do `ferramentas.md`**
    *   **Data:** 21/06/2025
    *   **Participantes:** Julia Gabriela, João Pedro Costa, Gabriel Flores, João Igor.
    *   **Defeitos Logados:**
        1.  **ID 01-FER (Crítico):** Descrição incorreta no histórico de versões.
            *   *Observação do Inspetor:* "Este erro invalida o registro de alterações e demonstra falta de atenção na documentação. É um defeito de alta severidade do ponto de vista de processo."
        2.  **ID 02-FER (Padronização):** Uso excessivo de HTML para formatação.
            *   *Observação do Moderador:* "A tabela precisa ser refatorada para Markdown. A complexidade do HTML atual é desnecessária e dificulta a manutenção."
        3.  **ID 03-FER (Omissão):** Ferramenta `mkdocs` não foi listada.
            *   *Observação do Leitor:* "Se usamos a ferramenta para gerar o site, ela deve estar documentada aqui."
    *   **Decisões:** O autor (João Pedro Costa) é responsável por corrigir o histórico de versões, refatorar a tabela para Markdown e adicionar a ferramenta `mkdocs` à lista.

#### 6. Retrabalho

*   **Defeito ID 01-FER:**
    *   **Correção Proposta:** Alterar a descrição da Versão 1.0 para "Criação do documento de ferramentas utilizadas".
    *   **Impacto da Não Correção:** Mantém um registro de auditoria falso, o que é grave em qualquer processo de documentação formal.
    *   **Ação:** Autor deve corrigir a descrição.
    *   **Reinspeção:** Sim, o histórico corrigido deve ser verificado.
*   **Defeito ID 02-FER:**
    *   **Correção Proposta:** Substituir toda a estrutura `<table>...</table>` por uma tabela em sintaxe Markdown. A imagem pode ser inserida na primeira coluna usando `![Logo](path)`.
    *   **Impacto da Não Correção:** Dificulta a edição e manutenção do documento, além de violar os padrões de consistência do projeto.
    *   **Ação:** Autor deve refatorar a tabela.
    *   **Reinspeção:** Sim, a nova tabela em Markdown deve ser inspecionada para garantir que a formatação e o conteúdo foram preservados.
*   **Defeito ID 03-FER:**
    *   **Correção Proposta:** Adicionar uma nova linha na tabela para a ferramenta `mkdocs`, com seu logo e descrição.
    *   **Impacto da Não Correção:** A documentação de ferramentas fica incompleta.
    *   **Ação:** Autor deve adicionar a ferramenta ausente.
    *   **Reinspeção:** Não necessária.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Caso necessário, uma nova reinspeção será agendada.

*   **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados e categorizados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada e registrada
    - Relatório de inspeção foi finalizado e aprovado pelos participantes

---

### **Inspeção Fagan: Artefato 5/7 - `docs/planejamento/heatmap.md`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Introdução, objetivo, figura (imagem do heatmap), tabela de dados do heatmap, seção de bibliografia, links e histórico de versões.
*   **Objetivo Principal:** Apresentar visualmente a disponibilidade da equipe, permitindo um planejamento mais eficaz de reuniões e atividades síncronas.
*   **Materiais Complementares:** A planilha Excel original de onde os dados foram extraídos, para validação cruzada.
*   **Simulação de Participantes:**
    *   **Moderador:** Amanda Cruz
    *   **Autor:** João Pedro Costa
    *   **Leitor:** João Vítor
    *   **Inspetor:** Julia Gabriela
*   **Simulação de Agenda:**
    *   **Data:** 21/06/2025
    *   **Horário:** 19:30 - 20:00
    *   **Pauta:** Revisão formal do artefato `heatmap.md`.

#### 2. Visão Geral

*   **Resumo Técnico:** O documento explica o conceito de heatmap de disponibilidade e apresenta os dados da equipe em dois formatos: uma imagem (Figura 1) e uma tabela Markdown. Contém seções de bibliografia, links para a fonte de dados e histórico de versões.
*   **Contexto no Projeto:** É um artefato de apoio ao gerenciamento, crucial para a logística da equipe. Ele influencia diretamente a definição de prazos no `cronograma.md`, garantindo que as atividades síncronas sejam agendadas nos horários de maior disponibilidade.
*   **Papéis e Responsabilidades:**
    *   **Moderador (Amanda):** Garantir que a representação dos dados (imagem e tabela) seja clara e consistente.
    *   **Autor (João Pedro):** Esclarecer a origem dos dados e as escolhas de representação visual.
    *   **Leitor (João Vítor):** Ler o documento e os dados da tabela para identificar possíveis erros ou inconsistências.
    *   **Inspetor (Julia):** Verificar a consistência entre a imagem e a tabela de dados, além da conformidade com os padrões do projeto.

#### 3. Checklist de Verificação
- [ ] Os dados da tabela e da imagem do heatmap são consistentes?
- [ ] O texto alternativo da imagem é descritivo?
- [ ] O termo "Referências" está padronizado?
- [ ] Não há uso de HTML para formatação?
- [ ] O histórico de versão está correto?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Inconsistência (Dados):** É necessário verificar se os dados na tabela Markdown correspondem exatamente aos dados apresentados na imagem do heatmap. Uma verificação manual é necessária.
    *   **Violação de Padrão (Formatação):** O documento utiliza `<div>`, `<font>`, `<p>` para legendas e fontes, violando o padrão de "Markdown puro".
    *   **Inconsistência (Nomenclatura):** A seção é chamada de "Bibliografia", enquanto outros documentos usam "Referências". É preciso padronizar.
    *   **Acessibilidade (Omissão):** O `alt text` da imagem é apenas "Heatmap". Um texto alternativo mais descritivo seria "Heatmap de disponibilidade da equipe, mostrando horários com maior concentração de membros disponíveis em verde".
*   **Perguntas Críticas Preparadas:**
    *   "Alguém validou se cada célula da tabela Markdown corresponde ao respectivo quadrado na imagem do heatmap?"
    *   "Por que a seção de referências aqui se chama 'Bibliografia'?"
    *   "O link para o arquivo Excel está acessível para todos os membros da equipe e para os avaliadores?"

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Código fonte/documento marcado com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção do `heatmap.md`**
    *   **Data:** 21/06/2025
    *   **Participantes:** Amanda Cruz, João Pedro Costa, João Vítor, Julia Gabriela.
    *   **Defeitos Logados:**
        1.  **ID 01-HEA (Padronização):** Uso de HTML para formatação.
            *   *Observação da Inspetora:* "O uso de `<font>` é particularmente problemático e obsoleto. Devemos usar Markdown."
        2.  **ID 02-HEA (Padronização):** Nomenclatura da seção "Bibliografia" inconsistente.
            *   *Observação do Moderador:* "Fica decidido que o termo padrão em todo o projeto será 'Referências'."
        3.  **ID 03-HEA (Acessibilidade):** Texto alternativo da imagem é genérico.
            *   *Observação da Inspetora:* "Devemos seguir as boas práticas de acessibilidade e fornecer descrições úteis para leitores de tela."
    *   **Decisões:** O autor (João Pedro Costa) é responsável por refatorar a formatação, padronizar o título da seção de referências e melhorar o texto alternativo da imagem.

#### 6. Retrabalho

*   **Defeito ID 01-HEA e ID 02-HEA:**
    *   **Correção Proposta:** Substituir as tags HTML por formatação Markdown e renomear a seção "Bibliografia" para "Referências".
    *   **Impacto da Não Correção:** Inconsistência visual e estrutural com os demais artefatos do projeto.
    *   **Ação:** Autor deve aplicar as correções de padronização.
    *   **Reinspeção:** Não necessária.
*   **Defeito ID 03-HEA:**
    *   **Correção Proposta:** Alterar `alt="Heatmap"` para `alt="Heatmap de disponibilidade da equipe, com cores variando de vermelho (baixa disponibilidade) a verde (alta disponibilidade)"`.
    *   **Impacto da Não Correção:** Dificulta a compreensão do conteúdo por usuários que dependem de leitores de tela.
    *   **Ação:** Autor deve atualizar o texto alternativo da imagem.
    *   **Reinspeção:** Não necessária.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Caso necessário, uma nova reinspeção será agendada.

*   **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados e categorizados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada e registrada
    - Relatório de inspeção foi finalizado e aprovado pelos participantes

---

### **Inspeção Fagan: Artefato 6/7 - `docs/planejamento/metodologia.md`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Introdução, descrição da metodologia de desenvolvimento (Scrum), metodologia de versionamento, técnicas de revisão (Revisão por Pares, Pareamento), referências e histórico de versão.
*   **Objetivo Principal:** Descrever e formalizar as metodologias e os processos que guiarão o trabalho da equipe, tanto no desenvolvimento quanto na garantia de qualidade da documentação.
*   **Materiais Complementares:** `fagan_introspeccao.md` e outros relatórios de inspeção para verificar se os processos descritos correspondem à prática.
*   **Simulação de Participantes:**
    *   **Moderador:** João Igor
    *   **Autores:** João Pedro Costa, Ryan Salles, João Igor
    *   **Leitor:** Gabriel Flores
    *   **Inspetor:** Amanda Cruz
*   **Simulação de Agenda:**
    *   **Data:** 21/06/2025
    *   **Horário:** 20:00 - 20:30
    *   **Pauta:** Revisão formal do artefato `metodologia.md`.

#### 2. Visão Geral

*   **Resumo Técnico:** O documento detalha os processos adotados pela equipe. Ele aborda o framework ágil (Scrum) para o gerenciamento do projeto e as técnicas de revisão de código/documentos. O objetivo é criar um manual de "como trabalhamos".
*   **Contexto no Projeto:** Este é um documento de governança. Ele estabelece as "regras do jogo" para a equipe. Sua precisão e clareza são essenciais para garantir que todos os membros trabalhem de forma coesa e sigam os mesmos processos.
*   **Papéis e Responsabilidades:**
    *   **Moderador (João Igor):** Garantir que as metodologias descritas sejam práticas e compreensíveis para todos.
    *   **Autores (Vários):** Defender e explicar a escolha das metodologias.
    *   **Leitor (Gabriel):** Ler as descrições para identificar jargões ou explicações confusas.
    *   **Inspetor (Amanda):** Verificar se as metodologias descritas estão alinhadas com as práticas reais da equipe.

#### 3. Checklist de Verificação
- [ ] Todas as metodologias realmente utilizadas estão descritas?
- [ ] A Inspeção Fagan está documentada como técnica de revisão?
- [ ] O histórico de versão está padronizado?
- [ ] Não há erros ortográficos?
- [ ] O termo "Referências" está padronizado?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Omissão (Conteúdo):** O documento descreve "Revisão por Pares" e "Pareamento", mas **omite a Inspeção Fagan**, que é um processo formal de revisão utilizado pela equipe (conforme evidenciado pela existência dos próprios relatórios de inspeção). Esta é uma omissão crítica.
    *   **Inconsistência (Conteúdo):** A seção "Metodologia I: Desenvolvimento" menciona Scrum, mas não detalha como ele é aplicado na prática (ex: tamanho das sprints, cerimônias como Daily, Planning, Review). A descrição é muito teórica.
    *   **Violação de Padrão (Nomenclatura):** Inconsistência nos nomes dos membros no histórico de versão ("Ryan Salles" vs. "Ryan Augusto").
*   **Perguntas Críticas Preparadas:**
    *   "Se estamos realizando Inspeções Fagan formais, por que este método não está documentado como nossa principal técnica de revisão de artefatos?"
    *   "Como a nossa implementação do Scrum funciona na prática? Quais cerimônias nós realmente seguimos?"
    *   "A descrição da 'Revisão por Pares' reflete o que fazemos, ou estamos, na verdade, seguindo o processo mais estruturado de Fagan?"

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Código fonte/documento marcado com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção do `metodologia.md`**
    *   **Data:** 21/06/2025
    *   **Participantes:** João Igor, João Pedro Costa, Ryan Salles, Gabriel Flores, Amanda Cruz.
    *   **Defeitos Logados:**
        1.  **ID 01-MET (Crítico):** Omissão da Inspeção Fagan como técnica de revisão.
            *   *Observação da Inspetora:* "Esta é a falha mais grave. O documento descreve um processo que não reflete nossa prática mais formal de garantia de qualidade. Precisamos incluir Fagan como nosso método oficial de inspeção de artefatos."
        2.  **ID 02-MET (Omissão):** Detalhes práticos da implementação do Scrum ausentes.
            *   *Observação do Moderador:* "Concordo. A seção sobre Scrum é muito acadêmica. Precisamos descrever brevemente nosso 'sabor' de Scrum."
    *   **Decisões:** A omissão da Inspeção Fagan deve ser corrigida com alta prioridade. Uma breve descrição do processo Fagan será adicionada. A seção do Scrum será enriquecida com detalhes práticos.

#### 6. Retrabalho

*   **Defeito ID 01-MET:**
    *   **Correção Proposta:** Adicionar uma nova subseção em "Técnicas de Revisão" chamada "Inspeção Fagan", explicando que este é o método formal usado para a revisão de artefatos de documentação, citando as etapas (Planejamento, Visão Geral, etc.).
    *   **Impacto da Não Correção:** O documento de metodologia fica desalinhado com a prática da equipe, perdendo seu valor como guia de processos e gerando inconsistência.
    *   **Ação:** Autores devem adicionar a seção sobre Inspeção Fagan.
    *   **Reinspeção:** Sim, a nova seção deve ser inspecionada para garantir sua clareza e precisão.
*   **Defeito ID 02-MET:**
    *   **Correção Proposta:** Adicionar uma ou duas frases na seção Scrum. Ex: "A equipe opera em sprints semanais, alinhadas com as entregas da disciplina, e utiliza reuniões de planejamento no início de cada entrega para distribuir tarefas."
    *   **Impacto da Não Correção:** A metodologia de desenvolvimento permanece vaga e teórica.
    *   **Ação:** Autores devem adicionar os detalhes práticos sobre o Scrum.
    *   **Reinspeção:** Não necessária.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Caso necessário, uma nova reinspeção será agendada.

*   **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados e categorizados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada e registrada
    - Relatório de inspeção foi finalizado e aprovado pelos participantes

---

### **Inspeção Fagan: Artefato 7/7 - `docs/planejamento/termosDeUso.md`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Introdução, 16 imagens dos termos de uso do aplicativo, referências e histórico de versões.
*   **Objetivo Principal:** Documentar a análise dos termos de uso do aplicativo "Cadastro Único", especificamente para verificar se há alguma restrição ao seu uso para fins acadêmicos.
*   **Materiais Complementares:** O site oficial do Cadastro Único para verificar se os termos de uso foram atualizados.
*   **Simulação de Participantes:**
    *   **Moderador:** Ryan Salles
    *   **Autor:** João Pedro Costa
    *   **Leitor:** Julia Gabriela
    *   **Inspetor:** Gabriel Flores
*   **Simulação de Agenda:**
    *   **Data:** 21/06/2025
    *   **Horário:** 20:30 - 21:00
    *   **Pauta:** Revisão formal do artefato `termosDeUso.md`.

#### 2. Visão Geral

*   **Resumo Técnico:** O documento apresenta uma conclusão sobre a análise dos termos de uso e exibe 16 imagens sequenciais que compõem os termos. O objetivo é fornecer a evidência visual que suporta a conclusão apresentada na introdução.
*   **Contexto no Projeto:** Este é um documento de diligência prévia (due diligence). Ele garante que o projeto está em conformidade legal e ética ao utilizar o aplicativo como objeto de estudo, mitigando riscos de violação de propriedade intelectual ou de uso.
*   **Papéis e Responsabilidades:**
    *   **Moderador (Ryan):** Verificar se a conclusão apresentada é claramente suportada pelas evidências (imagens).
    *   **Autor (João Pedro):** Esclarecer o processo de análise dos termos.
    *   **Leitor (Julia):** Ler a introdução e descrever as imagens para garantir que a lógica flua corretamente.
    *   **Inspetor (Gabriel):** Analisar a qualidade das evidências e a clareza da documentação.

#### 3. Checklist de Verificação
- [ ] Todas as imagens possuem texto alternativo descritivo?
- [ ] Os principais trechos dos termos de uso estão transcritos?
- [ ] A conclusão está fundamentada em cláusulas específicas?
- [ ] O histórico de versão está correto?
- [ ] Não há erros ortográficos?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Acessibilidade (Omissão):** O `alt text` de todas as 16 imagens é extremamente genérico (ex: `![Termo de Uso - Página 1]`, `![Termo de Uso - Página 2]`). Isso torna o documento inacessível para usuários de leitores de tela.
    *   **Eficiência (Conteúdo):** Apresentar 16 imagens em sequência torna o documento muito longo e pesado. Uma alternativa mais eficiente seria transcrever os trechos mais importantes dos termos de uso e manter as imagens em um anexo ou link.
    *   **Omissão (Conteúdo):** A conclusão é muito breve: "verificou-se que não há nenhuma cláusula que proíba ou autorize expressamente o uso". Seria mais robusto citar qual seção ou cláusula foi analisada com mais atenção (ex: "A seção 'Uso Permitido' não impõe restrições a fins educacionais").
*   **Perguntas Críticas Preparadas:**
    *   "Como um usuário com deficiência visual poderia consumir a informação contida nas 16 imagens?"
    *   "A apresentação de 16 imagens é a forma mais eficaz de comunicar nossa análise? Não poderíamos resumir e transcrever os pontos-chave?"
    *   "A nossa conclusão é robusta o suficiente? Podemos apontar para uma seção específica dos termos que suporte nossa afirmação?"

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Código fonte/documento marcado com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção do `termosDeUso.md`**
    *   **Data:** 21/06/2025
    *   **Participantes:** Ryan Salles, João Pedro Costa, Julia Gabriela, Gabriel Flores.
    *   **Defeitos Logados:**
        1.  **ID 01-TER (Crítico):** Falha grave de acessibilidade devido ao `alt text` genérico das imagens.
            *   *Observação do Inspetor:* "Este documento é praticamente inútil para um usuário de leitor de tela. Precisamos corrigir isso."
        2.  **ID 02-TER (Eficiência):** Formato de apresentação ineficiente (16 imagens).
            *   *Observação do Moderador:* "A experiência do usuário ao rolar por 16 imagens é ruim. Sugiro fortemente uma abordagem de transcrição."
    *   **Decisões:** O problema de acessibilidade é prioritário. O autor deve, no mínimo, melhorar o `alt text`. A equipe decide, como melhoria, transcrever os parágrafos mais relevantes dos termos de uso para o corpo do documento, reduzindo o número de imagens ou movendo-as para uma pasta de anexo e linkadas.

#### 6. Retrabalho

*   **Defeito ID 01-TER:**
    *   **Correção Proposta:** Atualizar o `alt text` de cada imagem com um resumo do seu conteúdo. Ex: `alt="Página 1 dos Termos de Uso, descrevendo o objeto do termo e as condições de aceitação."`.
    *   **Impacto da Não Correção:** O documento viola princípios básicos de acessibilidade web.
    *   **Ação:** Autor deve reescrever o texto alternativo para todas as 16 imagens.
    *   **Reinspeção:** Sim, a correção de acessibilidade deve ser verificada.
*   **Defeito ID 02-TER:**
    *   **Correção Proposta:** Criar uma nova seção "Principais Cláusulas Analisadas" e transcrever os trechos mais relevantes dos termos de uso usando citações (`>`). As imagens podem ser removidas ou movidas para uma pasta de anexo e linkadas.
    *   **Impacto da Não Correção:** O documento permanece de difícil leitura e navegação, com tempo de carregamento elevado.
    *   **Ação:** Autor deve refatorar o documento para uma apresentação baseada em texto.
    *   **Reinspeção:** Sim, a nova estrutura do documento deve ser inspecionada.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Caso necessário, uma nova reinspeção será agendada.

*   **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados e categorizados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada e registrada
    - Relatório de inspeção foi finalizado e aprovado pelos participantes

---

## Bibliografia

BARHATE, B. H. Software Inspection Improves Quality of Software Product. *International Journal of Computer Science & Informatics*, Vol.- II, Issue-1, 2. [Link para o artigo](../../assets/inspecao_fagan/Software_Inspection_Improves_Quality_of_Software_P.pdf)

---

## Histórico de Versão

| Versão |    Data    | Descrição  |   Autor  |  Revisor  |
| :----: | :--------: | :---------:| :-------:| :-------: |
|  1.0   | 21/06/2025 | Criação do Documento | [João Pedro Costa](https://github.com/johnaopedro) | [Ryan Salles](https://github.com/RA-Salles)  |
|  1.1   | 21/06/2025 | Desenvolvimento da introdução | [João Pedro Costa](https://github.com/johnaopedro) | [Ryan Salles](https://github.com/RA-Salles)  |
|  1.2   | 21/06/2025 | Criação do template da inspeção pelo metodo de Fagan e Criação das tabelas | [João Pedro Costa](https://github.com/johnaopedro) | [Ryan Salles](https://github.com/RA-Salles)  |
|  1.3   | 21/06/2025 | Desenvolvimento de todas as inspeções dos artefatos da etapa 1  | [João Pedro Costa](https://github.com/johnaopedro) | [Ryan Salles](https://github.com/RA-Salles)  |