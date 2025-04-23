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

João Pedro realizou a introspecção se colocando na posição de um usuário do aplicativo Cadastro Único. A partir dessa simulação, foram elicitados requisitos.


### Requisitos Funcionais
| RF    | Nome do RF                                | Descrição                                                                 |
|-------|-------------------------------------------|---------------------------------------------------------------------------|
| RF01  | Cadastro de Usuário                       | O sistema deve permitir o cadastro de novos usuários, coletando informações pessoais como nome, CPF, endereço, e outros dados necessários. |
| RF02  | Atualização de Dados                      | O sistema deve possibilitar ao usuário atualizar seus dados cadastrais a qualquer momento. |
| RF03  | Consultar Situação Cadastral              | O sistema deve permitir que o usuário consulte o status de seu cadastro e a situação atual do benefício. |
| RF04  | Emissão de Comprovante de Cadastro        | O sistema deve possibilitar que o usuário gere e imprima um comprovante de cadastro atualizado. |
| RF05  | Filtragem de Benefícios                   | O sistema deve permitir ao usuário visualizar os benefícios aos quais ele pode ter direito com base nos dados cadastrados. |

### Requisitos não-funcionais
| RNF   | Nome do RNF                              | Descrição                                                                 |
|-------|------------------------------------------|---------------------------------------------------------------------------|
| RNF01 | Usabilidade                              | O aplicativo deve ser de fácil navegação, intuitivo, e acessível para todos os usuários, incluindo pessoas com deficiência. |
| RNF02 | Segurança                                | O sistema deve garantir a segurança dos dados pessoais dos usuários, utilizando criptografia e práticas de segurança adequadas. |
| RNF03 | Performance                              | O sistema deve ser capaz de processar as informações de cadastro e consultas rapidamente, com tempo de resposta inferior a 3 segundos. |
| RNF04 | Compatibilidade com Dispositivos         | O aplicativo deve ser compatível com as principais plataformas móveis (Android e iOS). |
| RNF05 | Disponibilidade                          | O sistema deve garantir 99% de disponibilidade para os usuários, com tempo de inatividade mínimo. |


## Julia Paulino

Julia Paulino realizou a introspecção se colocando na posição de uma usuária do aplicativo Cadastro Único. A partir dessa simulação, foram elicitados requisitos divididos entre **já existentes no aplicativo** e **ainda não existentes (desejáveis)**.

### Requisitos Funcionais

#### Já Existentes

| RF    | Nome do RF                          | Descrição                                                                 |
|-------|--------------------------------------|---------------------------------------------------------------------------|
| RF01  | Consultar dados cadastrais          | Permite ao usuário visualizar seus dados no Cadastro Único.              |
| RF02  | Emitir comprovante de cadastro      | Permite ao usuário gerar e visualizar o comprovante do Cadastro Único.  |
| RF03  | Atualizar cadastro                  | Permite atualizar informações pessoais e familiares no sistema.          |
| RF04  | Consultar benefícios recebidos      | Exibe os benefícios sociais que o usuário está recebendo.                |
| RF05  | Pré-cadastrar família               | Possibilita iniciar um pré-cadastro para uma nova unidade familiar.      |
| RF06  | Localizar postos de atendimento     | Mostra os CRAS mais próximos com base na localização do usuário.         |
| RF07  | Enviar notificações                 | Permite o envio de mensagens importantes ao usuário por meio do app.     |
| RF08  | Integrar com o CNIS                 | Traz dados de vínculos e contribuições automaticamente do CNIS.          |
| RF09  | Excluir cadastros unipessoais       | Permite a exclusão de cadastros unipessoais indevidos.                   |
| RF10  | Preencher endereço automaticamente  | Utiliza o CEP para preencher os dados de endereço de forma automática.   |

#### Desejáveis

| RF    | Nome do RF                                | Descrição                                                                 |
|-------|-------------------------------------------|---------------------------------------------------------------------------|
| RF11  | Chatbot de atendimento automatizado       | Implementa um chatbot para atendimento automatizado ao usuário.          |
| RF12  | Notificação de pendências ou atualizações | Envia notificações sobre pendências ou atualizações necessárias ao usuário.|
| RF13  | Simulador de benefícios sociais          | Permite ao usuário simular quais benefícios sociais poderia receber.      |
| RF14  | Upload de documentos                     | Permite ao usuário fazer upload de documentos para o sistema.            |
| RF15  | Agendamento de atendimento no CRAS       | Possibilita o agendamento de atendimento nos postos de CRAS.             |

### Requisitos Não-Funcionais

#### Já Existentes

| RNF   | Nome do RNF                              | Descrição                                                                 |
|-------|------------------------------------------|---------------------------------------------------------------------------|
| RNF16 | Disponível para Android e iOS            | O aplicativo está disponível em ambas as plataformas móveis, Android e iOS.|
| RNF17 | Autenticação por conta gov.br            | O acesso ao aplicativo é feito por meio da conta gov.br do usuário.       |
| RNF18 | Atualizações regulares                   | O aplicativo possui atualizações periódicas para corrigir erros e melhorar funcionalidades.|
| RNF19 | Interface intuitiva e amigável           | O design do aplicativo é simples e fácil de navegar para o usuário.       |
| RNF20 | Capacidade de atender grande base de usuários | O aplicativo suporta muitos usuários acessando simultaneamente.           |
| RNF21 | Integração com sistemas oficiais do governo | O aplicativo está integrado com sistemas oficiais, como o CNIS.           |

#### Desejáveis

| RNF   | Nome do RNF                              | Descrição                                                                 |
|-------|------------------------------------------|---------------------------------------------------------------------------|
| RNF22 | Acessibilidade para pessoas com deficiência visual | O aplicativo oferece recursos de acessibilidade para deficientes visuais, como leitores de tela. |
| RNF23 | Desempenho otimizado para internet limitada | O aplicativo oferece desempenho otimizado para conexões de internet mais lentas.|
| RNF24 | Possibilidade de outros idiomas          | O aplicativo deve estar disponível em vários idiomas, permitindo maior acessibilidade. |
| RNF25 | Backup e restauração de sessão           | O aplicativo deve permitir backup e restauração das sessões do usuário, caso haja interrupção ou falha.|
| RNF26 | Modo escuro                              | O aplicativo oferece uma opção de modo escuro para melhorar a experiência do usuário em ambientes com pouca luz. |
| RNF27 | Alta disponibilidade e recuperação de desastres | O aplicativo deve ter mecanismos de recuperação de dados e funcionamento em caso de falhas ou desastres. |

---

## Requisitos Elicitados (Finais)

### Requisitos Funcionais

#### Já Existentes

| RF    | Nome do RF                          | Descrição                                                                 |
|-------|--------------------------------------|---------------------------------------------------------------------------|
#### Desejáveis

| RF    | Nome do RF                                | Descrição                                                                 |
|-------|-------------------------------------------|---------------------------------------------------------------------------|

### Requisitos Não-Funcionais

#### Já Existentes

| RNF   | Nome do RNF                              | Descrição                                                                 |
|-------|------------------------------------------|---------------------------------------------------------------------------|

#### Desejáveis

| RNF   | Nome do RNF                              | Descrição                                                                 |
|-------|------------------------------------------|---------------------------------------------------------------------------|

---

## Conclusão

Os requisitos elicitados por essa técnica podem divergir dos demais, tendo em vista que é uma técnica aplicada por participantes do projeto, de maneira subjetiva e com base em percepções individuais.

---

## Referências

> GOGUEN, Joseph A.; LINDE, Charlotte. Techniques for Requirements Elicitation. In: IEEE International Symposium on Requirements Engineering, 1993. p. 152-164. Acesso em: 23/04/2025.

## Histórico de Versões

| Versão | Data | Descrição  | Autor        | Revisor |
| :-----: | :----: | :----------: | :------------: | :--------: |
| 1.0    | 23/04/2025 | Introdução e requisitos iniciais | [João Pedro Costa](https://github.com/johnaopedro)                   | [Julia Gabriela](https://github.com/JuliaGabP)                      |
