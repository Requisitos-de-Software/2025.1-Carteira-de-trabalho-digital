# Inspeção Fagan – Etapa 5

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

O processo de inspeção Fagan segue uma estrutura rigorosa que visa maximizar a detecção e correção de defeitos. Esta metodologia requer uma definição clara do estado do produto de trabalho a ser inspecionado, com participantes assumindo papéis bem definidos durante todo o processo. É essencial que seja dedicado tempo adequado para a preparação dos inspetores, que utilizam checklists específicos para guiar sua análise.

Para os artefatos de pós-rastreabilidade, nossa inspeção terá um foco especial na verificação da completude e consistência dos elos de rastreabilidade, garantindo que todos os requisitos estejam adequadamente conectados aos artefatos do projeto. Será dada atenção especial à qualidade das relações estabelecidas, verificando se elas são significativas e bem justificadas. A conformidade com o meta-modelo de Toranzo será analisada, assegurando que os diferentes tipos de elos (satisfação, recurso, representação, alocado e agregação) estejam sendo utilizados corretamente.

### Processo de Inspeção

O processo de inspeção Fagan é rigorosamente estruturado e requer:
1. Definição clara do estado do produto de trabalho a ser inspecionado
2. Participantes com papéis bem definidos
3. Tempo adequado de preparação para os inspetores
4. Checklists específicos para guiar a inspeção
5. Critérios de entrada e saída bem estabelecidos
6. Documentação apropriada e coleta de dados
7. Procedimentos claros para retrabalho e verificação

### **Inspeção Fagan: Artefato 1/2 - `Matriz Geral de Rastreabilidade`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Introdução, objetivos, tipos de matrizes, metodologia, matriz geral.
*   **Objetivo Principal:** Avaliar a qualidade e completude da matriz geral de rastreabilidade, garantindo que todos os requisitos estejam adequadamente rastreados.
*   **Materiais Complementares:**
    *   Documentação dos requisitos elicitados
    *   Documentação dos artefatos do projeto
    *   Meta-modelo de Toranzo
*   **Simulação de Participantes:**
    *   **Moderador:** Amanda Cruz
    *   **Autores:** Julia Gabriela, João Pedro Costa
    *   **Leitor:** Ryan Salles
    *   **Inspetor:** Gabriel Flores
*   **Simulação de Agenda:**
    *   **Data:** 22/05/2025
    *   **Horário:** 14:00 - 14:30
    *   **Local:** Reunião Online - Microsoft Teams
    *   **Pauta:** Revisão formal da matriz geral de rastreabilidade

#### 2. Visão Geral

*   **Resumo Técnico:** A matriz geral de rastreabilidade é uma ferramenta que relaciona os requisitos com suas fontes e artefatos relacionados.
*   **Contexto no Projeto:** Este artefato é fundamental para garantir que todos os requisitos sejam rastreáveis e implementados.
*   **Papéis e Responsabilidades:**
    *   **Moderador (Amanda):** Garantir que a inspeção mantenha o foco na qualidade da rastreabilidade.
    *   **Autores (Julia e João Pedro):** Explicar as decisões de rastreabilidade.
    *   **Leitor (Ryan):** Ler a matriz e identificar inconsistências.
    *   **Inspetor (Gabriel):** Verificar a completude e correção das relações.

#### 3. Checklist de Verificação
- [ ] Todos os requisitos estão listados na matriz?
- [ ] As fontes dos requisitos estão corretamente identificadas?
- [ ] Os links para os artefatos relacionados estão funcionando?
- [ ] A implementação dos requisitos está corretamente indicada?
- [ ] A matriz está atualizada com os últimos requisitos?
- [ ] A formatação está consistente em toda a matriz?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Inconsistência (Links):** Alguns links para artefatos não estão funcionando.
    *   **Omissão (Rastreabilidade):** Alguns requisitos não têm todas as fontes identificadas.
    *   **Ambiguidade (Status):** O status de implementação não está claro para alguns requisitos.
    *   **Incompletude (Requisitos):** Alguns requisitos recentes não foram incluídos na matriz.
*   **Perguntas Críticas Preparadas:**
    *   "Como foi verificada a completude da matriz?"
    *   "Como são mantidos os links para os artefatos?"
    *   "Como é atualizado o status de implementação?"

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Matriz marcada com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção da `Matriz Geral`**
    *   **Data:** 22/05/2025
    *   **Participantes:** Amanda Cruz, Julia Gabriela, João Pedro Costa, Ryan Salles, Gabriel Flores
    *   **Defeitos Logados:**
        1.  **ID 01-MG (Links):** Links quebrados para artefatos
            *   *Observação do Inspetor:* "Vários links não estão funcionando corretamente."
        2.  **ID 02-MG (Fontes):** Fontes incompletas
            *   *Observação do Moderador:* "Alguns requisitos não têm todas as fontes listadas."
        3.  **ID 03-MG (Status):** Status ambíguo
            *   *Observação dos Autores:* "O status de implementação precisa ser mais claro."
    *   **Decisões:** Corrigir links quebrados, completar fontes e clarificar status de implementação.

#### 6. Retrabalho

*   **Defeito ID 01-MG:**
    *   **Correção Proposta:** Verificar e corrigir todos os links.
    *   **Impacto da Não Correção:** Dificuldade de navegação e verificação.
    *   **Ação:** Autores devem testar e atualizar links.
    *   **Reinspeção:** Sim, após correção dos links.
*   **Defeito ID 02-MG:**
    *   **Correção Proposta:** Revisar e completar fontes.
    *   **Impacto da Não Correção:** Perda de rastreabilidade.
    *   **Ação:** Autores devem identificar todas as fontes.
    *   **Reinspeção:** Sim, das fontes atualizadas.
*   **Defeito ID 03-MG:**
    *   **Correção Proposta:** Padronizar indicação de status.
    *   **Impacto da Não Correção:** Confusão sobre implementação.
    *   **Ação:** Autores devem definir padrão claro.
    *   **Reinspeção:** Sim, do status atualizado.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Caso necessário, uma nova reinspeção será agendada.

*   **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados e categorizados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada e registrada
    - Relatório de inspeção foi finalizado e aprovado pelos participantes

### **Inspeção Fagan: Artefato 2/2 - `Pós-Rastreabilidade`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Introdução, metodologia, elos de rastreabilidade, tabelas de rastreabilidade.
*   **Objetivo Principal:** Avaliar a qualidade e completude dos elos de rastreabilidade, garantindo que as relações entre requisitos e artefatos estejam bem estabelecidas.
*   **Materiais Complementares:**
    *   Meta-modelo de Toranzo
    *   Documentação dos requisitos
    *   Artefatos do projeto
*   **Simulação de Participantes:**
    *   **Moderador:** Gabriel Flores
    *   **Autores:** João Pedro Costa, Ryan Salles
    *   **Leitor:** Amanda Cruz
    *   **Inspetor:** Julia Gabriela
*   **Simulação de Agenda:**
    *   **Data:** 22/05/2025
    *   **Horário:** 14:30 - 15:00
    *   **Local:** Reunião Online - Microsoft Teams
    *   **Pauta:** Revisão formal dos elos de rastreabilidade

#### 2. Visão Geral

*   **Resumo Técnico:** O documento de pós-rastreabilidade estabelece elos entre requisitos e artefatos usando o meta-modelo de Toranzo.
*   **Contexto no Projeto:** Este artefato é crucial para garantir a rastreabilidade bidirecional dos requisitos.
*   **Papéis e Responsabilidades:**
    *   **Moderador (Gabriel):** Garantir que a inspeção mantenha o foco na qualidade dos elos.
    *   **Autores (João Pedro e Ryan):** Explicar as decisões de rastreabilidade.
    *   **Leitor (Amanda):** Ler os elos e identificar inconsistências.
    *   **Inspetor (Julia):** Verificar a conformidade com o meta-modelo.

#### 3. Checklist de Verificação
- [ ] Os elos seguem o meta-modelo de Toranzo?
- [ ] Todos os requisitos têm elos estabelecidos?
- [ ] As relações são significativas e bem justificadas?
- [ ] Os tipos de elos estão sendo usados corretamente?
- [ ] A documentação dos elos está clara e completa?
- [ ] As tabelas de rastreabilidade estão consistentes?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Inconsistência (Elos):** Alguns elos não seguem o meta-modelo.
    *   **Omissão (Requisitos):** Alguns requisitos não têm todos os tipos de elos.
    *   **Ambiguidade (Justificativas):** Algumas relações não estão bem justificadas.
    *   **Incompletude (Artefatos):** Nem todos os artefatos relevantes estão relacionados.
*   **Perguntas Críticas Preparadas:**
    *   "Como foi garantida a conformidade com o meta-modelo?"
    *   "Como foram identificados os elos relevantes?"
    *   "Como são justificadas as relações estabelecidas?"

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Elos marcados com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção dos `Elos de Rastreabilidade`**
    *   **Data:** 22/05/2025
    *   **Participantes:** Gabriel Flores, João Pedro Costa, Ryan Salles, Amanda Cruz, Julia Gabriela
    *   **Defeitos Logados:**
        1.  **ID 01-PR (Meta-modelo):** Elos inconsistentes
            *   *Observação do Inspetor:* "Alguns elos não seguem corretamente o meta-modelo."
        2.  **ID 02-PR (Completude):** Elos faltantes
            *   *Observação do Moderador:* "Alguns requisitos não têm todos os tipos de elos necessários."
        3.  **ID 03-PR (Justificativa):** Relações não justificadas
            *   *Observação dos Autores:* "Algumas relações precisam de melhor justificativa."
    *   **Decisões:** Revisar conformidade com meta-modelo, completar elos faltantes e melhorar justificativas.

#### 6. Retrabalho

*   **Defeito ID 01-PR:**
    *   **Correção Proposta:** Ajustar elos ao meta-modelo.
    *   **Impacto da Não Correção:** Inconsistência metodológica.
    *   **Ação:** Autores devem revisar todos os elos.
    *   **Reinspeção:** Sim, após ajustes.
*   **Defeito ID 02-PR:**
    *   **Correção Proposta:** Identificar e adicionar elos faltantes.
    *   **Impacto da Não Correção:** Rastreabilidade incompleta.
    *   **Ação:** Autores devem completar os elos.
    *   **Reinspeção:** Sim, dos novos elos.
*   **Defeito ID 03-PR:**
    *   **Correção Proposta:** Melhorar justificativas das relações.
    *   **Impacto da Não Correção:** Dificuldade de entendimento.
    *   **Ação:** Autores devem documentar justificativas.
    *   **Reinspeção:** Sim, das justificativas.

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
|  1.3   | 21/06/2025 | Desenvolvimento de todas as inspeções dos artefatos da etapa 5  | [João Pedro Costa](https://github.com/johnaopedro) | [Ryan Salles](https://github.com/RA-Salles)  |
