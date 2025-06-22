<span style="background-color:#2c2c7c; color:white; font-size:0.8em; font-weight: bold; padding:2px 6px; border-radius:4px;">Versão 1.0</span>

# Metodologias utilizadas

---

## Introdução 

Este documento detalha as metodologias de desenvolvimento que serão empregadas para garantir que o aplicativo Celular Seguro seja robusto, intuitivo e, acima de tudo, atenda às necessidades de segurança da população. Ao longo das próximas seções, exploraremos as técnicas de elicitação de requisitos, design, validação e gerenciamento, que são pilares para a construção de uma solução tecnológica de alto impacto social.

!!! Warning "Atenção!"
    O conteúdo deste tópico poderá sofrer alterações e atualizações frequentes à medida que o projeto Celular Seguro evolui. É importante ressaltar que as metodologias apresentadas aqui são dinâmicas e podem ser ajustadas para otimizar o desenvolvimento. Mantenha-se atualizado com as versões mais recentes para acompanhar as diretrizes de trabalho.

---

### Técnicas de Elicitação de Requisitos

A seguir, serão apresentadas as principais técnicas que podem ser utilizadas no desenvolvimento do projeto Celular Seguro, destacando seus objetivos e benefícios.

#### 1.0 Entrevista

No contexto do Celular Seguro, a **entrevista** é uma técnica essencial para coletar informações diretamente das partes interessadas, como usuários finais (cidadãos que utilizariam o aplicativo) e especialistas em segurança da informação.

De acordo com Vazquez e Simões (2016), vários aspectos devem ser considerados ao conduzir uma entrevista com partes interessadas. Para o Celular Seguro, é crucial:

* **Definir claramente o objetivo da entrevista**: Por exemplo, entender os cenários de roubo/furto, as expectativas sobre a ação do aplicativo, as informações cruciais a serem reportadas, e as preocupações com privacidade e segurança dos dados.
* **Preparar um roteiro com perguntas**: Elaborar questões que abordem a usabilidade, as funcionalidades desejadas, as integrações com outros sistemas (como o de registro de ocorrências), e os fluxos de notificação e bloqueio.
* **Planejar materiais de apoio**: Utilizar gravador (com consentimento), anotações, e até mesmo protótipos iniciais para guiar a conversa.
* **Comportamento do entrevistador**: Ser polido, educado e profissional é fundamental para criar um ambiente de confiança e encorajar a abertura dos entrevistados, especialmente ao lidar com temas sensíveis como segurança.

Esses critérios, entre outros, contribuem para uma entrevista eficaz, permitindo mapear as dores e necessidades dos usuários de forma detalhada.

#### 2.0 Prototipação

A **prototipação** será uma técnica valiosa para o projeto Celular Seguro, pois permite que a equipe e os stakeholders visualizem como o aplicativo funcionará na prática antes do desenvolvimento completo.

De acordo com Vazquez e Simões (2016), se algum requisito não for atendido corretamente ou for esquecido, o protótipo facilita sua identificação. Para o Celular Seguro, isso significa:

* **Visualização dos requisitos**: Criar protótipos de baixa ou alta fidelidade para as telas de registro, de notificação de ocorrência, de bloqueio de dispositivos e de acompanhamento de status.
* **Identificação de lacunas e inconsistências**: Através da interação com o protótipo, usuários e autoridades podem apontar funcionalidades ausentes, fluxos confusos ou informações que deveriam ser mais proeminentes.
* **Exploração de diferentes versões**: A prototipação permite testar diferentes abordagens para a interface do usuário (UI) e a experiência do usuário (UX), incentivando a criatividade na busca pela solução mais intuitiva e eficaz.

Essa técnica não é útil apenas para a elicitação de requisitos, mas também para a **validação**, garantindo que o produto final atenda às expectativas das partes interessadas e seja realmente útil em situações de emergência.

#### 3.0 Observação

A **observação** é uma técnica particularmente útil quando as partes interessadas têm dificuldade em expressar suas necessidades verbalmente ou quando é necessário entender o contexto real de uso do sistema. Para o Celular Seguro, a observação pode ser aplicada para:

* **Observar processos existentes**: Analisar como as vítimas de roubo/furto atualmente registram ocorrências, quais são os gargalos e as informações que são coletadas.
* **Compreender o comportamento do usuário**: Observar como as pessoas interagem com seus celulares no dia a dia, quais são os padrões de uso e as situações de risco.

Antes de iniciar a observação, é fundamental definir os objetivos claramente, selecionar o grupo a ser observado (por exemplo, usuários de smartphones, policiais em delegacias) e estabelecer o tempo de duração da observação (VAZQUEZ; SIMÕES, 2016).

**Possíveis problemas:** Se o ambiente de trabalho ou a situação de observação sofrer interferências externas que alterem a rotina real (por exemplo, uma simulação que não se aproxima da realidade de um roubo), a observação pode se tornar ineficaz.

**Tipos de observação (De acordo com Vazquez e Simões, 2016):**

* **Passiva**: O observador não interfere no processo, apenas registra as atividades e faz questionamentos ao final. Por exemplo, observar o fluxo de uma delegacia sem intervir.
* **Ativa**: O observador interage durante o processo, fazendo perguntas e participando ativamente. Por exemplo, acompanhar um policial em uma patrulha e questionar sobre a necessidade de informações em tempo real.

#### 4.0 Brainstorming

O **brainstorming** será uma técnica  para gerar ideias inovadoras e soluções criativas para o Celular Seguro, especialmente no que diz respeito a funcionalidades de segurança, interface intuitiva e mecanismos de resposta rápida.

É uma técnica de geração de ideias em que, inicialmente, nenhuma ideia deve ser descartada ou julgada como boa ou ruim. Recomendações para um brainstorming eficaz no contexto do Celular Seguro:

* **Envolver pessoas de diferentes áreas**: Reunir desenvolvedores, designers, especialistas em segurança, policiais, representantes de operadoras de telefonia e até mesmo cidadãos comuns para diversificar as perspectivas sobre o problema e a solução.
* **Garantir que participantes de menor hierarquia se sintam à vontade para contribuir**: Promover um ambiente onde todos se sintam seguros para expressar suas ideias, sem medo de julgamento.
* **Manter o foco no assunto principal**: Evitar desvios e focar na problemática do roubo/furto de celulares e como o aplicativo pode mitigá-la.

**Método de Classificação:** As ideias mais recorrentes ou mais votadas pelo grupo devem ser priorizadas para análise e possível implementação.

**Técnicas complementares:**

* **Suposição Invertida**: Questionar pressupostos, como "e se o usuário não tiver internet no momento do roubo?", para estimular novas ideias e soluções para cenários adversos.
* **SCAMPER**: Utilizar a sigla para **S**ubstituir, **C**ombinar, **A**daptar, **M**odificar, **P**ropor novos usos, **E**liminar ou **R**eorganizar ideias existentes. Por exemplo, "Como podemos substituir o método de autenticação para maior segurança?" ou "Podemos combinar o bloqueio do aparelho com a notificação às autoridades automaticamente?".
* **Storyboarding**: Representação em sequência visual de cenários de uso do aplicativo, desde o roubo até o bloqueio e recuperação, para identificar fluxos e requisitos ocultos.
* **Role Storming**: Geração de ideias assumindo papéis distintos, como o da vítima, do policial, do golpista, para entender diferentes pontos de vista e necessidades.

---

### Referências

VAZQUEZ, Carlos; SIMÕES, Guilherme. **Engenharia de requisitos: software orientado ao negócio**. Rio de Janeiro: Brasport, 2016.

---

# Histórico de Versões

| Versão | Data de produção   | Descrição da Alteração                               | Autor(es)             | Revisor(es)      | Data de Revisão |
| :----: | :----------------: | :--------------------------------------------------: | :-------------------: | :-------------:  | :-------------: |
| 1.0    | 22/06/2025         | Desenvolvimento do artefato, especificamente os tópicos 1.0, 2.0, 3.0 e 4.0 | <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a> | 22/06/2025 |