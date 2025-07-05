<span style="background-color:#2c2c7c; color:white; font-size:0.8em; font-weight: bold; padding:2px 6px; border-radius:4px;">Versão 2.0</span>

# QFD - Quality Function Deployment – Desdobramento da Função Qualidade

---

## Introdução

O [QFD](../QFD-CelularSeguro.pdf) (Quality Function Deployment – Desdobramento da Função Qualidade) é uma das ferramentas da qualidade criada na década de 60 pelo japonês Yoji Akao. Desdobramento da função qualidade: um nome um tanto técnico para um processo que, essencialmente, faz as empresas integrarem a Voz do Cliente (VOC) no desenvolvimento de produtos.

!!! Warning "Atenção!"
    O conteúdo deste tópico **poderá sofrer alterações** ao longo da Disciplina de Requisitos de Software. Portanto, as tabelas serão organizadas iniciando pela versão mais recente e finalizando com a versão mais antiga.

## Integrantes que atuaram no desenvolvimento do artefato

Esta tabela inicial terá somente os artefatos de alta relevância que cada integrante do projeto desenvolveu. O versionamento **completo** encontra-se ao final do artefato.

<font size="3"><p style="text-align: center">_Desenvolvimento do Artefato_</p></font>

| Nome | Função |
| :--- | :--- |
| [<span style="color:gold;">Felipe das Neves</span>](https://github.com/FelipeFreire-gf) | Responsável por desenvolver o artefato e: [[ Iframe 1 ]](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/requisitos_elicitados/#requisitos-funcionais), [Matriz QFD](../QFD-CelularSeguro.pdf) e [[ Tabela Final ]](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/QFD/#tabela-final-de-priorizacao)|
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

Caso prefira nesse link abre o pdf da matriz: [Matriz QFD](../QFD-CelularSeguro.pdf)

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

Com certeza. Com base na análise do QFD (Quality Function Deployment) do "Projeto Celular Seguro", montei uma tabela completa que organiza os requisitos técnicos conforme a prioridade final calculada.

A tabela está ordenada da maior para a menor prioridade, fornecendo uma visão clara de onde os esforços de desenvolvimento devem ser concentrados para maximizar o valor para o cliente.

Com certeza! Abaixo está a tabela final completa, seguida por uma legenda detalhada explicando o que cada coluna e seus respectivos valores representam.

### Tabela Final de Priorização

<font size="3"><p style="text-align: center">_Tabela Final de Priorização com Grau de Dificuldade_</p></font>

| Nova Ordem de Prioridade | Classificação Original | Requisito Técnico (Leitura Aproximada) | Pontuação de Importância Técnica | % de Importância | Grau de Dificuldade |
|:---:|:---:|---|:---:|:---:|:---:|
| 1 | 3 | Opção de contraste/tamanho de fonte | 467 | 4% | 5 |
| 2 | 1 | Logs de auditoria imutáveis | 1647 | 10% | 5 |
| 3 | 2 | Disponibilidade 24/7 | 1655 | 10% | 1 |
| 4 | 9 | Fallback para economizar dados móveis | 918 | 5% | 5 |
| 5 | 10 | Interface intuitiva e amigável | 873 | 5% | 1 |
| 6 | 4 | Monitoramento de acesso não autorizado | 1304 | 8% | 1 |
| 7 | 8 | Resposta rápida | 984 | 6% | 5 |
| 8 | 13 | Autenticação multifator (2FA) | 792 | 5% | 1 |
| 9 | 22 | *Requisito Ilegível* | 414 | 2% | 5 |
| 10 | 15 | Central de ajuda online/offline | 738 | 4% | 5 |
| 11 | 19 | Sincronização app-portal | 594 | 3% | 5 |
| 12 | 24 | Acessibilidade (Vlibras) | 216 | 1% | 5 |
| 13 | 14 | App inicia em < 2 segundos | 756 | 4% | 1 |
| 14 | 20 | Existência de tutoriais/assistente | 558 | 3% | 5 |
| 15 | 11 | Rastreamento em segundo plano | 855 | 5% | 5 |
| 16 | 7 | Compatibilidade com Android/iOS | 1008 | 6% | 1 |
| 17 | 5 | Política de privacidade acessível | 1185 | 7% | 1 |
| 18 | 6 | Transcrição em tempo real | 1026 | 6% | 5 |
| 19 | 23 | Layout consistente | 376 | 2% | 5 |
| 20 | 18 | Linguagem simples e acessível | 648 | 4% | 1 |
| 21 | 12 | Verificação de integridade com checksum | 810 | 5% | 5 |
| 22 | 21 | *Requisito Ilegível* | 540 | 3% | 1 |
| 23 | 17 | Precisão do GPS (<10m) | 684 | 4% | 1 |
| 24 | 16 | Backup criptografado (AES-256) | 702 | 4% | 1 |
| 25 | 25 | *Requisito Ilegível* | 180 | 1% | 5 |
| 26 | 26 | Notificações em tempo real | 126 | 1% | 5 |

<font size="3"><p style="text-align: center">_Autor: Felipe das Neves_</p></font>

---

### Legendas

* **Nova Ordem de Prioridade:**
    * **O que representa:** É a ordem de execução ou foco definida por você. O item 1 é o que você definiu como o mais prioritário, seguido pelo 2, e assim por diante.
    * **Como usar:** Serve como um guia para o planejamento das próximas etapas do projeto, baseado na sua análise estratégica.

* **Classificação Original**
    * **O que representa:** É a prioridade calculada automaticamente pela metodologia QFD, com base puramente nos dados da planilha. O valor 1 representa o requisito com a maior pontuação calculada, sendo o mais importante do ponto de vista técnico para satisfazer o cliente.
    * **Como usar:** Permite comparar a priorização matemática do QFD com a sua priorização estratégica ("Nova Ordem"). Grandes diferenças podem indicar a necessidade de reavaliar a estratégia ou os pesos no QFD.

* **Requisito Técnico (Leitura Aproximada):**
    * **O que representa:** O nome da especificação técnica ou requisito não funcional que precisa ser desenvolvido.
    * **Observação:** Conforme avisado, os nomes são uma interpretação da imagem de baixa qualidade do documento "QFD-Celular Seguro.pdf"[cite: 33].

* **Pontuação de Importância Técnica:**
    * **O que representa:** É o resultado numérico do cálculo do QFD. Uma pontuação mais alta significa que o requisito técnico tem um impacto maior em atender às necessidades mais importantes do cliente.
    * **Como é calculado:** É a soma de todas as multiplicações entre a "Importância do Cliente" e a "Força do Relacionamento" para cada requisito técnico.

* **% de Importância:**
    * **O que representa:** É o peso relativo de cada requisito técnico em relação ao todo. Mostra qual porcentagem da "importância total" está concentrada em cada item.
    * **Como usar:** Ajuda a visualizar rapidamente onde estão os maiores blocos de valor. Por exemplo, os requisitos com 10% são os mais impactantes do projeto.

* **Grau de Dificuldade:**
    * **O que representa:** Uma estimativa do esforço, tempo ou complexidade necessários para implementar o requisito técnico. Foi baseado nos dados que você forneceu (`1` ou `5`).
    * **Como interpretar:**
        * **1:** Baixa Dificuldade (mais fácil, rápido ou barato de implementar).
        * **5:** Alta Dificuldade (mais difícil, demorado ou caro de implementar).
    * **Como usar:** Essencial para cruzar o `valor` (Pontuação/Prioridade) com o `custo` (Dificuldade) e tomar decisões estratégicas, como focar em itens de "alto valor e baixa dificuldade" primeiro.

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