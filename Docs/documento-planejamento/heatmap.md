<span style="background-color:#2c2c7c; color:white; font-size:0.8em; font-weight: bold; padding:2px 6px; border-radius:4px;">Versão 1.3</span>

# Heatmap de Disponibilidade

---

## Introdução

O **heatmap de disponibilidade** é uma ferramenta visual essencial para equipes que buscam otimizar a coordenação e maximizar a produtividade. Ele permite identificar de forma rápida e eficiente os horários e dias em que os membros da equipe estão disponíveis para colaborar. Em contextos de trabalho flexível, especialmente em equipes remotas ou distribuídas, essa ferramenta se torna ainda mais relevante para facilitar a organização de tarefas, reuniões e atividades colaborativas. Ao consolidar as informações de disponibilidade dos integrantes, o heatmap oferece insights valiosos para uma melhor alocação de tempo e recursos, promovendo decisões mais ágeis e eficazes.

!!! Warning "Atenção!"
    O conteúdo deste tópico **poderá sofrer alterações** ao longo da Disciplina de Requisitos de Software. Portanto, as tabelas serão organizadas iniciando pela versão mais recente e finalizando com a versão mais antiga.

## Integrantes que atuaram no desenvolvimento do artefato

Esta tabela inicial terá somente os artefatos de alta relevância que cada integrante do projeto desenvolveu. O versionamento **completo** encontra-se ao final do artefato.

<font size="3"><p style="text-align: center">_Desenvolvimento do Artefato_</p></font>

| Nome | Função |
| :--- | :--- |
| [<span style="color:gold;">repolhudo</span>](https://github.com/repolho) | Autor das seguintes tabelas: [[ Tabela 1 ]](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-validacao/documentacao-artefatosAnteriores/#tabela-1-refatoracao-das-inspecoes-internas-anteriores)|
| [<span style="color:gold;">repolhudo junior</span>](https://github.com/arthurlleite) | Revisor do Artefato |

!!! Tip "Observação"
    Frizando claramente que as contribuições de cada integrante ainda que mínimas são ainda sim muito relevantes no desenvolvimento do artefo, considere verificar o histórico de versão. 

---

### Objetivo

O objetivo principal do heatmap de disponibilidade é maximizar a colaboração e a produtividade da equipe, proporcionando uma visão clara dos momentos em que todos os membros estão disponíveis simultaneamente. Essa visão facilita a organização de reuniões, sessões de brainstorming e outras atividades cruciais para o sucesso do projeto.

---

## Heatmap

A **Figura 1** e a **Tabela 1** a seguir representam a análise de disponibilidade do grupo. Os valores numéricos variam de 0 a 7, indicando o número de membros disponíveis em cada faixa horária.

<div align="center">
  <font size="3">
    <p style="text-align: center"><b>Figura 1:</b> Heatmap de disponibilidade da equipe</p>
  </font>
</div>

<div align="center">
  <img src="../../assets/img/HeadMap (1).png" alt="Heatmap de Disponibilidade" width="800px">
</div>

<font size="3"><p style="text-align: center">_Fonte: [Arthur Carvalho](https://github.com/arthurlleite) _</p></font>

---

<div align="center">
  <font size="3">
    <p style="text-align: center"><b>Tabela 1:</b> Mapeamento numérico de disponibilidade por horário</p>
  </font>
</div>

<div align="center">
  <table border="1" cellpadding="5">
    <thead>
      <tr>
        <th>Hora</th>
        <th>Segunda</th>
        <th>Terça</th>
        <th>Quarta</th>
        <th>Quinta</th>
        <th>Sexta</th>
        <th>Sábado</th>
        <th>Domingo</th>
      </tr>
    </thead>
    <tbody>
      <tr><td>08:00 - 09:00</td><td>0</td><td>0</td><td>1</td><td>0</td><td>0</td><td>2</td><td>2</td></tr>
      <tr><td>09:00 - 10:00</td><td>0</td><td>0</td><td>1</td><td>0</td><td>0</td><td>2</td><td>3</td></tr>
      <tr><td>10:00 - 11:00</td><td>0</td><td>0</td><td>1</td><td>0</td><td>0</td><td>2</td><td>3</td></tr>
      <tr><td>11:00 - 12:00</td><td>0</td><td>0</td><td>1</td><td>0</td><td>0</td><td>2</td><td>2</td></tr>
      <tr><td>12:00 - 13:00</td><td>0</td><td>1</td><td>0</td><td>1</td><td>1</td><td>2</td><td>1</td></tr>
      <tr><td>13:00 - 14:00</td><td>1</td><td>1</td><td>0</td><td>1</td><td>1</td><td>3</td><td>1</td></tr>
      <tr><td>14:00 - 15:00</td><td>2</td><td>2</td><td>1</td><td>2</td><td>3</td><td>4</td><td>3</td></tr>
      <tr><td>15:00 - 16:00</td><td>5</td><td>2</td><td>1</td><td>2</td><td>3</td><td>4</td><td>3</td></tr>
      <tr><td>16:00 - 17:00</td><td>5</td><td>5</td><td>4</td><td>1</td><td>4</td><td>5</td><td>4</td></tr>
      <tr><td>17:00 - 18:00</td><td>5</td><td>2</td><td>3</td><td>1</td><td>3</td><td>2</td><td>4</td></tr>
      <tr><td>18:00 - 19:00</td><td>5</td><td>3</td><td>3</td><td>3</td><td>3</td><td>2</td><td>2</td></tr>
      <tr><td>19:00 - 20:00</td><td>5</td><td>4</td><td>4</td><td>3</td><td>3</td><td>2</td><td>2</td></tr>
      <tr><td>20:00 - 21:00</td><td>6</td><td>5</td><td>4</td><td>3</td><td>4</td><td>2</td><td>3</td></tr>
      <tr><td>21:00 - 22:00</td><td>6</td><td>6</td><td>3</td><td>5</td><td>4</td><td>2</td><td>3</td></tr>
      <tr><td>22:00 - 23:00</td><td>6</td><td>5</td><td>6</td><td>4</td><td>4</td><td>3</td><td>2</td></tr>
      <tr><td>23:00 - 00:00</td><td>2</td><td>2</td><td>5</td><td>1</td><td>1</td><td>0</td><td>3</td></tr>
    </tbody>
  </table>
</div>

<font size="3"><p style="text-align: center">_Fonte: [Arthur Carvalho](https://github.com/arthurlleite) _</p></font>


---

## Bibliografia

> GOOGLE. Heatmap de Disponibilidade da Equipe. Google Sheets, 2025. Acesso em: 11 abr. 2025.

---

## Histórico de Versões

| Versão | Data de produção   | Descrição da Alteração                               | Autor(es)             | Revisor(es)      |Data de Revisão |
| :----: | :----------------: | :--------------------------------------------------: | :-------------------: | :-------------:  |  :-----------: |
| 1.0    | 11/04/2025         | Criação da seção de heatmap                          |<a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a>|<a style="color:gold;" href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>| 11/04/2025|
| 1.1    | 16/04/2025         | Adição dos autores do cronograma                     | <a style="color:gold; href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> |<a style="color:gold;" href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>, <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | 16/04/2025|
| 1.2    | 23/04/2025         | Padronização do Histórico de Versões e da Bibliografia|<a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a>|<a style="color:gold;" href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>| 23/04/2025|
| 1.3    | 08/05/2025| Padronização do Histórico de Versões| <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a>| <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a>| 08/05/2025|

