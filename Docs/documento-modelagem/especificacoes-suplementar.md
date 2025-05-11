# Especificação Suplementar
---

## Introdução

Especificação Suplementar pode ser definida como um documento em linguagem natural no qual são descritos os requisitos num sistema. Este documento captura requisitos complementares ao modelo de casos de uso do projeto [Celular Seguro](https://www.gov.br/pt-br/apps/celular-seguro-br). Ele inclui requisitos de usabilidade, desempenho, confiabilidade, suportabilidade, restrições de projeto, e requisitos legais e técnicos que não são abordados diretamente nos fluxos funcionais.. A metodologia mais utilizada para a produção de uma especificação suplementar é a **FURPS+**.

---

## Metodologia

Para a elaboração deste artefato, será adotada uma versão adaptada do modelo FURPS+, uma metodologia que classifica os requisitos do sistema em seis categorias principais: 

- **Functionality** (Funcionalidade)
- **Usability** (Usabilidade) 
- **Reliability** (Confiabilidade)
- **Performance** (Desempenho)
- **Supportability** (Suportabilidade) 
- e o grupo “+”, que abrange outros requisitos não funcionais, como **requisitos de design**, **implementação**, **interface** e **físicos**. Essa estrutura visa organizar e detalhar os requisitos de maneira sistemática e compreensível.

---

## Identificação do Projeto

- Projeto: **CELSEG** – [Celular Seguro](https://www.gov.br/pt-br/apps/celular-seguro-br)
- Requisitante: **Secretaria Nacional do Consumidor** ([Senacon](https://www.gov.br/mj/pt-br/assuntos/seus-direitos/consumidor))
- Gerente de Projetos: [Gabriel Lima](https://github.com/gabriel-lima258)

---

## Funcionalidade

Os requisitos funcionais foram elicitados na seção de elicitação das seguintes técnicas: [Análise de Documentos](./AnalisedeDocumentos.md), [Questionário](./Questionario.md), [Brainstorming](./Brainstorming.md) e [Observação](./Observacao.md)

A legenda para cada sigla abaixo:

- **RFx**: Requisito Funcional nºx
- **RNFx**: Requisito Não-Funcional nºx
- **ADDx**: Requisito nºx elicitado pela Análise de Documentos
- **QSx**: Requisito nºx elicitado pelo Questionário
- **BSx**: Requisito nºx elicitado pelo Brainstorming
- **OBSx**: Requisito nºx elicitado pela Observação

### Requisitos Funcionais (RF)

<font size="3">
  <p style="text-align:center; margin:-2em 0 0; line-height:1.2;">
    Tabela 1: Requisitos Funcionais do Celular Seguro<br>
  </p>
</font>

| **ID** | **Requisito Elicitado**                                                                                                                                                | **Rastreabilidade** |
| ------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| RF01  | O sistema deve permitir autenticação via Gov.br utilizando CPF e senha.                                                | ADD01, BS09, OBS1, OBS2, OBS17           |
| RF02  | O aplicativo deve exibir os Termos de Uso e requerer aceite na primeira abertura.                           | ADD02, OBS14           |
| RF03  | O usuário poderá cadastrar múltiplos celulares vinculados ao CPF.                              | ADD03, OBS11           |
| RF04  | O aplicativo deve permitir o cadastro de contatos de confiança para alertas em emergências.           | ADD04, BS12, OBS7            |
| RF05  | O sistema deve emitir alertas de bloqueio rápidos, via botão de emergência. | ADD05, BS15, OBS9            |
| RF06  | O usuário poderá selecionar o tipo de bloqueio: Modo Recuperação ou Bloqueio Total.     | ADD06            |
| RF07  | O sistema deve gerar número de protocolo após emissão de alerta.               | ADD07            |
| RF08  | O alerta deve ser enviado automaticamente para operadoras e instituições parceiras. | ADD08            |
| RF09  | O aplicativo deve permitir consulta de status do IMEI antes da compra. | ADD09, OBS10           |
| RF10  | O sistema deve estar disponível como aplicativo móvel (Android/iOS) e versão web, com as mesmas funcionalidades.    | ADD10, BS13           |
| RF11  | O sistema deve permitir emitir mais de um alerta por linha telefônica.                         | ADD11            |
| RF12  | O sistema deve notificar o usuário se um novo chip for inserido após modo Recuperação.                                  | ADD12, BS26            |
| RF13  | O sistema deve exibir um tutorial passo a passo para o usuário.                                 | BS11, OBS6, QS04            |
| RF14  | O aplicativo permite o registro de boletim de ocorrência.                                 | OBS8, QS02, QS09            |
| RF15  | O aplicativo deve permitir localizar o celular perdido e rastrear localização.                                  | BS04, RF01, QS01, BS06, BS05, BS20, BS24, BS35            |
| RF16  | O aplicativo deve exibir histórico de movimentação e permitir exportação em PDF.                                 | BS05, BS22, OBS5           |
| RF17  | O aplicativo envia notificações push sobre eventos e atividades suspeitas.                                  | OBS4, QS08, RF06, BS07, BS21            |
| RF18  | O usuário pode redefinir senha via e-mail.                                 | OBS3            |
| RF19  | O aplicativo deve redirecionar para ferramentas nativas de localização (como “Buscar” do iCloud).                                 | OBS13           |
| RF20  | O sistema deve permitir edição do perfil do usuário.                                 | OBS12           |
| RF21  | O sistema deve permitir emissão de som remoto para facilitar localização.                                 | BS19           |
| RF22  | O sistema deve registrar logs das ações remotas para auditoria.                                 | BS33           |
| RF23  | O aplicativo deve permitir compartilhamento temporário de localização com contatos.                                  | BS30            |
| RF24  | O sistema deve integrar com operadora para bloquear chip diretamente.                                  | BS08           |
| RF25  | O sistema deve permitir a recuperação do aparelho bloqueado caso reencontrado.                                  | QS08          |

<font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

### Requisitos Não‑Funcionais (RNF)

<font size="3">
  <p style="text-align:center; margin:-2em 0 0; line-height:1.2;">
    Tabela 2: Requisitos Não Funcionais do Celular Seguro
  </p>
</font>

| **ID** | **Requisito Elicitado**                                                                                                                                                 | **Rastreabilidade** |
| ------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| RNF01  | O aplicativo deve apresentar interface intuitiva e acessível, com menus claros, ícones bem definidos e design acessível.                                                   | BS36, OBS15, OBS18, QS17, QS7, QS12, Q19          |
| RNF02  | O tempo de carregamento das páginas deve ser inferior a 2 segundos em 4G.                     | OBS16, BS39, RNF23           |
| RNF03  | O sistema deve estar disponível 24×7 para todos os cidadãos brasileiros. | ADD13, OBS21, BS40           |
| RNF04  | Os alertas devem ser enviados em tempo mínimo (idealmente instantâneo) e bloqueios realizados em minutos.                | ADD14         |
| RNF05  | O sistema deve seguir requisitos de segurança da informação (criptografia, LGPD, etc.).                                  | ADD15, BS47, BS48           |
| RNF06  | O aplicativo deve apresentar feedback (confirmação) após ações importantes.                                                                           | OBS20, QS04          |
| RNF07  | O sistema deve garantir compatibilidade com as principais versões de Android, iOS e navegadores.                                             | ADD17, BS57           |
| RNF08  | O serviço deve ser gratuito, sem cobrança de uso ou download.                                            | ADD18        |
| RNF09  | O sistema deve cumprir normas e legislação (Anatel, Febraban, LGPD).                                             | ADD19           |
| RNF10  | O aplicativo deve oferecer acessibilidade: suporte a leitor de tela, VLibras, ajuste de contraste e fonte.                                             | BS42, BS43, OBS18          |
| RNF11  | O sistema deve apresentar estabilidade e funcionamento adequado durante emergências.                                             | QS9, RNF03           |
| RNF12  | O sistema deve possuir central de ajuda acessível online e offline.                                             | BS52           |

<font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

---

## Usabilidade

Define requisitos para garantir que o sistema seja fácil de usar, acessível e eficiente para o usuário final.

<font size="3">
  <p style="text-align:center; margin:-2em 0 0; line-height:1.2;">
    Tabela 3: Requisitos de Usabilidade
  </p>
</font>

| **ID** | **Descrição** | 
| ------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USA01  | Interface responsiva compatível com smartphones e tablets. | 
| USA02  | O tempo de carregamento das páginas deve ser inferior a 2 segundos em 4G. |
| USA03  | Tempo de resposta inferior a 2 segundos para consultas simples. |
| USA04  | O sistema deve apresentar cores compatíveis com a opção de alto contraste. |
| USA05  | Fluxo de registro com no máximo 3 passos para usuários finais. |

<font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

Legenda:

- **USAx**: Requisito de Usabilidade nºx

---

## Confiabilidade

Especifica o quão estável, preciso e tolerante a falhas o sistema deve ser.

<font size="3">
  <p style="text-align:center; margin:-2em 0 0; line-height:1.2;">
    Tabela 4: Requisitos de Confiabilidade
  </p>
</font>

| **ID** | **Descrição** | 
| ------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CON01  | O sistema deve seguir a Lei Geral de Proteção de Dados (LGPD). | 
| CON02  | Precisão de 99% nos dados retornados. |
| CON03  | O sistema deve possuir as informações atualizadas e condizentes com a realidade. |
| CON04  | O sistema deve possuir backups dos dados dos usuários e eventos. |
| CON05  | O sistema deve ser acessível 24 horas por dia, 7 dias por semana. | 
| CON06  | Taxa de erro crítica inferior a 1 a cada 100 mil transações. | 
| CON07  | O sistema deve impedir que o usuário realize atividades que possa colocar a integridade do sistema e de outros usuários em risco. | 

<font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

Legenda:

- **CONx**: Requisito de Confiabilidade nºx

---

## Desempenho

Define metas relacionadas à eficiência do sistema, como tempo de resposta, número de usuários e consumo de recursos.

<font size="3">
  <p style="text-align:center; margin:-2em 0 0; line-height:1.2;">
    Tabela 5: Requisitos de Desempenho
  </p>
</font>

| **ID** | **Descrição** | 
| ------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DES01  | Suporte a até 1 milhão de acessos simultâneos. | 
| DES02  | Tempo máximo de resposta: 3 segundos. |
| DES03  | Tempo de carregamento inicial: até 200ms. |
| DES04  | O sistema deve possuir uma navegação fluida, sem qualquer travamentos que possa atrapalhar ações. |
| DES05  | Escalabilidade horizontal automática. | 
| DES06  | Uso máximo de CPU por serviço: até 70%. | 

<font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

Legenda:

- **DESx**: Requisito de Desempenho nºx

---

## Suportabilidade

Envolve os requisitos relacionados ao suporte e manutenção do sistema. Estabelece como o sistema deve ser fácil de manter, atualizar e diagnosticar, garantindo sua evolução ao longo do tempo.

<font size="3">
  <p style="text-align:center; margin:-2em 0 0; line-height:1.2;">
    Tabela 6: Requisitos de Suportabilidade
  </p>
</font>

| **ID** | **Descrição** | 
| ------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| SUP01  | Documentação técnica disponível via Swagger e README. | 
| SUP02  | O sistema deve possuir uma capacidade de extensão para adicionar novas funcionalidades e acompanhar as mudanças. |
| SUP03  | Monitoramento com alertas em tempo real via Grafana. |
| SUP04  | Ambiente de staging para validações pré-produção. |
| SUP05  | Canal de suporte com SLA de até 8h úteis. | 
| SUP06  | O sistema deve possuir uma rastreabilidade com mecanismos para registrar e rastrear mudanças e correções ao longo do tempo, incluindo controle de versão e registros de alterações. | 
| SUP07  | O sistema deve possuir uma tolerância a falhas para garantir que o sistema possa lidar com falhas adequadamente, por meio de mecanismos de recuperação, detecção de falhas, manutenção da integridade dos dados, backups regulares e restauração rápida em caso de falhas. | 
| SUP08  | Código modular com testes automatizados (>90% de cobertura). | 

<font size="3"><p style="text-align: center">Fonte: [Gabriel Lima](https://github.com/gabriel-lima258).</p></font>

Legenda:

- **SUPx**: Requisito de Suportabilidade nºx

---

## Restrições do Projeto

Estabelece restrições técnicas ou organizacionais que precisam ser consideradas e respeitadas ao longo do processo de desenvolvimento do sistema, como limitações de infraestrutura, compatibilidade com tecnologias existentes, políticas internas ou diretrizes regulatórias.

---

#### Autenticação via GOV.br
- A autenticação de usuários deve obrigatoriamente ser realizada por meio da plataforma [Gov.br](https://www.gov.br/pt-br), com nível Prata ou Ouro. Isso garante confiabilidade da identidade e integração segura com dados sensíveis.
- É exigido em aplicações que envolvem dados pessoais ou ações com valor jurídico.

---

#### Hospedagem em nuvem brasileira
O sistema deve ser hospedado em provedores que garantam data centers localizados no Brasil, como:

- [GovCloud](https://aws.amazon.com/pt/govcloud-us/?whats-new.sort-by=item.additionalFields.postDateTime&whats-new.sort-order=desc)
- [Serpro Cloud](https://campanhas.serpro.gov.br/serpro-multicloud/)
- [AWS com infraestrutura no Brasil](https://aws.amazon.com/)

Justificativa: cumprimento da LGPD, que exige que dados de brasileiros sejam processados em território nacional quando possível.

---

#### Design System GOV.BR

A interface deve seguir obrigatoriamente o Design System do [Gov.br](https://www.gov.br/pt-br), respeitando:

- Paleta de cores institucional
- Componentes visuais padronizados (botões, cabeçalhos, campos etc.)
- Tipografia e responsividade

Justificativa: garantir identidade visual unificada e experiência de uso padronizada nos serviços públicos digitais.

---

#### Integrações obrigatórias

O sistema deve oferecer integração com os seguintes parceiros institucionais:

- [Anatel](https://www.gov.br/anatel/pt-br) – para consulta e bloqueio do IMEI.
- Operadoras de telefonia – para bloqueio de chip.
- [Secretarias de Segurança Pública (SSPs)](http://www.seguranca.sp.gov.br/institucional) – para compartilhamento de dados de boletins de ocorrência.

Essas integrações devem ser realizadas por meio de APIs REST autenticadas e seguras, e são obrigatórias para o funcionamento correto do fluxo de notificação e bloqueio.

---

## Outras Requisitos

---

## Componentes Comprados

---

## Interfaces

---

## Requisitos de Licenciamento

--- 

## Bibliografia

> HENRIQUE, Matheus. Especificação Suplementar. Repositório do Grupo Bilheteria Digital da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#metodologia>. Acesso em: 11 maio 2025.

## Histórico de Versões 

| Versão | Data de produção   | Descrição da Alteração                               | Autor(es)             | Revisor(es)      |Data de Revisão |
| :----: | :----------------: | :--------------------------------------------------: | :-------------------: | :-------------:  |  :-----------: |
| 1.0    | 09/05/2025         | Criação do documento                           |<a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a>    | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>| 09/05/2025|
| 1.1    | 11/05/2025         | Criação Introdutória dos temas de Funcionalidade, Usabilidade, Desempenho, Suportabilidade, Restrições do Projeto                          |<a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a>    | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Vitor Bessa</a>| 11/05/2025|