# First Things First

## Introdução

A priorização de requisitos é fundamental para garantir que funcionalidades críticas sejam desenvolvidas primeiro. No projeto Celular Seguro, utilizamos a técnica First Things First para organizar e priorizar os requisitos com base em benefício, penalidade, custo e risco. Essa abordagem ajuda a alinhar o desenvolvimento com os objetivos de segurança, usabilidade e acessibilidade do aplicativo.

## Metodologia

As pessoas que participaram da aplicação da técnica _First Things First_ (FTF) estão listadas na **Tabela 1**.

- **Mediador** – Conduz a sessão e apresenta os requisitos.
- **Cliente** – Atribui notas de **benefício** e **penalidade**.
- **Desenvolvedor** – Atribui notas de **custo** e **risco**.


*Tabela 1: Participantes da técnica First Things First.*

| **Nome**            | **Função**     |
|---------------------|----------------|
| Arthur Carvalho     | Mediador       |
| Usuário Representante | Cliente        |
| Gabriel Lima | Desenvolvedor |



*Legenda:* 

**Nome** – participante da técnica. 

**Função** – papel desempenhado na priorização.


---

A aplicação do FTF seguiu os passos:

1. Listagem e filtragem dos requisitos independentes.
2. Atribuição de notas de **benefício** e **penalidade** (escala 1 – 9) pelo Cliente.
3. Atribuição de notas de **custo** e **risco** (1 – 9) pelo Desenvolvedor.
4. Cálculo do **valor total** = Benefício × 2 + Penalidade × 1.
5. Normalização dos valores e cálculo da **prioridade**:

<p align="center" style="font-size: 18px;">prioridade = valor(%) / (Custo (%) × Custo Relativo) + (Risco (%) × Risco Relativo)</p>

6. Ordenação dos requisitos em ordem decrescente de prioridade.

### Pesos relativos

- Benefício: **2**  
- Penalidade: **1**  
- Custo: **1**  
- Risco: **1**

---

## Resultado da Priorização


*Tabela 2: Resultado da priorização dos requisitos.*

| **Funcionalidade** | **Benefício&nbsp;Relativo** | **Penalidade&nbsp;Relativa** | **Valor&nbsp;total** | **Valor&nbsp;(%)** | **Custo&nbsp;Relativo** | **Custo&nbsp;(%)** | **Risco&nbsp;Relativo** | **Risco&nbsp;(%)** | **Prioridade** |
|--------------------|----------------------------|-----------------------------|----------------------|--------------------|------------------------|--------------------|-------------------------|--------------------|---------------|
| Q01 | 9 | 9 | 27 | 4,98 | 1 | 1,35 | 1 | 1,16 | 1,984 |
| Q02 | 9 | 9 | 27 | 4,98 | 1 | 1,35 | 1 | 1,16 | 1,984 |
| OBS06 | 9 | 9 | 27 | 4,98 | 1 | 1,35 | 1 | 1,16 | 1,984 |
| OBS15 | 8 | 9 | 25 | 4,61 | 1 | 1,35 | 1 | 1,16 | 1,836 |
| OBS10 | 8 | 7 | 22 | 4,05 | 1 | 1,35 | 1 | 1,16 | 1,613 |
| OBS09 | 9 | 9 | 27 | 4,98 | 1 | 1,35 | 3 | 3,49 | 1,031 |
| BS15 | 8 | 9 | 25 | 4,61 | 2 | 2,70 | 2 | 2,33 | 0,458 |
| Q09 | 8 | 5 | 21 | 3,87 | 2 | 2,70 | 2 | 2,33 | 0,384 |
| BS08 | 7 | 6 | 20 | 3,69 | 2 | 2,70 | 2 | 2,33 | 0,366 |
| BS23 | 6 | 7 | 19 | 3,50 | 2 | 2,70 | 2 | 2,33 | 0,347 |
| BS17 | 6 | 7 | 19 | 3,50 | 2 | 2,70 | 2 | 2,33 | 0,347 |
| BS02 | 9 | 7 | 25 | 4,61 | 2 | 2,70 | 4 | 4,65 | 0,192 |
| BS37 | 8 | 7 | 23 | 4,24 | 3 | 4,05 | 3 | 3,49 | 0,170 |
| OBS18 | 6 | 8 | 20 | 3,69 | 3 | 4,05 | 3 | 3,49 | 0,163 |
| Q06 | 6 | 5 | 17 | 3,13 | 3 | 4,05 | 3 | 3,49 | 0,138 |
| BS52 | 9 | 9 | 27 | 4,98 | 4 | 5,41 | 4 | 4,65 | 0,123 |
| BS50 | 8 | 9 | 25 | 4,61 | 4 | 5,41 | 4 | 4,65 | 0,114 |
| BS48 | 6 | 7 | 19 | 3,50 | 4 | 5,41 | 4 | 4,65 | 0,086 |
| BS60 | 8 | 9 | 25 | 4,61 | 5 | 6,76 | 5 | 5,81 | 0,073 |
| OBS03 | 4 | 9 | 17 | 3,13 | 5 | 6,76 | 5 | 5,81 | 0,049 |
| OBS21 | 7 | 5 | 19 | 3,50 | 5 | 6,76 | 6 | 6,98 | 0,046 |
| OBS16 | 4 | 3 | 11 | 2,02 | 2 | 2,70 | 6 | 6,98 | 0,042 |
| Q19 | 6 | 3 | 15 | 2,76 | 5 | 6,76 | 6 | 6,98 | 0,036 |
| BS54 | 9 | 9 | 27 | 4,98 | 7 | 9,46 | 9 | 10,47 | 0,031 |
| BS56 | 5 | 3 | 13 | 2,39 | 6 | 8,11 | 6 | 6,98 | 0,026 |
| TOTAL|   |   | 542|      | 74| 100  | 86| 100  |


*Legenda:* 

**Funcionalidade** – código do requisito priorizado (**RFx** para funcionais, **RNFx** para não funcionais). 

**Benefício&nbsp;Relativo** e **Penalidade&nbsp;Relativa** – notas (1 – 9) atribuídas pelo *Cliente*. 

**Valor&nbsp;total** – Benefício × 2 + Penalidade × 1. 

**Valor&nbsp;(%)** – valor total normalizado. 

**Custo&nbsp;Relativo** e **Risco&nbsp;Relativo** – notas (1 – 9) atribuídas pelo *Desenvolvedor*. 

**Custo&nbsp;(%)** e **Risco&nbsp;(%)** – valores normalizados. 

**Prioridade** – razão entre Valor (%) e o esforço ((Custo (%) × Custo Relativo) + (Risco (%) × Risco Relativo)).


---

### Requisitos Funcionais


*Tabela 3: Requisitos Funcionais identificados para o Celular Seguro.*

| **ID (RFx)** | **Descrição do Requisito Funcional** |
|--------------|---------------------------------------|
| <a href="../../documento-elicitacao/Questionario/">Q01</a> | O aplicativo deve permitir localizar o celular perdido. |
| <a href="../../documento-elicitacao/Questionario/">Q02</a> | O aplicativo deve tornar visível e acessível a opção de registro de boletim de ocorrência. |
| <a href="../../documento-elicitacao/Questionario/">Q06</a> | O aplicativo deve notificar o usuário em caso de atividade suspeita relacionada ao dispositivo. |
| <a href="../../documento-elicitacao/Observacao/">OBS03</a> | Existe a funcionalidade de redefinir a senha via e-mail. |
| <a href="/documento-elicitacao/Observacao/">OBS06</a> | O sistema disponibiliza uma aba que te leva a um pdf com um tutorial do aplicativo. |
| <a href="/documento-elicitacao/Observacao/">OBS09</a> | Ao tentar emitir um alerta de roubo, o sistema exibe uma janela pop-up solicitando a confirmação do usuário antes de prosseguir com a ação. |
| <a href="/documento-elicitacao/Observacao/">OBS10</a> | 	Pelo MEI do aparelho, é possível consultar o status do celular e saber se ele se encontra como um celular roubado, furtado, etc ( irregular). |
| <a href="../../documento-elicitacao/Brainstorming/">BS02</a> | Apagar todos os dados do dispositivo |
| <a href="../../documento-elicitacao/Brainstorming/">BS08</a> | Bloquear chip por integração direta com a operadora |
| <a href="../../documento-elicitacao/Brainstorming/">BS15</a> | Botão de “bloqueio rápido” sempre acessível na tela principal. |
| <a href="../../documento-elicitacao/Brainstorming/">BS17</a> | Efetuar backup automático de contatos, fotos e mensagens antes do bloqueio remoto. |
| <a href="../../documento-elicitacao/Brainstorming/">BS23</a> | Definir “dispositivo de confiança” para controle remoto secundário. |

*Legenda:* 

**ID (RFx)** – identificador sequencial de Requisito Funcional. 

**Descrição** – definição concisa da funcionalidade exigida.


---

### Requisitos Não Funcionais



*Tabela 4: Requisitos Não Funcionais identificados para o Celular Seguro.*

| **ID (RNFx)** | **Descrição do Requisito Não Funcional** |
|--------------|-------------------------------------------|
| <a href="/documento-elicitacao/Observacao/">OBS15</a> | O aplicativo apresenta uma interface amigável e intuitiva, com ícones bem definidos e menus acessíveis.|
|  <a href="/documento-elicitacao/Observacao/">OBS16</a> | As páginas carregam em até 2 segundos em conexões padrão 4G. |
| <a href="/documento-elicitacao/Observacao/">OBS18</a> | O aplicativo é acessível para pessoas com deficiência visual (uso de leitor de tela, contraste, tamanho da fonte). |
| <a href="/documento-elicitacao/Observacao/">OBS21</a> | O aplicativo está disponível 24/7, com raras quedas detectadas durante a observação. |
| <a href="../../documento-elicitacao/Questionario/">Q09</a> | O aplicativo deve funcionar de maneira estável e confiável em momentos de emergência. |
| <a href="../../documento-elicitacao/Questionario/">Q19</a> | O aplicativo deve oferecer um modo escuro (dark mode) para maior conforto visual. |
| <a href="../../documento-elicitacao/Brainstorming/">BS37</a> | Linguagem simples sem jargões técnicos |
| <a href="../../documento-elicitacao/Brainstorming/">BS48</a> | Autenticação multifator (2 FA) com fallback via SMS. |
| <a href="../../documento-elicitacao/Brainstorming/">BS50</a> | Política de privacidade clara e facilmente acessível dentro do app |
| <a href="../../documento-elicitacao/Brainstorming/">BS52</a> | Central de ajuda acessível offline e online |
| <a href="../../documento-elicitacao/Brainstorming/">BS54</a> | Monitoramento de tentativas de acesso não autorizado com alertas automáticos. |
| <a href="../../documento-elicitacao/Brainstorming/">BS56</a> | Sincronização de estado entre app e portal em menos de 5 segundos |
| <a href="../../documento-elicitacao/Brainstorming/">BS60</a> | Atualizações automáticas de segurança e correções de vulnerabilidades em até 24 horas. |


*Legenda:* 

**ID (RNFx)** – identificador sequencial de Requisito Não Funcional. 

**Descrição** – detalhamento do critério de qualidade ou restrição.


---

## Legenda Geral

- **RF** – Requisito Funcional: descreve **o que** o sistema deve fazer para atender às necessidades do usuário ou do negócio.
- **RNF** – Requisito Não Funcional: descreve **como** o sistema deve se comportar ou quais restrições de qualidade deve obedecer (usabilidade, desempenho, segurança, etc.).

---

## Bibliografia

> <a id="FTF1Ref"></a> FIRST things first: Setting requirement priorities. In: **WIEGERS, K. E.; BEATTY, J.** *Software Requirements*. 3. ed. Microsoft Press, 2013. cap. 16, p. 313‑329.

---

## Histórico de Versões

| Versão | Data de Produção | Descrição da Alteração                                                                 | Autor(es)                                                                                                                      | Revisor(es)                                                                                                                  | Data de Revisão |
| :----: | :--------------: | :-------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------: | :-------------: |
| 1.0    | 01/05/2025       | Criação do documento FTF para Celular Seguro | <a style="color:gold;" href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>                               | <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a> | 01/05/2025     |                                            | 23/04/2025     |
| 1.1    | 04/05/2025       | Análise de valores de custo, valor e risco | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a>                               | <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a> | 04/05/2025     |                                            | 04/05/2025     |
| 1.2   | 08/05/2025| Padronização do Histórico de Versões| <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a>| <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a>| 08/05/2025|
