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

Os requisitos funcionais do projeto [Celular Seguro](https://github.com/Requisitos-de-Software/2025.1-CelularSeguro) foram elicitados na seção de elicitação das seguintes técnicas: [Análise de Documentos](../documento-elicitacao/AnalisedeDocumentos.md), [Questionário](../documento-elicitacao/Questionario.md), [Brainstorming](../documento-elicitacao/Brainstorming.md), [Observação](../documento-elicitacao/Observacao.md) e [Storytelling](../documento-elicitacao//Storytelling.md). 

---

## Usabilidade

Define requisitos para garantir que o sistema seja fácil de usar, acessível e eficiente para o usuário final.

<font size="3">
  <p style="text-align:center; margin:-2em 0 0; line-height:1.2;">
    Tabela 3: Requisitos de Usabilidade
  </p>
</font>

| **ID** | **Descrição** | **Verificação** |
| ------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------|
| USA01  | O tempo de carregamento das páginas inferior a 2 segundos em aparelhos com 4G/5G. | Tempo |
| USA02  | Tempo de resposta inferior a 2 segundos para consultas simples. | Tempo |
| USA03  | O sistema deve apresentar cores compatíveis com a opções de contraste. | Acessibilidade (WCAG) |
| USA04  | Fluxo de registro com no máximo 3 passos | Etapas |
| USA04  | O tempo de adaptação ao sistema leva cerca de 1 a 3 dias ao seguir o guia de usuário | Tempo |

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

| **ID** | **Descrição** | **Verificação** |
| ------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------- |
| CON01  | O sistema deve seguir a Lei Geral de Proteção de Dados (LGPD). | Checklist |
| CON02  | Precisão de 99% nos dados retornados. | Porcentagem |
| CON03  | Falhas críticas devem ser detectadas automaticamente em até 30 segundos. | Tempo |
| CON04  | O sistema deve possuir backups dos dados com até 30 minutos dos usuários e eventos. | Tempo |
| CON05  | O sistema deve ser acessível 24 horas por dia, 7 dias por semana. | Tempo |
| CON06  | Taxa de erro crítica < 1/100.000 transações. | Logs |
| CON07  | Suspensão temporária dos serviços Bancários executados de forma remota em até 30 minutos | Tempo |

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

| **ID** | **Descrição** |  **Verificação** |
| ------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------|
| DES01  | O sistema deve ser capaz de manter tempo de resposta inferior a 3 segundos sob carga de até 1 milhão de acessos simultâneos, com uso de CPU ≤ 80%. | Porcentagem |
| DES02  | Tempo máximo de resposta: 3 segundos. | Tempo |
| DES03  | Tempo de carregamento inicial: até 200ms. | Tempo |
| DES04  | O sistema deve possuir uma navegação fluida, sem qualquer travamentos além de 10 segundos que possa atrapalhar ações. | Tempo |
| DES05  | O sistema deve escalar horizontalmente de forma automática em no máximo 60 segundos sempre que o uso de CPU ultrapassar 70% | Porcentagem, Tempo | 

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

| **ID** | **Descrição** |  **Verificação** |
| ------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------ |
| SUP01  | Documentação técnica disponível via Swagger e README. | Documentação |
| SUP02  | O sistema deve permitir a adição de novos módulos com tempo médio de integração ≤ 8h, desde que respeitem os contratos definidos pelas **APIs**. | Tempo |
| SUP03  | Monitoramento com alertas em tempo real via Grafana. | Logs |
| SUP04  | Ambiente de staging para validações pré-produção. | Deploy, Testes |
| SUP05  | Canal de suporte com SLA de até 8h úteis. | Tempo |
| SUP06  | O sistema deve possuir uma rastreabilidade com mecanismos para registrar e rastrear mudanças e correções ao longo do tempo, incluindo controle de versão e registros de alterações. | Versionamneto |
| SUP07  | 	Após falhas, a integridade dos dados deve ser garantida com 0% de corrupção em logs de validação | Porcentagem | 
| SUP08  | Código modular com testes automatizados (>90% de cobertura). | Porcentagem |

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

Segue o [PDF](./Padrão%20Digital%20de%20Governo%20-%20Introdução%20-%20Padrão%20Mínimo.pdf) dos padrões mínimos aplicados ao Design System do GOV.br.

---

#### Integrações obrigatórias

O sistema deve oferecer integração com os seguintes parceiros institucionais:

- [Anatel](https://www.gov.br/anatel/pt-br) – Para consulta e bloqueio do IMEI.
- [ABR TELECOM](https://consultanumero.abrtelecom.com.br/consultanumero/consulta/consultaSituacaoAtualCtg) – Recebimento e validação das informações de pedido de bloqueio de terminais telefônicos móveis para envio às prestadoras participantes (Algar Telecom, Claro, Sercomtel, Telefônica, Tim, Datora Telecom, Emnify Brasil e Surf Telecom).
- [Delegacias Virtuais](https://www.gov.br/mj/pt-br/acesso-a-informacao/acoes-e-programas/celular-seguro/delegacias-virtuais-1/) – Compartilhamento de dados para realização de boletins de ocorrência.

Segue o [PDF](./Lista%20de%20Parceiros%20—%20Ministério%20da%20Justiça%20e%20Segurança%20Pública.pdf) dos demais parceiros do Aplicativo **Celular Seguro**.

---

## Outras Requisitos

Esta seção documenta requisitos técnicos globais que não estão diretamente ligados ao comportamento funcional do sistema, mas que são essenciais para garantir conformidade legal, compatibilidade, segurança, desempenho e operação adequada em seu ambiente de uso.

---

#### Padrões Aplicáveis

São normas, leis e especificações técnicas que o sistema deve obrigatoriamente seguir, garantindo segurança jurídica, acessibilidade e interoperabilidade:

- [LGPD](./L13709.pdf) **(Lei Geral de Proteção de Dados – Lei nº 13.709/2018)**:
O sistema deve proteger os dados pessoais dos usuários, garantindo base legal, consentimento, anonimização e direitos como acesso e exclusão de dados
- [WCAG 2.1](https://www.w3.org/TR/WCAG21/) – Nível AA: 
Toda interface deve estar em conformidade com as Diretrizes de Acessibilidade para Conteúdo Web (Web Content Accessibility Guidelines), permitindo uso por pessoas com deficiência.
- [OpenAPI 4.1](https://swagger.io/specification/v3/):
As APIs devem seguir o padrão OpenAPI (Swagger), garantindo documentação estruturada, integração fácil e testes automatizados.
- [HTTPS com TLS 1.3](https://datatracker.ietf.org/doc/html/rfc8446):
Toda comunicação entre cliente e servidor deve ser criptografada com protocolo HTTPS moderno (TLS 1.3 ou superior) para prevenir interceptações.
- [RESTful API Design]():
As APIs devem seguir o estilo REST, com uso de verbos HTTP corretos, URIs significativas, retorno em JSON e versionamento de endpoints.

---

#### Requisitos do Sistema

Descreve as características mínimas da infraestrutura e plataformas onde o sistema deve operar.

Banco de dados: PostgreSQL 15 ou superior, com suporte a replicação, backups automáticos e criptografia em repouso.

Compatibilidade com navegadores:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari

Hospedagem: Infraestrutura de nuvem compatível com escalabilidade horizontal, localizada no Brasil.

Autenticação: Integração com a plataforma [Gov.br](https://www.gov.br/pt-br) via OAuth2, usando login social e validação de nível de segurança (prata ou ouro).

---

#### Requisitos Ambientais
Estes requisitos consideram as condições práticas de uso do sistema, como conectividade, perfil dos usuários e contexto de operação.

##### Ambiente de uso predominante:
- O sistema será usado majoritariamente por dispositivos móveis, exigindo design responsivo e foco em usabilidade touch.

##### Tolerância a falhas de rede:
- Deve implementar recurso de retentativa automática para falhas temporárias de conexão, especialmente durante envio de formulários.

##### Baixo consumo de dados:
- O sistema deve ser otimizado para uso em redes móveis (3G/4G), com carregamento progressivo e recursos como cache e compressão GZIP.

##### Acessibilidade regional:
- Devido à abrangência nacional, o sistema deve lidar com diferentes fusos horários, conexões lentas e dispositivos com baixa resolução.

##### Recursos de acessibilidade nativa:
- Compatibilidade com leitores de tela, contraste adequado, teclas de navegação e rótulos semânticos em HTML.
  
---

## Componentes Comprados

Esta seção lista todos os componentes de software, serviços ou recursos adquiridos ou contratados para a construção do sistema Celular Seguro. Esses componentes são utilizados para acelerar o desenvolvimento, atender a requisitos legais ou oferecer infraestrutura de operação.

Cada item abaixo pode envolver licenciamento, integração técnica ou acordos de uso com fornecedores públicos ou privados.

---

#### [Certificado Digital ICP-Brasil](https://www.gov.br/iti/pt-br/assuntos/icp-brasil)

- Finalidade: Garantir autenticação segura e assinatura digital de transações com valor legal.
- Descrição: Utilizado para assinar comunicações oficiais, registros e autenticar o servidor da aplicação.
- Obrigatório: Sim, conforme padrão de segurança e interoperabilidade para órgãos federais.
  
**Referência**: [Infraestrutura de Chaves Públicas Brasileira (ICP-Brasil) – ITI](https://www.gov.br/iti/pt-br/assuntos/icp-brasil).

---

#### [Biblioteca de Autenticação do Login Único Gov.br](https://acesso.gov.br/roteiro-tecnico/)

- Finalidade: Permitir o login unificado com CPF e validação de identidade do cidadão.
- Descrição: Fornecida pelo governo federal (Serviço de Autenticação Centralizada), integra via OAuth2 e OpenID Connect.
- Obrigatório: Sim, para uso de dados pessoais ou serviços vinculados ao CPF do usuário.
  
**Referência**: [Manual de Integração Gov.br]((https://acesso.gov.br/roteiro-tecnico/)).

---

#### [Infraestrutura de Envio de Mensagens (e-mail e SMS)](https://docs.aws.amazon.com/ses/)

- Finalidade: Notificar usuários sobre atualizações no status do celular furtado/roubado.
- Descrição: Utiliza serviços como [AWS SES](https://docs.aws.amazon.com/ses/) (Simple Email Service) para e-mails transacionais e [Twilio](https://www.twilio.com/sms) ou [Serpro](https://servicos.serpro.gov.br/mensageria/) Mensageria para envio de SMS.
- Justificativa: Reduz custo e garante entregabilidade alta e escalável.
- Licenciamento: Por volume de mensagens enviadas (modelo pay-as-you-go).
  
---

#### [Biblioteca de Componentes Visuais do Gov.br](https://www.gov.br/ds/introducao/sobre)

- Finalidade: Garantir padronização visual e conformidade com o Design System do Governo Federal.
- Descrição: Biblioteca de CSS e componentes React que seguem diretrizes de identidade visual oficial.
- Obrigatório: Sim, para padronização e reconhecimento visual de serviços públicos.

Segue o [PDF](./Padrão%20Digital%20de%20Governo%20-%20Introdução%20-%20Padrão%20Mínimo.pdf) dos padrões mínimos aplicados ao Design System do GOV.br.

---

#### [Serviços de Hospedagem e Segurança em Nuvem]()

- Finalidade: Disponibilizar o sistema de forma segura, escalável e com alta disponibilidade.
- Descrição: Pode utilizar [AWS](https://www.gov.br/governodigital/pt-br/estrategia-de-governo-digital), [GovCloud](https://aws.amazon.com/govcloud-us/), [Serpro Cloud](https://servicos.serpro.gov.br/mensageria/) ou outra nuvem com data center no Brasil.

Recursos envolvidos:

- Instâncias EC2 (servidores)
- Balanceadores de carga
- Firewalls e gateways
- Backup automatizado

Justificativa: Permite cumprir exigências da LGPD e estratégias do Governo Digital.

---

#### [Serviço de Integração com Operadoras e Anatel](https://www.gov.br/anatel/pt-br)

- Finalidade: Enviar comandos de bloqueio diretamente para bases externas.
- Descrição: Sistemas como o SINESP ou plataformas fornecidas por operadoras podem exigir licenças ou acordos de cooperação.
- Licenciamento: Depende de contrato institucional ou integração oficial.

---

## Interfaces

As interfaces definem como o sistema Celular Seguro se conecta com seus usuários, outros sistemas, dispositivos físicos e infraestruturas de rede. São fundamentais para garantir interoperabilidade, usabilidade e integração com parceiros institucionais.

---

#### Interfaces de Usuário

As interfaces de usuário são as formas de interação direta entre os usuários e o sistema.

**Componentes principais**:

- Interface Web (PWA)
- Responsiva, otimizada para dispositivos móveis.
- Permite consulta de IMEI e registro de roubo.
- Compatível com leitores de tela e navegação por teclado.
- Portal Administrativo
- Voltado para agentes autorizados (SSPs, Anatel, Senacon).
- Oferece filtros, exportação de dados e painel estatístico.
- Interface Gov.br
- Tela de redirecionamento para login único.
- Permite autenticação segura via CPF.
- Design Padronizado (Gov.br Design System)
- Botões, cabeçalhos e formulários seguem padrões do governo federal.
- Mensagens e feedbacks ao usuário
- Sistema fornece mensagens claras em casos de sucesso, erro ou ação pendente.

---

#### Interfaces de Hardware

O sistema é 100% baseado em nuvem, portanto não possui integração direta com dispositivos físicos. No entanto, há considerações indiretas:

**Considerações relevantes**:

- Compatibilidade com dispositivos móveis
- O sistema deve funcionar corretamente em celulares com Android/iOS.
- Leitores de impressão digital ou reconhecimento facial
- Utilizados pelo Gov.br, não são responsabilidade direta do sistema, mas influenciam na autenticação.
- Dispositivos com acessibilidade nativa (ex: TalkBack, VoiceOver)
- O sistema precisa suportar tecnologias assistivas já embarcadas no hardware.
- Conexão com GPS ou sensores.

**Não aplicável**: o sistema não coleta nem usa dados de localização do dispositivo.

---

#### Interfaces de Software

Estas interfaces definem como o Celular Seguro se comunica com outros sistemas externos ou módulos internos via software.

**Integrações principais**:

- API RESTful com Anatel
- Envio de requisições de bloqueio de IMEI e consultas à base oficial.
- API RESTful com Operadoras
- Comunicação padronizada para bloqueio de chip associado ao IMEI informado.
- Integração com o Gov.br (OAuth2 / OpenID Connect)
- Para login e obtenção de dados do cidadão autenticado.
- Webhooks para notificações assíncronas
- Parceiros como SSPs podem ser notificados automaticamente via webhook.
- Swagger/OpenAPI para documentação
- APIs públicas documentadas para que terceiros possam integrar.

---

#### Interfaces de Comunicação

Define os protocolos, padrões e canais pelos quais o sistema se comunica com usuários e sistemas externos.

**Especificações**:

- Protocolo HTTPS com TLS 1.3
- Toda comunicação deve ser criptografada, segura e auditável.
- Formato de dados JSON
- Todos os endpoints da API aceitam e retornam dados em JSON.
- Versionamento de API
- URLs devem incluir versão (/api/v1/...) para garantir compatibilidade futura.
- Suporte a redes móveis e Wi-Fi
- O sistema deve funcionar adequadamente mesmo em redes 3G com latência elevada.
- VPN ou API Gateway para parceiros críticos
- Comunicação com órgãos sensíveis pode exigir canais exclusivos via VPN ou gateway autenticado.

---

## Requisitos de Licenciamento

Esta seção especifica os requisitos legais e contratuais relacionados ao uso de softwares, serviços, bibliotecas, componentes externos e dados utilizados no sistema Celular Seguro. O cumprimento dessas exigências garante que o projeto esteja em conformidade com leis de propriedade intelectual, normas de uso público e acordos de integração com terceiros.

Segue o [Termo de Uso](../TermoUso.pdf) do Celular Seguro.

--- 

## Referência Bibliográfica

>  SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 013a. Universidade de Brasília – UnB, 2023. Apresentação de slides. Disponível em: <https://aprender3.unb.br/pluginfile.php/3096118/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf>

> Artefato: Especificações Suplementares. Centro de Informática - UFPE. Disponível em: <https://www.cin.ufpe.br/~gta/rup-vc/core.base_rup/workproducts/rup_supplementary_specification_F5ACAA22.html>.

## Bibliografia

> HENRIQUE, Matheus. Especificação Suplementar. Repositório do Grupo Bilheteria Digital da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#metodologia>. Acesso em: 11 maio 2025.

## Histórico de Versões 

| Versão | Data de produção   | Descrição da Alteração                               | Autor(es)             | Revisor(es)      |Data de Revisão |
| :----: | :----------------: | :--------------------------------------------------: | :-------------------: | :-------------:  |  :-----------: |
| 1.0    | 09/05/2025         | Criação do documento                           |<a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a>    | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>| 09/05/2025|
| 1.1    | 11/05/2025         | Criação Introdutória dos temas de Funcionalidade, Usabilidade, Desempenho, Suportabilidade, Restrições do Projeto                          |<a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a>    | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>| 11/05/2025|
| 1.2    | 11/05/2025         | Adição de referências e termos de uso do aplicativo |<a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a>    | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>| 11/05/2025|
| 1.3    | 13/05/2025         | Correções relacionadas a referências de pdf e sugestões de correções da page |<a style="color:gold;" href="https://github.com/gabriel-lima258" target="_blank">Gabriel Lima</a>    | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Felipe das Neves</a>| 13/05/2025|
