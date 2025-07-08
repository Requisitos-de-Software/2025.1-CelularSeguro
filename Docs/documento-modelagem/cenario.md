<span style="background-color:#2c2c7c; color:white; font-size:0.8em; font-weight: bold; padding:2px 6px; border-radius:4px;">Versão 1.3</span>

# Cenários de Uso

---

## Introdução

<div style="text-align: justify;">
Os cenários permitem descrever interações típicas entre usuários e o sistema, facilitando a compreensão dos requisitos. Através deles, é possível identificar funcionalidades, restrições e comportamentos esperados. O objetivo é garantir uma base sólida para o desenvolvimento de sistemas alinhados às necessidades reais dos usuários. Os cenários produzidos estão listados de 1 a 5.
</div>

!!! Warning "Atenção!"
    O conteúdo deste tópico **poderá sofrer alterações** ao longo da Disciplina de Requisitos de Software. Portanto, as tabelas serão organizadas iniciando pela versão mais recente e finalizando com a versão mais antiga.

## Integrantes que atuaram no desenvolvimento do artefato

Esta tabela inicial terá somente os artefatos de alta relevância que cada integrante do projeto desenvolveu. O versionamento **completo** encontra-se ao final do artefato.

<font size="3"><p style="text-align: center">_Tabela de Contribuição_</p></font>

| Nome | Função |
| :--- | :--- |
| [<span style="color:gold;">repolhudo</span>](https://github.com/repolhudo) | Autor da: [[ Figura 1 ]](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-pre-rastreabilidade/aplicativos_analisados/#sinesp-cidadao)|
| [<span style="color:gold;">repolhudo junior</span>](https://github.com/arthurlleite) | Revisor do Artefato |

*Legenda:* 

**Nome** – participante da técnica. 

**Função** – papel desempenhado na priorização. 

!!! Tip "Observação"
    Frizando claramente que as contribuições de cada integrante ainda que mínimas são ainda sim muito relevantes no desenvolvimento do artefo, considere verificar o histórico de versão. 

---

## Cenário 1: Filtrar por tipo de celular

| **Elemento** | **Descrição**                                                                                                                                                                                                                                                                    |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Título       | Filtrar dispositivos por tipo de celular.                                                                                                                                                                                                                                        |
| Objetivo     | Permitir que o usuário encontre rapidamente dispositivos cadastrados filtrando-os por seu tipo (por exemplo, smartphone Android, iPhone, tablet etc.).                                                                                                                           |
| Contexto     | **Local:** Tela de lista de dispositivos no aplicativo Celular Seguro.<br>**Tempo:** Aproximadamente 1 minuto.<br>**Pré-condição:** Usuário logado e com ao menos um dispositivo cadastrado; existirem dispositivos de diferentes tipos na conta.                                |
| Atores       | Usuário do aplicativo Celular Seguro.                                                                                                                                                                                                                                            |
| Recursos     | Conexão ativa à internet.<br>Smartphone com o aplicativo Celular Seguro instalado.                                                                                                                                                                                               |
| Episódios    | 1. Usuário acessa a tela de lista de dispositivos.<br>2. Seleciona o ícone/botão de filtro.<br>3. Visualiza opções de filtro por tipo de celular.<br>4. Escolhe categoria desejada (Android, iOS, Básico etc.).<br>5. Sistema exibe somente os dispositivos do tipo selecionado. |
| Restrições   | - Só filtros correspondentes a categorias existentes na conta.<br>- Interface deve apresentar lista pré-definida de tipos reconhecidos pelo sistema.                                                                                                                             |
| Exceções     | **Erro de conexão:** Sem internet, exibir mensagem de erro e não aplicar filtro.<br>**Nenhum dispositivo do tipo:** Exibir mensagem informando que não há dispositivos na categoria selecionada.                                                                                 |
| Fonte        | Arthur Carvalho e Daniel Rodrigues                                                                                                                                                                                                                                               |

---

## Cenário 2: Selecionar ações de segurança para um dispositivo

| **Elemento** | **Descrição**                                                                                                                                                                                                                                                                                                                              |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Título       | Selecionar uma ação de segurança em um dispositivo cadastrado.                                                                                                                                                                                                                                                                             |
| Objetivo     | Permitir que o usuário escolha e execute ações de segurança (localizar, soar alarme, bloquear, apagar dados) para um dispositivo cadastrado.                                                                                                                                                                                               |
| Contexto     | **Local:** Tela de detalhes ou painel de controle de um dispositivo.<br>**Tempo:** Aproximadamente 2 minutos.<br>**Pré-condição:** Usuário logado; dispositivo registrado e sincronizado (ativo).                                                                                                                                          |
| Atores       | Usuário do aplicativo Celular Seguro.                                                                                                                                                                                                                                                                                                      |
| Recursos     | Conexão ativa à internet.<br>Smartphone ou interface web do Celular Seguro.<br>Dispositivo alvo previamente registrado no sistema.                                                                                                                                                                                                         |
| Episódios    | 1. Usuário navega até a tela de detalhes do dispositivo.<br>2. Visualiza lista de ações de segurança disponíveis.<br>3. Seleciona ação desejada (ex.: Bloqueio remoto).<br>4. Confirma detalhes ou confirmação extra.<br>5. Sistema envia comando via Internet.<br>6. Dispositivo executa ação.<br>7. Aplicativo informa sucesso ou falha. |
| Restrições   | - Ações só em dispositivos vinculados à conta.<br>- Ações potencialmente destrutivas requerem confirmação extra.<br>- Algumas ações dependem do dispositivo estar online.                                                                                                                                                                  |
| Exceções     | **Dispositivo offline:** Informar que a ação não pôde ser concluída; tentar novamente quando online.<br>**Falha de comunicação:** Exibir erro de envio do comando.<br>**Permissão não concedida:** Notificar motivo da falha se permissões insuficientes.                                                                                  |
| Fonte        | Arthur Carvalho e Daniel Rodrigues                                                                                                                                                                                                                                                                                                         |

---

## Cenário 3: Registrar um novo aparelho

| **Elemento** | **Descrição**                                                                                                                                                                                                                                                                                                                              |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Título       | Registrar um novo aparelho no sistema.                                                                                                                                                                                                                                                                                                     |
| Objetivo     | Permitir que o usuário cadastre um novo dispositivo (celular ou tablet) para monitoramento e uso das funcionalidades de segurança.                                                                                                                                                                                                         |
| Contexto     | **Local:** Tela de registro de dispositivo no aplicativo.<br>**Tempo:** Aproximadamente 3 minutos.<br>**Pré-condição:** Usuário logado; dispositivo em mãos ou informações disponíveis (IMEI, número de série).                                                                                                                            |
| Atores       | Usuário do aplicativo Celular Seguro.                                                                                                                                                                                                                                                                                                      |
| Recursos     | Conexão ativa à internet.<br>Dispositivo ou computador com acesso ao app/site.<br>Novo dispositivo a ser cadastrado.                                                                                                                                                                                                                       |
| Episódios    | 1. Seleciona opção “Adicionar novo aparelho”.<br>2. Preenche formulário ou usa coleta automática de dados (IMEI, modelo, fabricante, apelido).<br>3. Confirma envio do formulário.<br>4. Sistema valida IMEI e verificações de unicidade.<br>5. Cadastro é concluído e novo dispositivo aparece na lista.<br>6. Exibe mensagem de sucesso. |
| Restrições   | - Limite máximo de dispositivos por usuário (se aplicável).<br>- Só registrar dispositivos compatíveis.<br>- Campos obrigatórios (IMEI, série) devem estar corretos.                                                                                                                                                                       |
| Exceções     | **Dispositivo já cadastrado:** Notificar impossibilidade e orientar suporte.<br>**Dados inválidos:** Solicitar correção de informações.<br>**Falha de conexão:** Salvar temporariamente dados e permitir reenvio.<br>**Cancelamento:** Não alterar nada se o usuário desistir.                                                             |
| Fonte        | Arthur Carvalho e Daniel Rodrigues                                                                                                                                                                                                                                                                                                         |

---

## Cenário 4: Visualizar ocorrências em um mapa

| **Elemento** | **Descrição**                                                                                                                                                                                                                                                                                                                   |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Título       | Visualizar ocorrências de segurança em um mapa interativo.                                                                                                                                                                                                                                                                      |
| Objetivo     | Permitir que o usuário visualize em mapa geográfico as ocorrências relacionadas a dispositivos e roubos/furtos reportados.                                                                                                                                                                                                      |
| Contexto     | **Local:** Tela de mapa no aplicativo Celular Seguro.<br>**Tempo:** Indeterminado (carregamento inicial leva alguns segundos).<br>**Pré-condição:** Existirem ocorrências ou dispositivos marcados como perdidos; app com acesso à Internet.                                                                                    |
| Atores       | Usuário do aplicativo Celular Seguro.                                                                                                                                                                                                                                                                                           |
| Recursos     | Conexão ativa à internet.<br>Smartphone com permissão de localização e uso de API de mapas.                                                                                                                                                                                                                                     |
| Episódios    | 1. Acessa funcionalidade de mapa.<br>2. Sistema obtém dados de ocorrências.<br>3. Exibe mapa com marcadores: localização de dispositivos e pontos de roubos.<br>4. Usuário interage com zoom e pan.<br>5. Ao tocar em marcador, exibe detalhes (data/hora, estatísticas).<br>6. Usuário toma decisões com base nas informações. |
| Restrições   | - Possibilidade de filtrar ocorrências por período/tipo.<br>- Informações de terceiros devem ser anônimas (LGPD).<br>- Uso de API de mapas confiável e design responsivo.                                                                                                                                                       |
| Exceções     | **Sem dados:** Exibir mensagem “Nenhuma ocorrência disponível”.<br>**Falha de localização:** Centralizar mapa em região padrão e alertar indisponibilidade de GPS.<br>**Problemas de conexão:** Exibir erro e oferecer retry; carregar apenas dados já obtidos.                                                                 |
| Fonte        | Arthur Carvalho e Daniel Rodrigues                                                                                                                                                                                                                                                                                              |

---

## Cenário 5: Bloquear remotamente um dispositivo

| **Elemento** | **Descrição**                                                                                                                                                                                                                                                                                                                                                          |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Título       | Bloquear remotamente um dispositivo cadastrado.                                                                                                                                                                                                                                                                                                                        |
| Objetivo     | Permitir que o usuário bloqueie seu aparelho à distância para proteger dados e impedir uso indevido.                                                                                                                                                                                                                                                                   |
| Contexto     | **Local:** App/site em dispositivo alternativo.<br>**Tempo:** Aproximadamente 1 minuto.<br>**Pré-condição:** Usuário autenticado em outra plataforma; aparelho cadastrado e, preferencialmente, marcado como perdido/roubado; dispositivo alvo ligado e online para receber comando.                                                                                   |
| Atores       | Usuário do aplicativo Celular Seguro.                                                                                                                                                                                                                                                                                                                                  |
| Recursos     | Conexão ativa à internet no dispositivo de envio; infraestrutura de envio (Internet/SMS).                                                                                                                                                                                                                                                                              |
| Episódios    | 1. Usuário acessa Celular Seguro de outro dispositivo.<br>2. Faz login e seleciona aparelho alvo.<br>3. Clica em “Bloqueio Remoto do Dispositivo”.<br>4. Confirma ação (senha ou prompt extra).<br>5. Sistema envia comando de bloqueio.<br>6. Se online, aparelho bloqueia imediatamente; se offline, tenta enviar quando conectar.<br>7. Notifica usuário do status. |
| Restrições   | - Requer permissões prévias (privilégios de administrador).<br>- Somente proprietário autenticado pode bloquear.<br>- Ação depende de infraestrutura de rede e SO do dispositivo.                                                                                                                                                                                      |
| Exceções     | **Inacessível:** Após várias tentativas sem resposta, informar usuário e sugerir bloqueio de IMEI/SIM via operadora.<br>**Falha na execução:** Notificar resultado incerto e orientar nova tentativa.<br>**Erro de sessão:** Redirecionar para login se sessão expirar no meio do processo.                                                                            |
| Fonte        | Arthur Carvalho e Daniel Rodrigues                                                                                                                                                                                                                                                                                                                                     |

---

## Cenário 6: Alterar apelido de um dispositivo cadastrado

| **Elemento** | **Descrição** |
| ------------ | ------------- |
| **Título** | Alterar o apelido de um dispositivo cadastrado. |
| **Objetivo** | Permitir que o usuário personalize o nome do dispositivo para facilitar a identificação na lista de dispositivos cadastrados. |
| **Contexto** | **Local:** Tela de detalhes do dispositivo.<br>**Tempo:** Aproximadamente 1 minuto.<br>**Pré-condição:** Usuário autenticado; dispositivo já cadastrado. |
| **Atores** | Usuário do aplicativo Celular Seguro. |
| **Recursos** | Conexão ativa à internet.<br>Smartphone ou acesso ao site Celular Seguro. |
| **Episódios** | 1. Usuário acessa a lista de dispositivos.<br>2. Seleciona o dispositivo desejado.<br>3. Clica em "Editar Apelido".<br>4. Digita novo apelido e confirma.<br>5. Sistema salva alteração e atualiza o nome na interface. |
| **Restrições** | - Apelido deve ter tamanho máximo de 30 caracteres.<br>- Não aceitar apelidos duplicados para o mesmo usuário. |
| **Exceções** | **Conexão perdida:** Informar falha ao salvar e permitir nova tentativa.<br>**Campo vazio ou inválido:** Exibir alerta e solicitar correção. |
| **Fonte** | Arthur Carvalho e Daniel Rodrigues |

---

## Cenário 7: Receber notificação de alteração de status do dispositivo

| **Elemento** | **Descrição** |
| ------------ | ------------- |
| **Título** | Receber notificação ao alterar status de dispositivo. |
| **Objetivo** | Informar o usuário em tempo real quando o status do dispositivo mudar para perdido, recuperado ou bloqueado. |
| **Contexto** | **Local:** Sistema de notificações do app ou push notification.<br>**Tempo:** Imediato após alteração.<br>**Pré-condição:** Notificações habilitadas no dispositivo do usuário. |
| **Atores** | Usuário do aplicativo Celular Seguro. |
| **Recursos** | Conexão ativa à internet.<br>Dispositivo com notificações push habilitadas. |
| **Episódios** | 1. Usuário ou sistema altera status do dispositivo.<br>2. Sistema gera notificação push informando a alteração.<br>3. Usuário visualiza notificação e pode clicar para abrir detalhes no app. |
| **Restrições** | - Notificações dependem de permissão do usuário.<br>- Informações sensíveis devem ser protegidas (não incluir dados pessoais). |
| **Exceções** | **Dispositivo sem notificações:** Enviar e-mail como alternativa.<br>**Falha de envio:** Registrar tentativa e reenviar automaticamente. |
| **Fonte** | Arthur Carvalho e Daniel Rodrigues |

---

## Cenário 8: Consultar histórico de localização de um dispositivo

| **Elemento** | **Descrição** |
| ------------ | ------------- |
| **Título** | Consultar histórico de localização do dispositivo. |
| **Objetivo** | Permitir ao usuário visualizar os últimos locais registrados pelo dispositivo para rastreamento. |
| **Contexto** | **Local:** Tela de detalhes do dispositivo.<br>**Tempo:** Indeterminado.<br>**Pré-condição:** Dispositivo cadastrado com rastreamento ativo. |
| **Atores** | Usuário do aplicativo Celular Seguro. |
| **Recursos** | Conexão ativa à internet.<br>Permissão de rastreamento de localização no dispositivo. |
| **Episódios** | 1. Usuário acessa detalhes do dispositivo.<br>2. Seleciona "Histórico de Localização".<br>3. Visualiza lista de localizações com data e hora.<br>4. Pode selecionar ponto no mapa para ver detalhes. |
| **Restrições** | - Histórico limitado a 30 dias.<br>- Exibir apenas para dispositivos com rastreamento habilitado. |
| **Exceções** | **Sem histórico:** Exibir mensagem informativa.<br>**Falha de conexão:** Permitir nova tentativa de carregamento. |
| **Fonte** | Arthur Carvalho e Daniel Rodrigues |

---

## Cenário 9: Ativar modo perdido no dispositivo

| **Elemento** | **Descrição** |
| ------------ | ------------- |
| **Título** | Ativar modo perdido em um dispositivo. |
| **Objetivo** | Permitir ao usuário marcar um dispositivo como perdido para intensificar rastreamento e exibir mensagem personalizada na tela do aparelho. |
| **Contexto** | **Local:** Tela de detalhes do dispositivo.<br>**Tempo:** Aproximadamente 1 minuto.<br>**Pré-condição:** Dispositivo cadastrado e online. |
| **Atores** | Usuário do aplicativo Celular Seguro. |
| **Recursos** | Conexão ativa à internet.<br>Dispositivo com Celular Seguro instalado e permissões necessárias. |
| **Episódios** | 1. Usuário acessa detalhes do dispositivo.<br>2. Seleciona "Ativar Modo Perdido".<br>3. Digita mensagem de contato opcional.<br>4. Confirma ativação.<br>5. Sistema envia comando ao dispositivo e ativa o modo perdido. |
| **Restrições** | - Requer autenticação prévia.<br>- Modo só pode ser ativado em dispositivos do usuário. |
| **Exceções** | **Dispositivo offline:** Agendar envio do comando.<br>**Erro de envio:** Informar falha e permitir nova tentativa. |
| **Fonte** | Arthur Carvalho e Daniel Rodrigues |

---

## Cenário 10: Compartilhar status de dispositivo com contato de confiança

| **Elemento** | **Descrição** |
| ------------ | ------------- |
| **Título** | Compartilhar status do dispositivo com contato de confiança. |
| **Objetivo** | Permitir ao usuário compartilhar a última localização e status do dispositivo com um contato em caso de perda ou roubo. |
| **Contexto** | **Local:** Tela de detalhes do dispositivo.<br>**Tempo:** Aproximadamente 2 minutos.<br>**Pré-condição:** Dispositivo cadastrado; contato de confiança previamente configurado. |
| **Atores** | Usuário do aplicativo Celular Seguro. |
| **Recursos** | Conexão ativa à internet.<br>Dispositivo do usuário com app Celular Seguro. |
| **Episódios** | 1. Usuário acessa detalhes do dispositivo.<br>2. Seleciona "Compartilhar Status".<br>3. Escolhe contato de confiança.<br>4. Sistema envia mensagem com status e última localização. |
| **Restrições** | - Contato deve estar cadastrado previamente.<br>- Permissão do usuário para envio de localização. |
| **Exceções** | **Erro de envio:** Notificar usuário e permitir nova tentativa. |
| **Fonte** | Arthur Carvalho e Daniel Rodrigues |

---

## Cenário 11: Receber alerta de troca de chip no dispositivo

| **Elemento** | **Descrição** |
| ------------ | ------------- |
| **Título** | Receber alerta de troca de chip no dispositivo cadastrado. |
| **Objetivo** | Notificar o usuário caso o chip do dispositivo seja trocado, auxiliando na detecção de furto ou uso não autorizado. |
| **Contexto** | **Local:** Sistema de notificações do aplicativo.<br>**Tempo:** Imediato após detecção da troca.<br>**Pré-condição:** Dispositivo cadastrado e funcional com rastreamento ativo. |
| **Atores** | Usuário do aplicativo Celular Seguro. |
| **Recursos** | Conexão ativa à internet no dispositivo. |
| **Episódios** | 1. Sistema detecta alteração no número do SIM card.<br>2. Gera notificação ao usuário informando alteração detectada.<br>3. Usuário acessa detalhes e verifica informações. |
| **Restrições** | - Requer permissão de monitoramento de SIM card. |
| **Exceções** | **Notificação não entregue:** Tentar novamente ou enviar e-mail. |
| **Fonte** | Arthur Carvalho e Daniel Rodrigues |

---

## Cenário 12: Remover dispositivo cadastrado

| **Elemento** | **Descrição** |
| ------------ | ------------- |
| **Título** | Remover dispositivo cadastrado do sistema. |
| **Objetivo** | Permitir ao usuário excluir um dispositivo que não deseja mais monitorar pelo aplicativo. |
| **Contexto** | **Local:** Tela de detalhes do dispositivo.<br>**Tempo:** Aproximadamente 1 minuto.<br>**Pré-condição:** Usuário logado no sistema. |
| **Atores** | Usuário do aplicativo Celular Seguro. |
| **Recursos** | Conexão ativa à internet. |
| **Episódios** | 1. Usuário acessa detalhes do dispositivo.<br>2. Seleciona "Remover Dispositivo".<br>3. Confirma remoção.<br>4. Sistema exclui registro do dispositivo e atualiza lista. |
| **Restrições** | - Remoção apenas pelo proprietário do dispositivo. |
| **Exceções** | **Erro de conexão:** Permitir nova tentativa.<br>**Erro de autenticação:** Solicitar login novamente. |
| **Fonte** | Arthur Carvalho e Daniel Rodrigues |

---

## Cenário 13: Atualizar firmware do aplicativo remotamente

| **Elemento** | **Descrição** |
| ------------ | ------------- |
| **Título** | Atualizar firmware do Celular Seguro remotamente. |
| **Objetivo** | Permitir que o usuário atualize remotamente a versão do app no dispositivo cadastrado, garantindo maior segurança. |
| **Contexto** | **Local:** Painel de controle do dispositivo.<br>**Tempo:** Aproximadamente 5 minutos.<br>**Pré-condição:** Dispositivo online e cadastrado. |
| **Atores** | Usuário do aplicativo Celular Seguro. |
| **Recursos** | Conexão ativa à internet. |
| **Episódios** | 1. Usuário acessa painel do dispositivo.<br>2. Verifica disponibilidade de atualização.<br>3. Seleciona "Atualizar Agora".<br>4. Sistema envia comando e acompanha progresso.<br>5. Confirma sucesso ou notifica falha. |
| **Restrições** | - Dispositivo deve estar conectado.<br>- Pode consumir dados móveis. |
| **Exceções** | **Falha de atualização:** Exibir motivo e orientações. |
| **Fonte** | Arthur Carvalho e Daniel Rodrigues |

---

## Cenário 14: Consultar status do bloqueio de IMEI

| **Elemento** | **Descrição** |
| ------------ | ------------- |
| **Título** | Consultar status do bloqueio de IMEI do dispositivo. |
| **Objetivo** | Permitir ao usuário verificar se o IMEI do dispositivo está bloqueado na operadora em caso de roubo ou furto. |
| **Contexto** | **Local:** Tela de detalhes do dispositivo.<br>**Tempo:** Indeterminado.<br>**Pré-condição:** Dispositivo cadastrado com IMEI informado. |
| **Atores** | Usuário do aplicativo Celular Seguro. |
| **Recursos** | Conexão ativa à internet. |
| **Episódios** | 1. Usuário acessa detalhes do dispositivo.<br>2. Seleciona "Consultar Status de IMEI".<br>3. Sistema consulta base de dados de IMEIs bloqueados.<br>4. Exibe status atual para o usuário. |
| **Restrições** | - Requer integração com bases de dados de operadoras. |
| **Exceções** | **Falha de consulta:** Informar ao usuário e permitir nova tentativa. |
| **Fonte** | Arthur Carvalho e Daniel Rodrigues |

---

<p style="text-align: center">Entrevista Cenários</p>

<center>
<iframe width="560" height="315" src="https://youtu.be/82g1cYMHM-Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</center>

<p style="text-align: center">Caso não abra <a href="https://youtu.be/82g1cYMHM-Q" target="blanket">clique aqui</a></p>
>PDF (07 julho. 2025): [Termo de Compromisso](https://github.com/Requisitos-de-Software/2025.1-CelularSeguro/blob/main/Docs/assets/pdf/verificacao/Copia_de_Termo_Consentimento_CelularSeguro_assinado.pdf)

<font size="3"><p style="text-align: center">Fonte: [Arthur Carvalho](https://github.com/arthurlleite)</p></font>


## Bibliografia

> SERRANO, Milene. *Requisitos – Aula 10*. 2017. Apresentação de slides. Disponível em: [aprender3.unb.br](https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf). Último acesso em: 14 abr. 2025.
>
> *ANÁLISE de Requisitos de Software da Aplicação Bilheteria Digital*, 2024. Disponível em: [requisitos-de-software.github.io](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/). Último acesso em: 14 abr. 2025.

---

## Histórico de Versões

| Versão | Data de produção |    Descrição da alteração    |                                              Autor(es)                                             |                    Revisor(es)                    | Data de revisão |
| :----: | :--------------: | :--------------------------: | :------------------------------------------------------------------------------------------------: | :-----------------------------------------------: | :-------------: |
|   1.0  |    09/05/2025    |     Criação do documento     |                         [Gabriel Lima](https://github.com/gabriel-lima258)                         |  [Mateus Bastos](https://github.com/MateuSansete) |    09/05/2025   |
|   1.1  |    14/05/2025    | Desenvolvimento do documento | [Arthur Carvalho](https://github.com/arthurlleite),  | [Leonardo de Melo](https://github.com/leozinlima) |    14/05/2025   |
|   1.2  |    17/05/2025    | Tabelas concertadas e ajustadas | [Leonardo de Melo](https://github.com/leozinlima) | [Arthur Carvalho](https://github.com/arthurlleite), [Daniel Rodrigues](https://github.com/Bessazs) |    17/05/2025   |
|   1.3  |    05/07/2025     | Inserção da tabela de contribuição | [Felipe das Neves](https://github.com/FelipeFreire-gf) | [Arthur Carvalho](https://github.com/arthurlleite), [Mateus Bastos](https://github.com/MateuSansete) |    05/07/2025    |
|   1.4  |    07/07/2025    | Adicionado mais Cenários | [Arthur Carvalho](https://github.com/arthurlleite) | [Leonardo de Melo](https://github.com/leozinlima) |    07/07/2025   |
|   1.5  |    07/07/2025    | Adicionado  Entrevista | [Arthur Carvalho](https://github.com/arthurlleite) | [Leonardo de Melo](https://github.com/leozinlima) |    07/07/2025   |