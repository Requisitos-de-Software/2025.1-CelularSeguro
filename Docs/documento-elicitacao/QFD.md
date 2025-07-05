<span style="background-color:#2c2c7c; color:white; font-size:0.8em; font-weight: bold; padding:2px 6px; border-radius:4px;">Versão 2.0</span>

# QFD - Quality Function Deployment – Desdobramento da Função Qualidade

---

## Introdução

O [QFD](../qfdpp.pdf) (Quality Function Deployment – Desdobramento da Função Qualidade) é uma das ferramentas da qualidade criada na década de 60 pelo japonês Yoji Akao. Desdobramento da função qualidade: um nome um tanto técnico para um processo que, essencialmente, faz as empresas integrarem a Voz do Cliente (VOC) no desenvolvimento de produtos.

!!! Warning "Atenção!"
    O conteúdo deste tópico **poderá sofrer alterações** ao longo da Disciplina de Requisitos de Software. Portanto, as tabelas serão organizadas iniciando pela versão mais recente e finalizando com a versão mais antiga.

## Integrantes que atuaram no desenvolvimento do artefato

Esta tabela inicial terá somente os artefatos de alta relevância que cada integrante do projeto desenvolveu. O versionamento **completo** encontra-se ao final do artefato.

<font size="3"><p style="text-align: center">_Desenvolvimento do Artefato_</p></font>

| Nome | Função |
| :--- | :--- |
| [<span style="color:gold;">Felipe das Neves</span>](https://github.com/FelipeFreire-gf) | Responsável por desenvolver o artefato e: [[ Iframe 1 ]](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#requisitos-funcionais) e [[ Tabela 2 ]](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#requisitos-nao-funcionais)|
| [<span style="color:gold;">Todos os integrantes</span>](https://github.com/leozinlima) | Auxiliaram no preenchimento do QFD |
| [<span style="color:gold;">Leonardo de Melo</span>](https://github.com/leozinlima) | Revisor do Artefato |

*Legenda:* 

**Nome** – participante da técnica. 

**Função** – papel desempenhado na priorização.

!!! Tip "Observação"
    Frizando claramente que as contribuições de cada integrante ainda que mínimas são ainda sim muito relevantes no desenvolvimento do artefo, considere verificar o histórico de versão. 

---

## Metodologia:

O Quality Function Deployment (QFD) é uma abordagem estruturada para o planejamento de produtos e serviços. Seu principal objetivo é traduzir as necessidades e desejos do cliente, conhecidos como a "Voz do Cliente", em especificações técnicas e de engenharia, a "Voz da Engenharia". Isso garante que o produto final esteja genuinamente alinhado com as expectativas do mercado.

A ferramenta visual do QFD é a "Casa da Qualidade", que possui diferentes seções, cada uma com um propósito específico, conforme detalhado abaixo.

---

O **iFrame 1** a seguir representam a análise dos requisitos do cliente "o quê" para com os requisitos não funcionais "como" para a definição de prioridade, sendo o maior valor como menos prioritário e o menor como o mais prioritário.

<font size="3"><p style="text-align: center">_iFrame 1 - Matriz QFD_</p></font>

<iframe src="https://docs.google.com/spreadsheets/d/1mGqH9aXBEOleN6P2CAvTt_sWJA58jakpskyewBJyOeM/edit?usp=sharing" width="100%" height="800"></iframe>


<font size="3"><p style="text-align: center">_Autor: [Felipe das Neves](https://github.com/FelipeFreire-gf) _</p></font>

---

## Análise dos Componentes do QFD "Celular Seguro"

O [QFD](../qfdpp.pdf) apresentado é composto pelas seguintes seções:

### 1. Requisitos do Cliente (O Quê)

Esta é a fundação da análise. Localizada na coluna à esquerda do diagrama, ela lista as funcionalidades e características que os clientes esperam do produto.

* **Importância para o Cliente:** Cada requisito recebe uma nota de 1 a 5, indicando sua importância sob a perspectiva do cliente. Requisitos com nota 5, como "Localizar o celular perdido/rastrear em tempo real" e "Registro e bloqueio remoto do aparelho", são considerados de máxima importância.

### 2. Requisitos Técnicos (Como)

Localizada na parte superior do diagrama, esta seção lista as especificações técnicas e os atributos de engenharia que a equipe de desenvolvimento usará para atender aos requisitos do cliente. Eles estão agrupados em categorias como Interface, Desempenho, Segurança e Privacidade.

Exemplos de requisitos técnicos incluem:

* **Desempenho:** Resposta rápida, Disponibilidade 24/7.

* **Segurança:** Backup criptografado (AES-256), Autenticação multifator (2FA).

* **Interface:** Layout consistente, Acessibilidade (Vlibras e leitor de tela).

### 3. Matriz de Relacionamento

O corpo central do diagrama é a matriz que conecta os Requisitos do Cliente (O Quê) com os Requisitos Técnicos (Como). Ela utiliza símbolos para indicar a força dessa relação:

* **Relação Forte (9 pontos):** Indicada por um círculo preenchido. Mostra que o requisito técnico tem um impacto direto e forte em atender à necessidade do cliente.

* **Relação Moderada (3 pontos):** Indicada por um círculo vazio. O requisito técnico contribui para a necessidade do cliente, mas de forma menos intensa.

* **Relação Fraca (1 ponto):** Indicada por um triângulo. O requisito técnico tem uma influência leve ou indireta.

### 4. Análise da Concorrência

Na seção à direita, o projeto é comparado com três concorrentes: Cerberus, Find My Device e Find My Phone. Cada concorrente recebe uma nota de 1 a 5 em relação ao seu desempenho em cada requisito do cliente. Esta análise ajuda a identificar oportunidades de mercado e pontos onde o "Celular Seguro" pode se diferenciar.

---

## Cálculo e Análise dos Resultados

A principal saída quantitativa do QFD é a priorização dos requisitos técnicos. Isso é feito através de cálculos que transformam os dados da matriz em pontuações acionáveis.

### Pontuação de Importância Técnica

Para cada requisito técnico (coluna), uma pontuação de importância é calculada. O objetivo é medir o impacto total daquele requisito técnico na satisfação geral do cliente.

A fórmula para este cálculo é:

$$\text{Pontuação de Importância Técnica} = \sum (\text{Importância do Cliente} \times \text{Valor da Relação})$$

**Exemplo de Cálculo (para a coluna "Disponibilidade 24/7"):**

Para calcular a pontuação de 1175 para "Disponibilidade 24/7", o processo seria:

1.  Percorrer toda a coluna "Disponibilidade 24/7".

2.  Para cada linha (requisito do cliente) que tiver um símbolo de relação, multiplicar a "Importância do Cliente" daquela linha pelo valor do símbolo (9, 3 ou 1).

3.  Somar todos os resultados obtidos.

Por exemplo, se "Localizar o celular" (Importância 5) tem uma relação forte (9) com "Disponibilidade 24/7", ele contribui com `5 * 9 = 45` pontos para a pontuação total daquela coluna. A soma de todas essas contribuições resulta na "Pontuação de importância técnica".

### Classificação de Prioridades

Com base nas pontuações de importância técnica, os requisitos técnicos são finalmente classificados em ordem de prioridade.

* **Maior Pontuação, Maior Prioridade:** Requisitos com as pontuações mais altas são os mais críticos para o sucesso do projeto, pois são os que mais fortemente impactam os requisitos mais importantes do cliente.

* **Exemplo de Priorização:**

    * O requisito técnico **"Disponibilidade 24/7"** obteve a maior pontuação (1175) e, portanto, é a **prioridade número 1**.

    * **"Precisão do GPS (<10m)"** também tem uma pontuação alta (1175) e é a **prioridade número 1**. (Nota: pode haver empates na pontuação, resultando em múltiplas prioridades máximas).

    * Em contrapartida, **"Fallback para economizar dados móveis"** tem uma das pontuações mais baixas (113), sendo classificado como **prioridade 26** (baixa).

---

## Bibliografia

> “Como preencher a matriz QFD ou Casa da Qualidade”, Lucidchart, 02-nov-2023.

## Histórico de Versões

| Versão | Data de produção   | Descrição da Alteração                               | Autor(es)             | Revisor(es)      | Data de Revisão |
| :----: | :----------------: | :--------------------------------------------------: | :-------------------: | :-------------:  |  :-----------: |
| 1.0 | 28/04/2025 | Desenvolvimento do tópico QFD | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>, <a style="color:gold;" href="https://github.com/Bessazs" target="_blank">Vitor Pereira</a> | 28/04/25 |
| 1.1 | 06/05/2025 | Inserção do iFrame e do pdf | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>, <a style="color:gold;" href="https://github.com/Bessazs" target="_blank">Vitor Pereira</a> | 06/05/25 |
| 1.2  | 08/05/2025| Padronização do Histórico de Versões| <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a>| <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a>| 08/05/2025|
| 2.0    | 04/07/2025 | Inserção da tabela de contribuição e refatoração completa do artefato | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>| 04/07/2025|