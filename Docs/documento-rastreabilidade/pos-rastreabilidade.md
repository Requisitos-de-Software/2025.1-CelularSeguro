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

---

# Requisitos funcionais

### RF01

<details>

<summary> O aplicativo deve permitir localizar o celular perdido. </summary>

<center>

Tabela 2 - RF01

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF01</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/">QS01</a>, <a href="../Storytelling/">ST06</a>, <a href="../AnalisedeDocumentos/">ADD01</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF02

<details>

<summary> O aplicativo deve tornar visível e acessível a opção de registro de boletim de ocorrência. </summary>

<center>

Tabela 3 - RF02

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF02</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/">QS02</a>, <a href="../Observacao/">OBS02</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF03

<details>

<summary> O aplicativo permite acessar ou cancelar contas bancárias vinculadas ao aparelho. </summary>

<center>

Tabela 4 - RF03

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF03</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito:  <a href="../Questionario/">QS03</a>, <a href="../Brainstorming/">BS03</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF04

<details>

<summary> O aplicativo deve oferecer o passo a passo do que fazer após um furto ou roubo. </summary>

<center>

Tabela 5 - RF04

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF04</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/">QS04</a>, <a href="../AnalisedeDocumentos/">ADD02</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF05

<details>

<summary> O aplicativo deve fornecer confirmação visual (feedback) ao usuário após realizar ações importantes. </summary>

<center>

Tabela 6 - RF05

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF05</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/">Q12</a>, <a href="../Brainstorming/">BS04</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF06

<details>

<summary> O aplicativo deve notificar o usuário em caso de atividade suspeita relacionada ao dispositivo. </summary>

<center>

Tabela 7 - RF06

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF06</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/">QS08</a>, <a href="../Brainstorming/">BS06</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF07

<details>

<summary> O aplicativo deve permitir a recuperação do aparelho bloqueado caso reencontrado. </summary>

<center>

Tabela 8 - RF07

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF07</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/">QS08</a>, <a href="../Storytelling/">ST03</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF08

<details>

<summary> O aplicativo deve permitir que o usuário registre um boletim de ocorrência. </summary>

<center>

Tabela 9 - RF08

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF08</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/">QS09</a>, <a href="../AnalisedeDocumentos/">ADD03</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF09

<details>

<summary> Modo Falso Desligamento/Fake Shutdown. Simular que o celular foi desligado quando, na verdade, continua rastreável e operacional para comandos remotos. </summary>

<center>

Tabela 10 - RF09

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF09</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/">QS14</a>, <a href="../Brainstorming/">BS07</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF10

<details>

<summary> O sistema deve permitir autenticação do usuário via conta Gov.br, utilizando CPF e senha, como pré‑requisito de acesso. </summary>

<center>

Tabela 11 - RF10

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF10</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../AnalisedeDocumentos/">ADD01</a>, <a href="../Brainstorming/">BS09</a>, <a href="../Observacao/">OBS01</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF11

<details>

<summary> O aplicativo deve exibir os Termos de Uso e Privacidade na primeira vez que for aberto e requerer que o usuário os aceite para prosseguir. </summary>

<center>

Tabela 12 - RF11

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF11</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../AnalisedeDocumentos/">ADD01</a>, <a href="../Observacao/">OBS03</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF12

<details>

<summary> O usuário poderá cadastrar múltiplos telefones celulares em sua conta no Celular Seguro, vinculando cada número de telefone ao seu CPF. </summary>

<center>

Tabela 13 - RF12

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF12</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../AnalisedeDocumentos/">ADD01</a>, <a href="../Brainstorming/">BS02</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF13

<details>

<summary> O aplicativo deve permitir o cadastro de “pessoas de confiança”, autorizando contatos escolhidos a emitir alertas em nome do usuário em caso de emergência. </summary>

<center>

Tabela 14 - RF13

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF13</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Storytelling/">ST05</a>, <a href="../Brainstorming/">BS05</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF14

<details>

<summary> O sistema deve fornecer uma função de emissão de alerta de bloqueio em caso de roubo, furto ou perda do aparelho, acionada por um botão de emergência de forma rápida. </summary>

<center>

Tabela 15 - RF14

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF14</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../AnalisedeDocumentos/">ADD04</a>, <a href="../Observacao/">OBS04</a>, <a href="../Storytelling/">ST02</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF15

<details>

<summary> Ao emitir um alerta, o usuário deverá selecionar o tipo de bloqueio desejado: Modo Recuperação (bloqueia linha e contas, mantendo o IMEI ativo) ou Bloqueio Total. </summary>

<center>

Tabela 16 - RF15

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF15</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../AnalisedeDocumentos/">ADD04</a>, <a href="../Brainstorming/">BS06</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF16

<details>

<summary> Após o disparo do alerta, o sistema deve gerar um número de protocolo único e apresentá‑lo ao usuário, para referência junto às autoridades e parceiros. </summary>

<center>

Tabela 17 - RF16

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF16</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../AnalisedeDocumentos/">ADD04</a>, <a href="../Questionario/">QS07</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF17

<details>

<summary> O alerta emitido pelo Celular Seguro deverá ser enviado automaticamente às operadoras de telefonia e instituições financeiras parceiras para os bloqueios necessários. </summary>

<center>

Tabela 18 - RF17

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF17</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../AnalisedeDocumentos/">ADD04</a>, <a href="../Brainstorming/">BS10</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF18

<details>

<summary> O aplicativo deve oferecer a funcionalidade de consultar se um aparelho possui restrição, permitindo verificar pelo IMEI se um celular é bloqueado antes de comprá‑lo. </summary>

<center>

Tabela 19 - RF18

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF18</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../AnalisedeDocumentos/">ADD03</a>, <a href="../Questionario/">QS11</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF19

<details>

<summary> O Celular Seguro deve estar disponível tanto como aplicativo móvel (Android/iOS) quanto via versão web, oferecendo as mesmas funcionalidades em ambas plataformas. </summary>

<center>

Tabela 20 - RF19

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF19</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../AnalisedeDocumentos/">ADD01</a>, <a href="../Brainstorming/">BS08</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF20

<details>

<summary> O sistema deve possibilitar a emissão de mais de um alerta para a mesma linha telefônica, permitindo novos alertas após ocorrências distintas. </summary>

<center>

Tabela 21 - RF20

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF20</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS06</a>, <a href="../Questionario/">QS13</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF21

<details>

<summary> Em modo Recuperação, o sistema deve receber notificações de quando um novo chip for inserido no aparelho e enviar alerta ao usuário. </summary>

<center>

Tabela 22 - RF21

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF21</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../AnalisedeDocumentos/">ADD04</a>, <a href="../Brainstorming/">BS06</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF22

<details>

<summary> Bloquear remotamente o aparelho. </summary>

<center>

Tabela 23 - RF22

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF22</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../AnalisedeDocumentos/">ADD04</a>, <a href="../Brainstorming/">BS06</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF23

<details>

<summary> Apagar todos os dados do dispositivo </summary>

<center>

Tabela 24 - RF23

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF23</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS06</a>, <a href="../Questionario/">QS06</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF24

<details>

<summary> Contatar autoridades automaticamente com relatório de segurança. </summary>

<center>

Tabela 25 - RF24

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF24</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Storytelling/">ST04</a>, <a href="../Brainstorming/">BS10</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF25

<details>

<summary> Rastrear em tempo real a localização do dispositivo. </summary>

<center>

Tabela 26 - RF25

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF25</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/">QS01</a>, <a href="../AnalisedeDocumentos/">ADD04</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF26

<details>

<summary> Exibir histórico de movimentação no mapa. </summary>

<center>

Tabela 27 - RF26

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF26</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS05</a>, <a href="../Observacao/">OBS05</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF27

<details>

<summary> Informar localização exata via coordenadas e mapa </summary>

<center>

Tabela 28 - RF27

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF27</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/">QS01</a>, <a href="../Observacao/">OBS06</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF28

<details>

<summary> Emitir alerta S.O.S. automático para contatos de emergência. </summary>

<center>

Tabela 29 - RF28

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF28</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Storytelling/">ST05</a>, <a href="../Brainstorming/">BS05</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF29

<details>

<summary> Bloquear chip por integração direta com a operadora. </summary>

<center>

Tabela 30 - RF29

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF29</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../AnalisedeDocumentos/">ADD04</a>, <a href="../Brainstorming/">BS10</a>  </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF30

<details>

<summary> Guia de usuário passo a passo embutido no app. </summary>

<center>

Tabela 31 - RF30

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF30</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS01</a>, <a href="../Observacao/">OBS02</a>  </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF31

<details>

<summary> Cadastro de contatos de segurança e envio de notificações prioritárias. </summary>

<center>

Tabela 32 - RF31

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF31</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS05</a>, <a href="../Storytelling/">ST05</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF32

<details>

<summary> Portal web para controle remoto das mesmas funções do app. </summary>

<center>

Tabela 33 - RF32

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF32</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../AnalisedeDocumentos/">ADD01</a>, <a href="../Brainstorming/">BS08</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF33

<details>

<summary> Sincronizar notificações push e e‑mail entre app e portal. </summary>

<center>

Tabela 34 - RF33

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF33</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS08</a>, <a href="../Questionario/">QS13</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF34

<details>

<summary> Botão de “bloqueio rápido” sempre acessível na tela principal. </summary>

<center>

Tabela 35 - RF34

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF34</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Observacao/">OBS04</a>, <a href="../Brainstorming/">BS06</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF35

<details>

<summary> Comandos por voz para funções críticas (bloqueio, rastreamento, SOS). </summary>

<center>

Tabela 36 - RF35

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF35</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS07</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF36

<details>

<summary> Efetuar backup automático de contatos, fotos e mensagens antes do bloqueio remoto </summary>

<center>

Tabela 37 - RF36

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF36</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS06</a>, <a href="../Questionario/">QS06</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF37

<details>

<summary> Restaurar dados de backup via e‑mail. </summary>

<center>

Tabela 38 - RF37

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF37</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS06</a>, <a href="../Questionario/">QS06</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF38

<details>

<summary> Emissão de som remoto para facilitar localização. </summary>

<center>

Tabela 39 - RF38

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF38</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/">QS01</a>, <a href="../Storytelling/">ST06</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF39

<details>

<summary> Oferecer rastreamento via satélite em áreas sem cobertura de celular. </summary>

<center>

Tabela 40 - RF39

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF39</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS07</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF40

<details>

<summary> Enviar notificação por e‑mail com detalhes da tentativa de acesso suspeito. </summary>

<center>

Tabela 41 - RF40

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF40</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/">QS08</a>, <a href="../Brainstorming/">BS06</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF41

<details>

<summary> Gerar relatório de movimentação para download em PDF. </summary>

<center>

Tabela 42 - RF41

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF41</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS10</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RF42

<details>

<summary> Definir “dispositivo de confiança” para controle remoto secundário. </summary>

<center>

Tabela 43 - RF42

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-funcionais">RF42</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td></tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS05</a>, <a href="../Observacao/">OBS07</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

---

# Requisitos não funcionais

### RNF01

<details>

<summary>O aplicativo deve funcionar de maneira estável e confiável em momentos de emergência.</summary>

<center>

Tabela 44 - RNF01

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF01</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/">QS09</a>, <a href="../Observacao/">OBS21</a>, <a href="../Brainstorming/">BS40</a>, <a href="../Storytelling/">ST11</a>, <a href="../AnalisedeDocumentos/">ADD13</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF02

<details>

<summary>A interface deve ter design acessível a usuários com pouca familiaridade com tecnologia, como idosos.</summary>

<center>

Tabela 45 - RNF02

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF02</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/">Q19</a>, <a href="../Observacao/">OBS18</a>, <a href="../Brainstorming/">BS42</a>/<a href="../Brainstorming/">BS43</a>, <a href="../Storytelling/">ST8</a>, <a href="../AnalisedeDocumentos/">ADD17</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF03

<details>

<summary>O aplicativo deve oferecer um modo escuro (dark mode) para maior conforto visual.</summary>

<center>

Tabela 46 - RNF03

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF03</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/">QS09</a>, <a href="../Brainstorming/">BS43</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF04

<details>

<summary>O aplicativo deve apresentar legendas em ícones e menus para facilitar a compreensão.</summary>

<center>

Tabela 47 - RNF04

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF04</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/">QS12</a>, <a href="../Observacao/">OBS15</a>, <a href="../Brainstorming/">BS36</a>, <a href="../Storytelling/">ST8</a>, <a href="../AnalisedeDocumentos/">ADD16</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF05

<details>

<summary>O aplicativo deve enviar um SMS para uma pessoa quando a mesma for adicionada como pessoa de confiança.</summary>

<center>

Tabela 48 - RNF05

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF05</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/">QS14</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF06

<details>

<summary>Suporte Técnico, como disponibilizar canais de suporte claros e responsivos para auxiliar os usuários.</summary>

<center>

Tabela 49 - RNF06

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF06</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/">QS14</a>, <a href="../Observacao/">OBS21</a>, <a href="../Brainstorming/">BS52</a>, <a href="../AnalisedeDocumentos/">ADD17</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF07

<details>

<summary>O serviço Celular Seguro deve estar disponível para todos os cidadãos brasileiros, 24×7, sem interrupções planejadas.</summary>

<center>

Tabela 50 - RNF07

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF07</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../AnalisedeDocumentos/">ADD13</a>, <a href="../Observacao/">OBS21</a>, <a href="../Brainstorming/">BS40</a>, <a href="../Storytelling/">ST11</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF08

<details>

<summary>O tempo de resposta para comunicação de um alerta aos parceiros deve ser mínimo – idealmente instantâneo – e os bloqueios devem ocorrer em minutos.</summary>

<center>

Tabela 51 - RNF08

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF08</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../AnalisedeDocumentos/">ADD14</a>, <a href="../Storytelling/">ST9</a>, <a href="../Brainstorming/">BS41</a>, <a href="../Brainstorming/">BS58</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF09

<details>

<summary>O aplicativo e a plataforma devem seguir requisitos de segurança da informação: conexão criptografada, proteção de dados conforme LGPD.</summary>

<center>

Tabela 52 - RNF09

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF09</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../AnalisedeDocumentos/">ADD15</a>, <a href="../Storytelling/">ST10</a>, <a href="../Brainstorming/">BS47</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF10

<details>

<summary>O serviço deverá ser oferecido gratuitamente, sem cobrança pelo download ou uso do aplicativo.</summary>

<center>

Tabela 53 - RNF10

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF10</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../AnalisedeDocumentos/">ADD18</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF11

<details>

<summary>O sistema deve cumprir a legislação e normas vigentes, incluindo portarias, resoluções da Anatel e diretrizes da Febraban.</summary>

<center>

Tabela 54 - RNF11

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF11</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../AnalisedeDocumentos/">ADD19</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF12

<details>

<summary>Linguagem simples sem jargões técnicos.</summary>

<center>

Tabela 55 - RNF12

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF12</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS37</a>, <a href="../Storytelling/">ST8</a>, <a href="../AnalisedeDocumentos/">ADD16</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF13

<details>

<summary> 	Layout consistente seguindo heurísticas de Nielsen.</summary>

<center>

Tabela 56 - RNF13

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF13</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS38</a>, <a href="../Storytelling/">ST8</a>, <a href="../AnalisedeDocumentos/">ADD16</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF14

<details>

<summary>Tempo de resposta da interface < 200 ms.</summary>

<center>

Tabela 57 - RNF14

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF14</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS39</a>, <a href="../Storytelling/">ST9</a>, <a href="../AnalisedeDocumentos/">ADD14</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF15

<details>

<summary>Suporte a VLibras e leitor de tela para acessibilidade.</summary>

<center>

Tabela 58 - RNF15

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF15</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS42</a>, <a href="../Observacao/">OBS18</a>, <a href="../AnalisedeDocumentos/">ADD17</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF16

<details>

<summary>Transcrição em tempo real sem falhas de reconhecimento.</summary>

<center>

Tabela 59 - RNF16

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF16</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS44</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF17

<details>

<summary> 	Precisão de localização GPS menor do que 10 metros.</summary>

<center>

Tabela 60 - RNF17

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF17</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS45</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF18

<details>

<summary>Autenticação multifator (2FA) com fallback via SMS.</summary>

<center>

Tabela 61 - RNF18

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF18</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS48</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF19

<details>

<summary>Logs de auditoria imutáveis e armazenados por no mínimo 1 ano.</summary>

<center>

Tabela 62 - RNF19

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF19</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS49</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF20

<details>

<summary>Política de privacidade clara e facilmente acessível dentro do app.</summary>

<center>

Tabela 63 - RNF20

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF20</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS50</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF21

<details>

<summary>Verificação de integridade de dados no drive com checksum.</summary>

<center>

Tabela 64 - RNF21

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF21</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS53</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF22

<details>

<summary>Compatibilidade com Android e iOS (últimas 3 versões principais).</summary>

<center>

Tabela 65 - RNF22

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF22</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS57</a>, <a href="../AnalisedeDocumentos/">ADD17</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF23

<details>

<summary>Tempo de inicialização do app < 2 segundos.</summary>

<center>

Tabela 66 - RNF23

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF23</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS58</a>, <a href="../Storytelling/">ST9</a>, <a href="../AnalisedeDocumentos/">ADD14</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF24

<details>

<summary>Atualizações automáticas de segurança e correções de vulnerabilidades em até 24 horas.</summary>

<center>

Tabela 67 - RNF24

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF24</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS60</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF25

<details>

<summary>As páginas carregam em até 2 segundos em conexões padrão 4G.</summary>

<center>

Tabela 68 - RNF25

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF25</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Observacao/">OBS16</a>, <a href="../Brainstorming/">BS39</a>, <a href="../Storytelling/">ST9</a>, <a href="../AnalisedeDocumentos/">ADD14</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF26

<details>

<summary>O aplicativo responde corretamente mesmo com entradas erradas.</summary>

<center>

Tabela 69 - RNF26

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF26</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Observacao/">OBS19</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

### RNF27

<details>

<summary>O aplicativo apresenta confirmação de suas ações.</summary>

<center>

Tabela 70 - RNF27

<table>
<thead>
<tr>
<th style="text-align:center"><a href="../../documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais">RNF27</a></th>
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
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Observacao/">OBS20</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a>.</font>

</center>

</details>

---

## Referências Bibliográficas

> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 25 de jun de 2023.

> TORANZO, M.; CASTRO, J; MELLO, E. Uma proposta para melhorar o rastreamento de requisitos. PUC-Rio: Workshop em Engenharia de Requisitos, Rio de Janeiro, 2002. Disponível em: http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf. Acesso em: 25 de jun de 2023.

---

# Histórico de Versões

| Versão | Data de produção   | Descrição da Alteração                               | Autor(es)             | Revisor(es)      | Data de Revisão |
| :----: | :----------------: | :--------------------------------------------------: | :-------------------: | :-------------:  | :-------------: |
| 1.0    | 06/02/2025         | Criação inicial do documento                         | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | 06/06/2025 |
| 1.1    | 06/02/2025         | Adição das seções de Introdução e Metodologia | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | 06/06/2025 |
| 1.2    | 08/02/2025         | Inicialização da seção de Rastreabilidade | <a style="color:gold;" href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a> | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | 08/06/2025 |
| 1.3    | 08/02/2025         | Atualização da seção de Rastreabilidade | <a style="color:gold;" href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a> | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | 08/06/2025 |
