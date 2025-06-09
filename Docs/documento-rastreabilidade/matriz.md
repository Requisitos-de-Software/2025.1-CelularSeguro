# Matriz Geral de Rastreabilidade
---
### Introdução

A matriz geral de rastreabilidade é um documento fundamental na engenharia de requisitos que reúne, de maneira organizada, todos os requisitos funcionais identificados durante o projeto, mostrando tanto sua rastreabilidade anterior (pré-rastreabilidade) quanto a posterior (pós-rastreabilidade). O objetivo é oferecer uma visão completa e estruturada das conexões entre os requisitos, suas fontes (como as técnicas de elicitação utilizadas) e os artefatos que deles derivam ou que estão relacionados.

De acordo com Sayão e Leite (2005), a rastreabilidade é o mecanismo que viabiliza a ligação entre os diversos elementos envolvidos no ciclo de vida de um sistema, incluindo requisitos, documentos, decisões e implementações. A matriz geral viabiliza essa conexão por meio de **referências cruzadas e elos rastreáveis**, revelando **dependências**, **origens documentais** e **impactos** que cada requisito pode ter em diferentes fases do desenvolvimento.[[ 1 ]](#ref1)

Assim, a matriz não só facilita a entendimento e análise integrada dos requisitos, como também apoia a gestão de alterações, o controle da qualidade e a manutenção e evolução do sistema ao longo do seu ciclo de vida.

---

### Objetivos

O objetivo da matriz geral é consolidar as informações dos artefatos de **Backward-From** (rastreabilidade retroativa) e **Forward-From** (rastreabilidade prospectiva), proporcionando uma **visão unificada** do ciclo de vida dos requisitos. Através dessa unificação, é possível:

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
- **Elos**: Ligações semânticas entre os requisitos e outros elementos indicando dependência, influência ou refinamento.

Esta matriz representa, portanto, uma peça-chave no processo de **documentação e rastreamento completo dos requisitos**, apoiando práticas de desenvolvimento ágil, melhoria contínua e validação sistemática.

---

## Requisitos funcionais

<p style="text-align:center"><b><a id="tab_1" style="visibility:hidden;"></a>Tabela 1</b> – Requisitos funcionais</p>

| ID | Descrição | Pré-Rastreabilidade | Implementação | Artefatos | Elos |
|----|-----------|---------------------|---------------|-----------|------|
| RF01 | Localizar o celular perdido. | QS01, ST06, ADD01 | Sim | [Casos de Uso](../../documento-modelagem/caso-de-uso/), [Léxicos](../../documento-modelagem/lexico/) | [RF01](../pos-rastreabilidade/#rf01) |
| RF02 | Tornar visível o registro de boletim. | QS02, OBS02 | Sim | [Casos de Uso](../../documento-modelagem/caso-de-uso/), [Léxicos](../../documento-modelagem/lexico/) | [RF02](../pos-rastreabilidade/#rf02) |
| RF03 | Acessar / cancelar contas bancárias vinculadas. | QS03, BS03 | Não | [Casos de Uso](../../documento-modelagem/caso-de-uso/) | [RF03](../pos-rastreabilidade/#rf03) |
| RF04 | Passo-a-passo após furto/roubo. | QS04, ADD02 | Não | [Casos de Uso](../../documento-modelagem/caso-de-uso/), [Léxicos](../../documento-modelagem/lexico/) | [RF04](../pos-rastreabilidade/#rf04) |
| RF05 | Feedback visual pós-ação. | Q12, BS04 | Não | Não se aplica | [RF05](../pos-rastreabilidade/#rf05) |
| RF06 | Notificar atividade suspeita. | QS08, BS06 | Não | [Léxicos](../../documento-modelagem/lexico/) | [RF06](../pos-rastreabilidade/#rf06) |
| RF07 | Recuperar aparelho bloqueado. | QS08, ST03 | Não | [Léxicos](../../documento-modelagem/lexico/) | [RF07](../pos-rastreabilidade/#rf07) |
| RF08 | Registrar boletim de ocorrência. | QS09, ADD03 | Sim | Não se aplica | [RF08](../pos-rastreabilidade/#rf08) |
| RF09 | Modo Falso Desligamento. | QS14, BS07 | Não | Não se aplica | [RF09](../pos-rastreabilidade/#rf09) |
| RF10 | Autenticação Gov.br. | ADD01, BS09, OBS01 | Sim | Não se aplica | [RF10](../pos-rastreabilidade/#rf10) |
| RF11 | Exibir Termos de Uso/Privacidade na 1ª abertura. | ADD01, OBS03 | Sim | Não se aplica | [RF11](../pos-rastreabilidade/#rf11) |
| RF12 | Cadastrar múltiplos celulares. | ADD01, BS02 | Sim | Não se aplica | [RF12](../pos-rastreabilidade/#rf12) |
| RF13 | Cadastrar pessoas de confiança. | ST05, BS05 | Sim | Não se aplica | [RF13](../pos-rastreabilidade/#rf13) |
| RF14 | Botão de emergência (alerta de bloqueio). | ADD04, OBS04, ST02 | Sim | [Casos de Uso](../../documento-modelagem/caso-de-uso/) | [RF14](../pos-rastreabilidade/#rf14) |
| RF15 | Selecionar tipo de bloqueio. | ADD04, BS06 | Sim | [Casos de uso](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/) | [RF15](../pos-rastreabilidade/#rf15) |
| RF16 | Gerar protocolo único pós-alerta. | ADD04, QS07 | Não | [Casos de uso](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/), [Léxicos](../../documento-modelagem/lexico/) | [RF16](../pos-rastreabilidade/#rf16) |
| RF17 | Envio automático de alerta a parceiros. | ADD04, BS10 | Sim | [Casos de uso](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/) | [RF17](../pos-rastreabilidade/#rf17) |
| RF18 | Consulta de restrição por IMEI. | ADD03, QS11 | Não | Não se aplica | [RF18](../pos-rastreabilidade/#rf18) |
| RF19 | Mesmas funções em app e portal web. | ADD01, BS08 | Sim | Não se aplica | [RF19](../pos-rastreabilidade/#rf19) |
| RF20 | Permitir múltiplos alertas para mesma linha. | BS06, QS13 | Não | Não se aplica | [RF20](../pos-rastreabilidade/#rf20) |
| RF21 | Em modo Recuperação, o sistema deve receber notificações de quando um novo chip for inserido no aparelho e enviar alerta ao usuário. | <a href="../AnalisedeDocumentos/">ADD04</a>, <a href="../Brainstorming/">BS06</a> | Não | [Casos de uso](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/) | [RF21](../pos-rastreabilidade/#rf21) |
| RF22 | Bloquear remotamente o aparelho | <a href="../AnalisedeDocumentos/">ADD04</a>, <a href="../Brainstorming/">BS06</a> | Não | [Casos de uso](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/) | [RF22](../pos-rastreabilidade/#rf22) |
| RF23 | Apagar todos os dados do dispositivo | <a href="../Brainstorming/">BS06</a>, <a href="../Questionario/">QS06</a> | Não | Não se aplica| [RF23](../pos-rastreabilidade/#rf23) |
| RF24 | Contatar autoridades automaticamente com relatório de segurança | <a href="../Storytelling/">ST04</a>, <a href="../Brainstorming/">BS10</a> | Não | [Casos de uso](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/), [Léxicos](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/) | [RF24](../pos-rastreabilidade/#rf24) |
| RF25 | Rastrear em tempo real a localização do dispositivo | <a href="../Questionario/">QS01</a>, <a href="../AnalisedeDocumentos/">ADD04</a> | Não | Não se aplica | [RF25](../pos-rastreabilidade/#rf25) |
| RF26 | Exibir histórico de movimentação no mapa | <a href="../Brainstorming/">BS05</a>, <a href="../Observacao/">OBS05</a> | Não | Não se aplica | [RF26](../pos-rastreabilidade/#rf26) |
| RF27 | Informar localização exata via coordenadas e mapa | <a href="../Questionario/">QS01</a>, <a href="../Observacao/">OBS06</a> | Não | [Casos de uso](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/), [Léxicos](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/) | [RF27](../pos-rastreabilidade/#rf27) |
| RF28 | Emitir alerta S.O.S. automático para contatos de emergência | <a href="../Storytelling/">ST05</a>, <a href="../Brainstorming/">BS05</a> | Não | Não se aplica | [RF28](../pos-rastreabilidade/#rf28) |
| RF29 | Bloquear chip por integração direta com a operadora | <a href="../AnalisedeDocumentos/">ADD04</a>, <a href="../Brainstorming/">BS10</a> | Sim | [Casos de uso](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/) | [RF29](../pos-rastreabilidade/#rf29) |
| RF30 | Guia de usuário passo a passo embutido no app | <a href="../Brainstorming/">BS01</a>, <a href="../Observacao/">OBS02</a> | Sim | Não se aplica | [RF30](../pos-rastreabilidade/#rf30) |
| RF31 | Cadastro de contatos de segurança e envio de notificações prioritárias | <a href="../Brainstorming/">BS05</a>, <a href="../Storytelling/">ST05</a> | Sim | Não se aplica | [RF31](../pos-rastreabilidade/#rf31) |
| RF32 | Portal web para controle remoto das mesmas funções do app | <a href="../AnalisedeDocumentos/">ADD01</a>, <a href="../Brainstorming/">BS08</a> | Sim | Não se aplica | [RF32](../pos-rastreabilidade/#rf32) |
| RF33 | Sincronizar notificações push e e‑mail entre app e portal | <a href="../Brainstorming/">BS08</a>, <a href="../Questionario/">QS13</a> | Sim | Não se aplica | [RF33](../pos-rastreabilidade/#rf33) |
| RF34 | Botão de “bloqueio rápido” sempre acessível na tela principal | <a href="../Observacao/">OBS04</a>, <a href="../Brainstorming/">BS06</a> | Sim | Não se aplica | [RF34](../pos-rastreabilidade/#rf34) |
| RF35 | Comandos por voz para funções críticas (bloqueio, rastreamento, SOS) | <a href="../Brainstorming/">BS07</a> | Não | Não se aplica | [RF35](../pos-rastreabilidade/#rf35) |
| RF36 | Efetuar backup automático de contatos, fotos e mensagens antes do bloqueio remoto | <a href="../Brainstorming/">BS06</a>, <a href="../Questionario/">QS06</a> | Não | Não se aplica | [RF36](../pos-rastreabilidade/#rf36) |
| RF37 | Restaurar dados de backup via e‑mail | <a href="../Brainstorming/">BS06</a>, <a href="../Questionario/">QS06</a> | Não | Não se aplica | [RF37](../pos-rastreabilidade/#rf37) |
| RF38 | Emissão de som remoto para facilitar localização | <a href="../Questionario/">QS01</a>, <a href="../Storytelling/">ST06</a> | Não | [Casos de uso](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/), [Léxicos](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/) | [RF38](../pos-rastreabilidade/#rf38) |
| RF39 | Oferecer rastreamento via satélite em áreas sem cobertura de celular | <a href="../Brainstorming/">BS07</a> | Não | Não se aplica | [RF39](../pos-rastreabilidade/#rf39) |
| RF40 | Enviar notificação por e‑mail com detalhes da tentativa de acesso suspeito | <a href="../Questionario/">QS08</a>, <a href="../Brainstorming/">BS06</a> | Não | [Léxicos](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/) | [RF40](../pos-rastreabilidade/#rf40) |
| RF41 | Gerar relatório de movimentação para download em PDF | <a href="../Brainstorming/">BS10</a> | Não | Não se aplica | [RF41](../pos-rastreabilidade/#rf41) |
| RF42 | Definir “dispositivo de confiança” para controle remoto secundário | <a href="../Brainstorming/">BS05</a>, <a href="../Observacao/">OBS07</a> | Não | Não se aplica | [RF42](../pos-rastreabilidade/#rf42) |

<font size="2"><p style="text-align: center"><b>Fonte:  <a href="https://github.com/MateuSansete">Mateus Bastos </a> e <a href="https://github.com/gabriel-lima258">Gabriel Lima</p></font>


---

# Requisitos não funcionais

<p style="text-align:center"><b><a id="tab_2" style="visibility:hidden;"></a>Tabela 2</b> – Requisitos não funcionais</p>

| ID | Descrição | Rastreabilidade | Implementação | Artefatos | Elos |
|----|-----------|-----------------|---------------|-----------|------|
| RNF01 | O aplicativo deve funcionar de maneira estável e confiável em momentos de emergência. | <a href="../Questionario/">QS09</a>, <a href="../Observacao/">OBS21</a>, <a href="../Brainstorming/">BS40</a>, <a href="../Storytelling/">ST11</a>, <a href="../AnalisedeDocumentos/">ADD13</a> | Não | [Especificação Suplementar](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/) | [RNF01](../pos-rastreabilidade/#rnf01) |
| RNF02 | A interface deve ter design acessível a usuários com pouca familiaridade com tecnologia, como idosos. | <a href="../Questionario/">Q19</a>, <a href="../Observacao/">OBS18</a>, <a href="../Brainstorming/">BS42</a>/<a href="../Brainstorming/">BS43</a>, <a href="../Storytelling/">ST8</a>, <a href="../AnalisedeDocumentos/">ADD17</a> | Não | [Especificação Suplementar](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/) | [RNF02](../pos-rastreabilidade/#rnf02) |
| RNF03 | O aplicativo deve oferecer um modo escuro (dark mode) para maior conforto visual. | <a href="../Questionario/">QS09</a>, <a href="../Brainstorming/">BS43</a> | Não | Não se aplica | [RNF03](../pos-rastreabilidade/#rnf03) |
| RNF04 | O aplicativo deve apresentar legendas em ícones e menus para facilitar a compreensão. | <a href="../Questionario/">QS12</a>, <a href="../Observacao/">OBS15</a>, <a href="../Brainstorming/">BS36</a>, <a href="../Storytelling/">ST8</a>, <a href="../AnalisedeDocumentos/">ADD16</a> | Sim | [Especificação Suplementar](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/) | [RNF04](../pos-rastreabilidade/#rnf04) |
| RNF05 | O aplicativo deve enviar um SMS para uma pessoa quando a mesma for adicionada como pessoa de confiança. | <a href="../Questionario/">QS14</a> | Não | Não se aplica | [RNF05](../pos-rastreabilidade/#rnf05) |
| RNF06 | Suporte Técnico, como disponibilizar canais de suporte claros e responsivos para auxiliar os usuários. | <a href="../Questionario/">QS14</a>, <a href="../Observacao/">OBS21</a>, <a href="../Brainstorming/">BS52</a>, <a href="../AnalisedeDocumentos/">ADD17</a> | Não | [Especificação Suplementar](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/) | [RNF06](../pos-rastreabilidade/#rnf06) |
| RNF07 | O serviço Celular Seguro deve estar disponível para todos os cidadãos brasileiros, 24×7, sem interrupções planejadas. | <a href="../AnalisedeDocumentos/">ADD13</a>, <a href="../Observacao/">OBS21</a>, <a href="../Brainstorming/">BS40</a>, <a href="../Storytelling/">ST11</a> | Não | [Especificação Suplementar](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/) | [RNF07](../pos-rastreabilidade/#rnf07) |
| RNF08 | O tempo de resposta para comunicação de um alerta aos parceiros deve ser mínimo – idealmente instantâneo – e os bloqueios devem ocorrer em minutos. | <a href="../AnalisedeDocumentos/">ADD14</a>, <a href="../Storytelling/">ST9</a>, <a href="../Brainstorming/">BS41</a>, <a href="../Brainstorming/">BS58</a> | Não | [Especificação Suplementar](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/) | [RNF08](../pos-rastreabilidade/#rnf08) |
| RNF09 | O aplicativo e a plataforma devem seguir requisitos de segurança da informação: conexão criptografada, proteção de dados conforme LGPD. | <a href="../AnalisedeDocumentos/">ADD15</a>, <a href="../Storytelling/">ST10</a>, <a href="../Brainstorming/">BS47</a> | Não | [Especificação Suplementar](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/) | [RNF09](../pos-rastreabilidade/#rnf09) |
| RNF10 | O serviço deverá ser oferecido gratuitamente, sem cobrança pelo download ou uso do aplicativo. | <a href="../AnalisedeDocumentos/">ADD18</a> | Sim | Não se aplica | [RNF10](../pos-rastreabilidade/#rnf10) |
| RNF11 | O sistema deve cumprir a legislação e normas vigentes, incluindo portarias, resoluções da Anatel e diretrizes da Febraban. | <a href="../AnalisedeDocumentos/">ADD19</a> | Sim | [Especificação suplementar](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/) | [RNF11](../pos-rastreabilidade/#rnf11) |
| RNF12 | Linguagem simples sem jargões técnicos. | <a href="../Brainstorming/">BS37</a>, <a href="../Storytelling/">ST8</a>, <a href="../AnalisedeDocumentos/">ADD16</a> | Sim | [Léxicos](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/) | [RNF12](../pos-rastreabilidade/#rnf12) |
| RNF13 | Layout consistente seguindo heurísticas de Nielsen. | <a href="../Brainstorming/">BS38</a>, <a href="../Storytelling/">ST8</a>, <a href="../AnalisedeDocumentos/">ADD16</a> | Não | Não se aplica | [RNF13](../pos-rastreabilidade/#rnf13) |
| RNF14 | Tempo de resposta da interface < 200 ms. | <a href="../Brainstorming/">BS39</a>, <a href="../Storytelling/">ST9</a>, <a href="../AnalisedeDocumentos/">ADD14</a> | Sim | [NFR Framework](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/) | [RNF14](../pos-rastreabilidade/#rnf14) |
| RNF15 | Suporte a VLibras e leitor de tela para acessibilidade. | <a href="../Brainstorming/">BS42</a>, <a href="../Observacao/">OBS18</a>, <a href="../AnalisedeDocumentos/">ADD17</a> | Não | [Especificação Suplementar](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/) | [RNF15](../pos-rastreabilidade/#rnf15) |
| RNF16 | Transcrição em tempo real sem falhas de reconhecimento. | <a href="../Brainstorming/">BS44</a> | Não | [Especificação Suplementar](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/) | [RNF16](../pos-rastreabilidade/#rnf16) |
| RNF17 | Precisão de localização GPS menor do que 10 metros. | <a href="../Brainstorming/">BS45</a> | Não | [Casos de Uso](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/), [Léxicos](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/lexico/), [Cenários](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/cenario/), [NFR Framework](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/) | [RNF17](../pos-rastreabilidade/#rnf17) |
| RNF18 | Autenticação multifator (2FA) com fallback via SMS. | <a href="../Brainstorming/">BS48</a> | Não | [Casos de Uso](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/), [Especificação Suplementar](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/) | [RNF18](../pos-rastreabilidade/#rnf18) |
| RNF19 | Logs de auditoria imutáveis e armazenados por no mínimo 1 ano. | <a href="../Brainstorming/">BS49</a> | Não | [Casos de Uso](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/) | [RNF19](../pos-rastreabilidade/#rnf19) |
| RNF20 | Política de privacidade clara e facilmente acessível dentro do app. | <a href="../Brainstorming/">BS50</a> | Não | [NFR Framework](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/) | [RNF20](../pos-rastreabilidade/#rnf20) |
| RNF21 | Verificação de integridade de dados no drive com checksum. | <a href="../Brainstorming/">BS53</a> | Não | [Especificação Suplementar](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/) | [RNF21](../pos-rastreabilidade/#rnf21) |
| RNF22 | Compatibilidade com Android e iOS (últimas 3 versões principais). | <a href="../Brainstorming/">BS57</a>, <a href="../AnalisedeDocumentos/">ADD17</a> | Sim | [Especificação Suplementar](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/) | [RNF22](../pos-rastreabilidade/#rnf22) |
| RNF23 | Tempo de inicialização do app < 2 segundos. | <a href="../Brainstorming/">BS58</a>, <a href="../Storytelling/">ST9</a>, <a href="../AnalisedeDocumentos/">ADD14</a> | Sim | [Especificação Suplementar](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/) | [RNF23](../pos-rastreabilidade/#rnf23) |
| RNF24 | Atualizações automáticas de segurança e correções de vulnerabilidades em até 24 horas. | <a href="../Brainstorming/">BS60</a> | Não | [Especificação Suplementar](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/) | [RNF24](../pos-rastreabilidade/#rnf24) |
| RNF25 | As páginas carregam em até 2 segundos em conexões padrão 4G. | <a href="../Observacao/">OBS16</a>, <a href="../Brainstorming/">BS39</a>, <a href="../Storytelling/">ST9</a>, <a href="../AnalisedeDocumentos/">ADD14</a> | Sim | [Especificação Suplementar](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/especificacoes-suplementar/), [NFR Framework](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/) | [RNF25](../pos-rastreabilidade/#rnf25) |
| RNF26 | O aplicativo responde corretamente mesmo com entradas erradas. | <a href="../Observacao/">OBS19</a> | Não | [NFR Framework](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/) | [RNF26](../pos-rastreabilidade/#rnf26) |
| RNF27 | O aplicativo apresenta confirmação de suas ações. | <a href="../Observacao/">OBS20</a> | Sim | [Casos de uso](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/), [NFR Framework](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/) | [RNF27](../pos-rastreabilidade/#rnf27) |

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/MateuSansete">Mateus Bastos </a>, <a href="https://github.com/Bessazs">Vitor Bessa</a> e <a href="https://github.com/zDrNz">Daniel Rodrigues</a></p></font>
---

### Referência

><a name="ref1"></a> SAYÃO, Miriam; LEITE, Julio Cesar Sampaio do Prado. **Rastreabilidade de Requisitos**. Monografias em Ciência da Computação, Nº 20/05. Departamento de Informática, PUC-Rio, 2005.






---
# Histórico de Versões

| Versão | Data de produção   | Descrição da Alteração                               | Autor(es)             | Revisor(es)      | Data de Revisão |
| :----: | :----------------: | :--------------------------------------------------: | :-------------------: | :-------------:  | :-------------: |
| 1.0    | 06/02/2025         | Criação inicial do documento                         | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | 06/06/2025 |
| 1.1    | 06/02/2025         | Adição das seções de Introdução, Objetivos e Metodologia | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | 06/06/2025 
| 1.2    | 07/06/2025         | Atualização da rastreabilidade dos artefatos | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> , <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a>  | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | 08/02/2025 |
| 1.3    | 08/06/2025         | Atualização de termos utilizados | <a style="color:gold;" href="https://github.com/zDrNz" target="_blank">Daniel Rodrigues</a> | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | 08/06/2025 |
| 1.4    | 08/02/2025         | Adição de rastreabilidade nas tabela de requisitos funcionais e não funcionais | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | 06/06/2025 
| 1.5    | 08/06/2025         | Adição dos requisitos não funcionais | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Vitor Bessa</a> , <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Daniel Rodrigues</a>  | <a style="color:gold;" href="https://github.com/zDrNz" target="_blank">Mateus Bastos</a> | 08/02/2025 |
| 1.6    | 08/06/2025         | Correção dos links de rastreabilidade | <a style="color:gold;" href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a>  | <a style="color:gold;" href="https://github.com/zDrNz" target="_blank">Daniel Rodrigues</a> | 08/02/2025 |
| 1.7    | 08/06/2025         | Adição dos requisitos não funcionais | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Vitor Bessa</a> , <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Daniel Rodrigues</a>  | <a style="color:gold;" href="https://github.com/zDrNz" target="_blank">Mateus Bastos</a> | 08/02/2025 |
| 1.8    | 08/02/2025         | Hiperlinks nos atributos das tabelas de Requisitos funcionais e não funcionais | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | 08/06/2025 

