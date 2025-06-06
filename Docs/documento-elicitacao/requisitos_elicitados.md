# Requisitos Elicitados

## Introdução

Essa página reune todos os requisitos funcionais e não funcionais elicitados usando as técnicas de [Análise de Documentos](../AnalisedeDocumentos/),  [Questionário](../Questionario), [Brainstorming](../Brainstorming/), [Storytelling](../Storytelling/) e [Observação](../Observacao/)

---

## Metodologia

A tabela 1 apresenta os requisitos funcionais, sendo que cada linha contém um ID, sua respectiva descrição, um hyperlink de rastreabilidade que direciona à página da(s) técnica(s) que elicitou o requisitão em questão e se ele foi implementado ou não, analogamente a tabela 2 que apresenta os requisitos não funcionais.

A legenda para cada sigla é a seguinte:

- RFx: Requisito Funcional nºx
- ISx: Requisito nºx elicitado pela Introspecção
- Qx: Requisito nºx elicitado pelo Questionário
- BSx: Requisito nºx elicitado pelo Brainstorming
- OBSx: Requisito nºx elicitado pela Observação

---

## Requisitos funcionais

<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 1</b> - Requisitos funcionais</p>

| ID   | Descrição                                                                                                                                       | Rastreabilidade                       | Implementação |
|------|--------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------|----------------|
| RF01 | O aplicativo deve permitir localizar o celular perdido.                                                                                        | <a href="../Questionario/">QS01</a>, <a href="../Storytelling/">ST06</a>   | Não            |
| RF02 | O aplicativo deve tornar visível e acessível a opção de registro de boletim de ocorrência.                                                     | <a href="../Questionario/">QS02</a>   | Não            |
| RF03 | O aplicativo permite acessar ou cancelar contas bancárias vinculadas ao aparelho.                                                              | <a href="../Questionario/">QS03</a>   | Não            |
| RF04 | O aplicativo deve oferecer o passo a passo do que fazer após um furto ou roubo.                                                                | <a href="../Questionario/">QS04</a>   | Não            |
| RF05 | O aplicativo deve fornecer confirmação visual (feedback) ao usuário após realizar ações importantes.                                           | <a href="../Questionario/">Q12</a>    | Não            |
| RF06 | O aplicativo deve notificar o usuário em caso de atividade suspeita relacionada ao dispositivo.                                                | <a href="../Questionario/">QS08</a>   | Não            |
| RF07 | O aplicativo deve permitir a recuperação do aparelho bloqueado caso reencontrado.                                                              | <a href="../Questionario/">QS08</a>   | Não            |
| RF08 | O aplicativo deve permitir que o usuário registre um boletim de ocorrência.                                                                    | <a href="../Questionario/">QS09</a>   | Sim            |
| RF09 | Modo Falso Desligamento/Fake Shutdown. Simular que o celular foi desligado quando, na verdade, continua rastreável e operacional para comandos remotos. | <a href="../Questionario/">QS14</a> | Não            |
| RF10 | O sistema deve permitir autenticação do usuário via conta Gov.br, utilizando CPF e senha, como pré‑requisito de acesso.                        | <a href="../AnalisedeDocumentos/">ADD01</a>, <a href="../Brainstorming/">BS09</a>, <a href="../Observacao/">OBS01</a>  |                |
| RF11 | O aplicativo deve exibir os Termos de Uso e Privacidade na primeira vez que for aberto e requerer que o usuário os aceite para prosseguir.    |                                       |                |
| RF12 | O usuário poderá cadastrar múltiplos telefones celulares em sua conta no Celular Seguro, vinculando cada número de telefone ao seu CPF.       |                                       |                |
| RF13 | O aplicativo deve permitir o cadastro de “pessoas de confiança”, autorizando contatos escolhidos a emitir alertas em nome do usuário em caso de emergência. |                              |                |
| RF14 | O sistema deve fornecer uma função de emissão de alerta de bloqueio em caso de roubo, furto ou perda do aparelho, acionada por um botão de emergência de forma rápida. | |                |
| RF15 | Ao emitir um alerta, o usuário deverá selecionar o tipo de bloqueio desejado: Modo Recuperação (bloqueia linha e contas, mantendo o IMEI ativo) ou Bloqueio Total. | | |
| RF16 | Após o disparo do alerta, o sistema deve gerar um número de protocolo único e apresentá‑lo ao usuário, para referência junto às autoridades e parceiros. | | |
| RF17 | O alerta emitido pelo Celular Seguro deverá ser enviado automaticamente às operadoras de telefonia e instituições financeiras parceiras para os bloqueios necessários. | | |
| RF18 | O aplicativo deve oferecer a funcionalidade de consultar se um aparelho possui restrição, permitindo verificar pelo IMEI se um celular é bloqueado antes de comprá‑lo. | | |
| RF19 | O Celular Seguro deve estar disponível tanto como aplicativo móvel (Android/iOS) quanto via versão web, oferecendo as mesmas funcionalidades em ambas plataformas. | | |
| RF20 | O sistema deve possibilitar a emissão de mais de um alerta para a mesma linha telefônica, permitindo novos alertas após ocorrências distintas. | | |
| RF21 | Em modo Recuperação, o sistema deve receber notificações de quando um novo chip for inserido no aparelho e enviar alerta ao usuário.            |                                       |                |
| RF22 | Bloquear remotamente o aparelho                                                                                                                |                                       |                |
| RF23 | Apagar todos os dados do dispositivo                                                                                                           |                                       |                |
| RF24 | Contatar autoridades automaticamente com relatório de segurança                                                                                |                                       |                |
| RF25 | Rastrear em tempo real a localização do dispositivo                                                                                            |                                       |                |
| RF26 | Exibir histórico de movimentação no mapa                                                                                                       |                                       |                |
| RF27 | Informar localização exata via coordenadas e mapa                                                                                              |                                       |                |
| RF28 | Emitir alerta S.O.S. automático para contatos de emergência                                                                                    |                                       |                |
| RF29 | Bloquear chip por integração direta com a operadora                                                                                           |                                       |                |
| RF30 | Guia de usuário passo a passo embutido no app                                                                                                  |                                       |                |
| RF31 | Cadastro de contatos de segurança e envio de notificações prioritárias                                                                         |                                       |                |
| RF32 | Portal web para controle remoto das mesmas funções do app                                                                                      |                                       |                |
| RF33 | Sincronizar notificações push e e‑mail entre app e portal                                                                                      |                                       |                |
| RF34 | Botão de “bloqueio rápido” sempre acessível na tela principal                                                                                  |                                       |                |
| RF35 | Comandos por voz para funções críticas (bloqueio, rastreamento, SOS)                                                                           |                                       |                |
| RF36 | Efetuar backup automático de contatos, fotos e mensagens antes do bloqueio remoto                                                              |                                       |                |
| RF37 | Restaurar dados de backup via e‑mail                                                                                                           |                                       |                |
| RF38 | Emissão de som remoto para facilitar localização                                                                                               |                                       |                |
| RF39 | Oferecer rastreamento via satélite em áreas sem cobertura de celular                                                                          |                                       |                |
| RF40 | Enviar notificação por e‑mail com detalhes da tentativa de acesso suspeito                                                                     |                                       |                |
| RF41 | Gerar relatório de movimentação para download em PDF                                                                                           |                                       |                |
| RF42 | Definir “dispositivo de confiança” para controle remoto secundário  



<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/FelipeFreire-gf">Felipe das Neves</a>, <a href="https://github.com/gabriel-lima258">Gabriel Lima</a></p></font>


---

## Requisitos não funcionais

A legenda para cada sigla é a seguinte:

- RNFx: Requisito Não-Funcional nºx
- ISx: Requisito nºx elicitado pela Introspecção
- Qx: Requisito nºx elicitado pelo Questionário
- BSx: Requisito nºx elicitado pelo Brainstorming
- OBSx: Requisito nºx elicitado pela Observação

<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 2</b> - Requisitos não funcionais</p>

| ID    | Descrição                                                                                                                                      | Rastreabilidade                       | Implementação |
|-------|------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------|----------------|
| RNF01 | O aplicativo deve funcionar de maneira estável e confiável em momentos de emergência.                                                         | <a href="../Questionario/">QS09</a> | Não            |
| RNF02 | A interface deve ter design acessível a usuários com pouca familiaridade com tecnologia, como idosos.                                         | <a href="../Questionario/">Q19</a>    | Não            |
| RNF03 | O aplicativo deve oferecer um modo escuro (dark mode) para maior conforto visual.                                                             | <a href="../Questionario/">QS09</a>   | Não            |
| RNF04 | O aplicativo deve apresentar legendas em ícones e menus para facilitar a compreensão.                                                         | <a href="../Questionario/">QS12</a>   | Sim            |
| RNF05 | O aplicativo deve enviar um SMS para uma pessoa quando a mesma for adicionada como pessoa de confiança.                                      | <a href="../Questionario/">QS14</a>   | Não            |
| RNF06 | Suporte Técnico, como disponibilizar canais de suporte claros e responsivos para auxiliar os usuários.                                       | <a href="../Questionario/">QS14</a>   | Não            |
| RNF07 | O serviço Celular Seguro deve estar disponível para todos os cidadãos brasileiros, 24×7, sem interrupções planejadas.                         |                                       |                |
| RNF08 | O tempo de resposta para comunicação de um alerta aos parceiros deve ser mínimo – idealmente instantâneo – e os bloqueios devem ocorrer em minutos. |                               |                |
| RNF09 | O aplicativo e a plataforma devem seguir requisitos de segurança da informação: conexão criptografada, proteção de dados conforme LGPD.      |                                       |                |
| RNF10 | O serviço deverá ser oferecido gratuitamente, sem cobrança pelo download ou uso do aplicativo.                                                |                                       |                |
| RNF11 | O sistema deve cumprir a legislação e normas vigentes, incluindo portarias, resoluções da Anatel e diretrizes da Febraban.                    |                                       |                |
| RNF12 | Linguagem simples sem jargões técnicos.                                                                                                       |                                       |                |
| RNF13 | Layout consistente seguindo heurísticas de Nielsen.                                                                                           |                                       |                |
| RNF14 | Tempo de resposta da interface < 200 ms.                                                                                                       |                                       |                |
| RNF15 | Suporte a VLibras e leitor de tela para acessibilidade.                                                                                       |                                       |                |
| RNF16 | Transcrição em tempo real sem falhas de reconhecimento.                                                                                       |                                       |                |
| RNF17 | Precisão de localização GPS melhor que 10 m.                                                                                                   |                                       |                |
| RNF18 | Autenticação multifator (2FA) com fallback via SMS.                                                                                           |                                       |                |
| RNF19 | Logs de auditoria imutáveis e armazenados por no mínimo 1 ano.                                                                                |                                       |                |
| RNF20 | Política de privacidade clara e facilmente acessível dentro do app.                                                                           |                                       |                |
| RNF21 | Verificação de integridade de dados no drive com checksum.                                                                                    |                                       |                |
| RNF22 | Compatibilidade com Android e iOS (últimas 3 versões principais).                                                                             |                                       |                |
| RNF23 | Tempo de inicialização do app < 2 segundos.                                                                                                    |                                       |                |
| RNF24 | Atualizações automáticas de segurança e correções de vulnerabilidades em até 24 horas.                                                        |                                       |                |
| RNF25 | As páginas carregam em até 2 segundos em conexões padrão 4G.                                                                                  |                                       |                |
| RNF26 | O aplicativo responde corretamente mesmo com entradas erradas.                                                                                |                                       |                |
| RNF27 | O aplicativo apresenta confirmação de suas ações.                                                                                             |                                       |                |





<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/FelipeFreire-gf">Felipe das Neves</a>, <a href="https://github.com/gabriel-lima258">Gabriel Lima</a></p></font>

---

## Histórico de Versões

| Versão | Data de produção   | Descrição da Alteração                               | Autor(es)             | Revisor(es)      |Data de Revisão |
| :----: | :----------------: | :--------------------------------------------------: | :-------------------: | :-------------:  |  :-----------: |
| 1.0    | 29/04/2025         | Desenvolvimento do tópico                            |<a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a>    | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Matheus</a>| 29/04/2025|
| 1.1    | 04/05/2025         | Inserção dos requisitos funcionais e não funcionais do questionário                            |<a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a>    | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus</a>| 04/05/2025|
| 2.0    | 06/06/2025          | IRefatorando a lista de todos os RF e RNF |<a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a>    | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus</a>| 06/06/2025 |
