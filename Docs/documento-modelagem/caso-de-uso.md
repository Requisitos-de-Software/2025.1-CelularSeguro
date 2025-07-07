<span style="background-color:#2c2c7c; color:white; font-size:0.8em; font-weight: bold; padding:2px 6px; border-radius:4px;">Versão 2.0</span>

# Casos de Uso

---

## Introdução
Um caso de uso é uma descrição detalhada de como um sistema será utilizado por seus usuários em um determinado contexto ou situação. Ele descreve as interações entre os atores (usuários ou sistemas externos) e o sistema, especificando os passos necessários para atingir um objetivo específico. Cada caso de uso foca em uma funcionalidade ou tarefa que o sistema deve realizar, detalhando as ações dos usuários e as respostas esperadas do sistema. Este tipo de modelagem é essencial no desenvolvimento de software, pois ajuda a mapear os requisitos funcionais, garantindo que o sistema atenda às necessidades dos usuários finais [2].

Além disso, os casos de uso permitem uma visão clara das funcionalidades do sistema, oferecendo uma maneira estruturada de documentar o comportamento esperado do sistema durante a interação com o usuário. Eles servem como base para o desenvolvimento do sistema, auxiliando na análise e design, e são usados para validar os requisitos e guiar a implementação.

!!! Warning "Atenção!"
    O conteúdo deste tópico **poderá sofrer alterações** ao longo da Disciplina de Requisitos de Software. Portanto, as tabelas serão organizadas iniciando pela versão mais recente e finalizando com a versão mais antiga.

---

## Integrantes que atuaram no desenvolvimento do artefato

Esta tabela inicial terá somente os artefatos de alta relevância que cada integrante do projeto desenvolveu. O versionamento **completo** encontra-se ao final do artefato.

<font size="3"><p style="text-align: center">_Desenvolvimento do Artefato_</p></font>

| Nome | Função |
| :--- | :--- |
| [<span style="color:gold;">Leonardo de Melo</span>](https://github.com/leozinlima) | Responsável por desenvolver o artefato e: [[ Elementos do Diagrama de Caso de Uso ]](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#elementos-do-diagrama-de-caso-de-uso) e [[ Especialização dos casos de uso ]](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#emitir-alerta-de-roubo)|
| [<span style="color:gold;">Mateus Bastos</span>](https://github.com/MateuSansete) | Responsável por desenvolver : [[ Introdução ]](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#introducao) e [[ Metodologia ]](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#metodologia)|
| [<span style="color:gold;">Vitor Bessa</span>](https://github.com/Bessazs) | Responsável por desenvolver : [[ Diagrama de Casos de Uso]](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/caso-de-uso/#diagrama-de-casos-de-uso)|
| [<span style="color:gold;">Felipe das Neves</span>](https://github.com/FelipeFreire-gf) | Revisor do Artefato |

*Legenda:* 

**Nome** – participante da técnica. 

**Função** – papel desempenhado na priorização.

!!! Tip "Observação"
    Frizando claramente que as contribuições de cada integrante ainda que mínimas são ainda sim muito relevantes no desenvolvimento do artefo, considere verificar o histórico de versão. 

---

## Metodologia

Para representar as interações entre os usuários e o sistema Celular Seguro.gov, foi utilizada a técnica de modelagem UML por meio de diagramas de caso de uso. Essa abordagem permite descrever o comportamento esperado do sistema, sem especificar a ordem em que as ações ocorrem. [[ 1 ]](#ref1).

O diagrama de caso de uso mostra graficamente como diferentes atores (usuários, sistemas externos ou organizações) interagem com os casos de uso, que representam processos ou funcionalidades relevantes para o sistema. Cada ator pode representar um papel específico e pode participar de múltiplos casos de uso. Uma associação entre ator e caso de uso indica sua participação ativa no processo descrito.

A definição do limite do sistema também é uma etapa fundamental, pois determina o que é considerado interno ou externo à aplicação modelada. Dentro desses limites, os casos de uso representam conjuntos significativos de eventos que ocorrem quando o ator utiliza o sistema para atingir um objetivo, como registrar um celular, bloquear o aparelho, ou acompanhar o andamento de uma solicitação.

Essa modelagem foi baseada em cenários realistas e generalizados de uso, permitindo compreender as principais funcionalidades esperadas da aplicação e facilitando a validação e a comunicação entre os membros da equipe de desenvolvimento.

---

## Elementos do Diagrama de Caso de Uso

<font size="3">
  <p style="text-align:center; margin:-2em 0 0; line-height:1.2;">
    Tabela 1: Elementos do Diagrama de Caso de Uso<br>
    <span style="font-size:0.85em; font-style:italic;">
      Legenda dos elementos utilizados em diagramas de caso de uso, com seus símbolos correspondentes.
    </span>
  </p>
</font>

| Componente | Propósito | Ícone
|------|------|:-------:
| Atuador | Representa qualquer pessoa ou sistema externo que interage com o software. | <figure class="usecaseElement" style="width: 20%; display: flex;">![actor](../assets/usecase/actor.png)</figure>
| Elipse (Função) | Denota uma ação ou serviço que o sistema oferece em resposta a solicitações dos atuadores; o nome da funcionalidade fica dentro da elipse. | <figure class="usecaseElement" style="width: 40%; display: flex;">![elipse](../assets/usecase/elipse.png)</figure>
| Contorno (Limite do Sistema) | Define o perímetro do sistema sob análise, envolvendo todos os casos de uso e atuadores externos relacionados. | <figure class="usecaseElement" style="width: 40%; display: flex;">![retangulo](../assets/usecase/retangulo.png)</figure>
| Conector (Relações) | Mostra as ligações entre atuadores e casos de uso, indicando quem participa de cada função ou como casos de uso se relacionam entre si. | <figure class="usecaseElement" style="width: 40%; display: flex;">![flechas](../assets/usecase/flecha.png)</figure>

**Autor do tabela 1:** <a  href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>, <a href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>, <a  href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a>

No diagrama de caso de uso, também é possível detalhar:

- Requisitos externos: funcionalidades que o sistema deve oferecer para atender demandas de usuários ou outros sistemas.  
- Capacidades do sistema: ações internamente disponíveis que permitem satisfazer essas demandas.  
- Restrições de ambiente: condições ou interfaces que o sistema exige do contexto onde opera para cumprir suas funções.

---

## Diagrama de Casos de Uso

<font size="3">
  <p style="text-align:center; margin:-2em 0 0; line-height:1.2;">
    Figura 1 – Diagrama de Caso de Uso do Celular Seguro<br>
    <span style="font-size:0.85em; font-style:italic;">
      Visão geral dos casos de uso do sistema Celular Seguro, destacando o ator principal, os casos de uso essenciais (emitir alerta de roubo, registrar boletim, localizar celular, bloqueio remoto e backup de dados por e-mail) e as relações de inclusão («include») e extensão («extend») que conectam funcionalidades auxiliares.
    </span>
  </p>
</font>

![Diagrama de Caso de Uso – Celular Seguro](../assets/usecase/UseCaseDiagram1.svg)

**Autor da figura 1:** <a  href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>, <a  href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>, <a  href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a>

---

## Especialização dos casos de uso

##  Emitir alerta de roubo

<font size="3">
  <p style="text-align:center; margin:-2em 0 0; line-height:1.2;">
    Tabela 2: Caso de Uso UC01 – Emitir Alerta de Roubo<br>
    <span style="font-size:0.85em; font-style:italic;">
      Detalhamento do caso de uso UC01 para emissão de alerta de roubo, especificando fluxos principal, alternativo e de exceção.
    </span>
  </p>
</font>

| UC01                  | Informações                                                                                                 |
|:----------------------|:------------------------------------------------------------------------------------------------------------|
| **Descrição**         | O usuário é capaz de emitir um alerta imediato de roubo do dispositivo.                                     |
| **Ator**              | Usuário                                                                                                     |
| **Pré-condições**     | Usuário autenticado; dispositivo previamente registrado no sistema.                                         |
| **Ação**              | O usuário emite um alerta de roubo via aplicativo.                                                          |
| **Fluxo principal**   | 1. O usuário acessa o app.<br>2. Seleciona “Emitir Alerta de Roubo”.<br>3. Sistema exibe popup de confirmação.<br>4. Usuário confirma.<br>5. Sistema registra alerta, aciona “Registrar Boletim” e “Notificar Autoridades”. |
| **Fluxo alternativo** | 1. O usuário cancela no popup de confirmação.<br>2. Sistema retorna ao painel.  <br>3. Usuário perde a conexão de dados antes de confirmar; sistema salva alerta em modo offline e sincroniza ao reconectar.                           |
| **Fluxo de exceção**  | 1. Falha na notificação às autoridades.<br>2. Sistema exibe mensagem de erro e registra falha.<br>3. Erro de banco de dados ao registrar o alerta; sistema exibe mensagem “Erro interno, tente novamente” e enfileira o alerta para nova tentativa.             |
| **Pós-condições**     | Alerta de roubo registrado; boletim iniciado; autoridades notificadas.                                      |
| **Data de Criação**   | 13/05/2025                                                                                                  |
| **Rastreabilidade**   | [OBS09](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Observacao/#tabela-de-requisitos-funcionais)                                                                                       |

**Autor do tabela 2:** <a  href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>, <a  href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>, <a  href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a>

----

##  Registrar Boletim

<font size="3">
  <p style="text-align:center; margin:-2em 0 0; line-height:1.2;">
    Tabela 3: Caso de Uso UC02 – Registrar Boletim<br>
    <span style="font-size:0.85em; font-style:italic;">
      Detalhamento do caso de uso UC02 para registro formal de boletim de ocorrência detalhando o roubo.
    </span>
  </p>
</font>

| UC02                 | Informações                                                                                 |
|:---------------------|:--------------------------------------------------------------------------------------------|
| **Descrição**        | O usuário registra formalmente um boletim de ocorrência detalhando o roubo.                 |
| **Ator**             | Usuário                                                                                     |
| **Pré-condições**    | Usuário autenticado com login gov.br; dispositivo com conexão ativa.                        |
| **Ação**             | O usuário preenche o formulário e envia o boletim.                                          |
| **Fluxo principal**  | 1. Usuário seleciona “Registrar Boletim”.<br>2. Sistema exibe formulário.<br>3. Usuário preenche os campos e envia.<br>4. Sistema valida e exibe protocolo. |
| **Fluxo alternativo**| 1. Usuário tenta enviar sem preencher todos os campos.<br>2. Sistema bloqueia envio e exibe aviso.<br>3.Usuário preenche formulário e sai da tela; ao retornar, sistema exibe dados salvos em rascunho. |
| **Fluxo de exceção** | 1. Erro no servidor ao registrar.<br>2. Sistema exibe mensagem de falha.<br>3. Timeout na validação de captcha; sistema solicita recarregar o captcha e reenviar.                    |
| **Pós-condições**     | Boletim registrado com número de protocolo.                                                 |
| **Data de Criação**   | 13/05/2025                                                                                 |
| **Rastreabilidade**   | [QS02](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#requisitos-elicitados), [QS09](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#requisitos-elicitados), [OBS8](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Observacao/#tabela-de-requisitos-funcionais)                                                                                |

**Autor do tabela 3:** <a  href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>, <a  href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>, <a  href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a>

---

##  Localizar Celular

<font size="3">
  <p style="text-align:center; margin:-2em 0 0; line-height:1.2;">
    Tabela 4: Caso de Uso UC03 – Localizar Celular<br>
    <span style="font-size:0.85em; font-style:italic;">
      Detalhamento do caso de uso UC03 para localizar a posição atual ou última conhecida do dispositivo.
    </span>
  </p>
</font>

| UC03                 | Informações                                                                                     |
|:---------------------|:------------------------------------------------------------------------------------------------|
| **Descrição**        | Permite ao usuário localizar a posição atual ou última conhecida do dispositivo.                |
| **Ator**             | Usuário                                                                                          |
| **Pré-condições**    | Boletim registrado; dispositivo com rastreamento ativado e online.                              |
| **Ação**             | O usuário solicita a localização do aparelho.                                                    |
| **Fluxo principal**  | 1. Usuário acessa “Localizar Celular”.<br>2. Sistema verifica pré-condições.<br>3. Solicita coordenadas ao provedor.<br>4. Exibe mapa com marcador da localização. |
| **Fluxo alternativo**| 1. Dispositivo offline.<br>2. Sistema exibe última localização conhecida.<br>3. Provedor de localização retorna coordenadas imprecisas; sistema solicita ao usuário escolher entre “usar dados aproximados” ou “tentar novamente”.                       |
| **Fluxo de exceção** | 1. Erro na API de localização.<br>2. Sistema exibe mensagem de indisponibilidade.<br>3. Falha de autenticação junto ao provedor externo; sistema exibe “Sessão expirada, faça login novamente” e interrompe o caso de uso.               |
| **Pós-condições**    | Localização exibida no mapa ou mensagem de erro apresentada.                                     |
| **Data de Criação**  | 13/05/2025                                                                                       |
| **Rastreabilidade**  | [BS04](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais), [QS01](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#requisitos-elicitados), [ST6](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Storytelling/#tabela-de-requisitos-funcionais)|

**Autor do tabela 4:** <a  href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>, <a  href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>, <a  href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a>

---

##  Bloqueio Remoto do Aparelho

<font size="3">
  <p style="text-align:center; margin:-2em 0 0; line-height:1.2;">
    Tabela 5: Caso de Uso UC04 – Bloqueio Remoto do Aparelho<br>
    <span style="font-size:0.85em; font-style:italic;">
      Detalhamento do caso de uso UC04 para bloqueio remoto do aparelho, especificando fluxos principal, alternativo e de exceção.
    </span>
  </p>
</font>

| UC04                 | Informações                                                                                   |
|:---------------------|:----------------------------------------------------------------------------------------------|
| **Descrição**        | O usuário bloqueia o aparelho remotamente para impedir seu uso.                                |
| **Ator**             | Usuário                                                                                        |
| **Pré-condições**    | Boletim registrado; dispositivo localizado anteriormente.                                      |
| **Ação**             | O usuário envia comando de bloqueio remoto.                                                   |
| **Fluxo principal**  | 1. Usuário acessa “Bloqueio Remoto”.<br>2. Sistema solicita confirmação.<br>3. Usuário confirma.<br>4. Sistema envia comando à operadora e registra ação. |
| **Fluxo alternativo**| 1. Usuário cancela confirmação.<br>2. Sistema retorna ao painel.<br>3. Operadora não responde imediatamente; sistema avisa “Bloqueio em andamento” e permite ao usuário consultar status posteriormente.                               |
| **Fluxo de exceção** | 1. Falha na comunicação com operadora.<br>2. Sistema exibe mensagem de erro.<br>3. Token de autorização inválido; sistema solicita nova autenticação do usuário antes de reenviar o comando.                  |
| **Pós-condições**    | Dispositivo bloqueado ou falha registrada.                                                    |
| **Data de Criação**  | 13/05/2025                                                                                    |
| **Rastreabilidade**  | [BS15](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais)                                                                                   |

**Autor do tabela 5:** <a  href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>, <a  href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>, <a  href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a>

---

##  Backup de Dados via Email

<font size="3">
  <p style="text-align:center; margin:-2em 0 0; line-height:1.2;">
    Tabela 6: Caso de Uso UC05 – Backup de Dados via Email<br>
    <span style="font-size:0.85em; font-style:italic;">
      Detalhamento do caso de uso UC05 para envio de backup de dados por email com link seguro.
    </span>
  </p>
</font>

| UC05                 | Informações                                                                                   |
|:---------------------|:----------------------------------------------------------------------------------------------|
| **Descrição**        | O usuário solicita envio de backup de dados por email com link seguro.                         |
| **Ator**             | Usuário                                                                                       |
| **Pré-condições**    | Usuário autenticado; backup disponível.                                                       |
| **Ação**             | O usuário seleciona um backup e envia por email.                                              |
| **Fluxo principal**  | 1. Usuário acessa “Backup de Dados”.<br>2. Sistema mostra backups disponíveis.<br>3. Usuário seleciona e clica em “Enviar”.<br>4. Sistema envia email com link seguro. |
| **Fluxo alternativo**| 1. Email inválido ou não cadastrado.<br>2. Sistema exibe aviso para atualização do cadastro.<br>3. Usuário seleciona múltiplos backups em sequência; sistema enfileira cada envio e exibe confirmação para cada um.  |
| **Fluxo de exceção** | 1. Erro no envio do email.<br>2. Sistema exibe falha e orienta nova tentativa.<br>3. Servidor de email retorna resposta “quota excedida”; sistema sugere ao usuário limpar backups antigos e tentar novamente.                |
| **Pós-condições**    | Email enviado com sucesso ou falha registrada.                                                |
| **Data de Criação**  | 13/05/2025                                                                                    |
| **Rastreabilidade**  | [BS18](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais)                                                                                    |

**Autor do tabela 6:** <a  href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>, <a  href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>, <a  href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a>

---

##  Gerar Relatório de Movimentação em PDF

<font size="3">
  <p style="text-align:center; margin:-2em 0 0; line-height:1.2;">
    Tabela 7: Caso de Uso UC06 – Gerar Relatório de Movimentação em PDF<br>
    <span style="font-size:0.85em; font-style:italic;">
      Detalhamento do caso de uso UC06 para geração de relatório de movimentação e download em PDF.
    </span>
  </p>
</font>

| UC06                 | Informações                                                                                                                        |
|:---------------------|:-----------------------------------------------------------------------------------------------------------------------------------|
| **Descrição**        | Permite ao usuário gerar um relatório de movimentação de dados e fazer o download em formato PDF.                                 |
| **Ator**             | Usuário                                                                                                                            |
| **Pré-condições**    | Usuário autenticado; existem registros de movimentação disponíveis no sistema.                                                     |
| **Ação**             | O usuário seleciona o período ou filtros e solicita a geração do relatório.                                                        |
| **Fluxo principal**  | 1. Usuário acessa “Relatórios” no menu.<br>2. Seleciona “Movimentação”.<br>3. Define intervalo de datas e filtros.<br>4. Clica em “Gerar PDF”.<br>5. Sistema valida parâmetros, compila os dados e disponibiliza link de download.<br>6. Usuário faz o download do arquivo PDF. |
| **Fluxo alternativo**| 1. Parâmetros inválidos (datas invertidas ou filtros inconsistentes).<br>2. Sistema exibe aviso “Verifique os filtros e tente novamente”.<br>3. Usuário cancela geração após selecionar filtros; sistema retorna ao formulário de filtros sem gerar PDF. |
| **Fluxo de exceção** | 1. Erro durante a compilação do relatório ou geração do PDF.<br>2. Sistema exibe “Falha ao gerar relatório, tente mais tarde”.<br>3. Falha de permissão de leitura em um dos bancos de dados; sistema exibe “Dados indisponíveis” e gera relatório parcial.     |
| **Pós-condições**    | Arquivo PDF com relatório de movimentação disponível para download ou mensagem de erro apresentada.                                |
| **Data de Criação**  | 15/05/2025                                                                                                                         |
| **Rastreabilidade**  | [BS22](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais)                                                                                                                               |

**Autor do tabela 7:** <a  href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>, <a  href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>, <a  href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a>

---

##  Definir Dispositivo de Confiança

<font size="3">
  <p style="text-align:center; margin:-2em 0 0; line-height:1.2;">
    Tabela 8: Caso de Uso UC07 – Definir Dispositivo de Confiança<br>
    <span style="font-size:0.85em; font-style:italic;">
      Detalhamento do caso de uso UC07 para cadastrar um dispositivo autorizado como secundário para controle remoto.
    </span>
  </p>
</font>

| UC07                  | Informações                                                                                                                                          |
|:----------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Descrição**         | Permite ao usuário registrar um “dispositivo de confiança” que possa receber comandos remotos secundários.                                            |
| **Ator**              | Usuário                                                                                                                                              |
| **Pré-condições**     | Usuário autenticado; dispositivo principal ativo e sincronizado com o sistema.                                                                       |
| **Ação**              | O usuário escolhe um dispositivo já registrado (ex.: tablet, outro celular) e marca como confiável para receber ordens remotas.                      |
| **Fluxo principal**   | 1. Usuário acessa “Configurações de Segurança”.<br>2. Seleciona “Dispositivos de Confiança”.<br>3. Sistema exibe lista de dispositivos vinculados.<br>4. Usuário escolhe dispositivo secundário e clica em “Definir como Confiável”.<br>5. Sistema envia código de verificação ao dispositivo secundário.<br>6. Usuário insere o código no app principal.<br>7. Sistema valida o código e marca o dispositivo como confiável. |
| **Fluxo alternativo** | 1. Dispositivo não aparece na lista (não vinculado).<br>2. Sistema exibe aviso “Vincule o dispositivo antes de defini-lo como confiável”.<br>3. Código de verificação demora a chegar; sistema oferece opção “reenviar código” após 30 segundos.               |
| **Fluxo de exceção**  | 1. Código de verificação inválido ou expirado.<br>2. Sistema exibe “Código incorreto ou expirado” e oferece opção de reenviar código.<br>3. Falha de comunicação com dispositivo secundário; sistema exibe “Não foi possível enviar código, tente novamente” e mantém sessão ativa.               |
| **Pós-condições**     | Dispositivo secundário passa a receber comandos remotos autorizados.                                                                                  |
| **Data de Criação**   | 15/05/2025                                                                                                                                            |
| **Rastreabilidade**   | [BS23](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais)                                                                                                                                                  |

**Autor do tabela 8:** <a  href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>, <a  href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>, <a  href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a>

---

## Limpeza Remota com Autenticação Forte

<font size="3">
  <p style="text-align:center; margin:-2em 0 0; line-height:1.2;">
    Tabela 9: Caso de Uso UC08 – Limpeza Remota com Autenticação Forte<br>
    <span style="font-size:0.85em; font-style:italic;">
      Detalhamento do caso de uso UC08 para execução de limpeza remota somente após verificação de identidade reforçada.
    </span>
  </p>
</font>

| UC08                 | Informações                                                                                                                                                    |
|:---------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Descrição**        | Executar limpeza completa do dispositivo de forma remota somente após autenticação de múltiplos fatores (MFA).                                                  |
| **Ator**             | Usuário                                                                                                                                                        |
| **Pré-condições**    | Boletim registrado; dispositivo localizado e online; usuário autenticado; métodos de MFA configurados (SMS, app autenticador ou biometria).                   |
| **Ação**             | O usuário solicita o comando de limpeza remota e fornece credenciais adicionais de segurança.                                                                  |
| **Fluxo principal**  | 1. Usuário acessa “Limpeza Remota” no painel.<br>2. Sistema avisa sobre necessidade de autenticação forte.<br>3. Usuário insere código MFA ou utiliza biometria.<br>4. Sistema valida MFA.<br>5. Sistema envia comando de wipe ao fornecedor do OS.<br>6. Fornecedor confirma início da limpeza.<br>7. Sistema exibe “Limpeza iniciada” e registra data/hora. |
| **Fluxo alternativo**| 1. Usuário insere credencial MFA inválida.<br>2. Sistema exibe “Código incorreto” e permite nova tentativa até X vezes.<br>3. Após X falhas, aborta operação e notifica usuário. |
| **Fluxo de exceção** | 1. Dispositivo offline ao tentar enviar comando.<br>2. Sistema armazena solicitação e notifica usuário de pendência.<br>3. Erro técnico na API de wipe.<br>4. Sistema exibe “Falha ao iniciar limpeza, tente novamente” e registra erro. |
| **Pós-condições**    | Comando de limpeza enviado ou pendente; registro de tentativa de limpeza com status de sucesso ou falha.                                                        |
| **Data de Criação**  | 15/05/2025                                                                                                                                                     |
| **Rastreabilidade**  | [BS32](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais)                                                                                                                                                           |

**Autor do tabela 9:** <a  href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>, <a  href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>, <a  href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a>

---

##  Editar Perfil via Aba

<font size="3">
  <p style="text-align:center; margin:-2em 0 0; line-height:1.2;">
    Tabela 10: Caso de Uso UC09 – Editar Perfil via Aba<br>
    <span style="font-size:0.85em; font-style:italic;">
      Detalhamento do caso de uso UC09 para edição de perfil do usuário através de uma aba dedicada no aplicativo.
    </span>
  </p>
</font>

| UC09                 | Informações                                                                                                              |
|:---------------------|:-------------------------------------------------------------------------------------------------------------------------|
| **Descrição**        | Permite ao usuário alterar seus dados pessoais (nome, foto, contato etc.) através de uma aba de perfil no aplicativo.    |
| **Ator**             | Usuário                                                                                                                  |
| **Pré-condições**    | Usuário autenticado; conexão com a internet; perfil existente no sistema.                                                 |
| **Ação**             | O usuário acessa a aba “Meu Perfil” e atualiza as informações desejadas.                                                  |
| **Fluxo principal**  | 1. Usuário abre o menu e seleciona “Meu Perfil”.<br>2. Sistema exibe formulário com os dados atuais.<br>3. Usuário edita campos e clica em “Salvar”.<br>4. Sistema valida entradas e atualiza o perfil.<br>5. Sistema confirma “Perfil atualizado com sucesso”. |
| **Fluxo alternativo**| 1. Usuário navega para outra aba sem salvar.<br>2. Sistema pergunta “Deseja descartar alterações?”.<br>3. Usuário confirma ou retorna ao formulário. |
| **Fluxo de exceção** | 1. Dados inválidos (formato de e-mail incorreto, campos obrigatórios vazios).<br>2. Sistema exibe mensagem de erro específica e não salva.<br>3. Erro ao carregar avatar do servidor; sistema exibe placeholder e permite nova tentativa de upload. |
| **Pós-condições**    | Perfil do usuário atualizado no sistema; alterações refletidas nas próximas sessões.                                      |
| **Data de Criação**  | 15/05/2025                                                                                                               |
| **Rastreabilidade**  | [OBS12](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Observacao/#tabela-de-requisitos-funcionais)                                                                                                                     |

**Autor do tabela 10:** <a  href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>, <a  href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>, <a  href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a>

---

##  Gerenciar Contas Bancárias Vinculadas

<font size="3">
  <p style="text-align:center; margin:-2em 0 0; line-height:1.2;">
    Tabela 11: Caso de Uso UC10 – Gerenciar Contas Bancárias Vinculadas<br>
    <span style="font-size:0.85em; font-style:italic;">
      Detalhamento do caso de uso UC10 para visualização e cancelamento de contas bancárias associadas ao aparelho.
    </span>
  </p>
</font>

| UC10                 | Informações                                                                                                                     |
|:---------------------|:--------------------------------------------------------------------------------------------------------------------------------|
| **Descrição**        | Permite ao usuário consultar detalhes ou cancelar a vinculação de contas bancárias associadas ao aparelho.                     |
| **Ator**             | Usuário                                                                                                                         |
| **Pré-condições**    | Usuário autenticado; existe ao menos uma conta bancária vinculada ao aparelho.                                                  |
| **Ação**             | O usuário acessa a área de “Contas Bancárias” e opta por visualizar ou desvincular uma conta.                                   |
| **Fluxo principal**  | 1. Usuário seleciona “Contas Bancárias” no menu de configurações.<br>2. Sistema lista todas as contas vinculadas.<br>3. Usuário clica em uma conta para ver detalhes.<br>4. Sistema exibe informações da conta.<br>5. Usuário seleciona “Cancelar Vinculação”.<br>6. Sistema solicita confirmação.<br>7. Usuário confirma e sistema remove a conta vinculada, exibindo mensagem de sucesso. |
| **Fluxo alternativo**| 1. Usuário visualiza detalhes e opta por não cancelar.<br>2. Sistema retorna à lista de contas sem alterações.<br>3. Usuário seleciona múltiplas contas para desvincular; sistema confirma desvinculação em lote.                  |
| **Fluxo de exceção** | 1. Erro ao obter lista de contas ou detalhes (timeout, falha de API).<br>2. Sistema exibe “Não foi possível carregar as contas, tente novamente”.<br>3. Usuário tenta novamente mais tarde. |
| **Pós-condições**    | Conta bancária desvinculada com sucesso, ou visualização concluída sem alterações.                                             |
| **Data de Criação**  | 15/05/2025                                                                                                                      |
| **Rastreabilidade**  | [QS03](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#requisitos-elicitados)                                                                                                                      |

**Autor do tabela 11:** <a  href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>, <a  href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>, <a  href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a>

---

##  Guia de Ações Pós-Furto

<font size="3">
  <p style="text-align:center; margin:-2em 0 0; line-height:1.2;">
    Tabela 12: Caso de Uso UC11 – Guia de Ações Pós-Furto<br>
    <span style="font-size:0.85em; font-style:italic;">
      Detalhamento do caso de uso UC11 para apresentar ao usuário o passo a passo de procedimentos após furto ou roubo do aparelho.
    </span>
  </p>
</font>

| UC11                 | Informações                                                                                                          |
|:---------------------|:---------------------------------------------------------------------------------------------------------------------|
| **Descrição**        | O aplicativo fornece um guia interativo com orientações detalhadas sobre o que fazer após o furto ou roubo do aparelho. |
| **Ator**             | Usuário                                                                                                               |
| **Pré-condições**    | Usuário autenticado; boletim de ocorrência registrado; conexão à internet.                                            |
| **Ação**             | O usuário acessa a seção “Guia Pós-Furto” para visualizar instruções passo a passo.                                   |
| **Fluxo principal**  | 1. Usuário abre o menu e seleciona “Guia Pós-Furto”.<br>2. Sistema carrega a lista de etapas recomendadas.<br>3. Usuário navega pelas etapas (contatar polícia, bloquear chip, limpar dados etc.).<br>4. Sistema exibe explicação detalhada de cada etapa e links diretos para ações (Registrar Boletim, Bloqueio Remoto, Limpeza Remota).<br>5. Caso de uso finalizado quando o usuário completa todas as etapas ou sai da seção. |
| **Fluxo alternativo**| 1. Usuário inicia o guia mas perde a conexão.<br>2. Sistema exibe versão offline simplificada com passos básicos.<br>3. Usuário retoma conexão para conteúdo completo. |
| **Fluxo de exceção** | 1. Falha ao carregar o conteúdo do guia (erro de API).<br>2. Sistema exibe mensagem “Não foi possível carregar as instruções, tente novamente mais tarde”.<br>3. Falha na leitura de configuração local; sistema exibe “Conteúdo temporariamente indisponível” e oferece link para download manual. |
| **Pós-condições**    | Guia exibido; acesso rápido às funcionalidades de urgência disponível; registro de acesso ao guia para auditoria.    |
| **Data de Criação**  | 15/05/2025                                                                                                            |
| **Rastreabilidade**  | [QS04](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#requisitos-elicitados)                                                                                                                  |

**Autor do tabela 12:** <a  href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>, <a  href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>, <a  href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a>

---

##  Cadastrar Pessoa de Confiança

<font size="3">
  <p style="text-align:center; margin:-2em 0 0; line-height:1.2;">
    Tabela 13: Caso de Uso UC12 – Cadastrar Pessoa de Confiança<br>
    <span style="font-size:0.85em; font-style:italic;">
      Detalhamento do caso de uso UC12 para permitir ao usuário cadastrar contatos autorizados a emitir alertas em situações de emergência.
    </span>
  </p>
</font>

| UC12                  | Informações                                                                                                                                                          |
|:----------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Descrição**         | O aplicativo permite ao usuário definir “pessoas de confiança” que possam enviar alertas em seu nome durante emergências.                                             |
| **Ator**              | Usuário                                                                                                                                                             |
| **Pré-condições**     | Usuário autenticado; lista de contatos do dispositivo disponível; autorização de acesso aos contatos concedida pelo usuário.                                         |
| **Ação**              | O usuário seleciona contatos da sua agenda e cadastra-os como confiáveis para emissão de alertas remotos.                                                            |
| **Fluxo principal**   | 1. Usuário acessa “Configurações de Emergência”.<br>2. Seleciona “Pessoas de Confiança”.<br>3. Sistema exibe lista de contatos.<br>4. Usuário marca os contatos desejados e clica em “Salvar”.<br>5. Sistema confirma “Contatos de confiança cadastrados com sucesso”. |
| **Fluxo alternativo** | 1. Usuário não seleciona nenhum contato e tenta salvar.<br>2. Sistema exibe aviso “Selecione ao menos um contato para continuar”.<br>3. Usuário importa grupo de contatos por CSV; sistema valida e apresenta lista para confirmação.                                     |
| **Fluxo de exceção**  | 1. Falha na leitura da lista de contatos (permissão negada pelo sistema operacional).<br>2. Sistema exibe “Permissão de acesso aos contatos negada” e orienta a habilitar nas configurações.<br>3. Erro de parsing no CSV importado; sistema exibe “Arquivo inválido” e sugestão de template. |
| **Pós-condições**     | Contatos selecionados armazenados como pessoas de confiança; podem ser usados para envio de alertas em casos de emergência.                                           |
| **Data de Criação**   | 15/05/2025                                                                                                                                                           |
| **Rastreabilidade**   | [ADD04](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/#requisitos-funcionais-rf_1)                                                                                                                                                           |

**Autor do tabela 13:** <a  href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>, <a  href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>, <a  href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a>

---

##  Backup Periódico de Dados

<font size="3">
  <p style="text-align:center; margin:-2em 0 0; line-height:1.2;">
    Tabela 14: Caso de Uso UC13 – Backup Periódico de Dados<br>
    <span style="font-size:0.85em; font-style:italic;">
      Detalhamento do caso de uso UC13 para realização automática de backup periódico dos dados do dispositivo.
    </span>
  </p>
</font>

| UC13                 | Informações                                                                                                                                                                     |
|:---------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Descrição**        | Como usuário, desejo que o sistema realize backups automáticos e periódicos dos dados do meu celular (contatos, fotos etc.) para garantir recuperação em caso de roubo ou perda. |
| **Ator**             | Usuário                                                                                                                                                                         |
| **Pré-condições**    | Usuário autenticado; espaço de armazenamento disponível no servidor; permissão de backup concedida.                                                                            |
| **Ação**             | O sistema agenda e executa backups periódicos conforme configuração do usuário.                                                                                                 |
| **Fluxo principal**  | 1. Usuário acessa “Configurações de Backup”.<br>2. Define frequência (diária, semanal etc.) e tipo de dados a serem incluídos.<br>3. Clica em “Ativar Backup Automático”.<br>4. Sistema agenda tarefas de backup.<br>5. Em cada execução, sistema realiza backup e notifica o usuário.<br>6. Caso de uso finalizado. |
| **Fluxo alternativo**| 1. Usuário cancela configuração de backup automático.<br>2. Sistema desativa backups programados e confirma “Backup automático desativado”.<br>3. Usuário altera frequência de backup já existente; sistema atualiza cronograma sem necessidade de desativar e reativar.                                       |
| **Fluxo de exceção** | 1. Falha ao acessar dados (erro de permissão ou I/O).<br>2. Sistema registra erro, notifica usuário “Falha no backup, verifique permissões” e mantém agendamento.<br>3. Espaço em disco insuficiente; sistema notifica o usuário e pausa backups até liberação de espaço.             |
| **Pós-condições**    | Backups periódicos executados com sucesso ou registro de falhas mantendo histórico de tentativas.                                                                               |
| **Data de Criação**  | 15/05/2025                                                                                                                                                                      |
| **Rastreabilidade**  | [ST4](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Storytelling/#tabela-de-requisitos-funcionais)                                                                                                                                                                        |

**Autor do tabela 14:** <a  href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>, <a  href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>, <a  href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a>

---

##  Feedback Visual ao Usuário

<font size="3">
  <p style="text-align:center; margin:-2em 0 0; line-height:1.2;">
    Tabela 15: Caso de Uso UC14 – Feedback Visual ao Usuário<br>
    <span style="font-size:0.85em; font-style:italic;">
      Detalhamento do caso de uso UC14 para exibir confirmação visual após ações críticas no aplicativo.
    </span>
  </p>
</font>

| UC14                 | Informações                                                                                           |
|:---------------------|:------------------------------------------------------------------------------------------------------|
| **Descrição**        | O aplicativo deve fornecer confirmação visual (feedback) ao usuário após realizar ações importantes.  |
| **Ator**             | Usuário                                                                                               |
| **Pré-condições**    | Usuário autenticado; ação executável (registro, envio, bloqueio etc.) concluída pelo sistema.         |
| **Ação**             | O sistema exibe elemento visual (banner, toast, modal) indicando sucesso ou falha da operação.         |
| **Fluxo principal**  | 1. Usuário executa ação crítica (ex.: enviar boletim, bloquear dispositivo).<br>2. Sistema processa a solicitação.<br>3. Sistema exibe feedback visual de sucesso.<br>4. Feedback permanece visível por tempo predefinido ou até dismiss. |
| **Fluxo alternativo**| 1. Ação é concluída com aviso informativo (ex.: dados salvos com observações).<br>2. Sistema exibe feedback informativo em vez de sucesso genérico.<br>3. Usuário ignora feedback e realiza outra ação; sistema salva estado da ação anterior e exibe feedback ao retornar. |
| **Fluxo de exceção** | 1. Operação falha (erro de rede, validação, servidor).<br>2. Sistema exibe feedback visual de erro e orienta nova tentativa.<br>3. Erro ao renderizar componente de feedback; sistema exibe fallback textual e registra erro para auditoria. |
| **Pós-condições**    | Usuário visualmente informado sobre o resultado da ação; interface retorna ao estado padrão.         |
| **Data de Criação**  | 15/05/2025                                                                                            |
| **Rastreabilidade**  | [Q12](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#requisitos-elicitados)                                                                                                  |

**Autor do tabela 15:** <a  href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>, <a  href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>, <a  href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a>

---

## Bibliografia

> <a name="ref1">[ 1 ]</a> **MICROSOFT.** Criar um diagrama de caso de uso UML. Disponível em: [https://support.microsoft.com/pt-br/topic/criar-um-diagrama-de-caso-de-uso-uml-92cc948d-fc74-466c-9457-e82d62ee1298](https://support.microsoft.com/pt-br/topic/criar-um-diagrama-de-caso-de-uso-uml-92cc948d-fc74-466c-9457-e82d62ee1298). Acesso em 14 de Maio.


> <a name="ref2"> [2] </a>**IBM** Diagrams: Use Case. Disponível em: [https://www.ibm.com/docs/pt-br/rsm/7.5.0?topic=diagrams-use-case](https://www.ibm.com/docs/pt-br/rsm/7.5.0?topic=diagrams-use-case) Acesso em: 13 maio 2025.

> <a name="ref2"> [3] </a> **MINISTÉRIO DA CIÊNCIA, TECNOLOGIA, INOVAÇÕES E COMUNICAÇÕES.** [Especificação de Caso de Uso: UC<000> - <Nome do Caso de Uso>. Versão 1.0. Autor: MCTIC - CGSI. Nome do Arquivo: [SIGLA] UC[000][Nome_do_caso_de_uso].docx. Brasília, 2025.](../assets/pdf/caso-de-uso/SiglaProjeto_EspecificacaoCasoUso.pdf)



---

## Histórico de Versões 

| Versão | Data de produção   | Descrição da Alteração                               | Autor(es)             | Revisor(es)      | Data de Revisão |
| :----: | :----------------: | :--------------------------------------------------: | :-------------------: | :-------------:  |  :-----------: |
| 1.0    | 09/05/2025         | Criação do documento                                 | <a  href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a>    | <a  href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | 09/05/2025 |
| 1.1    | 13/05/2025         | Inicialização do Casos de Uso                        | <a  href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>, <a  href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>, <a  href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a> | <a  href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a>, <a  href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | 13/05/2025 |
| 1.2    | 13/05/2025         | Ajuste nos Casos de Uso e adição de novos detalhes   | <a  href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a>, <a  href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>, <a  href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | <a  href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a>, <a  href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | 13/05/2025 |
| 1.3    | 14/05/2025         | Adição das referências                               | <a  href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>    | <a  href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a>, <a  href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a> | 14/05/2025 |
| 1.4    | 15/05/2025         | Inclusão de novas tabelas UC's                               | <a  href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>    | <a  href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a>, <a  href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | 15/05/2025 |
| 1.5    | 05/07/2025 | Inserção da tabela de contribuição| <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>| 05/07/2025|
| 1.6    | 06/07/2025 | Correção do diagrama de caso de Uso| <a style="color:gold;" href="https://github.com/bessazs" target="_blank">Vítor Bessa</a> | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>| 05/07/2025|