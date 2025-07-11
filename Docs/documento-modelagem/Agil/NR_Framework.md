<span style="background-color:#2c2c7c; color:white; font-size:0.8em; font-weight: bold; padding:2px 6px; border-radius:4px;">Versão 2.1</span>

# NFR Framework

---

## Introdução

O NFR framework criado por (CHUNG et al., 2000), foi adotado por propor uma abordagem específica para o tratamento de Requisitos Não-Funcionais e fornecer uma execelente representação para expressar esses requisitos.

Este framework é utilizado neste trabalho para representar os requisitos não-funcionais conforme sua priorização neste [artefato](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_priorizados/), onde estes requisitos serão expressados através de um grafo SIG (Softgoal Interdependency Graph) uma forma de visualização do NFR framework.

!!! Warning "Atenção!"
    O conteúdo deste tópico **poderá sofrer alterações** ao longo da Disciplina de Requisitos de Software. Portanto, as tabelas serão organizadas iniciando pela versão mais recente e finalizando com a versão mais antiga.

## Integrantes que atuaram no desenvolvimento do artefato

Esta tabela inicial terá somente os artefatos de alta relevância que cada integrante do projeto desenvolveu. O versionamento **completo** encontra-se ao final do artefato.

<font size="3"><p style="text-align: center">_Tabela de Contribuição_</p></font>

| Nome | Função |
| :--- | :--- |
| [<span style="color:gold;">Felipe Freire</span>](https://github.com/FelipeFreire-gf) | Autor da Introdução, Metodologia, NFR Geral, NFR Usabilidade e Acessibilidade: [[ Figura 9 ]](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-05-acessibilidade), [[ Figura 10 ]](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-06-completo) e fez 2 cartões de especificação|
| [<span style="color:gold;">Mateus Bastos</span>](https://github.com/MateuSansete) | Autor dos NFRs de Confiabilidade e Segurança figura "SIG Adaptado" e: [[ Figura 8 ]](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-04-seguranca), [[ Figura 6 ]](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-02-confiabilidadeo), fez 2 cartões de especificação  e revisou o artefato|
| [<span style="color:gold;">Daniel Rodrigues</span>](https://github.com/zDrNz) | Autor dos NFRs de Desempenho figura "SIG Adaptado" e: [[ Figura 7 ]](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/NR_Framework/#nfr-03-desempenho) e fez 2 cartões de especificação |
| [<span style="color:gold;">Vitor Pereira</span>](https://github.com/Bessazs) | Autor de 2 cartões de especificação |
| [<span style="color:gold;">Gabriel Lima</span>](https://github.com/gabriel-lima258) | Autor de 2 cartões de especificação |
| [<span style="color:gold;">Leonardo de Melo</span>](https://github.com/leozinlima) | Autor de 2 cartões de especificação |
| [<span style="color:gold;">Arthur Carvalho</span>](https://github.com/arthurlleite) | Autor de 2 cartões de especificação |

*Legenda:* 

**Nome** – participante da técnica. 

**Função** – papel desempenhado na priorização. 

!!! Tip "Observação"
    Frizando claramente que as contribuições de cada integrante ainda que mínimas são ainda sim muito relevantes no desenvolvimento do artefo, considere verificar o histórico de versão. 

---

## Softgoal Interdependency Graph

O **Softgoal Interdependency Graph (SIG)** é uma representação visual do funcionamento do NFR Framework. Ele serve para registrar graficamente o posicionamento da equipe de desenvolvimento em relação aos softgoals (objetivos não funcionais) e demonstrar, de forma clara, as interdependências entre eles.

---

### Tipos de Softgoal

Para entender o SIG, é essencial compreender o que é um NFR Softgoal: trata-se de um objetivo que não possui critérios de satisfação claramente definidos. Em outras palavras, é uma meta abstrata, cuja realização é avaliada posteriormente.

Esses softgoals podem assumir formas distintas:

- **Softgoals NFR**: são metas genéricas como segurança, usabilidade ou desempenho.
- **Softgoals de Operacionalização**: representam maneiras concretas de atingir um softgoal abstrato, podendo ser tratados como funcionalidades do sistema.
- **Softgoals de Afirmação**: são declarações em linguagem natural que reforçam ou justificam determinadas decisões no modelo.

A Figura 1 ilustra esses diferentes tipos de softgoal.

<font size="3"><p style="text-align: center"><b>Figura 1</b> - Tipos de Softgoal</p></font>
<figure markdown class="usecaseElement">

![TIPOS](../../assets/nfr/tipos.png){width: 300}

</figure>
<font size="3"><p style="text-align: center"> Fonte: (SILVA, 2019)</p></font>

---

### Interdependências

As interdependências representam as conexões entre os softgoals e podem ser divididas em duas categorias principais: **decomposições** e **contribuições**.

#### Decomposições

Decomposições são divisões de softgoals em partes menores, podendo ocorrer em todos os níveis: softgoals NFR, de operacionalização ou de afirmação. Elas ajudam a esclarecer objetivos e detalhar soluções. Existem quatro tipos principais:

- **Decomposição NFR**: permite subdividir grandes metas em componentes mais simples e claros, facilitando a priorização.
- **Decomposição de Operacionalização**: especifica uma solução genérica em soluções mais detalhadas.
- **Decomposição de Afirmação**: reforça ou refuta argumentos utilizados no projeto.
- **Decomposição de Priorização**: especial, pois refina um softgoal em outro de mesma natureza, atribuindo, porém, diferentes prioridades.

<font size="3"><p style="text-align: center"><b>Figura 2</b> - Tipos de Decomposição</p></font>
<figure markdown class="usecaseElement">

![DECOMPOSIÇÃO](../../assets/nfr/decompL.png){width: 300}

</figure>
<font size="3"><p style="text-align: center"> Fonte: (SILVA, 2019)</p></font>

---

#### Contribuições

No modelo NFR, os softgoals podem influenciar outros — essa influência pode ser positiva ou negativa, total ou parcial. Os principais tipos de contribuição são:

- **AND**: todos os sub-softgoals precisam ser satisfeitos para que o objetivo principal seja alcançado.
- **OR**: basta que um dos sub-softgoals seja satisfeito.
- **MAKE (++)**: contribuição fortemente positiva.
- **BREAK (--)**: contribuição fortemente negativa.
- **HELP (+)**: contribuição positiva parcial.
- **HURT (-)**: contribuição negativa parcial.
- **UNKNOWN (?)**: o tipo de contribuição é desconhecido.
- **EQUALS**: existe uma equivalência entre a satisfação dos softgoals.
- **SOME**: sabe-se a direção da contribuição, mas não sua intensidade.

---

### Propagação de Impactos

A propagação de impactos diz respeito à forma como alterações em um softgoal podem influenciar outros requisitos não funcionais interligados. Compreender essas relações é crucial para avaliar prioridades, resolver conflitos e tomar decisões mais embasadas.

Os impactos podem ser representados por:

- **✓ (satisfeito)**: contribuição positiva direta.
- **𝒲+ (fracamente satisfeito)**: impacto positivo, mas com menor intensidade.
- **X (negado)**: impacto negativo que inviabiliza outro requisito.
- **𝒲- (fracamente negado)**: impacto negativo moderado.
- **🗲 (conflitante)**: existe um conflito entre os objetivos, com efeitos positivos e negativos simultâneos.
- **u (indeterminado)**: não há informações suficientes para avaliar o impacto.

---

## Metodologia

Cada integrante do projeto obteve dois requisitos não-funcionais obtido através das técnicas de [priorização](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/introducao) e validados com um usuário do aplicativo, onde cada integrante fez de forma remota ou presencial. Houve também uma criterização a respeito de cada funcionalidade do aplicativo que cada integrante ficou responsável que pode ser analisada na tabela 0 a seguir:

<font size="3"><p style="text-align: center">Tabela 0: Separação das Funcionalidades do aplicativo por integrante</p></font>

| Funcionalidade                | Integrante Responsável |
|-------------------------------|------------------------|
| Registrar Telefone            | Arthur                 |
| Registrar Pessoa de Confiança | Felipe                 |
| Emitir Alerta                 | Daniel                 |
| Celulares com Restrição       | Gabriel                |
| Registrar Boletim             | Mateus                 |
| Perfil                        | Leonardo               |
| Buscar Dispositivo            | Vitor                  |

<font size="3"><p style="text-align: center">Autor: <a href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a></p></font>

---

## Cartão de Especificação

Os cartões de especificação a seguir, Tabelas de 1 a 6, foram utilizados para definir os Requisitos Não-Funcionais a serem utilizados na confecção dos NFR Frameworks. 


<font size="3"><p style="text-align: center">Tabela 1: Cartão de Especificação (Boletim de ocorrência - Usabilidade)</p></font>

| Campo               | RNF01                                                                                                   |
|---------------------|--------------------------------------------------------------------------------------------------------|
| **Nº Requisito:**        | 1                                                                                                  |
| **Classificação:**       | Usabilidade                                                                                            |
| **Descrição:**           | O sistema deve apresentar a confirmação de envio do boletim com linguagem clara e acessível, incluindo número de protocolo visível por no mínimo 10 segundos. |
| **Justificativa:**       | Garantir que o usuário compreenda que o boletim foi enviado com sucesso e que possa anotar ou copiar o número de protocolo sem pressa, melhorando a experiência e a confiança no sistema. |
| **Origem do Requisito:** | Entrevista com usuário (Arthur)                                                                        |
| **Critério de Aceitação:** | Após o envio do boletim, o número de protocolo deve ser exibido em destaque, com opção de cópia e visibilidade mínima de 10 segundos. |
| **Dependências:**        | Envio bem-sucedido do boletim de ocorrência                                                           |
| **Prioridade:**          | Alta                                                                                            |
| **Conflitos:**           | Nenhum                                                                                                |
| **História:**            |[US12](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us12-notificacao-de-confirmacao-apos-envio-do-boletim)
  



<font size="3"><p style="text-align: center">Tabela 2: Cartão de Especificação (Boletim de ocorrência - Desempenho e Confiabilidade)</p></font>

| Campo               | RNF02                                                                                                   |
|---------------------|--------------------------------------------------------------------------------------------------------|
| **Nº Requisito:**         | 2                                                                                                  |
| **Classificação:**        | Desempenho / Confiabilidade                                                                             |
| **Descrição:**            | O sistema deve permitir o envio de anexos com limite máximo de 10 MB por arquivo, aceitando os formatos JPG, PNG e PDF. |
| **Justificativa:**        | Evitar sobrecarga no sistema e garantir que os arquivos anexados sejam compatíveis e leves o suficiente para envio eficiente e seguro. |
| **Origem do Requisito:**  | Entrevista com usuário (Arthur) e análise técnica                                                      |
| **Critério de Aceitação:** | O sistema deve bloquear arquivos que ultrapassem o limite ou estejam em formato não aceito, exibindo mensagem clara e impedindo o envio. |
| **Dependências:**         | Funcionalidade de envio de boletim com anexos                                                          |
| **Prioridade:**           | Média                                                                                            |
| **Conflitos:**            | Nenhum                                                                                                |
| **História:**             |   [US08](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-modelagem/Agil/Historias_de_usuario/#us07-confirmar-envio-do-boletim-com-protocolo-visivel)

<font size="3"><p style="text-align: center">Autor: <a href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a></p></font>

As tabelas 3 e 4 são referentes a funcionalidade de Resgistrar pessoa de confiança. Critério do QFD para a criterização da prioridade, aliada os RNFs obtidos do questionário.

<font size="3"><p style="text-align: center">Tabela 3: Cartão de Especificação (Pessoa de confiança - Funcionalidade)</p></font>

| Campo               | RNF03                                                                                                   |
|---------------------|--------------------------------------------------------------------------------------------------------|
| **Nº Requisito:**          | 3                                                                                                 |
| **Classificação:**         | Funcionalidade                                                                       |
| **Descrição:** | Para cada Pessoa de Confiança listada, deve haver uma opção acessível para iniciar o processo de remoção (ex: um ícone de lixeira, um menu de opções ao manter pressionado). |
| **Justificativa:** | Permitir que o usuário mantenha sua lista de Pessoas de Confiança atualizada e relevante, removendo contatos que não são mais desejados ou apropriados para essa função, assegurando que apenas as pessoas corretas permaneçam com esse status. |
| **Origem do Requisito:** | Definição da Funcionalidade 'Gerenciar Pessoas de Confiança' / User Story US36 |
| **Critério de Aceitação:** | Para cada contato exibido na lista de Pessoas de Confiança, uma opção de remoção (ex: ícone de lixeira ou item em menu de contexto) deve estar acessível. Ao ser acionada, o sistema deve solicitar confirmação ao usuário e, se confirmada, o contato deve ser removido permanentemente do sistema e a lista atualizada. |
| **Dependências:** | Pessoas já cadastradas na lista de confiança |
| **Prioridade:** | Alta  |
| **Conflitos:** | Nenhum conflito direto identificado. O risco de remoção acidental deve ser mitigado pela etapa de confirmação. |
| **História:** |  <a href="../Historias_de_usuario#us36">US36</a> |

<font size="3"><p style="text-align: center">Autor: <a href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a></p></font>


<font size="3"><p style="text-align: center">Tabela 4: Cartão de Especificação (Acessibilidade - Dark Mode)</p></font>

| Campo               | RNF04                                                                                                   |
|---------------------|--------------------------------------------------------------------------------------------------------|
| **Nº Requisito:**          | 4                                                                                                 |
| **Classificação:**         | Usabilidade / Acessibilidade / Funcionalidade                                                                        |
| **Descrição:** | O aplicativo deve oferecer um modo escuro (dark mode) para maior conforto visual.|
| **Justificativa:** |  Proporcionar uma melhor experiência de uso em ambientes com pouca luminosidade, reduzir o cansaço visual, atender às preferências de uma parcela de usuário, mesmo que esse requisito tenha sido verificado apenas para a funcionalidade: Registrar pessoa de confiança, tal requisito se extende ou sistema completo.|
| **Origem do Requisisto:** | Obtido da técnica de elicitação do questionário: [RNF05](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/)|
| **Critério de Aceitação:** | O aplicativo deve possuir uma opção nas configurações que permita ao usuário alternar entre o tema claro (padrão) e o modo escuro. Todos os textos, ícones e elementos interativos devem manter boa legibilidade e contraste adequado no modo escuro, conforme as diretrizes de acessibilidade (ex: WCAG AA). A transição entre os modos deve ser suave e todas as telas do aplicativo devem ser compatíveis.|
| **Dependências:** | Definição da paleta de cores para o modo claro e escuro. |
| **Prioridade:** | Baixa                                                                                 |
| **Conflitos:** | Nenhum                           |
| **História:** | 30/06/2025 |

<font size="3"><p style="text-align: center">Autor: <a href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a></p></font>

---

As tabelas 5 e 6 descrevem, respectivamente, o RNF de manter o layout da tela de Perfil consistente com o restante do app e o RNF de oferecer alto contraste e fonte ajustável, ambos priorizados para melhorar usabilidade e acessibilidade.

<font size="3"><p style="text-align: center">Tabela 5: Cartão de Especificação (Perfil – Layout Consistente)</p></font>

| Campo               | RNF05                                                                                                   |
|---------------------|--------------------------------------------------------------------------------------------------------|
| **Nº Requisito:**          | 5                                                                                                 |
| **Classificação:**         | Usabilidade / Aparência                                                                          |
| **Descrição:**             | A tela de Perfil deve ter o mesmo visual e organização que as outras telas do aplicativo. Isso inclui posição de título, espaçamento, cores e tamanho de texto. |
| **Justificativa:**         | Usar o mesmo padrão em todas as telas faz com que o usuário saiba onde estão as informações e botões, evitando confusão e facilitando o uso. |
| **Origem:**                | [BS38](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-nao-funcionais) |
| **Critério de Aceitação:** | 1. O título “Perfil” aparece com a mesma fonte e cor que os títulos de outras páginas.<br>2. Foto, nome, e-mail e botão “Editar Perfil gov.br” ocupam posições semelhantes às de outras telas.<br>3. Botões na tela de Perfil têm aparência e comportamento iguais aos da Home e Configurações (mesma cor e feedback ao clicar).<br>4. Espaços entre elementos seguem o guia de estilo do aplicativo (distâncias iguais às de outras telas). |
| **Dependências:**          | Guia de estilo do app (cores, fontes, espaçamentos) aprovado pela equipe de design. |
| **Prioridade:**            | Média  |
| **Conflitos:**             | Se for necessário adicionar novos elementos (gráficos, listas), será preciso ajustar o layout sem perder a consistência. |
| **História:**              | <a href="../Historias_de_usuario#us14">US14</a>  |


<font size="3"><p style="text-align: center">Fonte: [Leonardo de Melo](https://github.com/leozinlima)</p></font>


<font size="3"><p style="text-align: center">Tabela 6: Cartão de Especificação (Perfil – Alto Contraste e Fonte Ajustável)</p></font>

| Campo               | RNF06                                                                                                   |
|---------------------|--------------------------------------------------------------------------------------------------------|
| **Nº Requisito:**       | 6                                                                                                 |
| **Classificação:**       | Acessibilidade / Legibilidade                                                                          |
| **Descrição:**             | A tela de Perfil deve oferecer opção de alto contraste e permitir aumentar ou reduzir o tamanho da fonte. |
| **Justificativa:**         | Isso ajuda quem tem dificuldade para enxergar letras pequenas ou usar o aplicativo em ambientes muito claros ou muito escuros. |
| **Origem:**                | [BS43](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-nao-funcionais) |
| **Critério de Aceitação:** | 1. Nas configurações, o usuário escolhe “Contraste Padrão” ou “Alto Contraste” e, imediatamente, a tela de Perfil muda as cores.<br>2. Nas configurações, o usuário escolhe “Fonte Pequena”, “Fonte Média” ou “Fonte Grande” e o texto do Perfil (nome, e-mail, botões) muda sem cortar nada.<br>3. No modo “Alto Contraste”, o texto e o fundo na tela de Perfil têm cores claramente diferentes para facilitar a leitura.<br>4. Ao mudar contraste ou fonte, a tela de Perfil atualiza em até 0,2 segundos, sem precisar fechar o aplicativo. |
| **Dependências:**          | Guia de cores para “Alto Contraste” e opções de tamanho de fonte definidas no guia de estilo. |
| **Prioridade:**            | Baixa |
| **Conflitos:**             | Se alguns ícones não tiverem versão para alto contraste, será necessário trocar esses ícones. Ajustar fonte para “Grande” pode exigir mais espaço na tela. |
| **História:**              | <a href="../Historias_de_usuario#us14">US14</a>  |


<font size="3"><p style="text-align: center">Fonte: [Leonardo de Melo](https://github.com/leozinlima)</p></font>

---

As Tabelas 7 e 8 apresentam os requisitos não funcionais (RNF) de usabilidade e segurança no menu "Registrar Telefone", com foco em interface intuitiva e criptografia dos dados, priorizados para garantir uma experiência confiável ao usuário.


<font size="3"><p style="text-align: center">Tabela 7: Cartão de Especificação (Registrar Celular – Acessibilidade e Estrutras Claras)</p></font>


| Campo               | RNF07                                                                                                   |
|---------------------|--------------------------------------------------------------------------------------------------------|
| **Nº Requisito:**       | 7                                                                                                  |
| **Classificação:**       | Usabilidade / Acessibilidade                                                                           |
| **Descrição:**           | O sistema deve apresentar menus e botões no módulo de Registro de Telefone com estrutura clara e uso de affordances visuais (ícones e feedback gráfico/textual) para indicar as ações disponíveis, como adicionar, editar ou remover um número , com a ideia principal focada no tempo de resposta para o usuário. |
| **Justificativa:**       | Facilitar o uso da funcionalidade por usuários de diferentes perfis (inclusive idosos e pessoas sob estresse), reduzindo ambiguidade visual,  evitando erros de uso ao registrar o telefone e ajustando o tempo de resposta visual mais criterioso. |
| **Origem do Requisito:** | [BS36](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais) |
| **Critério de Aceitação:** | O usuário deve conseguir realizar o cadastro ou exclusão de um telefone utilizando apenas os ícones e textos da interface, sem necessidade de tutorial, com confirmação visual imediata ao final de cada ação e com um tempo de resposta realtivamente bom ( entre 1.4 a 2.4 milesegundos). |
| **Dependências:**        | Tela de Registro de Telefone; Interface gráfica consistente                                             |
| **Prioridade:**          | Alta                                                                                               |
| **Conflitos:**           | Nenhum identificado                                                                                     |
| **História:**            | [US01](https://requisitos-de-software.github.io/2025.1-CelularSeguro/modelagem/#us01---cadastro-de-múltiplos-celulares), [US06](https://requisitos-de-software.github.io/2025.1-CelularSeguro/modelagem/#us06---validação-do-número-de-celular) |

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a></p></font>

---

<font size="3"><p style="text-align: center">Tabela 8: Cartão de Especificação (Registrar Celular – Segurança e Criptografia)</p></font>

| Campo               | RNF08                                                                                                   |
|---------------------|--------------------------------------------------------------------------------------------------------|
| **Nº Requisito:**   | 8                                                                                                      |
| **Classificação**   | Segurança / Confiabilidade                                                                             |
| **Descrição**       | O aplicativo deve garantir criptografia ponta-a-ponta (como AES-256) nos dados transmitidos e armazenados durante o processo de registro de telefone, incluindo o número, código de verificação e identificação do usuário. Nenhuma informação sensível deve ser transmitida em texto claro. |
| **Justificativa**       | Proteger os dados pessoais e garantir que o número de telefone cadastrado e validado não seja interceptado ou alterado por terceiros, alinhando-se à LGPD e às boas práticas de segurança da informação. |
| **Origem do Requisito** | [ADD15](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/) |
| **Critério de Aceitação** | Toda a comunicação relacionada ao registro de telefone deve utilizar protocolo HTTPS com TLS atualizado. As informações sensíveis devem ser criptografadas e não podem ser recuperadas por interceptação direta da rede. |
| **Dependências**       | Integração com servidor seguro e sistema de autenticação                                               |
| **Prioridade**       | Alta                                                                                             |
| **Conflitos**       | Nenhum                                                                                                  |
| **História**       | [US06](https://requisitos-de-software.github.io/2025.1-CelularSeguro/modelagem/#us06---validação-do-número-de-celular) |

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a></p></font>

As Tabelas 9 e 10 apresentam os requisitos não funcionais (RNF) de usabilidade e segurança no menu "Emitir Alerta".

<a id="rnf09"></a>
<font size="3"><p style="text-align: center">Tabela 9: Cartão de Especificação (Emitir alerta-Alerta e Bloqueio)</p></font>

| Campo                      | RNF09                                         |
| :------------------------- |                                                                  |
| **Nº Requisito:**          | 9                                                                                                            |
| **Classificação:**         | Desempenho                                                                                               |
| **Descrição:**             | O sistema deve comunicar alertas aos parceiros com o menor tempo possível, idealmente de forma instantânea. Além disso, bloqueios de sistema ou ações de segurança devem ser efetuados em até 2 minutos após a detecção do evento. |
| **Justificativa:**         | Em cenários críticos, como ameaças à segurança ou violação de dados, é essencial que o alerta seja comunicado imediatamente aos parceiros e que as ações preventivas (como bloqueios) ocorram em tempo adequado para mitigar riscos. |
| **Origem:**                | [OBS16](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/#requisitos-naofuncionais-rnf) |
| **Critério de Aceitação:** | 1. Alertas devem ser enviados em até 1 segundo após o evento.<br>2. Bloqueios devem ocorrer em até 2 minutos da detecção automática ou comando humano. |
| **Dependências:**          | Detecção de evento, canal de comunicação ativo. |
| **Prioridade:**            | Alta |
| **Conflitos:**             | Potencial impacto em consumo de rede e uso de CPU |
| **História:**              | 01/06/2025 |


<font size="3"><p style="text-align: center">Fonte: [Daniel Rodrigues](https://github.com/zDrNz)</p></font>


<font size="3"><p style="text-align: center">Tabela 10: Cartão de Especificação (Páginas-Tempo de Carregamento)</p></font>

| Campo                      | RNF10                                         |
| :------------------------- |                                                                  |
| **Nº Requisito:**          | 10                                                                                                  |
| **Classificação:**             | Desempenho                                                                                               |
| **Descrição:**             | As páginas do sistema devem carregar completamente em até 2 segundos quando acessadas via conexão padrão 4G. |
| **Justificativa:**         | Um tempo de carregamento rápido melhora a experiência do usuário, reduz abandono e é essencial em contextos móveis onde a responsividade é crítica. |
| **Origem:**                | [OBS16](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Observacao/#tabela-de-requisitos-nao-funcionais)  |
| **Critério de Aceitação:** | 1. Em testes com rede 4G padrão, 95% das páginas devem carregar em até 2 segundos. |
| **Dependências:**          | Otimização de backend, compactação de conteúdo, rede 4G disponível |
| **Prioridade:**            | Alta |
| **Conflitos:**             | Pode entrar em conflito com carregamento de recursos pesados (como gráficos) |
| **História:**              | 01/06/2025 |


<font size="3"><p style="text-align: center">Fonte: [Daniel Rodrigues](https://github.com/zDrNz)</p></font>

As Tabelas 11 e 12 apresentam os requisitos não funcionais (RNF) de usabilidade e segurança no menu "Buscar Aplicativo".

<font size="3"><p style="text-align: center">Tabela 11: Cartão de Especificação (Localização - Precisão da localização)</p></font>

| Campo               | RNF11                                                                                                  |
|---------------------|--------------------------------------------------------------------------------------------------------|
| **Nº Requisito:**   | 11                                                                                                  |
| **Classificação:**  |  Segurança                                                                           |
| **Descrição:**      |  O sistema deve fornecer informações de localização do dispositivo com alta precisão, garantindo que os dados exibidos representem fielmente o posicionamento real do dispositivo no mapa.  
| **Justificativa:**  |  Garantir a precisão da localização é fundamental para que funcionalidades como rastrear, bloquear ou recuperar o dispositivo sejam eficazes. Isso contribui diretamente para a confiança do usuário no sistema, reduzindo frustrações causadas por erros de posicionamento e garantindo a usabilidade do serviço, especialmente em situações críticas, como perda ou roubo do dispositivo. |
| **Origem do Requisito:**  |  [BS04](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais), [QS01](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#requisitos-elicitados), [ST6](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Storytelling/#tabela-de-requisitos-funcionais)   |
| **Critério de Aceitação:**  |  O sistema deve utilizar fontes de localização de alta precisão, como GPS, Wi-Fi e redes móveis, combinadas quando necessário. A margem de erro aceitável deve ser inferior a 10 metros em ambientes externos e tão precisa quanto possível em ambientes internos. A localização deve ser atualizada em tempo real ou com atraso máximo de 5 segundos. Além disso, o sistema deve informar claramente ao usuário se a precisão da localização está comprometida no momento. |
| **Dependências:**   |  Disponibilidade dos serviços de GPS, Wi-Fi e dados móveis no dispositivo e   Permissões de localização ativas no dispositivo. |
| **Prioridade:**     |  Alta                                                                                            |
| **Conflitos:**      |  Nenhum                                                                                                |
| **História:**       |  01/06/2025                                                                                           |

<font size="3"><p style="text-align: center">Fonte: [Vitor Bessa](https://github.com/Bessazs)</p></font>

<font size="3"><p style="text-align: center">Tabela 12: Cartão de Especificação (Localização- Segurança)</p></font>

| Campo               | RNF12                                                                                                  |
|---------------------|--------------------------------------------------------------------------------------------------------|
| **Nº Requisito:**   | 12                                                                                                  |
| **Classificação:**  |  Segurança                                                                         |
| **Descrição:**      |  Os dados de localização do dispositivo devem ser protegidos contra acessos não autorizados, utilizando criptografia tanto na transmissão quanto no armazenamento. |
| **Justificativa:**  | Informações de localização são altamente sensíveis, pois podem revelar a posição exata do usuário em tempo real. Proteger esses dados garante a privacidade, evita riscos de segurança pessoal e aumenta a confiança dos usuários no sistema. Além disso, estar em conformidade com leis de proteção de dados, como a LGPD, é essencial. |
| **Origem do Requisito:**  |  [BS04](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#tabela-de-requisitos-funcionais), [QS01](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#requisitos-elicitados), [ST6](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Storytelling/#tabela-de-requisitos-funcionais)   |
| **Critério de Aceitação:**  | - Todos os dados de localização devem ser criptografados em trânsito (durante a comunicação entre cliente e servidor) e em repouso (armazenados no servidor). <br> - O acesso às informações de localização deve ser restrito apenas aos usuários autenticados e autorizados. <br> - Caso haja tentativa de acesso não autorizado, o sistema deve bloquear a tentativa e registrar um log de segurança. <br> - O sistema deve fornecer ao usuário opções para gerenciar as permissões de compartilhamento da sua localização. |
| **Dependências:**   |  Implementação de protocolos de segurança e infraestrutura de backend compatível com armazenamento seguro (criptografia de banco de dados, gerenciamento de chaves). |
| **Prioridade:**     |  Alta                                                                                            |
| **Conflitos:**      |  Nenhum                                                                                                |
| **História:**       |  01/06/2025                                                                                           |

<font size="3"><p style="text-align: center">Fonte: [Vitor Bessa](https://github.com/Bessazs)</p></font>


<font size="3"><p style="text-align: center">Tabela 13: Cartão de Especificação (Controle de Acesso Seguro)</p></font>

| Campo                 | RNF13 |
|-----------------------|--------|
| **Nº Requisito:**     | 13 |
| **Classificação:**    | Segurança / Funcionalidade |
| **Descrição:**        | O sistema deve implementar controle de acesso baseado em papéis (RBAC), limitando funcionalidades conforme o tipo de usuário (usuário comum, pessoa de confiança, administrador), impedindo o acesso indevido mesmo por rotas alternativas. |
| **Justificativa:**    | Garantir que apenas usuários autorizados possam acessar funcionalidades sensíveis é essencial para prevenir ações indevidas, vazamento de dados e garantir o princípio do menor privilégio, reforçando a segurança do sistema. |
| **Origem do Requisito:** | Técnicas de brainstorming e análise de documentos de sistemas similares com perfis diferenciados de usuário. Também motivado pela revisão de qualidade solicitada pelo professor. |
| **Critério de Aceitação:** | O sistema deve: <br> - Ter ao menos três níveis de permissão: usuário comum, pessoa de confiança e administrador;<br> - Restringir funcionalidades conforme o perfil;<br> - Impedir o acesso por manipulação de interface ou chamadas diretas a URLs;<br> - Exibir mensagens de erro claras quando o acesso for negado. |
| **Dependências:**     | RNF04 (Segurança), RNF08 (Autenticação), RF relacionados ao login e uso de funcionalidades sensíveis |
| **Prioridade:**       | Alta |
| **Conflitos:**        | Pode afetar a usabilidade caso o controle seja excessivamente restritivo ou mal comunicado ao usuário. |
| **História:**         | Criado em 05/07/2025 para complementar o RNF07, conforme revisão docente sobre clareza e verificabilidade dos artefatos de segurança. |

<font size="3"><p style="text-align: center">Fonte: [Mateus Bastos](https://github.com/MateuSansete)</p></font>


<font size="3"><p style="text-align: center">Tabela 14: Cartão de Especificação (Autenticação Segura)</p></font>

| Campo                 | RNF14 |
|-----------------------|--------|
| **Nº Requisito:**     | 14 |
| **Classificação:**    | Segurança / Funcionalidade |
| **Descrição:**        | O sistema deve implementar mecanismos de autenticação segura, incluindo senha forte e autenticação em dois fatores (2FA), para proteger o acesso às funcionalidades sensíveis do aplicativo. |
| **Justificativa:**    | A autenticação é a primeira barreira de defesa do sistema. Garantir que apenas usuários legítimos acessem o sistema protege informações pessoais e reduz o risco de invasões, fraudes e uso indevido. |
| **Origem do Requisito:** | Técnicas de brainstorming e análise de aplicativos com autenticação robusta (ex: Signal, Telegram). Revisado após recomendação do professor. Substitui o RNF08. |
| **Critério de Aceitação:** | O sistema deve:<br> - Solicitar senha forte (mínimo de 8 caracteres, com letras, números e símbolo);<br> - Oferecer autenticação em dois fatores (2FA) nas funcionalidades críticas, como envio de alerta e alteração de dados de confiança;<br> - Realizar bloqueio temporário após 5 tentativas falhas de login;<br> - Exibir mensagens claras para erros de autenticação. |
| **Dependências:**     | RNF04 (Segurança), RNF13 (Controle de Acesso Seguro) |
| **Prioridade:**       | Alta |
| **Conflitos:**        | Pode impactar a usabilidade se os métodos forem excessivamente rigorosos ou mal explicados. |
| **História:**         | Criado em 05/07/2025 como versão revisada e técnica do RNF08 – Autenticação. |

<font size="3"><p style="text-align: center">Fonte: [Mateus Bastos](https://github.com/MateuSansete)</p></font>

---

### Vídeo de Validação com o Usuário

<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/aKZyAkc5Bms" title="Vídeo de Validação - Registrar Telefone" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</center>

<p style="text-align: center">Caso o vídeo não carregue, <a href="https://youtu.be/aKZyAkc5Bms" target="_blank">clique aqui para assistir no YouTube</a>.</p>

---

### Termo de Compromisso Assinado

> **PDF – 01/06/2025 – Termo de Compromisso e Imagem Assinado**  
> Arquivo disponível em: [Cópia do Termo de Consentimento Celular Seguro (PDF)](https://github.com/Requisitos-de-Software/2025.1-CelularSeguro/blob/main/Docs/assets/pdf/verificacao/Copia_de_Termo_Consentimento_CelularSeguro_assinado%20(1).pdf)

## NFR 0 - Geral

A Figura 2 a seguir demonstra o Softgoal Interdependency Graph para se ter uma visão geral.

<font size="3"><p style="text-align: center"><b>Figura 2</b> - SIG Geral</p></font>


![SIG GERAL](../../assets/nfr/geralL.png)

<font size="3"><p style="text-align: center">Fonte: (SILVA, 2019)</p></font>

No entanto, como o foco é trabalhar apenas com Requisitos Não-Funcionais ainda não implementados pelo aplicativo, adaptou-se o SIG acima para a utilização dos tópicos necessários, conforme a figura 3:

<font size="3"><p style="text-align: center"><b>Figura 3</b> - SIG Geral Adaptado</p></font>


![SIG GERAL](../../assets/nfr/geralAdaptado.jpeg)

<font size="3"><p style="text-align: center">Fonte: (SILVA, 2019)</p></font>

---

Legendas estão conforma a figura 4:

<font size="3"><p style="text-align: center"><b>Figura 4</b> - Legendas SIG </p></font>


![SIG GERAL](../../assets/nfr/legendas.jpeg)

<font size="3"><p style="text-align: center">Fonte: (SILVA, 2019)</p></font>


## NFR 01 - Usabilidade

Diagrama de SIG de usabilidade, figura 5:

<font size="3"><p style="text-align: center"><b>Figura 5</b> SIG Usabilidade</p></font>


<center>
  <span style="background-color:#c5a352; color:white; font-size:0.8em; font-weight: bold; padding:2px 6px; border-radius:4px;"> Refatoração até 07/07 | Versão 2.0</span>
</center>

![SIG GERAL](../../assets/nfr/usabilidade23.png)

<font size="3"><p style="text-align: center">Autor: Felipe das Neves</p></font>



---

### Requisitos Não-Funcionais - Usabilidade 

<font size="3"><p style="text-align: center">Tabela 13 - Requisitos Não-Funcionais: Usabilidade (Baseada no Modelo Goal-Oriented)</p></font>




| Código Original (se aplicável) | Nome do Softgoal / Operacionalização | Descrição / Detalhes de Implementação | Tipo de Elemento (Nuvem) |
| :----------------------------- | :----------------------------------- | :------------------------------------ | :----------------------- |
| -                              | **Usabilidade** | O objetivo geral de facilidade de uso e satisfação do usuário com o aplicativo. | Normal                   |
| -                              | **Conforto Visual** | Garantir que a interface seja agradável e reduza a fadiga ocular do usuário. | Normal                   |
| -                              | **Satisfação do Usuário** | Atender às expectativas e preferências dos usuários, contribuindo para uma experiência positiva. | Normal                   |
| -                              | **Acessibilidade** | Garantir que o aplicativo seja utilizável por pessoas com diferentes habilidades e necessidades. | Normal                   |
| RNF04                          | **Oferecer Modo Escuro (Dark Mode)** | O aplicativo deve oferecer um modo escuro para maior conforto visual, incluindo todos os textos, ícones e elementos interativos com legibilidade e contraste adequados. A transição deve ser suave e todas as telas compatíveis. | Borda Grossa (Operacionalização) |
| -                              | Alternar Tema (RNF04.1)              | O aplicativo deve possuir uma opção nas configurações para alternar entre os temas claro e escuro. | Normal                   |
| -                              | Legibilidade e Contraste Adequados (RNF04.2) | Todos os elementos visuais devem manter boa legibilidade e contraste no modo escuro, conforme diretrizes de acessibilidade (ex: WCAG AA). | Normal                   |
| -                              | Transição Suave (RNF04.3)            | A mudança entre os modos claro e escuro deve ocorrer de forma fluida. | Normal                   |
| -                              | Compatibilidade entre Telas (RNF04.4)| Todas as telas do aplicativo devem ser compatíveis com o modo escuro. | Normal                   |
| -                              | **Paleta de Cores Definida** | Definição prévia da paleta de cores para os modos claro e escuro, essencial para legibilidade. | Tracejada (Dependência/Afirmação) |
| US36                           | **Confirmação Clara e Acessível de Envio** | O sistema deve apresentar a confirmação de envio do boletim com linguagem clara e acessível, incluindo número de protocolo visível por no mínimo 10 segundos. | Normal (Operacionalização) |
| US01, US06                     | **Clareza e Responsividade em Menus/Botões (Registro)** | O sistema deve apresentar menus e botões no módulo de Registro de Telefone com estrutura clara e uso de affordances visuais (ícones e feedback gráfico/textual), focado no tempo de resposta. | Normal (Operacionalização) |

<font size="3"><p style="text-align: center">Fonte: <a style="color:white blue;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a></p></font>

### Propagação dos Impactos - Usabilidade 

A tabela 14 a seguir detalha os softgoals de Usabilidade e como os requisitos e operacionalizações específicas impactam esses objetivos, incluindo as conotações de impacto e rótulos de satisfação conforme definidos no modelo Goal-Oriented.


<font size="3"><p style="text-align: center">Tabela 14 - Propagação dos Impactos: Usabilidade</p></font>

| NFR / Softgoal / Operacionalização | Rótulo/Status Avaliado | Contribuição de/para | Avaliador | Prioridade (se aplicável) |
| :--------------------------------- | :--------------------- | :------------------- | :-------- | :------------------------ |
| **Usabilidade** | U                      | -                    | Felipe das Neves | -                         |
| `-- (++) --> Conforto Visual`    | W+                     | `De:` Usabilidade    | Felipe das Neves | -                         |
| `-- (++) --> Satisfação do Usuário` | W+                     | `De:` Usabilidade    | Felipe das Neves | -                         |
| `-- (++) --> Acessibilidade`     | W+                     | `De:` Usabilidade    | Felipe das Neves | -                         |
| **Oferecer Modo Escuro (Dark Mode)** | W+ (Operacionalização) | `Para:` Conforto Visual (++) / Satisfação do Usuário (++) | Felipe das Neves | **Baixa (\!)** |
| `-- (++) --> Alternar Tema`      | -                      | `De:` Oferecer Modo Escuro | Felipe das Neves | -                         |
| `-- (++) --> Legibilidade e Contraste Adequados` | -                      | `De:` Oferecer Modo Escuro | Felipe das Neves | -                         |
| `-- (?) --> Paleta de Cores Definida` | -                      | `Para:` Legibilidade e Contraste Adequados | Equipe de Design | -                         |
| `-- (+) --> Transição Suave`     | -                      | `De:` Oferecer Modo Escuro | Felipe das Neves | -                         |
| `-- (+) --> Compatibilidade entre Telas` | -                      | `De:` Oferecer Modo Escuro | Felipe das Neves | -                         |
| **Confirmação Clara e Acessível de Envio (US36)** | ✓ (Operacionalização) | `Para:` Usabilidade (++) / Acessibilidade (++) | Felipe das Neves | -                         |
| **Clareza e Responsividade em Menus/Botões (Registro) (US01, US06)** | ✓ (Operacionalização) | `Para:` Usabilidade (++) / Satisfação do Usuário (++) | Felipe das Neves | -                         |

<font size="3"><p style="text-align: center">Fonte: <a style="color:white blue;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a></p></font>

---

## NFR 02 - Confiabilidade

A figura 6 a seguir demonstra o SIG de Confiabilidade:

<font size="3"><p style="text-align: center"><b>Figura 6</b> SIG Confiabilidade</p></font>


![SIG NFR Confiabilidade](../../assets/nfr/confiabilidade.png)

<font size="3"><p style="text-align: center">Fonte: <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a></p></font>

### Requisitos Não-Funcionais - Confiabilidade

Na Tabela 15 a seguir, são descritos os Requisitos Não-Funcionais relacionados à **Confiabilidade**, levando em consideração aspectos como envio de informações sem falhas, criptografia segura dos dados e acionamento confiável de alertas em situações emergenciais. Esses requisitos foram elaborados com base na modelagem do NFR Framework para o aplicativo *Celular Seguro*.



<font size="3"><p style="text-align: center">Tabela 15 - Requisitos Não-Funcionais: Confiabilidade</p></font>


| Código | Nome                                      | Descrição                                                                                                                                                                             |
| :----- | :---------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| RNF01  | Estabilidade e Confiabilidade Operacional | O aplicativo deve funcionar de maneira estável e confiável em momentos de emergência e sob condições de uso normais, garantindo a execução ininterrupta das suas funções essenciais.      |
| RNF02  | Envio de Anexos com Integridade           | O sistema deve permitir o envio de arquivos (PDF, JPG, PNG) de até 10MB, garantindo a integridade dos dados transmitidos, sem falhas ou perdas.                                             |
| RNF07  | Disponibilidade do Serviço (24x7)         | O serviço Celular Seguro deve estar disponível para todos os cidadãos brasileiros 24 horas por dia, 7 dias por semana, sem interrupções planejadas, para garantir acesso constante.    |
| RNF21  | Verificação de Integridade de Dados       | O sistema deve realizar verificação da integridade de dados armazenados no drive local através de checksums, para prevenir corrupção e garantir a validade das informações.             |
| RNF26  | Robustez contra Entradas Inválidas        | O aplicativo deve responder corretamente e de forma resiliente mesmo diante de entradas erradas ou inesperadas do usuário, sem travar ou apresentar comportamentos inconsistentes. |


<font size="3"><p style="text-align: center">Fonte: <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a></p></font>

### Propagação dos Impactos - Confiabilidade

<font size="3"><p style="text-align: center">Tabela 16 - Propagação dos Impactos: Confiabilidade</p></font>

| NFR / Softgoal                     | Impacto                           | Avaliador  |
| :--------------------------------- | :-------------------------------- | :--------- |
| Confiabilidade                     | 𝒲+                                | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |
| Garantir envio de anexos confiável | 𝒲+                                | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |
| Garantir criptografia de dados     | 𝒲+                                | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |
| Garantir acionamento confiável     | 𝒲+                                | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |
| Prevenção de falhas no envio       | 𝒲+                                | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |
| Comunicação de alertas em até 1s   | ✓                                 | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |
| Criptografia ponta-a-ponta (AES-256) | ✓                                 | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |
| Uso de protocolo HTTPS/TLS         | ✓                                 | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |
| Reação ao evento em até 2 minutos  | ✓                                 | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |
| Arquivos até 10MB (JPG, PNG, PDF)  | ✓                                 | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |
| Falha no envio acima de 10MB       |  X                                |    <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>       |

<font size="3"><p style="text-align: center">Fonte: <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a></p></font>

---

## NFR 03 - Desempenho

A figura 7 a seguir demonstra o SIG de Desempenho:


<font size="3"><p style="text-align: center"><b>Figura 7</b> - SIG Desempenho </p></font>


![SIG GERAL](../../assets/nfr/desempenho.png)

<font size="3"><p style="text-align: center">Fonte: Daniel Rodrigues</p></font>

### Requisitos Não-Funcionais - Desempenho

Na Tabela 17, estão listados os RNF presentes no NFR Famework de Desempenho:

<b>Tabela 17</b> - Requisitos Não-Funcionais 

| RNF (Fonte) | Descrição | Classificação | Origem |
|-------------|---------|-------|-------|
| Tempo de Resposta  |  O sistema deve possuir uma limitação superior do tempo de processamento de uma requisição. | Desempenho | Desempenho |
| Infraestrutura  | O sistema deve possuir uma infraestrutura para processar os dados. | Desempenho | Tempo de Resposta |
| Servidores  | O sistema deve possuir servidores para perdurar os dados. | Desempenho | Infraestrutura |
| Manutenção em tempo real  | O sistema deve ser capaz de realizar a manutenção dos servidores e de outros aspectos da infraestrutura. | Desempenho | Servidores e Infraestrutura |

<font size="3"><p style="text-align: center">Fonte: Daniel Rodrigues</p></font>

### Propagação dos Impactos - Desempenho

Na Tabela 18, está presente a avaliação da propagação dos impactos referentes à Figura x.

<b>Tabela 18</b> - Impactos Desempenho

| NFR                        | Impacto| Avaliador         |
|----------------------------------|-------------|------------------------|
| Desempenho                       | ⚡          | [Daniel Rodrigues](https://github.com/zDrNz) |
| Envio de Alertas Imediato        | ⚡          | [Daniel Rodrigues](https://github.com/zDrNz) |
| Bloqueio em até 2 minutos        | ✓           | [Daniel Rodrigues](https://github.com/zDrNz) |
| Carregamento em até 2s (4G)      | ⚡          | [Daniel Rodrigues](https://github.com/zDrNz) |
| Precisão da Detecção             | ↘/-         | [Daniel Rodrigues](https://github.com/zDrNz) |
| Segurança                        | ↘/+         | [Daniel Rodrigues](https://github.com/zDrNz) |
| Infraestrutura Móvel             | ↘/+         | [Daniel Rodrigues](https://github.com/zDrNz) |
| Consumo de Bateria               | ✗           | [Daniel Rodrigues](https://github.com/zDrNz) |
| Processamento Offline            | ↘/-         | [Daniel Rodrigues](https://github.com/zDrNz) |
| Usabilidade em Redes Lentas      | ✗           | [Daniel Rodrigues](https://github.com/zDrNz) |
| Manutenção em Tempo Real         | ✓           | [Daniel Rodrigues](https://github.com/zDrNz) |
| Escalabilidade (Crescimento)     | ↘/+         | [Daniel Rodrigues](https://github.com/zDrNz) |


<font size="3"><p style="text-align: center">Fonte: Daniel Rodrigues</p></font>

---

## NFR 04 - Segurança


Abaixo na figura 8 está o SIG de Segurança:

<font size="3"><p style="text-align: center"> Figura 8: Sig Segurança</p></font>

![SIG Segurança](../../assets/nfr/seguranca.jpeg)

<font size="3"><p style="text-align: center"> Fonte: Mateus Bastos</p></font>


### Requisitos Não-Funcionais - Segurança

A seguir, são apresentados os requisitos não funcionais específicos para o NFR de Segurança do projeto "Celular Seguro", 
.

<p style="text-align: center"><b>Tabela 19</b> - Requisitos Não Funcionais: Segurança</p>


| Código | Nome                                      | Descrição                                                                                                                                                                                                                                 |
| :----- | :---------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [RNF09](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais)  | O aplicativo e a plataforma devem seguir requisitos de segurança da informação: conexão criptografada, proteção de dados conforme LGPD.  | O aplicativo deve garantir a segurança da informação através de conexão criptografada (TLS 1.3) e proteção de dados em repouso (AES-256), conforme a LGPD.                                                                                 |
| [RNF18](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais)  | Autenticação multifator (2FA) com fallback via SMS.           | O sistema deve suportar e oferecer autenticação multifator (2FA) para todos os usuários, com fallback via SMS. A 2FA deve ser obrigatória para acessos críticos, utilizando o Gov.br.                                                           |
| [RNF19](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais)  | Logs de auditoria imutáveis e armazenados por no mínimo 1 ano. | O sistema deve gerar e armazenar logs de auditoria imutáveis de eventos de segurança por no mínimo 1 ano, para garantir rastreabilidade e conformidade.                                                                                  |
| [RNF20](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais)  | Política de privacidade clara e facilmente acessível dentro do app.  | O aplicativo deve disponibilizar uma política de privacidade clara e facilmente acessível, detalhando a coleta, armazenamento e uso de dados em conformidade com a LGPD.                                                                 |
| [RNF24](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais)  | Atualizações automáticas de segurança e correções de vulnerabilidades em até 24 horas.     | O sistema deve aplicar atualizações automáticas de segurança e correções de vulnerabilidades críticas em até 24 horas após a disponibilidade, visando proteção contínua contra novas ameaças.                                                |



<font size="3"><p style="text-align: center">Fonte: <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a></p></font>

---

### Propagação dos Impactos - Segurança

Na Tabela 20, está presente a avaliação da propagação dos impactos referentes à Figura 8 (SIG da Segurança).

<font size="3"><p style="text-align: center">Tabela 20 – Impactos Segurança</p></font>


| NFR                                                | Impacto | Avaliador      |
|----------------------------------------------------|---------|----------------|
| Segurança                                         | 𝒲+      | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |
| Criptografia AES-256                               | 𝒲+      | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |
| TLS 1.3 para dados em trânsito                     | 𝒲+      | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |
| Conformidade com LGPD                              | 𝒲+      | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |
| Controle de Acesso Seguro                          | 𝒲+      | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |
| Papéis definidos (RBAC)                            | ✓       | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |
| Permissões específicas para emissão de alertas e acesso a dados | ✓       | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |
| Autenticação Segura                                | 𝒲+      | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |
| Login gov.br + senha                               | ✓       | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |
| Autenticação 2FA                                   | ✓       | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |
| Resposta a Tentativas de Acesso Indevido           | 𝒲+      | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |
| Mecanismo de bloqueio após 5 tentativas inválidas  | ✓       | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |
| Detecção de comportamento suspeito no login        | ✓       | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |
| Alerta ao Titular sobre tentativas de acesso       | ✓       | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |
| Mitigação de acessos indevidos por tentativa de login                                | 𝒲+       | <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> |


<font size="3"><p style="text-align: center">Fonte: <a style="color:white blue;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a></p></font>



---


## NFR 05 - Acessibilidade

A figura 9 a seguir demonstra o SIG de Acessibilidade:

<font size="3"><p style="text-align: center"><b>Figura 9</b> - SIG Acessibilidade </p></font>


![SIG GERAL](../../assets/nfr/acessibilidade.png)

<font size="3"><p style="text-align: center">Fonte: Felipe das Neves</p></font>

---

### Requisitos Não-Funcionais - Acessibilidade

<font size="3"><p style="text-align: center">Tabela 21 - Requisitos Não-Funcionais: Acessibilidade</p></font>

| Código Original (se aplicável) | Nome do Softgoal / Operacionalização | Descrição / Detalhes de Implementação | Tipo de Elemento (Nuvem) |
| :----------------------------- | :----------------------------------- | :------------------------------------ | :----------------------- |
| -                              | **Acessibilidade** | O objetivo geral de garantir que o aplicativo seja utilizável por pessoas com as mais diversas habilidades e necessidades, incluindo o uso de tecnologias assistivas. | Normal                   |
| -                              | **Previsibilidade da Interface** | A interface do usuário deve ser consistente e previsível em seu layout e comportamento para reduzir a carga cognitiva e auxiliar a navegação. | Normal                   |
| US14 / RNF05                   | **Manter Layout Consistente** | A interface da tela de Perfil deve manter o mesmo visual e organização (título, espaçamento, cores, tamanho de texto) que as demais telas do aplicativo. | Borda Grossa (Operacionalização) |
| -                              | Título Consistente (RNF05.1)         | O título 'Perfil' deve aparecer com a mesma fonte e cor que os títulos de outras telas. | Normal                   |
| -                              | Posição Elementos Similares (RNF05.2)| Foto, nome, e-mail e botão 'Editar Perfil gov.br' devem ocupar posições semelhantes às de outras telas. | Normal                   |
| -                              | Aparência e Comportamento Botões (RNF05.3)| Botões na tela de Perfil devem ter aparência e comportamento iguais aos de outras telas (Home e Configurações). | Normal                   |
| -                              | Espaçamento Consistente (RNF05.4)    | Espaços entre elementos devem seguir o guia de estilo do aplicativo (distâncias iguais às de outras telas). | Normal                   |
| -                              | **Guia de Estilo do App Aprovado** | Artefato com diretrizes de cores, fontes e espaçamentos aprovado pela equipe de design, essencial para a consistência visual. | Tracejada (Dependência/Afirmação) |
| RNF04 (Parte)                  | Legibilidade e Contraste Adequados | Todos os elementos visuais devem manter boa legibilidade e contraste no modo escuro, conforme diretrizes de acessibilidade (ex: WCAG AA). | Normal (Reaproveitado/Contribuinte) |

<font size="3"><p style="text-align: center">Fonte: Felipe das Neves</p></font>


### Propagação dos Impactos - Acessibilidade

A tabela a seguir detalha os softgoals de Acessibilidade e como os requisitos e operacionalizações específicas impactam esses objetivos, incluindo as conotações de impacto e rótulos de satisfação conforme definidos no modelo Goal-Oriented.

<font size="3"><p style="text-align: center">Tabela 22 - Propagação dos Impactos: Acessibilidade</p></font>

| NFR / Softgoal / Operacionalização | Rótulo/Status Avaliado | Contribuição de/para | Avaliador | Prioridade (se aplicável) |
| :--------------------------------- | :--------------------- | :------------------- | :-------- | :------------------------ |
| **Acessibilidade** | W+                     | `De:` Usabilidade    | Felipe das Neves | -                         |
| `-- (++) --> Previsibilidade da Interface` | W+                     | `De:` Acessibilidade | Felipe das Neves | -                         |
| **Manter Layout Consistente (RNF05)** | W+ (Operacionalização) | `Para:` Previsibilidade da Interface (++) / Acessibilidade (++) | Felipe das Neves | **Média (\!)** |
| `-- (++) --> Título Consistente` | -                      | `De:` Manter Layout Consistente | Felipe das Neves | -                         |
| `-- (++) --> Posição Elementos Similares` | -                      | `De:` Manter Layout Consistente | Felipe das Neves | -                         |
| `-- (++) --> Aparência e Comportamento Botões` | -                      | `De:` Manter Layout Consistente | Felipe das Neves | -                         |
| `-- (++) --> Espaçamento Consistente` | -                      | `De:` Manter Layout Consistente | Felipe das Neves | -                         |
| `-- (?) --> Guia de Estilo do App Aprovado` | -                      | `Para:` Manter Layout Consistente | Equipe de Design | -                         |
| **Legibilidade e Contraste Adequados (RNF04)** | W+ (Parte da Oper.) | `Para:` Acessibilidade (++) | Felipe das Neves | -                         |

<font size="3"><p style="text-align: center">Fonte: Felipe das Neves</p></font>

---

## NFR 06 - Completo

A figura 10 a seguir demonstra o SIG completo da aplicação "Celular Seguro:


<font size="3"><p style="text-align: center"><b>Figura 10</b> - SIG Completo </p></font>


![SIG GERAL](../../assets/nfr/completo.png)

<font size="3"><p style="text-align: center">Fonte: Felipe das Neves</p></font>

---

## Requisitos Não-Funcionais Utilizados para o Desenvolvimento do NFR

A Tabela 21 a seguir lista os Requisitos Não-Funcionais aplicáveis à tela Registar Pessoa de Confiança.

<p style="text-align: center"><b>Tabela 8</b> - Requisitos Não-Funcionais</p>

| ID    | Descrição | Rastreabilidade | Implementação |
| :---- | :--------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------- | :------------ |
| [RNF01](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#rnf01) | Confirmação clara e acessível de envio do boletim, incluindo número de protocolo visível por no mínimo 10 segundos. | — | Não |
| [RNF02](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#rnf02) | Envio de anexos com limite máximo de 10 MB por arquivo, aceitando JPG, PNG e PDF. | — | Não |
| [RNF03](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#rnf03) | Opção acessível para iniciar o processo de remoção de Pessoa de Confiança. | [BS23](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#palavras-chave-identificadas) | Não |
| [RNF04](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#rnf04) | Modo escuro (dark mode) para maior conforto visual. | [BS4](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#palavras-chave-identificadas) | Não |
| [RNF05](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#rnf05) | Layout consistente na tela de Perfil. | [BS2](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#palavras-chave-identificadas) | Não |
| [RNF06](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#rnf06) | Opção de alto contraste e fonte ajustável na tela de Perfil. | [OBS18](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Observacao/#tabela-de-requisitos-nao-funcionais) | Não |
| [RNF07](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#rnf07) | Menus e botões claros e responsivos no Registro de Telefone. | [BS1](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#palavras-chave-identificadas) | Não |
| [RNF08](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#rnf08) | Criptografia ponta-a-ponta nos dados do Registro de Telefone. | [BS3](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#palavras-chave-identificadas) | Não |
| [RNF09](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#rnf09) | Conformidade de Segurança e Criptografia (LGPD). | [BS5](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#palavras-chave-identificadas), [OBS21](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Observacao/#tabela-de-requisitos-nao-funcionais) | Não |
| [RNF09](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#rnf09) | Conformidade de Segurança e Criptografia (LGPD). | [BS47](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#bs47), [OBS21](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Observacao/#obs21), [ADD15](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/#requisitos-funcionais), [ST10](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Storytelling/#tabela-de-requisitos-nao-funcionais) | Não |
| [RNF10](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#rnf10) | Páginas carregam em até 2 segundos em 4G. | [OBS16](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Observacao/#obs16), [ST9](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Storytelling/#tabela-de-requisitos-nao-funcionais) | Não |
| [RNF11](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#rnf11) | Precisão de localização GPS menor que 10 metros. | [BS45](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#bs45), [ST6](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Storytelling/#tabela-de-requisitos-nao-funcionais) | Não |
| [RNF12](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#rnf12) | Proteção dos dados de localização com criptografia. | [BS47](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#bs47), [ADD15](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/#requisitos-funcionais), [ST10](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Storytelling/#tabela-de-requisitos-nao-funcionais) | Não |
| [RNF13](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#rnf13) | Controle de acesso baseado em papéis (RBAC). | [BS9](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#bs9), [ADD15](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/#requisitos-funcionais) | Não |
| [RNF14](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#rnf14) | Autenticação segura (senha forte e 2FA). | [BS48](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#bs48), [ADD15](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/AnalisedeDocumentos/#requisitos-funcionais) | Não |
| [RNF18](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#rnf18) | Autenticação multifator (2FA) com fallback via SMS. | [BS48](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#bs48) | Não |
| [RNF19](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#rnf19) | Logs de auditoria imutáveis por no mínimo 1 ano. | [BS49](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#bs49) | Não |
| [RNF20](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#rnf20) | Política de privacidade clara e acessível. | [BS50](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#bs50) | Não |
| [RNF24](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#rnf24) | Atualizações automáticas de segurança em até 24h. | [BS60](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Brainstorming/#bs60), [OBS21](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Observacao/#obs21) | Não |

<font size="3"><p style="text-align: center">Autor: <a href="https://github.com/MateuSansete" target="_blank"> Mateus Bastos </a> e  <a href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a></p></font>


---

## Bibliografia

> <a name="ref1"></a> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, 2019. Disponível em: <https://repositorio.ufpe.br/handle/123456789/34150>. Acesso em: 31/05/2025.

> <a name="ref2"></a>CHUNG, L., NIXON, B. A., YU, E., MYLOPOULOS, J. Non-functional requirementsin software engineering. Springer Science & Business Media: [S.l.], 2000. v. 5.

---

## Histórico de Versões

| Versão | Data de Produção | Descrição da Alteração | Autor(es) | Revisor(es) | Data de Revisão |
|:------:|:----------------:|:----------------------:|:---------:|:-----------:|:--------------:|
| 1.0 | 22/05/2025 | Versão inicial do documento | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a>, <a style="color:gold;" href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a> | 22/05/2025 |
| 1.1    | 31/05/2025         | Desenvolvimento do Tópico Introdução, Metodologia, Carta de Especificação, NFR 0                            | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> e <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>  | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | 31/05/2025 |
| 1.2    | 31/05/2025         | Desenvolvimento das tabelas 1 e 2 do Cartão de especificação                           |  <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>  | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | 31/05/2025 |
| 1.3    | 31/05/2025         | Adição do NFR 02 Confiabilidade e NFR 04 Segurança                           |  <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>  | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | 31/05/2025 |
| 1.4    | 01/06/2025         | Adição de tabelas  | <a style="color:gold;" href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>  | <a style="color:gold;" href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a> | 01/06/2025 |
| 1.5    | 01/06/2025         | Desenvolvimento do Softgoal Interdependency Graph  | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a>  | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | 01/06/2025 |
| 1.6    | 01/06/2025         | Desenvolvimento das tabelas 7 e 8 do Cartão de especificação  | <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a>  | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | 01/06/2025 |
| 1.7    | 01/06/2025         | Desenvolvimento das tabelas 9 e 10 do Cartão de especificação e Desempenho | <a style="color:gold;" href="https://github.com/zDrNz" target="_blank">Daniel Rodrigues</a>  |  <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | 01/06/2025 |
| 1.8    | 01/06/2025         | Desenvolvimento das tabelas 11 e 12 do Cartão de especificação e padronização  | <a style="color:gold;" href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a>  |  <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | 01/06/2025 |
| 1.9    | 01/06/2025         | Padronização das tabelas e figuras  | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a>  | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Mateus Bastos</a> | 01/06/2025 |
| 2.0    | 01/05/2025         | Padronização do diagrma "Geral adaptado"                           |  <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>  | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | 01/05/2025 |
| 2.1    | 05/07/2025 | Inserção da tabela de contribuição| <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>| 05/07/2025|
| 2.1    | 06/07/2025 | Criação da tabela de Requisitos não funcionais utilizados no NFR|<a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> e <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a>| <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | 06/07/2025|
