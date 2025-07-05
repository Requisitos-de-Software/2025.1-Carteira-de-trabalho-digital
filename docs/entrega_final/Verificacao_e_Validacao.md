# Documento de Verificação e Validação (V&V)

## Função dos autores
| Nome                                               | Função                                                            | 
|----------------------                              |----------------------------------------------------------------   |
|[Gabriel Flores](https://github.com/Gabrielfcoelho)  | Elaboração do Documento | 
|[Ryan Salles](https://github.com/RA-Salles)         | Revisão geral| 

## 1. Introdução

Este documento descreve os processos de Verificação e Validação (V&V) adotados no projeto Cadastro Único. O objetivo é garantir que todos os requisitos foram devidamente implementados, revisados e validados, assegurando que o produto final atende às expectativas das partes interessadas e padrões de qualidade definidos pelo grupo.

## 2. Metodologia de Verificação

Utilizamos o processo de inspeção Fagan para garantir a máxima detecção e correção de defeitos. Essa metodologia robusta exige uma definição clara do produto a ser inspecionado e o envolvimento de participantes com papéis bem definidos. É crucial que os inspetores dediquem tempo adequado à preparação, utilizando checklists específicos para guiar a análise.

O processo Fagan define critérios claros de entrada e saída, assegurando a conclusão adequada de cada etapa antes de avançar. Toda a inspeção é documentada, incluindo a coleta de dados relevantes, e são estabelecidos procedimentos claros para retrabalho e verificação.

Para os artefatos de planejamento, nossa inspeção focará na completude e consistência do cronograma, na adequação das ferramentas, na clareza da metodologia e na viabilidade geral do planejamento. Analisaremos cuidadosamente a distribuição de tarefas, a definição de responsabilidades e a adequação dos prazos. Também daremos atenção especial à integração entre os diferentes elementos do planejamento, como a relação entre o cronograma e o heatmap de disponibilidade da equipe.


## 3. Verificação

Abaixo é possível encontrar os link para as listas de verificação dos artefatos entregues até o momento da verificação e as inspeções de Fagan realizadas.

### Listas de Verificação

- [Entrega 1](../verificacao/checklist_1.md)
- [Entrega 2](../vericacao/checklist_2.md)
- [Entrega 3](../vericacao/checklist_3.md)
- [Entrega 4](../vericacao/checklist_4.md)
- [Entrega 6](../vericacao/checklist_6.md)

### Inspeções do Grupo

- [Etapa 1](../inspecoes/grupo/inspecao_1.md)
- [Etapa 2](../inspecoes/grupo/inspecao_2.md)
- [Etapa 3](../inspecoes/grupo/inspecao_3.md)
- [Etapa 4](../inspecoes/grupo/inspecao_4.md)
- [Etapa 6](../inspecoes/grupo/inspecao_6.md)


### Inspeções de Fagan

- [Etapa 1](../inspecoes/inspecoes_de_fagan/etapa1.md)
- [Etapa 2](../inspecoes/inspecoes_de_fagan/etapa2.md)
- [Etapa 3](../inspecoes/inspecoes_de_fagan/etapa3.md)
- [Etapa 4](../inspecoes/inspecoes_de_fagan/etapa4.md)
- [Etapa 6](../inspecoes/inspecoes_de_fagan/etapa6.md)

## 4. Metodologia de Validação

A validação teve como foco garantir que o sistema atenda às necessidades do usuário final e aos objetivos do projeto. As estratégias utilizadas foram a comprovação informal e prototipação.  

A comprovação informal, uma das estratégias de validação, envolve a leitura de descrições em linguagem natural e a utilização de clientes para identificar problemas na expressão dos requisitos. Esta abordagem carece de apoio automatizado e depende muito das habilidades analíticas dos leitores. O principal foco da comprovação informal é a identificação de erros na informação e nos fatos.

A prototipação, ou prototipagem, é outra estratégia de validação que utiliza diversos tipos de protótipos para obter feedback do Universo de Informações. Isso pode incluir o uso de linguagens de alto nível (geradores de aplicação) ou linguagens de especificação executáveis. O objetivo central da prototipação é validar os requisitos e a especificação com base nas expectativas do usuário. O foco aqui é analisar o comportamento dos fatos em relação às expectativas do usuário.


## 5. Tabela de Validação

| Artefato                   | Responsável       | Usuário | Data | Evidência |
|----------------------------------|-------------------|-------------------------------------|------------|---------------|
| Introspecção                   | [João Pedro](https://github.com/johnaopedro), [Ryan Salles](https://github.com/RA-Salles)  | Lucas | 05/06/2025 | [Introspecção](../elicitacao/tecnicas/introspecção.md) |
| Análise de documentação        | [João Pedro](https://github.com/johnaopedro), [Ryan Salles](https://github.com/RA-Salles)  | Lucas | 05/06/2025 | [Análise de documentação](../elicitacao/tecnicas/analise_documentacao.md) |
| Moscow                         | [João Pedro](https://github.com/johnaopedro), [Ryan Salles](https://github.com/RA-Salles), [Gabriel Flores](https://github.com/Gabrielfcoelho), [João Igor](https://github.com/JoaoPC10)  | Artur | 05/06/2025 | [Moscow](../elicitacao/priorizacao/moscow.md) |
| Three level scale              | [João Pedro](https://github.com/johnaopedro), [Ryan Salles](https://github.com/RA-Salles), [Gabriel Flores](https://github.com/Gabrielfcoelho), [João Igor](https://github.com/JoaoPC10)  | Artur | 05/06/2025 | [Three level scale](../elicitacao/priorizacao/three_level_scale.md) |
| Histórias de usuário           | [João Pedro](https://github.com/johnaopedro), [Ryan Salles](https://github.com/RA-Salles), [Julia Gabriela](https://github.com/JuliaGabP)  | Davi | 30/05/2025 | [Histórias de usuário](../modelagem/agil/historia_de_usuario.md) |
| Backlog                        | [João Pedro](https://github.com/johnaopedro), [Ryan Salles](https://github.com/RA-Salles)  | Davi | 01/06/2025 | [Backlog](../modelagem/agil/backlog.md) |
| Filtragem de benefícios        | [João Igor](https://github.com/JoaoPC10), [Ryan Salles](https://github.com/RA-Salles), [Gabriel Flores](https://github.com/Gabrielfcoelho)            | Artur                 | 05/06/2025 | [Protótipos](../prototipo/prototipo.md) |
| Atualizar dados cadastrais                | [João Igor](https://github.com/JoaoPC10), [Ryan Salles](https://github.com/RA-Salles), [Gabriel Flores](https://github.com/Gabrielfcoelho)            | Artur                 | 05/06/2025 | [Protótipos](../prototipo/prototipo.md) |
| Upload de documentos                      | [Gabriel Flores](https://github.com/Gabrielfcoelho), [Ryan Salles](https://github.com/RA-Salles), [João Igor](https://github.com/JoaoPC10) | Artur                 | 05/06/2025 | [Protótipos](../prototipo/prototipo.md) | 
| Notificação de Pendências ou atualizações | [Gabriel Flores](https://github.com/Gabrielfcoelho), [Ryan Salles](https://github.com/RA-Salles), [João Igor](https://github.com/JoaoPC10) | Artur                 | 05/06/2025 | [Protótipos](../prototipo/prototipo.md) |
| Chat de atendimento                       | [João Pedro](https://github.com/johnaopedro)        | Artur                 | 05/06/2025 | [Protótipos](../prototipo/prototipo.md) |
| Agendar atendimento                       | [João Pedro](https://github.com/johnaopedro)        | Artur                 | 05/06/2025 | [Protótipos](../prototipo/prototipo.md) |
| Assistência por voz                       | [Ryan Salles](https://github.com/RA-Salles), [Gabriel Flores](https://github.com/Gabrielfcoelho)         | Artur                 | 05/06/2025 | [Protótipos](../prototipo/prototipo.md) |
| Chatbot                                   | [Ryan Salles](https://github.com/RA-Salles), [Gabriel Flores](https://github.com/Gabrielfcoelho)         | Artur                 | 05/06/2025 | [Protótipos](../prototipo/prototipo.md) |

<center>
    Autor(es): 
    <a href="https://github.com/Gabrielfcoelho" target="_blank">Gabriel Flores</a>
</center>

## 6. Conclusão

## 6. Conclusão

A adoção rigorosa das metodologias de Verificação e Validação (V&V) descritas neste documento foi fundamental para assegurar a qualidade e a confiabilidade do sistema desenvolvido. Por meio da aplicação de inspeções sistemáticas, listas de verificação e validação contínua junto aos usuários, foi possível identificar e corrigir inconsistências, antecipar possíveis falhas e alinhar o produto final às reais necessidades dos stakeholders.

O uso da inspeção Fagan permitiu uma análise detalhada dos artefatos, promovendo a colaboração entre os membros da equipe e garantindo que cada etapa do processo fosse devidamente revisada antes de avançar. Já as estratégias de validação, como a comprovação informal e a prototipação, proporcionaram um ciclo de feedback constante, permitindo ajustes rápidos e eficazes com base nas expectativas dos usuários finais.

Essas práticas não apenas elevaram o padrão de qualidade do projeto, mas também fortaleceram a comunicação entre equipe técnica e usuários, promovendo transparência e confiança em todas as fases do desenvolvimento. Como resultado, o sistema entregue apresenta maior robustez, usabilidade e aderência aos requisitos estabelecidos, contribuindo para o sucesso do projeto e a satisfação

## Bibliografia

> BARHATE, B. H. Software Inspection Improves Quality of Software Product. *International Journal of Computer Science & Informatics*, Vol.- II, Issue-1, 2. 2013. [Link para o artigo](../../assets/referencias/inspecao_fagan/Software_Inspection_Improves_Quality_of_Software_P.pdf)

> Sommerville, Ian. Engenharia de software. 08. ed. São Paulo: Pearson Addison Wesley, 2011

> SIQUEIRA, Fábio Levy. Gerência e Qualidade de Software - Aula 06 - Técnica de revisão. 2018. Disponível em: < https://youtu.be/nA1BVDd9GUE >. Acesso em: 20/06/2025.

> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 23. Gama: Universidade de Brasília (UnB). Slide de apresentação. Acesso em: 5 de julho 2025.  

As figuras 1 a 3 apresentam imagens que representam a bibliografia utilizada para elaboração desse documento.

### Figura 1: Sommerville sobre inspeções

<div style="text-align: center;">
    <img src="../../../assets/referencias/inspecao_fagan/sommerville_inspec.png" alt="Sommeville cap 8">
</div>

**Fonte:** Adaptado de SOMMERVILLE (2011).

### Figura 2: Apresentação de Fábio L. Siqueira sobre técnicas de inspeção

<div style="text-align: center;">
    <img src="../../../assets/referencias/inspecao_fagan/siqueira_inspec.png" alt="Siqueira revisões">
</div>

**Fonte:** Adaptado de SIQUEIRA (2025).

### Figura 3: Diagrama de Barhate sobre inspeções

<div style="text-align: center;">
    <img src="../../../assets/referencias/inspecao_fagan/barhate_inspec.png" alt="Barhate diagrama">
</div>

**Fonte:** Adaptado de BARHATE (2013).

### Figura 4: Comprovação informal

<div style="text-align: center;">
    <img src="../../../assets/referencias/validacao/comprovacao_informal.png" alt="Comprovação informal">
</div>

**Fonte:** Adaptado de SERRANO.

### Figura 5: Prototipação

<div style="text-align: center;">
    <img src="../../../assets/referencias/validacao/prototipacao.png" alt="Prototipação">
</div>

**Fonte:** Adaptado de SERRANO.

---

## Histórico de versão
| Versão |    Data    |    Descrição     |         Autor         |       Revisor      |
| :----: | :--------: | :--------------: | :-------------------: | :----------------: |
|  1.0   | 04/07/2025 | Desenvolvimento das informações da pagina | [Gabriel Flores](https://github.com/Gabrielfcoelho)     | [Ryan Salles](https://github.com/RA-Salles) |
