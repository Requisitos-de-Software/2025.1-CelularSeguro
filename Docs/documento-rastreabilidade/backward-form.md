## Rastreabilidade dos Requisitos Funcionais (Backward-Form)

### Introdução

A rastreabilidade de requisitos é uma prática essencial da engenharia de requisitos, pois permite compreender a origem, o contexto e as motivações que justificam a existência de cada funcionalidade do sistema. Neste projeto, utilizamos a abordagem **backward-form** de rastreabilidade, que estabelece, para cada requisito funcional, os elementos do processo de elicitação que contribuíram para sua formulação.

Segundo Sayão e Leite (2005), a rastreabilidade backward consiste em identificar, para cada requisito, os artefatos anteriores (como documentos, respostas de usuários e interações com stakeholders) que fundamentaram sua criação. Tal abordagem proporciona maior **transparência, validação cruzada** entre as fontes e **facilita a manutenção evolutiva** dos requisitos ao longo do ciclo de vida do software.

---

### Metodologia

A rastreabilidade backward foi construída com base nos dados gerados durante a etapa de elicitação de requisitos do projeto. Utilizamos cinco técnicas distintas de elicitação:

- **Análise de Documentos (ADD):** consulta a leis, políticas públicas e normativas técnicas sobre segurança de dispositivos móveis e autenticação digital.
- **Questionário (QS):** aplicação de formulários com usuários em potencial, visando levantar percepções, necessidades e expectativas.
- **Brainstorming (BS):** sessões coletivas com membros da equipe para levantar e refinar ideias iniciais.
- **Storytelling (ST):** criação de narrativas baseadas em situações reais ou hipotéticas de perda, roubo ou uso indevido de celulares.
- **Observação Direta (OBS):** acompanhamento e análise do uso de sistemas similares por usuários reais, em situações cotidianas.

Cada requisito funcional foi analisado em relação ao conteúdo obtido por essas técnicas. Quando duas ou mais fontes contribuíram para a formulação de um requisito, todas foram listadas na coluna de rastreabilidade. As associações foram feitas manualmente, com base na documentação coletada e arquivada nas abas específicas do projeto.

---

### Legenda das Tabelas

A tabela de requisitos funcionais utiliza links e siglas que identificam claramente a técnica de elicitação utilizada como origem do requisito. A seguir, apresentamos a legenda dessas siglas:

| Sigla   | Técnica de Elicitação        |
|---------|------------------------------|
| **ADD** | Análise de Documentos        |
| **QS**  | Questionário                 |
| **BS**  | Brainstorming                |
| **ST**  | Storytelling                 | 
| **OBS** | Observação             | 



A estrutura backward-form permite identificar a origem de cada requisito, fortalecendo o vínculo entre as funcionalidades propostas e os interesses dos stakeholders, além de subsidiar futuras fases de verificação, validação e manutenção do sistema.

---



---

### Referências

SAYÃO, Miriam; LEITE, Julio Cesar Sampaio do Prado. **Rastreabilidade de Requisitos**. Monografias em Ciência da Computação, Nº 20/05. Departamento de Informática, PUC-Rio, 2005.
