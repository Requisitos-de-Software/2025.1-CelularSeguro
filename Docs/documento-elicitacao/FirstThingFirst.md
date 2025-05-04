# First Things First

## Introdução

A priorização de requisitos é fundamental para garantir que funcionalidades críticas sejam desenvolvidas primeiro. No projeto Celular Seguro, utilizamos a técnica First Things First para organizar e priorizar os requisitos com base em benefício, penalidade, custo e risco. Essa abordagem ajuda a alinhar o desenvolvimento com os objetivos de segurança, usabilidade e acessibilidade do aplicativo.

## Metodologia

As pessoas que participaram da aplicação da técnica _First Things First_ (FTF) estão listadas na **Tabela 1**.

- **Mediador** – Conduz a sessão e apresenta os requisitos.
- **Cliente** – Atribui notas de **benefício** e **penalidade**.
- **Desenvolvedor** – Atribui notas de **custo** e **risco**.

<center>

*Tabela 1: Participantes da técnica First Things First.*

| **Nome**            | **Função**     |
|---------------------|----------------|
| Arthur Carvalho     | Mediador       |
| Usuário Representante | Cliente        |
| Gabriel Lima | Desenvolvedor |


</center>

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

<p align="center" style="font-size: 18px;">prioridade = valor(%) / (custo(%) × 1 + risco(%) × 0,5)</p>

6. Ordenação dos requisitos em ordem decrescente de prioridade.

### Pesos relativos

- Benefício: **2**  
- Penalidade: **1**  
- Custo: **1**  
- Risco: **0,5**

---

## Resultado da Priorização

<center>

*Tabela 2: Resultado da priorização dos requisitos.*

| **Funcionalidade** | **Benefício&nbsp;Relativo** | **Penalidade&nbsp;Relativa** | **Valor&nbsp;total** | **Valor&nbsp;(%)** | **Custo&nbsp;Relativo** | **Custo&nbsp;(%)** | **Risco&nbsp;Relativo** | **Risco&nbsp;(%)** | **Prioridade** |
|--------------------|----------------------------|-----------------------------|----------------------|--------------------|------------------------|--------------------|-------------------------|--------------------|---------------|
| Q01 | 9 | 9 | 27 | 4,53 | 1 | 1,35 | 1 | 1,16 | 2,344 |
| Q02 | 9 | 9 | 27 | 4,53 | 1 | 1,35 | 1 | 1,16 | 2,344 |
| OBS15 | 8 | 8 | 24 | 4,03 | 1 | 1,35 | 1 | 1,16 | 2,083 |
| OBS06 | 7 | 7 | 21 | 3,52 | 1 | 1,35 | 1 | 1,16 | 1,823 |
| OBS09 | 9 | 9 | 27 | 4,53 | 1 | 1,35 | 3 | 3,49 | 1,463 |
| OBS10 | 5 | 5 | 15 | 2,52 | 1 | 1,35 | 1 | 1,16 | 1,302 |
| BS15 | 9 | 9 | 27 | 4,53 | 2 | 2,70 | 2 | 2,33 | 1,172 |
| BS23 | 9 | 9 | 27 | 4,53 | 2 | 2,70 | 2 | 2,33 | 1,172 |
| BS17 | 9 | 9 | 27 | 4,53 | 2 | 2,70 | 2 | 2,33 | 1,172 |
| BS08 | 8 | 8 | 24 | 4,03 | 2 | 2,70 | 2 | 2,33 | 1,042 |
| BS02 | 9 | 7 | 25 | 4,19 | 2 | 2,70 | 4 | 4,65 | 0,834 |
| OBS16 | 9 | 9 | 27 | 4,53 | 2 | 2,70 | 6 | 6,98 | 0,732 |
| OBS18 | 8 | 8 | 24 | 4,03 | 3 | 4,05 | 3 | 3,49 | 0,694 |
| Q09 | 5 | 5 | 15 | 2,52 | 2 | 2,70 | 2 | 2,33 | 0,651 |
| BS37 | 7 | 7 | 21 | 3,52 | 3 | 4,05 | 3 | 3,49 | 0,608 |
| BS48 | 9 | 9 | 27 | 4,53 | 4 | 5,41 | 4 | 4,65 | 0,586 |
| BS50 | 9 | 9 | 27 | 4,53 | 4 | 5,41 | 4 | 4,65 | 0,586 |
| BS52 | 9 | 9 | 27 | 4,53 | 4 | 5,41 | 4 | 4,65 | 0,586 |
| Q06 | 6 | 5 | 17 | 2,85 | 3 | 4,05 | 3 | 3,49 | 0,492 |
| OBS03 | 9 | 9 | 27 | 4,53 | 5 | 6,76 | 5 | 5,81 | 0,469 |
| BS60 | 9 | 9 | 27 | 4,53 | 5 | 6,76 | 5 | 5,81 | 0,469 |
| Q19 | 7 | 8 | 22 | 3,69 | 5 | 6,76 | 6 | 6,98 | 0,360 |
| OBS21 | 7 | 5 | 19 | 3,19 | 5 | 6,76 | 6 | 6,98 | 0,311 |
| BS54 | 9 | 9 | 27 | 4,53 | 7 | 9,46 | 9 | 10,47 | 0,308 |
| BS56 | 6 | 6 | 18 | 3,02 | 6 | 8,11 | 6 | 6,98 | 0,260 |

</center>

*Legenda:* 

**Funcionalidade** – código do requisito priorizado (**RFx** para funcionais, **RNFx** para não funcionais). 

**Benefício&nbsp;Relativo** e **Penalidade&nbsp;Relativa** – notas (1 – 9) atribuídas pelo *Cliente*. 

**Valor&nbsp;total** – Benefício × 2 + Penalidade × 1. 

**Valor&nbsp;(%)** – valor total normalizado. 

**Custo&nbsp;Relativo** e **Risco&nbsp;Relativo** – notas (1 – 9) atribuídas pelo *Desenvolvedor*. 

**Custo&nbsp;(%)** e **Risco&nbsp;(%)** – valores normalizados. 

**Prioridade** – razão entre Valor (%) e o esforço ((Custo (%) × 1) + (Risco (%) × 0,5)).


---

### Requisitos Funcionais

<center>

*Tabela 3: Requisitos Funcionais identificados para o Celular Seguro.*

| **ID (RFx)** | **Descrição do Requisito Funcional** |
|--------------|---------------------------------------|
| <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">Q01</a> | O aplicativo deve permitir localizar o celular perdido. |
| <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">Q02</a> | O aplicativo deve tornar visível e acessível a opção de registro de boletim de ocorrência. |
| <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">Q06</a> | O aplicativo deve notificar o usuário em caso de atividade suspeita relacionada ao dispositivo. |
| <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">OBS03</a> | Existe a funcionalidade de redefinir a senha via e-mail. |
| <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">OBS06</a> | O sistema disponibiliza uma aba que te leva a um pdf com um tutorial do aplicativo. |
| <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">OBS09</a> | Ao tentar emitir um alerta de roubo, o sistema exibe uma janela pop-up solicitando a confirmação do usuário antes de prosseguir com a ação. |
| <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">OBS10</a> | 	Pelo MEI do aparelho, é possível consultar o status do celular e saber se ele se encontra como um celular roubado, furtado, etc ( irregular). |
| <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">BS02</a> | Apagar todos os dados do dispositivo |
| <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">BS08</a> | Bloquear chip por integração direta com a operadora |
| <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">BS15</a> | Botão de “bloqueio rápido” sempre acessível na tela principal. |
| <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">BS17</a> | Efetuar backup automático de contatos, fotos e mensagens antes do bloqueio remoto. |
| <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">BS23</a> | Definir “dispositivo de confiança” para controle remoto secundário. |

</center>

*Legenda:* 

**ID (RFx)** – identificador sequencial de Requisito Funcional. 

**Descrição** – definição concisa da funcionalidade exigida.


---

### Requisitos Não Funcionais

<center>

*Tabela 4: Requisitos Não Funcionais identificados para o Celular Seguro.*

| **ID (RNFx)** | **Descrição do Requisito Não Funcional** |
|--------------|-------------------------------------------|
| <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">OBS15</a> | O aplicativo apresenta uma interface amigável e intuitiva, com ícones bem definidos e menus acessíveis.|
|  <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">OBS16</a> | As páginas carregam em até 2 segundos em conexões padrão 4G. |
| <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">OBS18</a> | O aplicativo é acessível para pessoas com deficiência visual (uso de leitor de tela, contraste, tamanho da fonte). |
| <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">OBS21</a> | O aplicativo está disponível 24/7, com raras quedas detectadas durante a observação. |
| <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">Q09</a> | O aplicativo deve funcionar de maneira estável e confiável em momentos de emergência. |
| <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">Q19</a> | O aplicativo deve oferecer um modo escuro (dark mode) para maior conforto visual. |
| <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">BS37</a> | Linguagem simples sem jargões técnicos |
| <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">BS48</a> | Autenticação multifator (2 FA) com fallback via SMS. |
| <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">BS50</a> | Política de privacidade clara e facilmente acessível dentro do app |
| <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">BS52</a> | Central de ajuda acessível offline e online |
| <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">BS54</a> | Monitoramento de tentativas de acesso não autorizado com alertas automáticos. |
| <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">BS56</a> | Sincronização de estado entre app e portal em menos de 5 segundos |
| <a href="../../Docs/documento-elicitacao/AnalisedeDocumentos.md">BS60</a> | Atualizações automáticas de segurança e correções de vulnerabilidades em até 24 horas. |

</center>

*Legenda:* 

**ID (RNFx)** – identificador sequencial de Requisito Não Funcional. 

**Descrição** – detalhamento do critério de qualidade ou restrição.


---

## Legenda Geral

- **RF** – Requisito Funcional: descreve **o que** o sistema deve fazer para atender às necessidades do usuário ou do negócio.
- **RNF** – Requisito Não Funcional: descreve **como** o sistema deve se comportar ou quais restrições de qualidade deve obedecer (usabilidade, desempenho, segurança, etc.).

---

## Referência Bibliográfica

> <a id="FTF1Ref"></a> FIRST things first: Setting requirement priorities. In: **WIEGERS, K. E.; BEATTY, J.** *Software Requirements*. 3. ed. Microsoft Press, 2013. cap. 16, p. 313‑329.

---

## Histórico de Versões

| Versão | Data de Produção | Descrição da Alteração                                                                 | Autor(es)                                                                                                                      | Revisor(es)                                                                                                                  | Data de Revisão |
| :----: | :--------------: | :-------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------: | :-------------: |
| 1.0    | 01/05/2025       | Criação do documento FTF para Celular Seguro | <a style="color:gold;" href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>                               | <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a> | 01/05/2025     |                                            | 23/04/2025     |