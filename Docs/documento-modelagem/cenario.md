# Cenários de Uso – Celular Seguro

## Introdução 

<div style="text-align: justify;">
Os cenários permitem descrever interações típicas entre usuários e o sistema, facilitando a compreensão dos requisitos. Através deles, é possível identificar funcionalidades, restrições e comportamentos esperados. O objetivo é garantir uma base sólida para o desenvolvimento de sistemas alinhados às necessidades reais dos usuários. Os cenários produzidos estão listados nas tabelas de 1 a 5.
<>

## Cenário 1

<font size="3"><p style="text-align: center">Cenário 1: Filtrar por tipo de celular</p></font>

|**Cenário 1**|
|--------------|
|**Titulo**    |
|_Filtrar dispositivos por tipo de celular._|
|**Objetivo**  |
|_Permitir que o usuário encontre rapidamente dispositivos cadastrados filtrando-os por seu tipo (por exemplo, smartphone Android, iPhone, tablet etc.)._|
|**Contexto**  |
|<p>Local: _Tela de lista de dispositivos no aplicativo Celular Seguro._</p> <p>Tempo: _Aproximadamente 1 minuto._</p> <p>Pré-condição: _O usuário estar logado no aplicativo e possuir pelo menos um dispositivo cadastrado; existirem dispositivos de diferentes tipos cadastrados na conta do usuário._</p>|
|**Atores**    |
|_Usuário do aplicativo Celular Seguro._|
|**Recursos**  |
|<p>_Conexão ativa à internet._</p><p>_Smartphone com o aplicativo Celular Seguro instalado._ </p> |
|**Episódios** |
|<p>_O usuário acessa a tela que lista todos os seus dispositivos cadastrados no Celular Seguro._</p> <p>_O usuário seleciona a opção de *filtrar dispositivos* disponível na interface (por exemplo, um ícone ou botão de filtro na tela)._</p> <p>_O aplicativo exibe as opções de filtro, incluindo a possibilidade de filtrar por tipo de celular (categoria do dispositivo)._</p> <p>_O usuário escolhe o tipo de celular desejado (por exemplo, "Android", "iOS", "Telefone básico" etc.) na lista de categorias de dispositivos._</p> <p>_O aplicativo filtra a lista e exibe apenas os dispositivos do tipo selecionado, permitindo ao usuário visualizar somente aqueles dispositivos que se encaixam na categoria escolhida._</p>|
|**Restrição** |
|<p>_O usuário só pode aplicar filtros de tipos que correspondam a categorias de dispositivo existentes em sua conta (ou disponíveis no sistema)._</p> <p>_O aplicativo deve fornecer ao usuário uma lista pré-definida de tipos/categorias de celular para seleção, garantindo que o filtro seja aplicado apenas a tipos reconhecidos pelo sistema._</p>|
|**Exceção**   |
|<p>_*Erro de conexão:* Se não houver conexão à Internet no momento da filtragem, o aplicativo exibirá uma mensagem de erro e não aplicará o filtro._</p> <p>_*Nenhum dispositivo do tipo:* Se o usuário não tiver nenhum dispositivo do tipo selecionado (ou não existirem dispositivos naquele tipo), o aplicativo exibirá uma mensagem indicando que nenhum dispositivo corresponde ao filtro escolhido, ou apresentará a lista vazia correspondente ao filtro._</p>|

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a> e <a href="https://github.com/zDrNz" target="_blank">Daniel Rodrigues</a></p></font>

## Cenário 2

<font size="3"><p style="text-align: center">Cenário 2: Selecionar ações de segurança para um dispositivo</p></font>

|**Cenário 2**|
|--------------|
|**Titulo**    |
|_Selecionar uma ação de segurança em um dispositivo cadastrado._|
|**Objetivo**  |
|_Permitir que o usuário escolha e execute ações de segurança disponibilizadas pelo Celular Seguro (como localizar, fazer soar alarme, bloquear ou apagar dados) para um de seus dispositivos cadastrados._|
|**Contexto**  |
|<p>Local: _Tela de detalhes ou painel de controle de um dispositivo específico no aplicativo Celular Seguro._</p> <p>Tempo: _Aproximadamente 2 minutos._</p> <p>Pré-condição: _O usuário estar logado e ter pelo menos um dispositivo registrado no aplicativo; o dispositivo alvo estar cadastrado no Celular Seguro e sincronizado (ativo) para receber comandos de segurança._</p>|
|**Atores**    |
|_Usuário do aplicativo Celular Seguro._|
|**Recursos**  |
|<p>_Conexão ativa à internet._</p><p>_Smartphone com o aplicativo Celular Seguro instalado (ou acesso à interface web do serviço) para gerenciar o dispositivo._ </p><p>_Dispositivo alvo previamente registrado no sistema (o telefone que receberá a ação de segurança)._</p>|
|**Episódios** |
|<p>_O usuário navega até a tela de *detalhes do dispositivo* que deseja proteger (por exemplo, selecionando o aparelho em uma lista de dispositivos cadastrados)._</p> <p>_O aplicativo exibe as informações do dispositivo selecionado, bem como uma lista de *ações de segurança disponíveis* (como "Localizar dispositivo", "Fazer celular tocar", "Bloqueio remoto", "Limpeza de dados")._</p> <p>_O usuário seleciona a ação de segurança desejada na lista de opções (por exemplo, *Bloqueio remoto* do aparelho)._</p> <p>_O aplicativo pode exibir uma tela de confirmação ou detalhes adicionais da ação (por exemplo, solicitando confirmação para executar o bloqueio ou fornecendo opções específicas daquela ação)._</p> <p>_O usuário confirma a execução da ação de segurança solicitada._</p> <p>_O aplicativo envia o comando correspondente para o dispositivo alvo através da Internet (por exemplo, instruindo-o a bloquear a tela, tocar o alarme ou enviar localização)._</p> <p>_O dispositivo alvo executa a ação de segurança recebida (por exemplo, o celular é bloqueado imediatamente ou começa a emitir um alarme sonoro)._</p> <p>_O aplicativo exibe uma notificação ou mensagem ao usuário confirmando que a ação de segurança foi acionada com sucesso (ou informa caso não tenha sido possível realizá-la)._</p>|
|**Restrição** |
|<p>_O usuário somente poderá executar ações de segurança em dispositivos que estejam vinculados à sua conta no Celular Seguro._</p> <p>_Certas ações de segurança podem requerer que o dispositivo alvo esteja *online* no momento da requisição (por exemplo, para receber um comando de bloqueio ou de apagar dados). O sistema deve deixar claro quais ações dependem de conectividade imediata._</p> <p>_O design da interface deve garantir que a seleção de ações de segurança seja intuitiva e que ações potencialmente destrutivas (como apagar dados) tenham uma etapa de confirmação para evitar enganos._</p>|
|**Exceção**   |
|<p>_*Dispositivo offline:* Se o dispositivo alvo não estiver conectado à Internet no momento da solicitação, o aplicativo exibirá uma mensagem de erro ou informará que a ação não pôde ser concluída imediatamente. (Possivelmente o sistema tentará novamente quando o dispositivo ficar online, mas o usuário deve ser alertado da falha inicial.)_</p> <p>_*Falha na comunicação:* Em caso de falha no envio do comando (problemas no servidor ou na rede), o aplicativo informará ao usuário que ocorreu um erro ao tentar executar a ação de segurança._</p> <p>_*Permissão não concedida:* Se por alguma razão o dispositivo alvo não tiver concedido permissões necessárias para determinada ação (por exemplo, não autorizou o aplicativo a apagar dados remotamente), a ação não será realizada e o usuário será notificado do motivo da falha._</p>|

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a> e <a href="https://github.com/zDrNz" target="_blank">Daniel Rodrigues</a></p></font>

## Cenário 3

<font size="3"><p style="text-align: center">Cenário 3: Registrar um novo aparelho</p></font>

|**Cenário 3**|
|--------------|
|**Titulo**    |
|_Registrar um novo aparelho no sistema._|
|**Objetivo**  |
|_Permitir que o usuário cadastre um novo dispositivo (celular ou tablet) em sua conta do Celular Seguro, para que possa monitorá-lo e utilizar as funcionalidades de segurança no futuro._|
|**Contexto**  |
|<p>Local: _Tela de registro de dispositivo no aplicativo Celular Seguro (acessada, por exemplo, a partir de uma opção "Adicionar novo aparelho" no menu principal ou na seção de dispositivos)._</p> <p>Tempo: _Aproximadamente 3 minutos (o processo de cadastro pode envolver preenchimento de dados e verificações)._</p> <p>Pré-condição: _O usuário estar logado em sua conta do Celular Seguro. O novo aparelho deve estar em mãos para que possa ser configurado, ou ao menos suas informações (como IMEI ou número de série) devem estar disponíveis. Idealmente, o aplicativo Celular Seguro deve estar instalado ou acessível no dispositivo a ser registrado, ou o usuário deve ter acesso à Internet para registrá-lo via portal._</p>|
|**Atores**    |
|_Usuário do aplicativo Celular Seguro._|
|**Recursos**  |
|<p>_Conexão ativa à internet._</p><p>_Smartphone (ou computador) do usuário com acesso ao aplicativo ou site do Celular Seguro para realizar o cadastro._ </p> <p>_Novo dispositivo a ser cadastrado (que poderá ser o próprio aparelho em uso ou outro aparelho distinto)._</p>|
|**Episódios** |
|<p>_O usuário seleciona a opção *"Adicionar/Registrar novo aparelho"* na interface do Celular Seguro._</p> <p>_O aplicativo exibe um formulário ou um passo a passo solicitando as informações necessárias do novo dispositivo. Por exemplo, pode ser exibida a opção de identificar o aparelho automaticamente (caso o registro esteja sendo feito pelo próprio dispositivo) ou de inserir manualmente dados como *IMEI, modelo, fabricante, apelido/nome do aparelho* etc._</p> <p>_(Caso o registro seja feito no próprio aparelho a ser cadastrado: o aplicativo coleta automaticamente informações básicas do dispositivo – como modelo e IMEI – e pode pular alguns campos preenchendo-os automaticamente.)_</p> <p>_O usuário preenche quaisquer informações solicitadas que não foram automaticamente capturadas. Isso pode incluir dar um nome ao dispositivo (para fácil identificação na lista) e confirmar sua vinculação à conta atual._</p> <p>_O usuário confirma o registro submetendo o formulário de cadastro do novo aparelho._</p> <p>_O aplicativo verifica as informações fornecidas: por exemplo, checa se o IMEI inserido é válido e se já não existe outro aparelho com aquele IMEI cadastrado na conta (ou no sistema, caso cada aparelho só possa estar associado a um usuário)._</p> <p>_Estando tudo válido, o aplicativo registra o novo dispositivo no sistema, associando-o à conta do usuário._</p> <p>_O aplicativo exibe uma mensagem de sucesso confirmando que o novo aparelho foi registrado com êxito. O novo dispositivo passa a aparecer na lista de dispositivos do usuário, pronto para utilização das funções do Celular Seguro._</p>|
|**Restrição** |
|<p>_Cada usuário pode ter um número limite de dispositivos cadastrados simultaneamente (conforme as políticas do serviço Celular Seguro, se houver tal limite)._</p> <p>_Só é possível registrar dispositivos compatíveis com o serviço (por exemplo, aparelhos que suportem a instalação do app Celular Seguro ou algum tipo de configuração remota). O sistema deve validar a compatibilidade durante o registro._</p> <p>_Informações obrigatórias (como código IMEI ou número de série, se exigidas) devem ser fornecidas corretamente; caso contrário, o registro não será concluído._</p>|
|**Exceção**   |
|<p>_*Dispositivo já cadastrado:* Se o IMEI ou identificador do aparelho que o usuário está tentando registrar já estiver vinculado a outra conta (por exemplo, caso o aparelho tenha sido de outra pessoa ou já esteja registrado como perdido/roubado no sistema), o aplicativo deverá notificar que não é possível registrar esse dispositivo, possivelmente instruindo o usuário a entrar em contato com o suporte._</p> <p>_*Dados inválidos:* Se o usuário inserir algum dado incorreto ou inválido (por exemplo, um IMEI com formato errado), o sistema exibirá uma mensagem de erro solicitando a correção da informação antes de prosseguir._</p> <p>_*Falha de conexão:* Se durante o processo de registro a conexão for perdida, o aplicativo exibirá uma notificação de erro e poderá salvar temporariamente os dados inseridos para que o usuário tente enviar novamente quando a conexão retornar, em vez de reiniciar todo o processo._</p> <p>_*Cancelamento pelo usuário:* O usuário pode desistir do cadastro a qualquer momento antes de concluir. Nesse caso, nenhuma alteração é feita e o novo aparelho não é adicionado._</p>|

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a> e <a href="https://github.com/zDrNz" target="_blank">Daniel Rodrigues</a></p></font>

## Cenário 4

<font size="3"><p style="text-align: center">Cenário 4: Visualizar ocorrências em um mapa</p></font>

|**Cenário 4**|
|--------------|
|**Titulo**    |
|_Visualizar ocorrências de segurança em um mapa interativo._|
|**Objetivo**  |
|_Permitir que o usuário visualize, em um mapa geográfico, as ocorrências registradas relacionadas aos dispositivos e à segurança, como por exemplo a localização atual ou última localização conhecida de seus aparelhos e/ou pontos de incidência de roubos/furtos reportados._|
|**Contexto**  |
|<p>Local: _Tela de mapa dentro do aplicativo Celular Seguro, acessada possivelmente através de uma opção como "Mapa de Ocorrências" ou a partir dos detalhes de um dispositivo (ex.: opção de ver no mapa)._</p> <p>Tempo: _Indeterminado (o usuário pode navegar pelo mapa livremente; a ação inicial de carregamento dura alguns segundos)._</p> <p>Pré-condição: _Existirem ocorrências relevantes registradas no sistema para serem exibidas no mapa. Por exemplo, o usuário ter pelo menos um dispositivo marcado como perdido/roubado com localização conhecida, ou haver dados agregados de locais com incidência de roubos disponíveis no app. O dispositivo do usuário (que está executando o app) deve ter acesso à Internet para carregar o mapa e os dados._</p>|
|**Atores**    |
|_Usuário do aplicativo Celular Seguro._|
|**Recursos**  |
|<p>_Conexão ativa à internet._</p><p>_Smartphone com o aplicativo Celular Seguro (com permissão para usar serviços de mapa e possivelmente localização, caso queira mostrar a posição atual do usuário no mapa)._ </p> |
|**Episódios** |
|<p>_O usuário acessa a funcionalidade de mapa no aplicativo Celular Seguro (por exemplo, selecionando *"Visualizar ocorrências no mapa"* no menu principal ou em seção específica)._</p> <p>_O aplicativo obtém os dados necessários das ocorrências para plotagem. Isso pode incluir a posição atual/última conhecida dos dispositivos do próprio usuário (se marcados como perdidos) e/ou dados de locais onde houve ocorrências de roubo/furto de celulares reportadas por outros usuários ou autoridades._</p> <p>_O aplicativo exibe um mapa interativo na tela. No mapa, são exibidos *marcadores (pins)* indicando a localização das ocorrências relevantes: por exemplo, um ícone especial indicando o último local conhecido de um dispositivo perdido do usuário, e outros ícones indicando regiões com registros de ocorrências de roubo/furto._</p> <p>_O usuário pode interagir com o mapa realizando zoom e pan (arrastar), explorando diferentes áreas. Ao tocar em um marcador específico, o aplicativo exibe detalhes adicionais daquela ocorrência. Por exemplo: ao tocar no ícone do seu dispositivo perdido, o usuário vê informações como data/hora da última localização conhecida; ao tocar em um marcador genérico de ocorrência de roubo, pode ver informações estatísticas como “X ocorrências reportadas nesta região na última semana”._</p> <p>_O usuário utiliza as informações do mapa para auxiliar em sua tomada de decisão – por exemplo, verificar se seu celular perdido está em um local acessível ou se determinada área tem alto índice de roubos (para então ter mais cautela)._</p>|
|**Restrição** |
|<p>_As ocorrências exibidas podem ser filtradas por período ou tipo conforme configuração do sistema; o mapa deve evitar sobrecarga mostrando apenas informações relevantes ou dentro de uma área de interesse do usuário._</p> <p>_Questões de privacidade: ao exibir ocorrências em mapa, nenhuma informação pessoal de outros usuários deve ser revelada. Por exemplo, se há dados agregados de roubos de terceiros, eles devem ser anônimos e agregados, respeitando a privacidade e a LGPD._</p> <p>_O aplicativo deve usar uma API de mapas confiável e atualizada para renderizar o mapa e os pontos. Deve também contar com design responsivo, garantindo que todos os marcadores e detalhes sejam visíveis e acessíveis em diferentes tamanhos de tela._</p>|
|**Exceção**   |
|<p>_*Sem dados para exibir:* Caso não haja nenhuma ocorrência registrada (nem localização de dispositivo perdido do usuário nem dados públicos de roubos) dentro do escopo do mapa, o aplicativo exibirá o mapa vazio ou com uma mensagem do tipo "Nenhuma ocorrência disponível para exibir no momento"._</p> <p>_*Falha de GPS/Localização:* Se a funcionalidade exigir a localização atual do usuário (por exemplo, para centralizar o mapa próximo a ele) e esta não estiver disponível ou permitida, o mapa ainda será exibido mas possivelmente centralizado em uma região padrão (como um mapa do país), e o aplicativo pode alertar que não foi possível determinar a localização atual._</p> <p>_*Problemas de conexão ou carregamento:* Se a conexão cair durante o carregamento do mapa ou dos dados de ocorrências, o aplicativo mostrará uma mensagem de erro e poderá oferecer uma opção de tentar novamente. O mapa pode exibir apenas as partes que já foram carregadas ou ficar em branco até que haja conexão._</p>|

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a> e <a href="https://github.com/zDrNz" target="_blank">Daniel Rodrigues</a></p></font>

## Cenário 5

<font size="3"><p style="text-align: center">Cenário 5: Bloquear remotamente um dispositivo</p></font>

|**Cenário 5**|
|--------------|
|**Titulo**    |
|_Bloquear remotamente um dispositivo cadastrado._|
|**Objetivo**  |
|_Permitir que o usuário bloqueie seu aparelho à distância, tornando-o inutilizável por terceiros, em situações de perda ou roubo, a fim de proteger dados e impedir uso indevido._|
|**Contexto**  |
|<p>Local: _Aplicativo Celular Seguro executado em um dispositivo alternativo (por exemplo, no computador via web ou em outro smartphone), uma vez que o dispositivo alvo está perdido/roubado; ou, alternativamente, na própria interface do app caso o usuário esteja antecipadamente testando a função de bloqueio._</p> <p>Tempo: _Aproximadamente 1 minuto (ação imediata após perceber o roubo/perda)._</p> <p>Pré-condição: _O usuário estar autenticado em sua conta do Celular Seguro em algum dispositivo ou plataforma (web) alternativa. O aparelho a ser bloqueado deve estar previamente cadastrado na conta e, idealmente, *marcado como perdido/roubado* no sistema. O dispositivo alvo também precisa estar ligado e conectado à Internet ou à rede móvel para receber o comando de bloqueio em tempo real._</p>|
|**Atores**    |
|_Usuário do aplicativo Celular Seguro._|
|**Recursos**  |
|<p>_Conexão ativa à Internet no dispositivo utilizado para enviar o comando (e preferencialmente no dispositivo alvo para recebê-lo)._</p><p>_Acesso ao aplicativo Celular Seguro (ou site) em um dispositivo alternativo do usuário ou de apoio (como o celular de um amigo ou um computador)._ </p> |
|**Episódios** |
|<p>_O usuário, ao notar que seu celular principal foi perdido ou roubado, acessa o Celular Seguro através de outro meio (por exemplo, entra no site do Celular Seguro em um computador ou usa o aplicativo no celular de um familiar)._</p> <p>_O usuário faz login em sua conta do Celular Seguro, garantindo acesso à lista de dispositivos registrados em sua conta._</p> <p>_Na interface, o usuário localiza e seleciona o dispositivo correspondente ao aparelho perdido/roubado que deseja bloquear remotamente._</p> <p>_O aplicativo exibe as opções de segurança disponíveis para aquele dispositivo. O usuário então clica/seleciona a opção *"Bloqueio Remoto do Dispositivo"* (possivelmente apresentada como um botão destacado, dado que é uma função crucial em caso de roubo)._</p> <p>_O aplicativo solicita uma confirmação extra do usuário, considerando que essa ação irá bloquear o aparelho e possivelmente requer permissões elevadas. (Por exemplo, pode pedir que o usuário confirme a senha da conta ou responda "Tem certeza que deseja bloquear o dispositivo agora?")_</p> <p>_O usuário confirma a solicitação de bloqueio remoto._</p> <p>_O sistema Celular Seguro envia imediatamente um comando de bloqueio para o dispositivo alvo através da rede (internet ou SMS, dependendo da tecnologia disponível para alcançar o aparelho)._</p> <p>_*Caso o dispositivo alvo esteja online e acessível:* ele recebe o comando e executa o bloqueio – a tela do aparelho é imediatamente travada, possivelmente exibindo uma mensagem informando que o dispositivo foi bloqueado remotamente. Se definido, pode também acionar outras medidas (por exemplo, exigir senha para desbloquear, ou tornar inúteis cartões SIM)._</p> <p>_O aplicativo confirma ao usuário que o comando de bloqueio foi enviado com sucesso. Se houver retorno do dispositivo confirmando o bloqueio, o aplicativo notifica que o aparelho foi bloqueado._</p> <p>_*Caso o dispositivo alvo esteja offline no momento:* o sistema poderá continuar tentando enviar o comando por um período ou assim que o aparelho se conectar (dependendo das capacidades do serviço). O usuário é avisado de que o bloqueio será efetuado assim que o dispositivo estiver online, ou orientado a tentar novamente mais tarde._</p>|
|**Restrição** |
|<p>_Por segurança, a funcionalidade de bloqueio remoto pode exigir que o usuário tenha configurado previamente essa capacidade no dispositivo (por exemplo, o app Celular Seguro instalado com privilégios de administrador do dispositivo ou algo similar). Se não, o bloqueio talvez não seja possível._</p> <p>_O bloqueio remoto só pode ser realizado pelo legítimo proprietário autenticado na conta; tentativas de bloqueio por terceiros não autorizados devem ser impedidas pelo sistema (por exemplo, com autenticação de dois fatores para ações críticas)._</p> <p>_O comando de bloqueio deve ser enviado de forma segura e idealmente rápida. Há dependência da infraestrutura de rede móvel/Internet e do próprio sistema operacional do dispositivo para executar o bloqueio._</p>|
|**Exceção**   |
|<p>_*Dispositivo inacessível:* Se após múltiplas tentativas o aparelho continuar inacessível (desligado ou sem conexão) e não receber o comando, o aplicativo informará ao usuário que não foi possível comunicar com o dispositivo. Nesse caso, recomenda-se ao usuário outras ações (como acionar operadora para bloqueio do SIM/IMEI)._</p> <p>_*Falha na execução:* Se o dispositivo receber o comando mas ocorrer uma falha interna e ele não realizar o bloqueio (por exemplo, erro no aplicativo do dispositivo), o sistema não terá confirmação de sucesso. O usuário poderá ser notificado de que o resultado é incerto e possivelmente deverá tentar novamente ou tomar outras providências._</p> <p>_*Erro de autenticação:* Se por algum motivo a sessão do usuário não estiver válida (por exemplo, login expirado no meio do processo), a ação de bloqueio não será realizada e o usuário será redirecionado para efetuar login novamente por medida de segurança._</p>|

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a> e <a href="https://github.com/zDrNz" target="_blank">Daniel Rodrigues</a></p></font>

---

## Bibliografia

> SERRANO, Milene. *Requisitos – Aula 10*. 2017. Apresentação de slides. Disponível em: [aprender3.unb.br](https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf). Último acesso em: 14 abr. 2025.
> *ANÁLISE de Requisitos de Software da Aplicação Bilheteria Digital*, 2024. Disponível em: [requisitos-de-software.github.io](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/). Último acesso em: 14 abr. 2025.

---

## Histórico de Versões 

| Versão | Data de produção   | Descrição da Alteração                               | Autor(es)             | Revisor(es)      |Data de Revisão |
| :----: | :----------------: | :--------------------------------------------------: | :-------------------: | :-------------:  |  :-----------: |
| 1.0    | 09/05/2025         | Criação do documento                           |<a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a>    | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>| 09/05/2025|
| 1.1    | 14/05/2025         |  Desenvolvimento do documento  | <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a>, <a style="color:gold;" href="https://github.com/Bessazs" target="_blank">Daniel Rodrigues</a> | <a style="color:gold;" href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a> |    14/05/2025   |