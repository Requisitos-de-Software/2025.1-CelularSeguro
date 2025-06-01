
## Introdução

As histórias de usuário são uma técnica essencial na elicitação de requisitos dentro de metodologias ágeis, como Scrum e XP (Extreme Programming). Elas consistem em descrições sucintas e centradas no usuário, que expressam uma funcionalidade desejada de forma compreensível tanto para a equipe de desenvolvimento quanto para os stakeholders (Cohn, 2004). A estrutura típica de uma história de usuário segue o formato: “Como [tipo de usuário](), eu quero [ação]() para [objetivo]()”, o que auxilia na identificação clara do valor de negócio associado à funcionalidade (Leffingwell, 2011).



## Metodologia

A elaboração deste artefato adotou uma abordagem empírica de elicitação baseada na entrevista estruturada com o Product Owner (PO), o qual representou a visão do cliente no projeto. A sessão foi conduzida por meio da plataforma Teams, com entrevistas separadas organizadas conforme a [Tabela 1]() abaixo, configurando uma interação síncrona e informal — alinhada às boas práticas de desenvolvimento ágil descritas por Sommerville (2019).
Durante a entrevista, os critérios de aceitação foram formalizados, refletindo os comportamentos esperados do sistema em cada cenário de uso. Para fins de planejamento e gestão, foi adotado o método de priorização Three-Level Scale, que classifica as histórias de usuário em prioridades Alta, Média e Baixa (Leffingwell, 2011). Tal método é simples, porém eficaz, para equipes que operam sob ciclos curtos de entrega.

<font size="3"><p style="text-align: center">Tabela 1 - Cronograma dos participantes da entrevista.</p></font>

| Nome                                                    | Função                                     | Entrevistado                                | Data       | Hora |
| ------------------------------------------------------- | -------------------------------------------|---------------------------------------------|------------|------|
| [Gabriel Lima](https://github.com/gabriel-lima258)      | Elaborador das histórias                   | [Lucas](https://github.com/gabriel-lima258) | 29/05/2025 | 19:05 |

<font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

### Modelo

O modelo a ser seguido para realização das Histórias do Usuário está representado na [tabela 2]() abaixo. A sigla **US** representa a abreviação de User Stories (Histórias de Usuário), que será seguido pelo número indicador daquela história.


<font size="3"><p style="text-align: center">Tabela 2: Modelo de Histórias de Usuário (US)</p></font>

| ID |              História de Usuário             |                      Critérios de aceitação                      |   Rastreabilidade   | Prioridade | 
| :----: | :---------------------------------: | :----------------------------------------------: | :--------: | :--------: |
|  US**   | Detalhamento da história | Detalhar como aquela história será aceita | Rastro do requisito |   Nível de prioridade |  


<font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

## Histórias de Usuário

As tabelas de 1 a 42 descrevem as histórias de usuário elicitadas (Representadas pelo ID USX, onde X é o número da história).

---

### US00 - Cadastro de múltiplos celulares

??? abstract "Tabela 3 - História de Usuário [Cadastro de múltiplos celulares]"

    <center>

    <font size="3"><p style="text-align: center">Tabela 3 - História de Usuário [Cadastro de múltiplos celulares].</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US00                   | Cadastro de múltiplos celulares |
    | Descrição              | Eu, como usuário, gostaria de poder cadastrar múltiplos celulares na minha conta e vinculá-los ao meu CPF. |
    | Critérios de Aceitação | O sistema deve permitir adicionar mais de um número por CPF; Validar os números inseridos; Exibir lista de números cadastrados. |
    | Rastreabilidade        | [ADD03](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/#requisitos-funcionais-rf_1) |
    | Prioridade             | Média |

    <font size="3"><p style="text-align: center">Fonte: [Arthur Carvalho](https://github.com/arthurlleite).</p></font>

    </center>

---

### US01 - Confirmação visual após ações

??? abstract "Tabela 4 - História de Usuário [Confirmação visual após ações]"

    <center>

    <font size="3"><p style="text-align: center">Tabela 4 - História de Usuário [Confirmação visual após ações].</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US01                   | Confirmação visual após ações |
    | Descrição              | Eu, como usuário, quero ter confirmação visual ao realizar uma ação importante. |
    | Critérios de Aceitação | O sistema deve apresentar feedback visual (mensagem ou alerta) após ações críticas como login, cadastro e bloqueio remoto. |
    | Rastreabilidade        | [RF05](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#requisitos-funcionais) |
    | Prioridade             | Alta |

    <font size="3"><p style="text-align: center">Fonte: [Arthur Carvalho](https://github.com/arthurlleite).</p></font>

    </center>

---

### US02 - Notificação de atividade suspeita

??? abstract "Tabela 5 - História de Usuário [Notificação de atividade suspeita]"

    <center>

    <font size="3"><p style="text-align: center">Tabela 5 - História de Usuário [Notificação de atividade suspeita].</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US02                   | Notificação de atividade suspeita |
    | Descrição              | Eu, como usuário, quero receber notificação assim que o sistema identificar uma atividade suspeita ao meu dispositivo. |
    | Critérios de Aceitação | O sistema deve enviar notificação push; A notificação deve conter data, hora e tipo da atividade suspeita. |
    | Rastreabilidade        | [RF06](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#requisitos-funcionais) |
    | Prioridade             | Alta |

    <font size="3"><p style="text-align: center">Fonte: [Arthur Carvalho](https://github.com/arthurlleite).</p></font>

    </center>

---

### US03 - SMS após ação remota

??? abstract "Tabela 6 - História de Usuário [SMS após ação remota]"

    <center>

    <font size="3"><p style="text-align: center">Tabela 6 - História de Usuário [SMS após ação remota].</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US03                   | SMS após ação remota |
    | Descrição              | Eu, como usuário, gostaria de receber SMS após cadastramento remoto que eu fiz. |
    | Critérios de Aceitação | O sistema deve enviar SMS de confirmação após ações como bloqueio ou formatação remota. |
    | Rastreabilidade        | [BS29](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais) |
    | Prioridade             | Baixa |

    <font size="3"><p style="text-align: center">Fonte: [Arthur Carvalho](https://github.com/arthurlleite).</p></font>

    </center>

---

### US04 - Registro de logs para auditoria

??? abstract "Tabela 7 - História de Usuário [Registro de logs para auditoria]"

    <center>

    <font size="3"><p style="text-align: center">Tabela 7 - História de Usuário [Registro de logs para auditoria].</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US04                   | Registro de logs para auditoria |
    | Descrição              | Eu, como usuário, gostaria de registrar logs de todas as ações remotas que eu fizer para a auditoria. |
    | Critérios de Aceitação | O sistema deve manter logs com data, tipo de ação e status; Os logs devem ser exportáveis ou consultáveis pelo usuário. |
    | Rastreabilidade        | [BS33](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais) |
    | Prioridade             | Média |

    <font size="3"><p style="text-align: center">Fonte: [Arthur Carvalho](https://github.com/arthurlleite).</p></font>

    </center>

---

### US05 - Validação do número de celular

??? abstract "Tabela 8 - História de Usuário [Validação do número de celular]"

    <center>

    <font size="3"><p style="text-align: center">Tabela 8 - História de Usuário [Validação do número de celular].</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US05                   | Validação do número de celular |
    | Descrição              | Eu, como usuário, gostaria de uma função que valide o número de celular que estou registrando. |
    | Critérios de Aceitação | O sistema deve enviar um código de verificação para o número informado; O usuário só avança após a verificação. |
    | Rastreabilidade        | [US05](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/) |
    | Prioridade             | Alta |

    <font size="3"><p style="text-align: center">Fonte: [Arthur Carvalho](https://github.com/arthurlleite).</p></font>

    </center>

---

### US06 - Buscar dispositivo pelo app

??? abstract "Tabela 9 - História de Usuário [Buscar dispositivo pelo app]"

    <center>

    <font size="3"><p style="text-align: center">Tabela 9 - História de Usuário [Buscar dispositivo pelo app].</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US06                   | Buscar dispositivo pelo app |
    | Descrição              | Eu, como usuário, gostaria de buscar meu celular no próprio aplicativo. |
    | Critérios de Aceitação | O app deve exibir localização aproximada do dispositivo conectado; Deve depender de conexão ativa e GPS habilitado. |
    | Rastreabilidade        | [US06](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/) |
    | Prioridade             | Média |

    <font size="3"><p style="text-align: center">Fonte: [Arthur Carvalho](https://github.com/arthurlleite).</p></font>

    </center>

---

<p style="text-align: center">Entrevista 1</p>

<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/f2TnfiPgJio" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</center>

<p style="text-align: center">Caso não abra <a href="https://youtu.be/f2TnfiPgJio" target="blanket">clique aqui</a></p>
>PDF (30 maio. 2025): [Termo de Compromisso](https://github.com/Requisitos-de-Software/2025.1-CelularSeguro/blob/main/Docs/assets/pdf/verificacao/Copia_de_Termo_Consentimento_CelularSeguro_assinado.pdf)

<font size="3"><p style="text-align: center">Fonte: [Arthur Carvalho](https://github.com/arthurlleite)</p></font>


### US07 -  Confirmar envio do boletim com protocolo visível

??? abstract "Tabela 9 - Confirmar envio do boletim com protocolo visível (Não implementado)"

    <center>

    <font size="3"><p style="text-align: center">Tabela 9 - Confirmar envio do boletim com protocolo visível.</p></font>

    |    **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US01                   | Confirmar envio do boletim com protocolo visível |
    | **Descrição**          | Eu, como usuário, desejo visualizar uma confirmação clara e acessível com o  número de protocolo após o envio do boletim, para garantir que ele foi registrado corretamente. |
    | **Critérios de Aceitação** | - Após o envio bem-sucedido, o número de protocolo deve ser exibido em   destaque por no mínimo 10 segundos. <br> - Deve haver opção para copiar o número do protocolo. <br> - A   mensagem de confirmação deve utilizar linguagem clara e acessível. |
    | **Rastreabilidade**    | <a href="../Questionario/">OBS4</a>, <a href="../Questionario/">OBS8</a>, <a href="../Questionario/">OBS15</a>, <a href="../Questionario/">OBS20</a>|
    | **Prioridade**         | Alta |

    <font size="3"><p style="text-align: center">Fonte: [Mateus Bastos](https://github.com/MateuSansete)</p></font>

    </center>


### US08 - Usuário Anexar arquivos ao boletim

??? abstract "Tabela 10 - Usuário Anexar arquivos ao boletim"

    <center>

    <font size="3"><p style="text-align: center">Tabela 10 - Usuário Anexar arquivos ao boletim.</p></font>


    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US02                   | Anexar arquivos ao boletim |
    | **Descrição**          | Eu, como usuário, desejo anexar arquivos como imagens ou documentos ao boletim para fornecer provas adicionais do roubo. |
    | **Critérios de Aceitação** | - O sistema deve aceitar arquivos JPG, PNG e PDF. <br> - O tamanho máximo permitido por arquivo deve ser 10 MB. <br> - Arquivos fora dos padrões devem gerar mensagem de erro    clara. |
    | **Rastreabilidade**    | <a href="../Questionario/">OBS8</a>, <a href="../Questionario/">OBS19</a>|
    | **Prioridade**         | Média |


    <font size="3"><p style="text-align: center">Fonte: [Mateus Bastos](https://github.com/MateuSansete)</p></font>

    </center>


### US09 -  Registrar boletim de ocorrência

??? abstract "Tabela 11 - Registrar boletim de ocorrência"

    <center>

    <font size="3"><p style="text-align: center">Tabela 11 -  Registrar boletim de ocorrência.</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US03                   | Registrar boletim de ocorrência |
    | **Descrição**          | Eu, como usuário, desejo registrar um boletim de ocorrência pelo aplicativo para formalizar o roubo do meu celular de forma rápida e prática. |
    | **Critérios de Aceitação** | - O sistema deve disponibilizar um formulário com campos para dados do roubo. <br> - O botão “Registrar Boletim” deve estar acessível após o login com gov.br. <br> - Após o envio, o boletim deve ser processado pelo sistema. |
    | **Rastreabilidade**    | <a href="../Questionario/">OBS2</a>, <a href="../Questionario/">OBS8</a>|
    | **Prioridade**         | Alta |

    <font size="3"><p style="text-align: center">Fonte: [Mateus Bastos](https://github.com/MateuSansete)</p></font>


    </center>

### US10 - Validar campos obrigatórios do boletim

??? abstract "Tabela 12 - Validar campos obrigatórios do boletim"

    <center>

    <font size="3"><p style="text-align: center">Tabela 12 - Validar campos obrigatórios do boletim.</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US04                   | Validar campos obrigatórios do boletim |
    | **Descrição**          | Eu, como usuário, desejo ser impedido de enviar o boletim se campos obrigatórios não forem preenchidos, para garantir que as informações estejam completas. |
    | **Critérios de Aceitação** | - O sistema deve identificar campos obrigatórios não preenchidos. <br> - O botão de envio deve ser desabilitado ou gerar aviso se houver campos faltando. <br> - A mensagem de erro deve informar quais campos precisam ser preenchidos. |
    | **Rastreabilidade**    | <a href="../Questionario/">OBS2</a>, <a href="../Questionario/">OBS8</a>, <a href="../Questionario/">OBS19</a>|
    |    **Prioridade**         | Alta |

    <font size="3"><p style="text-align: center">Fonte: [Mateus Bastos](https://github.com/MateuSansete)</p></font>



    </center>

### US11 -  Exibir mensagem de erro em falha de envio

??? abstract "Tabela 12 - Exibir mensagem de erro em falha de envio"

    <center>

    <font size="3"><p style="text-align: center">Tabela 12 - Exibir mensagem de erro em falha de envio.</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US05                   | Exibir mensagem de erro em falha de envio |
    | **Descrição**          | Eu, como usuário, desejo ver uma mensagem clara e amigável quando o sistema não conseguir registrar o boletim, para entender o problema e tentar novamente mais tarde. |
    | **Critérios de Aceitação** | - Em caso de falha no servidor, o sistema deve exibir mensagem amigável ao usuário. <br> - A mensagem deve informar que houve uma falha no envio e sugerir nova tentativa. <br> - A interface não deve fechar ou apagar os dados preenchidos. |
    | **Rastreabilidade**    | <a href="../Questionario/">OBS8</a>, <a href="../Questionario/">OBS19</a>, <a href="../Questionario/">OBS20</a>|
    | **Prioridade**         | Média |

    <font size="3"><p style="text-align: center">Fonte: [Mateus Bastos](https://github.com/MateuSansete)</p></font>

    </center>


### US12 - Notificação de confirmação após envio do boletim

??? abstract "Notificação de confirmação após envio do boletim"

    <center>

    <font size="3"><p style="text-align: center">Tabela 14 - Notificação de confirmação após envio do boletim.</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US06                   | Notificação de confirmação após envio do boletim |
    | **Descrição**          | Eu, como usuário, desejo receber uma notificação no celular confirmando que o boletim foi enviado, mesmo se o app for fechado, para ter certeza de que o registro foi concluído. |
    | **Critérios de Aceitação** | - O sistema deve enviar uma notificação local confirmando o envio do boletim. <br> - A notificação deve incluir o número de protocolo. <br> - A notificação deve persistir até que o usuário interaja com ela. |
    | **Rastreabilidade**    | <a href="../Questionario/">OBS4</a>, <a href="../Questionario/">OBS8</a>, <a href="../Questionario/">OBS15</a>, <a href="../Questionario/">OBS20</a>|
    | **Prioridade**         | Média |

    <font size="3"><p style="text-align: center">Fonte: [Mateus Bastos](https://github.com/MateuSansete)</p></font>


    </center>

---
<p style="text-align: center">Entrevista 2</p>

<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/gnieMHXL8Ek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</center>

<p style="text-align: center">Caso não abra <a href="https://youtu.be/gnieMHXL8Ek" target="blanket">clique aqui</a></p>

<font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258)</p></font>

---

### US13 - Redefinir a senha via e-mail **(Não Implementado)**

??? abstract "Tabela 15 - História de Usuário Redefinir a senha via e-mail"

    <center>

    <font size="3"><p style="text-align: center">Tabela 15 - História de Usuário Redefinir a senha via e-mail.</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US13                   | Redefinir a senha via e-mail |
    | Descrição              | Eu, como usuário autenticado, desejo redefinir minha senha dentro do aplicativo, recebendo um código por e-mail, para manter o acesso caso eu esqueça ou deseje trocar a senha. |
    | Critérios de Aceitação | - Dentro de Perfil deve existir a opção “Redefinir senha”.<br> - Ao selecionar, o app envia um código de verificação para o e-mail cadastrado (ou SMS, conforme escolha do usuário).<br> - O usuário informa o código no app e define uma nova senha (≥ 8 caracteres, contendo letras maiúsculas, minúsculas e números).<br> - Após a troca, o app exibe mensagem de sucesso e mantém a sessão ativa.<br> - Caso o e-mail/telefone não exista no cadastro, exibir “contato não encontrado”.<br> |
    | Rastreabilidade        | [OBS3](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Observacao/#tabela-de-requisitos-funcionais) |
    | Prioridade             |  Alta |

    <font size="3"><p style="text-align: center">Fonte: [Leonardo de Melo](https://github.com/leozinlima)</p></font>

    </center>

### US14 - Editar o seu perfil por uma aba que é disponibilizada no aplicativo **(Não Implementado)**

??? abstract "Tabela 16 - História de Usuário Editar o seu perfil por uma aba que é disponibilizada no aplicativo"

    <center>

    <font size="3"><p style="text-align: center">Tabela 16 - História de Usuário Editar o seu perfil por uma aba que é disponibilizada no aplicativo.</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US14               | Editar o seu perfil por uma aba que é disponibilizada no aplicativo |
    | Descrição              | 	Eu, como usuário, desejo acessar uma aba “Perfil” para editar meus dados pessoais sem sair do aplicativo. |
    | Critérios de Aceitação | - Aba “Perfil” fixa no menu. <br> -  Campos editáveis: nome, e-mail, telefones, senha. <br> - Validação de formato em tempo real (e-mail, DDD+telefone). <br> - Botão “Salvar” persiste dados e mostra toast de sucesso; erro de rede mantém dados locais. <br> - Mudanças sincronizam com servidor sem encerrar sessão. |
    | Rastreabilidade        | [OBS12](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Observacao/#tabela-de-requisitos-funcionais) |
    | Prioridade             | Alta |

    <font size="3"><p style="text-align: center">Fonte: [Leonardo de Melo](https://github.com/leozinlima)</p></font>

    </center>

    

### US15 - Alterar a foto de perfil

??? abstract "Tabela 17 - História de Usuário Alterar a foto de perfil"

    <center>

    <font size="3"><p style="text-align: center">Tabela 17 - História de Usuário Alterar a foto de perfil.</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US15               | Alterar a foto de perfil |
    | Descrição              | 	Eu, como usuário, desejo alterar minha foto de perfil para personalizar minha identificação no aplicativo. |
    | Critérios de Aceitação |  - Botão “Alterar foto” disponível na aba Perfil.<br> - Usuário escolhe entre Galeria ou Câmera.<br> - App permite corte/ajuste e redimensiona a imagem .<br> - Preview + opções Confirmar/Cancelar.<br> - Foto atualiza instantaneamente no app; falha exibe mensagem e mantém foto anterior. |
    | Rastreabilidade        | - |
    | Prioridade             | Médio |

    <font size="3"><p style="text-align: center">Fonte: [Leonardo de Melo](https://github.com/leozinlima)</p></font>

    </center>

### US16 - Registrar documentos

??? abstract "Tabela 18 - História de Usuário Registrar documentos"

    <center>

    <font size="3"><p style="text-align: center">Tabela 18 - História de Usuário Registrar documentos.</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US16               | Registrar documentos |
    | Descrição              | 	Eu, como usuário, desejo registrar documentos (CPF, RG etc.) para agilizar autenticações e aumentar a segurança em caso de perda ou roubo do aparelho. |
    | Critérios de Aceitação | - No menu Perfil, deve aparecer a opção “Documentos”.<br> - Ao acessar “Documentos”, o usuário pode inserir número do CPF (11 dígitos) e do RG (9 dígitos) em campos distintos.<br> - O sistema valida o formato (quantidade de dígitos) antes de salvar.<br> - Documentos cadastrados aparecem em lista na mesma tela, com botão “Remover” ao lado de cada item.<br> - Se o CPF ou RG já estiver registrado, exibir “Documento já registrado”.<br> |
    | Rastreabilidade        | - |
    | Prioridade             | Alta |

    <font size="3"><p style="text-align: center">Fonte: [Leonardo de Melo](https://github.com/leozinlima)</p></font>

    </center>

### US17 - Definir dispositivo seguro

??? abstract "Tabela 19 - História de Usuário Definir dispositivo seguro"

    <center>

    <font size="3"><p style="text-align: center">Tabela 19 - História de Usuário Definir dispositivo seguro.</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US17               | Definir dispositivo seguro |
    | Descrição              | 	Eu, como usuário, desejo marcar meu smartphone como dispositivo seguro para impedir acessos não autorizados caso seja roubado ou troque de aparelho. |
    | Critérios de Aceitação | - No menu Perfil, exibir botão “Definir dispositivo seguro”.<br> - Ao tocar em “Definir dispositivo seguro”, o app salva localmente o status de “dispositivo confiável”.<br> - Enquanto marcado como seguro, não solicitar autenticação extra em logins futuros.<br> - O usuário pode desmarcar “Dispositivo seguro” no mesmo local, retornando ao estado padrão.<br> |
    | Rastreabilidade        | - |
    | Prioridade             | Alta |

    <font size="3"><p style="text-align: center">Fonte: [Leonardo de Melo](https://github.com/leozinlima)</p></font>

    </center>

### US18 - Fazer download do Termos de Uso do aplicativo

??? abstract "Tabela 20 - História de Usuário Fazer download do Termos de Uso do aplicativo"

    <center>

    <font size="3"><p style="text-align: center">Tabela 20 - História de Usuário Fazer download do Termos de Uso do aplicativo.</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US18               | Fazer download do Termos de Uso do aplicativo |
    | Descrição              | Eu, como usuário, desejo baixar os Termos de Uso em PDF para consultá-los offline e comprovar meus direitos e deveres. |
    | Critérios de Aceitação | - Na aba “Termos de Uso” deve existir botão “Baixar Termos de Uso (PDF)”. <br> - Ao tocar, o arquivo é baixado para a pasta padrão de downloads do sistema. <br> - O PDF deve conter versão e data visíveis na primeira página. <br> - Falta de conexão exibe aviso “Não foi possível baixar. Tente novamente.” |
    | Rastreabilidade        | - |
    | Prioridade             | Média |

    <font size="3"><p style="text-align: center">Fonte: [Leonardo de Melo](https://github.com/leozinlima)</p></font>


    </center>

<p style="text-align: center">Entrevista 3.2</p>

<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/A7ETUQPDKJc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</center>

<p style="text-align: center">Caso não abra <a href="https://youtu.be/A7ETUQPDKJc" target="blanket">clique aqui</a></p>

<font size="3"><p style="text-align: center">Fonte: [Leonardo de Melo](https://github.com/leozinlima)</p></font> 

---

### US19 - Leitura do IMEI via câmera do celular

??? abstract "Tabela 21 - História de Usuário Leitura do IMEI via câmera do celular"

    <center>

    <font size="3"><p style="text-align: center">Tabela 21 - História de Usuário Leitura do IMEI via câmera do celular.</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US19                   | Leitura do IMEI via câmera do celular |
    | Descrição              | Eu, como usuário, desejo escanear o código do IMEI com a câmera do celular para evitar o preenchimento manual. |
    | Critérios de Aceitação | - O aplicativo deve ativar a câmera do celular para escanear o código de barras do IMEI. <br> - O IMEI deve ser identificado automaticamente e preenchido no campo correspondente. |
    | Rastreabilidade        | [ADD09](../../documento-elicitacao/AnalisedeDocumentos.md) |
    | Prioridade             | Alta |

    <font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

    </center>

### US20 - Concessão de permissão para leitura do IMEI pelo próprio dispositivo **(Não Implementado)**

??? abstract "Tabela 22 - História de Usuário Concessão de permissão para leitura do IMEI pelo próprio dispositivo"

    <center>

    <font size="3"><p style="text-align: center">Tabela 22 - História de Usuário Concessão de permissão para leitura do IMEI pelo próprio dispositivo.</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US20                   | Concessão de permissão para leitura do IMEI pelo próprio dispositivo |
    | Descrição              | Eu, como usuário, desejo que o aplicativo identifique automaticamente o IMEI do meu dispositivo, sem que eu precise digitá-lo ou consultar manualmente. |
    | Critérios de Aceitação | - O aplicativo deve solicitar e utilizar permissões do sistema para acessar o número IMEI do dispositivo. <br> - A leitura deve ser automática e segura, sem necessidade de acesso à galeria ou digitação. |
    | Rastreabilidade        | - |
    | Prioridade             | Alta |

    <font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

    </center>

### US21 - Guia de detalhes adicionais sobre consulta de celulares com restrições

??? abstract "Tabela 23 - História de Usuário Guia de detalhes adicionais sobre consulta de celulares com restrições"

    <center>

    <font size="3"><p style="text-align: center">Tabela 23 - História de Usuário Guia de detalhes adicionais sobre consulta de celulares com restrições.</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US21                   | Guia de detalhes adicionais sobre consulta de celulares com restrições |
    | Descrição              | Eu, como usuário, desejo acessar um guia informativo sobre o que significa ter um celular com restrição, para entender melhor o resultado da consulta. |
    | Critérios de Aceitação | - O aplicativo deve exibir uma seção com explicações sobre os diferentes tipos de restrição de IMEI. <br> - Deve fornecer orientações sobre o que fazer em caso de restrição. |
    | Rastreabilidade        | [Q17](../../documento-elicitacao/Questionario.md) |
    | Prioridade             | Média |

    <font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

    </center>

### US22 - Consulta manual e direta do IMEI

??? abstract "Tabela 24 - História de Usuário Consulta manual e direta do IMEI"

    <center>

    <font size="3"><p style="text-align: center">Tabela 24 - História de Usuário Consulta manual e direta do IMEI.</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US22                   | Consulta manual e direta do IMEI |
    | Descrição              | Eu, como usuário, desejo inserir manualmente o número IMEI para verificar se o aparelho está bloqueado ou com restrição. |
    | Critérios de Aceitação | - O aplicativo deve permitir entrada manual do número IMEI. <br> - Ao inserir e confirmar o IMEI, o aplicativo deve exibir imediatamente o status do dispositivo. |
    | Rastreabilidade        | [OBS10](../../documento-elicitacao/Observacao.md) |
    | Prioridade             | Alta |

    <font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

    </center>

### US23 - Validações de erro claras e rápidas

??? abstract "Tabela 25 - História de Usuário Validações de erro claras e rápidas"

    <center>

    <font size="3"><p style="text-align: center">Tabela 25 - História de Usuário Validações de erro claras e rápidas.</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US23                   | Validações de erro claras e rápidas |
    | Descrição              | Eu, como usuário, desejo receber mensagens claras e imediatas quando um erro ocorre, para saber como corrigi-lo facilmente. |
    | Critérios de Aceitação | - O aplicativo deve exibir mensagens de erro descritivas (ex: “IMEI inválido” ou “Campo obrigatório”). <br> - As mensagens devem aparecer em até 2 segundos após a detecção do erro. |
    | Rastreabilidade        | [OBS19](../../documento-elicitacao/Observacao.md) |
    | Prioridade             | Média |

    <font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

    </center>

### US24 - Interface clara com instruções para realização das etapas de consulta

??? abstract "Tabela 26 - História de Usuário Interface clara com instruções para realização das etapas de consulta"

    <center>

    <font size="3"><p style="text-align: center">Tabela 26 - História de Usuário Interface clara com instruções para realização das etapas de consulta.</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US24                   | Interface clara com instruções para realização das etapas de consulta |
    | Descrição              | Eu, como usuário, desejo que a interface do aplicativo seja clara e me guie durante o processo de consulta, para que eu não tenha dúvidas sobre como realizar cada etapa. |
    | Critérios de Aceitação | - A interface deve apresentar instruções visuais ou textuais em cada etapa. <br> - As instruções devem ser breves, acessíveis e de fácil compreensão. |
    | Rastreabilidade        | [OBS15](../../documento-elicitacao/Observacao.md) |
    | Prioridade             | Média |

    <font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

    </center>


<p style="text-align: center">Entrevista 4</p>

<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/M8CNqx5xESw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</center>

<p style="text-align: center">Caso não abra <a href="https://youtu.be/M8CNqx5xESw" target="blanket">clique aqui</a></p>

<font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258)</p></font>

---

### US25 - [Título da US25]

??? abstract "Tabela 27 - História de Usuário [Título da US25]"

    <center>

    <font size="3"><p style="text-align: center">Tabela 27 - História de Usuário [Título da US25].</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US25               |  |
    | Descrição              |  |
    | Critérios de Aceitação |  |
    | Rastreabilidade        |  |
    | Prioridade             |  |

    <font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

    </center>

### US26 - [Título da US26]

??? abstract "Tabela 28 - História de Usuário [Título da US26]"

    <center>

    <font size="3"><p style="text-align: center">Tabela 28 - História de Usuário [Título da US26].</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US26               |  |
    | Descrição              |  |
    | Critérios de Aceitação |  |
    | Rastreabilidade        |  |
    | Prioridade             |  |

    <font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

    </center>

### US27 - [Título da US27]

??? abstract "Tabela 29 - História de Usuário [Título da US27]"

    <center>

    <font size="3"><p style="text-align: center">Tabela 29 - História de Usuário [Título da US27].</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US27               |  |
    | Descrição              |  |
    | Critérios de Aceitação |  |
    | Rastreabilidade        |  |
    | Prioridade             |  |

    <font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

    </center>

### US28 - [Título da US28]

??? abstract "Tabela 30 - História de Usuário [Título da US28]"

    <center>

    <font size="3"><p style="text-align: center">Tabela 30 - História de Usuário [Título da US28].</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US28               |  |
    | Descrição              |  |
    | Critérios de Aceitação |  |
    | Rastreabilidade        |  |
    | Prioridade             |  |

    <font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

    </center>

### US29 - [Título da US29]

??? abstract "Tabela 31 - História de Usuário [Título da US29]"

    <center>

    <font size="3"><p style="text-align: center">Tabela 31 - História de Usuário [Título da US29].</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US29               |  |
    | Descrição              |  |
    | Critérios de Aceitação |  |
    | Rastreabilidade        |  |
    | Prioridade             |  |

    <font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

    </center>

### US30 - [Título da US30]

??? abstract "Tabela 32 - História de Usuário [Título da US30]"

    <center>

    <font size="3"><p style="text-align: center">Tabela 32 - História de Usuário [Título da US30].</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US30               |  |
    | Descrição              |  |
    | Critérios de Aceitação |  |
    | Rastreabilidade        |  |
    | Prioridade             |  |

    <font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

    </center>


<p style="text-align: center">Entrevista 5</p>

<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/gnieMHXL8Ek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</center>

<p style="text-align: center">Caso não abra <a href="https://youtu.be/gnieMHXL8Ek" target="blanket">clique aqui</a></p>

<font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258)</p></font>

---

### US31 - Enviar um SMS para uma pessoa quando a mesma for adicionada como pessoa de confiança (não implementado)

??? abstract "Tabela 33 - Enviar um SMS para uma pessoa quando a mesma for adicionada como pessoa de confiança. (não implementado)"

    <center>

    <font size="3"><p style="text-align: center">Tabela 33 - Enviar um SMS para uma pessoa quando a mesma for adicionada como pessoa de confiança (Não implementado).</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US31               | Enviar um SMS para uma pessoa quando a mesma for adicionada como pessoa de confiança |
    | Descrição              | Eu, como usuário do aplicativo Celular Seguro, desejo que o aplicativo envie automaticamente um SMS para a pessoa que adicionei como 'Pessoa de Confiança', para que ela seja formalmente informada sobre essa designação e suas possíveis responsabilidades. |
    | Critérios de Aceitação | - Ao concluir o cadastro de uma nova "Pessoa de Confiança" com um número de telefone celular válido, um SMS é disparado automaticamente para o número fornecido. <br> - A mensagem SMS deve ter um conteúdo padrão, informando ao destinatário que foi adicionado(a) como Pessoa de Confiança no aplicativo Celular Seguro (o conteúdo exato deve ser definido e aprovado). <br> - Em caso de falha no envio do SMS (ex: número inválido, falha no gateway), o sistema deve registrar a falha. |
    | Rastreabilidade        | [RNF08 Questionario](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/) |
    | Prioridade             | Alta |

    <font size="3"><p style="text-align: center">Fonte: [Felipe das Neves](https://github.com/FelipeFreire-gf).</p></font>

    </center>

### US32 - Cadastrar contatos com base nos números já existentes no celular (não implementado)

??? abstract "Tabela 34 - Cadastrar contatos com base nos números já existentes no celular (não implementado)"

    <center>

    <font size="3"><p style="text-align: center">Tabela 34 - Cadastrar contatos com base nos números já existentes no celular (não implementado).</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US32               | Cadastrar contatos com base nos números já existentes no celular |
    | Descrição              | Eu, como usuário do aplicativo Celular Seguro, desejo poder selecionar um contato diretamente da agenda do meu celular ao cadastrar uma Pessoa de Confiança, para agilizar o processo, evitar erros de digitação e tornar o cadastro mais conveniente. |
    | Critérios de Aceitação | - Ao iniciar o processo de cadastro de uma nova Pessoa de Confiança, o aplicativo deve apresentar uma opção clara para 'Buscar na agenda' ou 'Selecionar dos contatos'. <br> - Ao escolher essa opção, o aplicativo deve solicitar permissão ao usuário para acessar os contatos do dispositivo, se essa permissão ainda não tiver sido concedida. <br> - Se o usuário negar a permissão, ele deve ser informado sobre a impossibilidade de usar a funcionalidade e ter a opção de prosseguir com o cadastro manual. <br> - Com a permissão concedida, o aplicativo deve exibir uma lista de contatos da agenda do dispositivo, permitindo que o usuário role e/ou pesquise para encontrar o contato desejado.|
    | Rastreabilidade        | Vídeo de validação da entrevista 6 |
    | Prioridade             | Alta |

    <font size="3"><p style="text-align: center">Fonte: [Felipe das Neves](https://github.com/FelipeFreire-gf).</p></font>

    </center>

### US33 - Cadastrar manualmente uma nova Pessoa de Confiança

??? abstract "Tabela 35 - Cadastrar manualmente uma nova Pessoa de Confiança"

    <center>

    <font size="3"><p style="text-align: center">Tabela 35 - História de Usuário [Título da US33].</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US33               | 	Cadastrar manualmente uma nova Pessoa de Confiança |
    | Descrição              | 	Eu, como usuário do aplicativo Celular Seguro, desejo poder inserir manualmente os dados de uma Pessoa de Confiança (como nome e telefone), para registrá-la no sistema mesmo que ela não esteja na minha agenda ou eu prefira não importar os dados. |
    | Critérios de Aceitação | - Na tela "Pessoa de Confiança", deve existir um botão ou opção clara para "+ Cadastrar Contato". <br> - Ao acionar a opção de cadastrar, o usuário deve ser direcionado para um formulário com campos para, no mínimo, Nome e Número de Telefone da Pessoa de Confiança. <br>  |
    | Rastreabilidade        | Vídeo de validação da entrevista 6 |
    | Prioridade             | Alta |

    <font size="3"><p style="text-align: center">Fonte: [Felipe das Neves](https://github.com/FelipeFreire-gf).</p></font>

    </center>

### US34 - Visualizar lista de Pessoas de Confiança cadastradas

??? abstract "Tabela 36 - Visualizar lista de Pessoas de Confiança cadastradas"

    <center>

    <font size="3"><p style="text-align: center">Tabela 36 - Visualizar lista de Pessoas de Confiança cadastradas.</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US34               | Visualizar lista de Pessoas de Confiança cadastradas |
    | Descrição              | Eu, como usuário do aplicativo Celular Seguro, desejo poder visualizar uma lista clara e organizada com todas as minhas Pessoas de Confiança já cadastradas, para que eu possa rapidamente identificar quem são e acessar opções de gerenciamento para elas. |
    | Critérios de Aceitação | - Ao acessar a funcionalidade "Pessoa de Confiança", se houver contatos previamente cadastrados, eles devem ser exibidos em formato de lista. <br> - Cada item na lista deve apresentar informações chave da Pessoa de Confiança, como Nome e, opcionalmente, parte do telefone ou um avatar/ícone distintivo. <br> - Se não houver nenhuma Pessoa de Confiança cadastrada, a mensagem "Nenhum registro encontrado" (ou similar) deve ser exibida, acompanhada de uma sugestão ou botão para adicionar um novo contato. |
    | Rastreabilidade        | Vídeo de validação da entrevista 6 |
    | Prioridade             | Alta |

    <font size="3"><p style="text-align: center">Fonte: [Felipe das Neves](https://github.com/FelipeFreire-gf).</p></font>

    </center>

### US35 - Pesquisar uma Pessoa de Confiança específica na lista

??? abstract "Tabela 37 - Pesquisar uma Pessoa de Confiança específica na lista"

    <center>

    <font size="3"><p style="text-align: center">Tabela 37 - Pesquisar uma Pessoa de Confiança específica na lista.</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US35               | Pesquisar uma Pessoa de Confiança específica na lista |
    | Descrição              | Eu, como usuário do aplicativo Celular Seguro que possui várias Pessoas de Confiança cadastradas, desejo poder pesquisar por um nome ou telefone na minha lista, para localizar rapidamente um contato específico sem precisar percorrer toda a lista manualmente. |
    | Critérios de Aceitação | - Na tela "Pessoa de Confiança", um campo de busca "Pesquisar contato" deve estar disponível e funcional. <br> - Conforme o usuário digita no campo de busca (ex: nome, parte do nome, número de telefone), a lista de Pessoas de Confiança deve ser filtrada em tempo real para exibir apenas os contatos que correspondem ao critério da pesquisa. <br> - A pesquisa deve ser, preferencialmente, insensível a maiúsculas/minúsculas e acentos. <br> - Se a pesquisa não retornar nenhum resultado, uma mensagem como "Nenhum contato encontrado para '[termo pesquisado]'" deve ser exibida.|
    | Rastreabilidade        | Vídeo de validação da entrevista 6 |
    | Prioridade             | Média |

    <font size="3"><p style="text-align: center">Fonte: [Felipe das Neves](https://github.com/FelipeFreire-gf).</p></font>

    </center>

### US36 - Remover uma Pessoa de Confiança da lista

??? abstract "Tabela 38 - Remover uma Pessoa de Confiança da lista"

    <center>

    <font size="3"><p style="text-align: center">Tabela 38 - Remover uma Pessoa de Confiança da lista.</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US36               | Remover uma Pessoa de Confiança da lista |
    | Descrição              | Eu, como usuário do aplicativo Celular Seguro, desejo poder remover uma Pessoa de Confiança cadastrada que não é mais relevante ou apropriada, para manter minha lista de contatos de emergência sempre atualizada. |
    | Critérios de Aceitação | - Para cada Pessoa de Confiança listada, deve haver uma opção acessível para iniciar o processo de remoção (ex: um ícone de lixeira, um menu de opções ao manter pressionado). <br> - Antes da remoção efetiva, o sistema deve exibir uma mensagem de confirmação ao usuário, perguntando se ele realmente deseja remover "[Nome da Pessoa de Confiança]". <br> - Se o usuário confirmar a remoção, a Pessoa de Confiança selecionada deve ser permanentemente excluída do sistema. <br> - Após a remoção, a lista de Pessoas de Confiança deve ser atualizada automaticamente, não exibindo mais o contato removido. <br> - Se o usuário cancelar a ação na etapa de confirmação, a Pessoa de Confiança não deve ser removida e deve permanecer na lista.|
    | Rastreabilidade        | Vídeo de validação da entrevista 6  |
    | Prioridade             | Alta |

    <font size="3"><p style="text-align: center">Fonte: [Felipe das Neves](https://github.com/FelipeFreire-gf).</p></font>

    </center>


<p style="text-align: center">Entrevista 6</p>

<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/ucqJMH2Jt9U" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</center>

<p style="text-align: center">Caso não abra <a href="https://youtu.be/ucqJMH2Jt9U" target="blanket">clique aqui</a></p>

<font size="3"><p style="text-align: center">Fonte: [Felipe das Neves](https://github.com/FelipeFreire-gf)</p></font>

---

### US37 - [Título da US37]

??? abstract "Tabela 39 - História de Usuário [Título da US37]"

    <center>

    <font size="3"><p style="text-align: center">Tabela 39 - História de Usuário [Título da US37].</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US37               |  |
    | Descrição              |  |
    | Critérios de Aceitação |  |
    | Rastreabilidade        |  |
    | Prioridade             |  |

    <font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

    </center>

### US38 - [Título da US38]

??? abstract "Tabela 40 - História de Usuário [Título da US38]"

    <center>

    <font size="3"><p style="text-align: center">Tabela 40 - História de Usuário [Título da US38].</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US38               |  |
    | Descrição              |  |
    | Critérios de Aceitação |  |
    | Rastreabilidade        |  |
    | Prioridade             |  |

    <font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

    </center>

### US39 - [Título da US39]

??? abstract "Tabela 41 - História de Usuário [Título da US39]"

    <center>

    <font size="3"><p style="text-align: center">Tabela 41 - História de Usuário [Título da US39].</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US39               |  |
    | Descrição              |  |
    | Critérios de Aceitação |  |
    | Rastreabilidade        |  |
    | Prioridade             |  |

    <font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

    </center>

### US40 - [Título da US40]

??? abstract "Tabela 42 - História de Usuário [Título da US40]"

    <center>

    <font size="3"><p style="text-align: center">Tabela 42 - História de Usuário [Título da US40].</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US40               |  |
    | Descrição              |  |
    | Critérios de Aceitação |  |
    | Rastreabilidade        |  |
    | Prioridade             |  |

    <font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

    </center>

### US41 - [Título da US41]

??? abstract "Tabela 43 - História de Usuário [Título da US41]"

    <center>

    <font size="3"><p style="text-align: center">Tabela 43 - História de Usuário [Título da US41].</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US41               |  |
    | Descrição              |  |
    | Critérios de Aceitação |  |
    | Rastreabilidade        |  |
    | Prioridade             |  |

    <font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

    </center>

### US42 - [Título da US42]

??? abstract "Tabela 44 - História de Usuário [Título da US42]"

    <center>

    <font size="3"><p style="text-align: center">Tabela 44 - História de Usuário [Título da US42].</p></font>

    | **ID**                 | **Nome** |
    | :--------------------- | :-------- |
    | US42               |  |
    | Descrição              |  |
    | Critérios de Aceitação |  |
    | Rastreabilidade        |  |
    | Prioridade             |  |

    <font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

    </center>


<p style="text-align: center">Entrevista 7</p>

<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/gnieMHXL8Ek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</center>

<p style="text-align: center">Caso não abra <a href="https://youtu.be/gnieMHXL8Ek" target="blanket">clique aqui</a></p>

<font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258)</p></font>

---

## Bibliografia

> Cohn, M. (2004). User Stories Applied: For Agile Software Development. Addison-Wesley.

> Leffingwell, D. (2011). Agile Software Requirements: Lean Requirements Practices for Teams, Programs, and the Enterprise. Addison-Wesley.

> Schwaber, K., & Sutherland, J. (2020). The Scrum Guide. Scrum.org. Disponível em: https://scrumguides.org

> Sommerville, I. (2019). Software Engineering (10ª ed.). Pearson.

> Wiegers, K. E., & Beatty, J. (2013). Software Requirements (3ª ed.). Microsoft Press.

## Histórico de Versões

| Versão | Data de Produção | Descrição da Alteração | Autor(es) | Revisor(es) | Data de Revisão |
|:------:|:----------------:|:----------------------:|:---------:|:-----------:|:--------------:|
| 1.0 | 22/05/2025 | Versão inicial do documento | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a>, <a style="color:gold;" href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a> | 22/05/2025 |
| 1.1 | 30/05/2025 | Criação do scopo da documentação US | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | 30/05/2025 |
| 1.2 | 30/05/2025 | Criação dos US 19 a 24 | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | 30/05/2025 |
| 1.3 | 31/05/2025 | Criação dos US 13 a 18 | <a style="color:gold;" href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a> | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | 31/05/2025 |
| 1.4 | 31/05/2025 | Criação dos US 31 a 36 | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | <a style="color:gold;" href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a> | 31/05/2025 |
| 1.5 | 31/05/2025 | Criação dos US 00 a 06 | <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a> | <a style="color:gold;" href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a> | 31/05/2025 |
| 1.6 | 31/05/2025 | Padronização  | <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a> | <a style="color:gold;" href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a> | 31/05/2025 |

