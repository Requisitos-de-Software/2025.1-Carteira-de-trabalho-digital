# Inspeção Fagan – Etapa 2

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

Para os artefatos de elicitação, nossa inspeção terá um foco especial na verificação da completude e clareza das técnicas utilizadas, garantindo que todas as fontes relevantes de requisitos foram adequadamente exploradas. Será dada atenção especial à consistência entre as diferentes técnicas de elicitação empregadas, à rastreabilidade das informações coletadas e à adequação das técnicas ao contexto específico do projeto. A análise também considerará se as personas, perfis de usuário e outros artefatos de elicitação refletem adequadamente o público-alvo do sistema.

### Processo de Inspeção

O processo de inspeção Fagan é rigorosamente estruturado e requer:
1. Definição clara do estado do produto de trabalho a ser inspecionado
2. Participantes com papéis bem definidos
3. Tempo adequado de preparação para os inspetores
4. Checklists específicos para guiar a inspeção
5. Critérios de entrada e saída bem estabelecidos
6. Documentação apropriada e coleta de dados
7. Procedimentos claros para retrabalho e verificação

## Funções dos autores

| Nome                                              | Função                                                                  | 
|---------------------------------------------------|-------------------------------------------------------------------------|
|[João Pedro Costa](https://github.com/johnaopedro) |Criação da página; Desenvolvimento da introdução; Criação das tabelas; Criação do template da inspeção pelo metodo de Fagan; Desenvolvimento de todas as inspeções. | 
|[Ryan Salles](https://github.com/RA-Salles)        |Revisão geral.                                                           | 
<center>
    Autor(es): 
    <a href="https://github.com/johnaopedro" target="_blank">João Pedro Costa</a>
</center>

---

### **Inspeção Fagan: Artefato 1/13 - `Análise de Documentação`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Introdução, metodologia, documentos analisados, requisitos elicitados (funcionais e não funcionais), vídeos, validação e referências.
*   **Objetivo Principal:** Documentar a análise de documentos oficiais e técnicos relacionados ao Cadastro Único para elicitar requisitos do sistema.
*   **Materiais Complementares:**
    *   Documentos oficiais analisados
    *   Padrões de documentação do projeto
    *   Histórico de versões
*   **Simulação de Participantes:**
    *   **Moderador:** Ryan Salles
    *   **Autor:** João Pedro Costa
    *   **Leitor:** Amanda Cruz
    *   **Inspetor:** Julia Gabriela
*   **Simulação de Agenda:**
    *   **Data:** 21/06/2025
    *   **Horário:** 19:00 - 19:30
    *   **Pauta:** Revisão formal do artefato de análise de documentação.

#### 2. Visão Geral

*   **Resumo Técnico:** O documento apresenta uma análise sistemática de documentos oficiais relacionados ao Cadastro Único, incluindo documentos do IBGE e relatórios governamentais. A partir dessa análise, são elicitados requisitos funcionais e não funcionais.
*   **Contexto no Projeto:** Este artefato é fundamental por fornecer uma base sólida de requisitos derivados de documentos oficiais, garantindo alinhamento com as necessidades reais do sistema.
*   **Papéis e Responsabilidades:**
    *   **Moderador (Ryan):** Garantir que a inspeção mantenha o foco na qualidade da análise documental.
    *   **Autor (João Pedro):** Esclarecer as escolhas feitas na análise dos documentos.
    *   **Leitor (Amanda):** Verificar a clareza e completude da documentação.
    *   **Inspetor (Julia):** Avaliar a consistência da análise e dos requisitos elicitados.

#### 3. Checklist de Verificação
- [ ] A metodologia está claramente descrita?
- [ ] Os documentos analisados estão devidamente referenciados?
- [ ] Os requisitos elicitados são rastreáveis aos documentos fonte?
- [ ] A classificação entre RF e RNF está correta?
- [ ] As referências estão no formato padronizado?
- [ ] O histórico de versão está completo e padronizado?
- [ ] A validação está documentada adequadamente?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Defeito Técnico (Rastreabilidade):** Alguns requisitos não possuem clara ligação com os documentos analisados.
    *   **Defeito de Padronização:** Inconsistência no formato de citação dos documentos fonte.
    *   **Defeito de Conteúdo:** Alguns requisitos poderiam ser mais específicos em relação às funcionalidades descritas.
    *   **Omissão:** Faltam detalhes sobre como a validação foi conduzida.

*   **Perguntas Críticas Preparadas:**
    *   "Como foi estabelecida a rastreabilidade entre os documentos e os requisitos?"
    *   "Qual foi o critério para classificação entre RF e RNF?"
    *   "Como foi realizada a validação dos requisitos elicitados?"

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Documento marcado com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção do `Análise de Documentação`**
    *   **Data:** 21/06/2025
    *   **Participantes:** Ryan Salles, João Pedro Costa, Amanda Cruz, Julia Gabriela
    *   **Defeitos Logados:**
        1.  **ID 01-AD (Rastreabilidade):** Melhorar a ligação entre requisitos e documentos fonte.
            *   *Observação do Inspetor:* "Necessário adicionar referências diretas aos trechos dos documentos que originaram cada requisito."
        2.  **ID 02-AD (Padronização):** Padronizar formato de citações.
            *   *Observação do Leitor:* "Diferentes formatos de citação sendo utilizados ao longo do documento."
        3.  **ID 03-AD (Validação):** Detalhar processo de validação.
            *   *Observação do Moderador:* "A seção de validação precisa ser mais detalhada."

*   **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados e categorizados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada e registrada
    - Relatório de inspeção foi finalizado e aprovado pelos participantes

#### 6. Retrabalho

*   **Defeito ID 01-AD:**
    *   **Correção Proposta:** Adicionar matriz de rastreabilidade ligando requisitos aos documentos fonte.
    *   **Impacto da Não Correção:** Dificuldade em validar a origem dos requisitos.
    *   **Ação:** Autor deve criar matriz de rastreabilidade.
    *   **Reinspeção:** Sim, necessária após adição da matriz.

*   **Defeito ID 02-AD:**
    *   **Correção Proposta:** Adotar formato ABNT para todas as citações.
    *   **Impacto da Não Correção:** Inconsistência na documentação.
    *   **Ação:** Autor deve revisar e padronizar citações.
    *   **Reinspeção:** Não necessária.

*   **Defeito ID 03-AD:**
    *   **Correção Proposta:** Expandir seção de validação com detalhes do processo.
    *   **Impacto da Não Correção:** Falta de transparência no processo de validação.
    *   **Ação:** Autor deve detalhar processo de validação.
    *   **Reinspeção:** Sim, após expansão da seção.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Uma nova inspeção será agendada para os itens que requerem reinspeção.

---

### **Inspeção Fagan: Artefato 2/13 - `Entrevista`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Introdução sobre a técnica de entrevista, metodologia, participantes, roteiro de perguntas, relatório das entrevistas, análise das respostas, requisitos identificados e vídeos das entrevistas.
*   **Objetivo Principal:** Documentar o processo de elicitação de requisitos através de entrevistas com usuários reais do sistema.
*   **Materiais Complementares:**
    *   Gravações das entrevistas
    *   Relatório das entrevistas em PDF
    *   Padrões de documentação do projeto
*   **Simulação de Participantes:**
    *   **Moderador:** Amanda Cruz
    *   **Autores:** Julia Gabriela, Gabriel Flores, João Pedro Costa
    *   **Leitor:** João Pedro Costa
    *   **Inspetor:** Ryan Salles
*   **Simulação de Agenda:**
    *   **Data:** 21/06/2025
    *   **Horário:** 19:30 - 20:00
    *   **Pauta:** Revisão formal do artefato de entrevista.

#### 2. Visão Geral

*   **Resumo Técnico:** O documento apresenta uma abordagem estruturada para a realização de entrevistas, incluindo um roteiro bem definido, gravações das entrevistas e uma análise detalhada das respostas obtidas. Os requisitos foram elicitados a partir das necessidades expressas pelos usuários.
*   **Contexto no Projeto:** As entrevistas são uma fonte valiosa de requisitos por permitirem contato direto com usuários reais do sistema, fornecendo insights sobre necessidades e problemas reais.
*   **Papéis e Responsabilidades:**
    *   **Moderador (Amanda):** Garantir que a inspeção mantenha foco na qualidade e completude do processo de entrevista.
    *   **Autores (Julia/Gabriel):** Esclarecer as escolhas metodológicas e análises realizadas.
    *   **Leitor (João Pedro):** Verificar a clareza e estrutura do documento.
    *   **Inspetor (Ryan):** Avaliar a consistência entre as entrevistas e os requisitos elicitados.

#### 3. Checklist de Verificação
- [ ] A metodologia de entrevista está claramente descrita?
- [ ] O perfil dos entrevistados está adequadamente documentado?
- [ ] O roteiro de perguntas é coerente com os objetivos?
- [ ] As entrevistas estão devidamente gravadas e transcritas?
- [ ] A análise das respostas é consistente?
- [ ] Os requisitos elicitados têm clara relação com as entrevistas?
- [ ] A validação dos requisitos está documentada?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Defeito Metodológico:** Algumas perguntas do roteiro poderiam ser mais objetivas.
    *   **Defeito de Análise:** A relação entre algumas respostas e os requisitos elicitados não está clara.
    *   **Defeito de Documentação:** Falta padronização na apresentação das transcrições.
    *   **Omissão:** Alguns vídeos de entrevista não possuem legendas ou transcrição.

*   **Perguntas Críticas Preparadas:**
    *   "Como foi feita a seleção dos entrevistados?"
    *   "Qual foi o critério para transformar respostas em requisitos?"
    *   "Como foi validada a interpretação das respostas?"

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Documento marcado com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção do `Entrevista`**
    *   **Data:** 21/06/2025
    *   **Participantes:** Amanda Cruz, Julia Gabriela, Gabriel Flores, João Pedro Costa, Ryan Salles
    *   **Defeitos Logados:**
        1.  **ID 01-ENT (Metodologia):** Melhorar objetividade das perguntas.
            *   *Observação do Inspetor:* "Algumas perguntas são muito abertas e poderiam ser mais direcionadas."
        2.  **ID 02-ENT (Rastreabilidade):** Melhorar ligação entre respostas e requisitos.
            *   *Observação do Leitor:* "Difícil identificar quais respostas geraram quais requisitos."
        3.  **ID 03-ENT (Acessibilidade):** Adicionar transcrições.
            *   *Observação do Moderador:* "Necessário garantir acessibilidade com transcrições completas."

*   **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados e categorizados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada e registrada
    - Relatório de inspeção foi finalizado e aprovado pelos participantes

#### 6. Retrabalho

*   **Defeito ID 01-ENT:**
    *   **Correção Proposta:** Revisar e refinar o roteiro de perguntas.
    *   **Impacto da Não Correção:** Respostas potencialmente dispersas ou incompletas.
    *   **Ação:** Autores devem revisar e ajustar o roteiro.
    *   **Reinspeção:** Não necessária.

*   **Defeito ID 02-ENT:**
    *   **Correção Proposta:** Criar matriz de rastreabilidade entre respostas e requisitos.
    *   **Impacto da Não Correção:** Dificuldade em validar a origem dos requisitos.
    *   **Ação:** Autores devem criar matriz de rastreabilidade.
    *   **Reinspeção:** Sim, após criação da matriz.

*   **Defeito ID 03-ENT:**
    *   **Correção Proposta:** Adicionar transcrições completas das entrevistas.
    *   **Impacto da Não Correção:** Problemas de acessibilidade.
    *   **Ação:** Autores devem providenciar transcrições.
    *   **Reinspeção:** Sim, após adição das transcrições.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Uma nova inspeção será agendada para os itens que requerem reinspeção.

---

### **Inspeção Fagan: Artefato 3/13 - `Introdução das Técnicas de Elicitação`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Introdução geral sobre técnicas de elicitação, descrição detalhada de cada técnica, justificativa das técnicas selecionadas.
*   **Objetivo Principal:** Apresentar e justificar as técnicas de elicitação de requisitos escolhidas para o projeto.
*   **Materiais Complementares:**
    *   Bibliografia sobre técnicas de elicitação
    *   Padrões de documentação do projeto
    *   Histórico de versões
*   **Simulação de Participantes:**
    *   **Moderador:** João Pedro Costa
    *   **Autor:** Gabriel Flores
    *   **Leitor:** Julia Gabriela
    *   **Inspetor:** Ryan Salles
*   **Simulação de Agenda:**
    *   **Data:** 21/06/2025
    *   **Horário:** 20:00 - 20:30
    *   **Pauta:** Revisão formal do artefato de introdução das técnicas.

#### 2. Visão Geral

*   **Resumo Técnico:** O documento apresenta uma visão geral das técnicas de elicitação de requisitos, com foco especial nas técnicas selecionadas para o projeto: análise de documentação, introspecção, entrevista e questionário.
*   **Contexto no Projeto:** Este artefato é fundamental por estabelecer a base metodológica para todo o processo de elicitação de requisitos do projeto.
*   **Papéis e Responsabilidades:**
    *   **Moderador (João Pedro):** Garantir que a inspeção mantenha foco na qualidade e completude das descrições.
    *   **Autor (Gabriel):** Esclarecer as escolhas metodológicas.
    *   **Leitor (Julia):** Verificar a clareza e estrutura do documento.
    *   **Inspetor (Ryan):** Avaliar a consistência e fundamentação das técnicas.

#### 3. Checklist de Verificação
- [ ] A introdução contextualiza adequadamente o tema?
- [ ] As técnicas estão descritas com clareza e completude?
- [ ] A justificativa para seleção das técnicas é coerente?
- [ ] As referências bibliográficas são adequadas e atuais?
- [ ] O texto está bem estruturado e coeso?
- [ ] As limitações de cada técnica são apresentadas?
- [ ] O histórico de versão está completo e padronizado?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Defeito Conceitual:** Algumas técnicas poderiam ter descrições mais aprofundadas.
    *   **Defeito de Fundamentação:** Algumas afirmações carecem de referências.
    *   **Defeito de Estrutura:** A organização do texto poderia ser mais clara.
    *   **Omissão:** Faltam exemplos práticos de aplicação das técnicas.

*   **Perguntas Críticas Preparadas:**
    *   "Por que essas técnicas específicas foram escolhidas?"
    *   "Como as limitações de cada técnica serão mitigadas?"
    *   "Qual a complementaridade entre as técnicas selecionadas?"

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Documento marcado com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção do `Introdução das Técnicas`**
    *   **Data:** 21/06/2025
    *   **Participantes:** João Pedro Costa, Gabriel Flores, Julia Gabriela, Ryan Salles
    *   **Defeitos Logados:**
        1.  **ID 01-INT (Fundamentação):** Adicionar mais referências.
            *   *Observação do Inspetor:* "Algumas afirmações precisam de embasamento teórico."
        2.  **ID 02-INT (Estrutura):** Melhorar organização do texto.
            *   *Observação do Leitor:* "A sequência de apresentação das técnicas pode ser mais lógica."
        3.  **ID 03-INT (Exemplificação):** Incluir exemplos práticos.
            *   *Observação do Moderador:* "Exemplos ajudariam a entender melhor cada técnica."

*   **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados e categorizados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada e registrada
    - Relatório de inspeção foi finalizado e aprovado pelos participantes

#### 6. Retrabalho

*   **Defeito ID 01-INT:**
    *   **Correção Proposta:** Adicionar referências bibliográficas atuais.
    *   **Impacto da Não Correção:** Falta de embasamento teórico.
    *   **Ação:** Autor deve pesquisar e adicionar referências.
    *   **Reinspeção:** Não necessária.

*   **Defeito ID 02-INT:**
    *   **Correção Proposta:** Reorganizar a apresentação das técnicas.
    *   **Impacto da Não Correção:** Dificuldade de compreensão.
    *   **Ação:** Autor deve reestruturar o documento.
    *   **Reinspeção:** Sim, após reestruturação.

*   **Defeito ID 03-INT:**
    *   **Correção Proposta:** Adicionar exemplos práticos para cada técnica.
    *   **Impacto da Não Correção:** Compreensão abstrata das técnicas.
    *   **Ação:** Autor deve incluir exemplos.
    *   **Reinspeção:** Não necessária.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Uma nova inspeção será agendada para os itens que requerem reinspeção.

---

### **Inspeção Fagan: Artefato 4/13 - `Introspecção`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Introdução sobre a técnica de introspecção, metodologia, cronograma, requisitos elicitados por cada participante, requisitos finais unificados, vídeos e validação.
*   **Objetivo Principal:** Documentar o processo de elicitação de requisitos através da técnica de introspecção.
*   **Materiais Complementares:**
    *   Bibliografia sobre introspecção
    *   Gravações das sessões
    *   Padrões de documentação do projeto
*   **Simulação de Participantes:**
    *   **Moderador:** Julia Gabriela
    *   **Autores:** João Pedro Costa, Julia Gabriela
    *   **Leitor:** Ryan Salles
    *   **Inspetor:** Amanda Cruz
*   **Simulação de Agenda:**
    *   **Data:** 21/06/2025
    *   **Horário:** 20:30 - 21:00
    *   **Pauta:** Revisão formal do artefato de introspecção.

#### 2. Visão Geral

*   **Resumo Técnico:** O documento apresenta a aplicação da técnica de introspecção por dois membros da equipe, que se colocaram na posição de usuários do sistema para identificar requisitos.
*   **Contexto no Projeto:** A introspecção complementa outras técnicas de elicitação ao permitir que a equipe se coloque no lugar do usuário.
*   **Papéis e Responsabilidades:**
    *   **Moderador (Julia):** Garantir que a inspeção mantenha foco na qualidade da aplicação da técnica.
    *   **Autores (João/Julia):** Esclarecer o processo de introspecção realizado.
    *   **Leitor (Ryan):** Verificar a clareza e estrutura do documento.
    *   **Inspetor (Amanda):** Avaliar a consistência dos requisitos elicitados.

#### 3. Checklist de Verificação
- [ ] A metodologia de introspecção está claramente descrita?
- [ ] O processo individual de cada participante está documentado?
- [ ] Os requisitos elicitados são coerentes com a técnica?
- [ ] A unificação dos requisitos está bem justificada?
- [ ] A validação dos requisitos está documentada?
- [ ] As limitações da técnica são apresentadas?
- [ ] O histórico de versão está completo e padronizado?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Defeito Metodológico:** O processo de unificação dos requisitos poderia ser mais detalhado.
    *   **Defeito de Validação:** A validação dos requisitos com usuários reais precisa ser mais robusta.
    *   **Defeito de Documentação:** Algumas sessões de introspecção não têm registro detalhado.
    *   **Omissão:** Faltam critérios claros para classificação dos requisitos.

*   **Perguntas Críticas Preparadas:**
    *   "Como foi feita a validação dos requisitos elicitados?"
    *   "Qual foi o critério para unificar requisitos similares?"
    *   "Como as limitações da técnica foram consideradas?"

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Documento marcado com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção do `Introspecção`**
    *   **Data:** 21/06/2025
    *   **Participantes:** Julia Gabriela, João Pedro Costa, Ryan Salles, Amanda Cruz
    *   **Defeitos Logados:**
        1.  **ID 01-IS (Metodologia):** Detalhar processo de unificação.
            *   *Observação do Inspetor:* "O processo de unificação dos requisitos precisa ser mais transparente."
        2.  **ID 02-IS (Validação):** Fortalecer validação.
            *   *Observação do Leitor:* "A validação com usuários reais precisa ser mais abrangente."
        3.  **ID 03-IS (Documentação):** Melhorar registros.
            *   *Observação do Moderador:* "Algumas sessões precisam de mais detalhes no registro."

*   **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados e categorizados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada e registrada
    - Relatório de inspeção foi finalizado e aprovado pelos participantes

#### 6. Retrabalho

*   **Defeito ID 01-IS:**
    *   **Correção Proposta:** Documentar critérios e processo de unificação.
    *   **Impacto da Não Correção:** Falta de transparência no processo.
    *   **Ação:** Autores devem detalhar o processo.
    *   **Reinspeção:** Sim, após documentação.

*   **Defeito ID 02-IS:**
    *   **Correção Proposta:** Realizar mais sessões de validação.
    *   **Impacto da Não Correção:** Baixa confiabilidade dos requisitos.
    *   **Ação:** Equipe deve planejar novas validações.
    *   **Reinspeção:** Sim, após validações.

*   **Defeito ID 03-IS:**
    *   **Correção Proposta:** Complementar registros das sessões.
    *   **Impacto da Não Correção:** Perda de informações importantes.
    *   **Ação:** Autores devem revisar e complementar registros.
    *   **Reinspeção:** Não necessária.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Uma nova inspeção será agendada para os itens que requerem reinspeção.

---

### **Inspeção Fagan: Artefato 5/13 - `Questionário`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Introdução sobre a técnica de questionário, metodologia, perguntas elaboradas, resultados obtidos, análise das respostas e requisitos elicitados.
*   **Objetivo Principal:** Documentar o processo de elicitação de requisitos através de questionários aplicados ao público-alvo.
*   **Materiais Complementares:**
    *   Formulários utilizados
    *   Dados brutos das respostas
    *   Análises estatísticas
*   **Simulação de Participantes:**
    *   **Moderador:** Ryan Salles
    *   **Autores:** Amanda Cruz, Gabriel Flores, João Pedro Costa
    *   **Leitor:** João Pedro Costa
    *   **Inspetor:** Julia Gabriela
*   **Simulação de Agenda:**
    *   **Data:** 21/06/2025
    *   **Horário:** 21:00 - 21:30
    *   **Pauta:** Revisão formal do artefato de questionário.

#### 2. Visão Geral

*   **Resumo Técnico:** O documento apresenta a aplicação de questionários para coletar informações e requisitos de um grupo maior de usuários potenciais.
*   **Contexto no Projeto:** O questionário permite coletar dados quantitativos e qualitativos de uma amostra maior de usuários.
*   **Papéis e Responsabilidades:**
    *   **Moderador (Ryan):** Garantir que a inspeção mantenha foco na qualidade dos dados coletados.
    *   **Autores (Amanda/Gabriel):** Esclarecer o processo de elaboração e aplicação do questionário.
    *   **Leitor (João):** Verificar a clareza e estrutura do documento.
    *   **Inspetor (Julia):** Avaliar a consistência da análise e dos requisitos elicitados.

#### 3. Checklist de Verificação
- [ ] A metodologia de elaboração do questionário está clara?
- [ ] As perguntas são objetivas e bem formuladas?
- [ ] A amostra de respondentes é representativa?
- [ ] A análise dos dados está bem fundamentada?
- [ ] Os requisitos elicitados são coerentes com as respostas?
- [ ] A validação dos requisitos está documentada?
- [ ] O histórico de versão está completo e padronizado?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Defeito Metodológico:** Falta justificativa para o tamanho da amostra.
    *   **Defeito de Análise:** Algumas conclusões não têm suporte direto nos dados.
    *   **Defeito de Documentação:** Faltam gráficos para algumas questões importantes.
    *   **Omissão:** Não há análise de correlação entre diferentes respostas.

*   **Perguntas Críticas Preparadas:**
    *   "Como foi definido o tamanho da amostra?"
    *   "Qual o critério para transformar respostas em requisitos?"
    *   "Como foi validada a representatividade da amostra?"

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Documento marcado com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção do `Questionário`**
    *   **Data:** 21/06/2025
    *   **Participantes:** Ryan Salles, Amanda Cruz, Gabriel Flores, João Pedro Costa, Julia Gabriela
    *   **Defeitos Logados:**
        1.  **ID 01-QS (Metodologia):** Justificar amostra.
            *   *Observação do Inspetor:* "Necessário explicar como foi definido o tamanho da amostra."
        2.  **ID 02-QS (Análise):** Revisar conclusões.
            *   *Observação do Leitor:* "Algumas conclusões precisam de mais evidências nos dados."
        3.  **ID 03-QS (Documentação):** Adicionar visualizações.
            *   *Observação do Moderador:* "Faltam gráficos para algumas questões importantes."

*   **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados e categorizados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada e registrada
    - Relatório de inspeção foi finalizado e aprovado pelos participantes

#### 6. Retrabalho

*   **Defeito ID 01-QS:**
    *   **Correção Proposta:** Adicionar seção sobre metodologia estatística.
    *   **Impacto da Não Correção:** Questionamento da validade dos resultados.
    *   **Ação:** Autores devem documentar cálculos amostrais.
    *   **Reinspeção:** Sim, após documentação.

*   **Defeito ID 02-QS:**
    *   **Correção Proposta:** Revisar análise de dados.
    *   **Impacto da Não Correção:** Requisitos podem não refletir necessidades reais.
    *   **Ação:** Equipe deve reanalisar dados e conclusões.
    *   **Reinspeção:** Sim, após revisão.

*   **Defeito ID 03-QS:**
    *   **Correção Proposta:** Criar visualizações adicionais.
    *   **Impacto da Não Correção:** Dificuldade na compreensão dos resultados.
    *   **Ação:** Autores devem adicionar gráficos faltantes.
    *   **Reinspeção:** Não necessária.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Uma nova inspeção será agendada para os itens que requerem reinspeção.

---

### **Inspeção Fagan: Artefato 6/13 - `Perfil de Usuário`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Metodologia de definição do perfil, dados demográficos, características dos usuários, análise de comportamento e necessidades.
*   **Objetivo Principal:** Documentar a caracterização do perfil dos usuários do sistema.
*   **Materiais Complementares:**
    *   Dados das pesquisas realizadas
    *   Análises estatísticas
    *   Documentos de referência sobre o público-alvo
*   **Simulação de Participantes:**
    *   **Moderador:** Gabriel Flores
    *   **Autores:** Julia Gabriela, Ryan Salles, João Pedro Costa
    *   **Leitor:** Amanda Cruz
    *   **Inspetor:** João Pedro Costa
*   **Simulação de Agenda:**
    *   **Data:** 21/06/2025
    *   **Horário:** 21:30 - 22:00
    *   **Pauta:** Revisão formal do artefato de perfil de usuário.

#### 2. Visão Geral

*   **Resumo Técnico:** O documento apresenta a caracterização detalhada dos usuários do sistema, incluindo aspectos demográficos, comportamentais e necessidades específicas.
*   **Contexto no Projeto:** O perfil de usuário é fundamental para orientar decisões de design e desenvolvimento.
*   **Papéis e Responsabilidades:**
    *   **Moderador (Gabriel):** Garantir que a inspeção mantenha foco na qualidade da caracterização.
    *   **Autores (Julia/Ryan):** Esclarecer o processo de definição dos perfis.
    *   **Leitor (Amanda):** Verificar a clareza e estrutura do documento.
    *   **Inspetor (João):** Avaliar a consistência dos perfis definidos.

#### 3. Checklist de Verificação
- [ ] A metodologia de definição do perfil está clara?
- [ ] Os dados demográficos estão bem fundamentados?
- [ ] As características dos usuários são relevantes para o sistema?
- [ ] A análise de comportamento está bem documentada?
- [ ] As necessidades dos usuários estão claramente identificadas?
- [ ] Há correlação com outros artefatos do projeto?
- [ ] O histórico de versão está completo e padronizado?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Defeito Metodológico:** Falta detalhamento da metodologia de coleta de dados.
    *   **Defeito de Análise:** Algumas características não têm justificativa clara.
    *   **Defeito de Documentação:** Faltam referências para alguns dados apresentados.
    *   **Omissão:** Não há análise de usuários com necessidades especiais.

*   **Perguntas Críticas Preparadas:**
    *   "Como foram coletados os dados demográficos?"
    *   "Qual a justificativa para as características selecionadas?"
    *   "Como foi validada a representatividade dos perfis?"

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Documento marcado com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção do `Perfil de Usuário`**
    *   **Data:** 21/06/2025
    *   **Participantes:** Gabriel Flores, Julia Gabriela, Ryan Salles, Amanda Cruz, João Pedro Costa
    *   **Defeitos Logados:**
        1.  **ID 01-PU (Metodologia):** Detalhar coleta de dados.
            *   *Observação do Inspetor:* "Necessário explicar como os dados foram coletados."
        2.  **ID 02-PU (Análise):** Justificar características.
            *   *Observação do Leitor:* "Algumas características precisam de melhor justificativa."
        3.  **ID 03-PU (Documentação):** Adicionar referências.
            *   *Observação do Moderador:* "Faltam fontes para alguns dados apresentados."

*   **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados e categorizados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada e registrada
    - Relatório de inspeção foi finalizado e aprovado pelos participantes

#### 6. Retrabalho

*   **Defeito ID 01-PU:**
    *   **Correção Proposta:** Documentar metodologia de coleta.
    *   **Impacto da Não Correção:** Questionamento da validade dos perfis.
    *   **Ação:** Autores devem detalhar processo de coleta.
    *   **Reinspeção:** Sim, após documentação.

*   **Defeito ID 02-PU:**
    *   **Correção Proposta:** Fundamentar características.
    *   **Impacto da Não Correção:** Perfis podem não refletir usuários reais.
    *   **Ação:** Equipe deve revisar e justificar características.
    *   **Reinspeção:** Sim, após revisão.

*   **Defeito ID 03-PU:**
    *   **Correção Proposta:** Adicionar referências bibliográficas.
    *   **Impacto da Não Correção:** Falta de credibilidade dos dados.
    *   **Ação:** Autores devem incluir fontes.
    *   **Reinspeção:** Não necessária.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Uma nova inspeção será agendada para os itens que requerem reinspeção.

---

### **Inspeção Fagan: Artefato 7/13 - `Personas`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Metodologia de criação de personas, descrição detalhada de cada persona, objetivos, necessidades, frustrações e características.
*   **Objetivo Principal:** Documentar a criação e caracterização das personas que representam os diferentes perfis de usuários do sistema.
*   **Materiais Complementares:**
    *   Perfis de usuário
    *   Resultados de pesquisas
    *   Imagens e recursos visuais
*   **Simulação de Participantes:**
    *   **Moderador:** Amanda Cruz
    *   **Autores:** João Pedro Costa, Ryan Salles
    *   **Leitor:** Gabriel Flores
    *   **Inspetor:** Julia Gabriela
*   **Simulação de Agenda:**
    *   **Data:** 21/06/2025
    *   **Horário:** 22:00 - 22:30
    *   **Pauta:** Revisão formal do artefato de personas.

#### 2. Visão Geral

*   **Resumo Técnico:** O documento apresenta as personas criadas para representar os diferentes perfis de usuários do sistema, incluindo suas características, necessidades e objetivos.
*   **Contexto no Projeto:** As personas são fundamentais para manter o foco nas necessidades reais dos usuários durante o desenvolvimento.
*   **Papéis e Responsabilidades:**
    *   **Moderador (Amanda):** Garantir que a inspeção mantenha foco na qualidade e representatividade das personas.
    *   **Autores (João/Ryan):** Esclarecer o processo de criação das personas.
    *   **Leitor (Gabriel):** Verificar a clareza e estrutura do documento.
    *   **Inspetor (Julia):** Avaliar a consistência e realismo das personas.

#### 3. Checklist de Verificação
- [ ] A metodologia de criação das personas está clara?
- [ ] As personas são baseadas em dados reais?
- [ ] Cada persona tem objetivos bem definidos?
- [ ] As necessidades e frustrações são realistas?
- [ ] As características são consistentes com os perfis de usuário?
- [ ] Há diversidade adequada entre as personas?
- [ ] O histórico de versão está completo e padronizado?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Defeito Metodológico:** Falta explicação do processo de seleção de características.
    *   **Defeito de Consistência:** Algumas personas têm características contraditórias.
    *   **Defeito de Documentação:** Faltam referências para dados utilizados.
    *   **Omissão:** Não há personas secundárias ou antipersonas.

*   **Perguntas Críticas Preparadas:**
    *   "Como foram selecionadas as características de cada persona?"
    *   "Qual a relação entre as personas e os dados de pesquisa?"
    *   "Como foi validada a representatividade das personas?"

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Documento marcado com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção do `Personas`**
    *   **Data:** 21/06/2025
    *   **Participantes:** Amanda Cruz, João Pedro Costa, Ryan Salles, Gabriel Flores, Julia Gabriela
    *   **Defeitos Logados:**
        1.  **ID 01-PS (Metodologia):** Detalhar seleção de características.
            *   *Observação do Inspetor:* "Necessário explicar como as características foram selecionadas."
        2.  **ID 02-PS (Consistência):** Revisar características contraditórias.
            *   *Observação do Leitor:* "Algumas características parecem inconsistentes entre si."
        3.  **ID 03-PS (Documentação):** Adicionar personas secundárias.
            *   *Observação do Moderador:* "Faltam personas secundárias e antipersonas."

*   **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados e categorizados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada e registrada
    - Relatório de inspeção foi finalizado e aprovado pelos participantes

#### 6. Retrabalho

*   **Defeito ID 01-PS:**
    *   **Correção Proposta:** Documentar processo de seleção.
    *   **Impacto da Não Correção:** Questionamento da validade das personas.
    *   **Ação:** Autores devem detalhar metodologia.
    *   **Reinspeção:** Sim, após documentação.

*   **Defeito ID 02-PS:**
    *   **Correção Proposta:** Revisar consistência.
    *   **Impacto da Não Correção:** Personas podem parecer irreais.
    *   **Ação:** Equipe deve revisar características.
    *   **Reinspeção:** Sim, após revisão.

*   **Defeito ID 03-PS:**
    *   **Correção Proposta:** Criar personas adicionais.
    *   **Impacto da Não Correção:** Cobertura incompleta dos perfis.
    *   **Ação:** Autores devem criar personas secundárias.
    *   **Reinspeção:** Sim, após criação.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Uma nova inspeção será agendada para os itens que requerem reinspeção.

---

### **Inspeção Fagan: Artefato 8/13 - `Requisitos Elicitados`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Lista consolidada de requisitos, classificação, rastreabilidade para técnicas de elicitação, priorização inicial.
*   **Objetivo Principal:** Documentar todos os requisitos elicitados através das diferentes técnicas utilizadas.
*   **Materiais Complementares:**
    *   Documentos de todas as técnicas de elicitação
    *   Matriz de rastreabilidade
    *   Critérios de classificação
*   **Simulação de Participantes:**
    *   **Moderador:** Julia Gabriela
    *   **Autores:** Amanda Cruz, João Pedro Costa
    *   **Leitor:** Ryan Salles
    *   **Inspetor:** Gabriel Flores
*   **Simulação de Agenda:**
    *   **Data:** 22/06/2025
    *   **Horário:** 00:30 - 01:00
    *   **Pauta:** Revisão formal do artefato de requisitos elicitados.

#### 2. Visão Geral

*   **Resumo Técnico:** O documento apresenta a consolidação de todos os requisitos identificados através das diferentes técnicas de elicitação.
*   **Contexto no Projeto:** Este artefato é fundamental por reunir e organizar todos os requisitos do sistema.
*   **Papéis e Responsabilidades:**
    *   **Moderador (Julia):** Garantir que a inspeção mantenha foco na qualidade e completude dos requisitos.
    *   **Autores (Amanda/João):** Esclarecer o processo de consolidação dos requisitos.
    *   **Leitor (Ryan):** Verificar a clareza e estrutura do documento.
    *   **Inspetor (Gabriel):** Avaliar a consistência e rastreabilidade dos requisitos.

#### 3. Checklist de Verificação
- [ ] Todos os requisitos estão claramente identificados?
- [ ] A classificação dos requisitos está consistente?
- [ ] A rastreabilidade para as técnicas está completa?
- [ ] Os requisitos são únicos (sem duplicatas)?
- [ ] A descrição dos requisitos é clara e não ambígua?
- [ ] A priorização inicial está justificada?
- [ ] O histórico de versão está completo e padronizado?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Defeito Metodológico:** Falta critério claro para eliminação de duplicatas.
    *   **Defeito de Rastreabilidade:** Alguns requisitos não têm fonte clara.
    *   **Defeito de Documentação:** Inconsistências na classificação.
    *   **Omissão:** Falta análise de conflitos entre requisitos.

*   **Perguntas Críticas Preparadas:**
    *   "Como foram tratados os requisitos duplicados?"
    *   "Qual o critério para classificação dos requisitos?"
    *   "Como foram resolvidos conflitos entre requisitos?"

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Documento marcado com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção do `Requisitos Elicitados`**
    *   **Data:** 22/06/2025
    *   **Participantes:** Julia Gabriela, Amanda Cruz, João Pedro Costa, Ryan Salles, Gabriel Flores
    *   **Defeitos Logados:**
        1.  **ID 01-RE (Metodologia):** Documentar tratamento de duplicatas.
            *   *Observação do Inspetor:* "Necessário explicar como requisitos duplicados foram tratados."
        2.  **ID 02-RE (Rastreabilidade):** Completar fontes.
            *   *Observação do Leitor:* "Alguns requisitos não têm fonte clara de elicitação."
        3.  **ID 03-RE (Documentação):** Padronizar classificação.
            *   *Observação do Moderador:* "Inconsistências na classificação dos requisitos."

*   **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados e categorizados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada e registrada
    - Relatório de inspeção foi finalizado e aprovado pelos participantes

#### 6. Retrabalho

*   **Defeito ID 01-RE:**
    *   **Correção Proposta:** Documentar processo de unificação.
    *   **Impacto da Não Correção:** Possível duplicidade de requisitos.
    *   **Ação:** Autores devem detalhar processo.
    *   **Reinspeção:** Sim, após documentação.

*   **Defeito ID 02-RE:**
    *   **Correção Proposta:** Revisar rastreabilidade.
    *   **Impacto da Não Correção:** Dificuldade na validação dos requisitos.
    *   **Ação:** Equipe deve completar rastreabilidade.
    *   **Reinspeção:** Sim, após revisão.

*   **Defeito ID 03-RE:**
    *   **Correção Proposta:** Padronizar classificações.
    *   **Impacto da Não Correção:** Confusão na interpretação dos requisitos.
    *   **Ação:** Autores devem revisar classificações.
    *   **Reinspeção:** Sim, após padronização.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Uma nova inspeção será agendada para os itens que requerem reinspeção.

---

### **Inspeção Fagan: Artefato 9/13 - `100dollars`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Metodologia de priorização 100dollars, distribuição de valores, justificativas, resultados da priorização.
*   **Objetivo Principal:** Documentar o processo de priorização de requisitos usando a técnica 100dollars.
*   **Materiais Complementares:**
    *   Lista de requisitos elicitados
    *   Critérios de priorização
    *   Resultados da distribuição
*   **Simulação de Participantes:**
    *   **Moderador:** Gabriel Flores
    *   **Autores:** Amanda Cruz, Ryan Salles, João Pedro Costa
    *   **Leitor:** Julia Gabriela
    *   **Inspetor:** João Pedro Costa
*   **Simulação de Agenda:**
    *   **Data:** 21/06/2025
    *   **Horário:** 23:00 - 23:30
    *   **Pauta:** Revisão formal do artefato de priorização 100dollars.

#### 2. Visão Geral

*   **Resumo Técnico:** O documento apresenta a aplicação da técnica 100dollars, onde stakeholders distribuem um orçamento fictício entre os requisitos.
*   **Contexto no Projeto:** A priorização é essencial para definir a ordem de implementação dos requisitos.
*   **Papéis e Responsabilidades:**
    *   **Moderador (Gabriel):** Garantir que a inspeção mantenha foco na qualidade da priorização.
    *   **Autores (Amanda/Ryan):** Esclarecer o processo de aplicação da técnica.
    *   **Leitor (Julia):** Verificar a clareza e estrutura do documento.
    *   **Inspetor (João):** Avaliar a consistência da priorização.

#### 3. Checklist de Verificação
- [ ] A metodologia 100dollars está claramente explicada?
- [ ] A distribuição dos valores está documentada?
- [ ] As justificativas para as distribuições são coerentes?
- [ ] O processo de participação dos stakeholders está claro?
- [ ] Os resultados finais estão bem apresentados?
- [ ] Há consistência com outros métodos de priorização?
- [ ] O histórico de versão está completo e padronizado?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Defeito Metodológico:** Falta explicação do processo de consolidação dos valores.
    *   **Defeito de Participação:** Não está claro quem foram os participantes.
    *   **Defeito de Documentação:** Algumas justificativas estão incompletas.
    *   **Omissão:** Falta comparação com outros métodos de priorização.

*   **Perguntas Críticas Preparadas:**
    *   "Como foram consolidados os valores de diferentes stakeholders?"
    *   "Qual foi o critério de seleção dos participantes?"
    *   "Como foram tratados casos de empate?"

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Documento marcado com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção do `100dollars`**
    *   **Data:** 21/06/2025
    *   **Participantes:** Gabriel Flores, Amanda Cruz, Ryan Salles, Julia Gabriela, João Pedro Costa
    *   **Defeitos Logados:**
        1.  **ID 01-100D (Metodologia):** Detalhar consolidação.
            *   *Observação do Inspetor:* "Necessário explicar como os valores foram consolidados."
        2.  **ID 02-100D (Participação):** Identificar participantes.
            *   *Observação do Leitor:* "Falta clareza sobre quem participou da priorização."
        3.  **ID 03-100D (Documentação):** Completar justificativas.
            *   *Observação do Moderador:* "Algumas distribuições não têm justificativa clara."

*   **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados e categorizados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada e registrada
    - Relatório de inspeção foi finalizado e aprovado pelos participantes

#### 6. Retrabalho

*   **Defeito ID 01-100D:**
    *   **Correção Proposta:** Documentar processo de consolidação.
    *   **Impacto da Não Correção:** Falta de transparência no resultado final.
    *   **Ação:** Autores devem detalhar metodologia.
    *   **Reinspeção:** Sim, após documentação.

*   **Defeito ID 02-100D:**
    *   **Correção Proposta:** Listar participantes.
    *   **Impacto da Não Correção:** Questionamento da representatividade.
    *   **Ação:** Equipe deve identificar participantes.
    *   **Reinspeção:** Não necessária.

*   **Defeito ID 03-100D:**
    *   **Correção Proposta:** Adicionar justificativas.
    *   **Impacto da Não Correção:** Falta de embasamento nas decisões.
    *   **Ação:** Autores devem completar justificativas.
    *   **Reinspeção:** Sim, após adição.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Uma nova inspeção será agendada para os itens que requerem reinspeção.

---

### **Inspeção Fagan: Artefato 10/13 - `First Thing First`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Metodologia First Thing First, critérios de avaliação, cálculos de priorização, resultados finais.
*   **Objetivo Principal:** Documentar o processo de priorização de requisitos usando a técnica First Thing First.
*   **Materiais Complementares:**
    *   Lista de requisitos elicitados
    *   Critérios de benefício e penalidade
    *   Planilhas de cálculo
*   **Simulação de Participantes:**
    *   **Moderador:** Gabriel Flores
    *   **Autores:** Amanda Cruz, Ryan Salles, João Pedro Costa
    *   **Leitor:** Julia Gabriela
    *   **Inspetor:** João Pedro Costa
*   **Simulação de Agenda:**
    *   **Data:** 21/06/2025
    *   **Horário:** 23:30 - 00:00
    *   **Pauta:** Revisão formal do artefato de priorização First Thing First.

#### 2. Visão Geral

*   **Resumo Técnico:** O documento apresenta a aplicação da técnica First Thing First, que prioriza requisitos baseado em benefícios, penalidades, custos e riscos.
*   **Contexto no Projeto:** Esta técnica complementa outros métodos de priorização com uma abordagem mais quantitativa.
*   **Papéis e Responsabilidades:**
    *   **Moderador (Gabriel):** Garantir que a inspeção mantenha foco na qualidade da priorização.
    *   **Autores (Amanda/Ryan):** Esclarecer o processo de aplicação da técnica.
    *   **Leitor (Julia):** Verificar a clareza e estrutura do documento.
    *   **Inspetor (João):** Avaliar a consistência dos cálculos e resultados.

#### 3. Checklist de Verificação
- [ ] A metodologia First Thing First está claramente explicada?
- [ ] Os critérios de benefício e penalidade estão bem definidos?
- [ ] Os cálculos estão corretos e documentados?
- [ ] O processo de avaliação está transparente?
- [ ] Os resultados finais estão bem apresentados?
- [ ] Há consistência com outros métodos de priorização?
- [ ] O histórico de versão está completo e padronizado?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Defeito Metodológico:** Falta detalhamento dos critérios de avaliação.
    *   **Defeito de Cálculo:** Algumas fórmulas não estão explícitas.
    *   **Defeito de Documentação:** Faltam exemplos práticos.
    *   **Omissão:** Não há análise de sensibilidade dos resultados.

*   **Perguntas Críticas Preparadas:**
    *   "Como foram definidos os pesos dos critérios?"
    *   "Como foram calculados os valores finais?"
    *   "Como foram validados os resultados?"

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Documento marcado com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção do `First Thing First`**
    *   **Data:** 21/06/2025
    *   **Participantes:** Gabriel Flores, Amanda Cruz, Ryan Salles, Julia Gabriela, João Pedro Costa
    *   **Defeitos Logados:**
        1.  **ID 01-FTF (Metodologia):** Detalhar critérios.
            *   *Observação do Inspetor:* "Necessário explicar como os critérios foram definidos."
        2.  **ID 02-FTF (Cálculo):** Explicitar fórmulas.
            *   *Observação do Leitor:* "Algumas fórmulas precisam ser melhor documentadas."
        3.  **ID 03-FTF (Documentação):** Adicionar exemplos.
            *   *Observação do Moderador:* "Faltam exemplos práticos de aplicação."

*   **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados e categorizados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada e registrada
    - Relatório de inspeção foi finalizado e aprovado pelos participantes

#### 6. Retrabalho

*   **Defeito ID 01-FTF:**
    *   **Correção Proposta:** Documentar critérios.
    *   **Impacto da Não Correção:** Falta de transparência na avaliação.
    *   **Ação:** Autores devem detalhar critérios.
    *   **Reinspeção:** Sim, após documentação.

*   **Defeito ID 02-FTF:**
    *   **Correção Proposta:** Incluir fórmulas.
    *   **Impacto da Não Correção:** Dificuldade na reprodução dos cálculos.
    *   **Ação:** Equipe deve documentar fórmulas.
    *   **Reinspeção:** Sim, após inclusão.

*   **Defeito ID 03-FTF:**
    *   **Correção Proposta:** Criar exemplos.
    *   **Impacto da Não Correção:** Dificuldade no entendimento da aplicação.
    *   **Ação:** Autores devem adicionar exemplos.
    *   **Reinspeção:** Não necessária.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Uma nova inspeção será agendada para os itens que requerem reinspeção.

---

### **Inspeção Fagan: Artefato 11/13 - `MoSCoW`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Metodologia MoSCoW, critérios de classificação, distribuição dos requisitos, justificativas.
*   **Objetivo Principal:** Documentar o processo de priorização de requisitos usando a técnica MoSCoW.
*   **Materiais Complementares:**
    *   Lista de requisitos elicitados
    *   Critérios de classificação
    *   Resultados da priorização
*   **Simulação de Participantes:**
    *   **Moderador:** Amanda Cruz
    *   **Autores:** Julia Gabriela, João Pedro Costa
    *   **Leitor:** Gabriel Flores
    *   **Inspetor:** Ryan Salles
*   **Simulação de Agenda:**
    *   **Data:** 22/06/2025
    *   **Horário:** 00:00 - 00:30
    *   **Pauta:** Revisão formal do artefato de priorização MoSCoW.

#### 2. Visão Geral

*   **Resumo Técnico:** O documento apresenta a aplicação da técnica MoSCoW, que classifica requisitos em Must have, Should have, Could have e Won't have.
*   **Contexto no Projeto:** Esta técnica oferece uma abordagem clara e direta para priorização de requisitos.
*   **Papéis e Responsabilidades:**
    *   **Moderador (Amanda):** Garantir que a inspeção mantenha foco na qualidade da priorização.
    *   **Autores (Julia/João):** Esclarecer o processo de aplicação da técnica.
    *   **Leitor (Gabriel):** Verificar a clareza e estrutura do documento.
    *   **Inspetor (Ryan):** Avaliar a consistência da classificação.

#### 3. Checklist de Verificação
- [ ] A metodologia MoSCoW está claramente explicada?
- [ ] Os critérios de classificação estão bem definidos?
- [ ] A distribuição dos requisitos é coerente?
- [ ] As justificativas são adequadas?
- [ ] Os resultados finais estão bem apresentados?
- [ ] Há consistência com outros métodos de priorização?
- [ ] O histórico de versão está completo e padronizado?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Defeito Metodológico:** Falta clareza nos critérios de classificação.
    *   **Defeito de Consistência:** Algumas classificações parecem inconsistentes.
    *   **Defeito de Documentação:** Justificativas insuficientes.
    *   **Omissão:** Falta análise da distribuição dos requisitos.

*   **Perguntas Críticas Preparadas:**
    *   "Quais critérios definem cada categoria?"
    *   "Como foi validada a consistência das classificações?"
    *   "Como foi considerado o balanceamento entre categorias?"

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Documento marcado com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção do `MoSCoW`**
    *   **Data:** 22/06/2025
    *   **Participantes:** Amanda Cruz, Julia Gabriela, João Pedro Costa, Gabriel Flores, Ryan Salles
    *   **Defeitos Logados:**
        1.  **ID 01-MS (Metodologia):** Detalhar critérios.
            *   *Observação do Inspetor:* "Necessário explicar critérios de cada categoria."
        2.  **ID 02-MS (Consistência):** Revisar classificações.
            *   *Observação do Leitor:* "Algumas classificações parecem inconsistentes."
        3.  **ID 03-MS (Documentação):** Melhorar justificativas.
            *   *Observação do Moderador:* "Justificativas precisam ser mais detalhadas."

*   **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados e categorizados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada e registrada
    - Relatório de inspeção foi finalizado e aprovado pelos participantes

#### 6. Retrabalho

*   **Defeito ID 01-MS:**
    *   **Correção Proposta:** Documentar critérios.
    *   **Impacto da Não Correção:** Falta de clareza na classificação.
    *   **Ação:** Autores devem detalhar critérios.
    *   **Reinspeção:** Sim, após documentação.

*   **Defeito ID 02-MS:**
    *   **Correção Proposta:** Realizar mais sessões de validação.
    *   **Impacto da Não Correção:** Baixa confiabilidade dos requisitos.
    *   **Ação:** Equipe deve planejar novas validações.
    *   **Reinspeção:** Sim, após validações.

*   **Defeito ID 03-MS:**
    *   **Correção Proposta:** Complementar registros das sessões.
    *   **Impacto da Não Correção:** Perda de informações importantes.
    *   **Ação:** Autores devem revisar e complementar registros.
    *   **Reinspeção:** Não necessária.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Uma nova inspeção será agendada para os itens que requerem reinspeção.

---

### **Inspeção Fagan: Artefato 12/13 - `Personas`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Metodologia de criação de personas, descrição detalhada de cada persona, objetivos, necessidades, frustrações e características.
*   **Objetivo Principal:** Documentar a criação e caracterização das personas que representam os diferentes perfis de usuários do sistema.
*   **Materiais Complementares:**
    *   Perfis de usuário
    *   Resultados de pesquisas
    *   Imagens e recursos visuais
*   **Simulação de Participantes:**
    *   **Moderador:** Amanda Cruz
    *   **Autores:** João Pedro Costa, Ryan Salles
    *   **Leitor:** Gabriel Flores
    *   **Inspetor:** Julia Gabriela
*   **Simulação de Agenda:**
    *   **Data:** 21/06/2025
    *   **Horário:** 22:00 - 22:30
    *   **Pauta:** Revisão formal do artefato de personas.

#### 2. Visão Geral

*   **Resumo Técnico:** O documento apresenta as personas criadas para representar os diferentes perfis de usuários do sistema, incluindo suas características, necessidades e objetivos.
*   **Contexto no Projeto:** As personas são fundamentais para manter o foco nas necessidades reais dos usuários durante o desenvolvimento.
*   **Papéis e Responsabilidades:**
    *   **Moderador (Amanda):** Garantir que a inspeção mantenha foco na qualidade e representatividade das personas.
    *   **Autores (João/Ryan):** Esclarecer o processo de criação das personas.
    *   **Leitor (Gabriel):** Verificar a clareza e estrutura do documento.
    *   **Inspetor (Julia):** Avaliar a consistência e realismo das personas.

#### 3. Checklist de Verificação
- [ ] A metodologia de criação das personas está clara?
- [ ] As personas são baseadas em dados reais?
- [ ] Cada persona tem objetivos bem definidos?
- [ ] As necessidades e frustrações são realistas?
- [ ] As características são consistentes com os perfis de usuário?
- [ ] Há diversidade adequada entre as personas?
- [ ] O histórico de versão está completo e padronizado?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Defeito Metodológico:** Falta explicação do processo de seleção de características.
    *   **Defeito de Consistência:** Algumas personas têm características contraditórias.
    *   **Defeito de Documentação:** Faltam referências para dados utilizados.
    *   **Omissão:** Não há personas secundárias ou antipersonas.

*   **Perguntas Críticas Preparadas:**
    *   "Como foram selecionadas as características de cada persona?"
    *   "Qual a relação entre as personas e os dados de pesquisa?"
    *   "Como foi validada a representatividade das personas?"

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Documento marcado com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção do `Personas`**
    *   **Data:** 21/06/2025
    *   **Participantes:** Amanda Cruz, João Pedro Costa, Ryan Salles, Gabriel Flores, Julia Gabriela
    *   **Defeitos Logados:**
        1.  **ID 01-PS (Metodologia):** Detalhar seleção de características.
            *   *Observação do Inspetor:* "Necessário explicar como as características foram selecionadas."
        2.  **ID 02-PS (Consistência):** Revisar características contraditórias.
            *   *Observação do Leitor:* "Algumas características parecem inconsistentes entre si."
        3.  **ID 03-PS (Documentação):** Adicionar personas secundárias.
            *   *Observação do Moderador:* "Faltam personas secundárias e antipersonas."

*   **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados e categorizados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada e registrada
    - Relatório de inspeção foi finalizado e aprovado pelos participantes

#### 6. Retrabalho

*   **Defeito ID 01-PS:**
    *   **Correção Proposta:** Documentar processo de seleção.
    *   **Impacto da Não Correção:** Questionamento da validade das personas.
    *   **Ação:** Autores devem detalhar metodologia.
    *   **Reinspeção:** Sim, após documentação.

*   **Defeito ID 02-PS:**
    *   **Correção Proposta:** Revisar consistência.
    *   **Impacto da Não Correção:** Personas podem parecer irreais.
    *   **Ação:** Equipe deve revisar características.
    *   **Reinspeção:** Sim, após revisão.

*   **Defeito ID 03-PS:**
    *   **Correção Proposta:** Criar personas adicionais.
    *   **Impacto da Não Correção:** Cobertura incompleta dos perfis.
    *   **Ação:** Autores devem criar personas secundárias.
    *   **Reinspeção:** Sim, após criação.

#### 7. Follow-up
Após as correções, o moderador revisará o artefato para garantir que todos os defeitos foram sanados. Uma nova inspeção será agendada para os itens que requerem reinspeção.

---

### **Inspeção Fagan: Artefato 13/13 - `Requisitos Elicitados`**

#### 1. Planejamento da Inspeção

*   **Elementos do Artefato:** Lista consolidada de requisitos, classificação, rastreabilidade para técnicas de elicitação, priorização inicial.
*   **Objetivo Principal:** Documentar todos os requisitos elicitados através das diferentes técnicas utilizadas.
*   **Materiais Complementares:**
    *   Documentos de todas as técnicas de elicitação
    *   Matriz de rastreabilidade
    *   Critérios de classificação
*   **Simulação de Participantes:**
    *   **Moderador:** Julia Gabriela
    *   **Autores:** Amanda Cruz, João Pedro Costa
    *   **Leitor:** Ryan Salles
    *   **Inspetor:** Gabriel Flores
*   **Simulação de Agenda:**
    *   **Data:** 22/06/2025
    *   **Horário:** 00:30 - 01:00
    *   **Pauta:** Revisão formal do artefato de requisitos elicitados.

#### 2. Visão Geral

*   **Resumo Técnico:** O documento apresenta a consolidação de todos os requisitos identificados através das diferentes técnicas de elicitação.
*   **Contexto no Projeto:** Este artefato é fundamental por reunir e organizar todos os requisitos do sistema.
*   **Papéis e Responsabilidades:**
    *   **Moderador (Julia):** Garantir que a inspeção mantenha foco na qualidade e completude dos requisitos.
    *   **Autores (Amanda/João):** Esclarecer o processo de consolidação dos requisitos.
    *   **Leitor (Ryan):** Verificar a clareza e estrutura do documento.
    *   **Inspetor (Gabriel):** Avaliar a consistência e rastreabilidade dos requisitos.

#### 3. Checklist de Verificação
- [ ] Todos os requisitos estão claramente identificados?
- [ ] A classificação dos requisitos está consistente?
- [ ] A rastreabilidade para as técnicas está completa?
- [ ] Os requisitos são únicos (sem duplicatas)?
- [ ] A descrição dos requisitos é clara e não ambígua?
- [ ] A priorização inicial está justificada?
- [ ] O histórico de versão está completo e padronizado?

#### 4. Preparação

*   **Análise Detalhada (Defeitos Encontrados):**
    *   **Defeito Metodológico:** Falta critério claro para eliminação de duplicatas.
    *   **Defeito de Rastreabilidade:** Alguns requisitos não têm fonte clara.
    *   **Defeito de Documentação:** Inconsistências na classificação.
    *   **Omissão:** Falta análise de conflitos entre requisitos.

*   **Perguntas Críticas Preparadas:**
    *   "Como foram tratados os requisitos duplicados?"
    *   "Qual o critério para classificação dos requisitos?"
    *   "Como foram resolvidos conflitos entre requisitos?"

#### 5. Reunião de Inspeção

*   **Critérios de Entrada para a Reunião:**
    - Logs de preparação completos de cada inspetor
    - Documento marcado com observações
    - Todos os participantes confirmaram revisão prévia do material
    - Checklist de verificação preenchido

*   **Ata da Reunião de Inspeção do `Requisitos Elicitados`**
    *   **Data:** 22/06/2025
    *   **Participantes:** Julia Gabriela, Amanda Cruz, João Pedro Costa, Ryan Salles, Gabriel Flores
    *   **Defeitos Logados:**
        1.  **ID 01-RE (Metodologia):** Documentar tratamento de duplicatas.
            *   *Observação do Inspetor:* "Necessário explicar como requisitos duplicados foram tratados."
        2.  **ID 02-RE (Rastreabilidade):** Completar fontes.
            *   *Observação do Leitor:* "Alguns requisitos não têm fonte clara de elicitação."
        3.  **ID 03-RE (Documentação):** Padronizar classificação.
            *   *Observação do Moderador:* "Inconsistências na classificação dos requisitos."

*   **Critérios de Saída da Reunião:**
    - Todos os defeitos identificados foram registrados e categorizados
    - Decisões sobre correções foram documentadas
    - Necessidade de reinspeção foi avaliada e registrada
    - Relatório de inspeção foi finalizado e aprovado pelos participantes

#### 6. Retrabalho

*   **Defeito ID 01-RE:**
    *   **Correção Proposta:** Documentar processo de unificação.
    *   **Impacto da Não Correção:** Possível duplicidade de requisitos.
    *   **Ação:** Autores devem detalhar processo.
    *   **Reinspeção:** Sim, após documentação.

*   **Defeito ID 02-RE:**
    *   **Correção Proposta:** Revisar rastreabilidade.
    *   **Impacto da Não Correção:** Dificuldade na validação dos requisitos.
    *   **Ação:** Equipe deve completar rastreabilidade.
    *   **Reinspeção:** Sim, após revisão.

*   **Defeito ID 03-RE:**
    *   **Correção Proposta:** Padronizar classificações.
    *   **Impacto da Não Correção:** Confusão na interpretação dos requisitos.
    *   **Ação:** Autores devem revisar classificações.
    *   **Reinspeção:** Sim, após padronização.

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