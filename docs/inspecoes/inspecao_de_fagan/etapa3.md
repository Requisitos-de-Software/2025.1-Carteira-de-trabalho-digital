# Inspeção Fagan – Etapa 3

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

Para os artefatos de modelagem, nossa inspeção terá um foco especial na verificação da conformidade com as notações e padrões estabelecidos, como UML e NFR Framework. Será dada atenção especial à consistência entre os diferentes modelos produzidos, garantindo que eles se complementem e não apresentem contradições. A rastreabilidade com os requisitos elicitados será cuidadosamente analisada, assegurando que cada elemento modelado tenha uma origem clara nos requisitos. Também será avaliada a clareza e completude das representações, verificando se os modelos comunicam efetivamente as informações necessárias para as próximas etapas do desenvolvimento.

### Processo de Inspeção

O processo de inspeção Fagan é rigorosamente estruturado e requer:
1. Definição clara do estado do produto de trabalho a ser inspecionado
2. Participantes com papéis bem definidos
3. Tempo adequado de preparação para os inspetores
4. Checklists específicos para guiar a inspeção
5. Critérios de entrada e saída bem estabelecidos
6. Documentação apropriada e coleta de dados
7. Procedimentos claros para retrabalho e verificação

### **Inspeção Fagan: Artefato 1/5 - `Cenários`**

#### 1. Planejamento da Inspeção

* **Elementos do Artefato:** Descrição dos cenários, atores, contexto, pré-condições, fluxo principal, pós-condições e exceções.
* **Objetivo Principal:** Avaliar a qualidade e completude dos cenários que descrevem as interações dos usuários com o sistema.
* **Materiais Complementares:**
    * Requisitos elicitados
    * Casos de uso
    * Léxicos
* **Simulação de Participantes:**
    * **Moderador:** Julia Gabriela
    * **Autores:** Amanda Cruz, João Pedro Costa, Ryan Salles
    * **Leitor:** Gabriel Flores
    * **Inspetor:** João Igor
* **Simulação de Agenda:**
    * **Data:** 22/06/2025
    * **Horário:** 14:00 - 14:30
    * **Pauta:** Revisão formal do artefato de cenários.

#### 2. Visão Geral

* **Resumo Técnico:** O documento apresenta 16 cenários detalhados que descrevem diferentes interações com o sistema CadÚnico.
* **Contexto no Projeto:** Os cenários são fundamentais para entender como os usuários interagem com o sistema.
* **Papéis e Responsabilidades:**
    * **Moderador (Julia):** Garantir foco na qualidade e completude dos cenários.
    * **Autores (Amanda/João/Ryan):** Esclarecer o processo de criação dos cenários.
    * **Leitor (Gabriel):** Verificar a clareza e estrutura do documento.
    * **Inspetor (João Igor):** Avaliar a consistência dos cenários.

#### 3. Checklist de Verificação
- [ ] Os cenários cobrem todas as principais funcionalidades?
- [ ] Os atores estão claramente identificados?
- [ ] O contexto está bem descrito?
- [ ] As pré-condições são realistas?
- [ ] Os fluxos principais são claros e completos?
- [ ] As pós-condições são coerentes?
- [ ] As exceções são adequadas?
- [ ] A rastreabilidade está completa?
- [ ] O histórico de versão está completo e padronizado?

#### 4. Preparação

* **Análise Detalhada (Defeitos Encontrados):**
    * **Defeito Metodológico:** Alguns cenários não seguem o padrão estabelecido.
    * **Defeito de Consistência:** Variações na descrição de atores similares.
    * **Defeito de Documentação:** Faltam exceções em alguns cenários.
    * **Omissão:** Alguns fluxos alternativos não foram considerados.

* **Perguntas Críticas Preparadas:**
    * "Como foram identificados os cenários principais?"
    * "Como foi validada a completude dos fluxos?"
    * "Como foram definidas as exceções?"

#### 5. Reunião de Inspeção

* **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Documento marcado com observações
    - Todos os participantes confirmaram revisão prévia
    - Checklist de verificação preenchido

* **Ata da Reunião de Inspeção dos `Cenários`**
    * **Data:** 22/06/2025
    * **Participantes:** Julia Gabriela, Amanda Cruz, João Pedro Costa, Ryan Salles, Gabriel Flores, João Igor
    * **Defeitos Logados:**
        1. **ID 01-CN (Padronização):** Padronizar descrição de atores.
            * *Observação do Inspetor:* "Necessário uniformizar como os atores são descritos."
        2. **ID 02-CN (Completude):** Adicionar exceções faltantes.
            * *Observação do Leitor:* "Alguns cenários têm poucas exceções."
        3. **ID 03-CN (Fluxos):** Incluir fluxos alternativos.
            * *Observação do Moderador:* "Faltam fluxos alternativos importantes."

* **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada
    - Relatório de inspeção foi finalizado

#### 6. Retrabalho

* **Defeito ID 01-CN:**
    * **Correção Proposta:** Criar padrão de descrição.
    * **Impacto da Não Correção:** Dificuldade de compreensão.
    * **Ação:** Autores devem revisar descrições.
    * **Reinspeção:** Não necessária.

* **Defeito ID 02-CN:**
    * **Correção Proposta:** Complementar exceções.
    * **Impacto da Não Correção:** Cenários incompletos.
    * **Ação:** Equipe deve adicionar exceções.
    * **Reinspeção:** Sim, após adições.

* **Defeito ID 03-CN:**
    * **Correção Proposta:** Adicionar fluxos alternativos.
    * **Impacto da Não Correção:** Cobertura incompleta.
    * **Ação:** Autores devem incluir fluxos.
    * **Reinspeção:** Sim, após inclusão.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Uma nova inspeção será agendada para os itens que requerem reinspeção.

---

### **Inspeção Fagan: Artefato 2/5 - `Léxico`**

#### 1. Planejamento da Inspeção

* **Elementos do Artefato:** Termos, classificações, sinônimos, noções e impactos.
* **Objetivo Principal:** Avaliar a qualidade e completude do léxico que define os termos importantes do domínio.
* **Materiais Complementares:**
    * Cenários
    * Casos de uso
    * Requisitos elicitados
* **Simulação de Participantes:**
    * **Moderador:** João Pedro Costa
    * **Autores:** Gabriel Flores, João Igor
    * **Leitor:** Ryan Salles
    * **Inspetor:** Julia Gabriela
* **Simulação de Agenda:**
    * **Data:** 22/06/2025
    * **Horário:** 14:30 - 15:00
    * **Pauta:** Revisão formal do artefato de léxico.

#### 2. Visão Geral

* **Resumo Técnico:** O documento apresenta um léxico com 35 termos classificados em verbos, objetos e estados.
* **Contexto no Projeto:** O léxico é essencial para estabelecer um vocabulário comum e consistente.
* **Papéis e Responsabilidades:**
    * **Moderador (João):** Garantir foco na qualidade e completude do léxico.
    * **Autores (Gabriel/João I.):** Esclarecer o processo de identificação e descrição dos termos.
    * **Leitor (Ryan):** Verificar a clareza e estrutura do documento.
    * **Inspetor (Julia):** Avaliar a consistência das definições.

#### 3. Checklist de Verificação
- [ ] Todos os termos importantes estão incluídos?
- [ ] As classificações estão corretas?
- [ ] Os sinônimos são adequados?
- [ ] As noções são claras e precisas?
- [ ] Os impactos são bem descritos?
- [ ] Há consistência nas definições?
- [ ] A formatação está padronizada?
- [ ] O histórico de versão está completo?

#### 4. Preparação

* **Análise Detalhada (Defeitos Encontrados):**
    * **Defeito Metodológico:** Inconsistência na classificação de alguns termos.
    * **Defeito de Completude:** Faltam termos importantes do domínio.
    * **Defeito de Documentação:** Algumas noções e impactos são vagos.
    * **Omissão:** Faltam sinônimos para alguns termos.

* **Perguntas Críticas Preparadas:**
    * "Como foram identificados os termos principais?"
    * "Qual o critério para classificação dos termos?"
    * "Como foi validada a completude do léxico?"

#### 5. Reunião de Inspeção

* **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Documento marcado com observações
    - Todos os participantes confirmaram revisão prévia
    - Checklist de verificação preenchido

* **Ata da Reunião de Inspeção do `Léxico`**
    * **Data:** 22/06/2025
    * **Participantes:** João Pedro Costa, Gabriel Flores, João Igor, Ryan Salles, Julia Gabriela
    * **Defeitos Logados:**
        1. **ID 01-LX (Classificação):** Revisar classificações.
            * *Observação do Inspetor:* "Alguns termos têm classificação questionável."
        2. **ID 02-LX (Completude):** Adicionar termos faltantes.
            * *Observação do Leitor:* "Identificados termos importantes não incluídos."
        3. **ID 03-LX (Clareza):** Melhorar noções e impactos.
            * *Observação do Moderador:* "Algumas definições estão vagas."

* **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada
    - Relatório de inspeção foi finalizado

#### 6. Retrabalho

* **Defeito ID 01-LX:**
    * **Correção Proposta:** Revisar classificações.
    * **Impacto da Não Correção:** Confusão na interpretação.
    * **Ação:** Autores devem revisar critérios.
    * **Reinspeção:** Sim, após revisão.

* **Defeito ID 02-LX:**
    * **Correção Proposta:** Incluir termos faltantes.
    * **Impacto da Não Correção:** Léxico incompleto.
    * **Ação:** Equipe deve identificar e adicionar termos.
    * **Reinspeção:** Sim, após adições.

* **Defeito ID 03-LX:**
    * **Correção Proposta:** Reescrever definições vagas.
    * **Impacto da Não Correção:** Ambiguidade no entendimento.
    * **Ação:** Autores devem melhorar descrições.
    * **Reinspeção:** Não necessária.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Uma nova inspeção será agendada para os itens que requerem reinspeção.

---

### **Inspeção Fagan: Artefato 3/5 - `Casos de Uso`**

#### 1. Planejamento da Inspeção

* **Elementos do Artefato:** Diagrama de casos de uso, especificações, atores, relacionamentos e fluxos.
* **Objetivo Principal:** Avaliar a qualidade e completude dos casos de uso que modelam as funcionalidades do sistema.
* **Materiais Complementares:**
    * Cenários
    * Léxico
    * Requisitos elicitados
* **Simulação de Participantes:**
    * **Moderador:** Ryan Salles
    * **Autores:** João Pedro Costa, Amanda Cruz
    * **Leitor:** Julia Gabriela
    * **Inspetor:** Gabriel Flores
* **Simulação de Agenda:**
    * **Data:** 22/06/2025
    * **Horário:** 15:00 - 15:30
    * **Pauta:** Revisão formal do artefato de casos de uso.

#### 2. Visão Geral

* **Resumo Técnico:** O documento apresenta o diagrama de casos de uso e suas especificações detalhadas.
* **Contexto no Projeto:** Os casos de uso são fundamentais para modelar as interações entre usuários e sistema.
* **Papéis e Responsabilidades:**
    * **Moderador (Ryan):** Garantir foco na qualidade e completude dos casos de uso.
    * **Autores (João/Amanda):** Esclarecer o processo de modelagem.
    * **Leitor (Julia):** Verificar a clareza e estrutura do documento.
    * **Inspetor (Gabriel):** Avaliar a consistência dos casos de uso.

#### 3. Checklist de Verificação
- [ ] O diagrama está bem estruturado e legível?
- [ ] Os atores estão corretamente identificados?
- [ ] Os relacionamentos são apropriados?
- [ ] As especificações são completas?
- [ ] Os fluxos principais estão claros?
- [ ] Os fluxos alternativos são adequados?
- [ ] As pré e pós-condições são coerentes?
- [ ] A rastreabilidade está completa?
- [ ] O histórico de versão está completo?

#### 4. Preparação

* **Análise Detalhada (Defeitos Encontrados):**
    * **Defeito Metodológico:** Inconsistência na especificação dos casos de uso.
    * **Defeito de Modelagem:** Alguns relacionamentos são questionáveis.
    * **Defeito de Documentação:** Fluxos alternativos incompletos.
    * **Omissão:** Faltam alguns casos de uso importantes.

* **Perguntas Críticas Preparadas:**
    * "Como foram identificados os casos de uso principais?"
    * "Qual o critério para definição dos relacionamentos?"
    * "Como foi validada a completude das especificações?"

#### 5. Reunião de Inspeção

* **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Documento marcado com observações
    - Todos os participantes confirmaram revisão prévia
    - Checklist de verificação preenchido

* **Ata da Reunião de Inspeção dos `Casos de Uso`**
    * **Data:** 22/06/2025
    * **Participantes:** Ryan Salles, João Pedro Costa, Amanda Cruz, Julia Gabriela, Gabriel Flores
    * **Defeitos Logados:**
        1. **ID 01-UC (Especificação):** Padronizar especificações.
            * *Observação do Inspetor:* "Especificações com níveis diferentes de detalhamento."
        2. **ID 02-UC (Modelagem):** Revisar relacionamentos.
            * *Observação do Leitor:* "Alguns relacionamentos parecem inadequados."
        3. **ID 03-UC (Completude):** Adicionar fluxos alternativos.
            * *Observação do Moderador:* "Fluxos alternativos insuficientes."

* **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada
    - Relatório de inspeção foi finalizado

#### 6. Retrabalho

* **Defeito ID 01-UC:**
    * **Correção Proposta:** Criar template de especificação.
    * **Impacto da Não Correção:** Dificuldade de compreensão.
    * **Ação:** Autores devem padronizar especificações.
    * **Reinspeção:** Sim, após padronização.

* **Defeito ID 02-UC:**
    * **Correção Proposta:** Avaliar e corrigir relacionamentos.
    * **Impacto da Não Correção:** Modelo incorreto.
    * **Ação:** Equipe deve revisar relacionamentos.
    * **Reinspeção:** Sim, após revisão.

* **Defeito ID 03-UC:**
    * **Correção Proposta:** Complementar fluxos alternativos.
    * **Impacto da Não Correção:** Especificações incompletas.
    * **Ação:** Autores devem adicionar fluxos.
    * **Reinspeção:** Não necessária.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Uma nova inspeção será agendada para os itens que requerem reinspeção.

---

### **Inspeção Fagan: Artefato 4/5 - `Especificação Suplementar`**

#### 1. Planejamento da Inspeção

* **Elementos do Artefato:** Requisitos não-funcionais, atributos de qualidade, restrições e interfaces.
* **Objetivo Principal:** Avaliar a qualidade e completude das especificações suplementares do sistema.
* **Materiais Complementares:**
    * Requisitos elicitados
    * Casos de uso
    * Cenários
* **Simulação de Participantes:**
    * **Moderador:** Gabriel Flores
    * **Autores:** Ryan Salles, Julia Gabriela, João Pedro Costa
    * **Leitor:** João Pedro Costa
    * **Inspetor:** Amanda Cruz
* **Simulação de Agenda:**
    * **Data:** 22/06/2025
    * **Horário:** 15:30 - 16:00
    * **Pauta:** Revisão formal do artefato de especificação suplementar.

#### 2. Visão Geral

* **Resumo Técnico:** O documento apresenta os requisitos não-funcionais e restrições do sistema usando o modelo FURPS+.
* **Contexto no Projeto:** As especificações suplementares complementam os casos de uso com requisitos não-funcionais.
* **Papéis e Responsabilidades:**
    * **Moderador (Gabriel):** Garantir foco na qualidade e completude das especificações.
    * **Autores (Ryan/Julia):** Esclarecer o processo de especificação.
    * **Leitor (João):** Verificar a clareza e estrutura do documento.
    * **Inspetor (Amanda):** Avaliar a consistência das especificações.

#### 3. Checklist de Verificação
- [ ] O modelo FURPS+ está bem aplicado?
- [ ] Os requisitos de usabilidade são adequados?
- [ ] Os requisitos de confiabilidade estão claros?
- [ ] Os requisitos de desempenho são mensuráveis?
- [ ] Os requisitos de suportabilidade são completos?
- [ ] As restrições estão bem definidas?
- [ ] As interfaces são bem especificadas?
- [ ] O histórico de versão está completo?

#### 4. Preparação

* **Análise Detalhada (Defeitos Encontrados):**
    * **Defeito Metodológico:** Alguns requisitos não seguem o FURPS+.
    * **Defeito de Mensurabilidade:** Requisitos de desempenho vagos.
    * **Defeito de Documentação:** Faltam critérios de aceitação.
    * **Omissão:** Interfaces externas não detalhadas.

* **Perguntas Críticas Preparadas:**
    * "Como foram definidos os critérios de qualidade?"
    * "Como serão medidos os requisitos de desempenho?"
    * "Como foram identificadas as interfaces?"

#### 5. Reunião de Inspeção

* **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Documento marcado com observações
    - Todos os participantes confirmaram revisão prévia
    - Checklist de verificação preenchido

* **Ata da Reunião de Inspeção da `Especificação Suplementar`**
    * **Data:** 22/06/2025
    * **Participantes:** Gabriel Flores, Ryan Salles, Julia Gabriela, João Pedro Costa, Amanda Cruz
    * **Defeitos Logados:**
        1. **ID 01-ES (FURPS+):** Ajustar categorização.
            * *Observação do Inspetor:* "Alguns requisitos estão em categorias erradas."
        2. **ID 02-ES (Mensurabilidade):** Definir métricas.
            * *Observação do Leitor:* "Requisitos de desempenho precisam ser quantificáveis."
        3. **ID 03-ES (Interfaces):** Detalhar interfaces.
            * *Observação do Moderador:* "Interfaces externas precisam ser melhor especificadas."

* **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada
    - Relatório de inspeção foi finalizado

#### 6. Retrabalho

* **Defeito ID 01-ES:**
    * **Correção Proposta:** Revisar categorização FURPS+.
    * **Impacto da Não Correção:** Organização incorreta.
    * **Ação:** Autores devem recategorizar requisitos.
    * **Reinspeção:** Sim, após revisão.

* **Defeito ID 02-ES:**
    * **Correção Proposta:** Adicionar métricas específicas.
    * **Impacto da Não Correção:** Dificuldade de validação.
    * **Ação:** Equipe deve definir métricas.
    * **Reinspeção:** Sim, após definição.

* **Defeito ID 03-ES:**
    * **Correção Proposta:** Especificar interfaces externas.
    * **Impacto da Não Correção:** Integração comprometida.
    * **Ação:** Autores devem detalhar interfaces.
    * **Reinspeção:** Não necessária.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Uma nova inspeção será agendada para os itens que requerem reinspeção.

---

### **Inspeção Fagan: Artefato 5/5 - `Etapa 3`**

#### 1. Planejamento da Inspeção

* **Elementos do Artefato:** Estrutura da inspeção, documentação dos defeitos, propostas de correção.
* **Objetivo Principal:** Avaliar a qualidade e completude da documentação da Etapa 3 da inspeção Fagan.
* **Materiais Complementares:**
    * Etapas 1 e 2 da inspeção
    * Artefatos inspecionados
    * Critérios de inspeção
* **Simulação de Participantes:**
    * **Moderador:** Amanda Cruz
    * **Autores:** João Pedro Costa, Ryan Salles
    * **Leitor:** Julia Gabriela
    * **Inspetor:** Gabriel Flores
* **Simulação de Agenda:**
    * **Data:** 22/06/2025
    * **Horário:** 16:00 - 16:30
    * **Pauta:** Revisão formal do artefato da Etapa 3.

#### 2. Visão Geral

* **Resumo Técnico:** O documento apresenta a documentação da Etapa 3 da inspeção Fagan, incluindo defeitos encontrados e propostas de correção.
* **Contexto no Projeto:** Esta etapa é crucial para garantir a qualidade dos artefatos inspecionados.
* **Papéis e Responsabilidades:**
    * **Moderador (Amanda):** Garantir foco na qualidade da documentação.
    * **Autores (João/Ryan):** Esclarecer o processo de documentação.
    * **Leitor (Julia):** Verificar a clareza e estrutura do documento.
    * **Inspetor (Gabriel):** Avaliar a consistência da documentação.

#### 3. Checklist de Verificação
- [ ] A estrutura da inspeção está clara?
- [ ] Os defeitos estão bem documentados?
- [ ] As propostas de correção são adequadas?
- [ ] Os impactos estão bem avaliados?
- [ ] As necessidades de reinspeção estão justificadas?
- [ ] A documentação está completa?
- [ ] O formato está padronizado?
- [ ] O histórico de versão está completo?

#### 4. Preparação

* **Análise Detalhada (Defeitos Encontrados):**
    * **Defeito Metodológico:** Inconsistência na documentação dos defeitos.
    * **Defeito de Completude:** Algumas propostas de correção vagas.
    * **Defeito de Documentação:** Falta padronização no formato.
    * **Omissão:** Alguns impactos não avaliados.

* **Perguntas Críticas Preparadas:**
    * "Como foi estruturada a documentação dos defeitos?"
    * "Qual o critério para definir necessidade de reinspeção?"
    * "Como foram avaliados os impactos?"

#### 5. Reunião de Inspeção

* **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Documento marcado com observações
    - Todos os participantes confirmaram revisão prévia
    - Checklist de verificação preenchido

* **Ata da Reunião de Inspeção da `Etapa 3`**
    * **Data:** 22/06/2025
    * **Participantes:** Amanda Cruz, João Pedro Costa, Ryan Salles, Julia Gabriela, Gabriel Flores
    * **Defeitos Logados:**
        1. **ID 01-E3 (Documentação):** Padronizar formato.
            * *Observação do Inspetor:* "Formato de documentação varia entre seções."
        2. **ID 02-E3 (Completude):** Detalhar correções.
            * *Observação do Leitor:* "Algumas propostas de correção precisam ser mais específicas."
        3. **ID 03-E3 (Impactos):** Avaliar impactos.
            * *Observação do Moderador:* "Faltam avaliações de impacto em alguns defeitos."

* **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada
    - Relatório de inspeção foi finalizado

#### 6. Retrabalho

* **Defeito ID 01-E3:**
    * **Correção Proposta:** Criar template de documentação.
    * **Impacto da Não Correção:** Dificuldade de compreensão.
    * **Ação:** Autores devem padronizar formato.
    * **Reinspeção:** Sim, após padronização.

* **Defeito ID 02-E3:**
    * **Correção Proposta:** Especificar correções.
    * **Impacto da Não Correção:** Correções inadequadas.
    * **Ação:** Equipe deve detalhar propostas.
    * **Reinspeção:** Sim, após detalhamento.

* **Defeito ID 03-E3:**
    * **Correção Proposta:** Completar avaliações.
    * **Impacto da Não Correção:** Decisões mal embasadas.
    * **Ação:** Autores devem avaliar impactos.
    * **Reinspeção:** Não necessária.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Uma nova inspeção será agendada para os itens que requerem reinspeção.

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