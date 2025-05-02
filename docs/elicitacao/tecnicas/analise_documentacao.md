# Análise de documentação

## Introdução
Esse documento apresenta a análise de documentação realizada pelo grupo 4 para os propósitos de compreender e elicitar os requisitos do aplicativo
cadastro único. 

Para os fins dessa análise, para todo documento analisado, uma análise será construída e, com base nessa análise, serão elicitados requisitos seguindo o modelo da tabela 1.

<center> <b>Tabela 1:</b> Requisitos de exemplo </center>
  
| **ID** | **Requisito Funcional** | **Descrição** |
|:------:|:-----------------------:|:-------------:|
| RE1    | Realizar uma determinada operação | O usuário é capaz de realizar a operação dentro do sistema |

<center>
 Autor(a): <a href="https://github.com/RA-Salles" target="_blank">Ryan Salles</a>
</center>

## Documentos análisados
Essa seção contém resumos dos documentos analisados para os fins de subsequente elicitação. 

### [Cadastro Único dos Programas Sociais - CadÚnico](https://ces.ibge.gov.br/base-de-dados/metadados/mds/cadastro-unico-dos-programas-sociais-cadunico.html)
O Cadastro Único dos Programas Sociais (CadÚnico) é um sistema de cadastro de famílias de baixa renda no Brasil, gerido pelo Ministério do Desenvolvimento Social e Combate à Fome, com suporte técnico da CAIXA. Criado em julho de 2001 pelo Decreto nº 3.877, o CadÚnico tem como objetivo identificar famílias com renda mensal de até meio salário mínimo por pessoa para subsidiar o planejamento de políticas públicas, podendo incluir famílias com renda superior caso estejam vinculadas a programas sociais. Ele abrange todos os municípios brasileiros e opera diariamente. A coleta de dados é realizada pelos municípios por meio de formulários preenchidos e digitados no Aplicativo de Entrada e Manutenção de Dados (off-line), sendo transmitidos à CAIXA via Conectividade Social.

A CAIXA processa os dados, atribui um Número de Identificação Social (NIS) único para cada pessoa cadastrada e devolve os resultados aos municípios em até 48 horas. Caso haja inconsistências, os dados são corrigidos e retransmitidos pelos municípios. As principais variáveis incluem informações sobre domicílio, pessoas e agricultores familiares. A documentação operacional é composta por formulários principais e suplementares, abrangendo diferentes situações, como vinculação a programas e pessoas em situação de rua. A divulgação ocorre em níveis nacional, regional, estadual e municipal, com relatórios anuais e acesso à base de dados mediante aprovação de projetos e acordos de cooperação técnica. Desde sua criação, o CadÚnico integrou-se a programas como o Bolsa Escola e o Bolsa Família, e, a partir de 2005, iniciou um processo contínuo de atualização cadastral com a adesão formal de estados e municípios. Trata-se de uma ferramenta essencial para identificar e atender famílias de baixa renda, permitindo a formulação de políticas públicas e a gestão de programas sociais.

### INSERIR DOC JOHN MIDIA
TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!
### INSERIR DOC JULIA
TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!TODO!

## Requisiots Elicitados
Essa seção contém os requisitos elicitados por consequência da análise da documentação. 

<center> <b>Tabela 2:</b> Requisitos Funcionais </center>

| **ID** | **Requisito Funcional**                                                                 | **Descrição**                                                                                                                                                                                                 |
|--------|-----------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| RF01   | Cadastro de Famílias                                                                   | Permitir o cadastro de famílias com renda mensal de até meio salário mínimo por pessoa ou vinculadas a programas sociais.                                                                                   |
| RF02   | Cadastro de Pessoas                                                                    | Registrar informações pessoais, como dados de identificação, documentação, frequência escolar, grau de instrução, entre outros.                                                                             |
| RF03   | Cadastro de Domicílios                                                                 | Registrar características do domicílio, como tipo de construção, abastecimento de água, iluminação, escoamento sanitário, entre outros.                                                                     |
| RF04   | Cadastro de Agricultores Familiares                                                    | Registrar informações sobre posse de terra, atividade primária, contratação de mão de obra e composição da renda.                                                                                           |
| RF05   | Atualização de Dados                                                                   | Permitir a atualização diária dos dados das famílias cadastradas.                                                                                                                                           |
| RF06   | Processamento de Dados                                                                 | Transmitir os dados coletados para a CAIXA, processá-los e atribuir um Número de Identificação Social (NIS) único para cada pessoa cadastrada.                                                              |
| RF07   | Correção de Inconsistências                                                            | Permitir a correção de inconsistências detectadas no processamento e retransmissão dos dados.                                                                                                               |
| RF08   | Consulta de Dados                                                                      | Permitir a consulta de dados cadastrais, situação de benefícios e ações de gestão de benefícios por meio do NIS.                                                                                            |
| RF09   | Relatórios e Divulgação                                                                | Gerar relatórios anuais com o perfil das famílias beneficiárias e disponibilizar dados para instituições de pesquisa e órgãos de governo mediante acordos e termos de responsabilidade.                      |
| RF10   | Formulários de Coleta                                                                  | Implementar formulários principais e suplementares para coleta de dados, abrangendo características de domicílios, famílias, pessoas, vinculação a programas e pessoas em situação de rua.                  |

<center>
 Autor(a): <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a>
</center>

### Tabela de Requisitos Não Funcionais

| **ID** | **Requisito Não Funcional**                                                            | **Descrição**                                                                                                                                                                                                 |
|--------|---------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| RNF01  | Desempenho                                                                            | Garantir o processamento dos dados e retorno aos municípios em até 48 horas.                                                                                                                                |
| RNF02  | Segurança                                                                             | Garantir a confidencialidade dos dados por meio de termos de responsabilidade e acordos de cooperação técnica, além de implementar mecanismos de autenticação para acesso aos dados.                         |
| RNF03  | Escalabilidade                                                                        | Suportar o cadastro e atualização de dados de até 19,5 milhões de famílias.                                                                                                                                  |
| RNF04  | Conformidade Legal                                                                    | Atender às regulamentações definidas pela Senarc e portarias relacionadas.                                                                                                                                   |
| RNF05  | Acessibilidade                                                                        | Garantir que o sistema seja acessível para operadores municipais e estaduais.                                                                                                                                |
| RNF06  | Disponibilidade                                                                       | Garantir que o sistema esteja disponível para uso diário.                                                                                                                                                   |
<center>
 Autor(a): <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a>
</center>
### Tabela 3: dos Requisitos Não Funcionais

| **ID** | **Restrição**                                                                          | **Descrição**                                                                                                                                                                                                 |
|--------|---------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| R01    | Compatibilidade com Aplicativo Off-line                                               | O sistema deve ser compatível com o aplicativo off-line utilizado pelos municípios para coleta e digitação de dados.                                                                                        |
| R02    | Transmissão via Conectividade Social                                                  | A transmissão de dados deve ser realizada exclusivamente por meio da ferramenta Conectividade Social da CAIXA.                                                                                              |
| R03    | Acesso Restrito                                                                       | O acesso à base de dados deve ser restrito a instituições autorizadas e mediante assinatura de termos específicos.                                                                                           |
<center>
 Autor(a): <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a>
</center>
# Referencias
> Requirements Elicitation. In: WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. [S. l.]: Microsoft Press, 2013. cap. 7, p. 128-129. ISBN 0735679665. Acesso em: 1 maio 2025.

> INSTITUTO BRASILEIRO DE GEOGRAFIA E ESTATÍSTICA (IBGE). Cadastro Único dos Programas Sociais - CadÚnico. Disponível em: https://ces.ibge.gov.br/base-de-dados/metadados/mds/cadastro-unico-dos-programas-sociais-cadunico.html. Acesso em: 1 maio 2025.

# Histórico de Versão

| Versão | Data | Descrição  | Autor(es) | Revisor(es) |
| :-----: | :----: | :----------: | :------------: | :--------: |
| 1.0 | 02/05/2025 | Criação do documento | [João Pedro](https://github.com/johnaopedro), [João Merlin](https://github.com/jvopBR), [Julia Gabriela](https://github.com/JuliaGabP), [Ryan Salles](https://github.com/RA-Salles)| A DEFINIR |
