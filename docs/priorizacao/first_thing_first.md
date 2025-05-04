# Introdução

A metodologia First Things First: Prioritizing Requirements, apresentada por Karl Wiegers, enfatiza a necessidade de priorização eficaz de requisitos em projetos de software. Como nem sempre é possível entregar todas as funcionalidades desejadas na primeira versão de um sistema, os stakeholders devem definir quais aspectos são mais críticos para o sucesso inicial do projeto. A priorização permite gerenciar expectativas, resolver conflitos e otimizar recursos, garantindo que as funções essenciais sejam implementadas primeiro.

## Metodologia First Things First
Wiegers propõe um modelo estruturado de priorização baseado em três fatores principais:
- **Valor para o cliente** – Identificação do benefício que cada requisito traz e a penalidade caso não seja implementado.
- **Custo de implementação** – Avaliação do esforço necessário para desenvolver determinada funcionalidade.
- **Riscos técnicos** – Consideração da complexidade e dos desafios envolvidos na implementação.

A metodologia sugere que os requisitos sejam agrupados em diferentes níveis de prioridade, como:
- **Alta prioridade** – Elementos essenciais para o funcionamento do sistema na próxima versão.
- **Média prioridade** – Funcionalidades importantes, mas que podem ser adiadas para versões futuras.
- **Baixa prioridade** – Melhorias e incrementos que podem ser considerados caso os recursos permitam.

Wiegers também destaca que a participação ativa dos stakeholders no processo de priorização é essencial, pois os clientes devem avaliar o impacto de cada funcionalidade e os desenvolvedores devem indicar a viabilidade técnica.

## Aplicação no app Cadastro Único
O **Cadastro Único**, sistema utilizado para identificar e registrar famílias de baixa renda, pode se beneficiar da metodologia **First Things First** para otimizar seu desenvolvimento e evolução. Seguindo os princípios de Wiegers, a aplicação pode:
- **Priorizar funcionalidades críticas** – Garantir que os requisitos essenciais, como cadastro, atualização de dados e integração com programas sociais, sejam implementados antes de recursos secundários.
- **Gerenciar recursos e tempo** – Evitar desperdício de esforço em funcionalidades menos prioritárias, focando no que realmente impacta a usabilidade e eficiência do sistema.
- **Reduzir riscos técnicos** – Adotar uma abordagem incremental, desenvolvendo primeiro os aspectos mais seguros e previsíveis antes de funcionalidades mais complexas.
- **Melhorar a experiência do usuário** – Garantir que o atendimento às famílias ocorra sem interrupções, otimizando processos essenciais antes de implementar melhorias secundárias.

## Requisitos

### Requisitos Funcionais (RF)

| **ID**  | **Descrição do Requisito** | **Importante?** | **Urgente?**| **Quadrante** | **Ação** |
|---------|----------------------------|-----------------|-------------|---------------|----------|
| RF01   | Cadastro e atualização de dados das famílias.               | Sim | Sim | 1 | Fazer Agora |
| RF02   | Integração com sistemas governamentais para conformidade.   | Sim | Sim | 1 | Fazer Agora |
| RF03   | Geração de relatórios analíticos detalhados.                | Sim | Não | 2 | Planejar |
| RF04   | Sistema de notificações automáticas para prazos e atualizações. | Sim | Não | 2 | Planejar |
| RF05   | Funcionalidades para consulta e edição de informações pelos usuários. | Sim | Sim | 1 | Fazer Agora |
| RF06   | Autenticação de usuários (login seguro com CPF e senha).       | Sim | Sim | 1 | Fazer Agora |
| RF07   | Recuperação de senha por e-mail ou SMS.                        | Sim | Sim | 1 | Fazer Agora |
| RF08   | Consulta de benefícios disponíveis.                            | Sim | Sim | 1 | Fazer Agora |
| RF09   | Atualização de status de inscrição.                            | Sim | Sim | 1 | Fazer Agora |
| RF10   | Histórico de atualizações no cadastro.                         | Sim | Não | 1 | Fazer Agora |


### Requisitos Não Funcionais (RNF)

| **ID**  | **Descrição do Requisito** | **Importante?** | **Urgente?**| **Quadrante** | **Ação** |
|---------|----------------------------|-----------------|-------------|---------------|----------|
| RNF01  | Garantir a acessibilidade para pessoas com deficiência (padrões WCAG). | Sim | Sim | 1 | Fazer Agora |
| RNF02  | Tempo de resposta do sistema inferior a 2 segundos por operação. | Sim | Não | 2 | Planejar |
| RNF03  | Interface amigável e intuitiva para melhorar a experiência do usuário. | Sim | Não | 2 | Planejar |
| RNF04  | Capacidade de suportar até 10 mil usuários simultâneos.      | Sim | Sim | 1 | Fazer Agora |
| RNF05  | Disponibilidade do sistema 99,9% do tempo.                  | Sim | Sim | 1 | Fazer Agora |
| RNF06  | Conformidade com a Lei Geral de Proteção de Dados (LGPD).       | Sim | Sim | 1 | Fazer Agora |
| RNF07  | Criptografia de dados sensíveis em trânsito e em repouso.       | Sim | Sim | 1 | Fazer Agora |
| RNF08  | Compatibilidade com dispositivos móveis variados.              | Sim | Não | 2 | Planejar |
| RNF09  | Operação funcional em redes de baixa velocidade (modo offline). | Sim | Não | 2 | Planejar |
| RNF10  | Atualizações automáticas sem necessidade de reinstalação manual. | Não | Não | 4 | Eliminar |
| RNF11  | Modo escuro, uma alternativa visual para ambientes com pouca luz  | Não | Não | 4 | Eliminar |
| RNF12  | Disponibilidade do app em múltiplos idiomas.          | Não | Não | 4 | Eliminar |

## Referências

> WIEGERS, Karl E. **First Things First: Prioritizing Requirements**. *Software Development*, setembro 1999. Acesso em: 23 abr. 2025.

## Histórico de Versões

| Versão | Data | Descrição  | Autor        | Revisor |
| :-----: | :----: | :----------: | :------------: | :--------: |
| 1.0    | 23/04/2025 | Criação da página da tecnica First Thing First| [João Pedro Costa](https://github.com/johnaopedro)                   | [Julia Gabriela](https://github.com/JuliaGabP)                      |
| 1.1 | 04/05/2025 | Priorização de requisitos | [Gabriel Flores](https://github.com/Gabrielfcoelho) | [Ryan](https://github.com/RA-Salles) e [João Pedro Costa](https://github.com/johnaopedro) |