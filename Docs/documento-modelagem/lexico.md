# Léxicos  
---

## Introdução

A construção do léxico, denominado *Language Extended Lexicon* (LEL), é um componente central na estratégia de aquisição de conhecimento proposta. O LEL é uma estrutura que visa descrever o vocabulário específico de uma aplicação, permitindo que tanto usuários quanto engenheiros de software compreendam a linguagem do problema sem a necessidade de entender completamente o problema em si.

---

## Estrutura do LEL

O LEL é definido por um conjunto de postulados que organizam suas entradas. Cada entrada no léxico é composta por:

- **Título**: Representa um sinal ou termo da linguagem da aplicação.  
- **Noções**: Incluem definições e significados associados ao título.  
- **Respostas Comportamentais**: Descrevem as ações ou reações esperadas relacionadas ao título.

A estrutura do LEL é projetada para ser auto-contida, minimizando a dependência de vocabulários externos e formando um grafo interconectado que representa as relações entre os termos.

---

## Aquisição e Validação do Léxico

A aquisição do léxico é realizada através de um processo que utiliza dicionários e heurísticas para identificar e validar os sinais e seus significados. A validação do léxico ocorreu da seguinte maneira:

- **Verificação Informal**: Envolvendo a leitura e comentários de atores do domínio de aplicação (UofD).

---

## Léxico de Verbos

| **Título**        | **Noções**                                                                 | **Respostas Comportamentais**                                                                 |
|-------------------|----------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| Localizar         | Ato de determinar a localização atual do dispositivo                       | O sistema obtém e exibe a localização do celular em tempo real através do mapa               |
| Bloquear          | Impedir o uso do dispositivo remotamente                                   | O sistema realiza bloqueio do aparelho após comando remoto ou agendamento                    |
| Autenticar        | Verificar a identidade do usuário                                           | O sistema solicita login seguro através do gov.br                                            |
| Solicitar         | Requisitar autorização de uso ou permissões                                | O sistema solicita permissão para acessar localização, câmera ou dados do dispositivo        |
| Enviar            | Transmitir informações para outro sistema ou servidor                      | O sistema envia a localização ou dados de status para o portal web                           |
| Emitir            | Gerar e disponibilizar mensagens ou documentos                             | O sistema emite notificações ou boletins de ocorrência                                       |
| Recuperar         | Obter dados previamente armazenados                                         | O sistema recupera backups de contatos, fotos ou documentos                                  |
| Compartilhar      | Tornar temporariamente acessível a localização ou informações              | O usuário compartilha sua localização com contatos confiáveis                                |
| Notificar         | Informar o usuário sobre eventos importantes                               | O sistema envia notificações sobre tentativas de acesso, troca de chip ou localização        |
| Gravar            | Registrar ações em logs para futura auditoria                              | O sistema armazena ações de acesso e comandos remotos em arquivos de log                     |

---

## Léxico de Objetos

| **Título**            | **Noções**                                                                 | **Respostas Comportamentais**                                                                |
|------------------------|----------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| Celular               | Dispositivo móvel do usuário                                               | Pode ser rastreado, bloqueado, apagado ou receber comandos remotos                           |
| Localização           | Informação de posição geográfica do celular                               | Utilizada para rastreamento em tempo real ou histórico de movimentos                         |
| Conta do usuário      | Perfil vinculado ao sistema gov.br                                         | Utilizada para autenticação e associação de ações remotas                                    |
| Backup                | Cópia de segurança dos dados do dispositivo                               | Recuperável após bloqueio, apagamento ou substituição do celular                             |
| Notificação           | Alerta enviado ao usuário                                                  | Indica eventos críticos como tentativa de desbloqueio, troca de chip ou rastreamento         |
| Contato de segurança  | Pessoa previamente cadastrada para emergências                            | Recebe localização ou alertas em caso de perda/roubo                                         |
| Portal web            | Plataforma online vinculada ao aplicativo                                 | Permite gerenciamento remoto do dispositivo                                                  |
| Comando remoto        | Instrução enviada para controle à distância                               | Pode ativar alarme, bloqueio, apagar dados, entre outros                                     |
| Chip (SIM Card)       | Componente de rede do celular                                              | Monitorado para detecção de troca não autorizada                                             |
| Log de ações          | Registro das atividades realizadas pelo sistema                           | Armazena eventos para auditoria e segurança                                                  |

---

## Léxico de Estados

| **Título**                 | **Noções**                                                                 | **Respostas Comportamentais**                                                                  |
|----------------------------|----------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
| Aplicativo instalado       | O app está presente no dispositivo                                        | Permite o início das funcionalidades, após configurações iniciais                              |
| Usuário autenticado        | Usuário realizou login com sucesso no gov.br                             | Sistema libera acesso às funcionalidades de rastreamento e bloqueio                           |
| Permissão concedida        | Sistema obteve autorização para acessar funcionalidades sensíveis         | Permite uso de localização, câmera, leitura de dados                                            |
| Modo perdido ativado       | Dispositivo entrou em estado de segurança                                 | Ativa automaticamente rastreamento, alarme, bloqueio e envio de localização                    |
| Dispositivo bloqueado      | Celular encontra-se inutilizável por ação remota                          | A tela permanece travada, impedindo o uso não autorizado                                        |
| Backup ativo               | Cópias de segurança estão sendo armazenadas                               | Dados são salvos periodicamente ou antes de ações como bloqueio                                |
| Notificação pendente       | Há eventos relevantes não visualizados pelo usuário                       | Sistema envia novamente alertas ou reforça com notificações persistentes                       |
| Tentativa de acesso detectada | Ocorreu uma tentativa de acessar o dispositivo                          | Sistema registra e notifica o evento ao usuário e contatos confiáveis                          |
| Chip alterado              | Foi detectada troca de cartão SIM                                          | Sistema emite alerta e atualiza o status de segurança                                           |
| Sincronizado com o portal  | App e portal web compartilham os mesmos dados                             | Ações realizadas no portal refletem no app e vice-versa                                        |

---

## Bibliografia

> SERRANO, Milene. Requisitos – Aula 10. Apresentação de slides. Disponível em: https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf. Acesso em: 14/05/2023.

> Silva, Lyrene. Tese de Doutorado: Uma Estratégia Orientada a Aspectos para Modelagem de Requisitos. Disponível em: <https://www-di.inf.puc-rio.br/~julio/lyrene-tese.pdf>. Acesso em: 14 maio. 2025b.

---

## Histórico de Versões 

| Versão | Data de produção   | Descrição da Alteração                               | Autor(es)             | Revisor(es)      |Data de Revisão |
| :----: | :----------------: | :--------------------------------------------------: | :-------------------: | :-------------:  |  :-----------: |
| 1.0    | 09/05/2025         | Criação do documento                           |<a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a>    | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>| 09/05/2025|
| 1.1 | 14/05/2025 | Desenvolvimento do Tópico | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | 14/05/25 |