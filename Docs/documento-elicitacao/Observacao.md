# Observação

---

## Metodologia

Para a realização da atividade, foi utilizada uma abordagem prática e simulada da técnica de observação. A execução foi feita por dois integrantes do grupo: um assumiu o papel de usuário [Daniel Rodrigues](https://github.com/zDrNz), interagindo com o aplicativo Celular Seguro como se estivesse em uma situação real de uso, enquanto o outro atuou como observador [Gabriel Lima](https://github.com/gabriel-lima258), acompanhando atentamente as ações realizadas, registrando dificuldades encontradas, comportamentos notáveis e possíveis melhorias. Essa simulação permitiu levantar requisitos de forma realista, mesmo sem a participação de um agente externo, garantindo a efetividade da técnica dentro do contexto acadêmico.

---

## Participantes

<center>

<font size="3"><p style="text-align: center">Tabela 1: Participantes da sessão de observação e suas funções.</p></font>


| Nome                                             | Função                   |
| ------------------------------------------------ | ------------------------ |
| [Gabriel Lima](https://github.com/gabriel-lima258),  [Arthur Carvalho](https://github.com/arthurlleite)    | Observadores           |
| [Daniel Rodrigues](https://github.com/zDrNz) | Usuário |


<font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258),  [Arthur Carvalho](https://github.com/arthurlleite) e [Daniel Rodrigues](https://github.com/zDrNz).</p></font>

</center>

**Usuário:** responsável por utilizar o aplicativo e suas funcionalidades, para que possa ser encontrados possíveis problemas no aplicativo.

**Observador:** responsável por registrar as funcionalidades possíveis de serem executadas e as que estão com algum tipo de problema ou não existem. 

---

## Gravação

<div style="text-align: center;">
  <p><strong>Vídeo: </strong> <a href="https://player.vimeo.com/video/1081298512?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479"> Observação - Requisitos</a></p>
  <div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/1081298512?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write; encrypted-media" style="position:absolute;top:0;left:0;width:100%;height:100%;" title="Observação-Video"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>
</div>

<font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258),  [Arthur Carvalho](https://github.com/arthurlleite) e [Daniel Rodrigues](https://github.com/zDrNz).</p></font>

## Tabela de Requisitos Funcionais

Durante o que foi observado, foram definidos os **Requisitos Funcionais (RF)** do sistema Celular Seguro. Estes representam funcionalidades ou comportamentos **necessários** que o aplicativo tem que proporcionar. A **Tabela 2** abaixo lista os requisitos funcionais identificados, com um identificador numérico, uma breve descrição, um código de referência (RFx) e se o requisito já está implementado ou não no sistema.

<font size="3"><p style="text-align: center">Tabela 2: Requisitos Funcionais identificados para o Celular Seguro.</p></font>

| **ID** | **Descrição do Requisito Funcional**                                   | **Código (RFx)** | **Implementado?** |
|:-------:|-------------------------------------------------------------------------|:------------------:|:-------------------:|
| OBS1     | O sistema permite que o usuário realize um cadastro com nome, e-mail e senha (pelo [GOV.br](https://www.gov.br/governodigital/pt-br/identidade/assinatura-eletronica/baixar-app-govbr)) | RF1 | Sim |
| OBS2     | O sistema exige login com e-mail e senha para acessar as funcionalidades principais (pelo [GOV.br](https://www.gov.br/governodigital/pt-br/identidade/assinatura-eletronica/baixar-app-govbr)). | RF2 | Sim |
| OBS3     | Existe a funcionalidade de redefinir a senha via e-mail. | RF3 | Sim |
| OBS4     | O aplicativo envia notificações push para alertar sobre eventos ou atualizações. | RF4 | Sim |
| OBS5     | O usuário pode visualizar relatórios com histórico de ações realizadas. | RF5 | Sim |
| OBS6     | O sistema disponibiliza uma aba que te leva a um pdf com um tutorial do aplicativo. | RF6 | Sim |
| OBS7     | Pode adicionar contato de confiança após a perda ou roubo do aparelho. | RF7 | Não |
| OBS8     | Dentro do aplicativo, é possível registar um boletim de ocorrência. | RF8 | Sim |
| OBS9     | Ao tentar emitir um alerta de roubo, o sistema exibe uma janela pop-up solicitando a confirmação do usuário antes de prosseguir com a ação. | RF9 | Não |
| OBS10     | Pelo MEI do aparelho, é possível consultar o status do celular e saber se ele se encontra como um celular roubado, furtado, etc ( irregular). | RF10 | Sim |
| OBS11     | O usuário  pode registrar o seu celular e mais outros celulares no banco de dados do aplicativo. | RF11 | Sim |
| OBS12     | É possível editar o seu perfil por uma aba que é disponibilizada no aplicativo. | RF12 | Não |
| OBS13     | O Usuário é redirecionado para uma aba referente à busca do dispositivo indicado para o sistema ao qual o aparelho é moldado (exemplo: se a pessoa tiver um iphone, será redirecionado para o “buscar” no icloud) | RF13 | Sim |
| OBS14     | Existe uma opção para mostrar os termos de uso do aplicativo. | RF14 | Sim |

<font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258),  [Arthur Carvalho](https://github.com/arthurlleite) e [Daniel Rodrigues](https://github.com/zDrNz).</p></font>

*Legenda:* 

- ID – Identificador numérico do requisito. 
- Descrição – definição concisa da funcionalidade exigida. 
- Código (RFx) – código de referência do Requisito Funcional (RF) seguido de um número sequencial. 
- Implementado? – indica se o requisito está implementado no sistema atualmente (Sim) ou não (Não). 

---

## Tabela de Requisitos Não Funcionais

Além das funções, foram identificados também alguns **Requisitos Não Funcionais (RNF)** relevantes para o Celular Seguro. Estes requisitos descrevem restrições de qualidade e critérios sobre *como* o sistema deve se comportar ou quais padrões deve seguir (desempenho, usabilidade, etc.), em vez de funcionalidades em si. A **Tabela 3** apresenta os requisitos não funcionais elicitados, com identificador, descrição, código (RNFx) e status de implementação.

<font size="3"><p style="text-align: center">Tabela 3: Requisitos Não Funcionais identificados para o Celular Seguro.</p></font>

| **ID** | **Descrição do Requisito Não Funcional**                              | **Código (RNFx)** | **Implementado?** |
|:-------:|-----------------------------------------------------------------------|:-------------------:|:-------------------:|
| OBS15     | O aplicativo apresenta uma interface amigável e intuitiva, com ícones bem definidos e menus acessíveis. | RNF1 | Sim|
| OBS16     | As páginas carregam em até 2 segundos em conexões padrão 4G.| RNF2 | Sim |
| OBS17     | O login via Gov.br oferece autenticação eficaz para todos os níveis de conta. | RNF3 | Não |
| OBS18     | O aplicativo é acessível para pessoas com deficiência visual (uso de leitor de tela, contraste, tamanho da fonte). | RNF4 | Não |
| OBS19     | O aplicativo responde corretamente mesmo com entradas erradas | RNF5 | Não |
| OBS20     | O aplicativo apresenta confirmação de suas ações. | RNF6 | Sim |
| OBS21     | O aplicativo está disponível 24/7, com raras quedas detectadas durante a observação. | RNF7 | Não |

<font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258),  [Arthur Carvalho](https://github.com/arthurlleite) e [Daniel Rodrigues](https://github.com/zDrNz).</p></font>


*Legenda:* 

- ID – Identificador numérico do requisito. 
- Descrição – detalhamento do critério de qualidade ou restrição. 
- Código (RNFx) – código de referência do Requisito Não Funcional (RNF) com numeração sequencial. 
- Implementado? – indica se o requisito já se encontra implementado (Sim) ou não (Não). 

---

## Legenda Geral

- **RF – Requisito Funcional:** descreve **o que** o sistema deve fazer. É uma funcionalidade ou serviço que o sistema deve prover para atender às necessidades do usuário ou do negócio (por exemplo, *“bloquear remotamente o dispositivo”*).  
- **RNF – Requisito Não Funcional:** descreve **como** o sistema deve se comportar ou quais restrições de qualidade ele deve obedecer. Engloba atributos como usabilidade, desempenho, segurança, confiabilidade, etc.
- **OBS – (Observação) Palavra-chave da sessão:** código associado às **palavras-chave** ou ideias brutas geradas na sessão de Observação. Cada *OBSx* corresponde a algo identificado na observação, utilizado para rastrear a origem das discussões e auxiliar na derivação dos requisitos correspondentes.

---

## Bibliográfia

  > SOMMERVILLE, Ian. Engenharia de Software. 10. ed. São Paulo: Pearson, 2019.
  > SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. **UnB Gama**, Brasília, 2023. Disponível em: <<https://aprender3.unb.br/pluginfile.php/2580553/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>>. Acesso em: 29/04/2023.

---

## Histórico de Versões

| Versão | Data de Produção | Descrição da Alteração | Autor(es) | Revisor(es) | Data de Revisão |
| :----: | :--------------: | :-------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------: | :-------------: |
| 1.0    | 01/05/2025       | Documento inicial de observação do projeto Celular Seguro | <a style="color:gold;" href="https://github.com/zDrNz" target="_blank">Daniel Rodrigues</a> | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a>|02/05/2025|
| 1.1    | 02/05/2025       | Inserção do vídeo e dos RFs e RNFs | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> |<a style="color:gold;" href="https://github.com/zDrNz" target="_blank">Daniel Rodrigues</a> |02/05/2025|
| 1.2    | 04/05/2025       | Correção do link do video | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> |<a style="color:gold;" href="https://github.com/zDrNz" target="_blank">Daniel Rodrigues</a> |04/05/2025|
