# Pós-Rastreabilidade
---
### Introdução

Este documento tem como finalidade demonstrar a conexão entre os requisitos, a arquitetura do sistema e a implementação. Dessa forma, são evidenciadas as relações de dependência entre os artefatos produzidos durante o desenvolvimento: sejam eles de requisitos, de arquitetura ou de código. A rastreabilidade é estruturada por meio de vínculos que representam a interligação entre esses elementos.

### Metodologia

A base metodológica adotada para estruturar a rastreabilidade foi o meta-modelo proposto por Toranzo. Esse modelo organiza os elementos rastreados em quatro grandes categorias:

- **Ambiental**: leis, padrões, estratégias e metas;
- **Organizacional**: processos, objetivos e regras;
- **Gerencial**: tarefas, objetivos e restrições;
- **Desenvolvimento**: requisitos, diagramas e código-fonte.

Neste projeto, a rastreabilidade está concentrada na categoria de **Desenvolvimento**, dado o escopo definido. Para adaptar o modelo às necessidades da pós-rastreabilidade, foram aplicadas modificações que permitem visualizar a ligação entre os requisitos elicitados e seus correspondentes artefatos de design e implementação. Os tipos de vínculo (ou elos) considerados neste processo são: **satisfação**, **recurso**, **representação**, **alocação** e **agregação**.

Vale destacar que o elo de **responsabilidade** foi excluído da análise, pois os artefatos disponíveis não permitem esse tipo de rastreamento.

A rastreabilidade foi aplicada exclusivamente aos requisitos que **não foram implementados** pela aplicação Bilheteria Digital, embora alguns tenham sido simulados no protótipo de alta fidelidade utilizado na etapa de validação. A estrutura usada para organizar essas informações pode ser visualizada na Tabela 1.

#### Tabela 1 – Modelo de Pós-Rastreabilidade

| Artefato Analisado | Tipo de Artefato         | Tipos de Elo           | Artefatos Relacionados |
|--------------------|--------------------------|------------------------|-------------------------|
| -                  | -                        | Satisfação             | -                       |
| -                  | -                        | Recurso                | -                       |
| -                  | -                        | Representação          | -                       |
| -                  | -                        | Alocado                | -                       |
| -                  | -                        | Agregação              | -                       |

<sub>Fonte: (TORANZO, 2002).</sub>

### Rastreabilidade

As tabelas a seguir detalham os elos identificados entre os artefatos e os requisitos, tanto funcionais quanto não funcionais, implementados ou não pela Bilheteria Digital. 


---
# Histórico de Versões

| Versão | Data de produção   | Descrição da Alteração                               | Autor(es)             | Revisor(es)      | Data de Revisão |
| :----: | :----------------: | :--------------------------------------------------: | :-------------------: | :-------------:  | :-------------: |
| 1.0    | 06/02/2025         | Criação inicial do documento                         | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | 06/02/2025 |
| 1.1    | 06/02/2025         | Adição das seções de Introdução e Metodologia | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | 08/02/2025 |
