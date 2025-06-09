# Matriz Geral de Rastreabilidade
---
### Introdução
A *matriz geral de rastreabilidade* consolida, em um único ponto, a pré- e pós-rastreabilidade de todos os requisitos do projeto Celular Seguro. Ela evidencia as origens (técnicas de elicitação), o estado de implementação, os artefatos de apoio e os *elos* que ligam cada requisito às seções de rastreabilidade detalhada.

---

### Objetivos
* Confirmar que todo requisito possui origem justificada.  
* Acompanhar o status de implementação.  
* Mapear artefatos (modelos, especificações, NFR cards, etc.).  
* Facilitar análise de impacto e gestão de mudanças por meio dos *elos*.

---

### Metodologia
Foi feita a junção das planilhas Backward-From e Forward-From, revisando cada linha para:  
1. *Remover campos vazios* (substituídos por links ou “Não se aplica”, quando pertinente);  
2. Garantir *links absolutos* para todos os artefatos do repositório;  
3. Incluir o *anchor* do pós-rastreabilidade em *Elos*.

---

## Requisitos funcionais

<p style="text-align:center"><b><a id="tab_1" style="visibility:hidden;"></a>Tabela 1</b> – Requisitos funcionais</p>

| ID | Descrição | Pré-Rastreabilidade | Implementação | Artefatos | Elos |
|----|-----------|---------------------|---------------|-----------|------|
| *RF01* | Localizar o celular perdido. | QS01, ST06, ADD01 | *Sim* | [Casos de Uso](../../documento-modelagem/caso-de-uso/), [Léxicos](../../documento-modelagem/lexico/) | [RF01](../pos-rastreabilidade/#rf01) |
| *RF02* | Tornar visível o registro de boletim. | QS02, OBS02 | *Sim* | [Casos de Uso](../../documento-modelagem/caso-de-uso/), [Léxicos](../../documento-modelagem/lexico/) | [RF02](../pos-rastreabilidade/#rf02) |
| *RF03* | Acessar / cancelar contas bancárias vinculadas. | QS03, BS03 | *Não* | [Casos de Uso](../../documento-modelagem/caso-de-uso/) | [RF03](../pos-rastreabilidade/#rf03) |
| *RF04* | Passo-a-passo após furto/roubo. | QS04, ADD02 | *Não* | Casos de Uso, Léxicos | [RF04](../pos-rastreabilidade/#rf04) |
| *RF05* | Feedback visual pós-ação. | Q12, BS04 | *Não* | *Não se aplica* | [RF05](../pos-rastreabilidade/#rf05) |
| *RF06* | Notificar atividade suspeita. | QS08, BS06 | *Não* | [Léxicos](../../documento-modelagem/lexico/) | [RF06](../pos-rastreabilidade/#rf06) |
| *RF07* | Recuperar aparelho bloqueado. | QS08, ST03 | *Não* | Léxicos | [RF07](../pos-rastreabilidade/#rf07) |
| *RF08* | Registrar boletim de ocorrência. | QS09, ADD03 | *Sim* | *Não se aplica* | [RF08](../pos-rastreabilidade/#rf08) |
| *RF09* | Modo Falso Desligamento. | QS14, BS07 | *Não* | *Não se aplica* | [RF09](../pos-rastreabilidade/#rf09) |
| *RF10* | Autenticação Gov.br. | ADD01, BS09, OBS01 | *Sim* | *Não se aplica* | [RF10](../pos-rastreabilidade/#rf10) |
| *RF11* | Exibir Termos de Uso/Privacidade na 1ª abertura. | ADD01, OBS03 | *Sim* | *Não se aplica* | [RF11](../pos-rastreabilidade/#rf11) |
| *RF12* | Cadastrar múltiplos celulares. | ADD01, BS02 | *Sim* | *Não se aplica* | [RF12](../pos-rastreabilidade/#rf12) |
| *RF13* | Cadastrar pessoas de confiança. | ST05, BS05 | *Sim* | *Não se aplica* | [RF13](../pos-rastreabilidade/#rf13) |
| *RF14* | Botão de emergência (alerta de bloqueio). | ADD04, OBS04, ST02 | *Sim* | [Casos de Uso](../../documento-modelagem/caso-de-uso/) | [RF14](../pos-rastreabilidade/#rf14) |
| *RF15* | Selecionar tipo de bloqueio. | ADD04, BS06 | *Sim* | Casos de Uso | [RF15](../pos-rastreabilidade/#rf15) |
| *RF16* | Gerar protocolo único pós-alerta. | ADD04, QS07 | *Não* | Casos de Uso, Léxicos | [RF16](../pos-rastreabilidade/#rf16) |
| *RF17* | Envio automático de alerta a parceiros. | ADD04, BS10 | *Sim* | Casos de Uso | [RF17](../pos-rastreabilidade/#rf17) |
| *RF18* | Consulta de restrição por IMEI. | ADD03, QS11 | *Não* | *Não se aplica* | [RF18](../pos-rastreabilidade/#rf18) |
| *RF19* | Mesmas funções em app e portal web. | ADD01, BS08 | *Sim* | *Não se aplica* | [RF19](../pos-rastreabilidade/#rf19) |
| *RF20* | Permitir múltiplos alertas para mesma linha. | BS06, QS13 | *Não* | *Não se aplica* | [RF20](../pos-rastreabilidade/#rf20) |
| *RF21* | Notificar troca de SIM em modo Recuperação. | ADD04, BS06 | *Não* | Casos de Uso | [RF21](../pos-rastreabilidade/#rf21) |
| *RF22* | Bloqueio remoto do aparelho. | ADD04, BS06 | *Não* | Casos de Uso | [RF22](../pos-rastreabilidade/#rf22) |
| *RF23* | Apagar todos os dados do dispositivo. | BS06, QS06 | *Não* | *Não se aplica* | [RF23](../pos-rastreabilidade/#rf23) |
| *RF24* | Contatar autoridades com relatório. | ST04, BS10 | *Não* | Casos de Uso, Léxicos | [RF24](../pos-rastreabilidade/#rf24) |
| *RF25* | Rastrear localização em tempo real. | QS01, ADD04 | *Não* | *Não se aplica* | [RF25](../pos-rastreabilidade/#rf25) |
| *RF26* | Histórico de movimentação no mapa. | BS05, OBS05 | *Não* | *Não se aplica* | [RF26](../pos-rastreabilidade/#rf26) |
| *RF27* | Localização exata (coordenadas/mapa). | QS01, OBS06 | *Não* | Casos de Uso, Léxicos | [RF27](../pos-rastreabilidade/#rf27) |
| *RF28* | Alerta SOS automático para contatos. | ST05, BS05 | *Não* | *Não se aplica* | [RF28](../pos-rastreabilidade/#rf28) |
| *RF29* | Bloquear chip via operadora. | ADD04, BS10 | *Sim* | Casos de Uso | [RF29](../pos-rastreabilidade/#rf29) |
| *RF30* | Guia de usuário embutido. | BS01, OBS02 | *Sim* | *Não se aplica* | [RF30](../pos-rastreabilidade/#rf30) |
| *RF31* | Contatos de segurança + notificações. | BS05, ST05 | *Sim* | *Não se aplica* | [RF31](../pos-rastreabilidade/#rf31) |
| *RF32* | Portal web para controle remoto. | ADD01, BS08 | *Sim* | *Não se aplica* | [RF32](../pos-rastreabilidade/#rf32) |
| *RF33* | Sincronizar notificações push/e-mail. | BS08, QS13 | *Sim* | *Não se aplica* | [RF33](../pos-rastreabilidade/#rf33) |
| *RF34* | Botão de “bloqueio rápido” fixo na tela. | OBS04, BS06 | *Sim* | *Não se aplica* | [RF34](../pos-rastreabilidade/#rf34) |
| *RF35* | Comandos por voz (bloqueio, SOS, etc.). | BS07 | *Não* | *Não se aplica* | [RF35](../pos-rastreabilidade/#rf35) |
| *RF36* | Backup automático antes do bloqueio. | BS06, QS06 | *Não* | *Não se aplica* | [RF36](../pos-rastreabilidade/#rf36) |
| *RF37* | Restaurar dados de backup via e-mail. | BS06, QS06 | *Não* | *Não se aplica* | [RF37](../pos-rastreabilidade/#rf37) |
| *RF38* | Som remoto para localizar aparelho. | QS01, ST06 | *Não* | Casos de Uso, Léxicos | [RF38](../pos-rastreabilidade/#rf38) |
| *RF39* | Rastreamento via satélite (offline). | BS07 | *Não* | *Não se aplica* | [RF39](../pos-rastreabilidade/#rf39) |
| *RF40* | E-mail detalhado de acesso suspeito. | QS08, BS06 | *Não* | [Léxicos](../../documento-modelagem/lexico/) | [RF40](../pos-rastreabilidade/#rf40) |
| *RF41* | Relatório de movimentação em PDF. | BS10 | *Não* | *Não se aplica* | [RF41](../pos-rastreabilidade/#rf41) |
| *RF42* | Definir dispositivo de confiança secundário. | BS05, OBS07 | *Não* | *Não se aplica* | [RF42](../pos-rastreabilidade/#rf42) |

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/arthurlleite">Vitor Pereira</a> e <a href="https://github.com/arthurlleite">Daniel Rodrigues</p></font>

---

## Requisitos não funcionais

<p style="text-align:center"><b><a id="tab_2" style="visibility:hidden;"></a>Tabela 2</b> – Requisitos não funcionais</p>

| ID | Descrição | Pré-Rastreabilidade | Implementação | Artefatos | Elos |
|----|-----------|---------------------|---------------|-----------|------|
| *RNF01* | Estabilidade/confiabilidade em emergências. | QS09, OBS21, BS40, ST11, ADD13 | *Não* | [Especificação Suplementar](../../documento-modelagem/especificacoes-suplementar/) | [RNF01](../pos-rastreabilidade/#rnf01) |
| *RNF02* | Design acessível (idosos). | Q19, OBS18, BS42/BS43, ST8, ADD17 | *Não* | Especificação Suplementar | [RNF02](../pos-rastreabilidade/#rnf02) |
| *RNF03* | Modo escuro (dark-mode). | QS09, BS43 | *Não* | Especificação Suplementar | [RNF03](../pos-rastreabilidade/#rnf03) |
| *RNF04* | Legendas em ícones/menus. | QS12, OBS15, BS36, ST8, ADD16 | *Sim* | Especificação Suplementar | [RNF04](../pos-rastreabilidade/#rnf04) |
| *RNF05* | SMS automático p/ pessoa de confiança. | QS14 | *Não* | [NFR Framework](../../documento-modelagem/Agil/NR_Framework/) | [RNF05](../pos-rastreabilidade/#rnf05) |
| *RNF06* | Canal de suporte técnico. | QS14, OBS21, BS52, ADD17 | *Não* | Especificação Suplementar | [RNF06](../pos-rastreabilidade/#rnf06) |
| *RNF07* | Disponibilidade 24×7. | ADD13, OBS21, BS40, ST11 | *Não* | Especificação Suplementar | [RNF07](../pos-rastreabilidade/#rnf07) |
| *RNF08* | Alerta instantâneo / bloqueio em minutos. | ADD14, ST9, BS41, BS58 | *Não* | Especificação Suplementar | [RNF08](../pos-rastreabilidade/#rnf08) |
| *RNF09* | Criptografia + LGPD. | ADD15, ST10, BS47 | *Não* | Especificação Suplementar | [RNF09](../pos-rastreabilidade/#rnf09) |
| *RNF10* | Serviço 100 % gratuito. | ADD18 | *Sim* | *Não se aplica* | [RNF10](../pos-rastreabilidade/#rnf10) |
| *RNF11* | Conformidade legal (Anatel, Febraban). | ADD19 | *Sim* | Especificação Suplementar | [RNF11](../pos-rastreabilidade/#rnf11) |
| *RNF12* | Linguagem simples. | BS37, ST8, ADD16 | *Sim* | Léxicos | [RNF12](../pos-rastreabilidade/#rnf12) |
| *RNF13* | Layout consistente (heurísticas). | BS38, ST8, ADD16 | *Não* | Especificação Suplementar | [RNF13](../pos-rastreabilidade/#rnf13) |
| *RNF14* | Resposta da interface < 200 ms. | BS39, ST9, ADD14 | *Sim* | NFR Framework | [RNF14](../pos-rastreabilidade/#rnf14) |
| *RNF15* | VLibras + leitor de tela. | BS42, OBS18, ADD17 | *Não* | Especificação Suplementar | [RNF15](../pos-rastreabilidade/#rnf15) |
| *RNF16* | Transcrição em tempo real. | BS44 | *Não* | Especificação Suplementar | [RNF16](../pos-rastreabilidade/#rnf16) |
| *RNF17* | GPS com precisão ≤ 10 m. | BS45 | *Não* | Casos de Uso, Léxicos, Cenários, NFR Framework | [RNF17](../pos-rastreabilidade/#rnf17) |
| *RNF18* | 2FA com fallback SMS. | BS48 | *Não* | Casos de Uso, Especificação Suplementar | [RNF18](../pos-rastreabilidade/#rnf18) |
| *RNF19* | Logs imutáveis (1 ano). | BS49 | *Não* | Casos de Uso | [RNF19](../pos-rastreabilidade/#rnf19) |
| *RNF20* | Política de privacidade clara. | BS50 | *Não* | NFR Framework | [RNF20](../pos-rastreabilidade/#rnf20) |
| *RNF21* | Checksum de integridade. | BS53 | *Não* | Especificação Suplementar | [RNF21](../pos-rastreabilidade/#rnf21) |
| *RNF22* | Compatível com Android/iOS (3 versões). | BS57, ADD17 | *Sim* | Especificação Suplementar | [RNF22](../pos-rastreabilidade/#rnf22) |
| *RNF23* | App inicia em < 2 s. | BS58, ST9, ADD14 | *Sim* | Especificação Suplementar | [RNF23](../pos-rastreabilidade/#rnf23) |
| *RNF24* | Patches de segurança ≤ 24 h. | BS60 | *Não* | Especificação Suplementar | [RNF24](../pos-rastreabilidade/#rnf24) |
| *RNF25* | Páginas ≤ 2 s no 4G. | OBS16, BS39, ST9, ADD14 | *Sim* | Especificação Suplementar, NFR Framework | [RNF25](../pos-rastreabilidade/#rnf25) |
| *RNF26* | Resposta correta a entradas erradas. | OBS19 | *Não* | NFR Framework | [RNF26](../pos-rastreabilidade/#rnf26) |
| *RNF27* | Confirmação visual das ações. | OBS20 | *Sim* | Casos de Uso, NFR Framework | [RNF27](../pos-rastreabilidade/#rnf27) |

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/arthurlleite">Vitor Pereira</a> e <a href="https://github.com/arthurlleite">Daniel Rodrigues</p></font>

---

### Referência

> SAYÃO, M.; LEITE, J. C. S. P. *Rastreabilidade de Requisitos*. Monografias em Ciência da Computação 20/05, PUC-Rio, 2005.

---

# Histórico de Versões

| Versão | Data de produção   | Descrição da Alteração                               | Autor(es)             | Revisor(es)      | Data de Revisão |
| :----: | :----------------: | :--------------------------------------------------: | :-------------------: | :-------------:  | :-------------: |
| 1.0    | 06/02/2025         | Criação inicial do documento                         | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | 06/06/2025 |
| 1.1    | 06/02/2025         | Adição das seções de Introdução, Objetivos e Metodologia | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | 06/06/2025 
| 1.2    | 07/06/2025         | Atualização da rastreabilidade dos artefatos | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> , <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a>  | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | 08/02/2025 |
| 1.3    | 07/06/2025         | Adição dos requisitos não funcionais | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Vitor Bessa</a> , <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Daniel Rodrigues</a>  | <a style="color:gold;" href="https://github.com/zDrNz" target="_blank">Mateus Bastos</a> | 08/02/2025 |
| 1.4    | 07/06/2025         | Correção dos links de rastreabilidade | <a style="color:gold;" href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a>  | <a style="color:gold;" href="https://github.com/zDrNz" target="_blank">Daniel Rodrigues</a> | 08/02/2025 |
