<span style="background-color:#2c2c7c; color:white; font-size:0.8em; font-weight: bold; padding:2px 6px; border-radius:4px;">Versão 1.6</span>

# Metodologia

---

A metodologia do projeto define como o processo foi conduzido, incluindo as práticas e estratégias utilizadas para o planejamento e execução das etapas. Para este projeto, a equipe optou por utilizar o método ágil **Scrum**, devido à familiaridade do grupo com seus princípios e dinâmicas.

!!! Warning "Atenção!"
    O conteúdo deste tópico **poderá sofrer alterações** ao longo da Disciplina de Requisitos de Software. Portanto, as tabelas serão organizadas iniciando pela versão mais recente e finalizando com a versão mais antiga.

## Integrantes que atuaram no desenvolvimento do artefato

Esta tabela inicial terá somente os artefatos de alta relevância que cada integrante do projeto desenvolveu. O versionamento **completo** encontra-se ao final do artefato.

<font size="3"><p style="text-align: center">_Tabela de Contribuição_</p></font>

| Nome | Função |
| :--- | :--- |
| [<span style="color:gold;">Gabriel Lima</span>](https://github.com/gabriel-lima258) | Autor responsável pelo artefato |
| [<span style="color:gold;">Arthur Leite</span>](https://github.com/arthurlleite) | Autor responsável pelo artefato  |
| [<span style="color:gold;">Leonardo de Melo</span>](https://github.com/leozinlima) | Revisor do Artefato |


*Legenda:* 

**Nome** – participante da técnica. 

**Função** – papel desempenhado na priorização. 

!!! Tip "Observação"
    Frizando claramente que as contribuições de cada integrante ainda que mínimas são ainda sim muito relevantes no desenvolvimento do artefo, considere verificar o histórico de versão. 

---

## SCRUM

O **Scrum** é um framework ágil que organiza o desenvolvimento de projetos em ciclos curtos e iterativos chamados de *sprints*. Cada sprint compreende um conjunto de tarefas específicas que devem ser realizadas dentro de um período determinado. Esse modelo é ideal para projetos com requisitos que evoluem com o tempo, como é o caso deste trabalho.

---

### Equipe Scrum

A tabela a seguir apresenta os papéis definidos segundo o framework Scrum e os integrantes do projeto responsáveis por cada função.

<font size="3"><p style="text-align: center">Tabela 1 – Composição da Equipe Scrum</p></font>

| **Função**             | **Responsável**            | **Descrição**                                                                                                              |
|------------------------|----------------------------|----------------------------------------------------------------------------------------------------------------------------|
| **Scrum Master**       | <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho </a>     | Responsável por facilitar a aplicação das práticas ágeis, removendo impedimentos e garantindo o bom andamento do projeto. |
| **Product Owner**      | <a style="color:gold;" href="https://github.com/EmivaltoJrr" target="_blank">Emivalto (monitor) </a>                | Representa os interesses dos stakeholders e garante que o produto entregue atenda às suas necessidades.                   |
| **Time de Desenvolvimento** |<a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a>, <a style="color:gold;" href="https://github.com/Bessazs" target="_blank">Vitor Pereira</a>, <a style="color:gold;" href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>, <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>, <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a>,  [<span style="color:gold;">Gabriel Lima</span>](https://github.com/gabriel-lima258),  [<span style="color:gold;">Daniel Rodrigues</span>](https://github.com/zDrNz)     | Equipe encarregada de implementar as tarefas planejadas em cada sprint.                                                   |

<font size="3"><p style="text-align: center">_Fonte: [Gabriel Lima](https://github.com/gabriel-lima258), [Arthur Carvalho](https://github.com/arthurlleite) _</p></font>

---

### Eventos do Scrum

A tabela abaixo apresenta os eventos Scrum utilizados pela equipe e suas respectivas finalidades.

<font size="3"><p style="text-align: center">Tabela 2 – Eventos Scrum utilizados no projeto</p></font>

| **Evento**   | **Descrição**                                                                                                               |
|--------------|-----------------------------------------------------------------------------------------------------------------------------|
| **Sprint**   | Ciclo de desenvolvimento semanal que visa o cumprimento de tarefas planejadas na reunião de *planning* e revisadas na *review*. |
| **Status**   | Reuniões rápidas entre sprints para alinhamento e verificação de obstáculos. Realizadas às quartas às 22h.                  |

<font size="3"><p style="text-align: center">_Fonte: [Gabriel Lima](https://github.com/gabriel-lima258), [Arthur Carvalho](https://github.com/arthurlleite) _</p></font>

---

## Reuniões da Equipe

Abaixo, apresenta-se o cronograma de reuniões definidas após análise da disponibilidade dos membros.

<font size="3"><p style="text-align: center">Tabela 3 – Cronograma de Reuniões da Equipe</p></font>

| **Tipo de Reunião**   | **Dia/Horário**      | **Observações**                                                                                   |
|------------------------|----------------------|---------------------------------------------------------------------------------------------------|
| **Planning + Review**  | Segunda-feira às 16h | Reunião principal para planejamento das tarefas e avaliação das entregas anteriores.              |
| **Status**             | Quarta-feira às 22h  | Reunião curta, realizada de forma mais dinâmica e objetiva.                                       |

<font size="3"><p style="text-align: center">_Fonte: [Gabriel Lima](https://github.com/gabriel-lima258), [Arthur Carvalho](https://github.com/arthurlleite) _</p></font>

---

## Outras Práticas Utilizadas

Além dos eventos do Scrum, a equipe também adotou a prática de **programação em duplas** (*pair programming*), onde:

- Um membro atua como programador (codificando);
- O outro como revisor (analisando lógica, erros e melhorias).

Essa prática contribui para:
- Compartilhamento de conhecimento;
- Detecção precoce de erros;
- Aumento da qualidade do código produzido.

---

## Política de Contribuição

Este repositório segue uma política de versionamento e colaboração inspirada nas melhores práticas de Engenharia de Software.

### Branches

A tabela abaixo apresenta o padrão de nomenclatura para criação de branches durante o desenvolvimento do projeto.

**Tabela 4 – Padrão de nomenclatura para branches**

| **Tipo**           | **Padrão de nome**        | **Exemplo**                     |
|--------------------|---------------------------|----------------------------------|
| Funcionalidade     | `feature/nome-curto`      | `feature/caso-de-uso-login`     |
| Correção           | `fix/descricao`           | `fix/erro-ortografia`           |
| Documento          | `doc/tipo-de-arquivo`     | `doc/especificacao-supp`        |
| Refatoração        | `refactor/parte`          | `refactor/casos-de-uso`         |

**Fonte**: Guia de Contribuição do Projeto; CONTRIBUTING.MD (Arquivo fonte), 2025.

---

### Commits

O padrão de commits utilizado segue a estrutura `<tipo>: <descrição breve>`. Exemplos:

- `doc: adicionar glossário inicial`
- `feat: adicionar caso de uso para login`
- `fix: corrigir diagrama de atividades do cadastro`

---

### Issues

As *issues* seguem o modelo de clareza, com título e descrição objetivos. Exemplo:

```markdown
## Tarefa
Adicionar o caso de uso "Recuperar Senha" no documento de requisitos funcionais.

## Checklist
- [ ] Criar branch feature/caso-de-uso-recuperar-senha
- [ ] Criar diagrama de caso de uso
- [ ] Especificar fluxo principal e alternativo
```
---
### Pull Requests (PRs)
Cada PR inclui:

- Título descritivo e padronizado

- Checklist de revisão

- Associação a uma issue (quando aplicável)

---

## Bibliografia

> ALVES, Isaque, ROCHA, Carla. Qualifying Software Engineers Undergraduates in DevOps - Challenges of introducing technical and non-technical conceptss in a project-oriented course. Arxiv. [S. l.], v.1, 2021. Disponível em: <https://arxiv.org/abs/2102.06662. Acesso em: 10 abr. 2025.


---

## Histórico de Versões

| Versão | Data de produção   | Descrição da Alteração                                                     | Autor(es)             | Revisor(es)|Data de Revisão |
| :----: | :----------------: | :------------------------------------------------------------------------: | :-------------------: | :--------: |  :-------------: |
| 1.0    | 09/04/2025         | Criação do documento                                                       | <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a>, <a style="color:gold;" href="https://github.com/Bessazs" target="_blank">Vitor Pereira</a> | <a style="color:gold;" href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a> | 09/04/2025 |
| 1.1    | 13/04/2025         | Correção nas referências bibliográficas e reajuste nos tópicos             | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves| <a style="color:gold;" href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>| 13/04/2025|
| 1.2    | 16/04/2025         | Adição dos autores do cronograma                                           | <a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a> | <a style="color:gold;" href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>, <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | 16/04/2025| 
| 1.3    | 22/04/2025         | Correção de alguns erros nas tabelas                                       | <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a> | <a style="color:gold;" href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>, <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | 22/04/2025|
| 1.4    | 23/04/2025         | Padronização do histórico de versões e da Bibliografia                     | <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a> | <a style="color:gold;" href="https://github.com/leozinlima" target="_blank">Leonardo de Melo</a>, <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a> | 23/04/2025|
| 1.5   | 08/05/2025| Padronização do Histórico de Versões| <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a>| <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a>>| 08/05/2025|
| 1.6    | 04/07/2025 | Inserção da tabela de contribuição| <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>| 04/07/2025|
