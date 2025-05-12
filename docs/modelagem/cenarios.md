# Cenários

Esse documento descreverá os cenários para o aplicativo CadÚnico

## Introdução 

Cenários são uma forma de modelagem de requisitos 

## Cenários

Essa seção contém os cenários elaborados com base nos requisitos elicitados e observações realizadas durante a etapa de elicitação. 

**Cenário 1: Visualizar Benefícios**  
**Nome do Cenário:** Visualização de benefícios ativos  
**Ator principal:** Usuário cadastrado  
**Contexto:** O usuário deseja verificar se há algum benefício ativo vinculado ao seu cadastro no
CadÚnico, como Bolsa Família.  
**Pré-condições:** O usuário já possui cadastro validado no CadÚnico e está autenticado no
aplicativo.  
**Fluxo principal:**  
1. O usuário acessa o aplicativo do CadÚnico.
2. Seleciona a opção “Meus Benefícios”.
3. O sistema busca as informações junto à base do governo.
4. É exibida uma lista de benefícios ativos, com nome do programa, status
(ativo/suspenso), valor recebido e data da última atualização.   

**Pós-condições:** O usuário visualiza seus benefícios ativos de forma clara e atualizada.  
**Exceções:**  
- Caso o usuário não possua benefícios ativos, o sistema exibe uma mensagem
informativa.
- Se ocorrer falha de comunicação com o banco de dados, o sistema exibe uma mensagem
de erro.

**Cenário 2: Alteração de Dados Cadastrais**  
**Nome do Cenário:** Atualização de dados pessoais e residênciais  
**Ator principal:** Usuário cadastrado  
**Contexto:** O usuário mudou de endereço e precisa atualizar suas informações no CadÚnico.  
**Pré-condições:** O usuário está logado e seu cadastro já existe no sistema.  
**Fluxo principal:**  
1. O usuário acessa o aplicativo e entra na seção “Atualizar Cadastro”.  
2. Informa que deseja alterar dados residenciais.  
3. Atualiza endereço, telefone e informações de contato.  
4. Confirma os dados e envia para análise.  
5. O sistema notifica que a atualização será verificada por um agente público.  

**Pós-condições:** Os dados atualizados são enviados para análise, e o usuário recebe uma
notificação de que a atualização está em processo.    
**Exceções:**  
- Se o CPF estiver em inconsistência, o sistema bloqueia a alteração e exibe mensagem.
- Se o endereço informado for inválido (CEP inexistente), o sistema solicita correção.

**Cenário 3: Realizar Cadastro no Aplicativo**  
**Nome do Cenário:** Primeiro cadastro no CadÚnico  
**Ator principal:** Novo usuário  
**Contexto:** O usuário nunca utilizou o CadÚnico e quer se cadastrar pelo aplicativo.  
**Pré-condições:** O usuário possui documentos válidos e acesso à internet.  
**Fluxo principal:**  
1. O usuário instala e abre o aplicativo.
2. Seleciona “Fazer Primeiro Cadastro”.
3. Preenche os dados pessoais (nome, CPF, data de nascimento, endereço, composição
familiar).
4. Envia a solicitação.
5. O sistema gera um protocolo e informa que o usuário será contactado para validação.  

**Pós-condições:** Um cadastro preliminar é criado e enviado para avaliação por um agente social.  
**Exceções:**  
- Se o CPF já existir no sistema, o cadastro é bloqueado e o sistema sugere login.
- Caso falte algum dado obrigatório, o app impede o envio e destaca os campos
incompletos.

## Vídeo
O vídeo abaixo refere-se ao cenário, descrito neste artefato, realizada no **Microsoft Teams**:

<iframe width="560" height="315" src="https://www.youtube.com/embed/DohE9Bf-ppg?si=w5koy8vx1bkrT6M8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Referências
CARLOS EDUARDO VAZQUEZ; GUILHERME SIQUEIRA SIMÕES. Engenharia de Requisitos. [s.l.] Brasport, 2016.

<div style="text-align: left;">
    <img src="../../assets/referencias/cenarios/referencia_cenarios.jpeg" alt="Cenários">
</div>

## Bibliografia

## Histórico de Versão
| Versão |    Data    |    Descrição     |         Autor         |       Revisor      |
| :----: | :--------: | :--------------: | :-------------------: | :----------------: |
|  1.0   | 08/05/2025 | Criando a pagina e adicionando a introdução de cada tema | [Ryan Salles](https://github.com/RA-Salles), [Julia Gabriela](https://github.com/JuliaGabP) | [João Pedro](https://github.com/joaopedro) |
|  1.1   | 12/05/2025 | Criação de cenários e referências| [Julia Gabriela](https://github.com/JuliaGabP) | [João Pedro](https://github.com/joaopedro) |
|  1.2   | 12/05/2025 | Inserindo vídeo e atualizando formatação| [Julia Gabriela](https://github.com/JuliaGabP) | [João Pedro](https://github.com/joaopedro) |

