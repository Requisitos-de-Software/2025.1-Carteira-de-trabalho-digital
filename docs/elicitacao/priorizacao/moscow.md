# MoSCoW

## Funções dos autores

| Nome                 | Função                                                            | 
|----------------------|----------------------------------------------------------------   |
|[João Pedro Costa](https://github.com/johnaopedro)| Ajustes gerais| 
|[Julia Gabriela](https://github.com/JuliaGabP)|Revisão geral.| 
|[Ryan Salles](https://github.com/RA-Salles)|Criação do documento.| 
<center>
    Autor(es): 
    <a href="https://github.com/johnaopedro" target="_blank">João Pedro Costa</a>
</center>

# Introdução 

Esse documento visa priorizar os requisitos elicitados utilizando a técnica MoSCoW.

Segundo Wiegers (2013), a técnica de priorização MoSCoW funciona como uma forma de explicar e demonstrar aos clientes e partes interessadas quando e se uma determinada funcionalidade será implementada utilizando a escala de nome homônimo, apresentada por meio do Tabela 1.

<center>
    <b>Tabela 1:</b> Escala MoSCoW
</center>

| Sigla | Nome | Significado|
|:-----:|:----:|:----------:|
| M     | Must   | O requisito precisa ser implementado para obter sucesso. Ausência destes requisitos implicam na não realização do projeto. |
| S     | Should | O requisito é importante e deve ser implementado, se possível. Ausências causam impactos relevante, mas não catastróficos. |
| C     | Could  | O requisito pode ser implementado caso hajam recursos remanescentes para tal. Ausências causam impactos mínimos. |
| W     | Won't  | O requisito não será implementado nesse período. A ausência desse requisito não causará impactos durante o período |

<center>
    <b> Autor(es): </b> <a href="https://github.com/RA-Salles" target="_blank">Ryan Salles</a>
</center>

Os requisitos priorizados por essa técnica são essencialmente mutáveis ao apresentar a classifiação W com a restrição de um período de tempo, podendo ser alterada para outra classificação no futuro. Caso isso não seja esclarecido, as partes interessadas, clientes e/ou podem se sentir compelidas a manter o maior número possível de requisitos na categoria Must.  

# Metodologia
Essa seção tratará brevemente sobre como a técnica foi utilizada.

Para cada requisito elicitado, ele foi separado em um requisito funcional ou não funcional, posteriormente, ele foi priorizado utilizando o modelo da Tabela 2, cada um correspondendo a uma tupla. 
<center>
    <b>Tabela 2:</b> Modelo de priorização
</center>

| Tipo | Nome | Rastro | Prioridade |
|:----:|:----:|:------:|:----------:|
|RX  | Um nome descritivo | QSTX, ENTY, ADDZ | MSCW |

<center>
    <b> Autor(es): </b> <a href="https://github.com/RA-Salles" target="_blank">Ryan Salles</a>
</center>

Legenda:
- RX : Requisito n° X, podendo ser um Requisito Funcional(RF) ou Não Funcional(RNF).
- QSTX, ENTY, etc. : Um código de identificação para onde o requisito foi elicitado
- MSCW : Uma categoria de priorização MoSCoW. 

# Priorização
Essa seção contêm a priorização realizada.

## Requisitos Funcionais
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
    <b>Tabela 3:</b> Requisitos Funcionais Priorizados
</center>

| ID      | Nome do Requisito                     | Descrição                                                                    | Rastreabilidade                      | Prioridade |
|---------|---------------------------------------|------------------------------------------------------------------------------| -------------------------------------|------------|
| RF01    | Cadastro de Famílias                  | Cadastro de famílias com renda até meio salário mínimo ou programas sociais. | Questionário / Análise de documentos | M          |
| RF02    | Cadastro de Pessoas                   | Registro de identificação, escolaridade etc.                                 | Questionário / Análise de documentos | M          |
| RF03    | Cadastro de Domicílios                | Registro de tipo de construção, saneamento, etc.                             | Questionário / Análise de documentos | M          |
| RF04    | Cadastro de Agricultores Familiares   | Registro de posse de terra, renda e trabalho.                                | Questionário / Análise de documentos | S          |
| RF05    | Atualização de Dados                  | Atualização dos dados cadastrais.                                            | Questionário / Introspecção          | M          |
| RF06    | Processamento de Dados                | Envio à CAIXA e geração de NIS.                                              | Questionário / Análise de documentos | M          |
| RF07    | Correção de Inconsistências           | Correção e retransmissão de dados.                                           | Análise de Documentos                | M          |
| RF08    | Consulta de Dados                     | Consulta cadastral e benefícios.                                             | Questionário / Introspecção          | M          |
| RF09    | Relatórios e Divulgação               | Geração de relatórios e compartilhamento com órgãos.                         | Análise de Documentos                | M          |
| RF10    | Formulários de Coleta                 | Formulários principais e suplementares.                                      | Análise de Documentos                | M          |
| RF11    | Cadastro MEI                          | Cadastro de usuário como MEI.                                                | Análise de Documentos                | W          |
| RF12    | Informações MEI                       | Seção sobre MEI.                                                             | Análise de Documentos                | C          |
| RF13    | Personalização MEI                    | Conteúdos personalizados conforme setor e região.                            | Análise de Documentos                | W          |
| RF14    | Consultar dados cadastrais            | Visualização dos dados do Cadastro Único.                                    | Introspecção                         | M          |
| RF15    | Pré-cadastrar família                 | Início de pré-cadastro de unidade familiar.                                  | Introspecção                         | M          |
| RF16    | Localizar postos de atendimento       | Localiza CRAS com base na localização do usuário.                            | Introspecção                         | C          |
| RF17    | Enviar notificações                   | Envio de mensagens importantes via app.                                      | Introspecção                         | C          |
| RF18    | Integrar com o CNIS                   | Integração automática com CNIS.                                              | Introspecção                         | S          |
| RF19    | Cadastro de Usuário                   | Coleta de dados pessoais.                                                    | Introspecção                         | M          |
| RF20    | Atualização de Dados                  | Atualização dos dados cadastrais.                                            | Introspecção                         | M          |
| RF21    | Consultar Situação Cadastral          | Verificação do status do cadastro.                                           | Introspecção                         | M          |
| RF22    | Emissão de Comprovante de Cadastro    | Geração de comprovante de cadastro.                                          | Introspecção                         | S          |
| RF23    | Filtragem de Benefícios               | Filtro de benefícios conforme dados cadastrados.                             | Introspecção                         | S          |
| RF24    | Consulta de Benefícios                | Consulta de status de benefícios.                                            | Entrevista                           | M          |
| RF25    | Informações Cadastrais                | Visualização de informações cadastrais.                                      | Entrevista                           | M          |

<center>
    Autor(es): 
    <a href="https://github.com/RA-Salles" target="_blank">Ryan Salles</a>, 
    <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a>
</center>

## Requisitos Não Funcionais
Essa seção apresenta os requisitos não funcionais priorizados por meio da Tabela 4.

<center>
    <b>Tabela 4:</b> Requisitos Não Funcionais Priorizados
</center>

| ID      | Nome do Requisito                       | Descrição                                                          | Rastreabilidade                      | Prioridade |
| ------- | -------------------------------------   | ------------------------------------------------------------------ | ---------------------------------    | ---------- |
| RNF01   | Desempenho                              | Processamento de dados em até 48h.                                 | Análise de documentos                | M          |
| RNF02   | Segurança                               | Confidencialidade e autenticação.                                  | Análise de documentos / Introspecção | M          |
| RNF03   | Escalabilidade                          | Suportar até 19,5 milhões de famílias.                             | Análise de documentos                | M          |
| RNF04   | Conformidade Legal                      | Atender portarias e regras da Senarc.                              | Análise de documentos                | M          |
| RNF05   | Acessibilidade                          | Acessível para operadores estaduais e municipais.                  | Análise de documentos                | M          |
| RNF06   | Disponibilidade                         | Sistema disponível diariamente.                                    | Análise de documentos / Introspecção | M          |
| RNF07   | Compatibilidade com Aplicativo Off-line | Compatível com app offline dos municípios.                         | Análise de documentos                | M          |
| RNF08   | Transmissão via Conectividade Social    | Uso exclusivo da ferramenta da CAIXA.                              | Análise de documentos                | M          |
| RNF09   | Acesso Restrito                         | Acesso restrito a instituições autorizadas.                        | Análise de documentos                | M          |
| RNF10   | Integração MEI                          | Comunicação com sistemas voltados ao MEI.                          | Análise de documentos                | W          |
| RNF11   | Interface intuitiva e amigável          | Interface simples e de fácil navegação.                            | Introspecção, Entrevista             | M          |
| RNF12   | Suporte a grande base de usuários       | Suporte a muitos acessos simultâneos.                              | Introspecção                         | M          |
| RNF13   | Integração com sistemas oficiais        | Integração com sistemas como CNIS.                                 | Introspecção                         | M          |
| RNF14   | Usabilidade                             | Navegação intuitiva.                                               | Introspecção                         | M          |
| RNF15   | Segurança                               | Criptografia e proteção de dados sensíveis.                        | Introspecção                         | M          |
| RNF16   | Performance                             | Respostas em até 3 segundos.                                       | Introspecção                         | S          |
| RNF17   | Compatibilidade com Dispositivos        | Compatível com Android e iOS.                                      | Introspecção                         | M          |
| RNF18   | Disponibilidade                         | 99% de disponibilidade.                                            | Introspecção                         | M          |
<center>
    Autor(es): 
    <a href="https://github.com/RA-Salles" target="_blank">Ryan Salles</a>, 
    <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a>
</center>

# Validação 

## Validação 

A validação da priorização foi realizada presencialmente. As informações da reunião presencial são apresentadas por meio da tabela 1 e 2

<center>
    <b> Tabela 1:</b> Informações da Entrevista
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

<center>
    <b> Tabela 2:</b> Participantes da Entrevista
</center>

| Nome                                         | Função                   |
| :------------------------------------------: | :----------------------: |
| Artur                                        | Usuário/ Project Owner   |
| [João Pedro](https://github.com/johnaopedro) | Entrevistador            |
| [Ryan Salles](https://github.com/RA-Salles)  | Auxiliar                 |
| [João Igor](https://github.com/JoaoPC10)     | Auxiliar                 |
| [Gabriel Flores](https://github.com/Gabrielfcoelho)  | Auxiliar         |

<center>
    <b>Autor(es)</b><a href="https://github.com/RA-Salles" target="_blank">Ryan Salles</a>
</center>

<iframe width="560" height="315" src="https://www.youtube.com/embed/1K4FEeSuBGc?si=97xbGpE2TW24kuwV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

# Referências
> FIRST things first: Setting requirement priorities. In: WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. [S. l.]: Microsoft Press, 2013. cap. 16, p. 313-329. ISBN 0735679665.

# Histórico de Versões 
| Versão  | Data       | Descrição                              | Autor                                              | Revisor                                                          |
| :-----: | :----:     | :----------:                           | :------------:                                     | :--------:                                                       |
| 1.0     | 28/04/2025 | Criação da página da técnica MoSCoW    | [Ryan Salles](https://github.com/RA-Salles)        |  [João Pedro Costa](https://github.com/johnaopedro)              |
| 1.1     | 04/05/2025 | Adicionando links e corrigindo tabelas | [João Pedro Costa](https://github.com/johnaopedro) | [Ryan Salles](https://github.com/RA-Salles)                      |
