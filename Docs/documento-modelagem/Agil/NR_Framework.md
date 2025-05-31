# NFR Framework
---

## Introdução

O NFR framework criado por (CHUNG et al., 2000), foi adotado por propor uma abordagem específica para o tratamento de Requisitos Não-Funcionais e fornecer uma execelente representação para expressar esses requisitos.

Este framework é utilizado neste trabalho para representar os requisitos não-funcionais conforme sua priorização neste [artefato](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_priorizados/), onde estes requisitos serão expressados através de um grafo SIG (Softgoal Interdependency Graph) uma forma de visualização do NFR framework.

---

## Metodologia

Cada integrante do projeto obteve dois requisitos não-funcionais obtido através das técnicas de [priorização](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/introducao) e validados com um usuário do aplicativo, onde cada integrante fez de forma remota ou presencial. Houve também uma criterização a respeito de cada funcionalidade do aplicativo que cada integrante ficou responsável que pode ser analisada na tabela 1 a seguir:

<font size="3"><p style="text-align: center">Tabela 1: Separação das Funcionalidades do aplicativo por integrante</p></font>

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

Aliada a essa especificação de trabalho de cada integrante, separamos pelas respecivas funcionalidades os NFRs gerados pelo framework. 

---

## Cartão de Especificação

Os cartões de especificação a seguir, Tabelas de 1 a 6, foram utilizados para definir os Requisitos Não-Funcionais a serem utilizados na confecção dos NFR Frameworks. 

As tabelas 3 e 4 são referentes a funcionalidade de Resgistrar pessoa de confiança. Critério do QFD para a criterização da prioridade, aliada os RNFs obtidos do questionário.

<font size="3"><p style="text-align: center">Tabela 3: Cartão de Especificação 1</p></font>

| Nº Requisito: 3 (<a id="anchor_RNF03" href="#RNF03">RNF03</a>)| Classificação: Funcional |
|---------------| ------------|
| Descrição: O aplicativo deve enviar um SMS para uma pessoa quando a mesma for adicionada como pessoa de confiança.
| Justificativa: Garantir que a pessoa designada como 'de confiança' seja formalmente notificada sobre sua nomeação. Isso aumenta a transparência, permite que ela esteja ciente de seu papel e responsabilidades potenciais, e pode servir como um primeiro passo para seu engajamento ou consentimento.
| Origem do Requisisto: [RNF08 Questionario](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/)
| Critério de Aceitação: O sistema deve ser capaz de recomendar ao usuário eventos condizentes com suas preferências. 
| Dependências: Nenhum
| Prioridade: 4.2
| Conflitos: Pode gerar custos adicionais de SMS.
| História: 31/05/2023

<font size="3"><p style="text-align: center">Autor: <a href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a></p></font>


<font size="3"><p style="text-align: center">Tabela 4: Cartão de Especificação 4</p></font>

| Nº Requisito: 4 (<a id="anchor_RNF04" href="#RNF04">RNF04</a>)| Classificação: Usabilidade, Acessibilidade e Funcionalidade |
|---------------| ------------|
| Descrição: O aplicativo deve oferecer um modo escuro (dark mode) para maior conforto visual.
| Justificativa:  Proporcionar uma melhor experiência de uso em ambientes com pouca luminosidade, reduzir o cansaço visual, atender às preferências de uma parcela de usuário, mesmo que esse requisito tenha sido verificado apenas para a funcionalidade: Registrar pessoa de confiança, tal requisito se extende ou sistema completo.
| Origem do Requisisto: [RNF05 Questionario](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/)
| Critério de Aceitação: O aplicativo deve possuir uma opção nas configurações que permita ao usuário alternar entre o tema claro (padrão) e o modo escuro. Todos os textos, ícones e elementos interativos devem manter boa legibilidade e contraste adequado no modo escuro, conforme as diretrizes de acessibilidade (ex: WCAG AA). A transição entre os modos deve ser suave e todas as telas do aplicativo devem ser compatíveis.
| Dependências: Definição da paleta de cores para o modo claro e escuro.
| Prioridade: 3.8
| Conflitos: Nenhum
| História: 31/05/2023

<font size="3"><p style="text-align: center">Autor: <a href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a></p></font>

---

## NFR 0 - Geral

A Figura 1 a seguir demonstra o Softgoal Interdependency Graph para se ter uma visão geral.

<font size="3"><p style="text-align: center"><b>Figura 3</b> - SIG Geral</p></font>


![SIG GERAL](../../assets/nfr/geralL.png)

<font size="3"><p style="text-align: center">Fonte: (SILVA, 2019)</p></font>

No entanto, como o foco é trabalhar apenas com Requisitos Não-Funcionais ainda não implementados pelo aplicativo, adaptou-se o SIG acima para a utilização dos tópicos necessários, conforme a figura 2:

<font size="3"><p style="text-align: center"><b>Figura 2</b> - SIG Geral Adaptado</p></font>


![SIG GERAL](../../assets/nfr/geralAdaptado.png)

<font size="3"><p style="text-align: center">Fonte: (SILVA, 2019)</p></font>

## NFR 01 - Usabilidade

Os Requisitos utilizados para a confecção da Figura 3 estão presentes na Tabela 9:

### Requisitos Não-Funcionais - Usabilidade


### Propagação dos Impactos - Usabilidade


## NFR 02 - Eficiência

### Requisitos Não-Funcionais - Eficiência

### Propagação dos Impactos - Eficiência


## NFR 03 - Desempenho

### Requisitos Não-Funcionais - Desempenho

### Propagação dos Impactos - Desempenho


## Requisitos Não-Funcionais Utilizados para o Desenvolvimento do NFR

obs cada integrante complete a tabela com o seus requisitos

A Tabela 8 a seguir lista os Requisitos Não-Funcionais utilizados para o desenvolvimento do NFR Framework.

<p style="text-align: center"><b>Tabela 8</b> - Requisitos Não-Funcionais</p>

| ID                                            | Descrição                         | Rastreabilidade                                                                                                                            | Implementação |
| :-------------------------------------------- | :-------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------- | :------------ |
| <a id="RNF03" href="#anchor_RNF01">RNF03</a> | O aplicativo deve enviar um SMS para uma pessoa quando a mesma for adicionada como pessoa de confiança.    | [RNF08](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#requisitos-nao-funcionais)      | Não           |
| <a id="RNF04" href="#anchor_RNF02">RNF04</a> | O aplicativo deve oferecer um modo escuro (dark mode) para maior conforto visual.    | [RNF05](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/Questionario/#requisitos-nao-funcionais)                                     | Não           |

<font size="3"><p style="text-align: center">Autor: <a href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a></p></font>


---

A Tabela 9 lista os Requisitos Não-Funcionais elicitados pelo NFR Framework.

obs cada integrante complete a tabela com o seus requisitos

<p style="text-align: center"><b>Tabela 9</b> - Requisitos Não-Funcionais</p>

|  ID  | Descrição |
|------|---------|
|NFR03| O aplicativo deve enviar um SMS para uma pessoa quando a mesma for adicionada como pessoa de confiança. |
|NFR04| O aplicativo deve oferecer um modo escuro (dark mode) para maior conforto visual.|


<font size="3"><p style="text-align: center">Autor: <a href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a></p></font>




---

## Bibliografia

> <a name="ref1"></a> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, 2019. Disponível em: <https://repositorio.ufpe.br/handle/123456789/34150>. Acesso em: 31/05/2025.

> <a name="ref2"></a>CHUNG, L., NIXON, B. A., YU, E., MYLOPOULOS, J. Non-functional requirementsin software engineering. Springer Science & Business Media: [S.l.], 2000. v. 5.

## Histórico de Versões

| Versão | Data de Produção | Descrição da Alteração | Autor(es) | Revisor(es) | Data de Revisão |
|:------:|:----------------:|:----------------------:|:---------:|:-----------:|:--------------:|
| 1.0 | 22/05/2025 | Versão inicial do documento | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a>, <a style="color:gold;" href="https://github.com/Bessazs" target="_blank">Vitor Bessa</a> | 22/05/2025 |
| 1.1    | 31/05/2025         | Desenvolvimento do Tópico Introdução, Metodologia,                            | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | 31/05/2025 |