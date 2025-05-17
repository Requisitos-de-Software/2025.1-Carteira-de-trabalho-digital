# Léxico

## Introdução

O principal objetivo do léxico, a ser executado pelos Engenheiros de requisitos, é a identificação de palavras ou frases peculiares ao meio social da aplicação sob estudo. Cada símbolo é descrito com noção, significado do símbolo, e impacto, descrição do efeito/uso/ocorrência do símbolo na aplicação.

## Modelo de Tabela de Léxicos

<center> 
    <b>Tabela 1:</b> Modelo de Tabela 
</center>  

| Léxico |  Classificação | Sinônimos | Noção | Impacto |
|:----------:|:-----------:|:----------:|:----------:|:-------:|
| Nome do Léxico | Verbo/Objeto/Estado | Palavras ou expressões com sentido parecido | Quem é o sujeito? | Quais ações executa ou sofre|

<center>
    Autor(es): 
    <a href="https://github.com/Gabrielfcoelho" target="_blank">Gabriel Flores</a>, 
    <a href="https://github.com/JoaoPC10" target="_blank">João Igor</a>
</center>

## Tabela de Léxicos Adições por Gabriel Flores e João Igor

| Léxico |  Classificação | Sinônimos | Noção | Impacto |
|:----------:|:-----------:|:----------:|:----------:|-------|
| [Cadastrar Família](#cadastrar-família) | Verbo | [Registrar família](#cadastrar-família), [inserir família](#cadastrar-família) | Ação de incluir uma nova [família](#família) no [Cadastro](#cadastro) Único, informando dados pessoais, endereço, composição [familiar](#família) e renda. | Permite que a [família](#família) seja avaliada para inclusão em [programas sociais](#programa-social). |
| [Atualizar Cadastro](#atualizar-cadastro) | Verbo | [Modificar dados](#atualizar-cadastro), [Revisar informações](#atualizar-cadastro) | Alteração dos dados de uma [família](#família) já cadastrada, geralmente por mudanças na renda, endereço ou composição [familiar](#família). | Mantém o [cadastro](#cadastro) vigente e evita suspensão de benefícios. |
| [Consultar Cadastro](#consultar-cadastro) | Verbo | [Visualizar cadastro](#consultar-cadastro), [Ver dados](#consultar-cadastro) | Ação de visualizar as informações de um [cadastro](#cadastro) já existente. Pode ser feita por operadores ou pelo próprio [responsável familiar](#responsável-familiar). | Facilita o acompanhamento e validação dos dados registrados. |
| [Emitir Comprovante](#emitir-comprovante) | Verbo | [Gerar comprovante](#emitir-comprovante), [Baixar documento](#emitir-comprovante) | Geração de um [documento](#documentos-pessoais) que comprova o registro ou a atualização no [Cadastro Único](#cadastro). | Permite ao cidadão comprovar situação cadastral perante órgãos públicos. |
| [Validar Informações](#validar-informações) | Verbo | [Verificar dados](#validar-informações), [Confirmar cadastro](#validar-informações) | Confirmação da veracidade dos dados informados por [famílias](#família). | Impede fraudes e garante qualidade nas decisões sobre benefícios. |
| [Realizar Entrevista](#realizar-entrevista) | Verbo | [Coletar informações](#realizar-entrevista), [Aplicar questionário](#realizar-entrevista) | Atividade conduzida por [entrevistador social](#entrevistador-social) para coletar dados das [famílias](#família). | Essencial para preenchimento correto do [cadastro](#cadastro). |
| [Agendar Atendimento](#agendar-atendimento) | Verbo | [Marcar atendimento](#agendar-atendimento), [Definir horário](#agendar-atendimento) | Reserva de data e hora para que a [família](#família) compareça ao [CRAS](#centro-de-referência-de-assistência-socialcras). | Organiza o fluxo de cadastramentos, evitando sobrecarga. |
| [Família](#família) | Objeto | [Unidade familiar](#família) | Conjunto de pessoas que residem sob o mesmo teto e compartilham renda. | Unidade principal de análise e [cadastro](#cadastro). |
| [Pessoa](#pessoa) | Objeto | [Membro familiar](#pessoa) | Indivíduo que compõe uma [família](#família) registrada. | Seus dados alimentam o sistema e definem o perfil da [família](#família). |
| [Responsável Familiar](#responsável-familiar) | Objeto | [Representante familiar](#responsável-familiar) | Pessoa que representa o grupo [familiar](#família) perante o [Cadastro Único](#cadastro) | Seu [NIS](#número-de-identificação-socialnis) referencia todo o [cadastro](#cadastro) [familiar](#família). |
| [Número de Identificação Social(NIS)](#número-de-identificação-socialnis) | Objeto | [Código de identificação](#número-de-identificação-socialnis) | Código único que identifica cada [pessoa](#pessoa) cadastrada. | Usado em diversos sistemas para concessão de benefícios. |
| [Cadastro](#cadastro) | Objeto | [Registro](#cadastro) | Conjunto de informações organizadas sobre [famílias](#família) e [pessoas](#pessoa). | Elemento fundamental para a gestão de políticas sociais. |
| [Programa Social](#programa-social) | Objeto | [Benefício Social](#programa-social) | Políticas de transferência de renda ou assistência baseadas no [Cadastro Único](#cadastro). | O [cadastro](#cadastro) determina a elegibilidade. |
| [Centro de Referência de Assistência Social(CRAS)](#centro-de-referência-de-assistência-socialcras) | Objeto | [Unidade de atendimento](#centro-de-referência-de-assistência-socialcras) | Local onde ocorrem os atendimentos para cadastramento e atualização de dados. | Ponto de entrada do cidadão no sistema. |
| [Entrevistador Social](#entrevistador-social) | Objeto | [Agente social](#entrevistador-social) | Profissional que conduz as [entrevistas](#realizar-entrevista) e insere os dados no sistema. | Responsável direto pela qualidade dos dados inseridos. |
| [Documentos Pessoais](#documentos-pessoais) | Objeto | [Identificação](#documentos-pessoais) | Documentos necessários para comprovação dos dados informados no [cadastro](#cadastro). | Sem eles, o [cadastro](#cadastro) pode ser considerado inválido ou incompleto. |
| [Cadastro Ativo](#cadastro-ativo) | Estado | [Cadastro Válido](#cadastro-ativo) | Situação do [cadastro](#cadastro) que está atualizado e dentro do prazo exigido. | Permite recebimento de benefícios sem restrições. |
| [Cadastro Inativo](#cadastro-inativo) | Estado | [Cadastro vencido](#cadastro-inativo) | [Cadastro](#cadastro) fora do prazo de validade, exigindo atualização. | Pode bloquear o acesso a [programas sociais](#programa-social). |
| [Família Elegível](#família-elegível) | Estado | [Apta ao benefício](#família-elegível) | [Família](#família) que atende aos critérios de um ou mais [programas sociais](#programa-social). | Pode receber os benefícios previstos. |
| [Família Inelegível](#família-inelegível) | Estado | [Não apta ao benefício](#família-inelegível) | [Família](#família) que não atende aos critérios exigidos. | Não pode receber os benefícios. |
| [Cadastro Pendente](#cadastro-pendente) | Estado | [Cadastro incompleto](#cadastro-pendente) | [Cadastro](#cadastro) em processo de validação ou com dados faltantes. |  Pode atrasar a concessão de benefícios. |

<center>
    Autor(es): 
    <a href="https://github.com/Gabrielfcoelho" target="_blank">Gabriel Flores</a>, 
    <a href="https://github.com/JoaoPC10" target="_blank">João Igor</a>
</center>

## Tabela de Léxicos – Adições por João Pedro Costa

| Léxico | Classificação | Sinônimos | Noção | Impacto |
|:------:|:-------------:|:---------:|:-----:|:-------:|
| [Acessar Aplicativo](#acessar-aplicativo) | Verbo | [Entrar no app](#acessar-aplicativo), [Logar no sistema](#acessar-aplicativo) | Ação do usuário de abrir o aplicativo do [Cadastro Único](#cadastro) em seu dispositivo móvel, por meio de autenticação via senha ou biometria. | Permite ao cidadão visualizar, acompanhar ou modificar dados, facilitando o acesso remoto aos serviços sociais. |
| [Receber Notificação](#receber-notificação) | Verbo | [Ser avisado](#receber-notificação), [Receber alerta](#receber-notificação) | Recurso do aplicativo que envia mensagens automáticas ao usuário sobre prazos, atualizações de status do [cadastro](#cadastro) ou convocações para [entrevista](#realizar-entrevista). | Mantém o cidadão informado, reduzindo ausências e melhorando o cumprimento de exigências do sistema. |
| [Anexar Documentos](#anexar-documentos) | Verbo | [Enviar arquivos](#anexar-documentos), [Fazer upload de documentos](#anexar-documentos) | Ação do usuário de carregar fotos ou arquivos digitais de [documentos pessoais](#documentos-pessoais) diretamente pelo aplicativo. | Permite completar ou atualizar o [cadastro](#cadastro) sem necessidade de comparecer presencialmente ao CRAS, tornando o processo mais acessível e ágil. |


<center>
    Autor(es): <a href="https://github.com/johnaopedro" target="_blank">João Pedro Costa</a> <br>
</center> 

## Referências

> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 10. Gama: Universidade de Brasília (UnB). Slide de apresentação. Acesso em: 8 maio 2025.

<div align = "center">
<img src="../../assets/referencias/modelagem/RefLex.png" width="400"/>
<br>
<img src="../../assets/referencias/modelagem/RefTabLex.png" width="400"/>
</div>


## Histórico de Versões

| Versão | Data | Descrição  | Autor        | Revisor |
| :-----: | :----: | :----------: | :------------: | :--------: |
| 1.0    | 07/05/2025 | Criação da página de análise das técnicas de modelagem  | [João Igor](https://github.com/JoaoPC10) e [Gabriel Flores](https://github.com/Gabrielfcoelho) | [Ryan Salles](https://github.com/RA-Salles) |
| 1.1    | 08/05/2025 | Adição das Informações | [João Igor](https://github.com/JoaoPC10) e  [Gabriel Flores](https://github.com/Gabrielfcoelho) | [Ryan Salles](https://github.com/RA-Salles) |
| 1.2 | 09/05/2025 | Criação da tabela de léxicos | [Gabriel Flores](https://github.com/Gabrielfcoelho) e [João Igor](https://github.com/JoaoPC10) |  [Ryan Salles](https://github.com/RA-Salles) |
| 1.3 | 14/05/2025 | Criação de hiper links na tabela de léxicos | [Gabriel Flores](https://github.com/Gabrielfcoelho) |  [Ryan Salles](https://github.com/RA-Salles) |
| 1.4 | 16/05/2025 | Criação de outros lexicos relacionados ao conteúdo | [João Pedro Costa](https://github.com/johnaopedro) |  [Ryan Salles](https://github.com/RA-Salles) |
| 1.5 | 16/05/2025 | Corrigindo imagens | [João Pedro Costa](https://github.com/johnaopedro) |  [Ryan Salles](https://github.com/RA-Salles) |