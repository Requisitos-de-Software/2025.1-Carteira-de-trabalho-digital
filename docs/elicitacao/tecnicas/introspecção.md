# Introspecção

## Introdução

### Introspecção
A introspecção é uma abordagem utilizada na elicitação de requisitos que busca definir características essenciais de um sistema a partir de uma reflexão aprofundada sobre seu uso ideal. Por meio desse processo, o responsável pela análise imagina cenários hipotéticos nos quais determinadas tarefas seriam executadas, identificando assim os elementos indispensáveis para o funcionamento do software. No entanto, essa técnica apresenta desafios, pois a perspectiva dos especialistas pode não corresponder totalmente às necessidades e experiências dos usuários reais, especialmente no contexto do design de interfaces e da adoção de novas tecnologias.

### Desafios para Especialistas
Designers de interface, cientistas cognitivos e engenheiros de requisitos frequentemente enfrentam dificuldades ao compreender como os usuários aprendem novas tecnologias. Muitas vezes, especialistas ficam surpresos com o comportamento inconsistente dos usuários e têm dificuldade em entender o ambiente de trabalho e as condições para a adoção de novas tecnologias. A confusão em torno do termo "usuário ingênuo" também contribui para essa problemática. Conclui-se que a introspecção, sem considerar cuidadosamente o contexto, torna-se inviável.

## Metodologia

O processo de introspecção foi realizado individualmente pelos alunos **João Pedro** e **Julia Paulino**. Cada um se colocou na posição de usuário do aplicativo **Cadastro Único**, imaginando funcionalidades essenciais e desejáveis. Os requisitos elicitados por Julia Paulino estão descritos a seguir.

### Cronograma

| Nome          | Data       | Hora  |
|---------------|------------|-------|
| João Pedro    | 23/04/2025 | 12:30 |
| Julia Paulino | 23/04/2025 | 14:00 |

Fonte: João Pedro e Julia Paulino.

---

## João Pedro

João Pedro realizou a introspecção se colocando na posição de um usuário do aplicativo Cadastro Único. A partir dessa simulação, foram elicitados requisitos. Abaixo estão as tabelas 1 e 2, que apresentam os requisitos funcionais e não funcionais, respectivamente.

Legenda - Tabela 1:
 
- RFx: Requisitos Funcionais nºx.

<center><b>Tabela 1:</b> Requisitos Funcionais</center>
| RF    | Nome do RF                                | Descrição                                                                 |
|-------|-------------------------------------------|---------------------------------------------------------------------------|
| RF01  | Cadastro de Usuário                       | O sistema deve permitir o cadastro de novos usuários, coletando informações pessoais como nome, CPF, endereço, e outros dados necessários. |
| RF02  | Atualização de Dados                      | O sistema deve possibilitar ao usuário atualizar seus dados cadastrais a qualquer momento. |
| RF03  | Consultar Situação Cadastral              | O sistema deve permitir que o usuário consulte o status de seu cadastro e a situação atual do benefício. |
| RF04  | Emissão de Comprovante de Cadastro        | O sistema deve possibilitar que o usuário gere e imprima um comprovante de cadastro atualizado. |
| RF05  | Filtragem de Benefícios                   | O sistema deve permitir ao usuário visualizar os benefícios aos quais ele pode ter direito com base nos dados cadastrados. |
<center>
    Autor(es): <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a>
</center>

Legenda - Tabela 2:

- RNFx: Requisitos Não-Funcionais nºx.

<center><b>Tabela 2:</b> Requisitos Não Funcionais</center>
| RNF   | Nome do RNF                              | Descrição                                                                 |
|-------|------------------------------------------|---------------------------------------------------------------------------|
| RNF01 | Usabilidade                              | O aplicativo deve ser de fácil navegação, intuitivo, e acessível para todos os usuários, incluindo pessoas com deficiência. |
| RNF02 | Segurança                                | O sistema deve garantir a segurança dos dados pessoais dos usuários, utilizando criptografia e práticas de segurança adequadas. |
| RNF03 | Performance                              | O sistema deve ser capaz de processar as informações de cadastro e consultas rapidamente, com tempo de resposta inferior a 3 segundos. |
| RNF04 | Compatibilidade com Dispositivos         | O aplicativo deve ser compatível com as principais plataformas móveis (Android e iOS). |
| RNF05 | Disponibilidade                          | O sistema deve garantir 99% de disponibilidade para os usuários, com tempo de inatividade mínimo. |
<center>
    Autor(es): <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a>
</center>


## Julia Paulino

Julia Paulino realizou a introspecção se colocando na posição de uma usuária do aplicativo Cadastro Único. A partir dessa simulação, foram elicitados requisitos divididos entre **já existentes no aplicativo** e **ainda não existentes (desejáveis)**. Abaixo estão as tabelas 3 e 4, que apresentam os requisitos funcionais e não funcionais, respectivamente.

Legenda - Tabela 3:
 
- RFx: Requisitos Funcionais nºx.

<center><b>Tabela 3:</b> Requisitos Funcionais</center>

| RF    | Nome do RF                          | Descrição                                                                 |
|-------|--------------------------------------|---------------------------------------------------------------------------|
| RF01  | Consultar dados cadastrais          | Permite ao usuário visualizar seus dados no Cadastro Único.              |
| RF02  | Pré-cadastrar família               | Possibilita iniciar um pré-cadastro para uma nova unidade familiar.      |
| RF03  | Localizar postos de atendimento     | Mostra os CRAS mais próximos com base na localização do usuário.         |
| RF04  | Enviar notificações                 | Permite o envio de mensagens importantes ao usuário por meio do app.     |
| RF05  | Integrar com o CNIS                 | Traz dados de vínculos e contribuições automaticamente do CNIS.          |
<center>
    Autor(es): <a href="https://github.com/JuliaGabP" target="_blank">Julia Gabriela</a>
</center>

Legenda - Tabela 4:

- RNFx: Requisitos Não-Funcionais nºx.

<center><b>Tabela 4:</b> Requisitos Não Funcionais</center>

| RNF   | Nome do RNF                              | Descrição                                                                 |
|-------|------------------------------------------|---------------------------------------------------------------------------|
| RNF01 | Interface intuitiva e amigável           | O design do aplicativo é simples e fácil de navegar para o usuário.       |
| RNF02 | Capacidade de atender grande base de usuários | O aplicativo suporta muitos usuários acessando simultaneamente.           |
| RNF03 | Integração com sistemas oficiais do governo | O aplicativo está integrado com sistemas oficiais, como o CNIS.           |
<center>
    Autor(es): <a href="https://github.com/JuliaGabP" target="_blank">Julia Gabriela</a>
</center>

## Requisitos Elicitados (Finais)
Abaixo estão os requisitos finais, que foram elicitados a partir da introspecção realizada por João Pedro e Julia Paulino. Os requisitos foram unificados, removendo os requisitos desejáveis e mantendo apenas os já existentes no aplicativo. Abaixo estão as tabelas 5 e 6, que apresentam os requisitos funcionais e não funcionais, respectivamente.


Legenda - Tabela 5:
 
- RFx: Requisitos Funcionais nºx.

<center><b>Tabela 5:</b> Requisitos Funcionais</center>
| RF    | Nome do RF                          | Descrição                                                                 |
|-------|--------------------------------------|---------------------------------------------------------------------------|
| RF01  | Consultar dados cadastrais          | Permite ao usuário visualizar seus dados no Cadastro Único.              |
| RF02  | Pré-cadastrar família               | Possibilita iniciar um pré-cadastro para uma nova unidade familiar.      |
| RF03  | Localizar postos de atendimento     | Mostra os CRAS mais próximos com base na localização do usuário.         |
| RF04  | Enviar notificações                 | Permite o envio de mensagens importantes ao usuário por meio do app.     |
| RF05  | Integrar com o CNIS                 | Traz dados de vínculos e contribuições automaticamente do CNIS.          |
| RF06  | Cadastro de Usuário                 | O sistema deve permitir o cadastro de novos usuários, coletando informações pessoais. |
| RF07  | Atualização de Dados                | O sistema deve possibilitar ao usuário atualizar seus dados cadastrais.  |
| RF08  | Consultar Situação Cadastral        | Permite verificar o status do cadastro e da situação dos benefícios.     |
| RF09  | Emissão de Comprovante de Cadastro  | Gera um comprovante de cadastro atualizado para o usuário.               |
| RF10  | Filtragem de Benefícios             | Permite visualizar benefícios disponíveis com base nos dados cadastrados.|
<center>
    Autor(es): <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a>, <a href="https://github.com/JuliaGabP" target="_blank">Julia Gabriela</a>
</center>

---
Legenda - Tabela 6:

- RNFx: Requisitos Não-Funcionais nºx.

<center><b>Tabela 6:</b> Requisitos Não Funcionais</center>

| RNF   | Nome do RNF                              | Descrição                                                                 |
|-------|------------------------------------------|---------------------------------------------------------------------------|
| RNF01 | Interface intuitiva e amigável           | O design do aplicativo é simples e de fácil navegação.                    |
| RNF02 | Capacidade de atender grande base de usuários | Suporta um grande número de acessos simultâneos.                          |
| RNF03 | Integração com sistemas oficiais do governo | Integrado com sistemas como o CNIS.                                      |
| RNF04 | Usabilidade                              | Navegação intuitiva e acessibilidade geral.                              |
| RNF05 | Segurança                                | Uso de criptografia e proteção de dados sensíveis.                       |
| RNF06 | Performance                              | Resposta rápida nas interações do usuário (até 3 segundos).              |
| RNF07 | Compatibilidade com Dispositivos         | Compatível com Android e iOS.                                            |
| RNF08 | Disponibilidade                          | Garantia de 99% de disponibilidade com mínimas interrupções.             |
<center>
    Autor(es): <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a>, <a href="https://github.com/JuliaGabP" target="_blank">Julia Gabriela</a>
</center>

---


## Conclusão

Os requisitos elicitados por essa técnica podem divergir dos demais, tendo em vista que é uma técnica aplicada por participantes do projeto, de maneira subjetiva e com base em percepções individuais.

---

## Referências

> GOGUEN, Joseph A.; LINDE, Charlotte. Techniques for Requirements Elicitation. In: IEEE International Symposium on Requirements Engineering, 1993. p. 152-164. Acesso em: 23/04/2025.

##### Imagem 1: Introspecção

<div style="text-align: center;">
    <img src="../../../assets/referencias_no_texto/introspeccao1.png" alt="Introspecção">
</div>

**Fonte:** Adaptado de GOGUEN, Joseph A.; LINDE, Charlotte. *Techniques for requirements elicitation*. In: IEEE INTERNATIONAL SYMPOSIUM ON REQUIREMENTS ENGINEERING, 1993. p. 152–164.

##### Imagem 2: Introspecção

<div style="text-align: center;">
    <img src="../../../assets/referencias_no_texto/introspeccao2.png" alt="Introspecção">
</div>

**Fonte:** Adaptado de GOGUEN, Joseph A.; LINDE, Charlotte. *Techniques for requirements elicitation*. In: IEEE INTERNATIONAL SYMPOSIUM ON REQUIREMENTS ENGINEERING, 1993. p. 152–164.

## Histórico de Versões

| Versão | Data | Descrição  | Autor        | Revisor |
| :-----: | :----: | :----------: | :------------: | :--------: |
| 1.0    | 23/04/2025 | Introdução e requisitos iniciais | [João Pedro Costa](https://github.com/johnaopedro) [Julia Gabriela](https://github.com/JuliaGabP)                   | [Ryan Salles](https://github.com/RA-Salles)                      |
| 1.1    | 03/05/2025 | Correções de ortográfia | [João Pedro Costa](https://github.com/johnaopedro)                   | [Ryan Salles](https://github.com/RA-Salles)                      |
| 1.2    | 04/05/2025 | Removendo requisitos desejáveis | [João Pedro Costa](https://github.com/johnaopedro)                   | [Ryan Salles](https://github.com/RA-Salles)                      |
| 1.3 | 04/05/2025 | Adicionando links e corrigindo tabelas | [João Pedro Costa](https://github.com/johnaopedro)                   | [Ryan Salles](https://github.com/RA-Salles)                      |
| 1.4 | 06/05/2025 | Adicionando imagens e referências | [João Pedro Costa](https://github.com/johnaopedro)                   | [Ryan Salles](https://github.com/RA-Salles)                      |