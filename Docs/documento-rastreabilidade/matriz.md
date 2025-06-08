# Matriz Geral de Rastreabilidade
---
### Introdução

A **matriz geral de rastreabilidade** é um artefato essencial na engenharia de requisitos que permite representar, de forma consolidada, os requisitos funcionais identificados ao longo do projeto, juntamente com sua **pré e pós-rastreabilidade**. A proposta é fornecer uma **visão integrada e sistemática** dos vínculos entre os requisitos, suas origens (como técnicas de elicitação) e os artefatos derivados ou relacionados.

De acordo com Sayão e Leite (2005), a rastreabilidade é o mecanismo que viabiliza a ligação entre os diversos elementos envolvidos no ciclo de vida de um sistema, incluindo requisitos, documentos, decisões e implementações. A matriz geral viabiliza essa conexão por meio de **referências cruzadas e elos rastreáveis**, revelando **dependências**, **origens documentais** e **impactos** que cada requisito pode ter em diferentes fases do desenvolvimento.

Dessa forma, a matriz não apenas favorece a **compreensão e análise sistêmica dos requisitos**, como também contribui para a **gestão de mudanças**, o **controle de qualidade** e a **manutenção evolutiva** do sistema ao longo do tempo.

---

### Objetivos

O objetivo da matriz geral é consolidar as informações dos artefatos de **Backward-Form** (rastreabilidade retroativa) e **Forward-Form** (rastreabilidade prospectiva), proporcionando uma **visão unificada** do ciclo de vida dos requisitos. Através dessa unificação, é possível:

- Verificar se todos os requisitos têm origem justificada (pré-rastreabilidade);
- Avaliar o estado de implementação de cada funcionalidade;
- Mapear os artefatos técnicos relacionados a cada requisito;
- Identificar **elos** e **interdependências** que auxiliam na análise de impacto.

Essa estrutura oferece um ponto central de consulta, facilitando o acompanhamento e a validação dos requisitos em todas as fases do projeto.

---

### Metodologia

A construção da matriz geral partiu dos **requisitos elicitados** no projeto, especialmente aqueles que ainda não estavam completamente implementados no momento da análise. Esses requisitos foram cruzados com os dados coletados nos artefatos de rastreabilidade backward e forward, permitindo a composição de uma tabela unificada.

A matriz geral é organizada em **sete colunas**, com os seguintes significados:

- **ID**: Identificador único do requisito funcional.
- **Descrição**: Texto descritivo que expressa claramente o comportamento esperado do sistema.
- **Pré-Rastreabilidade**: Técnicas e artefatos de elicitação (como questionários, storytelling ou análise de documentos) que fundamentam o requisito.
- **Implementado?**: Indicação do status de implementação no aplicativo (Sim, Não, Parcialmente).
- **Artefatos**: Representações técnicas ou documentais que detalham ou se relacionam diretamente com o requisito.
- **Elos**: Ligações semânticas entre os requisitos e outros elementos (outros requisitos, funcionalidades, testes, etc.), indicando dependência, influência ou refinamento.

Esta matriz representa, portanto, uma peça-chave no processo de **documentação e rastreamento completo dos requisitos**, apoiando práticas de desenvolvimento ágil, melhoria contínua e validação sistemática.

---

# Requisitos funcionais

<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 1</b> - Requisitos funcionais</p>

| ID   | Descrição                                                                                                                                                              | Rastreabilidade                                                                                                       | Implementação | Artefatos | Elos |
| ---- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- | ------------- | --------- | ---- |
| RF01 | O aplicativo deve permitir localizar o celular perdido.                                                                                                                | <a href="../Questionario/">QS01</a>, <a href="../Storytelling/">ST06</a>, <a href="../AnalisedeDocumentos/">ADD01</a> | Sim | Casos de Uso, Léxicos |      |
| RF02 | O aplicativo deve tornar visível e acessível a opção de registro de boletim de ocorrência.                                                                             | <a href="../Questionario/">QS02</a>, <a href="../Observacao/">OBS02</a>                                               | Sim           |     Casos de Uso, Léxicos         |      |
| RF03 | O aplicativo permite acessar ou cancelar contas bancárias vinculadas ao aparelho.                                                                                      | <a href="../Questionario/">QS03</a>, <a href="../Brainstorming/">BS03</a>                                             | Não           |    Casos de Uso       |      |
| RF04 | O aplicativo deve oferecer o passo a passo do que fazer após um furto ou roubo.                                                                                        | <a href="../Questionario/">QS04</a>, <a href="../AnalisedeDocumentos/">ADD02</a>                                      | Não           |   Casos de Uso, Léxicos        |      |
| RF05 | O aplicativo deve fornecer confirmação visual (feedback) ao usuário após realizar ações importantes.                                                                   | <a href="../Questionario/">Q12</a>, <a href="../Brainstorming/">BS04</a>                                              | Não           |           |      |
| RF06 | O aplicativo deve notificar o usuário em caso de atividade suspeita relacionada ao dispositivo.                                                                        | <a href="../Questionario/">QS08</a>, <a href="../Brainstorming/">BS06</a>                                             | Não           |   Léxico        |      |
| RF07 | O aplicativo deve permitir a recuperação do aparelho bloqueado caso reencontrado.                                                                                      | <a href="../Questionario/">QS08</a>, <a href="../Storytelling/">ST03</a>                                              | Não           |  Léxico         |      |
| RF08 | O aplicativo deve permitir que o usuário registre um boletim de ocorrência.                                                                                            | <a href="../Questionario/">QS09</a>, <a href="../AnalisedeDocumentos/">ADD03</a>                                      | Sim           |           |      |
| RF09 | Modo Falso Desligamento/Fake Shutdown. Simular que o celular foi desligado quando, na verdade, continua rastreável e operacional para comandos remotos.                | <a href="../Questionario/">QS14</a>, <a href="../Brainstorming/">BS07</a>                                             | Não           |           |      |
| RF10 | O sistema deve permitir autenticação do usuário via conta Gov.br, utilizando CPF e senha, como pré‑requisito de acesso.                                                | <a href="../AnalisedeDocumentos/">ADD01</a>, <a href="../Brainstorming/">BS09</a>, <a href="../Observacao/">OBS01</a> | Sim           |           |      |
| RF11 | O aplicativo deve exibir os Termos de Uso e Privacidade na primeira vez que for aberto e requerer que o usuário os aceite para prosseguir.                             | <a href="../AnalisedeDocumentos/">ADD01</a>, <a href="../Observacao/">OBS03</a>                                       | Sim           |           |      |
| RF12 | O usuário poderá cadastrar múltiplos telefones celulares em sua conta no Celular Seguro, vinculando cada número de telefone ao seu CPF.                                | <a href="../AnalisedeDocumentos/">ADD01</a>, <a href="../Brainstorming/">BS02</a>                                     | Sim           |           |      |
| RF13 | O aplicativo deve permitir o cadastro de “pessoas de confiança”, autorizando contatos escolhidos a emitir alertas em nome do usuário em caso de emergência.            | <a href="../Storytelling/">ST05</a>, <a href="../Brainstorming/">BS05</a>                                             | Sim           |           |      |
| RF14 | O sistema deve fornecer uma função de emissão de alerta de bloqueio em caso de roubo, furto ou perda do aparelho, acionada por um botão de emergência de forma rápida. | <a href="../AnalisedeDocumentos/">ADD04</a>, <a href="../Observacao/">OBS04</a>, <a href="../Storytelling/">ST02</a>  | Sim           |      Casos de uso     |      |
| RF15 | Ao emitir um alerta, o usuário deverá selecionar o tipo de bloqueio desejado: Modo Recuperação (bloqueia linha e contas, mantendo o IMEI ativo) ou Bloqueio Total.     | <a href="../AnalisedeDocumentos/">ADD04</a>, <a href="../Brainstorming/">BS06</a>                                     | Sim           |    Casos de uso       |      |
| RF16 | Após o disparo do alerta, o sistema deve gerar um número de protocolo único e apresentá‑lo ao usuário, para referência junto às autoridades e parceiros.               | <a href="../AnalisedeDocumentos/">ADD04</a>, <a href="../Questionario/">QS07</a>                                      | Não           |    Casos de uso, Léxico      |      |
| RF17 | O alerta emitido pelo Celular Seguro deverá ser enviado automaticamente às operadoras de telefonia e instituições financeiras parceiras para os bloqueios necessários. | <a href="../AnalisedeDocumentos/">ADD04</a>, <a href="../Brainstorming/">BS10</a>                                     | Sim           |   Casos de uso        |      |
| RF18 | O aplicativo deve oferecer a funcionalidade de consultar se um aparelho possui restrição, permitindo verificar pelo IMEI se um celular é bloqueado antes de comprá‑lo. | <a href="../AnalisedeDocumentos/">ADD03</a>, <a href="../Questionario/">QS11</a>                                      | Não           |           |      |
| RF19 | O Celular Seguro deve estar disponível tanto como aplicativo móvel (Android/iOS) quanto via versão web, oferecendo as mesmas funcionalidades em ambas plataformas.     | <a href="../AnalisedeDocumentos/">ADD01</a>, <a href="../Brainstorming/">BS08</a>                                     | Sim           |           |      |
| RF20 | O sistema deve possibilitar a emissão de mais de um alerta para a mesma linha telefônica, permitindo novos alertas após ocorrências distintas.                         | <a href="../Brainstorming/">BS06</a>, <a href="../Questionario/">QS13</a>                                             | Não           |           |      |
| RF21 | Em modo Recuperação, o sistema deve receber notificações de quando um novo chip for inserido no aparelho e enviar alerta ao usuário.                                   | <a href="../AnalisedeDocumentos/">ADD04</a>, <a href="../Brainstorming/">BS06</a>                                     | Não           |    Casos de uso       |      |
| RF22 | Bloquear remotamente o aparelho                                                                                                                                        | <a href="../AnalisedeDocumentos/">ADD04</a>, <a href="../Brainstorming/">BS06</a>                                     | Não           |     Casos de uso      |      |
| RF23 | Apagar todos os dados do dispositivo                                                                                                                                   | <a href="../Brainstorming/">BS06</a>, <a href="../Questionario/">QS06</a>                                             | Não           |           |      |
| RF24 | Contatar autoridades automaticamente com relatório de segurança                                                                                                        | <a href="../Storytelling/">ST04</a>, <a href="../Brainstorming/">BS10</a>                                             | Não           |   Casos de uso, Léxico        |      |
| RF25 | Rastrear em tempo real a localização do dispositivo                                                                                                                    | <a href="../Questionario/">QS01</a>, <a href="../AnalisedeDocumentos/">ADD04</a>                                      | Não           |           |      |
| RF26 | Exibir histórico de movimentação no mapa                                                                                                                               | <a href="../Brainstorming/">BS05</a>, <a href="../Observacao/">OBS05</a>                                              | Não           |           |      |
| RF27 | Informar localização exata via coordenadas e mapa                                                                                                                      | <a href="../Questionario/">QS01</a>, <a href="../Observacao/">OBS06</a>                                               | Não           |     Casos de uso, Léxico      |      |
| RF28 | Emitir alerta S.O.S. automático para contatos de emergência                                                                                                            | <a href="../Storytelling/">ST05</a>, <a href="../Brainstorming/">BS05</a>                                             | Não           |           |      |
| RF29 | Bloquear chip por integração direta com a operadora                                                                                                                    | <a href="../AnalisedeDocumentos/">ADD04</a>, <a href="../Brainstorming/">BS10</a>                                     | Sim           |   Casos de uso       |      |
| RF30 | Guia de usuário passo a passo embutido no app                                                                                                                          | <a href="../Brainstorming/">BS01</a>, <a href="../Observacao/">OBS02</a>                                              | Sim           |           |      |
| RF31 | Cadastro de contatos de segurança e envio de notificações prioritárias                                                                                                 | <a href="../Brainstorming/">BS05</a>, <a href="../Storytelling/">ST05</a>                                             | Sim           |           |      |
| RF32 | Portal web para controle remoto das mesmas funções do app                                                                                                              | <a href="../AnalisedeDocumentos/">ADD01</a>, <a href="../Brainstorming/">BS08</a>                                     | Sim           |           |      |
| RF33 | Sincronizar notificações push e e‑mail entre app e portal                                                                                                              | <a href="../Brainstorming/">BS08</a>, <a href="../Questionario/">QS13</a>                                             | Sim           |           |      |
| RF34 | Botão de “bloqueio rápido” sempre acessível na tela principal                                                                                                          | <a href="../Observacao/">OBS04</a>, <a href="../Brainstorming/">BS06</a>                                              | Sim           |           |      |
| RF35 | Comandos por voz para funções críticas (bloqueio, rastreamento, SOS)                                                                                                   | <a href="../Brainstorming/">BS07</a>                                                                                  | Não           |           |      |
| RF36 | Efetuar backup automático de contatos, fotos e mensagens antes do bloqueio remoto                                                                                      | <a href="../Brainstorming/">BS06</a>, <a href="../Questionario/">QS06</a>                                             | Não           |           |      |
| RF37 | Restaurar dados de backup via e‑mail                                                                                                                                   | <a href="../Brainstorming/">BS06</a>, <a href="../Questionario/">QS06</a>                                             | Não           |           |      |
| RF38 | Emissão de som remoto para facilitar localização                                                                                                                       | <a href="../Questionario/">QS01</a>, <a href="../Storytelling/">ST06</a>                                              | Não           |    Casos de uso, Léxico       |      |
| RF39 | Oferecer rastreamento via satélite em áreas sem cobertura de celular                                                                                                   | <a href="../Brainstorming/">BS07</a>                                                                                  | Não           |           |      |
| RF40 | Enviar notificação por e‑mail com detalhes da tentativa de acesso suspeito                                                                                             | <a href="../Questionario/">QS08</a>, <a href="../Brainstorming/">BS06</a>                                             | Não           |   Léxico        |      |
| RF41 | Gerar relatório de movimentação para download em PDF                                                                                                                   | <a href="../Brainstorming/">BS10</a>                                                                                  | Não           |           |      |
| RF42 | Definir “dispositivo de confiança” para controle remoto secundário                                                                                                     | <a href="../Brainstorming/">BS05</a>, <a href="../Observacao/">OBS07</a>                                              | Não           |           |      |



<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/FelipeFreire-gf">Felipe das Neves</a>, <a href="https://github.com/gabriel-lima258">Gabriel Lima, <a href="https://github.com/MateuSansete">Mateus Bastos </a></p></font>

# Requisitos não funcionais

<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 2</b> - Requisitos não funcionais</p>

| ID   | Descrição | Rastreabilidade   | Implementação | Artefatos | Elos |
| ---- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- | ------------- | --------- | ---- |
| RNF01 | O aplicativo deve funcionar de maneira estável e confiável em momentos de emergência.                                                         | <a href="../Questionario/">QS09</a>, <a href="../Observacao/">OBS21</a>, <a href="../Brainstorming/">BS40</a>, <a href="../Storytelling/">ST11</a>, <a href="../AnalisedeDocumentos/">ADD13</a>.             | Não            |
| RNF02 | A interface deve ter design acessível a usuários com pouca familiaridade com tecnologia, como idosos.                                         | <a href="../Questionario/">Q19</a>, <a href="../Observacao/">OBS18</a>, <a href="../Brainstorming/">BS42</a>/<a href="../Brainstorming/">BS43</a>, <a href="../Storytelling/">ST8</a>, <a href="../AnalisedeDocumentos/">ADD17</a>. | Não            |
| RNF03 | O aplicativo deve oferecer um modo escuro (dark mode) para maior conforto visual.                                                             | <a href="../Questionario/">QS09</a>, <a href="../Brainstorming/">BS43</a>.                         | Não            |
| RNF04 | O aplicativo deve apresentar legendas em ícones e menus para facilitar a compreensão.                                                         | <a href="../Questionario/">QS12</a>, <a href="../Observacao/">OBS15</a>, <a href="../Brainstorming/">BS36</a>, <a href="../Storytelling/">ST8</a>, <a href="../AnalisedeDocumentos/">ADD16</a>.           | Sim            |
| RNF05 | O aplicativo deve enviar um SMS para uma pessoa quando a mesma for adicionada como pessoa de confiança.                                      | <a href="../Questionario/">QS14</a>                                                | Não            |
| RNF06 | Suporte Técnico, como disponibilizar canais de suporte claros e responsivos para auxiliar os usuários.                                       | <a href="../Questionario/">QS14</a>, <a href="../Observacao/">OBS21</a>, <a href="../Brainstorming/">BS52</a>, <a href="../AnalisedeDocumentos/">ADD17</a>.           | Não            |
| RNF07 | O serviço Celular Seguro deve estar disponível para todos os cidadãos brasileiros, 24×7, sem interrupções planejadas.                         | <a href="../AnalisedeDocumentos/">ADD13</a>, <a href="../Observacao/">OBS21</a>, <a href="../Brainstorming/">BS40</a>, <a href="../Storytelling/">ST11</a>.     |         Não       |
| RNF08 | O tempo de resposta para comunicação de um alerta aos parceiros deve ser mínimo – idealmente instantâneo – e os bloqueios devem ocorrer em minutos. | <a href="../AnalisedeDocumentos/">ADD14</a>, <a href="../Storytelling/">ST9</a>, <a href="../Brainstorming/">BS41</a>, <a href="../Brainstorming/">BS58</a>. |       Não         |
| RNF09 | O aplicativo e a plataforma devem seguir requisitos de segurança da informação: conexão criptografada, proteção de dados conforme LGPD.      | <a href="../AnalisedeDocumentos/">ADD15</a>, <a href="../Storytelling/">ST10</a>, <a href="../Brainstorming/">BS47</a>.                                      |        Não        |
| RNF10 | O serviço deverá ser oferecido gratuitamente, sem cobrança pelo download ou uso do aplicativo.                                                | <a href="../AnalisedeDocumentos/">ADD18</a>                                                                                                  |        Sim        |
| RNF11 | O sistema deve cumprir a legislação e normas vigentes, incluindo portarias, resoluções da Anatel e diretrizes da Febraban.                    | <a href="../AnalisedeDocumentos/">ADD19</a>                                                                                                  |      Sim          |
| RNF12 | Linguagem simples sem jargões técnicos.                                                                                                       | <a href="../Brainstorming/">BS37</a>, <a href="../Storytelling/">ST8</a>, <a href="../AnalisedeDocumentos/">ADD16</a>.                                              |       Sim         |
| RNF13 | Layout consistente seguindo heurísticas de Nielsen.                                                                                           | <a href="../Brainstorming/">BS38</a>, <a href="../Storytelling/">ST8</a>, <a href="../AnalisedeDocumentos/">ADD16</a>.                                        |         Não       |
| RNF14 | Tempo de resposta da interface < 200 ms. | <a href="../Brainstorming/">BS39</a>, <a href="../Storytelling/">ST9</a>, <a href="../AnalisedeDocumentos/">ADD14</a>. | Sim |NFR Framework | |
| RNF15 | Suporte a VLibras e leitor de tela para acessibilidade. | <a href="../Brainstorming/">BS42</a>, <a href="../Observacao/">OBS18</a>, <a href="../AnalisedeDocumentos/">ADD17</a>. |         Não       | Especificação Suplementar | |
| RNF16 | Transcrição em tempo real sem falhas de reconhecimento. | <a href="../Brainstorming/">BS44</a>  |       Não         |Especificação Supleentar | |
| RNF17 | Precisão de localização GPS menor do que 10 metros. | <a href="../Brainstorming/">BS45</a>      |       Não         | Casos de Uso, Léxicos, Cenários, NFR Framework | |
| RNF18 | Autenticação multifator (2FA) com fallback via SMS. | <a href="../Brainstorming/">BS48</a>      |       Não         |  Casos de Uso, Especificação Suplementar | |
| RNF19 | Logs de auditoria imutáveis e armazenados por no mínimo 1 ano. | <a href="../Brainstorming/">BS49</a> |          Não      | Casos de Uso | |
| RNF20 | Política de privacidade clara e facilmente acessível dentro do app. | <a href="../Brainstorming/">BS50</a> |   Não   | NFR Framework | |
| RNF21 | Verificação de integridade de dados no drive com checksum. | <a href="../Brainstorming/">BS53</a> |         Não      | Especificação Suplementar | |
| RNF22 | Compatibilidade com Android e iOS (últimas 3 versões principais). | <a href="../Brainstorming/">BS57</a>, <a href="../AnalisedeDocumentos/">ADD17</a> |      Sim          | Especificação Suplementar | |
| RNF23 | Tempo de inicialização do app < 2 segundos. | <a href="../Brainstorming/">BS58</a>, <a href="../Storytelling/">ST9</a>, <a href="../AnalisedeDocumentos/">ADD14</a> |      Sim          | Especificação Suplementar | |
| RNF24 | Atualizações automáticas de segurança e correções de vulnerabilidades em até 24 horas. | <a href="../Brainstorming/">BS60</a> |       Não         | Especificação Suplementar | |
| RNF25 | As páginas carregam em até 2 segundos em conexões padrão 4G. | <a href="../Observacao/">OBS16</a>, <a href="../Brainstorming/">BS39</a>, <a href="../Storytelling/">ST9</a>, <a href="../AnalisedeDocumentos/">ADD14</a>  |         Sim       | Especificação Suplementar, NFR Framework | |
| RNF26 | O aplicativo responde corretamente mesmo com entradas erradas. | <a href="../Observacao/">OBS19</a> |        Não        | NFR Framework | |
| RNF27 | O aplicativo apresenta confirmação de suas ações. | <a href="../Observacao/">OBS20</a> |      Sim          | Casos de Uso, NFR Framework | |

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/Bessazs">Vitor Bessa</a>, <a href="https://github.com/gabriel-lima258">Gabriel Lima, <a href="https://github.com/MateuSansete">Mateus Bastos </a></p></font>
---

### Referência

SAYÃO, Miriam; LEITE, Julio Cesar Sampaio do Prado. **Rastreabilidade de Requisitos**. Monografias em Ciência da Computação, Nº 20/05. Departamento de Informática, PUC-Rio, 2005.







---
# Histórico de Versões

| Versão | Data de produção   | Descrição da Alteração                               | Autor(es)             | Revisor(es)      | Data de Revisão |
| :----: | :----------------: | :--------------------------------------------------: | :-------------------: | :-------------:  | :-------------: |
| 1.0    | 06/02/2025         | Criação inicial do documento                         | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | 06/06/2025 |
| 1.1    | 06/02/2025         | Adição das seções de Introdução, Objetivos e Metodologia | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | 06/06/2025 
| 1.2    | 07/06/2025         | Atualização da rastreabilidade dos artefatos | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> , <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a>  | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | 08/02/2025 |
