# Three-Level Scale

## Funções dos autores

| Nome                 | Função                                                                           | 
|----------------------|----------------------------------------------------------------                  |
|[João Pedro Costa](https://github.com/johnaopedro)| Criação do documento, ajustes e validação            | 
|[Julia Gabriela](https://github.com/JuliaGabP)    | Revisão geral.                                       | 
|[Ryan Salles](https://github.com/RA-Salles)       | Criação do documento, ajustes, manutenção e evolução | 
<center>
    Autor(es): 
    <a href="https://github.com/JuliaGabP" target="_blank">Julia Gabriela</a>
</center>

## Introdução

O Three-Level Scale é um método utilizado para priorizar requisitos em projetos de software, classificando-os em três categorias: alta prioridade, prioridade média e baixa prioridade. Esse método, embora seja subjetivo, é eficaz quando os stakeholders concordam sobre os critérios de cada nível. A avaliação é feita com base em duas dimensões principais:

- Importância: Relevância do requisito para os objetivos do negócio.
- Urgência: Necessidade imediata de implementação do requisito.

As categorias são definidas da seguinte forma:

- Alta Prioridade: Requisitos importantes e urgentes, necessários para alcançar os objetivos do negócio na próxima versão. Incluem obrigações contratuais ou requisitos de conformidade que não podem ser adiados.
- Prioridade Média: Requisitos importantes, mas não urgentes, que podem ser adiados para versões futuras sem grandes prejuízos.
- Baixa Prioridade: Requisitos que não são críticos para o negócio e podem ser adiados ou descartados sem impacto significativo.

Requisitos percebidos como urgentes, mas que não são importantes para os objetivos de negócio, devem ser evitados ou removidos, pois não agregam valor suficiente ao produto. Além disso, é recomendável incluir a prioridade de cada requisito como um atributo nos documentos de requisitos para garantir clareza e alinhamento entre os envolvidos.

## Aplicação no App Cadastro Único

No contexto do aplicativo Cadastro Único, o método pode ser aplicado para organizar e priorizar os requisitos de forma eficiente. A seguir, apresentamos os requisitos funcionais e não funcionais identificados, categorizados de acordo com a técnica Three-Level Scale. A partir dos requisitos obtidos pelas tecnicas de elicitação, que são [questionário](../tecnicas/questionario.md), [entrevista](../tecnicas/entrevista.md) e [análise de documentos](../tecnicas/analise_documentacao.md) e [introspecção](../tecnicas/introspecção.md), foram definidos os requisitos funcionais e não funcionais do sistema. Os requisitos foram organizados em tabelas, com suas respectivas descrições, rastreabilidade e prioridades.
Os requisitos foram classificados em três níveis de prioridade, com base na importância e urgência de cada um deles.

Note que alguns requisitos podem se repetir por conta de serem identificados em mais de uma técnica de elicitação. Além disso, alguns foram renomeados para melhorar a clareza. Os requisitos foram organizados em duas tabelas 1 e 2, uma para os requisitos funcionais e outra para os não funcionais. A seguir, apresentamos as tabelas com os requisitos priorizados. 

### Requisitos Priorizados

Os resultados da priorização realizada são apresentados por meio das tabelas 1 e 2.

### Requisitos Funcionais 

Essa seção apresenta os resultados da priorização dos requisitos funcionais por meio da tabela 1.

<center>
    <b>Tabela 1:</b> Requisitos Funcionais Elicitados
</center>

| ID                                             | Nome                                        | Implementado | Prioridade  |
| :--------------------------------------------: | :-----------------------------------------: | :----------: | :---------: |
| [RF01](../requisitos_elicitados.md#rf01)       | Cadastro de Famílias                        | Sim          | Média       |
| [RF02-v2](../requisitos_elicitados.md#rf02-v2) | Cadastro de Pessoas                         | Sim          | Alta        |
| [RF03](../requisitos_elicitados.md#rf03)       | Cadastro de Domicílios                      | Sim          | Média       |
| [RF04](../requisitos_elicitados.md#rf04)       | Cadastro de Agricultores Familiares         | Sim          | Alta        |
| [RF05](../requisitos_elicitados.md#rf05)       | Atualização de Dados de família             | Sim          | Média       |
| [RF06](../requisitos_elicitados.md#rf06)       | Processamento de Dados                      | Sim          | Alta        |
| [RF07](../requisitos_elicitados.md#rf07)       | Correção de Inconsistências                 | Sim          | Média       |
| [RF08](../requisitos_elicitados.md#rf08)       | Consulta de Dados                           | Sim          | Não Fazer   |
| [RF09](../requisitos_elicitados.md#rf09)       | Relatórios e Divulgação                     | Sim          | Baixa       |
| [RF10](../requisitos_elicitados.md#rf10)       | Formulários de Coleta                       | Sim          | Alta        |
| [RF11](../requisitos_elicitados.md#rf11)       | Cadastro MEI                                | Não          | Média       |
| [RF12](../requisitos_elicitados.md#rf12)       | Informações MEI                             | Não          | Baixa       |
| [RF13](../requisitos_elicitados.md#rf13)       | Personalização MEI                          | Não          | Média       |
| [RF14](../requisitos_elicitados.md#rf14)       | Consultar dados cadastrais                  | Sim          | Média       |
| [RF15](../requisitos_elicitados.md#rf15)       | Pré-cadastrar família                       | Sim          | Alta        |
| [RF16](../requisitos_elicitados.md#rf16)       | Localizar postos de atendimento             | Sim          | Alta        |
| [RF17](../requisitos_elicitados.md#rf17)       | Enviar notificações                         | Sim          | Alta        |
| [RF19](../requisitos_elicitados.md#rf19)       | Cadastro de Usuário                         | Sim          | Alta        |
| [RF20](../requisitos_elicitados.md#rf20)       | Atualização de Dados do Usuário             | Sim          | Média       |
| [RF21](../requisitos_elicitados.md#rf21)       | Consultar Situação Cadastral                | Sim          | Não Fazer   |
| [RF22](../requisitos_elicitados.md#rf22)       | Emissão de Comprovante de Cadastro          | Sim          | Média       |
| [RF23](../requisitos_elicitados.md#rf23)       | Filtragem de Benefícios                     | Não          | Alta        |
| [RF24-v2](../requisitos_elicitados.md#rf24-v2) | Consulta de status de Benefícios            | Sim          | Alta        |
| [RF25](../requisitos_elicitados.md#rf25)       | Informações Cadastrais                      | Sim          | Média       |
| [RF26](../requisitos_elicitados.md#rf26)       | Chatbot de atendimento automatizado         | Não          | Baixa       |
| [RF27](../requisitos_elicitados.md#rf27)       | Notificação de pendências ou atualizações   | Não          | Alta        |
| [RF28-v2](../requisitos_elicitados.md#rf28-v2) | Simulador de benefícios sociais             | Não          | Baixa       |
| [RF29](../requisitos_elicitados.md#rf29)       | Upload de documentos                        | Não          | Alta        |
| [RF30](../requisitos_elicitados.md#rf30)       | Agendamento de atendimento no CRAS          | Não          | Alta        |
| [RF31](../requisitos_elicitados.md#rf31)       | Notificações Personalizadas                 | Não          | Não Fazer   |
| [RF32](../requisitos_elicitados.md#rf32-v2)    | Guia de Atualização Cadastral               | Não          | Alta        |
| [RF33](../requisitos_elicitados.md#rf33)       | Simulador de Benefícios                     | Não          | Baixa       |
| [RF34](../requisitos_elicitados.md#rf34)       | Chat de Atendimento                         | Não          | Média       |
| [RF35](../requisitos_elicitados.md#rf35)       | Tutoriais Interativos                       | Não          | Alta        |
| [RF36](../requisitos_elicitados.md#rf36)       | Vídeos Explicativos                         | Não          | Média       |
| [RF37](../requisitos_elicitados.md#rf37)       | Assistência por Voz                         | Não          | Média       |
| [RF38](../requisitos_elicitados.md#rf38)       | Modo escuro                                 | Não          | Alta        |
| [RF40-v2](../requisitos_elicitados.md#rf40-v2) | Login                                       | Sim          | Alta        |


<center>
    Autor(es): 
    <a href="https://github.com/RA-Salles" target="_blank">Ryan Salles</a> 
</center>

## Requisitos Não Funcionais
Essa seção apresenta os resultados da priorização dos requisitos não funcionais elicitados por meio da Tabela 2.

<center>
    <b>Tabela 2:</b> Requisitos Não Funcionais elicitados
</center>

| ID                                         | Nome                                               | Implementado |Prioridade |
| :----------------------------------------: | :------------------------------------------------: | :----------: |:---------:|
| [RNF01](../requisitos_elicitados.md#rnf01) | Desempenho                                         | Não          | Alta      |
| [RNF02](../requisitos_elicitados.md#rnf02) | Segurança                                          | Sim          | Alta      |
| [RNF03](../requisitos_elicitados.md#rnf03) | Escalabilidade                                     | Sim          | Alta      |
| [RNF04](../requisitos_elicitados.md#rnf04) | Conformidade Legal                                 | Sim          | Alta      |
| [RNF05](../requisitos_elicitados.md#rnf05) | Acessibilidade                                     | Não          | Média     |
| [RNF06](../requisitos_elicitados.md#rnf06) | Disponibilidade                                    | Sim          | Alta      |
| [RNF07](../requisitos_elicitados.md#rnf07) | Compatibilidade com Aplicativo Off-line            | Não          | Alta      |
| [RNF08](../requisitos_elicitados.md#rnf08) | Transmissão via Conectividade Social               | Não          | Baixa     |
| [RNF09](../requisitos_elicitados.md#rnf09) | Acesso Restrito                                    | Sim          | Alta      |
| [RNF10](../requisitos_elicitados.md#rnf10) | Interface intuitiva e amigável                     | Sim          | Média     |
| [RNF11](../requisitos_elicitados.md#rnf11) | Suporte a grande base de usuários                  | Sim          | Média     |
| [RNF12](../requisitos_elicitados.md#rnf12) | Integração com sistemas oficiais                   | Sim          | Alta      |
| [RNF13](../requisitos_elicitados.md#rnf13) | Usabilidade                                        | Não          | Média     |
| [RNF14](../requisitos_elicitados.md#rnf14) | Compatibilidade com Dispositivos                   | Sim          | Alta      |
| [RNF15](../requisitos_elicitados.md#rnf15) | Acessibilidade para pessoas com deficiência visual | Não          | Média     |
| [RNF16](../requisitos_elicitados.md#rnf16) | Backup e restauração de sessão                     | Não          | Média     |
| [RNF17](../requisitos_elicitados.md#rnf17) | Alta disponibilidade e recuperação de desastres    | Não          | Média     |
| [RNF18](../requisitos_elicitados.md#rnf18) | Possibilidade de outros idiomas                    | Não          | Baixa     |
| [RNF19](../requisitos_elicitados.md#rnf19) | Integração MEI                                     | Não          | Alta      |
| [RNF19](../requisitos_elicitados.md#rnf20) | Integração com o GOV.br                            | Não          | Alta      |

<center>
    Autor(es): 
    <a href="https://github.com/RA-Salles" target="_blank">Ryan Salles</a>
</center>

## Validação 

A priorização foi realizada presencialmente. As informações da reunião presencial são apresentadas por meio da tabela 1 e 2

<center>
    <b> Tabela 1:</b> Informações da Entrevista
</center>

| Campo   | Informação                                               |
| :-----: | :------------------------------------------------------: |
| Local   | [UnB - FCTE](https://maps.app.goo.gl/f8bxb23JLZJpw7REA)  |
| Data    | 05/06/2025                                               |
| Horário | 9:00                                                     |
| Duração | Cerca de 20 minutos                                      |


<center>
    <b>Autor(es):</b><a href="https://github.com/RA-Salles" target="_blank"> Ryan Salles</a>
</center>
<br></br>
<center>
    <b> Tabela 2:</b> Participantes da Entrevista
</center>

| Nome                                             | Função                   |
| :------------------------------------------:     | :----------------------: |
| Artur                                            | Usuário/ Project Owner   |
| [João Pedro](https://github.com/johnaopedro)     | Entrevistador            |
| [Ryan Salles](https://github.com/johnaopedro)    | Secretário               |
| [João Igor](https://github.com/johnaopedro)      | Observador               |
| [Gabriel Flores](https://github.com/johnaopedro) | Secretário               |

<center>
    <b>Autor(es):</b><a href="https://github.com/RA-Salles" target="_blank"> Ryan Salles</a>
</center>
<br></br>
<center>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/HV6II_-XTVc?si=EM-kqJggTzlJKyXO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</center>

## Conclusão

A aplicação do método Three-Level Scale neste estudo permitiu organizar e priorizar os requisitos funcionais e não funcionais do sistema Cadastro Único, considerando sua importância e urgência. Essa priorização é essencial para garantir que os esforços sejam direcionados aos aspectos mais críticos do sistema.

## Referências

> Three level scale: Setting requirement priorities. In: WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. [S. l.]: Microsoft Press, 2013. cap. 16, p. 319-320. ISBN 0735679665.

##### Imagem 1: Three Level Scale

<div style="text-align: center;">
    <img src="../../../assets/referencias/three_level_scale/three_level_scale1.png" alt="Three Level Scale 1">
</div>

**Fonte:** Adaptado de WIEGERS, Karl E.; BEATTY, Joy. *Software Requirements*. 3. ed. [S. l.]: Microsoft Press, 2013. cap. 16, p. 319-320.

##### Imagem 2: Three Level Scale

<div style="text-align: center;">
    <img src="../../../assets/referencias/three_level_scale/three_level_scale2.png" alt="Three Level Scale 2">
</div>

**Fonte:** Adaptado de WIEGERS, Karl E.; BEATTY, Joy. *Software Requirements*. 3. ed. [S. l.]: Microsoft Press, 2013. cap. 16, p. 319-320.

## Histórico de Versões

| Versão  | Data       | Descrição                                                      | Autor                                                                | Revisor                                            |
| :-----: | :----:     | :----------:                                                   | :------------:                                                       | :--------:                                         |
| 1.0     | 28/04/2025 | Criação da página da técnica Three Level Scale                 | [João Pedro Costa](https://github.com/johnaopedro)                   | [Ryan Salles](https://github.com/RA-Salles)        |
| 1.1     | 03/05/2025 | Atualização da aplicação da técnica                            | [João Pedro Costa](https://github.com/johnaopedro)                   | [Ryan Salles](https://github.com/RA-Salles)        |
| 1.2     | 04/05/2025 | Alteração nas prioridades do MEI                               | [Ryan Salles](https://github.com/RA-Salles)                          | [João Pedro Costa](https://github.com/johnaopedro) |
| 1.3     | 04/05/2025 | Adicionando links e corrigindo tabelas                         | [João Pedro Costa](https://github.com/johnaopedro)                   | [Ryan Salles](https://github.com/RA-Salles)        |
| 1.4     | 06/05/2025 | Ajustando conteúdo, adicionando imagens, o video e referências | [João Pedro Costa](https://github.com/johnaopedro)                   | [Julia Gabriela](https://github.com/JuliaGabP)     |
| 2.0     | 02/07/2025 | Adequação do documento para validação e conserto em cascata    | [Ryan Salles](https://github.com/RA-Salles)                          | [João Pedro Costa](https://github.com/johnaopedro) |
