# Léxicos 
---

## Introdução

O LAL (Léxico Ampliado da Linguagem) é uma notação que utiliza a descrição de termos por meio de léxicos.
Trata-se de uma técnica destinada a descrever os símbolos de uma linguagem, sendo amplamente utilizada na Engenharia de Requisitos.

O principal objetivo do uso do LAL é identificar palavras ou expressões específicas do domínio da aplicação em estudo, favorecendo o entendimento entre os envolvidos no processo de desenvolvimento.


<font size="3"><p style="text-align: center">Fonte: <a href="../Aula_10_lexicos_milene.pdf" target="_blank">SERRANO, Maurício e SERRANO, Milene [1]</a></p></font>

---

## Metodologia

Cada símbolo é descrito com noção e impacto.

* **Noção**: Significado literal (denotação).
* **Impacto**: efeito/uso/ocorrência do símbolo na aplicação ou do efeito de algo na aplicação sobre o símbolo (conotação). 

Essa estrutura é exemplificada na tabela 1 a seguir:

<font size="3"><p style="text-align: center">Tabela 1: Léxicos do tipo LAL</p></font>

| **Tipo** | **Noção**                                                                | **Impacto**                                                                                                     | **Sinônimo**                                                                 |
| -------- | ------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| Verbo    | Quem realiza, quando acontece e quais os procedimentos envolvidos.       | Quais reflexos da ação no ambiente (outras ações que devem ocorrer e quais os novos estados decorrentes).       | Termos alternativos que indicam a mesma ação no contexto do sistema.         |
| Objeto   | Definir o objeto e identificar outros objetos com os quais se relaciona. | Ações que podem ser aplicadas ao objeto.                                                                        | Nomes equivalentes ou variações linguísticas que se referem ao mesmo objeto. |
| Estado   | O que significa e quais ações levaram a esse estado.                     | Identificar outros estados e ações que podem ocorrer a partir do estado que se descreve.                        | Expressões que descrevem a mesma condição ou situação.                       |

<font size="3"><p style="text-align: center">Fonte: <a href="../Aula_10_lexicos_milene.pdf" target="_blank">SERRANO, Maurício e SERRANO, Milene [1]</a></p></font>

Para a obtenção dos requisitos não implementados utilizamos as referências do [questionário](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/).

---

## Léxico - Verbos

A tabela de verbos descreve as ações relevantes para o funcionamento do sistema, identificando quem as realiza, quando ocorrem e quais procedimentos estão envolvidos. Cada verbo representa uma função executada pelo sistema ou pelo usuário. 

O impacto dessas ações é descrito por meio das respostas comportamentais, que indicam seus efeitos no ambiente, como mudanças de estado ou o disparo de novas ações. Além disso, essas ações são associadas diretamente aos requisitos funcionais correspondentes, conforme apresentado na Tabela 2 a seguir:

<font size="3"><p style="text-align: center">Tabela 2: Léxico - Verbos</p></font>

| **Título** | **Noção**                                                 | **Impacto**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | **Sinônimos**                                |
| ---------- | --------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------- |
| Localizar  | Ação de determinar a posição atual do dispositivo.        | Permite que o sistema mostre a posição do celular no mapa. [QS01](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais)                                                                                                                                                                                                                                                                                                         | Rastrear, encontrar, identificar localização |
| Bloquear   | Ação de impedir o uso do dispositivo remotamente.         | Dispositivo torna-se inutilizável, mesmo que esteja com outra pessoa. [QS08](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais)                                                                                                                                                                                                                                                                                              | Trancar, restringir, inutilizar              |
| Solicitar  | Requisitar permissões para funcionamento adequado do app. | Sistema solicita acesso à localização e dados sensíveis. [QS07](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais)                                                                                                                                                                                                                                                                                                           | Pedir, requisitar, demandar                  |
| Enviar     | Transmitir dados para sistemas externos.                  | Envia localização ou alertas ao portal web ou contatos de segurança. [QS08](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais)                                                                                                                                                                                                                                                                                               | Transmitir, despachar, encaminhar            |
| Emitir     | Gerar documento ou alerta a partir de evento.             | Emite notificações ou orientações ao usuário, como o passo a passo após furto. [QS02](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais), [QS04](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais), [QS08](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais) | Disparar, gerar, produzir                    |
| Recuperar  | Ação de restaurar dados armazenados anteriormente.        | Permite restaurar backups após o bloqueio ou perda do aparelho. [QS08](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais)                                                                                                                                                                                                                                                                                                    | Restaurar, restituir, reaver                 |
| Notificar  | Informar usuário sobre evento relevante.                  | Alerta o usuário sobre tentativas de acesso ou trocas de chip. [QS08](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais)                                                                                                                                                                                                                                                                                                     | Avisar, alertar, informar                    |


<font size="3">
  <p style="text-align: center">
    Autores: 
    <a href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> e 
    <a href="https://github.com/MateuSansete" target="_blank">Mateus Sansete</a>
  </p>
</font>


---

## Léxico - Objetos

Esta tabela define os principais objetos manipulados no contexto da aplicação, como dispositivos, contas e dados. A noção descreve o que é cada objeto e suas relações com outros elementos do sistema. Já o impacto identifica quais ações podem ser aplicadas a esses objetos, refletindo diretamente em funcionalidades do sistema. 

Os objetos aqui descritos são centrais para a operação e segurança do aplicativo, que são representados na tabela 3 a seguir:

<font size="3"><p style="text-align: center">Tabela 3: Léxicos - Objetos</p></font>

| **Título**               | **Noção**                                                                                                                                                                               | **Impacto**                                                                                                                                                                                                                                                                                                                                                      | **Sinônimos**                                        |
| ------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| **Celular**              | Dispositivo móvel sob posse do usuário.                                                                                                                                                 | Pode ser localizado, bloqueado, apagado ou ter dados restaurados remotamente. [QS01](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais), [QS08](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais) | Smartphone, aparelho móvel, telefone                 |
| **Localização**          | Informação geográfica do aparelho.                                                                                                                                                      | É usada para exibir a posição em tempo real no mapa. [QS01](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais)                                                                                                                                                                    | Posição, coordenada, rastreamento                    |
| **Backup**               | Conjunto de dados salvos do dispositivo.                                                                                                                                                | Pode ser recuperado após bloqueio ou substituição do aparelho. [QS08](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais)                                                                                                                                                          | Cópia de segurança, salvamento, restauração          |
| **Notificação**          | Alerta informativo gerado pelo sistema.                                                                                                                                                 | Informa eventos como tentativa de desbloqueio ou alerta de segurança. [QS08](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais)                                                                                                                                                   | Alerta, aviso, comunicação                           |
| **Contato de segurança** | Pessoa indicada pelo usuário para emergências. [QS08](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais) | Recebe notificações em casos críticos.                                                                                                                                                                                                                                                                                                                           | Contato confiável, pessoa de emergência, responsável |
| **Chip (SIM Card)**      | Elemento de rede vinculado ao celular.                                                                                                                                                  | Alterações geram alertas de segurança. [QS08](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais)                                                                                                                                                                                  | Cartão SIM, módulo SIM, chip telefônico              |


<font size="3">
  <p style="text-align: center">
    Autores: 
    <a href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> e 
    <a href="https://github.com/MateuSansete" target="_blank">Mateus Sansete</a>
  </p>
</font>

---

## Léxico - Estados

A tabela de estados descreve as diferentes condições em que o sistema ou seus componentes podem se encontrar. A noção explica o que significa cada estado e como ele é alcançado, enquanto a resposta comportamental detalha suas consequências, como ações automáticas ou transições para novos estados. 

Esses estados refletem o comportamento dinâmico da aplicação e estão alinhados a requisitos funcionais e não funcionais que garantem sua confiabilidade, que são representados na tabela 4 a seguir:

<font size="3"><p style="text-align: center">Tabela 4: Léxicos - Estados</p></font>

| **Título**                        | **Noção**                                                | **Impacto**                                                                                                                                                                                                                                                                                                                                       | **Sinônimos**                                                     |
| --------------------------------- | -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| **Aplicativo instalado**          | O app foi baixado e está presente no dispositivo.        | Permite acesso inicial às funcionalidades. [QS17](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais)                                                                                                                                                               | App baixado, software instalado, sistema presente                 |
| **Permissão concedida**           | App recebeu autorização para acessar recursos sensíveis. | Habilita rastreamento, notificações e backup. [QS07](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais)                                                                                                                                                            | Autorização dada, acesso permitido, consentimento                 |
| **Modo perdido ativado**          | Estado de segurança máximo do sistema.                   | Dispara bloqueio, alarme, rastreamento e envio de localização. [QS01](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais), [QS08](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais) | Alerta total, modo segurança, estado de emergência                |
| **Dispositivo bloqueado**         | Aparelho está inutilizável remotamente.                  | Impede qualquer uso sem autorização. [QS08](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais)                                                                                                                                                                     | Celular trancado, aparelho travado, uso restrito                  |
| **Backup ativo**                  | Dados do celular estão sendo armazenados regularmente.   | Garante recuperação em caso de perda ou roubo. [QS08](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais)                                                                                                                                                           | Cópia contínua, salvamento automático, sincronização de dados     |
| **Notificação pendente**          | Evento relevante ainda não foi visualizado.              | Gera novas tentativas de envio ou reforço com sons/alertas. [QS08](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais)                                                                                                                                              | Alerta não lido, mensagem pendente, aviso aguardando visualização |
| **Tentativa de acesso detectada** | Alguém tentou usar o celular sem permissão.              | Aciona alertas e registro no log. [QS08](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais)                                                                                                                                                                        | Acesso não autorizado, intrusão detectada, tentativa de invasão   |
| **Chip alterado**                 | Foi detectada uma troca do SIM Card.                     | Gera alerta de segurança para o usuário e contatos. [QS08](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais)                                                                                                                                                      | Troca de SIM, substituição de chip, alteração de cartão           |
| **Sincronizado com o portal**     | Sistema do app estão atualizados com os mesmos dados.    | Ações realizadas em um refletem automaticamente no outro. [QS09](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#Tabela-4:-Requisitos-Funcionais)                                                                                                                                                | Integrado com servidor, conectado ao portal, dados espelhados     |

                                      

<font size="3"><p style="text-align: center">Autor: <a href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a></p></font>

---
## Referências Bibliográficas

> <a name="ref1">[ 1 ]</a> SERRANO, Milene. Requisitos – Aula 10. Apresentação de slides. Disponível em: https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf. Acesso em: 16/05/2023.

---

## Bibliografia

> Silva, Lyrene. Tese de Doutorado: Uma Estratégia Orientada a Aspectos para Modelagem de Requisitos. Disponível em: <https://www-di.inf.puc-rio.br/~julio/lyrene-tese.pdf>. Acesso em: 14 maio. 2025b.

---

## Histórico de Versões 



| Versão | Data de produção   | Descrição da Alteração                               | Autor(es)             | Revisor(es)      | Data de Revisão |
| :----: | :----------------: | :--------------------------------------------------: | :-------------------: | :-------------:  | :-------------: |
| 1.0    | 09/05/2025         | Criação do documento                                 | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> |  <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | 09/05/2025 |
| 1.1    | 14/05/2025         | Desenvolvimento do Tópico                            | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a>, <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | 14/05/2025 |
| 1.2    | 16/05/2025         | Ajustes nos requisitos dos léxicos                   | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | 16/05/2025 |
| 1.3    | 16/05/2025         | Correção, padronização das tabelas e referenciamento dos requisitos citados | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | 16/05/2025 |
| 1.4    | 17/05/2025         |Inserção dos sinônimos nas tabelas                          | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | 17/05/2025 |

