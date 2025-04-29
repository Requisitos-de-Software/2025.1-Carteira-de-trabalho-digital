# Three-Level Scale
## Introdução

O **Three-Level Scale** é um método utilizado para priorizar requisitos em projetos de software, classificando-os em três categorias: **alta prioridade**, **prioridade média** e **baixa prioridade**. Esse método, embora seja subjetivo, é eficaz quando os stakeholders concordam sobre os critérios de cada nível. A avaliação é feita com base em duas dimensões principais:

- **Importância**: Relevância do requisito para os objetivos do negócio.
- **Urgência**: Necessidade imediata de implementação do requisito.

As categorias são definidas da seguinte forma:

- **Alta Prioridade**: Requisitos importantes e urgentes, necessários para alcançar os objetivos do negócio na próxima versão. Incluem obrigações contratuais ou requisitos de conformidade que não podem ser adiados.
- **Prioridade Média**: Requisitos importantes, mas não urgentes, que podem ser adiados para versões futuras sem grandes prejuízos.
- **Baixa Prioridade**: Requisitos que não são críticos para o negócio e podem ser adiados ou descartados sem impacto significativo.

Requisitos percebidos como urgentes, mas que não são importantes para os objetivos de negócio, devem ser evitados ou removidos, pois não agregam valor suficiente ao produto.

Além disso, é recomendável incluir a prioridade de cada requisito como um atributo nos documentos de requisitos, como o SRS (Software Requirements Specification) ou em um banco de dados de requisitos, para garantir clareza e alinhamento entre os envolvidos.

Em projetos maiores, pode ser necessário realizar uma segunda rodada de priorização dentro dos requisitos de alta prioridade, subdividindo-os em "alto", "mais alto" e "altíssimo", para manter o foco nas funcionalidades realmente essenciais.

---

## Aplicação no App Cadastro Único

No contexto do app **Cadastro Único**, o método pode ser aplicado para organizar e priorizar os requisitos de forma eficiente:

### Alta Prioridade
- Cadastro e atualização de dados das famílias, atendendo às exigências legais.
- Integração com sistemas governamentais para assegurar conformidade com políticas públicas.
- Funcionalidades de acessibilidade para garantir a inclusão de pessoas com deficiência.
- Autenticação de usuários (login seguro com CPF e senha).
- Consulta de benefícios disponíveis com base no perfil da família.
- Atualização de status de inscrição (pendente, aprovado, recusado).

### Prioridade Média
- Sistema de notificações automáticas para informar usuários sobre prazos e atualizações.
- Melhorias na interface do usuário (UX/UI), com foco em usabilidade.
- Geração de relatórios analíticos detalhados para suportar decisões estratégicas.
- Recuperação de senha por e-mail ou SMS.
- Histórico de atualizações e registros de alterações no cadastro.
- Compatibilidade com dispositivos de diferentes resoluções.
- Modo offline limitado para conexões lentas.

### Baixa Prioridade
- Personalização estética do aplicativo, como alteração de temas.
- Elementos de gamificação para engajamento dos usuários.
- Suporte para múltiplos idiomas, caso não seja uma demanda imediata ou ampla.
- Atualizações automáticas de versão sem reinstalação manual.

---

## Requisitos

### Requisitos Funcionais (RF)

| **ID**  | **Descrição do Requisito**                                   | **Prioridade**      |
|---------|-------------------------------------------------------------|---------------------|
| RF01   | Cadastro e atualização de dados das famílias.               | Alta Prioridade     |
| RF02   | Integração com sistemas governamentais para conformidade.   | Alta Prioridade     |
| RF03   | Geração de relatórios analíticos detalhados.                | Prioridade Média    |
| RF04   | Sistema de notificações automáticas para prazos e atualizações. | Prioridade Média    |
| RF05   | Funcionalidades para consulta e edição de informações pelos usuários. | Alta Prioridade     |
| RF06   | Autenticação de usuários (login seguro com CPF e senha).       | Alta Prioridade     |
| RF07   | Recuperação de senha por e-mail ou SMS.                        | Prioridade Média    |
| RF08   | Consulta de benefícios disponíveis.                            | Alta Prioridade     |
| RF09   | Atualização de status de inscrição.                            | Alta Prioridade     |
| RF10   | Histórico de atualizações no cadastro.                            | Prioridade Média    |


### Requisitos Não Funcionais (RNF)

| **ID**  | **Descrição do Requisito**                                   | **Prioridade**      |
|---------|-------------------------------------------------------------|---------------------|
| RNF01  | Garantir a acessibilidade para pessoas com deficiência (padrões WCAG). | Alta Prioridade     |
| RNF02  | Tempo de resposta do sistema inferior a 2 segundos por operação. | Alta Prioridade     |
| RNF03  | Interface amigável e intuitiva para melhorar a experiência do usuário. | Prioridade Média    |
| RNF04  | Capacidade de suportar até 10 mil usuários simultâneos.      | Alta Prioridade     |
| RNF05  | Disponibilidade do sistema 99,9% do tempo.                  | Alta Prioridade     |
| RNF06  | Conformidade com a Lei Geral de Proteção de Dados (LGPD).       | Alta Prioridade     |
| RNF07  | Criptografia de dados sensíveis em trânsito e em repouso.       | Alta Prioridade     |
| RNF08  | Compatibilidade com dispositivos móveis variados.              | Prioridade Média    |
| RNF09  | Operação funcional em redes de baixa velocidade (modo offline). | Prioridade Média    |
| RNF10  | Atualizações automáticas sem necessidade de reinstalação manual. | Baixa Prioridade    |

## Referências

> Three level scale: Setting requirement priorities. In: WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. [S. l.]: Microsoft Press, 2013. cap. 16, p. 319-320. ISBN 0735679665.

## Histórico de Versões

| Versão | Data | Descrição  | Autor        | Revisor |
| :-----: | :----: | :----------: | :------------: | :--------: |
| 1.0    | 28/04/2025 | Criação da página da tecnica Three Level Scale| [João Pedro Costa](https://github.com/johnaopedro)                   | [Ryan Salles](https://github.com/RA-Salles) |