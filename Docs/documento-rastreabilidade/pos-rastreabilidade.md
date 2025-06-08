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

| <span >Artefato Analisado</span> | Classificação do Artefato Analisado |
| :--------------------------------------------------: | :---------------------------------: |
|                     Tipos de Elo                     |       Artefatos Relacionados        |
|                      Satisfação                      |                  -                  |
|                       Recurso                        |                  -                  |
|                    Representação                     |                  -                  |
|                       Alocado                        |                  -                  |
|                      Agregação                       |                  -                  |

<sub>Fonte: (TORANZO, 2002).</sub>

### Rastreabilidade

As tabelas a seguir detalham os elos identificados entre os artefatos e os requisitos, tanto funcionais quanto não funcionais, implementados ou não pela Bilheteria Digital. 

### RF01

<details>

<summary> O aplicativo filtra os eventos por Estado e por Município. </summary>

<center>

Tabela 2 - RF01

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF01</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade">Especificação Suplementar USA03</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia">NFR Eficiência</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-4">Cenário 04</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#requisitos-nao-funcionais">Requisitos NFR02 e NFR03</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#confiabilidade">Especificação Suplementar CON01 e CON02</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://www.figma.com/proto/CSsRpoXBR0BWWojN1ZrDn0/Protótipo-de-Alta-FIdelidade?page-id=0%3A1&amp;type=design&amp;node-id=107-1118&amp;viewport=29390%2C34193%2C3.02&amp;scaling=min-zoom&amp;starting-point-node-id=107%3A1118&amp;show-proto-sidebar=1">Protótipo de Alta Fidelidade:</a><br><img src="../../assets/rastreabilidade/RF01.gif" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos">Léxico 01</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#metodologia">Épico 1 - Feature 1</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-01-usabilidade">NFR Usabilidade</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso">Casos de Uso UC01</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-4">Cenário 04</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us01">História de Usuário US01</a> <br> Requisitos: <a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS01</a>, <a href="../../elicitacao/elicitacao/tecnicas/brainstorming/#anchor_BS">BS08</a> e <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS01</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF02

<details>

<summary> O aplicativo filtra os eventos por data e por horário. </summary>

<center>

Tabela 3 - RF02

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF02</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade">Especificação Suplementar USA04</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia">NFR Eficiência</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-2">Cenário 02</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#requisitos-nao-funcionais">Requisitos NFR02 e NFR03</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#confiabilidade">Especificação Suplementar CON01 e CON02</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://www.figma.com/proto/CSsRpoXBR0BWWojN1ZrDn0/Protótipo-de-Alta-FIdelidade?page-id=0%3A1&amp;type=design&amp;node-id=107-1118&amp;viewport=29390%2C34193%2C3.02&amp;scaling=min-zoom&amp;starting-point-node-id=107%3A1118&amp;show-proto-sidebar=1">Protótipo de Alta Fidelidade:</a><br><img src="../../assets/rastreabilidade/RF02.gif" height="500" width="250"> <br>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos">Léxico 01</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#metodologia">Épico 1 - Feature 1</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-01-usabilidade">NFR Usabilidade</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso">Casos de Uso UC01</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us04">História de Usuário US04</a> <br> Requisitos: <a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS02</a> e <a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q03</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF03

<details>

<summary> O aplicativo filtra os eventos por idade mínima de entrada. </summary>

<center>

Tabela 4 - RF03

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF03</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade">Especificação Suplementar USA04</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia">NFR Eficiência</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-3">Cenário 03</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#requisitos-nao-funcionais">Requisitos NFR02 e NFR03</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#confiabilidade">Especificação Suplementar CON01 e CON02</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://www.figma.com/proto/CSsRpoXBR0BWWojN1ZrDn0/Protótipo-de-Alta-FIdelidade?page-id=0%3A1&amp;type=design&amp;node-id=107-1118&amp;viewport=29390%2C34193%2C3.02&amp;scaling=min-zoom&amp;starting-point-node-id=107%3A1118&amp;show-proto-sidebar=1">Protótipo de Alta Fidelidade:</a><br><img src="../../assets/rastreabilidade/RF03.gif" height="500" width="250"> <br>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos">Léxico 01</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#metodologia">Épico 1 - Feature 2</a>  <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-01-usabilidade">NFR Usabilidade</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso">Casos de Uso UC01</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS03</a> e <a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q02</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF04

<details>

<summary> O aplicativo permite realizar a compra do ingresso. </summary>

<center>

Tabela 5 - RF04

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF04</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade">Especificação Suplementar USA04</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#cartoes-de-especificacao">Cartão de Especificação 3</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade">Especificação Suplementar USA05</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><img src="../../assets/rastreabilidade/RF04.gif" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-5">Cenário 05</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us07">História de Usuário US07</a> <br> Requisitos: <a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS04</a>, <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS03</a>, <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS10</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF05

<details>

<summary> O aplicativo permite o cadastro e o login do usuário. </summary>

<center>

Tabela 6 - RF05

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF05</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us09">História de Usuário US09</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us25">História de Usuário US25</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us28">História de Usuário US28</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us27">História de Usuário US27</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#metodologia">Épico 3 - Feature 6</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><font><figure markdown><img src="../../assets/rastreabilidade/RF05.gif" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS05</a>, <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS01, <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS02</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF06

<details>

<summary> O aplicativo permite excluir cadastro. </summary>

<center>

Tabela 7 - RF06

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF06</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><font><figure markdown><img src="../../assets/rastreabilidade/RF06.gif" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito:  <a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS06</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF07

<details>

<summary>O aplicativo permite cadastrar métodos de pagamento. </summary>

<center>

Tabela 8 - RF07

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF07</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade">Especificação Suplementar USA05</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#confiabilidade">Especificação Suplementar CON03</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso">Casos de Uso UC03</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-5">Cenário 05</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#metodologia">Épico 2 - Feature 4</a> <br> <font><figure markdown><img src="../assets/rastreabilidade/RF07.jpg" alt="">{: style=&quot;height:500px;width:250px&quot;}</td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS07</a>, <a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q08, <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS15</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF08

<details>

<summary>O aplicativo permite cancelar compras.</summary>

<center>

Tabela 9 - RF08

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF08</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us27">História de Usuário US20</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#metodologia">Épico 5 - Feature 11</a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS08</a>, <a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q09</a>, <a href="../../elicitacao/tecnicas/observacao/#anchor_IS">OBS12</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF09

<details>

<summary>O aplicativo possui um mecanismo de busca.</summary>

<center>

Tabela 10 - RF09

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF09</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade">Especificação Suplementar USA04</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos">Léxico 01</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l03-evento-com-tags">Léxico 02</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-1">Cenário 01</a> <br> <a href="https://requisitos-de-software.github.io/2023.2-BilheteriaDigital/modelagem/cenarios/#cenario-2">Cenário 02</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-3">Cenário 03</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-4">Cenário 04</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso">Casos de Uso UC01</a> <br> <font><figure markdown><img src="../../assets/rastreabilidade/RF09.gif" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS09</a>, <a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q01</a>, <a href="../../elicitacao/tecnicas/brainstorm/#anchor_BS">BS04</a>, <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS02</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF10

<details>

<summary>O aplicativo filtra eventos por categorias.</summary>

<center>

Tabela 11 - RF10

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF10</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade">Especificação Suplementar USA04</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia">NFR Eficiência</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-1">Cenário 01</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#requisitos-nao-funcionais">Requisitos NFR02 e NFR03</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#confiabilidade">Especificação Suplementar CON01 e CON02</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://www.figma.com/proto/CSsRpoXBR0BWWojN1ZrDn0/Protótipo-de-Alta-FIdelidade?page-id=0%3A1&amp;type=design&amp;node-id=107-1118&amp;viewport=29390%2C34193%2C3.02&amp;scaling=min-zoom&amp;starting-point-node-id=107%3A1118&amp;show-proto-sidebar=1">Protótipo de Alta Fidelidade:</a><br><img src="../../assets/rastreabilidade/RF10.gif" height="500" width="250"> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us02">História de Usuário US02</a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos">Léxico 01</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#metodologia">Épico 1 - Feature 2</a>  <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-01-usabilidade">NFR Usabilidade</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso">Casos de Uso UC01</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q04</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF11

<details>

<summary>O aplicativo dá sugestões de eventos com base no histórico de buscas do usuário.</summary>

<center>

Tabela 12 - RF11

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF11</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade">Especificação Suplementar USA06</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia">NFR Eficiência</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#requisitos-nao-funcionais">Requisitos NFR02 e NFR03</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#confiabilidade">Especificação Suplementar CON01 e CON02</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l02-sugestoes-de-eventos">Léxico 02</a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos">Léxico 01</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-01-usabilidade">NFR Usabilidade</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso">Casos de Uso UC02</a> <br> Requisitos: <a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q05</a> e <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS11</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF12

<details>

<summary>O aplicativo tem palavras-chave ou tags associadas a eventos para facilitar a busca.</summary>

<center>

Tabela 13 - RF12

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF12</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#desempenho">Especificação Suplementar DES01</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia">NFR Eficiência</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#requisitos-nao-funcionais">Requisitos NFR02 e NFR03</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#confiabilidade">Especificação Suplementar CON01 e CON02</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l03-evento-com-tags">Léxico 03</a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-01-usabilidade">NFR Usabilidade</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso">Casos de Uso UC02</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q06</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF13

<details>

<summary>O aplicativo notifica usuário sobre eventos, quando permitido.</summary>

<center>

Tabela 14 - RF13

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF13</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade">Especificação Suplementar USA06</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#desempenho">Especificação Suplementar DES01 e DES05</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia">NFR Eficiência</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso">Casos de Uso UC02</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#requisitos-nao-funcionais">Requisitos NFR02 e NFR03</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#confiabilidade">Especificação Suplementar CON01 e CON02</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l04-notificar-eventos">Léxico 04</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us22">Histórias de Usuário US22 e US23</a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-01-usabilidade">NFR Usabilidade</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#metodologia">Épico 2 - Feature 3</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l02-sugestoes-de-eventos">Léxico 02</a> <br> Requisitos: <a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q07</a> e <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS06</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF14

<details>

<summary>O usuário é capaz de filtrar eventos.</summary>

<center>

Tabela 15 - RF14

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF14</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#cartoes-de-especificacao">Cartão de Especificação 5</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://www.figma.com/proto/CSsRpoXBR0BWWojN1ZrDn0/Protótipo-de-Alta-FIdelidade?page-id=0%3A1&amp;type=design&amp;node-id=107-1118&amp;viewport=29390%2C34193%2C3.02&amp;scaling=min-zoom&amp;starting-point-node-id=107%3A1118&amp;show-proto-sidebar=1">Protótipo de Alta Fidelidade:</a><br><img src="../../assets/rastreabilidade/RF14P.gif" height="500" width="250"> <br><a href="https://play.google.com/store/apps/details?id=com.bilheteriadigital.mobile&hl=pt_BR&gl=US">Aplicativo Bilheteria Digital:</a><br> <font><figure markdown><img src="../../assets/rastreabilidade/RF14.gif" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso">Casos de Uso UC01</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos">Léxico 01</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l03-evento-com-tags">Léxico 02</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-1">Cenário 01</a> <br> <a href="https://requisitos-de-software.github.io/2023.2-BilheteriaDigital/modelagem/cenarios/#cenario-2">Cenário 02</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-3">Cenário 03</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-4">Cenário 04</a> <br> Requisito: <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS05</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF15

<details>

<summary>O usuário pode salvar os dados do cartão no app.</summary>

<center>

Tabela 16 - RF15

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF15</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade">Especificação Suplementar USA05</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#confiabilidade">Especificação Suplementar CON03</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-5">Cenário 05</a> <br> <font><figure markdown><img src="../../assets/rastreabilidade/RF15.gif" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us17">Histórias de Usuário US17</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#metodologia">Épico 3 - Feature 6</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS07</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF16

<details>

<summary>O usuário pode fornecer sua localização.</summary>

<center>

Tabela 17 - RF16

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF16</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso">Casos de Uso UC01</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-4">Cenário 04</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos">Léxico 01</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS09</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF17

<details>

<summary>O usuário pode acessar o calendário de eventos.</summary>

<center>

Tabela 18 - RF17

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF17</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#desempenho">Especificação Suplementar DES01</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso">Casos de Uso UC01</a> <br>  <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#metodologia">Épico 1 - Feature 1</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://www.figma.com/proto/CSsRpoXBR0BWWojN1ZrDn0/Protótipo-de-Alta-FIdelidade?page-id=0%3A1&amp;type=design&amp;node-id=107-1118&amp;viewport=29390%2C34193%2C3.02&amp;scaling=min-zoom&amp;starting-point-node-id=107%3A1118&amp;show-proto-sidebar=1">Protótipo de Alta Fidelidade:</a><br><img src="../../assets/rastreabilidade/RF17P.gif" height="500" width="250"><br><a href="https://play.google.com/store/apps/details?id=com.bilheteriadigital.mobile&hl=pt_BR&gl=US">Aplicativo Bilheteria Digital:</a><br><font><figure markdown><img src="../../assets/rastreabilidade/RF17.gif" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-2">Cenário 02</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos">Léxico 01</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us04">Histórias de Usuário US04</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS10</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF18

<details>

<summary>O usuário pode responder a pesquisa de perfil sobre seus gostos.</summary>

<center>

Tabela 19 - RF18

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF18</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l02-sugestoes-de-eventos">Léxico 02</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso">Casos de Uso UC04</a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#requisitos-nao-funcionais">NFR08</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#metodologia">Épico 2 - Feature 4</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us21">Histórias de Usuário US21</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS12</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF19

<details>

<summary>O usuário consegue acessar as informações do evento.</summary>

<center>

Tabela 20 - RF19

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF19</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#confiabilidade">Especificação Suplementar CON02</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso">Casos de Uso UC01</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l04-notificar-eventos">Léxico 04</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#cartoes-de-especificacao">Cartão de Especificação 2</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us13">Histórias de Usuário US13</a> <br> <font><figure markdown><img src="../../assets/rastreabilidade/RF19.gif" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us29">Histórias de Usuário US29</a> <br> Requisito: <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS13</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF20

<details>

<summary>O usuário é capaz de acessar as atrações do evento.</summary>

<center>

Tabela 21 - RF20

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF20</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS14</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF21

<details>

<summary>O usuário possui acesso a pré-venda.</summary>

<center>

Tabela 22 - RF21

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF21</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS16</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF22

<details>

<summary>O usuário recebe a cópia do ingresso por e-mail.</summary>

<center>

Tabela 23 - RF22

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF22</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade">Especificação Suplementar USA03</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us18">Histórias de Usuário US18</a> <br> <font><figure markdown><img src="../../assets/rastreabilidade/RF22.jpg" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#metodologia">Épico 4 - Feature 9</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us14">Histórias de Usuário US14</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS17</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF23

<details>

<summary>O usuário é capaz de conectar uma carteira digital.</summary>

<center>

Tabela 24 - RF23

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF23</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade">Especificação Suplementar USA06</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#desempenho">Especificação Suplementar DES01 e DES05</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia">NFR Eficiência</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso">Casos de Uso UC03</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-5">Cenário 05</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-5">Cenário 05</a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-01-usabilidade">NFR Usabilidade</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#metodologia">Épico 2 - Feature 4</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS18</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF24

<details>

<summary>O usuário é capaz de mudar o idioma do app.</summary>

<center>

Tabela 25 - RF24

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF24</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade">Especificação Suplementar USA06</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#desempenho">Especificação Suplementar DES01 e DES05</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia">NFR Eficiência</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso">Casos de Uso UC03</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us31">História de Usuário US31</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l06-mudar-idioma">Léxico 06</a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-01-usabilidade">NFR Usabilidade</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#metodologia">Épico 3 - Feature 6</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS19</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF25

<details>

<summary>O usuário é capaz de aumentar a fonte.</summary>

<center>

Tabela 26 - RF25

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF25</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade">Especificação Suplementar USA02</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS20</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RF26

<details>

<summary>O usuário é capaz de dar zoom.</summary>

<center>

Tabela 27 - RF26

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF26</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade">Especificação Suplementar USA02</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us30">História de Usuário US30</a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS22</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/G16C'>Gabriel Campello</a>.</font>

</center>

</details>

### RF27

<details>

<summary>O usuário é capaz de acessar a assistente virtual.</summary>

<center>

Tabela 28 - RF27

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF27</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#suportabilidade">Especificação Suplementar SUP05</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario">Léxico 05</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS23</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/G16C'>Gabriel Campello</a>.</font>

</center>

</details>

### RF28

<details>

<summary>O  usuário é capaz de compartilhar o evento.</summary>

<center>

Tabela 29 - RF28

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF28</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><br> <font><figure markdown><img src="../../assets/rastreabilidade/RF28.gif" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS03</a> e <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS24</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/G16C'>Gabriel Campello</a>.</font>

</center>

</details>

### RF29

<details>

<summary>O aplicativo permite escolher a quantidade de ingressos que o usuário deseja comprar.</summary>

<center>

Tabela 30 - RF29

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF29</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us15">História de Usuário US15</a> <br> <font><figure markdown><img src="../../assets/rastreabilidade/RF29.gif" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#epico-4-seguranca">Épico 4 - Feature 9</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS04</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/G16C'>Gabriel Campello</a>.</font>

</center>

</details>

### RF30

<details>

<summary>O aplicativo permite selecionar as poltronas para pessoas idosas, crianças, obesas ou com deficiência, caso as tenha.	</summary>

<center>

Tabela 31 - RF30

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF30</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us08">História de Usuário US08</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us29">História de Usuário US29</a> <br> <font><figure markdown><img src="../../assets/rastreabilidade/RF3031.gif" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#epico-4-seguranca">Épico 4 - Feature 9</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#epico-5-padronizacao">Épico 5 - Feature 10</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS05</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/G16C'>Gabriel Campello</a>.</font>

</center>

</details>

### RF31

<details>

<summary>O aplicativo permite selecionar as poltronas especiais.</summary>

<center>

Tabela 32 - RF31

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF31</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us08">História de Usuário US08</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us29">História de Usuário US29</a> <br> <font><figure markdown><img src="../../assets/rastreabilidade/RF3031.gif" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#epico-4-seguranca">Épico 4 - Feature 9</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#epico-5-padronizacao">Épico 5 - Feature 10</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS06</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/G16C'>Gabriel Campello</a>.</font>

</center>

</details>

### RF32

<details>

<summary>Na seleção de ingresso, o aplicativo permite adicionar um cupom de desconto.</summary>

<center>

Tabela 33 - RF32

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF32</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><br> <font><figure markdown><img src="../../assets/rastreabilidade/RF32.gif" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS07</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/G16C'>Gabriel Campello</a>.</font>

</center>

</details>

### RF33

<details>

<summary>Caso o local disponibilize, o aplicativo disponibiliza uma visão prévia da poltrona.</summary>

<center>

Tabela 34 - RF33

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF33</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><br> <font><figure markdown><img src="../../assets/rastreabilidade/RF3031.gif" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS08</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/G16C'>Gabriel Campello</a>.</font>

</center>

</details>

### RF34

<details>

<summary>O aplicativo permite a doação por parte do usuário para fundações.</summary>

<center>

Tabela 35 - RF34

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF34</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><br> <font><figure markdown><img src="../../assets/rastreabilidade/RF34.gif" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS09</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/G16C'>Gabriel Campello</a>.</font>

</center>

</details>

### RF35

<details>

<summary>O aplicativo possui uma função para entrar em contato com o suporte.</summary>

<center>

Tabela 36 - RF35

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF35</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#suportabilidade">Especificação Suplementar SUPO5</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#requisitos-de-sistema-de-ajuda-e-de-documentacao-de-usuario-on-line">Especificação Suplementar RAU02</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><br> <font><figure markdown><img src="../../assets/rastreabilidade/RF35.gif" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS11</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/G16C'>Gabriel Campello</a>.</font>

</center>

</details>

### RF36

<details>

<summary>O aplicativo permite ao usuário alterar seus dados.</summary>

<center>

Tabela 37 - RF36

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF36</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#confiabilidade">Especificação Suplementar CON03</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#confiabilidade">Especificação Suplementar CON06</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#suportabilidade">Especificação Suplementar SUP07</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td> <br> <font><figure markdown><img src="../../assets/rastreabilidade/RF36.gif" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS13</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/G16C'>Gabriel Campello</a>.</font>

</center>

</details>

### RF37

<details>

<summary>O aplicativo possui uma função que auxilia na recuperação da conta do usuário.</summary>

<center>

Tabela 38 - RF37

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF37</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#suportabilidade">Especificação Suplementar SUP08</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><font><figure markdown><img src="../../assets/rastreabilidade/RF05.gif" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS14</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/G16C'>Gabriel Campello</a>.</font>

</center>

</details>

### RF38

<details>

<summary>O aplicativo possui uma função que auxilia na recuperação da conta do usuário.</summary>

<center>

Tabela 38 - RF37

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF37</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#suportabilidade">Especificação Suplementar SUP08</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><font><figure markdown><img src="../../assets/rastreabilidade/RF05.gif" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS14</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/G16C'>Gabriel Campello</a>.</font>

</center>

</details>

### RF39

<details>

<summary>O aplicativo possui uma função que auxilia na recuperação da conta do usuário.</summary>

<center>

Tabela 38 - RF37

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF37</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#suportabilidade">Especificação Suplementar SUP08</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><font><figure markdown><img src="../../assets/rastreabilidade/RF05.gif" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS14</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/G16C'>Gabriel Campello</a>.</font>

</center>

</details>

### RF40

<details>

<summary>O aplicativo possui uma função que auxilia na recuperação da conta do usuário.</summary>

<center>

Tabela 38 - RF37

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF37</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#suportabilidade">Especificação Suplementar SUP08</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><font><figure markdown><img src="../../assets/rastreabilidade/RF05.gif" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS14</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/G16C'>Gabriel Campello</a>.</font>

</center>

</details>

### RF41

<details>

<summary>O aplicativo possui uma função que auxilia na recuperação da conta do usuário.</summary>

<center>

Tabela 38 - RF37

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF37</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#suportabilidade">Especificação Suplementar SUP08</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><font><figure markdown><img src="../../assets/rastreabilidade/RF05.gif" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS14</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/G16C'>Gabriel Campello</a>.</font>

</center>

</details>

### RF42

<details>

<summary>O aplicativo possui uma função que auxilia na recuperação da conta do usuário.</summary>

<center>

Tabela 38 - RF37

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF37</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#suportabilidade">Especificação Suplementar SUP08</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><font><figure markdown><img src="../../assets/rastreabilidade/RF05.gif" height="500" width="250"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS14</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/G16C'>Gabriel Campello</a>.</font>

</center>

</details>

### RNF01

<details>

<summary>O app deve encriptar as informações do usuário.</summary>

<center>

Tabela 39 - RNF01

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF01</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#desempenho">Especificação Suplementar - CON03, CON04, CON07, CON08 e SUP08</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#epico-1-categorizar">Épico 4 - Feature 8</a> <br></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us12">História de Usuário - US11 e US24</a> <br> Requisitos: <a href="../../elicitacao/tecnicas/questionario/#anchor_QNF">Q10</a> e <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BSNF">BS31</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RNF02

<details>

<summary>O app deve fornecer eventos de forma personalizada, levando em consideração a atividade e preferências do usuário.</summary>

<center>

Tabela 40 - RNF02

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RF02</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#desempenho">Especificação Suplementar - USA01, CON02, DES01 e DES05</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://www.figma.com/proto/CSsRpoXBR0BWWojN1ZrDn0/Protótipo-de-Alta-FIdelidade?page-id=0%3A1&amp;type=design&amp;node-id=107-1118&amp;viewport=29390%2C34193%2C3.02&amp;scaling=min-zoom&amp;starting-point-node-id=107%3A1118&amp;show-proto-sidebar=1">Protótipo de Alta Fidelidade:</a><br><img src="../../assets/rastreabilidade/RNF02.gif" height="500" width="250"><br></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l02-sugestoes-de-eventos">Léxico 02</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#epico-1-categorizar">Épico 5 - Features 4 e 10</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-01-usabilidade">NFR - Usabilidade</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us12">História de Usuário - US21 e US12</a> <br> Requisitos: <a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS10</a>, <a href="../../elicitacao/tecnicas/questionario/#anchor_QNF">Q11</a>, <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BSNF">BS35</a>, <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BSNF">BS36</a> e <a href="../../elicitacao/tecnicas/observacao/#anchor_OBSNF">OBS22</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RNF03

<details>

<summary>O app deve disponibilizar todas as informações do evento em uma página.</summary>

<center>

Tabela 41 - RNF03

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RNF03</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#desempenho">Especificação Suplementar - USA01 ,CON02 e DES05</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td> <br></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia">NFR - Eficiência</a><br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#epico-1-categorizar">Épico 5 - Feature 10</a> <br></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us12">História de Usuário - US13 e US29</a> <br> Requisitos: <a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS11</a>, <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BSNF">BS25</a>, <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BSNF">BS26</a>, <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BSNF">BS27</a>, <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BSNF">BS28</a>, <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BSNF">BS29</a>, <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BSNF">BS30</a>, <a href="(../../elicitacao/tecnicas/observacao/#anchor_OBSNF">OBS15</a>&gt;) e <a href="../../elicitacao/tecnicas/observacao/#anchor_OBSNF">OBS16</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RNF04

<details>

<summary>A compra deve ser feita em no máximo 5 páginas.</summary>

<center>

Tabela 42 - RNF04

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RNF04</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#desempenho">Especificação Suplementar - USA01, USA04, USA05, USA06 e DES04</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td> <br></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia">NFR - Eficiência</a><br></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS13</a>, <a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS16</a>, <a href="../../elicitacao/tecnicas/questionario/#anchor_QNF">Q14</a>, <a href="../../elicitacao/tecnicas/observacao/#anchor_OBSNF">OBS17</a>, <a href="../../elicitacao/tecnicas/observacao/#anchor_OBSNF">OBS18</a> e <a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS14</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RNF05

<details>

<summary>O app deve permitir a resolução de problemas sem uma interação com um humano.</summary>

<center>

Tabela 43 - RNF05

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RNF05</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#desempenho">Especificação Suplementar - USA01, USA04, USA06, CON01, CON02, CON05, CON08, CON09, DES03, DES04, DES05, RAU01 e RAU04 </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS12</a>, <a href="../../elicitacao/tecnicas/questionario/#anchor_QNF">Q15</a>, <a href="../../elicitacao/tecnicas/questionario/#anchor_QNF">Q16</a>, <a href="../../elicitacao/tecnicas/observacao/#anchor_OBSNF">OBS19</a>, <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BSNF">BS33</a> e <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BSNF">BS34</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RNF06

<details>

<summary>O app deve fornecer uma experiência de login com apenas 2 cliques.</summary>

<center>

Tabela 44 - RNF06

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RNF06</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#desempenho">Especificação Suplementar - USA01, USA02, USA03, USA04, USA06, CON01, CON02, CON05, DES02, DES03, DES04 e DES05</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#epico-4-seguranca">Épicos 3 e 5 - Features 6 e 11</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us12">História de Usuário - US27 e US25</a> <br> Requisitos: <a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS15</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RNF07

<details>

<summary>O app não deve ter tempo de resposta superior a 200 ms.</summary>

<center>

Tabela 45 - RNF07

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RNF07</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#desempenho">Especificação Suplementar - DES02</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia">NFR - Eficiência</a> <br></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/questionario/#anchor_QNF">Q12</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RNF08

<details>

<summary>Os eventos devem estar organizados no banco de dados de acordo com suas categorias para facilitar a filtragem.</summary>

<center>

Tabela 46 - RNF08

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RNF08</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#desempenho">Especificação Suplementar - USA01, DES01 e DES05</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/">Casos de Uso - UC01</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-1">Cenário 01, 02, 03 e 04</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td> <br></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos">Léxico 01 e 03</a> <br> <a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#epico-1-categorizar">Épicos 1 e 5 - Features 1, 2 e 10</a> <br></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us12">História de Usuário - US01, US02, US04, US12, US13</a> <br> Requisitos:  <a href="../../elicitacao/tecnicas/questionario/#anchor_QNF">Q13</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RNF09

<details>

<summary>O app deve mostrar as informações de compras do usuário em uma única tela.</summary>

<center>

Tabela 47 - RNF09

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RNF09</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#desempenho">Especificação Suplementar - USA01, CON01, CON02, CON06, CON07, DES05</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td> <br></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#epico-1-categorizar">Épico 5 - Feature 10</a> <br></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us12">História de Usuário - US019</a> <br> Requisitos: <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BSNF">BS32</a> e <a href="../../elicitacao/tecnicas/observacao/#anchor_OBSNF">OBS21</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

### RNF10

<details>

<summary>O app deve permitir o acesso às informações do usuário em até 3 cliques.</summary>

<center>

Tabela 48 - RNF10

<table>
<thead>
<tr>
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais">RNF10</a></th>
<th>Desenvolvimento</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Tipos de Elo</td>
<td>Artefatos Relacionados</td>
</tr>
<tr>
<td style="text-align:center">Satisfação</td>
<td><a href="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#desempenho">Especificação Suplementar - USA01, USA04, USA06, CON02, CON08, DES04, </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td> <br></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>-</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisitos: <a href="../../elicitacao/tecnicas/observacao/#anchor_OBSNF">OBS20</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/arthurmlv'>Arthur de Melo</a> e <a href='https://github.com/RafaelCLG0'>Rafael Ferreira</a>.</font>

</center>

</details>

---
# Histórico de Versões

| Versão | Data de produção   | Descrição da Alteração                               | Autor(es)             | Revisor(es)      | Data de Revisão |
| :----: | :----------------: | :--------------------------------------------------: | :-------------------: | :-------------:  | :-------------: |
| 1.0    | 06/02/2025         | Criação inicial do documento                         | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | 06/06/2025 |
| 1.1    | 06/02/2025         | Adição das seções de Introdução e Metodologia | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | 06/06/2025 |
| 1.2    | 06/02/2025         | Inicialização da seção de Rastreabilidade | <a style="color:gold;" href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a> | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | 06/06/2025 |
