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

A rastreabilidade foi aplicada exclusivamente aos requisitos que **não foram implementados** pela aplicação Celular Seguro, embora alguns tenham sido simulados no protótipo de alta fidelidade utilizado na etapa de validação. A estrutura usada para organizar essas informações pode ser visualizada na Tabela 1.

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

As tabelas a seguir detalham os elos identificados entre os artefatos e os requisitos, tanto funcionais quanto não funcionais, implementados ou não pelo Celular seguro. 

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
<td><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#funcionalidade">Especificação Suplementar USA04</a> <br> <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a></td>
<br> <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-01-usabilidade">NFR Usabilidade</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-01-usabilidade">Cenário 04</a> <br> <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-01-usabilidade">Requisitos NFR02 e NFR03</a> <br> <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-01-usabilidade">Especificação Suplementar CON01 e CON02</a></td>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://www.figma.com/proto/jpY7Ll4PCtCUi53bcdk4bb/Celular-Seguro?node-id=181-129&p=f&t=o1y1vv6G7TYjQMrQ-1&scaling=scale-down&content-scaling=fixed&page-id=181%3A2&starting-point-node-id=181%3A129;type=design&amp;node-id=107-1118&amp;viewport=29390%2C34193%2C3.02&amp;scaling=min-zoom&amp;starting-point-node-id=107%3A1118&amp;show-proto-sidebar=1">Protótipo de Alta Fidelidade:</a><br><img src="../../assets/videos prototipo/RF01.gif" style="width: 100%; max-width: 700px; display: block; margin: auto;"></td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/modelagem/lexicos/#l01-filtrar-eventos">Léxico 01</a> <br> <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/modelagem/agil/backlog/#metodologia">Épico 1 - Feature 1</a> <br> <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/modelagem/agil/nfrframework/#nfr-01-usabilidade">NFR Usabilidade</a> <br> <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/modelagem/useCase/#especializacao-dos-casos-de-uso">Casos de Uso UC01</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/">QS01</a>, <a href="../Storytelling/">ST06</a>, <a href="../AnalisedeDocumentos/">ADD01</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<td><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#funcionalidade">Especificação Suplementar USA04</a> <br> <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a> <br> <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-01-usabilidade">NFR Usabilidade</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="../../documento-modelagem/CasoDeUso/#uc02--registrar-boletim">UC02 - Registrar Boletim</a><br><a href="../../documento-modelagem/Agil/Historias_de_usuario/#us03---registrar-boletim-de-ocorrência">US03 - Registrar boletim de ocorrência</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="../../documento-modelagem/Backlog/#épico-2--boletim-de-ocorrência">Épico 2 - Boletim de Ocorrência</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/#qs02">QS02</a>, <a href="../Observacao/#obs02">OBS02</a>, <a href="../Storytelling/#st04">ST04</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<td><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#funcionalidade">Especificação Suplementar USA04</a> <br> <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a> <br> <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-01-usabilidade">NFR Usabilidade</a></td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="../../documento-modelagem/CasoDeUso/#uc10--gerenciar-contas-bancárias-vinculadas">UC10 - Gerenciar Contas Bancárias Vinculadas</a><br><a href="../../documento-modelagem/Agil/Historias_de_usuario/#us21---cancelar-conta-bancária-vinculada">US21 - Cancelar conta bancária vinculada</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="../../documento-modelagem/Backlog/#épico-3--conta--perfil">Épico 3 - Conta & Perfil</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito:  <a href="../Questionario/#qs03">QS03</a>, <a href="../Brainstorming/#bs03">BS03</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#requisitos-elicitados">RF04</a></th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#usabilidade">Especificação Suplementar USA05</a> <br> 
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-01-usabilidade">NFR Usabilidade</a> <br> 
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#tabela-12-caso-de-uso-uc11-guia-de-acoes-pos-furto">UC11 - Guia de Ações Pós-Furto</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-2-%E2%80%93-boletim-de-ocorr%C3%AAncia">Épico 2 – Boletim de Ocorrência</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#requisitos-elicitados">QS04</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#requisitos-funcionais">RF05</a></th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#usabilidade">Especificação Suplementar USA01, USA02</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-01-usabilidade">NFR Usabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#tabela-15-caso-de-uso-uc14-feedback-visual-ao-usuario">UC14 - Feedback Visual ao Usuário</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us01">US01 - Confirmação visual após ações</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-4-%E2%80%93-comunica%C3%A7%C3%A3o--notifica%C3%A7%C3%B5es">Épico 4 – Comunicação & Notificações</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#requisitos-elicitados">Q12</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#requisitos-funcionais">RF06</a></th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#confiabilidade">Especificação Suplementar CON03</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-04-segurança">NFR Segurança</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us02">US02 - Notificação de atividade suspeita</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://www.figma.com/proto/jpY7Ll4PCtCUi53bcdk4bb/Celular-Seguro?node-id=181-129&p=f&t=o1y1vv6G7TYjQMrQ-1&scaling=scale-down&content-scaling=fixed&page-id=181%3A2&starting-point-node-id=181%3A129;type=design&amp;node-id=107-1118&amp;viewport=29390%2C34193%2C3.02&amp;scaling=min-zoom&amp;starting-point-node-id=107%3A1118&amp;show-proto-sidebar=1">Protótipo de Alta Fidelidade:</a><br><img src="../../assets/videos prototipo/RF06.gif" style="width: 100%; max-width: 700px; display: block; margin: auto;"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-4-%E2%80%93-comunica%C3%A7%C3%A3o--notifica%C3%A7%C3%B5es">Épico 4 – Comunicação & Notificações</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#requisitos-elicitados">QS08</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#requisitos-funcionais">RF07</a></th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#confiabilidade">Especificação Suplementar CON01, SUP06</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-04-segurança">NFR Segurança</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us28">US28 - Escolher tipo de bloqueio</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-6-%E2%80%94-localiza%C3%A7%C3%A3o-e-controle-remoto">Épico 6 – Localização e Controle Remoto</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#requisitos-elicitados">QS08</a></td>
</tr>
</tbody>
</table>

<font size="3">Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Observacao/#tabela-de-requisitos-funcionais">RF08</a></th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#usabilidade">Especificação Suplementar USA04, CON01, CON02</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-01-usabilidade">NFR Usabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#tabela-3-caso-de-uso-uc02-registrar-boletim">UC02 - Registrar Boletim</a><br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us09">US09 - Registrar boletim de ocorrência</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-2-%E2%80%93-boletim-de-ocorr%C3%AAncia">Épico 2 – Boletim de Ocorrência</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>
  Requisito: <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#requisitos-elicitados">QS02</a>, 
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#requisitos-elicitados">QS09</a>, 
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Observacao/#tabela-de-requisitos-funcionais">OBS8</a>
</td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais">RF09</a></th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#confiabilidade">Especificação Suplementar CON01, CON05</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-04-segurança">NFR Segurança</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>Não especificado em um UC ou US dedicado nos artefatos.</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-6-%E2%80%94-localiza%C3%A7%C3%A3o-e-controle-remoto">Épico 6 – Localização e Controle Remoto</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/">QS14</a>, <a href="../Brainstorming/">BS07</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/#requisitos-funcionais-rf_1">RF10</a></th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#autentica%C3%A7%C3%A3o-via-govbr">Especificação Suplementar - Autenticação via GOV.br</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-04-segurança">NFR Segurança</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#restri%C3%A7%C3%B5es-do-projeto">Especificação Suplementar - Restrições do Projeto</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-3-%E2%80%93-conta--perfil">Épico 3 – Conta & Perfil</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/#requisitos-funcionais-rf_1">ADD01</a>, <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/">BS09</a>, <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Observacao/">OBS01</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/#requisitos-funcionais-rf_1">RF11</a></th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#requisitos-de-licenciamento">Especificação Suplementar - Requisitos de Licenciamento</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#padr%C3%B5es-aplic%C3%A1veis">Padrões Aplicáveis - LGPD</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us18">US18 - Fazer download do Termos de Uso do aplicativo</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-3-%E2%80%93-conta--perfil">Épico 3 – Conta & Perfil</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/">ADD01</a>, <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Observacao/">OBS03</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/#requisitos-funcionais-rf_1">RF12</a></th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#usabilidade">Especificação Suplementar USA04, CON01</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-01-usabilidade">NFR Usabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us00">US00 - Cadastro de múltiplos celulares</a></td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://www.figma.com/proto/jpY7Ll4PCtCUi53bcdk4bb/Celular-Seguro?node-id=181-129&p=f&t=o1y1vv6G7TYjQMrQ-1&scaling=scale-down&content-scaling=fixed&page-id=181%3A2&starting-point-node-id=181%3A129;type=design&amp;node-id=107-1118&amp;viewport=29390%2C34193%2C3.02&amp;scaling=min-zoom&amp;starting-point-node-id=107%3A1118&amp;show-proto-sidebar=1">Protótipo de Alta Fidelidade:</a><br><img src="../../assets/videos prototipo/RF12.gif" style="width: 100%; max-width: 700px; display: block; margin: auto;"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-1-%E2%80%93-cadastro-de-dispositivos">Épico 1 – Cadastro de Dispositivos</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/">ADD01</a>, <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/">BS02</a></td>
</tr>
</tbody>
</table>
<font size="3">Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

</center>


<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/#requisitos-funcionais-rf_1">RF13</a></th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#confiabilidade">Especificação Suplementar CON01, SUP06</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-04-segurança">NFR Segurança</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#tabela-13-caso-de-uso-uc12-cadastrar-pessoa-de-confianca">UC12 - Cadastrar Pessoa de Confiança</a><br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us29">US29 - Permitir que pessoas de confiança emitam alerta</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://www.figma.com/proto/jpY7Ll4PCtCUi53bcdk4bb/Celular-Seguro?node-id=181-129&p=f&t=o1y1vv6G7TYjQMrQ-1&scaling=scale-down&content-scaling=fixed&page-id=181%3A2&starting-point-node-id=181%3A129;type=design&amp;node-id=107-1118&amp;viewport=29390%2C34193%2C3.02&amp;scaling=min-zoom&amp;starting-point-node-id=107%3A1118&amp;show-proto-sidebar=1">Protótipo de Alta Fidelidade:</a><br><img src="../../assets/videos prototipo/RF13 E RF31.gif" style="width: 100%; max-width: 700px; display: block; margin: auto;"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-5-%E2%80%93-pessoa-de-confian%C3%A7a">Épico 5 – Pessoa de Confiança</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Storytelling/">ST05</a>, <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/">BS05</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center"><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/#requisitos-funcionais-rf_1">RF14</a></th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#desempenho">Especificação Suplementar DES02, DES04, CON03</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-01-usabilidade">NFR Usabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#tabela-2-caso-de-uso-uc01-emitir-alerta-de-roubo">UC01 - Emitir Alerta de Roubo</a><br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us27">US27 - Confirmar antes da emissão do alerta</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-4-%E2%80%93-comunica%C3%A7%C3%A3o--notifica%C3%A7%C3%B5es">Épico 4 – Comunicação & Notificações</a></td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/">ADD04</a>, <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Observacao/">OBS04</a>, <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Storytelling/">ST02</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/#requisitos-funcionais-rf_1">RF15</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#confiabilidade">Especificação Suplementar CON07, USA04</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-01-usabilidade">NFR Usabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us28">US28 - Escolher tipo de bloqueio</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-6-%E2%80%94-localiza%C3%A7%C3%A3o-e-controle-remoto">Épico 6 – Localização e Controle Remoto</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>
  Requisito: 
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/">ADD04</a>, 
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/">BS06</a>
</td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/#requisitos-funcionais-rf_1">RF16</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#suportabilidade">Especificação Suplementar SUP06, CON02</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-01-usabilidade">NFR Usabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us30">US30 - Gerar número de protocolo</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-4-%E2%80%93-comunica%C3%A7%C3%A3o--notifica%C3%A7%C3%B5es">Épico 4 – Comunicação & Notificações</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>
  Requisito: 
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/">ADD04</a>, 
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/">QS07</a>
</td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/#requisitos-funcionais-rf_1">RF17</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#integra%C3%A7%C3%B5es-obrigat%C3%B3rias">Especificação Suplementar - Integrações Obrigatórias</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-04-segurança">NFR Segurança</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#tabela-2-caso-de-uso-uc01-emitir-alerta-de-roubo">UC01 - Emitir Alerta de Roubo</a><br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#tabela-5-caso-de-uso-uc04-bloqueio-remoto-do-aparelho">UC04 - Bloqueio Remoto do Aparelho</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-6-%E2%80%94-localiza%C3%A7%C3%A3o-e-controle-remoto">Épico 6 – Localização e Controle Remoto</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>
  Requisito: 
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/">ADD04</a>, 
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/">BS10</a>
</td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/#requisitos-funcionais-rf_1">RF18</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#integra%C3%A7%C3%B5es-obrigat%C3%B3rias">Especificação Suplementar - Integrações Obrigatórias</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#desempenho">USA02, CON02</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us22">US22 - Consulta manual e direta do IMEI</a><br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us19">US19 - Leitura do IMEI via câmera do celular</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-1-%E2%80%93-cadastro-de-dispositivos">Épico 1 – Cadastro de Dispositivos</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>
  Requisito: 
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/">ADD09</a>, 
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/">QS11</a>
</td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<td><a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#funcionalidade">Especificação Suplementar USA04</a> <br> <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a></td>
<br> <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-01-usabilidade">NFR Usabilidade</a></td>
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

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/#requisitos-funcionais-rf_1">RF20</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#suportabilidade">Especificação Suplementar SUP06, CON01</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-01-usabilidade">NFR Usabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#tabela-2-caso-de-uso-uc01-emitir-alerta-de-roubo">UC01 - Emitir Alerta de Roubo</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-4-%E2%80%93-comunica%C3%A7%C3%A3o--notifica%C3%A7%C3%B5es">Épico 4 – Comunicação & Notificações</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS06</a>, <a href="../Questionario/">QS13</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/#requisitos-funcionais-rf_1">RF21</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#confiabilidade">Especificação Suplementar CON03, CON05</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-04-segurança">NFR Segurança</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/#tabela-4-lexicos-estados">Léxico - Estado: Chip alterado</a><br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us28">US28 - Escolher tipo de bloqueio</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-4-%E2%80%93-comunica%C3%A7%C3%A3o--notifica%C3%A7%C3%B5es">Épico 4 – Comunicação & Notificações</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../AnalisedeDocumentos/">ADD04</a>, <a href="../Brainstorming/">BS06</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais">RF22</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#confiabilidade">Especificação Suplementar CON07, DES02</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-04-segurança">NFR Segurança</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#tabela-5-caso-de-uso-uc04-bloqueio-remoto-do-aparelho">UC04 - Bloqueio Remoto do Aparelho</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us39">US39 - Bloquear dispositivo</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-6-%E2%80%94-localiza%C3%A7%C3%A3o-e-controle-remoto">Épico 6 – Localização e Controle Remoto</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../AnalisedeDocumentos/">ADD04</a>, <a href="../Brainstorming/">BS06</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais">RF23</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#confiabilidade">Especificação Suplementar CON01</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-04-segurança">NFR Segurança</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#tabela-9-caso-de-uso-uc08-limpeza-remota-com-autenticacao-forte">UC08 - Limpeza Remota com Autenticação Forte</a><br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us40">US40 - Redefinir dispositivo para padrões de fábrica</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-6-%E2%80%94-localiza%C3%A7%C3%A3o-e-controle-remoto">Épico 6 – Localização e Controle Remoto</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS06</a>, <a href="../Questionario/">QS06</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Storytelling/#tabela-de-requisitos-funcionais">RF24</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#integra%C3%A7%C3%B5es-obrigat%C3%B3rias">Especificação Suplementar - Integrações Obrigatórias</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-04-segurança">NFR Segurança</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#tabela-2-caso-de-uso-uc01-emitir-alerta-de-roubo">UC01 - Emitir Alerta de Roubo</a><br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#tabela-7-caso-de-uso-uc06-gerar-relatorio-de-movimentacao-em-pdf">UC06 - Gerar Relatório de Movimentação em PDF</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-4-%E2%80%93-comunica%C3%A7%C3%A3o--notifica%C3%A7%C3%B5es">Épico 4 – Comunicação & Notificações</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Storytelling/">ST04</a>, <a href="../Brainstorming/">BS10</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais">RF25</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#desempenho">Especificação Suplementar CON02, DES02</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-03-desempenho">NFR Desempenho (RNF11)</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#tabela-4-caso-de-uso-uc03-localizar-celular">UC03 - Localizar Celular</a><br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us37">US37 - Localizar o dispositivo em tempo real</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-6-%E2%80%94-localiza%C3%A7%C3%A3o-e-controle-remoto">Épico 6 – Localização e Controle Remoto</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/">QS01</a>, <a href="../AnalisedeDocumentos/">ADD04</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais">RF26</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#confiabilidade">Especificação Suplementar CON02, CON04, DES02</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-01-usabilidade">NFR Usabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/cenario/#cenario-4-visualizar-ocorrencias-em-um-mapa">Cenário 4 - Visualizar ocorrências em um mapa</a><br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#tabela-7-caso-de-uso-uc06-gerar-relatorio-de-movimentacao-em-pdf">UC06 - Gerar Relatório de Movimentação em PDF</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-6-%E2%80%94-localiza%C3%A7%C3%A3o-e-controle-remoto">Épico 6 – Localização e Controle Remoto</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS05</a>, <a href="../Observacao/">OBS05</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#requisitos-elicitados">RF27</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#desempenho">Especificação Suplementar CON02, DES02</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-03-desempenho">NFR Desempenho (RNF11)</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#tabela-4-caso-de-uso-uc03-localizar-celular">UC03 - Localizar Celular</a><br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us37">US37 - Localizar o dispositivo em tempo real</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-6-%E2%80%94-localiza%C3%A7%C3%A3o-e-controle-remoto">Épico 6 – Localização e Controle Remoto</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/">QS01</a>, <a href="../Observacao/">OBS06</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Storytelling/#tabela-de-requisitos-funcionais">RF28</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#confiabilidade">Especificação Suplementar CON01, CON03, DES02</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-04-segurança">NFR Segurança</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us25">US25 - Alertar automaticamente por comportamento suspeito</a><br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#tabela-13-caso-de-uso-uc12-cadastrar-pessoa-de-confianca">UC12 - Cadastrar Pessoa de Confiança</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-4-%E2%80%93-comunica%C3%A7%C3%A3o--notifica%C3%A7%C3%B5es">Épico 4 – Comunicação & Notificações</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Storytelling/">ST05</a>, <a href="../Brainstorming/">BS05</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais">RF29</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#integra%C3%A7%C3%B5es-obrigat%C3%B3rias">Especificação Suplementar - Integrações Obrigatórias</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-04-segurança">NFR Segurança</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#tabela-5-caso-de-uso-uc04-bloqueio-remoto-do-aparelho">UC04 - Bloqueio Remoto do Aparelho</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-6-%E2%80%94-localiza%C3%A7%C3%A3o-e-controle-remoto">Épico 6 – Localização e Controle Remoto</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../AnalisedeDocumentos/">ADD04</a>, <a href="../Brainstorming/">BS10</a>  </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais">RF30</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#usabilidade">Especificação Suplementar USA05</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-01-usabilidade">NFR Usabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#tabela-12-caso-de-uso-uc11-guia-de-acoes-pos-furto">UC11 - Guia de Ações Pós-Furto</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-3-%E2%80%93-conta--perfil">Épico 3 – Conta & Perfil</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS01</a>, <a href="../Observacao/">OBS02</a>  </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais">RF31</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#confiabilidade">Especificação Suplementar CON01, DES02</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-04-segurança">NFR Segurança</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#tabela-13-caso-de-uso-uc12-cadastrar-pessoa-de-confianca">UC12 - Cadastrar Pessoa de Confiança</a><br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us31">US31 a US36 - Gerenciamento de Pessoas de Confiança</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://www.figma.com/proto/jpY7Ll4PCtCUi53bcdk4bb/Celular-Seguro?node-id=181-129&p=f&t=o1y1vv6G7TYjQMrQ-1&scaling=scale-down&content-scaling=fixed&page-id=181%3A2&starting-point-node-id=181%3A129;type=design&amp;node-id=107-1118&amp;viewport=29390%2C34193%2C3.02&amp;scaling=min-zoom&amp;starting-point-node-id=107%3A1118&amp;show-proto-sidebar=1">Protótipo de Alta Fidelidade:</a><br><img src="../../assets/videos prototipo/RF13 E RF31.gif" style="width: 100%; max-width: 700px; display: block; margin: auto;"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-5-%E2%80%93-pessoa-de-confian%C3%A7a">Épico 5 – Pessoa de Confiança</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS05</a>, <a href="../Storytelling/">ST05</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais">RF32</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#interfaces-de-usu%C3%A1rio">Especificação Suplementar - Interfaces de Usuário</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-01-usabilidade">NFR Usabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/cenario/#cenario-2-selecionar-acoes-de-seguranca-para-um-dispositivo">Cenário 2 - Selecionar ações de segurança</a><br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/cenario/#cenario-5-bloquear-remotamente-um-dispositivo">Cenário 5 - Bloquear remotamente um dispositivo</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>Todos os Épicos</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../AnalisedeDocumentos/">ADD01</a>, <a href="../Brainstorming/">BS08</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais">RF33</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#confiabilidade">Especificação Suplementar CON02, SUP06</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-01-usabilidade">NFR Usabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/#tabela-4-lexicos-estados">Léxico - Estado: Sincronizado com o portal</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-4-%E2%80%93-comunica%C3%A7%C3%A3o--notifica%C3%A7%C3%B5es">Épico 4 – Comunicação & Notificações</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS08</a>, <a href="../Questionario/">QS13</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Observacao/#tabela-de-requisitos-funcionais">RF34</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#usabilidade">Especificação Suplementar USA04, DES02</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-01-usabilidade">NFR Usabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#tabela-2-caso-de-uso-uc01-emitir-alerta-de-roubo">UC01 - Emitir Alerta de Roubo</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-4-%E2%80%93-comunica%C3%A7%C3%A3o--notifica%C3%A7%C3%B5es">Épico 4 – Comunicação & Notificações</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Observacao/">OBS04</a>, <a href="../Brainstorming/">BS06</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais">RF35</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#requisitos-ambientais">Especificação Suplementar - Requisitos Ambientais (Acessibilidade)</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-01-usabilidade">NFR Usabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>Não especificado em um UC ou US dedicado nos artefatos.</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-6-%E2%80%94-localiza%C3%A7%C3%A3o-e-controle-remoto">Épico 6 – Localização e Controle Remoto</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS07</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais">RF36</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#confiabilidade">Especificação Suplementar CON04, DES02</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-04-segurança">NFR Segurança</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#tabela-14-caso-de-uso-uc13-backup-periodico-de-dados">UC13 - Backup Periódico de Dados</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us42">US42 - Realizar backup dos dados</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-6-%E2%80%94-localiza%C3%A7%C3%A3o-e-controle-remoto">Épico 6 – Localização e Controle Remoto</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS06</a>, <a href="../Questionario/">QS06</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais">RF37</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#confiabilidade">Especificação Suplementar CON01, CON04</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-04-segurança">NFR Segurança</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#tabela-6-caso-de-uso-uc05-backup-de-dados-via-email">UC05 - Backup de Dados via Email</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us42">US42 - Realizar backup dos dados e disponibilizá-lo por e-mail</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-6-%E2%80%94-localiza%C3%A7%C3%A3o-e-controle-remoto">Épico 6 – Localização e Controle Remoto</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS06</a>, <a href="../Questionario/">QS06</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais">RF38</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#desempenho">Especificação Suplementar DES02</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-01-usabilidade">NFR Usabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us38">US38 - Fazer o dispositivo emitir som</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/cenario/#cenario-2-selecionar-acoes-de-seguranca-para-um-dispositivo">Cenário 2 - Selecionar ações de segurança</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href="https://www.figma.com/proto/jpY7Ll4PCtCUi53bcdk4bb/Celular-Seguro?node-id=181-129&p=f&t=o1y1vv6G7TYjQMrQ-1&scaling=scale-down&content-scaling=fixed&page-id=181%3A2&starting-point-node-id=181%3A129;type=design&amp;node-id=107-1118&amp;viewport=29390%2C34193%2C3.02&amp;scaling=min-zoom&amp;starting-point-node-id=107%3A1118&amp;show-proto-sidebar=1">Protótipo de Alta Fidelidade:</a><br><img src="../../assets/videos prototipo/RF38.gif" style="width: 100%; max-width: 700px; display: block; margin: auto;"></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-6-%E2%80%94-localiza%C3%A7%C3%A3o-e-controle-remoto">Épico 6 – Localização e Controle Remoto</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/">QS01</a>, <a href="../Storytelling/">ST06</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais">RF39</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#requisitos-ambientais">Especificação Suplementar - Requisitos Ambientais</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-03-desempenho">NFR Desempenho</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>Não especificado em um UC ou US dedicado nos artefatos.</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-6-%E2%80%94-localiza%C3%A7%C3%A3o-e-controle-remoto">Épico 6 – Localização e Controle Remoto</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS07</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais">RF40</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#componentes-comprados">Especificação Suplementar - Componentes Comprados (Envio de e-mail)</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-04-segurança">NFR Segurança</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us02">US02 - Notificação de atividade suspeita</a><br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/#tabela-4-lexicos-estados">Léxico - Estado: Tentativa de acesso detectada</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-4-%E2%80%93-comunica%C3%A7%C3%A3o--notifica%C3%A7%C3%B5es">Épico 4 – Comunicação & Notificações</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Questionario/">QS08</a>, <a href="../Brainstorming/">BS06</a></td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais">RF41</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#confiabilidade">Especificação Suplementar CON02, DES02, SUP06</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidade">NFR Confiabilidade</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-01-usabilidade">NFR Usabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#tabela-7-caso-de-uso-uc06-gerar-relatorio-de-movimentacao-em-pdf">UC06 - Gerar Relatório de Movimentação em PDF</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-6-%E2%80%94-localiza%C3%A7%C3%A3o-e-controle-remoto">Épico 6 – Localização e Controle Remoto</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS10</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

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
<th style="text-align:center">
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais">RF42</a>
</th>
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
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#confiabilidade">Especificação Suplementar CON01, SUP06</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-04-segurança">NFR Segurança</a> <br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-01-usabilidade">NFR Usabilidade</a>
</td>
</tr>
<tr>
<td style="text-align:center">Recurso</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#tabela-8-caso-de-uso-uc07-definir-dispositivo-de-confianca">UC07 - Definir Dispositivo de Confiança</a>
</td>
</tr>
<tr>
<td style="text-align:center">Representação</td>
<td><a href=""> - </a></td>
</tr>
<tr>
<td style="text-align:center">Alocado</td>
<td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#%C3%A9pico-3-%E2%80%93-conta--perfil">Épico 3 – Conta & Perfil</a>
</td>
</tr>
<tr>
<td style="text-align:center">Agregação</td>
<td>Requisito: <a href="../Brainstorming/">BS05</a>, <a href="../Observacao/">OBS07</a> </td>
</tr>
</tbody>
</table>

<font>Fonte: <a href='https://github.com/leozinlima'>Leonardo de Melo</a> e <a href='https://github.com/FelipeFreire-gf'>Felipe das Neves</a></font>

</center>

</details>

---

# Requisitos não funcionais

<!-- ============================= RNF 01 ============================= -->
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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Confiabilidade</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#confiabilidade">Especificação Suplementar – CON01, CON02 & CON05</a>; 
<a href="../Questionario/">QS09</a>; <a href="../Observacao/">OBS21</a>; <a href="../Brainstorming/">BS40</a>; <a href="../Storytelling/">ST11</a>; <a href="../AnalisedeDocumentos/">ADD13</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso – UC01 Emitir Alerta, UC02 Registrar Boletim & UC04 Bloqueio Remoto</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos – Localizar • Bloquear • Notificar</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/cenario/">Cenário 2 – Selecionar ações de segurança</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/">NFR Framework – Confiabilidade</a>
</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../Questionario/">QS09</a>, <a href="../Observacao/">OBS21</a>, <a href="../Brainstorming/">BS40</a>, <a href="../Storytelling/">ST11</a>, <a href="../AnalisedeDocumentos/">ADD13</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 02 ============================= -->
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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Usabilidade</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#usabilidade">Especificação Suplementar – USA03, USA04 & USA05</a>; 
<a href="../Questionario/">Q19</a>; <a href="../Observacao/">OBS18</a>; <a href="../Brainstorming/">BS42</a>/<a href="../Brainstorming/">BS43</a>; <a href="../Storytelling/">ST8</a>; <a href="../AnalisedeDocumentos/">ADD17</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos – verbos “Solicitar” & objetos de navegação</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/cenario/">Cenário 1 – Filtrar por tipo de celular</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso – UC11 Guia Pós-Furto (passo a passo simplificado)</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/">NFR Framework – Usabilidade</a>
</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../Questionario/">Q19</a>, <a href="../Observacao/">OBS18</a>, <a href="../Brainstorming/">BS42</a>/<a href="../Brainstorming/">BS43</a>, <a href="../Storytelling/">ST8</a>, <a href="../AnalisedeDocumentos/">ADD17</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 03 ============================= -->
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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Usabilidade</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#usabilidade">Especificação Suplementar – USA03</a>; 
<a href="../Questionario/">QS09</a>; <a href="../Brainstorming/">BS43</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso – UC09 Editar Perfil (preferência de tema)</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/cenario/">Cenário 2 – Selecionar ações (painel com alternância de tema)</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/">NFR Framework – Cartão RNF04 (Modo Escuro)</a>
</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../Questionario/">QS09</a>, <a href="../Brainstorming/">BS43</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 04 ============================= -->
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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Usabilidade</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#usabilidade">Especificação Suplementar – USA03</a>; 
<a href="../Questionario/">QS12</a>; <a href="../Observacao/">OBS15</a>; <a href="../Brainstorming/">BS36</a>; <a href="../Storytelling/">ST8</a>; <a href="../AnalisedeDocumentos/">ADD16</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos – Padronização de termos de interface</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso – UC14 Feedback Visual</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/">NFR Framework – Usabilidade</a>
</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../Questionario/">QS12</a>, <a href="../Observacao/">OBS15</a>, <a href="../Brainstorming/">BS36</a>, <a href="../Storytelling/">ST8</a>, <a href="../AnalisedeDocumentos/">ADD16</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 05 ============================= -->
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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Confiabilidade</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#confiabilidade">Especificação Suplementar – CON03</a>; 
<a href="../Questionario/">QS14</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso – UC12 Cadastrar Pessoa de Confiança</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos – Contato de Segurança • Notificação</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/">NFR Framework – Cartão RNF08 (SMS Pessoa de Confiança)</a><br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us31">História de Usuário – US31</a><br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#epico-5-pessoa-de-confianca">Backlog – Épico 5 / Feature 5.1</a>
</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../Questionario/">QS14</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 06 ============================= -->
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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Suportabilidade</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#suportabilidade">Especificação Suplementar – SUP05</a>; 
<a href="../Questionario/">QS14</a>; <a href="../Observacao/">OBS21</a>; <a href="../Brainstorming/">BS52</a>; <a href="../AnalisedeDocumentos/">ADD17</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso – UC11 Guia Pós-Furto (orientação ao usuário)</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos – Notificação & Estado “Notificação pendente”</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/">NFR Framework – Suportabilidade</a>
</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../Questionario/">QS14</a>, <a href="../Observacao/">OBS21</a>, <a href="../Brainstorming/">BS52</a>, <a href="../AnalisedeDocumentos/">ADD17</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 07 ============================= -->
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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Confiabilidade</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#confiabilidade">Especificação Suplementar – CON05</a>; 
<a href="../AnalisedeDocumentos/">ADD13</a>; <a href="../Observacao/">OBS21</a>; <a href="../Brainstorming/">BS40</a>; <a href="../Storytelling/">ST11</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos – Estado “Aplicativo instalado” & “Sincronizado com o portal”</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/cenario/">Cenário 5 – Bloquear dispositivo remotamente (necessidade de uptime)</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/">NFR Framework – Cartão RNF07 (Disponibilidade 24×7)</a>
</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../AnalisedeDocumentos/">ADD13</a>, <a href="../Observacao/">OBS21</a>, <a href="../Brainstorming/">BS40</a>, <a href="../Storytelling/">ST11</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 08 ============================= -->
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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Desempenho</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#desempenho">Especificação Suplementar – DES02 & DES04</a>; 
<a href="../AnalisedeDocumentos/">ADD14</a>; <a href="../Storytelling/">ST9</a>; <a href="../Brainstorming/">BS41</a>; <a href="../Brainstorming/">BS58</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso – UC01 Emitir Alerta</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos – verbo “Emitir” & objeto “Notificação”</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/cenario/">Cenário 5 – Bloquear remotamente</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/">NFR Framework – Cartão RNF09 (Tempo de Resposta)</a><br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us29">História de Usuário – US29</a>
</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../AnalisedeDocumentos/">ADD14</a>, <a href="../Storytelling/">ST9</a>, <a href="../Brainstorming/">BS41</a>, <a href="../Brainstorming/">BS58</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 09 ============================= -->
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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Segurança</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#seguranca">Especificação Suplementar – SEG01</a>; 
<a href="../AnalisedeDocumentos/">ADD15</a>; <a href="../Storytelling/">ST10</a>; <a href="../Brainstorming/">BS47</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso – UC08 Limpeza Remota com MFA</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos – objetos “Backup” & “Notificação” (criptografia / LGPD)</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/cenario/">Cenário 2 – Selecionar ações de segurança</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/">NFR Framework – Cartão RNF08 (Segurança / LGPD)</a>
</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../AnalisedeDocumentos/">ADD15</a>, <a href="../Storytelling/">ST10</a>, <a href="../Brainstorming/">BS47</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 10 ============================= -->
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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Legal / +</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td><a href="../AnalisedeDocumentos/">ADD18</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos – verbo “Solicitar” (sem custos)</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/cenario/">Cenário 3 – Registrar novo aparelho (fluxo sem cobrança)</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>-</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../AnalisedeDocumentos/">ADD18</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 11 ============================= -->
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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Legal / +</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#confiabilidade">Especificação Suplementar – CON05</a>; <a href="../AnalisedeDocumentos/">ADD19</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso – UC10 Gerenciar Contas Bancárias (Febraban)</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos – objeto “Chip” (normas Anatel)</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>-</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../AnalisedeDocumentos/">ADD19</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 12 ============================= -->
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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Usabilidade</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos</a>; <a href="../Brainstorming/">BS37</a>; <a href="../Storytelling/">ST8</a>; <a href="../AnalisedeDocumentos/">ADD16</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos – tabelas de noção/impacto (terminologia simplificada)</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/cenario/">Cenário 1 – Filtros intuitivos</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/">NFR Framework – Usabilidade</a>
</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../Brainstorming/">BS37</a>, <a href="../Storytelling/">ST8</a>, <a href="../AnalisedeDocumentos/">ADD16</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 13 ============================= -->
### RNF13
<details>
<summary>Layout consistente seguindo heurísticas de Nielsen.</summary>

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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Usabilidade</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#usabilidade">Especificação Suplementar – USA01</a>; <a href="../Brainstorming/">BS38</a>; <a href="../Storytelling/">ST8</a>; <a href="../AnalisedeDocumentos/">ADD16</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso – UC09 Editar Perfil & UC14 Feedback Visual</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos – objetos “Celular” & “Notificação” (consistência visual)</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/">NFR Framework – Cartão RNF05 (Layout Consistente)</a><br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us14">História de Usuário – US14</a>
</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../Brainstorming/">BS38</a>, <a href="../Storytelling/">ST8</a>, <a href="../AnalisedeDocumentos/">ADD16</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 14 ============================= -->
### RNF14
<details>
<summary>Tempo de resposta da interface &lt; 200 ms.</summary>

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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Desempenho</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/">NFR Framework</a>; 
<a href="../Brainstorming/">BS39</a>; <a href="../Storytelling/">ST9</a>; <a href="../AnalisedeDocumentos/">ADD14</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso – UC03 Localizar Celular (atualização em tempo real)</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/cenario/">Cenário 4 – Visualizar ocorrências em mapa</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/">NFR Framework – Cartão RNF07 (≤ 200 ms)</a>
</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../Brainstorming/">BS39</a>, <a href="../Storytelling/">ST9</a>, <a href="../AnalisedeDocumentos/">ADD14</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 15 ============================= -->
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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Usabilidade</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#usabilidade">Especificação Suplementar – USA03</a>; 
<a href="../Brainstorming/">BS42</a>; <a href="../Observacao/">OBS18</a>; <a href="../AnalisedeDocumentos/">ADD17</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso – UC11 Guia Pós-Furto (conteúdo multimídia)</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos – objeto “Notificação” (lida por leitor de tela)</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/">NFR Framework – Usabilidade</a>
</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../Brainstorming/">BS42</a>, <a href="../Observacao/">OBS18</a>, <a href="../AnalisedeDocumentos/">ADD17</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 16 ============================= -->
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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Usabilidade</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#usabilidade">Especificação Suplementar – USA02</a>; <a href="../Brainstorming/">BS44</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos – verbo “Emitir” (transcrição de fala → texto)</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso – UC03 Localizar (feedback de áudio → texto no mapa)</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>-</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../Brainstorming/">BS44</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 17 ============================= -->
### RNF17
<details>
<summary>Precisão de localização GPS menor do que 10 metros.</summary>

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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Desempenho</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/">NFR Framework</a>; 
<a href="../Brainstorming/">BS45</a>; 
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso</a>; 
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos</a>; 
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/cenario/">Cenários</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso – UC03 Localizar Celular</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos – verbo “Localizar” & objeto “Localização”</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/cenario/">Cenário 4 – Visualizar ocorrências em mapa</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/">NFR Framework – Cartão RNF11 (GPS ≤ 10 m)</a><br>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us37">História de Usuário – US37</a>
</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../Brainstorming/">BS45</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 18 ============================= -->
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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Segurança</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#seguranca">Especificação Suplementar – SEG02</a>; 
<a href="../Brainstorming/">BS48</a>; <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso – UC08 Limpeza Remota (exige MFA)</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos – objeto “Notificação” (código SMS)</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Backlog/#epico-3-conta--perfil">Backlog – Épico 3 / Feature 3.1 (2FA)</a>
</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../Brainstorming/">BS48</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 19 ============================= -->
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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Confiabilidade</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso</a>; <a href="../Brainstorming/">BS49</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso – UC06 Gerar Relatório PDF</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos – Estado “Tentativa de acesso detectada”</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us04">História de Usuário – US04</a>
</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../Brainstorming/">BS49</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 20 ============================= -->
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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Segurança</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/">NFR Framework</a>; <a href="../Brainstorming/">BS50</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso – UC10 Gerenciar Contas Bancárias (dados sensíveis)</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos – objeto “Backup” (proteção de dados)</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us18">História de Usuário – US18</a>
</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../Brainstorming/">BS50</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 21 ============================= -->
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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Confiabilidade</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#confiabilidade">Especificação Suplementar – CON07</a>; <a href="../Brainstorming/">BS53</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso – UC05 Backup via E-mail & UC13 Backup Periódico</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos – objeto “Backup” & estado “Backup ativo”</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>-</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../Brainstorming/">BS53</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 22 ============================= -->
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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Suportabilidade</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#suportabilidade">Especificação Suplementar – SUP02</a>; 
<a href="../Brainstorming/">BS57</a>; <a href="../AnalisedeDocumentos/">ADD17</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos – objeto “Celular” (múltiplos sistemas operacionais)</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/cenario/">Cenário 1 – Filtrar por tipo de celular</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/">NFR Framework – Suportabilidade</a>
</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../Brainstorming/">BS57</a>, <a href="../AnalisedeDocumentos/">ADD17</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 23 ============================= -->
### RNF23
<details>
<summary>Tempo de inicialização do app &lt; 2 segundos.</summary>

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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Desempenho</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#desempenho">Especificação Suplementar – DES03</a>; 
<a href="../Brainstorming/">BS58</a>; <a href="../Storytelling/">ST9</a>; <a href="../AnalisedeDocumentos/">ADD14</a><br>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/">NFR Framework</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos – estado “Aplicativo instalado”</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/cenario/">Cenário 3 – Registrar novo aparelho (fluxo rápido)</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/">NFR Framework – Desempenho</a>
</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../Brainstorming/">BS58</a>, <a href="../Storytelling/">ST9</a>, <a href="../AnalisedeDocumentos/">ADD14</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 24 ============================= -->
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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Confiabilidade</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#confiabilidade">Especificação Suplementar – CON04</a>; <a href="../Brainstorming/">BS60</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso – UC13 Backup Periódico (rotinas automáticas)</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos – estado “Backup ativo”</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>-</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../Brainstorming/">BS60</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 25 ============================= -->
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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Desempenho</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/#desempenho">Especificação Suplementar – DES02</a>; 
<a href="../Observacao/">OBS16</a>; <a href="../Brainstorming/">BS39</a>; <a href="../Storytelling/">ST9</a>; <a href="../AnalisedeDocumentos/">ADD14</a><br>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/">NFR Framework</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/cenario/">Cenário 4 – Visualizar ocorrências (mapa otimizado)</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso – UC06 Relatório PDF (carregamento rápido)</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/">NFR Framework – Desempenho</a>
</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../Observacao/">OBS16</a>, <a href="../Brainstorming/">BS39</a>, <a href="../Storytelling/">ST9</a>, <a href="../AnalisedeDocumentos/">ADD14</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 26 ============================= -->
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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Usabilidade</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/">NFR Framework</a>; <a href="../Observacao/">OBS19</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso – UC14 Feedback Visual (mensagens claras de erro)</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/">Léxicos – objeto “Notificação”</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us23">História de Usuário – US23</a>
</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../Observacao/">OBS19</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

</center>
</details>

<!-- ============================= RNF 27 ============================= -->
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
<tr><td style="text-align:center">Tipos de Elo</td><td><strong>Usabilidade</strong></td></tr>
<tr><td style="text-align:center">Satisfação</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/">NFR Framework</a>; 
<a href="../Observacao/">OBS20</a>; <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso</a></td></tr>
<tr><td style="text-align:center">Recurso</td><td>
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/">Casos de Uso – UC14 Feedback Visual</a>;  
<a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/cenario/">Cenário 2 – Selecionar ações (confirmação de bloqueio)</a>
</td></tr>
<tr><td style="text-align:center">Representação</td><td>-</td></tr>
<tr><td style="text-align:center">Alocado</td><td>
  <a href="https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us01">História de Usuário – US01</a>
</td></tr>
<tr><td style="text-align:center">Agregação</td><td>Requisito: <a href="../Observacao/">OBS20</a></td></tr>
</tbody>
</table>

<font>Fonte: <a href="https://github.com/arthurlleite">Arthur Carvalho</a>.</font>

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
| 1.4    | 08/02/2025         | Atualização da seção de pós-rastreabilidade, adição dos RNFs | <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a> | <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a> | 08/06/2025 |
| 1.5    | 08/02/2025         | Atualização da seção de pós-rastreabilidade, adição dos RFs | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a> | 08/06/2025 |
