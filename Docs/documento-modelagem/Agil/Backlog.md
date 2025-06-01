# Backlog

---

## Introdução

O Backlog de Produto organiza todas as funcionalidades e requisitos do Celular Seguro em uma lista priorizada, servindo de base para o planejamento das Sprints no Scrum. Por ser um artefato dinâmico, ele é continuamente refinado sempre que surgem novas informações ou feedback. O Dono do Produto é responsável por manter cada item com identificação única, critérios de aceitação claros, estimativa de esforço e prioridade definida pelo método Three Level Scale (Alta, Média ou Baixa). Assim, em cada Sprint Planning, a equipe sabe exatamente o que deve ser entregue para gerar valor incremental, alinhando segurança e usabilidade ao longo do desenvolvimento.


---

## Metodologia

Para elaborar o Backlog, iniciou-se pela elicitação de requisitos (entrevistas, análise documental, questionários), levantando necessidades funcionais e não funcionais. Requisitos de alto nível foram agrupados em épicos, depois decompostos em features e, em seguida, em histórias de usuário com critérios “Dado–Quando–Então”. O Dono do Produto e a equipe priorizaram cada história pelo método Three Level Scale (Alta, Média, Baixa), estimaram esforço em horas e, a cada Sprint, refinaram o Backlog em sessões de grooming, ajustando prioridades, detalhando itens e dividindo histórias conforme surgem novas informações.

---

<center>

*Tabela 1* - Product Backlog (Celular Seguro)  

<table>
  <thead>
    <tr>
      <th>Épico</th>
      <th>Feature</th>
      <th>História de usuário</th>
      <th>Priorização</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="8"><strong>Épico 1 – Cadastro de Dispositivos</strong></td>
      <td>Feature 1.1 – Cadastro de múltiplos celulares</td>
      <td><a href="../Historias_de_usuario#us00">US00</a> – Cadastro de múltiplos celulares</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>Feature 1.2 – Validação de número de celular</td>
      <td><a href="../Historias_de_usuario#us05">US05</a> – Validação do número de celular</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Feature 1.3 – Busca de dispositivo</td>
      <td><a href="../Historias_de_usuario#us06">US06</a> – Buscar dispositivo pelo app</td>
      <td>Média</td>
    </tr>
    <tr>
      <td rowspan="3">Feature 1.4 – Leitura de IMEI</td>
      <td><a href="../Historias_de_usuario#us19">US19</a> – Leitura do IMEI via câmera do celular</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td><a href="../Historias_de_usuario#us20">US20</a> – Concessão de permissão para leitura do IMEI</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td><a href="../Historias_de_usuario#us22">US22</a> – Consulta manual e direta do IMEI</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td rowspan="2">Feature 1.5 – Guia de consulta de IMEI</td>
      <td><a href="../Historias_de_usuario#us21">US21</a> – Guia de detalhes sobre consulta de celulares com restrições</td>
      <td>Média</td>
    </tr>
    <tr>
      <td><a href="../Historias_de_usuario#us24">US24</a> – Interface clara com instruções para consulta</td>
      <td>Média</td>
    </tr>
    <tr>
      <td rowspan="6"><strong>Épico 2 – Boletim de Ocorrência</strong></td>
      <td rowspan="3">Feature 2.1 – Registro de boletim</td>
      <td><a href="../Historias_de_usuario#us09">US09</a> – Registrar boletim de ocorrência</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td><a href="../Historias_de_usuario#us10">US10</a> – Validar campos obrigatórios do boletim</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td><a href="../Historias_de_usuario#us11">US11</a> – Exibir mensagem de erro em falha de envio</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>Feature 2.2 – Documentos e anexos</td>
      <td><a href="../Historias_de_usuario#us08">US08</a> – Anexar arquivos ao boletim</td>
      <td>Média</td>
    </tr>
    <tr>
      <td rowspan="2">Feature 2.3 – Confirmações e notificações</td>
      <td><a href="../Historias_de_usuario#us07">US07</a> – Confirmar envio do boletim com protocolo visível</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td><a href="../Historias_de_usuario#us12">US12</a> – Notificação de confirmação após envio do boletim</td>
      <td>Média</td>
    </tr>
    <tr>
      <td rowspan="6"><strong>Épico 3 – Conta &amp; Perfil</strong></td>
      <td>Feature 3.1 – Redefinir senha</td>
      <td><a href="../Historias_de_usuario#us13">US13</a> – Redefinir a senha via e-mail</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Feature 3.2 – Editar perfil</td>
      <td><a href="../Historias_de_usuario#us14">US14</a> – Editar o seu perfil</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Feature 3.3 – Alterar foto de perfil</td>
      <td><a href="../Historias_de_usuario#us15">US15</a> – Alterar a foto de perfil</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>Feature 3.4 – Registrar documentos</td>
      <td><a href="../Historias_de_usuario#us16">US16</a> – Registrar documentos</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Feature 3.5 – Definir dispositivo seguro</td>
      <td><a href="../Historias_de_usuario#us17">US17</a> – Definir dispositivo seguro</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Feature 3.6 – Termos de Uso</td>
      <td><a href="../Historias_de_usuario#us18">US18</a> – Fazer download do Termos de Uso</td>
      <td>Média</td>
    </tr>
    <tr>
      <td rowspan="4"><strong>Épico 4 – Comunicação &amp; Notificações</strong></td>
      <td rowspan="2">Feature 4.1 – Feedback visual</td>
      <td><a href="../Historias_de_usuario#us01">US01</a> – Feedback visual (toasts)</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td><a href="../Historias_de_usuario#us23">US23</a> – Validações de erro claras e rápidas</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>Feature 4.2 – Atividade suspeita</td>
      <td><a href="../Historias_de_usuario#us02">US02</a> – Notificação de atividade suspeita</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Feature 4.3 – Envio de SMS</td>
      <td><a href="../Historias_de_usuario#us03">US03</a> – SMS após ação remota</td>
      <td>Baixa</td>
    </tr>
    <tr>
      <td rowspan="6"><strong>Épico 5 – Pessoa de Confiança</strong></td>
      <td>Feature 5.1 – Notificar pessoa de confiança</td>
      <td><a href="../Historias_de_usuario#us31">US31</a> – Notificar Pessoa de Confiança</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Feature 5.2 – Importar da agenda</td>
      <td><a href="../Historias_de_usuario#us32">US32</a> – Importar Pessoa de Confiança da agenda</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Feature 5.3 – Cadastrar manualmente</td>
      <td><a href="../Historias_de_usuario#us33">US33</a> – Cadastrar Pessoa de Confiança manualmente</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Feature 5.4 – Visualizar lista</td>
      <td><a href="../Historias_de_usuario#us34">US34</a> – Visualizar lista de Pessoas de Confiança</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Feature 5.5 – Pesquisar contato</td>
      <td><a href="../Historias_de_usuario#us35">US35</a> – Pesquisar Pessoa de Confiança</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>Feature 5.6 – Remover contato</td>
      <td><a href="../Historias_de_usuario#us36">US36</a> – Remover Pessoa de Confiança</td>
      <td>Alta</td>
    </tr>
  </tbody>
</table>

</center>

<font size="3"><p style="text-align: center">Fonte: [Leonardo de Melo](https://github.com/leozinlima)</p></font>

---

## Temas

* **Funcionalidades**
  Agrupa épicos relacionados às ações diretas do usuário no aplicativo Celular Seguro:

  * **Cadastro de Dispositivos**, permitindo registrar e validar múltiplos celulares e consultar IMEI;
  * **Boletim de Ocorrência**, para registrar, anexar documentos e receber confirmação de protocolo;
  * **Conta & Perfil**, que inclui redefinir senha, editar dados pessoais, alterar foto de perfil, registrar documentos e marcar dispositivo seguro;
  * **Comunicação & Notificações**, garantindo feedback visual, envio de SMS e notificações push em atividades suspeitas;
  * **Pessoa de Confiança**, para cadastrar, visualizar, pesquisar e remover contatos de confiança.

* **Qualidade & Confiabilidade**
  Engloba requisitos técnicos e não funcionais que garantem experiência segura e estável:

  * **Desempenho** nas buscas de IMEI e consulta de boletins;
  * **Segurança**, com criptografia de dados sensíveis em trânsito e em repouso, autenticação de dois fatores e validações de formato;
  * **Acessibilidade**, oferecendo alto contraste, opções de audiodescrição e suporte a troca de idioma;
  * **Feedback Visual**, exibindo toasts e modais claros para cada etapa sensível do fluxo.

---

## Épicos

Após a definição dos temas, os requisitos de alto nível do Celular Seguro são decompostos em **épicos** para reduzir ainda mais a abstração das atividades a serem realizadas. Cada épico representa um conjunto relacionado de funcionalidades e, por sua vez, é detalhado em **features** que descrevem subconjuntos de funcionalidades intermediárias. Para o Celular Seguro, temos:

* **Épico 1 – Cadastro de Dispositivos**: abrange o registro, validação e consulta de celulares (incluindo leitura e guia de IMEI).
* **Épico 2 – Boletim de Ocorrência**: reúne o fluxo de registro de boletim, anexos e confirmações/ notificações de protocolo.
* **Épico 3 – Conta & Perfil**: inclui redefinir senha por e-mail, editar dados pessoais, alterar foto de perfil, registrar documentos, definir dispositivo confiável e acessar Termos de Uso.
* **Épico 4 – Comunicação & Notificações**: trata do feedback visual no app, envio de SMS e notificações push em casos de atividade suspeita.
* **Épico 5 – Pessoa de Confiança**: cobre o cadastro, importação, listagem, pesquisa e remoção de contatos de confiança.

---

## Features

Definido cada épico, são geradas _features_, que descrevem de forma simplificada as funcionalidades que o Celular Seguro deve oferecer para atender aos objetivos dos usuários. Elas situam-se entre o nível abstrato dos épicos e o detalhamento das histórias de usuário:

1. **Épico 1 – Cadastro de Dispositivos**

    - **Feature 1.1 – Cadastro de múltiplos celulares**: permite ao usuário registrar vários números de celular vinculados ao mesmo CPF.  
    - **Feature 1.2 – Validação de número de celular**: envia código de verificação por SMS ou e-mail para confirmar que o número informado pertence ao usuário.  
    - **Feature 1.3 – Busca de dispositivo**: exibe localização aproximada do aparelho perdido ou roubado, usando dados de GPS/IMEI.  
    - **Feature 1.4 – Leitura de IMEI**: faz a leitura automática do IMEI por meio da câmera do celular, solicita permissões nativas e oferece inserção manual.  
    - **Feature 1.5 – Guia de consulta de IMEI**: apresenta instruções e explicações sobre tipos de restrições e procedimentos para consulta.  

2. **Épico 2 – Boletim de Ocorrência**

    - **Feature 2.1 – Registro de boletim**: disponibiliza formulário para o preenchimento dos dados de roubo/perda, com validação de campos obrigatórios.  
    - **Feature 2.2 – Documentos e anexos**: permite anexar imagens ou documentos (JPG, PNG, PDF) ao boletim antes do envio.  
    - **Feature 2.3 – Confirmações e notificações**: exibe número de protocolo após o envio e envia notificação push ou SMS de confirmação mesmo com o app em segundo plano.  

3. **Épico 3 – Conta & Perfil**

    - **Feature 3.1 – Redefinir senha**: possibilita ao usuário solicitar e inserir um código recebido por e-mail (ou SMS) para criar nova senha sem sair do aplicativo.  
    - **Feature 3.2 – Editar perfil**: oferece aba “Perfil” fixa no menu onde o usuário pode alterar nome, e-mail, telefones e senha com validações em tempo real.  
    - **Feature 3.3 – Alterar foto de perfil**: disponibiliza botão para capturar ou escolher foto na galeria, com ferramenta de corte e pré-visualização antes de salvar.  
    - **Feature 3.4 – Registrar documentos**: exibe seção “Documentos” no perfil para cadastrar CPF, RG e outros, validando formato e permitindo remoção.  
    - **Feature 3.5 – Definir dispositivo seguro**: permite marcar o aparelho atual como confiável, evitando autenticações extras em logins futuros, e desmarcar quando desejar.  
    - **Feature 3.6 – Termos de Uso**: disponibiliza botão de download de PDF dos Termos de Uso, contendo versão e data, com tratamento para falha de conexão.  

4. **Épico 4 – Comunicação & Notificações**

    - **Feature 4.1 – Feedback visual**: exibe toasts de sucesso ou erro imediatamente após ações críticas (ex.: cadastro, envio de boletim).  
    - **Feature 4.2 – Atividade suspeita**: envia notificação push sempre que o sistema identificar comportamento anômalo no acesso ou uso do dispositivo.  
    - **Feature 4.3 – Envio de SMS**: dispara mensagem de texto em eventos relevantes, como confirmação de redefinição de senha ou bloqueio remoto do aparelho.  

5. **Épico 5 – Pessoa de Confiança**

    - **Feature 5.1 – Notificar pessoa de confiança**: envia SMS automático ao cadastrar um contato de confiança, informando que ele foi designado.  
    - **Feature 5.2 – Importar da agenda**: permite ao usuário buscar e selecionar contatos diretamente da lista de contatos do dispositivo.  
    - **Feature 5.3 – Cadastrar manualmente**: disponibiliza formulário com campos para nome e telefone ao registrar um contato sem usar agenda.  
    - **Feature 5.4 – Visualizar lista**: exibe todos os contatos de confiança cadastrados em uma lista organizada, com acesso rápido a detalhes.  
    - **Feature 5.5 – Pesquisar contato**: oferece campo de busca que filtra a lista de contatos em tempo real, facilitando encontrar um nome específico.  
    - **Feature 5.6 – Remover contato**: permite excluir um contato de confiança com confirmação explícita antes de remover da lista.  

---

### Histórias de Usuário

As Histórias de Usuário no Celular Seguro detalham ainda mais as funcionalidades descritas nas features e estão todas reunidas na seção de [Histórias de Usuário](../Historias_de_usuario). Cada história apresenta de forma concisa o que o usuário deseja realizar e por que isso é importante, seguindo sempre o formato:

> **“Como \[Perfil], eu quero \[Ação] para que \[Benefício]”**

Por meio dessas narrativas, descrevem-se cenários como redefinir senha, editar perfil, registrar documentos, consultar IMEI, enviar boletim de ocorrência, notificar pessoa de confiança e receber alertas de atividade suspeita, todos com critérios de aceitação que garantem quando cada funcionalidade pode ser considerada concluída.

---

### Épico 1 – Cadastro de Dispositivos

Este épico reúne as funcionalidades que permitem ao usuário registrar, validar e consultar seus aparelhos móveis dentro do aplicativo. Abrange desde o cadastro de múltiplos celulares associados ao mesmo CPF até a leitura de IMEI, seja por câmera ou manualmente. A história de usuário a seguir o generaliza:

<center>
> **"Como usuário do Celular Seguro, eu desejo registrar e validar meus dispositivos para que eu possa consultar o IMEI e garantir a segurança em caso de perda ou roubo."**
</center>

### Épico 2 – Boletim de Ocorrência

Este épico reúne as funcionalidades que permitem ao usuário registrar formalmente a perda ou o roubo de um dispositivo, anexar documentos comprobatórios e receber confirmação com número de protocolo.

<center>  
> **"Como usuário do Celular Seguro, eu desejo registrar um boletim de ocorrência por meio do aplicativo para que eu possa formalizar o incidente e obter um protocolo de atendimento."**  
</center>

### Épico 3 – Conta & Perfil

Este épico engloba as funcionalidades que permitem ao usuário gerenciar suas credenciais e informações pessoais dentro do aplicativo Celular Seguro. Inclui desde redefinir senha e editar dados de perfil até alterar foto, cadastrar documentos e definir dispositivo confiável, garantindo que o usuário mantenha suas informações seguras e atualizadas.

<center>  
> **"Como usuário do Celular Seguro, eu desejo gerenciar meus dados de conta e perfil para que eu possa manter minhas informações atualizadas e aumentar a segurança de acesso."**  
</center>  

### Épico 4 – Comunicação & Notificações

Este épico agrupa as funcionalidades que garantem a segurança do usuário por meio de alertas, feedback visual e envio de mensagens em situações críticas, evitando que ele deixe passar ações suspeitas ou falhas no processo.

<center>  
> **"Como usuário do Celular Seguro, eu desejo receber notificações e feedback imediato em casos de atividade suspeita ou erro, para que eu possa tomar providências rapidamente e evitar consequências indesejáveis."**
</center>  

### Épico 5 – Pessoa de Confiança

Este épico enfatiza as funcionalidades que tornam o fluxo de emergência mais eficiente e intuitivo, permitindo ao usuário designar contatos de confiança de forma rápida e organizada. As características garantem que, em situações críticas, o acesso a essa informação seja imediato, reduzindo o tempo de resposta e aumentando a confiabilidade do sistema. Além disso, a interface para gerenciar esses contatos é clara e simples, facilitando o uso sem curva de aprendizado.

<center>  
> **"Como usuário do Celular Seguro, eu desejo cadastrar e gerenciar facilmente meus contatos de confiança para que, em caso de emergência, eu possa notificar rapidamente as pessoas certas."**
</center>  

---
## Bibliografia

> **WIEGERS, Karl E.; BEATTY, Joy.** _Software Requirements — Third Edition_. Microsoft Press, 2013.  
> **SCRUM GUIDE.** _The Definitive Guide to Scrum_. Scrum.org e Scrum Alliance, 2020.  
> **COHN, Mike.** _User Stories Applied: For Agile Software Development_. Addison-Wesley, 2004.  
> **LEFFINGWELL, Dean.** _Agile Software Requirements: Lean Requirements Practices for Teams, Programs, and the Enterprise_. Addison-Wesley, 2011.  
> **SOMMERVILLE, Ian.** _Software Engineering_ (10ª ed.). Pearson, 2019.

---

## Histórico de Versões

| Versão | Data de Produção | Descrição da Alteração | Autor(es) | Revisor(es) | Data de Revisão |
|:------:|:----------------:|:----------------------:|:---------:|:-----------:|:--------------:|
| 1.0 | 22/05/2025 | Versão inicial do documento | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a>, <a style="color:gold;" href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a> | 22/05/2025 |
| 1.1 | 01/06/2025 | Criação do backlog | <a style="color:gold;" href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a> | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | 01/06/2025 |
| 1.2 | 01/06/2025 | Padronização da documentação | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | <a style="color:gold;" href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a> | 01/06/2025 |
| 1.3 | 01/06/2025 | Ajustes nos textos e mudanças de épicos | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | <a style="color:gold;" href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a> | 01/06/2025 |