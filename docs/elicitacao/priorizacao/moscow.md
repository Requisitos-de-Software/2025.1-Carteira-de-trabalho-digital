# MoSCoW

## Funções dos autores

| Nome                                                | Função                                                            | 
|----------------------                               |-------------------------------------------------------------------|
| [João Pedro Costa](https://github.com/johnaopedro)  | Ajustes e suporte técnico para validação                          | 
| [Julia Gabriela](https://github.com/JuliaGabP)      | Revisão geral                                                     | 
| [Ryan Salles](https://github.com/RA-Salles)         | Criação do documento, manutenção e validação                      | 
| [Gabriel Flores](https://github.com/Gabrielfcoelho) | Suporte técnico para validação                                    |
| [João Igor](https://github.com/JoaoPC10)            | Suporte técnico para validação                                    |
<center>
    Autor(es): 
    <a href="https://github.com/johnaopedro" target="_blank">João Pedro Costa</a>
</center>

## Introdução 

Esse documento visa priorizar os requisitos elicitados utilizando a técnica MoSCoW.

Segundo Wiegers (2013), a técnica de priorização MoSCoW funciona como uma forma de explicar
e demonstrar aos clientes e partes interessadas quando e se uma determinada funcionalidade
será implementada utilizando a escala de nome homônimo, apresentada por meio do Tabela 1.

<center>
    <b>Tabela 1:</b> Escala MoSCoW
</center>

| Sigla | Nome   | Nome traduzido | Significado                                                                                                                |
|:-----:|:----:  | :------------: |:----------:                                                                                                                |
| M     | Must   | Precisa        | O requisito precisa ser implementado para obter sucesso. Ausência destes requisitos implicam na não realização do projeto. |
| S     | Should | Deve           | O requisito é importante e deve ser implementado, se possível. Ausências causam impactos relevante, mas não catastróficos. |
| C     | Could  | Poderia        | O requisito pode ser implementado caso hajam recursos remanescentes para tal. Ausências causam impactos mínimos.           |
| W     | Won't  | Não Deve       | O requisito não será implementado nesse período. A ausência desse requisito não causará impactos durante o período         |

<center>
    <b> Autor(es): </b> <a href="https://github.com/RA-Salles" target="_blank">Ryan Salles</a>
</center>

Os requisitos priorizados por essa técnica são essencialmente mutáveis ao apresentar a classifiação W com a restrição de um período de tempo,
podendo ser alterada para outra classificação no futuro. Caso isso não seja esclarecido, as partes interessadas, clientes e/ou podem se sentir
compelidas a manter o maior número possível de requisitos na categoria Must.

Adicionalmente, segundo WIEGERS (2013),

## Metodologia
Essa seção tratará brevemente sobre como a técnica foi utilizada.

Para cada requisito elicitado, ele foi separado em um requisito funcional ou não funcional, posteriormente, ele foi priorizado utilizando o modelo da Tabela 2, cada um correspondendo a uma tupla. 
<center>
    <b>Tabela 2:</b> Modelo de priorização
</center>

| Tipo | Nome               | Rastro           | Prioridade |
|:----:|:----:              |:------:          |:----------:|
|RX    | Um nome descritivo | QSTX, ENTY, ADDZ | M/S/C/W       |

<center>
    <b> Autor(es): </b> <a href="https://github.com/RA-Salles" target="_blank">Ryan Salles</a>
</center>

Legenda:
- RX : Requisito n° X, podendo ser um Requisito Funcional(RF) ou Não Funcional(RNF).
- QSTX, ENTY, etc. : Um código de identificação para onde o requisito foi elicitado
- MSCW : Uma categoria de priorização MoSCoW. 

## Priorização
Essa seção contêm a priorização realizada.

### Requisitos Funcionais
Essa subseção apresenta a priorização de requisitos funcionais por meio da tabela 3. 

<!--ATENÇÃO, LEIA ESSE COMENTÁRIO
    As tabela foi feita com base na presente 
    na three level scale.

    Os seguintes requisitos foram observados como duplicatas:
    RF01 ~ RF02 ~ RF03 -> RF19. 
        O que diabos é o usuário, então? Uma pessoa física, a família? A 
        família entraria como dados do usuário, eu imagino, mas o cadastro 
        de pessoas parece equivalente ao cadastro do usuário. 

    RNF20 -> RNF19 -> RNF11.
        São equivalentes, as três pedem que a interface seja de fácil uso.
-->

<center>
    <b>Tabela 1:</b> Requisitos Funcionais Priorizados segundo a Técnica MoSCoW
</center>

| ID                                             | Nome                                        | Implementado | Prioridade  |
| :--------------------------------------------: | :-----------------------------------------: | :----------: | :---------: |
| [RF01](../requisitos_elicitados.md#rf01)       | Cadastro de Famílias                        | Sim          | Should      |
| [RF02-v2](../requisitos_elicitados.md#rf02-v2) | Cadastro de Pessoas                         | Sim          | Must        |
| [RF03](../requisitos_elicitados.md#rf03)       | Cadastro de Domicílios                      | Sim          | Should      |
| [RF04](../requisitos_elicitados.md#rf04)       | Cadastro de Agricultores Familiares         | Sim          | Must        |
| [RF05](../requisitos_elicitados.md#rf05)       | Atualização de Dados de família             | Sim          | Should      |
| [RF06](../requisitos_elicitados.md#rf06)       | Processamento de Dados                      | Sim          | Must        |
| [RF07](../requisitos_elicitados.md#rf07)       | Correção de Inconsistências                 | Sim          | Should      |
| [RF08](../requisitos_elicitados.md#rf08)       | Consulta de Dados                           | Sim          | Won't       |
| [RF09](../requisitos_elicitados.md#rf09)       | Relatórios e Divulgação                     | Sim          | Could       |
| [RF10](../requisitos_elicitados.md#rf10)       | Formulários de Coleta                       | Sim          | Must        |
| [RF11](../requisitos_elicitados.md#rf11)       | Cadastro MEI                                | Não          | Should      |
| [RF12](../requisitos_elicitados.md#rf12)       | Informações MEI                             | Não          | Could       |
| [RF13](../requisitos_elicitados.md#rf13)       | Personalização MEI                          | Não          | Should      |
| [RF14](../requisitos_elicitados.md#rf14)       | Consultar dados cadastrais                  | Sim          | Should      |
| [RF15](../requisitos_elicitados.md#rf15)       | Pré-cadastrar família                       | Sim          | Must        |
| [RF16](../requisitos_elicitados.md#rf16)       | Localizar postos de atendimento             | Sim          | Must        |
| [RF17](../requisitos_elicitados.md#rf17)       | Enviar notificações                         | Sim          | Must        |
| [RF19](../requisitos_elicitados.md#rf19)       | Cadastro de Usuário                         | Sim          | Must        |
| [RF20](../requisitos_elicitados.md#rf20)       | Atualização de Dados do Usuário             | Sim          | Should      |
| [RF21](../requisitos_elicitados.md#rf21)       | Consultar Situação Cadastral                | Sim          | Won't       |
| [RF22](../requisitos_elicitados.md#rf22)       | Emissão de Comprovante de Cadastro          | Sim          | Should      |
| [RF23](../requisitos_elicitados.md#rf23)       | Filtragem de Benefícios                     | Não          | Must        |
| [RF24-v2](../requisitos_elicitados.md#rf24-v2) | Consulta de status de Benefícios            | Sim          | Must        |
| [RF25](../requisitos_elicitados.md#rf25)       | Informações Cadastrais                      | Sim          | Should      |
| [RF26](../requisitos_elicitados.md#rf26)       | Chatbot de atendimento automatizado         | Não          | Could       |
| [RF27](../requisitos_elicitados.md#rf27)       | Notificação de pendências ou atualizações   | Não          | Must        |
| [RF28-v2](../requisitos_elicitados.md#rf28-v2) | Simulador de benefícios sociais             | Não          | Could       |
| [RF29](../requisitos_elicitados.md#rf29)       | Upload de documentos                        | Não          | Must        |
| [RF30](../requisitos_elicitados.md#rf30)       | Agendamento de atendimento no CRAS          | Não          | Must        |
| [RF31](../requisitos_elicitados.md#rf31)       | Notificações Personalizadas                 | Não          | Won't       |
| [RF32](../requisitos_elicitados.md#rf32-v2)    | Guia de Atualização Cadastral               | Não          | Must        |
| [RF33](../requisitos_elicitados.md#rf33)       | Simulador de Benefícios                     | Não          | Could       |
| [RF34](../requisitos_elicitados.md#rf34)       | Chat de Atendimento                         | Não          | Should      |
| [RF35](../requisitos_elicitados.md#rf35)       | Tutoriais Interativos                       | Não          | Must        |
| [RF36](../requisitos_elicitados.md#rf36)       | Vídeos Explicativos                         | Não          | Should      |
| [RF37](../requisitos_elicitados.md#rf37)       | Assistência por Voz                         | Não          | Should      |
| [RF38](../requisitos_elicitados.md#rf38)       | Modo escuro                                 | Não          | Must        |
| [RF40-v2](../requisitos_elicitados.md#rf40-v2) | Login                                       | Sim          | Must        |


<center>
    Autor(es): 
    <a href="https://github.com/RA-Salles" target="_blank">Ryan Salles</a> 
</center>

### Requisitos Não Funcionais
Essa seção apresenta os resultados da priorização dos requisitos não funcionais elicitados por meio da Tabela 2.

<center>
    <b>Tabela 2:</b> Requisitos Não Funcionais Priorizados segundo a técnica MoSCoW
</center>

| ID                                         | Nome                                               | Implementado |Prioridade |
| :----------------------------------------: | :------------------------------------------------: | :----------: |:---------:|
| [RNF01](../requisitos_elicitados.md#rnf01) | Desempenho                                         | Não          | Must      |
| [RNF02](../requisitos_elicitados.md#rnf02) | Segurança                                          | Sim          | Must      |
| [RNF03](../requisitos_elicitados.md#rnf03) | Escalabilidade                                     | Sim          | Must      |
| [RNF04](../requisitos_elicitados.md#rnf04) | Conformidade Legal                                 | Sim          | Must      |
| [RNF05](../requisitos_elicitados.md#rnf05) | Acessibilidade                                     | Não          | Should    |
| [RNF06](../requisitos_elicitados.md#rnf06) | Disponibilidade                                    | Sim          | Must      |
| [RNF07](../requisitos_elicitados.md#rnf07) | Compatibilidade com Aplicativo Off-line            | Não          | Must      |
| [RNF08](../requisitos_elicitados.md#rnf08) | Transmissão via Conectividade Social               | Não          | Could     |
| [RNF09](../requisitos_elicitados.md#rnf09) | Acesso Restrito                                    | Sim          | Must      |
| [RNF10](../requisitos_elicitados.md#rnf10) | Interface intuitiva e amigável                     | Sim          | Should    |
| [RNF11](../requisitos_elicitados.md#rnf11) | Suporte a grande base de usuários                  | Sim          | Should    |
| [RNF12](../requisitos_elicitados.md#rnf12) | Integração com sistemas oficiais                   | Sim          | Must      |
| [RNF13](../requisitos_elicitados.md#rnf13) | Usabilidade                                        | Não          | Should    |
| [RNF14](../requisitos_elicitados.md#rnf14) | Compatibilidade com Dispositivos                   | Sim          | Must      |
| [RNF15](../requisitos_elicitados.md#rnf15) | Acessibilidade para pessoas com deficiência visual | Não          | Should    |
| [RNF16](../requisitos_elicitados.md#rnf16) | Backup e restauração de sessão                     | Não          | Should    |
| [RNF17](../requisitos_elicitados.md#rnf17) | Alta disponibilidade e recuperação de desastres    | Não          | Should    |
| [RNF18](../requisitos_elicitados.md#rnf18) | Possibilidade de outros idiomas                    | Não          | Could     |
| [RNF19](../requisitos_elicitados.md#rnf19) | Integração MEI                                     | Não          | Must      |
| [RNF19](../requisitos_elicitados.md#rnf20) | Integração com o GOV.br                            | Não          | Must      |

<center>
    Autor(es): 
    <a href="https://github.com/RA-Salles" target="_blank">Ryan Salles</a>
</center>

## Conclusão

Uma técnica razoavelmente similar ao Three Level Scale, todavia, pouco restrita pela bibliografia utilizada. 

Apesar de permitir dinamismo na priorização e discussão dos requisitos apresentados, além das prioridades poderem ser 
diretamente comparáveis ao three level scale, o MoSCoW demonstra dificuldade em evitar a necessidade de ser explicado
ao cliente, não possui uma tradução fácil do método e demonstra ser de uso difícil para grandes grupos de usuários, observado
que não é possível realizar a exata média de um Must com um Should, por exemplo, levando a dificuldades da ordem exata
com a qual os requisitos deveriam ser implementados, levando em consideração a dependência entre requisitos.
A 100$ parece permitir maiores facilidades nesse aspecto de grupos de usuários e uma priorização final mais clara. 

Ao menos, a bibliografia utilizada dá a entender que é possível transferir a escala da Three Level Scale para o MoSCoW sem
grandes esforços, portanto exigindo menos retrabalho para priorizar os requisitos. 


## Validação 

A validação da priorização foi realizada presencialmente. As informações da reunião presencial são apresentadas por meio da tabela 3 e 4.

<center>
    <b> Tabela 3:</b> Informações da Entrevista
</center>

| Campo   | Informação                                               |
| :-----: | :------------------------------------------------------: |
| Local   | [UnB - FCTE](https://maps.app.goo.gl/f8bxb23JLZJpw7REA)  |
| Data    | 05/06/2025                                               |
| Horário | 9:20                                                     |
| Duração | Cerca de 5 minutos                                       |

<center>
    <b>Autor(es)</b><a href="https://github.com/RA-Salles" target="_blank">Ryan Salles</a>
</center>

---

<center>
    <b> Tabela 4:</b> Participantes da Entrevista
</center>

| Nome                                                 | Função                   |
| :------------------------------------------:         | :----------------------: |
| Artur                                                | Usuário/ Project Owner   |
| [João Pedro](https://github.com/johnaopedro)         | Secretário               |
| [Ryan Salles](https://github.com/RA-Salles)          | Entrevistador            |
| [João Igor](https://github.com/JoaoPC10)             | Observador               |
| [Gabriel Flores](https://github.com/Gabrielfcoelho)  | Secretário               |

<center>
    <b>Autor(es): </b><a href="https://github.com/RA-Salles" target="_blank">Ryan Salles</a>
</center>

---

<center>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/1K4FEeSuBGc?si=97xbGpE2TW24kuwV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</center>

---

## Referências
> FIRST things first: Setting requirement priorities. In: WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. [S. l.]: Microsoft Press, 2013. cap. 16, p. 320-321. ISBN 0735679665.

A figura 1 apresenta a referência WIEGERS e BEATTY (2013).

<center>
    <b>Figura 1:</b> MoSCoW segundo WIEGERS e BEATTY.
</center>

<div style="text-align: center;">
    <img src="../../../assets/referencias/moscow/moscow_wiegers.png" alt="Three Level Scale 2">
</div>

<center>
    <b>Fonte: </b> Adaptado de WIEGERS e BEATTY (2013).
</center>

---

## Histórico de Versões
 
| Versão  | Data       | Descrição                                                                                   | Autor                                              | Revisor                                            |
| :-----: | :----:     | :----------:                                                                                | :------------:                                     | :--------:                                         |
| 1.0     | 28/04/2025 | Criação da página da técnica MoSCoW                                                         | [Ryan Salles](https://github.com/RA-Salles)        | [João Pedro Costa](https://github.com/johnaopedro) |
| 1.1     | 04/05/2025 | Adicionando links e corrigindo tabelas                                                      | [João Pedro Costa](https://github.com/johnaopedro) | [Ryan Salles](https://github.com/RA-Salles)        |
| 2.0     | 03/07/2025 | Refatoração do documento e conserto em cascata ocasionado pelo versionamento dos requisitos | [Ryan Salles](https://github.com/RA-Salles)        | [João Pedro Costa](https://github.com/johnaopedro) |
