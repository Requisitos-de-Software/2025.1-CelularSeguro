<span style="background-color:#2c2c7c; color:white; font-size:0.8em; font-weight: bold; padding:2px 6px; border-radius:4px;">Versão 1.6</span>

# Aplicativo Selecionado:

## Celular Seguro

O **Celular Seguro** foi o aplicativo escolhido para representar o foco do projeto por sua relevância social, funcionalidade direta na proteção de dados e dispositivos móveis, além de refletir princípios modernos de segurança, interoperabilidade com instituições e governança pública digital. A seguir, apresentamos um resumo técnico de suas características e exigências, com base em seu Termo de Uso oficial.

!!! Warning "Atenção!"
    O conteúdo deste tópico **poderá sofrer alterações** ao longo da Disciplina de Requisitos de Software. Portanto, as tabelas serão organizadas iniciando pela versão mais recente e finalizando com a versão mais antiga.

## Integrantes que atuaram no desenvolvimento do artefato

Esta tabela inicial terá somente os artefatos de alta relevância que cada integrante do projeto desenvolveu. O versionamento **completo** encontra-se ao final do artefato.

<font size="3"><p style="text-align: center">_Tabela de Contribuição_</p></font>

| Nome | Função |
| :--- | :--- |
| [<span style="color:gold;">Mateus Bastos</span>](https://github.com/MateuSansete)  | Autor do Artefato |
| [<span style="color:gold;">Gabriel Lima</span>](https://github.com/gabriel-lima258) | Revisor do Artefato |
| [<span style="color:gold;">Arthur Carvalho</span>](https://github.com/arthurlleite) | Revisor do documento |
| [<span style="color:gold;">Felipe das Neves</span>](https://github.com/FelipeFreire-gf) | Revisor do documento |
| [<span style="color:gold;">Leonardo de Melo</span>](https://github.com/leozinlima) | Revisor do documento |
| [<span style="color:gold;">Vitor Bessa</span>](https://github.com/Bessazs) | Revisor do documento |
| [<span style="color:gold;">repolhudo</span>](https://github.com/repolhudo) | Autor da: [[ Figura 1 ]](https://requisitos-de-software.github.io/2025.1-CelularSeguro/documento-pre-rastreabilidade/aplicativos_analisados/#sinesp-cidadao)|
| [<span style="color:gold;">Mateus Bastos</span>](https://github.com/MateuSansete) | Criação do conteúdo da documentação |
| [<span style="color:gold;">Leonardo Lima](https://github.com/leozinlima) | Ajuste de referências e hiperlink da documentação |
| [<span style="color:gold;">repolhudo junior</span>](https://github.com/arthurlleite) | Revisor do Artefato |


*Legenda:* 

**Nome** – participante da técnica. 

**Função** – papel desempenhado na priorização. 

!!! Tip "Observação"
    Frizando claramente que as contribuições de cada integrante ainda que mínimas são ainda sim muito relevantes no desenvolvimento do artefo, considere verificar o histórico de versão. 

---


## Funcionalidades Principais

- **Cadastro de dispositivo móvel** com informações como IMEI, número de telefone, operadora e modelo.
- **Emissão de alerta de perda, roubo ou furto**, acionando o bloqueio da linha, do aparelho e de apps financeiros.
- **Cadastramento de Pessoas de Confiança** para emitir alertas em nome do usuário.
- **Notificações automáticas** às operadoras e instituições financeiras parceiras.
- **Acompanhamento do status** dos bloqueios realizados.
- **Acesso multiplataforma:** disponível como app (iOS/Android) e versão web, com autenticação Gov.br.

<font size="3"><p style="text-align: center">Fonte: <a href="https://www.gov.br/mj/pt-br/acesso-a-informacao/acoes-e-programas/celular-seguro/conheca-o-celular-seguro" target="_blank">gov.br/mj - Como funciona o Celular Seguro</a></p></font>
<font size="3"><p style="text-align: center">Fonte: <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-CelularSeguro/main/Docs/assets/pdf/Conheça o Celular Seguro — Ministério da Justiça e Segurança Pública.pdf" target="_blank">📄gov.br/mj - Como funciona o Celular Seguro(PDF)</a></p></font>
<font size="3"><p style="text-align: center">Fonte: <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-CelularSeguro/main/Docs/assets/pdf/Funcionalidades Celular Seguro aplicativo Celular Seguro_.pdf" target="_blank">📄gov.br/mj - Funcionalidades Celular Seguro(PDF)</a></p></font>
---

## Termos Relevantes

<font size="3"><p style="text-align: center">Tabela 1: Termos Relevantes</p></font>

| Termo                         | Definição Técnica                                                                 |
|------------------------------|-----------------------------------------------------------------------------------|
| **Usuário**                  | Cidadão autenticado via Gov.br que utiliza o aplicativo.                         |
| **Pessoa de Confiança**      | Contato autorizado a emitir alertas em nome do usuário.                          |
| **Dispositivo Cadastrado**   | Aparelho móvel registrado voluntariamente pelo usuário.                          |
| **Evento/Incidente**         | Ocorrência de roubo, furto ou extravio do dispositivo.                           |
| **Serviço Celular Seguro**   | Conjunto de ferramentas para proteger dados e serviços móveis.                   |

<font size="3"><p style="text-align: center">Fonte: <a href="https://www.gov.br/mj/pt-br/acesso-a-informacao/acoes-e-programas/celular-seguro/termos-de-uso-politica-privacidade-programa-celular-seguro" target="_blank">gov.br/mj - Termos de Uso e Política de Privacidade</a></p></font>
<font size="3"><p style="text-align: center">Fonte: <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-CelularSeguro/main/Docs/assets/pdf/Termos de Uso e Aviso de Privacidade — Ministério da Justiça e Segurança Pública.pdf" target="_blank">📄 gov.br/mj - Termos de Uso e Política de Privacidade (PDF)</a></p></font>


---

## Responsabilidades do Usuário

- Informar **dados verdadeiros e atualizados**, próprios e dos contatos.
- Garantir que os **dados de terceiros** sejam cadastrados apenas com autorização.
- **Manter sigilo** das credenciais Gov.br.
- **Atualizar** periodicamente as informações no aplicativo.
- **Responder por danos** causados por uso indevido ou não autorizado do serviço.
- **Baixar o app apenas pelas lojas oficiais** (App Store ou Google Play).
- Realizar comunicações complementares com a **polícia, operadora e bancos** após emitir o alerta.

<font size="3"><p style="text-align: center">Fonte: <a href="https://www.gov.br/mj/pt-br/acesso-a-informacao/acoes-e-programas/celular-seguro/termos-de-uso-politica-privacidade-programa-celular-seguro" target="_blank">gov.br/mj - Termos de Uso e Política de Privacidade</a></p></font>
<font size="3"><p style="text-align: center">Fonte: <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-CelularSeguro/main/Docs/assets/pdf/Termos de Uso e Aviso de Privacidade — Ministério da Justiça e Segurança Pública.pdf" target="_blank">📄 gov.br/mj - Termos de Uso e Política de Privacidade (PDF)</a></p></font>


---

## Base Legal Aplicada

<font size="3"><p style="text-align: center">Tabela 2: Base legal</p></font>

| Legislação / Norma                          | Conteúdo Abrangido                                                             |
|--------------------------------------------|--------------------------------------------------------------------------------|
| **LGPD (Lei nº 13.709/2018)**              | Regras de tratamento, proteção e consentimento de dados pessoais.             |
| **Marco Civil da Internet (Lei nº 12.965)**| Princípios e deveres no uso da internet.                                      |
| **Lei de Acesso à Informação (12.527)**    | Direito de acesso à informações públicas.                                     |
| **Lei nº 13.460/2017**                     | Direitos dos usuários de serviços públicos.                                   |
| **Portarias e Decretos do MJSP**           | Regras internas sobre proteção de dados, governança e serviços digitais.      |

<font size="3"><p style="text-align: center">Fonte: <a href="https://www.gov.br/mj/pt-br/acesso-a-informacao/acoes-e-programas/celular-seguro/termos-de-uso-politica-privacidade-programa-celular-seguro" target="_blank">gov.br/mj - Base Legal do Programa Celular Seguro</a></p></font>
<font size="3"><p style="text-align: center">Fonte: <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-CelularSeguro/main/Docs/assets/pdf/Termos de Uso e Aviso de Privacidade — Ministério da Justiça e Segurança Pública.pdf" target="_blank">📄 gov.br/mj - Base Legal do Programa Celular Seguro (PDF)</a></p></font>

---

## Segurança e Tratamento de Dados

- Adoção de **criptografia** e segurança de rede.
- Dados são **armazenados e compartilhados** apenas com operadoras, bancos e órgãos autorizados.
- Não há transferência internacional de dados.
- Uso de **cookies de sessão** para controle e segurança no acesso web.
- Possibilidade de **anonimização** e uso para fins estatísticos após encerramento do serviço.

<font size="3"><p style="text-align: center">Fonte: <a href="https://www.gov.br/mj/pt-br/acesso-a-informacao/acoes-e-programas/celular-seguro/termos-de-uso-politica-privacidade-programa-celular-seguro" target="_blank">gov.br/mj - Termos de Uso e Política de Privacidade</a></p></font>
<font size="3"><p style="text-align: center"> Fonte: <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-CelularSeguro/main/Docs/assets/pdf/Termos de Uso e Aviso de Privacidade — Ministério da Justiça e Segurança Pública.pdf" target="_blank">📄 gov.br/mj - Termos de Uso e Política de Privacidade (PDF)</a></p></font>


---

## Contato com o MJSP

- Canal: [Ouvidoria-Geral](https://www.gov.br/ouvidorias) e [Serviço de Informação ao Cidadão (SIC)](https://www.gov.br/acessoainformacao)
- E-mail do Encarregado LGPD: [encarregadolgpd@mj.gov.br](mailto:encarregadolgpd@mj.gov.br)
- Endereço: Esplanada dos Ministérios, Bloco T - Brasília/DF, CEP 70064-900

<font size="3"><p style="text-align: center">Fonte: <a href="https://www.gov.br/mj/pt-br/canais_atendimento" target="_blank">gov.br/mj - Canais de Atendimento</a></p></font>
<font size="3"><p style="text-align: center"> Fonte: <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-CelularSeguro/main/Docs/assets/pdf/capa — Ministério da Justiça e Segurança Pública.pdf" target="_blank">📄 gov.br/mj - Canais de atendimento (PDF)</a></p></font>



---

## Bibliografia

>BRASIL. Ministério da Justiça. Sinesp Cidadão. Disponível em: <https://www.gov.br/mj/pt-br/assuntos/sua-seguranca/seguranca-publica/sinesp-1>. Acesso em: 10 abr. 2025.

>BRASIL. Ministério das Comunicações. Celular Seguro. Disponível em: <https://www.gov.br/celularseguro>. Acesso em: 10 abr. 2025.

>BRASIL. Ministério da Infraestrutura. Carteira Digital de Trânsito. Disponível em: <https://www.gov.br/pt-br/servicos/obter-carteira-digital-de-transito>. Acesso em: 10 abr. 2025.

>BRASIL. Ministério da Justiça e Segurança Pública. Programa Celular Seguro: termos de uso e política de privacidade. Disponível em: <https://www.gov.br/mj/pt-br/acesso-a-informacao/acoes-e-programas/celular-seguro/termos-de-uso-politica-privacidade-programa-celular-seguro>. Acesso em: 13 abr. 2025.



---

## Histórico de Versões 

| Versão | Data de produção   | Descrição da Alteração                               | Autor(es)             | Revisor(es)      |Data de Revisão |
| :----: | :----------------: | :--------------------------------------------------: | :-------------------: | :-------------:  |  :-----------: |
| 1.0    | 09/04/2025 | Descrição e funcionalidades principais                                                                       | [<span style="color:gold;">Mateus Bastos</span>](https://github.com/MateuSansete)                                | [<span style="color:gold;">Vitor Pereira</span>](https://github.com/Bessazs), [<span style="color:gold;">Leonardo de Melo</span>](https://github.com/leozinlima) | 09/04/2025|
| 1.1    | 10/04/2025 | Termos relevantes, responsabilidade de usuário, Base Legal Aplicada, Contato com o MJSP                      | [<span style="color:gold;">Mateus Bastos</span>](https://github.com/MateuSansete)                                | [<span style="color:gold;">Vitor Pereira</span>](https://github.com/Bessazs), [<span style="color:gold;">Leonardo de Melo</span>](https://github.com/leozinlima) | 10/04/2025|
| 1.2    | 13/04/2025 | Ajuste de referências e fonte                                                                                 | [<span style="color:gold;">Mateus Bastos</span>](https://github.com/MateuSansete)                                |  [<span style="color:gold;">Leonardo de Melo</span>](https://github.com/leozinlima) | 13/04/2025|
| 1.3    | 22/04/2025 | Ajuste de referências e fonte                                                                                 | [<span style="color:gold;">Arthur Carvalho</span>](https://github.com/arthurlleite)                                |  [<span style="color:gold;">Leonardo de Melo</span>](https://github.com/leozinlima) | 22/04/2025|
| 1.4    | 22/04/2025 |Padronização do Histórico de Versões e da Bibliografia     | [<span style="color:gold;">Arthur Carvalho</span>](https://github.com/arthurlleite)                                |  [<span style="color:gold;">Leonardo de Melo</span>](https://github.com/leozinlima) | 23/04/2025|
| 1.5    | 08/05/2025| Padronização do Histórico de Versões| <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a>| <a style="color:gold;" href="https://github.com/arthurlleite" target="_blank">Arthur Carvalho</a>>| 08/05/2025|
| 1.6    | 04/07/2025 | Inserção da tabela de contribuição| <a style="color:gold;" href="https://github.com/FelipeFreire-gf" target="_blank">Felipe das Neves</a> | <a style="color:gold;" href="https://github.com/MateuSansete" target="_blank">Mateus Bastos</a>| 04/07/2025|




