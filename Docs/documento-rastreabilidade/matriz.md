## Matriz Geral de Rastreabilidade

### Introdução

A **matriz geral de rastreabilidade** é um artefato essencial na engenharia de requisitos que permite representar, de forma consolidada, os requisitos funcionais identificados ao longo do projeto, juntamente com sua **pré e pós-rastreabilidade**. A proposta é fornecer uma **visão integrada e sistemática** dos vínculos entre os requisitos, suas origens (como técnicas de elicitação) e os artefatos derivados ou relacionados.

De acordo com Sayão e Leite (2005), a rastreabilidade é o mecanismo que viabiliza a ligação entre os diversos elementos envolvidos no ciclo de vida de um sistema, incluindo requisitos, documentos, decisões e implementações. A matriz geral viabiliza essa conexão por meio de **referências cruzadas e elos rastreáveis**, revelando **dependências**, **origens documentais** e **impactos** que cada requisito pode ter em diferentes fases do desenvolvimento.

Dessa forma, a matriz não apenas favorece a **compreensão e análise sistêmica dos requisitos**, como também contribui para a **gestão de mudanças**, o **controle de qualidade** e a **manutenção evolutiva** do sistema ao longo do tempo.

---

### Objetivos

O objetivo da matriz geral é consolidar as informações dos artefatos de **Backward-Form** (rastreabilidade retroativa) e **Forward-Form** (rastreabilidade prospectiva), proporcionando uma **visão unificada** do ciclo de vida dos requisitos. Através dessa unificação, é possível:

- Verificar se todos os requisitos têm origem justificada (pré-rastreabilidade);
- Avaliar o estado de implementação de cada funcionalidade;
- Mapear os artefatos técnicos relacionados a cada requisito;
- Identificar **elos** e **interdependências** que auxiliam na análise de impacto.

Essa estrutura oferece um ponto central de consulta, facilitando o acompanhamento e a validação dos requisitos em todas as fases do projeto.

---

### Metodologia

A construção da matriz geral partiu dos **requisitos elicitados** no projeto, especialmente aqueles que ainda não estavam completamente implementados no momento da análise. Esses requisitos foram cruzados com os dados coletados nos artefatos de rastreabilidade backward e forward, permitindo a composição de uma tabela unificada.

A matriz geral é organizada em **sete colunas**, com os seguintes significados:

- **ID**: Identificador único do requisito funcional.
- **Descrição**: Texto descritivo que expressa claramente o comportamento esperado do sistema.
- **Pré-Rastreabilidade**: Técnicas e artefatos de elicitação (como questionários, storytelling ou análise de documentos) que fundamentam o requisito.
- **Implementado?**: Indicação do status de implementação no aplicativo (Sim, Não, Parcialmente).
- **Artefatos**: Representações técnicas ou documentais que detalham ou se relacionam diretamente com o requisito.
- **Elos**: Ligações semânticas entre os requisitos e outros elementos (outros requisitos, funcionalidades, testes, etc.), indicando dependência, influência ou refinamento.

Esta matriz representa, portanto, uma peça-chave no processo de **documentação e rastreamento completo dos requisitos**, apoiando práticas de desenvolvimento ágil, melhoria contínua e validação sistemática.

---

### Referência

SAYÃO, Miriam; LEITE, Julio Cesar Sampaio do Prado. **Rastreabilidade de Requisitos**. Monografias em Ciência da Computação, Nº 20/05. Departamento de Informática, PUC-Rio, 2005.

---





---
# Histórico de Versões

| Versão | Data de produção   | Descrição da Alteração                               | Autor(es)             | Revisor(es)      | Data de Revisão |
| :----: | :----------------: | :--------------------------------------------------: | :-------------------: | :-------------:  | :-------------: |
| 1.0    | 06/02/2025         | Criação inicial do documento                         | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | 06/02/2025 |
| 1.1    | 06/02/2025         | Adição das seções de Introdução, Objetivos e Metodologia | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | 08/02/2025 |
