# **Nexus Logística**
<p align="center">
  <img src="" width="500">
  
<br>
<p align="center">
  
  <a href ="#objetivo-do-projeto">  Objetivo do Projeto </a>  | 
  <a href ="#visão-d0-projeto"> Visão do Produto </a>  |
  <a href ="#metodologia"> Metodologia </a>  |
  <a href ="tecnologias-utilizadas"> Tecnologias Utilizadas </a>  |
  <a href ="#sprints"> Sprints </a>  |
  <a href ="#backlog-do-produto"> Backlog do Produto </a>  | 
  <a href ="#equipe"> Equipe </a>
</p>
</br>

## Objetivo do Projeto 📌
Desenvolver uma **plataforma de Business Intelligence (BI)** para disponibilizar informações sobre a **eficiência portuária**, com base nos tempos de processamento nos portos brasileiros e dados estatísticos da ANTAQ.  

O sistema deve permitir analisar e comparar a **produtividade dos terminais portuários**, identificar **principais motivos de paradas**, avaliar **tempos de operação** e fornecer **insights visuais interativos** para apoiar a tomada de decisão.


## Principais Análises 🔍
✅ **Eficiência dos terminais portuários** – produtividade comparativa entre terminais com base em infraestrutura instalada e carga movimentada  
✅ **Avaliação dos tempos de operação** – identificar portos com maior tempo de espera e mais ágeis na operação  
✅ **Paradas portuárias** – levantar os Top N motivos de paradas e suas variações ao longo do ano  
✅ **Movimentação** – principais portos em termos de quantidade transportada e número de operações mensais  
✅ **Cargas movimentadas** – principais tipos de carga movimentados  


## Visão do Produto 💡 
- Permitir segmentação por terminal, com ranking por eficiência e evolução da quantidade transportada por mês  
- Disponibilizar filtros e buscas personalizadas para análises específicas  
- Oferecer painel de estatísticas com visualização gráfica interativa dos tempos de operação, movimentações e paradas portuárias  

O produto final deve ser uma plataforma funcional, responsiva e intuitiva, apta a ser apresentada à comunidade acadêmica e possivelmente disponibilizada para uso público.

## Metodologia 📚 
- Utilização de **Scrum** para organização do trabalho em **Sprints**  
- Definição do **MVP** priorizando atividades de maior valor para o cliente  
- Elaboração do **Backlog do Produto** e divisão em Backlogs de Sprint  
- Estimativa de tempo e distribuição otimizada das atividades entre os desenvolvedores  
- Registro adequado de **DoR** (Definition of Ready) e **DoD** (Definition of Done)  

## Tecnologias Utilizadas 🚀 
- **Google Colab** para normalização, limpeza e análise inicial dos dados (RN.P.1)  
- **Python 3+** e **DAX** para desenvolvimento do back-end (RN.P.2)  
- **Power BI** para desenvolvimento do front-end (RN.P.3)  
- **GitHub** para controle de versão dos artefatos de projeto (RN.P.4)  
- **Interface responsiva e intuitiva** (RN.P.5 e RN.P.6)  

<br>

## Sprints 📅

Sprint 🎯 | Previsão | Status|
|------|--------|------|
|Kick Off | 12/09/2025 | Em andamento |
|1️⃣| 03/10/2025| A fazer |
|2️⃣| 24/10/2025 | A fazer |
|3️⃣| 14/11/2025 | A fazer |
|Feira de Soluções| 04/12/2025 | A fazer |

<br>

## Backlog do Produto 📋

| Rank  | Prioridade | User Story | Estimativa  | Sprint | Requisito |
|:-----:|:----------:|:----------:|:-----------:|:------:|:---------:|
|1|	Como analista de dados, quero acessar e baixar dados da ANTAQ via Colab, para iniciar o tratamento e análise. |	Alta |	4h	| Sprint 1	| RN.P.2 |
|2|	Como analista de dados, quero normalizar e limpar a base (remover duplicados e nulos), para manter consistência. |	Alta	| 6h	| Sprint 1	| RN.P.1 |
|3|	Como analista de dados, quero calcular tempos médios de operação portuária, para avaliar eficiência. |	Alta	| 4h	| Sprint 1	| RN.P.2 |
|4| Como analista de dados, quero construir o primeiro dashboard no Power BI, para ter visão geral de portos, cargas e operações. |	Média |	4h | Sprint 1 |	RN.P.2 |
|5|	Como analista de dados, quero implementar filtros avançados (período, tipo de carga), para análises personalizadas. |	Alta |	8h	| Sprint 1 | RN.P.1 |
|6|	Como analista de dados, quero criar painéis interativos com ranking de eficiência dos portos, para identificar portos mais produtivos. | Alta | 10h | Sprint 1 | RN.P.1 |
|7|	Como analista de dados, quero testar dashboards em diferentes resoluções de tela, para identificar ajustes de responsividade. | Média	| 6h | Sprint 1	| RN.P.2 |
|8|	Como analista de dados, quero ajustar layouts do Power BI para versão mobile, para que usuários possam acessar via celular.	| Média	| 5h |	Sprint 1	| RN.P.1 |
|9|	Como coordenador de operações, quero validar dashboards em notebook, tablet e celular, para garantir boa visualização para todos os stakeholders. |	Alta | 5h | Sprint 1 | RN.P.4 |
|10|	Como gestor de operações, quero acompanhar o tempo médio de operação por porto, para identificar gargalos e otimizar processos.	| Média	| 6h	| print 1	| RN.P.4 |
|11|	Como coordenador de logística, quero comparar desempenho mensal de cada porto, para ajustar alocação de recursos.	| Baixa	| 4h	| Sprint 1	| RN.P.2 |
|12|	Como diretor de logística, quero analisar tendências de carga ao longo do ano, para planejar investimentos estratégicos.	| Média	| 4h |	Sprint 1 | 	RN.P.2 |
|13|	Como diretor de operações, quero ter dashboards com visão geral de portos, cargas e operações, para monitorar performance do sistema.	| Alta | 4h	| Sprint 2 | RN.P.2 |
|14|	Como coordenador de planejamento, quero priorizar indicadores de eficiência, para orientar decisões gerenciais.	| Alta |	6h	| Sprint 2 |	RN.P.2 |
|15|	Como supervisor de operações, quero identificar operações com maior tempo de espera, para reduzir atrasos e custos. |	Média |	3h |	Sprint 2	| RN.P.2 |
|16|	Como responsável por relatórios técnicos, quero detalhar metodologia utilizada, para documentar processos e decisões. |	Média	| 3h |	Sprint 2	| RN.P.2 |
|17|	Como responsável por relatórios técnicos, quero registrar glossário de variáveis, para facilitar entendimento de dados.	| Alta |	10h |	Sprint 2 |	RN.P.1 |
|18|	Como responsável por relatórios técnicos, quero registrar análises exploratórias em relatório, para manter histórico completo. | Alta | 12h	| Sprint 2 |	RN.P.3 |
|19|	Como responsável por relatórios técnicos, quero preparar anexos com código e prints dos dashboards, para documentação detalhada.	| Média	| 6h |	Sprint 2 | RN.P.2 |
|20|	Como responsável por versionamento, quero criar repositório no GitHub, para controlar versões de scripts e datasets.	| Média	| 6h | Sprint 2 |	RN.P.2 |
|21|	Como responsável por versionamento, quero definir branches (main/dev), para organizar contribuições e desenvolvimento.	| Alta | 5h	| Sprint 2 |	RN.P.4 |
|22|	Como responsável por versionamento, quero atualizar repositório com scripts limpos e documentados, para manter histórico organizado.	| Média |	5h | Sprint 2 | RN.P.4 |
|23|	Como responsável por versionamento, quero criar issues no Jira para feedback do cliente, para rastrear pendências e melhorias.	| Média |	5h |	Sprint 2 |	RN.P.3 |
|24|	Como responsável por versionamento, quero revisar repositório e organizar releases finais, para entrega oficial. |	Baixa	| 5h |	Sprint 2 |	RN.P.2 |
|25|	Como responsável por versionamento, quero fechar issues e documentar histórico do Jira, para controle da equipe.	| Alta |	4h |	Sprint 3	| RN.P.2 |
|26| Como designer de apresentações, quero criar template no Canva/PowerPoint, para padronizar comunicações do grupo. |	Alta |	6h	| Sprint 3 | RN.P.2 |
|27| Como designer de apresentações, quero preparar slides de apresentação inicial, para a primeira reunião de acompanhamento.	| Média	| 3h	| Sprint 3	| RN.P.2 |
|28| Como designer de apresentações, quero montar slides com os primeiros gráficos, para facilitar entendimento do cliente.	| Média	| 4h	| Sprint 3	| RN.P.2 |
|29| Como designer de apresentações, quero criar storyboard para a feira, para planejar comunicação final.	| Alta	| 12h	| Sprint 3	| RN.P.3 |
|30| Como designer de apresentações, quero criar slides finais para a feira de soluções, para apresentação oficial.	| Alta	| 10h	| Sprint 3	| RN.P.5 |
|31| Como responsável por apresentações, quero ensaiar storytelling com o time, para garantir impacto na banca.	| Alta	| 10h	| Sprint 3	| RN.P.2 |
|32| Como responsável por apresentações, quero preparar roteiro de navegação em diferentes dispositivos, para demonstrar responsividade. | Média	| 8h | Sprint 3 |	RN.P.2 |
|33| Como analista de dados, quero calcular métricas-chave de desempenho, para auxiliar decisões estratégicas.	| Alta	| 6h	| Sprint 3 |	RN.P.4 |
|34| Como analista de dados, quero visualizar evolução de indicadores ao longo do tempo, para identificar tendências.	| Média	| 6h	| Sprint 3 | RN.P.4 |
|35| Como analista de dados, quero criar painéis comparativos entre portos e operações, para apoiar decisões gerenciais.	| Alta	| 8h	| Sprint 3 | RN.P.3 |
|36| Como gestor de operações, quero revisar entregas finais, para garantir que atendam aos requisitos do cliente. |	Alta	| 6h	| Sprint 3	| RN.P.2 |
|37| Como gestor de operações, quero coletar feedback em apresentação prévia, para ajustar detalhes antes da entrega final.	| Alta	| 6h	| Sprint 2 | RN.P.6 |
|38| Como responsável por relatórios técnicos, quero finalizar relatório acadêmico com resultados e conclusões, para entregar à banca.	| Média	| 4h | Sprint 2	| RN.P.6 |
|39| Como analista de dados, quero registrar insights estratégicos obtidos nos dashboards, para apoiar decisões futuras.	| Alta | 8h | Sprint 3 | RN.P.6 |
|40| Como coordenador de operações, quero acompanhar ensaios de apresentação, para garantir que o time esteja preparado.	| Média |	6h | Sprint 3 | RN.P.6 |
|41| Como coordenador de operações, quero planejar retrospectiva final, para avaliar aprendizado do time e melhorias do processo.	| Alta	| 4h | Sprint 3	| RN.P.6|


<br>

## Backlog da Sprint 📋

### Sprint 1 🎯 
- [ ] Acessar e baixar dados da ANTAQ via Colab para iniciar tratamento e análise
- [ ] Normalizar e limpar a base (remover duplicados e nulos) para manter consistência
- [ ] Calcular tempos médios de operação portuária para avaliar eficiência
- [ ] Construir o primeiro dashboard no Power BI para visão geral de portos, cargas e operações
- [ ] Implementar filtros avançados (período, tipo de carga) para análises personalizadas
- [ ] Criar painéis interativos com ranking de eficiência dos portos para identificar portos mais produtivos
- [ ] Testar dashboards em diferentes resoluções de tela para identificar ajustes de responsividade
- [ ] Ajustar layouts do Power BI para versão mobile para que usuários possam acessar via celular
- [ ] Validar dashboards em notebook, tablet e celular para garantir boa visualização para stakeholders
- [ ] Acompanhar tempo médio de operação por porto para identificar gargalos e otimizar processos
- [ ] Comparar desempenho mensal de cada porto para ajustar alocação de recursos

### Sprint 2 🎯
- [ ] Analisar tendências de carga ao longo do ano para planejar investimentos estratégicos
- [ ] Ter dashboards com visão geral de portos, cargas e operações para monitorar performance do sistema
- [ ] Priorizar indicadores de eficiência para orientar decisões gerenciais
- [ ] Identificar operações com maior tempo de espera para reduzir atrasos e custos
- [ ] Detalhar metodologia utilizada para documentar processos e decisões
- [ ] Registrar glossário de variáveis para facilitar entendimento de dados
- [ ] Registrar análises exploratórias em relatório para manter histórico completo
- [ ] Preparar anexos com código e prints dos dashboards para documentação detalhada
- [ ] Criar repositório no GitHub para controlar versões de scripts e datasets
- [ ] Definir branches (main/dev) para organizar contribuições e desenvolvimento
- [ ] Atualizar repositório com scripts limpos e documentados para manter histórico organizado
- [ ] Criar issues no Jira para feedback do cliente para rastrear pendências e melhorias
- [ ] Revisar repositório e organizar releases finais para entrega oficial

### Sprint 3 🎯
- [ ] Fechar issues e documentar histórico do Jira para controle da equipe
- [ ] Criar template no Canva/PowerPoint para padronizar comunicações do grupo
- [ ] Preparar slides de apresentação inicial para a primeira reunião de acompanhamento
- [ ] Montar slides com os primeiros gráficos para facilitar entendimento do cliente
- [ ] Criar storyboard para a feira para planejar comunicação final
- [ ] Criar slides finais para a feira de soluções para apresentação oficial
- [ ] Ensaiar storytelling com o time para garantir impacto na banca
- [ ] Preparar roteiro de navegação em diferentes dispositivos para demonstrar responsividade
- [ ] Calcular métricas-chave de desempenho para auxiliar decisões estratégicas
- [ ] Visualizar evolução de indicadores ao longo do tempo para identificar tendências
- [ ] Criar painéis comparativos com outros portos e operações para apoiar decisões gerenciais
- [ ] Revisar dashboards finais para garantir que atendam às necessidades dos clientes
- [ ] Coletar feedback em apresentação de dashboard para ajustar detalhes antes da entrega final
- [ ] Finalizar relatórios técnicos com análises e dashboards para entregar à banca
- [ ] Registrar insights estratégicos obtidos nos dashboards para apoiar decisões futuras
- [ ] Acompanhar ensaios de apresentação para garantir que o time esteja preparado
- [ ] Planejar retrospectiva final para aprendizado do time e melhorias do processo

<br>

## MVP 📊

<br>

## Equipe 👨‍💻
|    Função     | Nome |  LinkedIn & GitHub          |
| :-----------: | :------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Product Owner |  Lucas Melo    |     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)]() [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)]()     |
| Scrum Master  | Ana Caroline |      [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/ana-caroline-7570ba2a3?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/anacarolinae)     |
|  Team Member  | Rafaela Jonas |      [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)]() [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)]()  |
|  Team Member  | Tales |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)]() [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)]()   |
|  Team Member  | Mayla  |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)]() [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)]()      |
|  Team Member  | Bianca  |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)]() [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)]()      |

<br>
