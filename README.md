# **Nexus Logística**
<p align="center">
<img src="https://github.com/anacarolinae/Projeto-API-4-Semestre-Logistica/blob/main/Imagens/Logo%20Nexus%20Log%C3%ADstica.jpeg" width="400">
  
  
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
- **Power BI** para desenvolvimento do front-end (RN.P.3)  
- **GitHub** para controle de versão dos artefatos de projeto (RN.P.4)  

<br>

## Sprints 📅

|Sprint 🎯 | Previsão | Status| Histórico |
|----------|----------|-------|-----------|
|Kick Off | 12/09/2025 | Concluído ✅ | [MVP](https://github.com/anacarolinae/Projeto-API-4-Semestre-Logistica/blob/main/Documentos/Requisitos%20de%20Cliente%204LOG%20-%20CADI.pdf) |  
|1️⃣| 03/10/2025| Concluído ✅ | [MVP](https://github.com/anacarolinae/Projeto-API-4-Semestre-Logistica/blob/main/MVP/Sprint%201.md) |
|2️⃣| 24/10/2025 | Em andamento| [MVP](https://github.com/anacarolinae/Projeto-API-4-Semestre-Logistica/blob/main/MVP/Sprint%202.md) |
|3️⃣| 14/11/2025 | A fazer | [MVP](https://github.com/anacarolinae/Projeto-API-4-Semestre-Logistica/blob/main/MVP/Sprint%203.md) |
|:rocket: Feira de Soluções| 04/12/2025 | A fazer | [MVP]() |

<br>

## Backlog das Sprints 📋
| Rank | User Story | Prioridade | Estimativa | Sprint | Requisito |
|----|------------|------------|-------------|--------|-----------|
| 1  | Como **analista de mercado**, quero acessar e baixar dados da ANTAQ via Colab, para iniciar minhas próprias análises. | Alta | 4h | Sprint 1 | RN.P.2 |
| 2  | Como **gerente de planejamento**, quero que os dados estejam normalizados e limpos (sem duplicados e nulos), para garantir consistência nas análises. | Alta | 6h | Sprint 1 | RN.P.1 |
| 3  | Como **supervisor de operações**, quero visualizar tempos médios de operação portuária, para avaliar eficiência do dia a dia. | Alta | 4h | Sprint 1 | RN.P.2 |
| 4  | Como **diretor de operações**, quero um dashboard no Power BI com visão geral de portos, cargas e operações, para ter panorama completo. | Alta | 6h | Sprint 1 | RN.P.2 |
| 5  | Como **coordenador de logística**, quero aplicar filtros avançados (período, tipo de carga), para análises personalizadas. | Média | 4h | Sprint 1 | RN.P.2 |
| 6  | Como **coordenador de operações**, quero garantir que os dashboards funcionem em diferentes resoluções, para boa visualização em qualquer dispositivo. | Alta | 5h | Sprint 1 | RN.P.2 |
| 7  | Como **gerente de operações**, quero acompanhar o tempo médio de operação por porto, para identificar gargalos e otimizar processos. | Alta | 5h | Sprint 1 | RN.P.2 |
| 8  | Como **coordenador de logística**, quero compreender o desempenho mensal dos portos, para alocar adequadamente os recursos. | Alta | 5h | Sprint 1 | RN.P.2 |
| 9  | Como **diretor de logística**, quero analisar tendências de carga e destino ao longo dos anos, para planejar investimentos estratégicos. | Baixa | 6h | Sprint 1 | RN.P.2 |
| 10 | Como **diretor de operações**, quero dashboards consolidados de portos, cargas e operações, para monitorar performance do sistema. | Média | 4h | Sprint 1 | RN.P.2 |
| 11 | Como **coordenador de planejamento**, quero priorizar indicadores de eficiência, para orientar decisões gerenciais. | Alta | 6h | Sprint 1 | RN.P.2 |
| 12 | Como **supervisor de operações**, quero identificar operações com maior tempo de espera, para reduzir atrasos e custos. | Alta | 6h | Sprint 1 | RN.P.2 |
| 13 | Como gerente de planejamento, quero visualizar informações do setor agro para analisar e planejar melhor as operações. | Média | 10h | Sprint 2 | RN.P.4 |
| 14 | Como **gerente de planejamento**, quero acompanhar a evolução dos indicadores, para identificar tendências. | Média | 3h | Sprint 2 | RN.P.2 |
| 15 | Como gerente de planejamento, quero monitorar mudanças no clima para antecipar impactos nas operações. | Média | 5h | Sprint 2 | RN.P.3 |
| 16 | Como gerente de planejamento, quero saber qual terminal tem mais paradas por conta do clima para poder tomar decisões preventivas. | Média | 8h | Sprint 2 | RN.P.2 |
| 17 | Como gerente de planejamento, quero filtrar por porto com sugestões automáticas para encontrar rapidamente o porto desejado. | Média | 1h | Sprint 2 | RN.P.2 |
| 18 | Como **coordenador de logística**, quero comparar desempenho entre portos e operações, para embasar decisões de gestão. | Alta | 10h | Sprint 2 | RN.P.2 |
| 19 | Como **gerente de operações**, quero que os insights estratégicos extraídos dos dashboards estejam registrados, para apoiar decisões futuras. | Alta | 12h | Sprint 2 | RN.P.2 |
| 20 | Como **gerente regulatório**, quero ter relatórios com metodologia detalhada, para compreender processos e decisões. | Média | 6h | Sprint 2 | RN.P.2 |
| 21 | Como **coordenador técnico**, quero consultar glossário de variáveis, para facilitar interpretação dos dados. | Média | 4h | Sprint 2 | RN.P.2 |
| 22 | Como **diretor executivo**, quero relatório final com resultados e conclusões, para avaliar a solução apresentada. | Média | 4h | Sprint 2 | RN.P.2 |
| 23 | Como **engenheiro de software**, quero que os scripts finais estejam limpos e documentados, para facilitar reutilização. | Alta | 6h | Sprint 3 | RN.P.3 |
| 24 | Como **gerente de projetos**, quero que melhorias e pendências sejam rastreadas em Jira, para acompanhar evolução do projeto. | Alta | 6h | Sprint 3 | RN.P.3 |
| 25 | Como **gerente de TI**, quero que a entrega final seja organizada em releases documentadas, para facilitar validação. | Média | 6h | Sprint 3 | RN.P.2 |
| 26 | Como **coordenador de qualidade**, quero histórico das pendências fechadas no Jira, para acompanhar evolução. | Média | 6h | Sprint 3 | RN.P.3 |
| 27 | Como **diretor comercial**, quero apresentações padronizadas (template único), para comunicação consistente do proposta. | Alta | 4h | Sprint 3 | RN.P.3 |
| 28 | Como **gerente de contas**, quero visualizar slides iniciais claros, para compreender a solução desde o começo. | Alta | 6h | Sprint 3 | RN.P.3 |
| 29 | Como **gerente de operações**, quero ver gráficos ilustrativos nos slides, para facilitar entendimento dos dados. | Média | 6h | Sprint 3 | RN.P.2 |
| 30 | Como **diretor de marketing**, quero acompanhar storyboard das apresentações, para entender como será a comunicação final. | Alta | 6h | Sprint 3 | RN.P.4 |
| 31 | Como **diretor executivo**, quero assistir apresentação final estruturada, para julgar solução de forma clara. | Média | 6h | Sprint 3 | RN.P.2 |
| 32 | Como **diretor estratégico**, quero que a equipe apresente storytelling bem ensaiado, para transmitir impacto. | Alta | 8h | Sprint 3 | RN.P.2 |
| 33 | Como **diretor de operações**, quero revisar as entregas finais, para garantir que apenas materiais consistentes sejam recebidos. | Alta | 6h | Sprint 3 | RN.P.2 |
| 34 | Como **gerente de operações**, quero dar feedback em cada versão apresentada pela equipe, para ajustar detalhes antes da entrega final. | Média | 4h | Sprint 3 | RN.P.2 |
| 35 | Como **diretor executivo**, quero validar apresentação final antes da entrega oficial, para que a solução seja bem recebida. | Alta | 6h | Sprint 3 | RN.P.2 |
| 36 | Como **coordenador de operações**, quero planejar retrospectiva final, para avaliar aprendizado e melhorias do processo. | Média | 6h | Sprint 3 | RN.P.3 |
| 37  | Como **gerente de eficiência operacional**, quero ver painéis interativos com ranking dos portos, para identificar os mais produtivos. | Alta | 10h | Sprint 3 | RN.P.6 |

<br>

[![Acessar Jira](https://img.shields.io/badge/Acessar-Jira-blue?style=for-the-badge&logo=jira&logoColor=white)](https://biancatrevisan34.atlassian.net/jira/software/projects/SCRUM/boards/1/backlog)

<br>

## Equipe 👨‍💻
|    Função     | Nome |  LinkedIn & GitHub          |
| :-----------: | :------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Product Owner |  Lucas Melo    |     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-melo-4542701b0/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/LucasMeloLogistic)     |
| Scrum Master  | Ana Caroline |      [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/ana-caroline-7570ba2a3?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/anacarolinae)     |
|  Team Member  | Rafaela Jonas |      [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://br.linkedin.com/in/rafaela-jonas-a22a44341) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/RafaJonas)  |
|  Team Member  | Tales |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/talesferreiranogueira/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Talesfn1)   |
|  Team Member  | Mayla Costa |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/mayladepaula/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/mayladpaula)      |
|  Team Member  | Bianca  |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/biancastrevisan?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/TrevisanBS)      |

<br>
