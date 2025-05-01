# First Things First

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
| Equipe de Desenvolvimento | Desenvolvedor |

*Legenda:* **Nome** – participante da técnica. **Função** – papel desempenhado na priorização.

</center>

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
| RF12 | 9 | 9 | 27 | 4,53 | 1 | 1,35 | 1 | 1,16 | 2,344 |
| RNF7 | 9 | 9 | 27 | 4,53 | 1 | 1,35 | 1 | 1,16 | 2,344 |
| RNF2 | 8 | 8 | 24 | 4,03 | 1 | 1,35 | 1 | 1,16 | 2,083 |
| RNF12 | 7 | 7 | 21 | 3,52 | 1 | 1,35 | 1 | 1,16 | 1,823 |
| RF9 | 9 | 9 | 27 | 4,53 | 1 | 1,35 | 3 | 3,49 | 1,463 |
| RF10 | 5 | 5 | 15 | 2,52 | 1 | 1,35 | 1 | 1,16 | 1,302 |
| RF4 | 9 | 9 | 27 | 4,53 | 2 | 2,70 | 2 | 2,33 | 1,172 |
| RNF4 | 9 | 9 | 27 | 4,53 | 2 | 2,70 | 2 | 2,33 | 1,172 |
| RNF6 | 9 | 9 | 27 | 4,53 | 2 | 2,70 | 2 | 2,33 | 1,172 |
| RNF11 | 8 | 8 | 24 | 4,03 | 2 | 2,70 | 2 | 2,33 | 1,042 |
| RF3 | 9 | 7 | 25 | 4,19 | 2 | 2,70 | 4 | 4,65 | 0,834 |
| RF2 | 9 | 9 | 27 | 4,53 | 2 | 2,70 | 6 | 6,98 | 0,732 |
| RNF13 | 8 | 8 | 24 | 4,03 | 3 | 4,05 | 3 | 3,49 | 0,694 |
| RF7 | 5 | 5 | 15 | 2,52 | 2 | 2,70 | 2 | 2,33 | 0,651 |
| RNF9 | 7 | 7 | 21 | 3,52 | 3 | 4,05 | 3 | 3,49 | 0,608 |
| RF5 | 9 | 9 | 27 | 4,53 | 4 | 5,41 | 4 | 4,65 | 0,586 |
| RNF1 | 9 | 9 | 27 | 4,53 | 4 | 5,41 | 4 | 4,65 | 0,586 |
| RNF3 | 9 | 9 | 27 | 4,53 | 4 | 5,41 | 4 | 4,65 | 0,586 |
| RF8 | 6 | 5 | 17 | 2,85 | 3 | 4,05 | 3 | 3,49 | 0,492 |
| RF1 | 9 | 9 | 27 | 4,53 | 5 | 6,76 | 5 | 5,81 | 0,469 |
| RNF10 | 9 | 9 | 27 | 4,53 | 5 | 6,76 | 5 | 5,81 | 0,469 |
| RNF5 | 7 | 8 | 22 | 3,69 | 5 | 6,76 | 6 | 6,98 | 0,360 |
| RF6 | 7 | 5 | 19 | 3,19 | 5 | 6,76 | 6 | 6,98 | 0,311 |
| RNF8 | 9 | 9 | 27 | 4,53 | 7 | 9,46 | 9 | 10,47 | 0,308 |
| RF11 | 6 | 6 | 18 | 3,02 | 6 | 8,11 | 6 | 6,98 | 0,260 |

*Legenda:* **Funcionalidade** – código do requisito priorizado (**RFx** para funcionais, **RNFx** para não funcionais). **Benefício&nbsp;Relativo** e **Penalidade&nbsp;Relativa** – notas (1 – 9) atribuídas pelo *Cliente*. **Valor&nbsp;total** – Benefício × 2 + Penalidade × 1. **Valor&nbsp;(%)** – valor total normalizado. **Custo&nbsp;Relativo** e **Risco&nbsp;Relativo** – notas (1 – 9) atribuídas pelo *Desenvolvedor*. **Custo&nbsp;(%)** e **Risco&nbsp;(%)** – valores normalizados. **Prioridade** – razão entre Valor (%) e o esforço ((Custo (%) × 1) + (Risco (%) × 0,5)).

</center>

---

### Requisitos Funcionais

<center>

*Tabela 3: Requisitos Funcionais identificados para o Celular Seguro.*

| **ID (RFx)** | **Descrição do Requisito Funcional** |
|--------------|---------------------------------------|
| RF1 | O aplicativo permite realizar a compra do ingresso. |
| RF2 | O aplicativo permite o cadastro e o login do usuário. |
| RF3 | O aplicativo permite excluir cadastro. |
| RF4 | O aplicativo permite cancelar compras. |
| RF5 | O aplicativo possui um mecanismo de busca. |
| RF6 | O aplicativo dá sugestões de eventos com base no histórico de buscas do usuário. |
| RF7 | O aplicativo notifica o usuário sobre eventos, quando permitido. |
| RF8 | O usuário é capaz de filtrar eventos. |
| RF9 | O usuário é capaz de acessar as informações do evento. |
| RF10 | O usuário é capaz de mudar o idioma do app. |
| RF11 | O usuário é capaz de acessar a assistente virtual. |
| RF12 | O usuário é capaz de compartilhar o evento. |

*Legenda:* **ID (RFx)** – identificador sequencial de Requisito Funcional. **Descrição** – definição concisa da funcionalidade exigida.

</center>

---

### Requisitos Não Funcionais

<center>

*Tabela 4: Requisitos Não Funcionais identificados para o Celular Seguro.*

| **ID (RNFx)** | **Descrição do Requisito Não Funcional** |
|--------------|-------------------------------------------|
| RNF1 | Deve apresentar eventos de forma personalizada, de acordo com a atividade do usuário. |
| RNF2 | O usuário deve acessar data, local e preço do ingresso em no máximo 2 cliques. |
| RNF3 | O usuário deve acessar um tópico de ajuda em até 3 cliques. |
| RNF4 | Deve exibir aviso de início/fim de venda de ingressos em formato de notificação acessível com 1 clique. |
| RNF5 | Deve oferecer atendimento especial para idosos/deficientes. |
| RNF6 | Deve oferecer login seguro com credenciais do usuário. |
| RNF7 | Deve possuir área para reportar erros de funcionamento. |
| RNF8 | Deve proteger os dados de cadastro e compra dos usuários. |
| RNF9 | Deve exibir eventos relevantes ao usuário. |
| RNF10 | As notificações devem ser fornecidas em tempo hábil. |
| RNF11 | O sistema deve indexar e pesquisar palavras-chave rapidamente. |
| RNF12 | O aplicativo deve permitir compra de ingressos em menos de três telas. |
| RNF13 | O sistema deve solucionar problemas relacionados à compra de ingressos. |

*Legenda:* **ID (RNFx)** – identificador sequencial de Requisito Não Funcional. **Descrição** – detalhamento do critério de qualidade ou restrição.

</center>

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