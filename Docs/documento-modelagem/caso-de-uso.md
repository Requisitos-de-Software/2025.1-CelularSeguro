# Casos de Uso

---

## Introdução
Um caso de uso se refere a uma descrição detalhada de como o sistema será utilizado em uma determinada situação ou contexto. Ele descreve as interações entre os usuários e o sistema, apresentando os passos necessários para alcançar um objetivo específico. O objetivo dos casos de uso é auxiliar no processo de desenvolvimento de um sistema, fornecendo uma visão clara dos requisitos funcionais do sistema, descrevendo as ações que os usuários podem realizar e as respostas do sistema a essas ações.

---

# Metodologia

O diagrama de caso de uso é uma representação visual que resume as interações entre os usuários e um sistema, destacando suas funcionalidades e comportamentos. Ele é composto por atores, que representam os usuários ou sistemas externos, e casos de uso, que descrevem as ações realizadas pelos usuários e as respostas esperadas do sistema.

Para a modelagem dos casos de uso do aplicativo Celular Seguro.gov, foi utilizada a persona primária João da Silva, um motoboy de 36 anos que depende do celular para realizar suas entregas. João já passou por situações de roubo e, por isso, precisa de um sistema rápido e confiável que lhe permita bloquear ou rastrear seu aparelho em caso de furto. A partir da análise das dores e necessidades desse perfil de usuário, foi possível levantar os principais objetivos que ele busca alcançar com o uso da plataforma.

---

<font size="3"><p style="text-align: center"><b>Tabela 1</b>: Elementos do diagrama de casos de uso</p></font>

| Nome | Função | Elemento
|------|------|:-------:
| Ator | Representam os diferentes tipos de usuários externos que interagem com o sistema | <figure class="usecaseElement" style="width: 20%; display: flex;">![actor](../assets/usecase/actor.png)</figure>
| Elipse (Caso de Uso) | É usada para representar os casos de uso no diagrama. Um caso de uso descreve uma funcionalidade ou uma ação específica que o sistema pode realizar em resposta às interações dos atores. A elipse contém o nome do caso de uso | <figure class="usecaseElement" style="width: 40%; display: flex;">![elipse](../assets/usecase/elipse.png)</figure>
| Retângulo (Sistema) | Usado para representar o sistema ou o bloco em análise. Ele envolve os casos de uso e atores relacionados | <figure class="usecaseElement" style="width: 40%; display: flex;">![retangulo](../assets/usecase/retangulo.png)</figure>
| Flecha (Relações) | As flechas são usadas para representar as relações ou interações entre atores e casos de uso | <figure class="usecaseElement" style="width: 40%; display: flex;">![flechas](../assets/usecase/flecha.png)</figure>

**Autor do tabela 1:** <a style= href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>

Além disso, no diagrama de casos de uso é possível especificar:

- Os requisitos externos de um sistema, ou seja, as funcionalidades necessárias que o sistema deve oferecer para atender às necessidades dos usuários.
- As funcionalidades disponíveis no sistema, ou seja, o que o sistema é capaz de fazer para satisfazer as necessidades dos usuários.
- Os requisitos impostos pelo sistema ao ambiente em que está inserido, definindo como o sistema interage com o ambiente para realizar suas funções.

---
## Especialização dos casos de uso


| UC01             | Informações                                                                 |
|------------------|------------------------------------------------------------------------------|
| **Descrição**     | O usuário é capaz de emitir um alerta imediato de roubo do dispositivo.     |
| **Ator**          | Usuário                                                                     |
| **Pré-condições** | Usuário autenticado; dispositivo previamente registrado no sistema.         |
| **Ação**          | O usuário emite um alerta de roubo via aplicativo.                          |
| **Fluxo principal** | - O usuário acessa o app.  
- Seleciona “Emitir Alerta de Roubo”.  
- Sistema exibe popup de confirmação.  
- Usuário confirma.  
- Sistema registra alerta, aciona “Registrar Boletim” e “Notificar Autoridades”. |
| **Fluxo alternativo** | - O usuário cancela no popup de confirmação.  
- Sistema retorna ao painel. |
| **Fluxo de exceção** | - Falha na notificação às autoridades.  
- Sistema exibe mensagem de erro e registra falha. |
| **Pós-condições**  | Alerta de roubo registrado, boletim iniciado e autoridades notificadas.    |
| **Data de Criação**| 13/05/2025                                                                 |
| **Rastreabilidade**| RF01, RF02, RF05                                                           |


----

| UC02             | Informações                                                                  |
|------------------|-------------------------------------------------------------------------------|
| **Descrição**     | O usuário registra formalmente um boletim de ocorrência detalhando o roubo. |
| **Ator**          | Usuário                                                                      |
| **Pré-condições** | Usuário autenticado com login gov.br; dispositivo com conexão ativa.         |
| **Ação**          | O usuário preenche o formulário e envia o boletim.                           |
| **Fluxo principal** | - Usuário seleciona “Registrar Boletim”.  
- Sistema exibe formulário.  
- Usuário preenche os campos e envia.  
- Sistema valida e exibe protocolo. |
| **Fluxo alternativo** | - Usuário tenta enviar sem preencher todos os campos.  
- Sistema bloqueia envio e exibe aviso. |
| **Fluxo de exceção** | - Erro no servidor ao registrar.  
- Sistema exibe mensagem de falha. |
| **Pós-condições**  | Boletim registrado com número de protocolo.                                 |
| **Data de Criação**| 13/05/2025                                                                  |
| **Rastreabilidade**| RF02, RF06                                                                  |

---

| UC03             | Informações                                                                 |
|------------------|------------------------------------------------------------------------------|
| **Descrição**     | Permite ao usuário localizar a posição atual ou última conhecida do dispositivo. |
| **Ator**          | Usuário                                                                     |
| **Pré-condições** | Boletim registrado; dispositivo com rastreamento ativado e online.          |
| **Ação**          | O usuário solicita a localização do aparelho.                               |
| **Fluxo principal** | - Usuário acessa “Localizar Celular”.  
- Sistema verifica pré-condições.  
- Solicita coordenadas ao provedor.  
- Exibe mapa com marcador da localização. |
| **Fluxo alternativo** | - Dispositivo offline.  
- Sistema exibe última localização conhecida. |
| **Fluxo de exceção** | - Erro na API de localização.  
- Sistema exibe mensagem de indisponibilidade. |
| **Pós-condições**  | Localização exibida no mapa ou mensagem de erro apresentada.               |
| **Data de Criação**| 13/05/2025                                                                 |
| **Rastreabilidade**| RF03, RF07, RF10                                                           |

---

| UC04             | Informações                                                                 |
|------------------|------------------------------------------------------------------------------|
| **Descrição**     | O usuário bloqueia o aparelho remotamente para impedir seu uso.             |
| **Ator**          | Usuário                                                                     |
| **Pré-condições** | Boletim registrado; dispositivo localizado anteriormente.                   |
| **Ação**          | O usuário envia comando de bloqueio remoto.                                 |
| **Fluxo principal** | - Usuário acessa “Bloqueio Remoto”.  
- Sistema solicita confirmação.  
- Usuário confirma.  
- Sistema envia comando à operadora e registra ação. |
| **Fluxo alternativo** | - Usuário cancela confirmação.  
- Sistema retorna ao painel. |
| **Fluxo de exceção** | - Falha na comunicação com operadora.  
- Sistema exibe mensagem de erro. |
| **Pós-condições**  | Dispositivo bloqueado ou falha registrada.                                 |
| **Data de Criação**| 13/05/2025                                                                 |
| **Rastreabilidade**| RF04, RF08                                                                 |

---

| UC05             | Informações                                                                 |
|------------------|------------------------------------------------------------------------------|
| **Descrição**     | O usuário solicita envio de backup de dados por email com link seguro.      |
| **Ator**          | Usuário                                                                     |
| **Pré-condições** | Usuário autenticado; backup disponível.                                     |
| **Ação**          | O usuário seleciona um backup e envia por email.                            |
| **Fluxo principal** | - Usuário acessa “Backup de Dados”.  
- Sistema mostra backups disponíveis.  
- Usuário seleciona e clica em “Enviar”.  
- Sistema envia email com link seguro. |
| **Fluxo alternativo** | - Email inválido ou não cadastrado.  
- Sistema exibe aviso para atualização do cadastro. |
| **Fluxo de exceção** | - Erro no envio do email.  
- Sistema exibe falha e orienta nova tentativa. |
| **Pós-condições**  | Email enviado com sucesso ou falha registrada.                             |
| **Data de Criação**| 13/05/2025                                                                 |
| **Rastreabilidade**| RF09, RF11                                                                 |








## Bibliografia

---

## Histórico de Versões 

| Versão | Data de produção   | Descrição da Alteração                               | Autor(es)             | Revisor(es)      |Data de Revisão |
| :----: | :----------------: | :--------------------------------------------------: | :-------------------: | :-------------:  |  :-----------: |
| 1.0    | 09/05/2025         | Criação do documento                           |<a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a>    | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>| 09/05/2025|
| 1.1    | 13/05/2025         | Inicialização do Casos de Uso                           |<a style="color:gold;" href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>, <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> e <a style="color:gold; href="https://github.com/Bessazs" target="_blank">Vitor Pereira</a>    | <a style="color:gold; href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a>, <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a>| 13/05/2025|