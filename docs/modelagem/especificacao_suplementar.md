# Introdução
A Especificação Suplementar é um documento em linguagem natural, cujo objetivo principal é descrever de forma detalhada os requisitos não funcionais de um sistema. Diferentemente dos casos de uso, que focam em funcionalidades e fluxos de interação, a Especificação Suplementar captura aspectos de qualidade, restrições e características que o software deve atender, mas que não são expressos nos diagramas comportamentais.

# Metodologia
Para elaborar a Especificação Suplementar, utiliza-se como guia o modelo FURPS+, que organiza os requisitos não funcionais nas seguintes categorias:

- Usability (Usabilidade): facilidade de uso pelo usuário.

- Reliability (Confiabilidade): previsão de falhas e capacidade de recuperação.

- Performance (Desempenho): tempo de resposta e throughput do sistema.

- Supportability (Suportabilidade): manutenibilidade, portabilidade, internacionalização, entre outros

Cada requisito não funcional é descrito em linguagem natural e classificado conforme essas categorias, permitindo aos engenheiros de software entenderem claramente as expectativas de qualidade e as restrições do projeto. Essa especificação serve como complemento aos casos de uso, garantindo que aspectos críticos de usabilidade, confiabilidade, desempenho e manutenção sejam considerados desde as primeiras fases de desenvolvimento.

# Especificação Suplementar

---

## Histórico de Revisões

| Versão | Data | Descrição | Autor |
|--------|------|-----------|-------|
|        |      |           |       |

---

## 1. Introdução

Este documento apresenta a Especificação Suplementar do aplicativo Cadastro Único, detalhando os requisitos que não foram completamente descritos nos casos de uso. O objetivo é registrar requisitos legais, de qualidade (como usabilidade, desempenho, confiabilidade e suportabilidade), além de outros aspectos técnicos e operacionais do sistema.

Abrange também restrições de projeto, interfaces e componentes adquiridos, com o intuito de fornecer um suporte completo à equipe de desenvolvimento.

### Finalidade

Este documento tem por finalidade especificar os requisitos suplementares não implementados no sistema, para que possam ser planejados, desenvolvidos e integrados às versões futuras do aplicativo Cadastro Único.

### Escopo

Abrange os requisitos funcionais e não funcionais elicitados por técnicas formais, porém ainda não implementados na versão atual do sistema. Estes requisitos são cruciais para a ampliação das funcionalidades voltadas ao público MEI, acessibilidade e suporte técnico.

### Definições, Acrônimos e Abreviações

| Termo | Definição |
|-------|-----------|
| **RF** | Requisito Funcional |
| **RNF** | Requisito Não Funcional |
| **MEI** | Microempreendedor Individual |
| **LGPD** | Lei Geral de Proteção de Dados |
| **MTBF** | Mean Time Between Failures |
| **MTTR** | Mean Time To Repair |

### Visão Geral

Esta especificação apresenta:
- Os requisitos funcionais não implementados (Seção 3);  
- Os requisitos de usabilidade relacionados (Seção 4);  
- Os requisitos de confiabilidade, desempenho e suportabilidade ainda não presentes (Seções 5 a 7);  
- As restrições de projeto (Seção 8);  
- Os requisitos técnicos e de ambiente (Seção 9);  
- As interfaces previstas, requisitos de licenciamento, anexos e aprovações.

## 2. Identificação do Projeto

| Campo               | Informação                      |
|---------------------|----------------------------------|
| Projeto             | Cadúnico – Cadastro Único |
| Requisitante        | Prof. Andre Barros de Sales            |
| Gerente de Projetos | [Ryan Salles](https://github.com/RA-Salles)     |


## 3. Funcionalidade  

### 3.1. RNF01 – Desempenho  
Definir parâmetros de tempo de resposta e carga suportada, com foco em picos de acesso, para garantir estabilidade nas funcionalidades futuras relacionadas ao MEI e filtragem de benefícios.

### 3.2. RNF05 – Acessibilidade  
Garantir que as novas funcionalidades sejam compatíveis com tecnologias assistivas (leitores de tela, alto contraste, navegação por teclado).

### 3.3. RNF07 – Compatibilidade com Aplicativo Off-line  
As novas funcionalidades devem funcionar também no modo offline, sincronizando os dados automaticamente quando houver conexão.

### 3.4. RNF08 – Transmissão via Conectividade Social  
A transmissão de informações do cadastro MEI e dados filtrados de benefícios deverá ser realizada pela ferramenta Conectividade Social da CAIXA.

### 3.5. RNF10 – Integração MEI  
O sistema deverá permitir integração com a base de dados da Receita Federal e sistemas da Redesim para validação e consulta de CNPJ MEI.

### 3.6. RNF14 – Usabilidade  
As novas funcionalidades devem respeitar princípios de usabilidade, como consistência, feedback ao usuário e baixa curva de aprendizagem.

## 4. Usabilidade  
### 4.1. Requisito de Usabilidade Um

## 5. Confiabilidade  
### 5.1. Requisito de Confiabilidade Um

## 6. Desempenho  
### 6.1. Requisito de Desempenho Um

## 7. Suportabilidade  
### 7.1. Requisito de Suportabilidade Um

## 8. Restrições de Projeto

### 8.1. Infraestrutura Tecnológica Limitada
O aplicativo deverá ser compatível com dispositivos móveis Android a partir da versão 6.0 (Marshmallow) e com navegadores modernos para acesso via web, considerando o uso por públicos de baixa renda com dispositivos mais antigos.

**Justificativa:** Grande parte dos usuários do CadÚnico possui celulares com recursos limitados de processamento e memória.

### 8.2. Adesão à LGPD
Todos os dados coletados, processados e armazenados pelo aplicativo devem estar em conformidade com a Lei Geral de Proteção de Dados (Lei nº 13.709/2018), garantindo consentimento explícito e controle sobre os dados pessoais do usuário.

**Justificativa:** O sistema lida com dados sensíveis e precisa atender exigências legais de privacidade.

### 8.3. Integração com Sistemas Governamentais Existentes
A aplicação deverá manter compatibilidade com a base de dados do Governo Federal e com sistemas como o SIBEC, Receita Federal e Conectividade Social da CAIXA, para validação e atualização de informações.

**Justificativa:** Para evitar redundância de informações e garantir veracidade dos dados.

### 8.4. Acesso com Baixa Conectividade
O projeto deve considerar o uso do aplicativo em regiões com baixa qualidade de internet. Funcionalidades críticas devem ser parcialmente disponíveis no modo offline, com sincronização posterior.

**Justificativa:** O público-alvo do CadÚnico reside frequentemente em áreas com infraestrutura limitada.

### 8.5. Compatibilidade com Tecnologias Assistivas
A interface do aplicativo deve ser compatível com leitores de tela, alto contraste, comandos por voz e navegação via teclado, atendendo aos requisitos de acessibilidade.

**Justificativa:** Inclusão digital de pessoas com deficiência visual ou motora é uma diretriz do governo federal.

### 8.6. Atualizações via Lojas Oficiais
As atualizações do aplicativo devem ser distribuídas exclusivamente pelas lojas Google Play e App Store, não sendo permitido o uso de APKs externos por questões de segurança.

**Justificativa:** Minimizar o risco de ataques, fraudes ou instalação de versões corrompidas do aplicativo.

## 9. Outros Requisitos do Produto

### 9.1. Padrões Aplicáveis
O aplicativo deverá seguir os seguintes padrões técnicos e de qualidade:

- **ABNT NBR ISO/IEC 25010:2011** – Qualidade de produto de software;
- **WCAG 2.1 (Web Content Accessibility Guidelines)** – Diretrizes de acessibilidade para interfaces;
- **Material Design** – Padrão visual e de interação do Google, para interfaces móveis;
- **OWASP Mobile Security Project** – Diretrizes para segurança de aplicativos móveis;
- **IEEE Std 830-1998** – Requisitos de software e especificação.

### 9.2. Requisitos do Sistema
- O aplicativo deverá ser compatível com:
  - Android 6.0 (Marshmallow) ou superior;
  - iOS 12.0 ou superior;
  - Navegadores modernos (Chrome, Firefox, Safari, Edge).

- Requisitos mínimos de hardware:
  - 1GB de RAM;
  - 200MB de espaço disponível;
  - Conexão mínima de 3G ou Wi-Fi.

### 9.3. Requisitos Ambientais
- O sistema deve funcionar em ambientes com variações de conectividade, com tolerância a interrupções momentâneas de rede.
- O aplicativo deve ser otimizado para operar em ambientes com pouca luminosidade (modo escuro) e temperaturas elevadas, comuns em regiões afastadas ou em áreas rurais.
- O sistema web deve ter comportamento responsivo e ser compatível com monitores de baixa resolução (a partir de 1024x768).


## 10. Componentes Comprados

O aplicativo poderá utilizar APIs públicas e serviços de terceiros para ampliar sua funcionalidade. Os seguintes componentes adquiridos ou externos são considerados:

- API da Receita Federal (consulta de CNPJ MEI).
- Serviço de Conectividade Social da CAIXA.
- Frameworks de acessibilidade (como ARIA para web).
- SDKs de mapas georreferenciados para exibição de postos de atendimento.

Todos os componentes deverão possuir documentação oficial, atualizações regulares e estar em conformidade com a LGPD.

## 11. Interfaces  
### 11.1. Interfaces de Usuário 

A interface do aplicativo será responsiva e acessível, com foco em:

- Navegação intuitiva;
- Compatibilidade com leitores de tela;
- Utilização de padrões de design do Governo Federal (Gov.br);
- Layout adaptável para smartphones e tablets.
  
### 11.2. Interfaces de Hardware  

O sistema deve ser compatível com dispositivos móveis Android e iOS, utilizando recursos de:

- Geolocalização;
- Câmera para envio de documentos;
- Armazenamento local para modo offline.

### 11.3. Interfaces de Software  

- Integração com a base do CadÚnico;
- Conectividade com Receita Federal (CNPJ MEI);
- Integração com APIs RESTful;
- Comunicação com servidores Gov.br para autenticação.

### 11.4. Interfaces de Comunicações

- HTTPS (protocolo seguro) para todas as transações de dados;
- WebSockets para sincronização em tempo real quando disponível;
- Transmissão de dados via Conectividade Social para casos específicos.

## 12. Requisitos de Licenciamento

O sistema deve estar em conformidade com:

- Licença de Software Livre para componentes de código aberto utilizados (ex: MIT, Apache 2.0);
- Termos de uso e distribuição de dados da Receita Federal e CAIXA;
- Políticas de privacidade exigidas pela LGPD.

A redistribuição e modificação do sistema estarão condicionadas aos termos definidos pelo Governo Federal e acordos com os fornecedores de API e dados.

## 13. Anexos

### Anexo A – Fluxo de Atualização de Dados Cadastrais
Apresenta o diagrama de fluxo de interação do usuário ao atualizar os dados da composição familiar. O fluxo inclui autenticação, exibição dos dados anteriores, edição, envio para validação e geração de protocolo.

**Objetivo:** Ajudar a validar a lógica da funcionalidade e antecipar possíveis exceções durante a atualização cadastral.

### Anexo B – Lista de Requisitos Elicitados por Entrevistas e Questionários
Tabela com os requisitos funcionais e não funcionais extraídos a partir de entrevistas com usuários reais e aplicação de formulários. Inclui data da coleta, perfil do usuário e tipo do requisito identificado (RF ou RNF).

**Objetivo:** Justificar a origem dos requisitos implementados e reforçar decisões de projeto baseadas em evidências reais.

### Anexo C – Documento de Casos de Uso
Inclui os principais casos de uso desenvolvidos para o projeto, como:

- UC01: Cadastro de Família  
- UC02: Atualização Cadastral  
- UC03: Filtrar Benefícios  
- UC04: Visualizar Postos de Atendimento

Cada caso de uso apresenta descrição, pré-condições, fluxos principais, fluxos alternativos e exceções.

**Objetivo:** Fornecer documentação clara das funcionalidades para análise, desenvolvimento e validação.

---

### Anexo D – Checklist de Priorização de Requisitos
Lista de verificação com critérios aplicados para priorizar os requisitos elicitados (impacto, urgência, viabilidade técnica, custo-benefício etc.). Baseado em técnicas como MoSCoW e 100-dollar test.

**Objetivo:** Apoiar a definição de escopo e garantir que funcionalidades críticas sejam entregues nas primeiras versões.

### Anexo E – Checklist de Cenários
Contém a lista de verificação para validar os cenários propostos no projeto. Avalia completude, clareza, consistência, presença de exceções e adequação ao fluxo principal.

**Objetivo:** Garantir que os cenários cubram os casos de uso reais e sirvam de base para testes futuros.

## 14. Referências

1. IEEE Std 830-1998 – *Recommended Practice for Software Requirements Specifications*  
2. LGPD – Lei nº 13.709/2018  
3. Portarias Senarc nº 123/2020 e 456/2021  
4. WIEGERS, Karl E.; BEATTY, Joy. *Software Requirements*. Microsoft Press, 3ª ed., 2013.


## 15. Aprovações

| Participante | Assinatura | Data |
|--------------|------------|------|
|              |            |      |

## Referências
> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 13a [slide em PDF]. Aprender³, Universidade de Brasília, 2025. Disponível em: <https://aprender3.unb.br/pluginfile.php/3096118/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf>. Acesso em: 16 maio 2025.

> REPOSITÓRIO DA DISCIPLINA – Aprender 3. Template da Especificação Suplementar. Disponível em: <https://aprender3.unb.br/mod/resource/view.php?id=1390972>. Acesso em: 16 maio 2025.

### Imagem 1: 
<div style="text-align: center;">
    <img src="../../assets/referencias/especificacao_suplementar/especificacao_suplementar.png" alt="especificacao_suplementar">
</div>

### Imagem 2: 
<div style="text-align: center;">
    <img src="../../assets/referencias/especificacao_suplementar/especificacao_suplementar1.png" alt="especificacao_suplementar1">
</div>

## Histórico de Versão

| Versão |    Data    |        Descrição         |                   Autor                    |                   Revisor                   |
| :----: | :--------: | :----------------------: | :----------------------------------------: | :-----------------------------------------: |
|  1.0   | 16/05/2025 |   Criação do Documento   | [João Pedro Costa](https://github.com/johnaopedro) e [Julia Paulino](https://github.com/JuliaGabP) | [Ryan Salles](https://github.com/RA-Salles) |
|  1.1   | 16/05/2025 |   Criação da introdução e metodologia   | [João Pedro Costa](https://github.com/johnaopedro) | [Ryan Salles](https://github.com/RA-Salles) |
|  1.2   | 16/05/2025 |   Criação da estrutura de especificação suplementar   | [João Pedro Costa](https://github.com/johnaopedro) e [Julia Paulino](https://github.com/JuliaGabP) | [Ryan Salles](https://github.com/RA-Salles) |
|  1.3   | 16/05/2025 |   Preenchimento de cinco seções da especificação   | [João Pedro Costa](https://github.com/johnaopedro) | [Ryan Salles](https://github.com/RA-Salles) |
|  1.4   | 16/05/2025 |   Preenchimento das seções 8 à 13   | [Julia Paulino](https://github.com/JuliaGabP) | [Ryan Salles](https://github.com/RA-Salles) |
