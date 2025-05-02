# Celular Seguro: Observação

---

## Metodologia

Para a realização da atividade, foi utilizada uma abordagem prática e simulada da técnica de observação. A execução foi feita por dois integrantes do grupo: um assumiu o papel de usuário(**Daniel Rodrigues**), interagindo com o aplicativo Celular Seguro como se estivesse em uma situação real de uso, enquanto o outro atuou como observador(**Gabriel Lima**), acompanhando atentamente as ações realizadas, registrando dificuldades encontradas, comportamentos notáveis e possíveis melhorias. Essa simulação permitiu levantar requisitos de forma realista, mesmo sem a participação de um agente externo, garantindo a efetividade da técnica dentro do contexto acadêmico.

---

## Participantes da Sessão

A **Tabela 2** apresenta os participantes da sessão de observação do projeto Celular Seguro, incluindo seus nomes (ou identificações) e funções desempenhadas na reunião:

*Tabela 2: Participantes da sessão de observação e suas funções.*

| **Nome/ID**       | **Função na Sessão** |
|-------------------|----------------------|
| Daniel Rodrigues  | Usuário |
| Gabriel Lima      | Observador|

**Usuário:** responsável por utilizar o aplicativo e suas funcionalidades, para que possa ser encontrados possíveis problemas no aplicativo.
**Observador:** responsável por registrar as funcionalidades possíveis de serem executadas e as que estão com algum tipo de problema ou não existem. 

---

## Tabela de Requisitos Funcionais

Durante o que foi observado, foram definidos os **Requisitos Funcionais (RF)** do sistema Celular Seguro. Estes representam funcionalidades ou comportamentos **necessários** que o aplicativo tem que proporcionar. A **Tabela 3** abaixo lista os requisitos funcionais identificados, com um identificador numérico, uma breve descrição, um código de referência (RFx) e se o requisito já está implementado ou não no sistema.

*Tabela 3: Requisitos Funcionais identificados para o Celular Seguro.* 

| **ID** | **Descrição do Requisito Funcional**                                   | **Código (RFx)** | **Implementado?** |
|:-------:|-------------------------------------------------------------------------|:------------------:|:-------------------:|
| OBS1     | O aplicativo possui algum tipo de tutorial. | RF1 | Sim |
| OBS2     | O aplicativo permite cadastrar um novo telefone. | RF2 | Sim |
| OBS3     | O aplicativo permite pesquisar telefones cadastrados. | RF3 | Sim |
| OBS4     | O aplicativo permite consultar celulares com Restrição. | RF4 | Sim |
| OBS5     | O aplicativo tem consulta por IMEI de celulares bloqueados. | RF5 | Sim |
| OBS6     | O aplicativo permite emitir um alerta um furto/roubo/perda do aparelho. | RF6 | Sim |
| OBS7     | O aplicativo disponibiliza uma função de cancelar uma restrição/alerta. | RF7 | Não |
| OBS8     | Dentro do aplicativo, é possível registar um boletim de ocorrência. | RF8 | Não |
| OBS9     | O aplicativo possui uma função para entrar em contato com suporte. | RF9 | Não |

*Legenda:* **ID** – Identificador numérico do requisito. **Descrição** – definição concisa da funcionalidade exigida. **Código (RFx)** – código de referência do Requisito Funcional (RF) seguido de um número sequencial. **Implementado?** – indica se o requisito está implementado no sistema atualmente (Sim) ou não (Não). 

---

## Tabela de Requisitos Não Funcionais

Além das funções, foram identificados também alguns **Requisitos Não Funcionais (RNF)** relevantes para o Celular Seguro. Estes requisitos descrevem restrições de qualidade e critérios sobre *como* o sistema deve se comportar ou quais padrões deve seguir (desempenho, usabilidade, etc.), em vez de funcionalidades em si. A **Tabela 4** apresenta os requisitos não funcionais elicitados, com identificador, descrição, código (RNFx) e status de implementação.

*Tabela 4: Requisitos Não Funcionais identificados para o Celular Seguro.*

| **ID** | **Descrição do Requisito Não Funcional**                              | **Código (RNFx)** | **Implementado?** |
|:-------:|-----------------------------------------------------------------------|:-------------------:|:-------------------:|
| OBS10     | O aplicativo funciona corretamente em diferentes dispositivos Android e iOS. | RNF1 | Sim|
| OBS11     | O aplicativo guia de forma clara em como conseguir o IMEI do seu aprelho. | RNF2 | Sim |
| OBS12     | O login via Gov.br oferece autenticação eficaz para todos os níveis de conta. | RNF3 | Não |
| OBS13     | O aplicativo é acessível para pessoas com deficiência visual (uso de leitor de tela, contraste, tamanho da fonte). | RNF4 | Não |
| OBS14     | O aplicativo responde corretamente mesmo com entradas erradas | RNF5 | Não |
| OBS15     | O aplicativo apresenta uam confirmação de suas ações. | RNF6 | Sim |


*Legenda:* **ID** – Identificador numérico do requisito. **Descrição** – detalhamento do critério de qualidade ou restrição. **Código (RNFx)** – código de referência do Requisito Não Funcional (RNF) com numeração sequencial. **Implementado?** – indica se o requisito já se encontra implementado (Sim) ou não (Não). 

---

## Legenda Geral

- **RF – Requisito Funcional:** descreve **o que** o sistema deve fazer. É uma funcionalidade ou serviço que o sistema deve prover para atender às necessidades do usuário ou do negócio (por exemplo, *“bloquear remotamente o dispositivo”*).  
- **RNF – Requisito Não Funcional:** descreve **como** o sistema deve se comportar ou quais restrições de qualidade ele deve obedecer. Engloba atributos como usabilidade, desempenho, segurança, confiabilidade, etc.
- **OBS – (Observação) Palavra-chave da sessão:** código associado às **palavras-chave** ou ideias brutas geradas na sessão de Observação. Cada *OBSx* corresponde a algo identificado na observação, utilizado para rastrear a origem das discussões e auxiliar na derivação dos requisitos correspondentes.

---

## Referências Bibliográficas

- SOMMERVILLE, Ian. Engenharia de Software. 10. ed. São Paulo: Pearson, 2019.

---

## Histórico de Versões

| Versão | Data de Produção | Descrição da Alteração | Autor(es) | Revisor(es) | Data de Revisão |
| :----: | :--------------: | :-------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------: | :-------------: |
| 1.0    | 01/05/2025       | Documento inicial de observação do projeto Celular Seguro | <a style="color:gold;" href="https://github.com/zDrNz" target="_blank">Daniel Rodrigues</a> | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a>|02/05/2025|