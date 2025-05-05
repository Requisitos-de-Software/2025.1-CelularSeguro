### Introdução

O método de MoSCoW é uma técnica de priorização utilizada em gestão, análise de negócios, gestão de projetos e desenvolvimento de software. Visa chegar a um entendimento comum com as partes interessadas sobre a importância que atribuem à entrega de cada requisito; também é conhecido como priorização MoSCoW ou análise MoSCoW.

### Metodologia

Para que a priorização fosse feita, nós, equipe, nos reunimos via Discord onde foi discutido o levantamento dos requisitos elicitados pelas técnicas: questionário, brainstorming, storytelling, observação e prototipação aplicadas.

Dado isso, chegamos à conclusão onde melhor o requisito se encaixaria, de acordo com sua importância. Baseado nas personas e storytellings.

### Must "Deve"

Os requisitos classificados como Must (Tabela 1) representam funcionalidades essenciais para o funcionamento básico e seguro do aplicativo. Esses itens não podem ser deixados de fora, pois estão diretamente ligados aos objetivos principais do projeto, como o rastreamento do celular (RF01), bloqueio remoto com autenticação via gov.br (RF02, RF09), e a segurança de dados (RNF12, RNF13).


<font size="3"><p style="text-align: center">Tabela 1: Requisitos Must</p></font>

| Código | Descrição                                                             |
| ------ | --------------------------------------------------------------------- |
| RF01   | Localizar o celular perdido / rastrear em tempo real                  |
| RF02   | Registro e bloqueio remoto do aparelho / Apagar dados / Acesso gov.br |
| RF05   | Alerta de emergência para contatos confiáveis                         |
| RF06   | Localização via coordenadas e mapa                                    |
| RF08   | Emitir e registrar boletim de ocorrência                              |
| RF09   | Autenticação via gov.br (login seguro)                                |
| RF21   | Notificação de tentativa de acesso suspeito                           |
| RF24   | Atualização da localização em tempo real                              |
| RF26   | Notificação de troca de chip                                          |
| RF27   | Consulta de status do bloqueio e rastreamento                         |
| RF32   | Autenticação forte para limpeza remota                                |
| RNF01  | Interface intuitiva com ícones claros                                 |
| RNF02  | Linguagem simples e acessível                                         |
| RNF04  | Resposta rápida (<200ms nas ações críticas)                           |
| RNF05  | Disponibilidade 24/7 / 99,9% (SLA)                                    |
| RNF10  | Precisão do GPS (<10m)                                                |
| RNF11  | Rastreamento em segundo plano eficiente                               |
| RNF12  | Backup criptografado (AES-256)                                        |
| RNF13  | Autenticação multifator (2FA) com fallback                            |
| RNF15  | Política de privacidade visível                                       |
| RNF19  | Monitoramento de acesso não autorizado                                |
| RNF22  | Compatibilidade com Android/iOS (3 últimas)                           |
| RNF25  | Atualizações automáticas de segurança                                 |

<font size="3"><p style="text-align: center">Fonte: Felipe das Neves</p></font>

### Should "Deveria"

Na categoria Should (Tabela 2) estão funcionalidades importantes que agregam valor ao sistema, mas que podem ser implementadas após os itens essenciais. Elas complementam a experiência do usuário e ampliam a segurança e usabilidade do aplicativo, como o backup automático (RF04), portal web (RF13) e recursos de acessibilidade (RNF07, RNF08).

<font size="3"><p style="text-align: center">Requisitos Should</p></font>

| Código | Descrição                                       |
| ------ | ----------------------------------------------- |
| RF03   | Cadastro prévio do celular (IMEI, etc.)         |
| RF04   | Backup automático de dados / Restauração        |
| RF11   | Tutorial embutido (passo a passo)               |
| RF12   | Cadastro de contatos de segurança               |
| RF13   | Portal web com funções remotas                  |
| RF15   | Botão de bloqueio rápido                        |
| RF23   | Dispositivo de confiança para controle remoto   |
| RF28   | Modo perdido com ações automáticas              |
| RF33   | Logs de auditoria de ações remotas              |
| RF34   | Status de bateria/conectividade antes de ações  |
| RF35   | Integração com Google Maps para rotas/histórico |
| RNF03  | Layout consistente                              |
| RNF06  | Latência de tutoriais/assistente virtual <1s    |
| RNF07  | Acessibilidade: VLibras e leitor de tela        |
| RNF08  | Opção de contraste/tamanho de fonte             |
| RNF14  | Logs de auditoria imutáveis (1 ano)             |
| RNF16  | Notificações em tempo real (>99% entrega)       |
| RNF17  | Central de ajuda online/offline                 |
| RNF21  | Sincronização app-portal <5s                    |
| RNF23  | App inicia em <2 segundos                       |
| RNF24  | Suporte a múltiplos idiomas                     |

<font size="3"><p style="text-align: center">Fonte: Felipe das Neves</p></font>

### Could "Poderia"

Os itens da categoria Could (Tabela 3) são considerados desejáveis e inovadores, mas não prioritários neste momento. Incluem melhorias que podem ser implementadas no futuro para enriquecer a experiência do usuário, como comandos por voz (RF16), compartilhamento temporário de localização (RF30) e alarmes remotos (RF07, RF31).

<font size="3"><p style="text-align: center">Tabela 3: Requisitos Could</p></font>

| Código | Descrição                                          |
| ------ | -------------------------------------------------- |
| RF07   | Alarme remoto sonoro/visual                        |
| RF10   | Múltiplas opções de login (e-mail, social, gov.br) |
| RF14   | Sincronização de notificações entre app e portal   |
| RF16   | Comandos por voz para funções críticas             |
| RF17   | Backup automático antes do bloqueio                |
| RF18   | Restaurar backup via e-mail                        |
| RF19   | Emitir som remoto (mesmo em modo silencioso)       |
| RF22   | Relatório de movimentação em PDF                   |
| RF25   | Agendamento de bloqueio                            |
| RF29   | SMS de confirmação de ação remota                  |
| RF30   | Compartilhamento temporário de localização         |
| RF31   | Alarme sonoro e visual no dispositivo              |
| RNF09  | Transcrição em tempo real                          |
| RNF18  | Verificação de integridade com checksum            |
| RNF20  | Compressão para economizar dados móveis            |

<font size="3"><p style="text-align: center">Fonte: Felipe das Neves</p></font>

### Won't "Não vai"

Por fim, a categoria Won’t (Tabela 4) inclui requisitos que não serão implementados por ora, como o rastreamento via satélite (RF20), por envolver alta complexidade tecnológica e custo.

<font size="3"><p style="text-align: center">Requisitos Won't (por ora)</p></font>

| Código | Descrição                             |
| ------ | ------------------------------------- |
| RF20   | Rastreamento via satélite (sem sinal) |

<font size="3"><p style="text-align: center">Fonte: Felipe das Neves</p></font>

## Bibliografia

>SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. 2022. Apresentação de Power Point. 50 slides. color. Disponível em: https://aprender3.unb.br/pluginfile.php/2124453/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 04 mai. 2025.

---

## Histórico de Versões 

| Versão | Data de produção   | Descrição da Alteração                               | Autor(es)             | Revisor(es)      |Data de Revisão |
| :----: | :----------------: | :--------------------------------------------------: | :-------------------: | :-------------:  |  :-----------: |
| 1.0    | 04/05/2025         | Desenvolvimento do artefato                            |<a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a>    | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus</a>| 04/05/2025|