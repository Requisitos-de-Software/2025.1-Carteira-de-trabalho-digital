# Léxico

## Introdução

O principal objetivo do léxico, a ser executado pelos Engenheiros de requisitos, é a identificação de palavras ou frases peculiares ao meio social da aplicação sob estudo. Cada símbolo é descrito com noção, significado do símbolo, e impacto, descrição do efeito/uso/ocorrência do símbolo na aplicação.

## Modelo de Tabela de Léxicos

<center> 
    <b>Tabela 1:</b> Modelo de Tabela 
</center>  

| Léxico |  Classificação | Sinônimos | Noção | Impacto |
|:----------:|:-----------:|:----------:|:----------:|---------|
| Nome do Léxico | Verbo/Objeto/Estado | Palavras ou expressções com sentido parecido | Quem é o sujeito? | Quais ações executa ou sofre|

<center>
    Autor(es): 
    <a href="https://github.com/Gabrielfcoelho" target="_blank">Gabriel Flores</a>, 
    <a href="https://github.com/JoaoPC10" target="_blank">João Igor</a>
</center>

## Tabela de Léxicos

<center> 
    <b>Tabela 2:</b> Tabela de Léxicos 
</center>

| Léxico |  Classificação | Sinônimos | Noção | Impacto |
|:----------:|:-----------:|:----------:|:----------:|-------|
| Cadastrar Família | Verbo | Registrar família, inserir família | Ação de incluir uma nova família no Cadastro Único, informando dados pessoais, endereço, composição familiar e renda. | Permite que a família seja avaliada para inclusão em programas sociais. |
| Atualizar Cadastro | Verbo | Modificar dados, Revisar informações | Alteração dos dados de uma família já cadastrada, geralmente por mudanças na renda, endereço ou composição familiar. | Mantém o cadastro vigente e evita suspensão de benefícios. |
| Consultar Cadastro | Verbo | Visualizar cadastro, Ver dados. | Ação de visualizar as informações de um cadastro já existente. Pode ser feita por operadores ou pelo próprio responsável familiar. | Facilita o acompanhamento e validação dos dados registrados. |
| Emitir Comprovante | Verbo | Gerar comprovante, Baixar documento | Geração de um documento que comprova o registro ou a atualização no Cadastro Único. | Permite ao cidadão comprovar situação cadastral perante órgãos públicos. |
| Validar Informações | Verbo | Verificar dados, Confirmar cadastro | Confirmação da veracidade dos dados informados por famílias. | Impede fraudes e garante qualidade nas decisões sobre benefícios. |
| Realizar Entrevista | Verbo | Coletar informações, Aplicar questionário | Atividade conduzida por entrevistador social para coletar dados das famílias. | Essencial para preenchimento correto do cadastro. |
| Agendar Atendimento | Verbo |  Marcar atendimento, Definir horário | Reserva de data e hora para que a família compareça ao CRAS. | Organiza o fluxo de cadastramentos, evitando sobrecarga. |
| Família | Objeto | Unidade familiar | Conjunto de pessoas que residem sob o mesmo teto e compartilham renda. | Unidade principal de análise e cadastro. |
| Pessoa | Objeto | Membro familiar | Indivíduo que compõe uma família registrada. | Seus dados alimentam o sistema e definem o perfil da família. |
| Responsável Familiar | Objeto | Representante familiar | Pessoa que representa o grupo familiar perante o Cadastro Único | Seu NIS referencia todo o cadastro familiar. |
| Número de Identificação Social(NIS) | Objeto | Código de identificação | Código único que identifica cada pessoa cadastrada. | Usado em diversos sistemas para concessão de benefícios. |
| Cadastro | Objeto | Registro | Conjunto de informações organizadas sobre famílias e pessoas. |  Elemento fundamental para a gestão de políticas sociais. |
| Programa Social | Objeto | Benefício Social | Políticas de transferência de renda ou assistência baseadas no Cadastro Único. | O cadastro determina a elegibilidade. |
| Centro de Referência de Assistência Social(CRAS) | Objeto | Unidade de atendimento | Local onde ocorrem os atendimentos para cadastramento e atualização de dados. | Ponto de entrada do cidadão no sistema. |
| Entrevistador Social | Objeto | Agente social | Profissional que conduz as entrevistas e insere os dados no sistema. |  Responsável direto pela qualidade dos dados inseridos. |
| Documentos Pessoais | Objeto | Identificação | Documentos necessários para comprovação dos dados informados no cadastro. | Sem eles, o cadastro pode ser considerado inválido ou incompleto. |
| Cadastro Ativo | Estado |  Cadastro Válido |  Situação do cadastro que está atualizado e dentro do prazo exigido. | Permite recebimento de benefícios sem restrições. |
| Cadastro Inativo | Estado | Cadastro vencido | Cadastro fora do prazo de validade, exigindo atualização. | Pode bloquear o acesso a programas sociais. |
| Família Elegível | Estado | Apta ao benefício |  Família que atende aos critérios de um ou mais programas sociais. | Pode receber os benefícios previstos. |
| Família Inelegível | Estado | Não apta ao benefício | Família que não atende aos critérios exigidos. | Não pode receber os benefícios. |
| Cadastro Pendente | Estado | Cadastro incompleto | Cadastro em processo de validação ou com dados faltantes. | Cadastro em processo de validação ou com dados faltantes. |

<center>
    Autor(es): 
    <a href="https://github.com/Gabrielfcoelho" target="_blank">Gabriel Flores</a>, 
    <a href="https://github.com/JoaoPC10" target="_blank">João Igor</a>
</center>

## Referências

> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 10. Gama: Universidade de Brasília (UnB). Slide de apresentação. Acesso em: 8 maio 2025.

<div align = "center">
<img src="../../docs/assets/referencias/modelagem/RefLex.png" width="400"/>
<br>
<img src="../../docs/assets/referencias/modelagem/RefTabLex.png" width="400"/>
</div>


## Histórico de Versões

| Versão | Data | Descrição  | Autor        | Revisor |
| :-----: | :----: | :----------: | :------------: | :--------: |
| 1.0    | 07/05/2025 | Criação da página de análise das técnicas de modelagem  | [João Igor](https://github.com/JoaoPC10) e [Gabriel Flores](https://github.com/Gabrielfcoelho) | [Ryan Salles](https://github.com/RA-Salles) |
| 1.1    | 08/05/2025 | Adição das Informações | [João Igor](https://github.com/JoaoPC10) e  [Gabriel Flores](https://github.com/Gabrielfcoelho) | [Ryan Salles](https://github.com/RA-Salles) |
| 1.2 | 09/05/2025 | Criação da tabela de léxicos | [Gabriel Flores](https://github.com/Gabrielfcoelho) e [João Igor](https://github.com/JoaoPC10) |  [Ryan Salles](https://github.com/RA-Salles) |