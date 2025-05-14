# Cenários

Esse documento descreverá os cenários para o aplicativo CadÚnico

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

**Cenário 4: Conferir informações sobre benefícios**

**Nome do Cenário:** Conferir Informações sobre benefícios
**Ator principal:**  Usuário com ou sem autenticação. 
**Ator Secundário:** Aplicativo CadÚnico.
**Contexto:** O usuário gostaria de verificar o funcionamento de demais benefícios disponíveis e descobrir se são aplicáveis para sua condição.
**Pré-condições:** Um celular smartphone ou computador funcional compatível com o aplicativo.  
**Fluxo principal:**  
1. O usuário abre o aplicativo. 
2. O usuário acessa a tela de informações.
3. O aplicativo acessa sua base de dados local e apresenta os benefícios disponíveis.
4. O usuário acessa a tela específica sobre o benefício que gostaria de saber mais sobre.
5. O usuário lê as informações.  

**Pós-condições:** O usuário obtém as informações.
**Exceções:**  
1. Navegador do computador e/ou celular estão desatualizados.
2. O computador não possui internet. 

**Cenário 5: Verificar postos de atentdimento**

**Nome do Cenário:** Verificar postos de atendimento
**Ator principal:**  Usuário com ou sem autenticação 
**Ator Secundário:** Sistema CadÚnico, Aplicativo CadÚnico. 
**Contexto:** O usuário gostaria de verificar o local e horário de postos de atentdimento para poder ser atendido pessoalmente.
**Pré-condições:** Um celular smartphone ou computador funcional compatível com o aplicativo com acesso à internet.  
**Fluxo principal:**  
1. O usuário abre o aplicativo. 
2. O usuário acessa a tela de informações sobre postos de atendimento.
3. O usuário insere estado, município e tipo de posto.
4. O sistema verifica as informações mais recentes e envia para o aplicativo.
5. O aplicativo apresenta as informações recebidas pelo sistema. 
6. O usuário verifica os postos de atendimento. 

**Pós-condições:** O usuário obtém as informações desejadas.
**Exceções:**  
1. Navegador do computador e/ou celular estão desatualizados.
2. O usuário não possui acesso à internet. 
3. O usuário obtém um erro de interface e necessita resetar o aplicativo. 

**Cenário 6: Cadastro de Família**

**Nome do Cenário:** Cadastrar nova família no sistema  
**Ator principal:** Responsável familiar  
**Ator Secundário:** Sistema CadÚnico, Aplicativo CadÚnico  
**Contexto:** O responsável familiar deseja cadastrar sua família no Cadastro Único para acessar benefícios sociais.  
**Pré-condições:** Um celular smartphone ou computador funcional compatível com o aplicativo com acesso à internet; documentos dos membros da família.  

**Fluxo principal:**  
1. O usuário acessa o aplicativo.  
2. O usuário seleciona a opção “Cadastrar Família”.  
3. O sistema solicita dados pessoais do responsável (nome, CPF, nascimento, endereço, telefone).  
4. O usuário insere os dados dos demais membros da família (nome, parentesco, CPF/RG, data de nascimento, escolaridade, renda).  
5. O sistema valida os dados e verifica duplicidades.  
6. O usuário revisa e confirma o cadastro.  
7. O sistema emite um protocolo e registra o envio para análise.  

**Pós-condições:** A família é registrada como novo grupo familiar no sistema, com cadastro pendente de validação.  
**Exceções:**  
1. CPF do responsável já cadastrado em outro grupo familiar.  
2. Dados de algum membro incompletos ou inválidos.  
3. Falha na comunicação com o sistema durante o envio do formulário.  

**Cenário 7: Alteração de Dados da Família Cadastrada**

**Nome do Cenário:** Atualizar dados da composição familiar  
**Ator principal:** Responsável familiar  
**Ator Secundário:** Sistema CadÚnico, Aplicativo CadÚnico  
**Contexto:** A família cadastrada passou por mudanças (como saída ou entrada de membros, mudança de endereço ou de renda) e deseja atualizar o cadastro.  
**Pré-condições:** Um celular smartphone ou computador funcional compatível com o aplicativo com acesso à internet; o responsável deve estar autenticado no aplicativo.  

**Fluxo principal:**  
1. O usuário abre o aplicativo.  
2. O usuário acessa a opção “Atualizar Cadastro Familiar”.  
3. O sistema exibe os dados da família previamente cadastrados.  
4. O usuário edita informações desejadas: adição/remoção de membros, alteração de renda, escolaridade ou endereço.  
5. O sistema valida os novos dados inseridos.  
6. O usuário confirma as alterações e envia o formulário.  
7. O sistema gera um protocolo e registra a atualização como pendente de validação.  

**Pós-condições:** As informações da família são atualizadas no sistema e aguardam análise por um agente responsável.  
**Exceções:**  
1. Tentativa de excluir todos os membros da família.  
2. Dados inconsistentes (ex: renda muito alta ou CEP inválido).  
3. Falha no envio devido a problemas de conexão ou sessão expirada.  

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
| 1.3    | 12/05/2025 | Inserindo 2 novos cenários. | [Ryan Salles](https://github.com/RA-Salles) | [João Pedro](https://github.com/joaopedro) |
| 1.4    | 13/05/2025 | Inserindo 2 novos cenários. | [Julia Gabriela](https://github.com/JuliaGabP) | [João Pedro](https://github.com/joaopedro) |

