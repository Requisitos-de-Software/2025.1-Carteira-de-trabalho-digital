# Cenários

## Introdução

Este documento apresenta uma série de cenários desenvolvidos como parte do processo de engenharia de requisitos do aplicativo Cadastro Único (CadÚnico). Os cenários são descrições estruturadas de possíveis interações entre usuários e o sistema, com o objetivo de capturar comportamentos esperados, identificar requisitos e apoiar a validação das funcionalidades. Cada cenário contém informações sobre os atores envolvidos, o contexto da interação, pré-condições, fluxo principal de ações, pós-condições e exceções possíveis.

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

<center>
    Autor(es): 
    <a href="https://github.com/RA-Salles" target="_blank">Júlia Gabriela</a>
</center>

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

<center>
    Autor(es): 
    <a href="https://github.com/RA-Salles" target="_blank">Júlia Gabriela</a>
</center>

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

<center>
    Autor(es): 
    <a href="https://github.com/RA-Salles" target="_blank">Júlia Gabriela</a>
</center>

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

<center>
    Autor(es): 
    <a href="https://github.com/johnaopedro" target="_blank">Ryan Salles</a>
</center>

**Cenário 5: Verificar postos de atendimento**

**Nome do Cenário:** Verificar postos de atendimento
**Ator principal:**  Usuário com ou sem autenticação 
**Ator Secundário:** Sistema CadÚnico, Aplicativo CadÚnico. 
**Contexto:** O usuário gostaria de verificar o local e horário de postos de atendimento para poder ser atendido pessoalmente.
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

<center>
    Autor(es): 
    <a href="https://github.com/johnaopedro" target="_blank">Ryan Salles</a>
</center>

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

<center>
    Autor(es): 
    <a href="https://github.com/RA-Salles" target="_blank">Júlia Gabriela</a>
</center>

**Cenário 7: Filtrar Benefícios Sociais**

**Nome do Cenário:** Filtrar informações sobre benefícios sociais  
**Ator principal:** Usuário (autenticado ou não)  
**Ator Secundário:** Sistema CadÚnico, Aplicativo CadÚnico  
**Contexto:** O usuário deseja visualizar apenas os benefícios sociais que sejam relevantes ao seu perfil ou interesse, utilizando filtros para facilitar a busca.  
**Pré-condições:** Um celular smartphone ou computador funcional compatível com o aplicativo com acesso à internet.  

**Fluxo principal:**  
1. O usuário abre o aplicativo.  
2. O usuário acessa a seção “Benefícios Disponíveis”.  
3. O sistema apresenta a lista completa de benefícios.  
4. O usuário seleciona filtros como: tipo de benefício, público-alvo, localização, faixa de renda, entre outros.  
5. O sistema processa os filtros aplicados.  
6. O sistema exibe os benefícios que correspondem aos critérios selecionados.  
7. O usuário visualiza os detalhes dos benefícios listados.  

**Pós-condições:** O usuário acessa apenas os benefícios que correspondem aos filtros aplicados.  
**Exceções:**  
1. Nenhum benefício corresponde aos filtros utilizados.  
2. Campos de filtro mal preenchidos ou inválidos.  
3. Falha de conexão impede a exibição dos resultados.

<center>
    Autor(es): 
    <a href="https://github.com/RA-Salles" target="_blank">Júlia Gabriela</a>

</center>

**Cenário 8: Chatbot**

**Nome do Cenário:** Uso de chatbot "Assistente Virtual" para auxílio e resolução de dúvidas  
**Ator principal:** Usuário Cadastrado com dúvidas
**Ator Secundário:** Sistema de chatbot hipotético Assistente Virtual, Aplicativo CadÚnico,   
**Contexto:** Um usuário possui alguma duvida relacionada a realização de uma operação ou benefício.  
**Pré-condições:** Um celular smartphone ou computador funcional compatível com o aplicativo com acesso à internet.  

**Fluxo principal:**  
1. O usuário abre o aplicativo.  
2. O usuário aperta no botão de login.
3. O usuário é autenticado pelo Gov.br.
4. O usuário acessa a opção "conversar com o assistente virtual".
5. O usuário é movido à tela de interface do assistente virtual. 
6. O usuário realiza uma pergunta relacionada a benefícios ou operações no aplicativo. 
7. O sistema virtual responde a dúvida.  

**Pós-condições:** O usuário tem sua dúvida sanada.   
**Exceções:**  
1. Usuário não está cadastrado e falha na parte de autenticação.
2. Usuário não possui conexão com a internet em seu aparelho.
3. O Assistente Virtual não possui a informação necessária, frustrando a tentativa de uso.
4. O Assistente Virtual está em manutenção, frustrando a tentativa de uso. 

<center>
    Autor(es): 
    <a href="https://github.com/johnaopedro" target="_blank">Ryan Salles</a>
</center>

**Cenário 9: Modo Escuro**

**Nome do Cenário:** Modo Escuro
**Ator principal:** Usuário.
**Ator Secundário:** Aplicativo CadÚnico,   
**Contexto:** Um usuário está tentando utilizar o aplicativo em um ambiente de baixa luminosidade e a interface padrão é muito clara.  
**Pré-condições:** Um celular smartphone ou computador funcional compatível com o aplicativo com acesso à internet.  

**Fluxo principal:**  
1. O usuário abre o aplicativo.
2. O usuário se incomoda com a luminosidade.
3. O usuário aperta em um botão descrito como "Modo Escuro". 
4. O aplicativo atualiza a interface para utilizar cores mais frias.

**Pós-condições:** O usuário se sente mais confortável com o esquema de cores redefinido.   
**Exceções:**  
1. O esquema de cores redefinido torna o usuário mais desconfortável no momento. 
2. O usuário não consegue encontrar o botão "Modo Escuro".

<center>
    Autor(es): 
    <a href="https://github.com/johnaopedro" target="_blank">Ryan Salles</a>
</center>

## Vídeo
O vídeo abaixo refere-se ao cenário, descrito neste artefato, realizada no **Microsoft Teams**:

<iframe width="560" height="315" src="https://www.youtube.com/embed/DohE9Bf-ppg?si=w5koy8vx1bkrT6M8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Referências
CARLOS EDUARDO VAZQUEZ; GUILHERME SIQUEIRA SIMÕES. Engenharia de Requisitos. [s.l.] Brasport, 2016.

<div style="text-align: left;">
    <img src="../../assets/referencias/cenarios/referencia_cenarios.jpeg" alt="Cenários">
</div>


## Histórico de Versão
| Versão |    Data    |    Descrição     |         Autor         |       Revisor      |
| :----: | :--------: | :--------------: | :-------------------: | :----------------: |
|  1.0   | 08/05/2025 | Criando a pagina e adicionando a introdução de cada tema | [Ryan Salles](https://github.com/RA-Salles), [Julia Gabriela](https://github.com/JuliaGabP) | [João Pedro](https://github.com/johnaopedro) |
|  1.1   | 12/05/2025 | Criação de cenários e referências        | [Julia Gabriela](https://github.com/JuliaGabP) | [João Pedro](https://github.com/johnaopedro) |
|  1.2   | 12/05/2025 | Inserindo vídeo e atualizando formatação | [Julia Gabriela](https://github.com/JuliaGabP) | [João Pedro](https://github.com/johnaopedro) |
|  1.3   | 12/05/2025 | Inserindo 2 novos cenários.              | [Ryan Salles](https://github.com/RA-Salles)    | [João Pedro](https://github.com/johnaopedro) |
|  1.4   | 13/05/2025 | Inserindo 2 novos cenários.              | [Julia Gabriela](https://github.com/JuliaGabP) | [João Pedro](https://github.com/johnaopedro) |
|  1.5   | 13/05/2025 | Adicionando introdução                   | [Julia Gabriela](https://github.com/JuliaGabP) | [João Pedro](https://github.com/johnaopedro) |
|  1.6   | 13/05/2025 | Inserindo 2 novos cenários.              | [Ryan Salles](https://github.com/RA-Salles)    | [João Pedro](https://github.com/johnaopedro) |
|  1.7   | 14/05/2025 | Adição de autores a cada cenário         | [Ryan Salles](https://github.com/RA-Salles)    | [João Pedro](https://github.com/johnaopedro) |
