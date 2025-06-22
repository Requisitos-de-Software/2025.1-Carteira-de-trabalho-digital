# Inspeção Fagan – Etapa 4

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

Para os artefatos ágeis, nossa inspeção terá um foco especial na verificação da clareza e objetividade das histórias de usuário, garantindo que elas sigam o formato adequado e contenham todos os elementos necessários. Será dada atenção especial à priorização do backlog, verificando se ela reflete adequadamente as necessidades do negócio e dos usuários. A completude dos critérios de aceitação será analisada, assegurando que eles forneçam diretrizes claras para o desenvolvimento e teste. Também será verificada a rastreabilidade com outros artefatos do projeto e a conformidade com as boas práticas ágeis estabelecidas pela comunidade.

### Processo de Inspeção

O processo de inspeção Fagan é rigorosamente estruturado e requer:
1. Definição clara do estado do produto de trabalho a ser inspecionado
2. Participantes com papéis bem definidos
3. Tempo adequado de preparação para os inspetores
4. Checklists específicos para guiar a inspeção
5. Critérios de entrada e saída bem estabelecidos
6. Documentação apropriada e coleta de dados
7. Procedimentos claros para retrabalho e verificação

### **Inspeção Fagan: Artefato 1/3 - `NFR Framework`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Introdução, softgoals, operacionalizações, claims, propagações, impactos e contribuições entre softgoals.
*   **Objetivo Principal:** Avaliar a qualidade e completude do NFR Framework, garantindo que os requisitos não-funcionais estejam adequadamente representados e analisados.
*   **Materiais Complementares:**
    *   Documentação dos requisitos não-funcionais elicitados
    *   Guia de notação do NFR Framework
    *   Histórico de decisões de arquitetura
*   **Simulação de Participantes:**
    *   **Moderador:** Amanda Cruz
    *   **Autores:** João Pedro Costa, Ryan Salles
    *   **Leitor:** Julia Gabriela
    *   **Inspetor:** Gabriel Flores
*   **Simulação de Agenda:**
    *   **Data:** 22/05/2025
    *   **Horário:** 14:00 - 14:30
    *   **Pauta:** Revisão formal do artefato `NFR Framework`.

#### 2. Visão Geral

*   **Resumo Técnico:** O NFR Framework é uma abordagem para representar e analisar requisitos não-funcionais, usando um tipo de grafo de interdependência de softgoals (SIG). O documento apresenta diversos diagramas que capturam diferentes aspectos de qualidade do sistema.
*   **Contexto no Projeto:** Este artefato é fundamental para garantir que aspectos de qualidade como usabilidade, desempenho e segurança sejam adequadamente considerados no desenvolvimento.
*   **Papéis e Responsabilidades:**
    *   **Moderador (Amanda):** Garantir que a inspeção mantenha o foco nos aspectos de qualidade.
    *   **Autores (João Pedro e Ryan):** Explicar as decisões de modelagem e as relações entre softgoals.
    *   **Leitor (Julia):** Ler os diagramas e suas explicações para identificar inconsistências.
    *   **Inspetor (Gabriel):** Verificar a conformidade com a notação e a completude da análise.

#### 3. Checklist de Verificação
- [ ] Os softgoals estão claramente identificados?
- [ ] As operacionalizações são específicas e implementáveis?
- [ ] As propagações de impacto estão corretamente analisadas?
- [ ] Os claims justificam adequadamente as decisões?
- [ ] A notação está consistente em todos os diagramas?
- [ ] Todos os requisitos não-funcionais importantes foram considerados?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Inconsistência (Notação):** Alguns softgoals de operacionalização não seguem o padrão de representação com borda dupla.
    *   **Omissão (Análise):** Faltam claims para justificar algumas decisões de propagação de impacto.
    *   **Ambiguidade (Semântica):** A contribuição "HELP" entre softgoals de segurança não está clara quanto ao grau de suporte.
    *   **Incompletude (Escopo):** O aspecto de manutenibilidade não foi considerado no framework.
*   **Perguntas Críticas Preparadas:**
    *   "Por que algumas operacionalizações não têm critérios de satisfação definidos?"
    *   "Como foi determinado o impacto das contribuições parciais?"
    *   "Existem conflitos entre os diferentes aspectos de qualidade que precisam ser melhor analisados?"

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Diagramas marcados com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção do `NFR Framework`**
    *   **Data:** 22/05/2025
    *   **Participantes:** Amanda Cruz, João Pedro Costa, Ryan Salles, Julia Gabriela, Gabriel Flores.
    *   **Defeitos Logados:**
        1.  **ID 01-NFR (Notação):** Inconsistência na representação de operacionalizações.
            *   *Observação do Inspetor:* "A falta de padronização dificulta a leitura e compreensão dos diagramas."
        2.  **ID 02-NFR (Análise):** Justificativas insuficientes para propagações.
            *   *Observação do Moderador:* "Claims são essenciais para documentar o raciocínio por trás das decisões."
        3.  **ID 03-NFR (Escopo):** Ausência de análise de manutenibilidade.
            *   *Observação dos Autores:* "Este é um aspecto crítico que precisa ser incorporado ao framework."
    *   **Decisões:** Os autores devem padronizar a notação, adicionar claims para todas as propagações significativas e criar um novo diagrama para manutenibilidade.

#### 6. Retrabalho

*   **Defeito ID 01-NFR:**
    *   **Correção Proposta:** Revisar todos os diagramas e ajustar a representação das operacionalizações para usar consistentemente a borda dupla.
    *   **Impacto da Não Correção:** Dificuldade de compreensão e possíveis interpretações errôneas dos diagramas.
    *   **Ação:** Autores devem atualizar a notação em todos os diagramas.
    *   **Reinspeção:** Sim, após a padronização.
*   **Defeito ID 02-NFR:**
    *   **Correção Proposta:** Adicionar claims explicativos para cada propagação de impacto significativa.
    *   **Impacto da Não Correção:** Perda do raciocínio que justifica as decisões de design.
    *   **Ação:** Autores devem documentar as justificativas.
    *   **Reinspeção:** Sim, focada na clareza e completude dos claims.
*   **Defeito ID 03-NFR:**
    *   **Correção Proposta:** Criar um novo SIG focado em manutenibilidade.
    *   **Impacto da Não Correção:** Aspectos importantes de qualidade não considerados.
    *   **Ação:** Autores devem desenvolver o novo diagrama.
    *   **Reinspeção:** Sim, do novo diagrama.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Caso necessário, uma nova reinspeção será agendada.

*   **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados e categorizados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada e registrada
    - Relatório de inspeção foi finalizado e aprovado pelos participantes

### **Inspeção Fagan: Artefato 2/3 - `História de Usuário`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Histórias de usuário, critérios de aceitação, prioridades, rastreabilidade e perfis de usuário.
*   **Objetivo Principal:** Avaliar a qualidade e completude das histórias de usuário, garantindo que atendam aos padrões ágeis e forneçam informações claras para o desenvolvimento.
*   **Materiais Complementares:**
    *   Template de histórias de usuário
    *   Documentação de perfis de usuário
    *   Matriz de rastreabilidade
*   **Simulação de Participantes:**
    *   **Moderador:** Julia Gabriela
    *   **Autores:** João Pedro Costa, Amanda Cruz
    *   **Leitor:** Gabriel Flores
    *   **Inspetor:** Ryan Salles
*   **Simulação de Agenda:**
    *   **Data:** 22/05/2025
    *   **Horário:** 14:30 - 15:00
    *   **Local:** Reunião Online - Microsoft Teams
    *   **Pauta:** Revisão formal das histórias de usuário

#### 2. Visão Geral

*   **Resumo Técnico:** As histórias de usuário são uma técnica ágil para capturar requisitos do ponto de vista do usuário, seguindo o formato "Como [papel] quero [objetivo] para [benefício]".
*   **Contexto no Projeto:** Este artefato é essencial para garantir que as necessidades dos usuários sejam adequadamente capturadas e priorizadas.
*   **Papéis e Responsabilidades:**
    *   **Moderador (Julia):** Garantir que a inspeção mantenha o foco na qualidade das histórias.
    *   **Autores (João Pedro e Amanda):** Explicar as decisões de escrita e priorização.
    *   **Leitor (Gabriel):** Ler as histórias e identificar inconsistências.
    *   **Inspetor (Ryan):** Verificar a conformidade com o padrão e a completude.

#### 3. Checklist de Verificação
- [ ] As histórias seguem o formato "Como [papel] quero [objetivo] para [benefício]"?
- [ ] Os critérios de aceitação são testáveis?
- [ ] As prioridades estão claramente definidas?
- [ ] A rastreabilidade está adequada?
- [ ] Os perfis de usuário estão bem definidos?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Metodológicos:**
        * Algumas histórias não seguem o formato padrão
        * Critérios de aceitação muito genéricos
    *   **Documentação:**
        * Falta de padronização na descrição dos perfis
        * Inconsistências na numeração das histórias
    *   **Consistência:**
        * Divergências na definição de prioridades
        * Rastreabilidade incompleta em algumas histórias
    *   **Omissão:**
        * Faltam critérios de aceitação específicos
        * Ausência de algumas dependências entre histórias
*   **Perguntas Críticas Preparadas:**
    *   "Por que algumas histórias não seguem o formato padrão?"
    *   "Como foram definidos os critérios de aceitação?"
    *   "Como as prioridades foram estabelecidas?"

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Histórias marcadas com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção das `Histórias de Usuário`**
    *   **Data:** 22/05/2025
    *   **Participantes:** Julia Gabriela, João Pedro Costa, Amanda Cruz, Gabriel Flores, Ryan Salles
    *   **Defeitos Logados:**
        1.  **ID 01-US (Formato):** Histórias não padronizadas
            *   *Observação do Inspetor:* "Algumas histórias não seguem o formato padrão, dificultando a compreensão."
        2.  **ID 02-US (Critérios):** Critérios de aceitação genéricos
            *   *Observação do Moderador:* "Os critérios precisam ser mais específicos e testáveis."
        3.  **ID 03-US (Rastreabilidade):** Falta de rastreabilidade
            *   *Observação dos Autores:* "Algumas histórias não estão adequadamente vinculadas aos requisitos."
    *   **Decisões:** Padronizar todas as histórias, detalhar critérios de aceitação e completar a rastreabilidade.

#### 6. Retrabalho

*   **Defeito ID 01-US:**
    *   **Correção Proposta:** Reescrever histórias no formato padrão.
    *   **Impacto da Não Correção:** Dificuldade de compreensão e implementação.
    *   **Ação:** Autores devem revisar e padronizar todas as histórias.
    *   **Reinspeção:** Sim, após a padronização.
*   **Defeito ID 02-US:**
    *   **Correção Proposta:** Detalhar critérios de aceitação.
    *   **Impacto da Não Correção:** Dificuldade em validar implementações.
    *   **Ação:** Autores devem especificar critérios testáveis.
    *   **Reinspeção:** Sim, focada nos critérios.
*   **Defeito ID 03-US:**
    *   **Correção Proposta:** Completar matriz de rastreabilidade.
    *   **Impacto da Não Correção:** Perda de conexão com requisitos.
    *   **Ação:** Autores devem mapear todas as relações.
    *   **Reinspeção:** Sim, da matriz atualizada.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Caso necessário, uma nova reinspeção será agendada.

*   **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados e categorizados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada e registrada
    - Relatório de inspeção foi finalizado e aprovado pelos participantes

### **Inspeção Fagan: Artefato 3/3 - `Backlog`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Épicas, features, histórias, prioridades, dependências e estimativas.
*   **Objetivo Principal:** Avaliar a estrutura e organização do backlog, garantindo que represente adequadamente o escopo do projeto.
*   **Materiais Complementares:**
    *   Documentação de priorização
    *   Histórias de usuário
    *   Critérios de estimativa
*   **Simulação de Participantes:**
    *   **Moderador:** Ryan Salles
    *   **Autores:** João Pedro Costa, Julia Gabriela
    *   **Leitor:** Amanda Cruz
    *   **Inspetor:** Gabriel Flores
*   **Simulação de Agenda:**
    *   **Data:** 22/05/2025
    *   **Horário:** 15:00 - 15:30
    *   **Local:** Reunião Online - Microsoft Teams
    *   **Pauta:** Revisão formal do backlog do produto

#### 2. Visão Geral

*   **Resumo Técnico:** O backlog do produto é uma lista priorizada de todas as funcionalidades desejadas, organizadas em épicas e features.
*   **Contexto no Projeto:** Este artefato é crucial para o planejamento e execução do desenvolvimento ágil.
*   **Papéis e Responsabilidades:**
    *   **Moderador (Ryan):** Garantir que a inspeção mantenha o foco na estrutura e priorização.
    *   **Autores (João Pedro e Julia):** Explicar a organização e critérios de priorização.
    *   **Leitor (Amanda):** Ler o backlog e identificar inconsistências.
    *   **Inspetor (Gabriel):** Verificar a estrutura e completude.

#### 3. Checklist de Verificação
- [ ] Os itens estão adequadamente priorizados?
- [ ] As épicas estão bem definidas?
- [ ] As features estão claramente descritas?
- [ ] A granularidade das histórias é apropriada?
- [ ] As dependências estão mapeadas?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Metodológicos:**
        * Algumas épicas muito abrangentes
        * Granularidade inconsistente entre histórias
    *   **Documentação:**
        * Falta de descrição detalhada em algumas features
        * Critérios de priorização não explícitos
    *   **Consistência:**
        * Divergências na estrutura hierárquica
        * Inconsistências na estimativa de esforço
    *   **Omissão:**
        * Faltam algumas dependências técnicas
        * Ausência de critérios de ordenação
*   **Perguntas Críticas Preparadas:**
    *   "Como foi definida a granularidade das histórias?"
    *   "Quais critérios foram usados para priorização?"
    *   "Como as dependências técnicas foram identificadas?"

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Backlog marcado com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção do `Backlog`**
    *   **Data:** 22/05/2025
    *   **Participantes:** Ryan Salles, João Pedro Costa, Julia Gabriela, Amanda Cruz, Gabriel Flores
    *   **Defeitos Logados:**
        1.  **ID 01-BL (Estrutura):** Épicas muito abrangentes
            *   *Observação do Inspetor:* "Algumas épicas precisam ser divididas para melhor gerenciamento."
        2.  **ID 02-BL (Priorização):** Critérios não explícitos
            *   *Observação do Moderador:* "É necessário documentar os critérios de priorização."
        3.  **ID 03-BL (Dependências):** Mapeamento incompleto
            *   *Observação dos Autores:* "Faltam algumas dependências técnicas importantes."
    *   **Decisões:** Revisar estrutura das épicas, documentar critérios de priorização e completar mapeamento de dependências.

#### 6. Retrabalho

*   **Defeito ID 01-BL:**
    *   **Correção Proposta:** Dividir épicas muito abrangentes.
    *   **Impacto da Não Correção:** Dificuldade de planejamento e execução.
    *   **Ação:** Autores devem reavaliar e reorganizar épicas.
    *   **Reinspeção:** Sim, após a reestruturação.
*   **Defeito ID 02-BL:**
    *   **Correção Proposta:** Documentar critérios de priorização.
    *   **Impacto da Não Correção:** Falta de transparência nas decisões.
    *   **Ação:** Autores devem explicitar critérios.
    *   **Reinspeção:** Sim, dos critérios documentados.
*   **Defeito ID 03-BL:**
    *   **Correção Proposta:** Mapear todas as dependências técnicas.
    *   **Impacto da Não Correção:** Risco de problemas na implementação.
    *   **Ação:** Autores devem completar o mapeamento.
    *   **Reinspeção:** Sim, do mapa de dependências.

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
