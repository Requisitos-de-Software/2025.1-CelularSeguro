<span style="background-color:#2c2c7c; color:white; font-size:0.8em; font-weight: bold; padding:2px 6px; border-radius:4px;">Versão 1.1</span>

# MoScoW

---

## Introdução

O método de MoSCoW é uma técnica de priorização utilizada em gestão, análise de negócios, gestão de projetos e desenvolvimento de software. Visa chegar a um entendimento comum com as partes interessadas sobre a importância que atribuem à entrega de cada requisito; também é conhecido como priorização MoSCoW ou análise MoSCoW.

!!! Warning "Atenção!"
    O conteúdo deste tópico **poderá sofrer alterações** ao longo da Disciplina de Requisitos de Software. Portanto, as tabelas serão organizadas iniciando pela versão mais recente e finalizando com a versão mais antiga.

## Integrantes que atuaram no desenvolvimento do artefato

Esta tabela inicial terá somente os artefatos de alta relevância que cada integrante do projeto desenvolveu. O versionamento **completo** encontra-se ao final do artefato.

<font size="3"><p style="text-align: center">_Desenvolvimento do Artefato_</p></font>

| Nome | Função |
| :--- | :--- |
| [<span style="color:gold;">Felipe das Neves</span>](https://github.com/FelipeFreire-gf) | Responsável por desenvolver o artefato e: [[ Tabela 1 ]](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/MoSCoW/#must-deve), [[ Tabela 2 ]](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/MoSCoW/#should-deveria), [[ Tabela 3 ]](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/MoSCoW/#could-poderia), [[ Tabela 4 ]](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-elicitacao/MoSCoW/#historico-de-versoes)|
| [<span style="color:gold;">Mateus Bastos</span>](https://github.com/MateuSansete) | Revisor do Artefato |

*Legenda:* 

**Nome** – participante da técnica. 

**Função** – papel desempenhado na priorização. 

!!! Tip "Observação"
    Frizando claramente que as contribuições de cada integrante ainda que mínimas são ainda sim muito relevantes no desenvolvimento do artefo, considere verificar o histórico de versão. 

---

### Metodologia

Para que a priorização fosse feita, nossa equipe utilizou como base os resultados da análise de **Desdobramento da Função Qualidade (QFD)**. O QFD traduziu as necessidades dos clientes em prioridades de desenvolvimento, gerando uma pontuação de importância e um ranking para cada requisito.

Com base nesse ranking quantitativo, e cruzando a informação de valor (pontuação QFD) com o esforço estimado (Grau de Dificuldade), classificamos os requisitos dentro da metodologia MoSCoW. Essa abordagem garante que a priorização final esteja alinhada tanto com o valor percebido pelo cliente quanto com a viabilidade técnica.

---

### Must "Deve"

Os requisitos classificados como **Must** (Tabela 1) representam o núcleo de maior valor do produto, conforme identificado pela análise QFD[cite: 1, 4]. Eles possuem as maiores pontuações de importância, indicando que são essenciais para atender às principais expectativas dos clientes. A ausência desses itens comprometeria criticamente a proposta de valor do aplicativo, tornando-os inegociáveis para a primeira versão.

<font size="3"><p style="text-align: center">_Tabela 1: Requisitos Must_</p></font>

| Descrição do Requisito | Pontuação QFD | Dificuldade |
|---|:---:|:---:|
| Disponibilidade 24/7 | 1655 | 1 |
| Logs de auditoria imutáveis  | 1647 | 5 |
| Monitoramento de acesso não autorizado  | 1304 | 1 |
| Política de privacidade acessível  | 1185 | 1 |
| Transcrição em tempo real  | 1026 | 5 |
| Compatibilidade com Android/iOS  | 1008 | 1 |
| Opção de contraste/tamanho de fonte  | 467 | 5 |

<font size="3"><p style="text-align: center">_Autor: Felipe das Neves_</p></font>

---

### Should "Deveria"

Na categoria **Should** (Tabela 2) estão funcionalidades de alto e médio valor que são importantes para uma experiência completa, mas não são tão críticas quanto os itens "Must". Embora o produto funcione sem eles, sua ausência seria sentida pelo usuário. Estes requisitos devem ser implementados logo após a garantia dos itens essenciais.

<font size="3"><p style="text-align: center">_Tabela 2: Requisitos Should_</p></font>

| Descrição do Requisito | Pontuação QFD | Dificuldade |
|---|:---:|:---:|
| Resposta rápida  | 984 | 5 |
| Fallback para economizar dados móveis  | 918 | 5 |
| Interface intuitiva e amigável  | 873 | 1 |
| Rastreamento em segundo plano  | 855 | 5 |
| Verificação de integridade com checksum  | 810 | 5 |
| Autenticação multifator (2FA)  | 792 | 1 |
| App inicia em \< 2 segundos  | 756 | 1 |
| Central de ajuda online/offline  | 738 | 5 |
| Backup criptografado (AES-256)  | 702 | 1 |
| Precisão do GPS (\<10m)  | 684 | 1 |
| Linguagem simples e acessível  | 648 | 1 |

<font size="3"><p style="text-align: center">_Autor: Felipe das Neves_</p></font>

---

### Could "Poderia"

Os itens da categoria **Could** (Tabela 3) são considerados desejáveis. Eles possuem menor pontuação de importância no QFD, indicando um impacto menor na satisfação das necessidades principais do cliente. São ótimos candidatos a serem incluídos caso haja tempo e recursos disponíveis após a conclusão das categorias "Must" e "Should", servindo para refinar e diferenciar o produto.

<font size="3"><p style="text-align: center">_Tabela 3: Requisitos Could_</p></font>

| Descrição do Requisito | Pontuação QFD | Dificuldade |
|---|:---:|:---:|
| Sincronização app-portal  | 594 | 5 |
| Existência de tutoriais/assistente  | 558 | 5 |
| *Requisito Ilegível*  | 540 | 1 |
| *Requisito Ilegível* | 414 | 5 |
| Layout consistente | 376 | 5 |
| Acessibilidade (Vlibras) | 216 | 5 |

<font size="3"><p style="text-align: center">_Autor: Felipe das Neves_</p></font>

---

### Won't "Não vai"

Por fim, a categoria **Won’t** (Tabela 4) inclui requisitos que foram explicitamente definidos como fora do escopo para esta fase do projeto. [cite\_start]A análise QFD confirmou seu baixo valor relativo (as menores pontuações) e, em muitos casos, uma alta dificuldade de implementação[cite: 4]. A decisão de não implementá-los agora permite que a equipe foque os recursos nos itens de maior impacto.

<font size="3"><p style="text-align: center">_Tabela 4: Requisitos Won't (por ora)_</p></font>

| Descrição do Requisito | Pontuação QFD | Dificuldade |
|---|:---:|:---:|
| *Requisito Ilegível*  | 180 | 5 |
| Notificações em tempo real  | 126 | 5 |

<font size="3"><p style="text-align: center">_Autor: Felipe das Neves_</p></font>

---

## Bibliografia

>SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. 2022. Apresentação de Power Point. 50 slides. color. Disponível em: https://aprender3.unb.br/pluginfile.php/2124453/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 04 mai. 2025.

---

## Histórico de Versões 

| Versão | Data de produção   | Descrição da Alteração                               | Autor(es)             | Revisor(es)      |Data de Revisão |
| :----: | :----------------: | :--------------------------------------------------: | :-------------------: | :-------------:  |  :-----------: |
| 1.0    | 04/05/2025         | Desenvolvimento do artefato                            |<a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a>    | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>| 04/05/2025|
| 1.1    | 05/07/2025 | Inserção da tabela de contribuição| <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>| 05/07/2025|