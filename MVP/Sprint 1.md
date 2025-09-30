#  MVP - Sprint 1 📌

## Objetivo do MVP 🎯

O MVP busca resolver a necessidade de acesso, limpeza e análise eficiente dos dados da ANTAQ, oferecendo uma visão clara sobre o desempenho dos portos e operações logísticas. A hipótese a ser validada é que, ao centralizar e analisar esses dados, será possível identificar portos mais produtivos, otimizar processos logísticos e apoiar decisões estratégicas baseadas em informações precisas. Como valor entregue ao usuário final, a solução disponibilizará dashboards interativos e customizáveis, com filtros avançados e métricas de desempenho, possibilitando decisões mais rápidas, fundamentadas e ajustes operacionais em tempo real.

## Descrição da Solução 📝 

Será desenvolvido um MVP de análise de dados que permite o acesso à base de dados da ANTAQ, com funcionalidades para normalizar e limpar os dados, calcular métricas de desempenho portuário e criar dashboards interativos no Power BI. O objetivo é validar a eficiência dos dashboards e ferramentas analíticas para usuários finais como analistas de dados, coordenadores de operações e gestores de logística.

### Funcionalidades principais incluídas
- Acesso e download de dados da ANTAQ via Colab.
- Normalização e limpeza de dados (remoção de duplicados e nulos).
- Cálculo de tempos médios de operação portuária.
- Criação de dashboards no Power BI com métricas de desempenho.
- Filtros avançados para personalização das análises.
- Painéis interativos com ranking de eficiência dos portos.
- Ajuste de layouts para versão mobile e diferentes resoluções de tela.

### Limitações conhecidas
- A quantidade de dados pode afetar a performance do sistema se não for bem otimizada.
- O acesso aos dados da ANTAQ pode ser limitado por questões de atualização e disponibilidade.
- A personalização do dashboard para diferentes dispositivos pode exigir ajustes adicionais após feedback.

### Escopo reduzido
O escopo inicial inclui a implementação da integração com a ANTAQ, normalização dos dados, cálculo das métricas principais e a criação de dashboards básicos com filtros essenciais.

## Personas / Usuários-Alvo 👥

### Persona 1: Analista de Dados
- **Necessidades**: Acessar e limpar dados de forma rápida, construir dashboards informativos para análise de performance portuária.
- **Dores atendidas**: Falta de automação no tratamento de dados, dificuldade em acessar dados em tempo real.

### Persona 2: Coordenador de Operações
- **Necessidades**: Acompanhar a eficiência dos portos e identificar gargalos operacionais.
- **Dores atendidas**: Dificuldade em comparar o desempenho dos portos, ineficiência na alocação de recursos.


## User Stories (Backlog do MVP) 🔑 

| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| US1 | Como analista de dados, quero acessar e baixar dados da ANTAQ via Colab, para iniciar o tratamento e análise. | Alta       | 5 pontos   |
| US2 | Como analista de dados, quero normalizar e limpar a base (remover duplicados e nulos), para manter consistência. | Alta       | 5 pontos   |
| US3 | Como analista de dados, quero calcular tempos médios de operação portuária, para avaliar eficiência. | Alta       | 5 pontos   |
| US4 | Como analista de dados, quero construir o primeiro dashboard no Power BI, para ter visão geral de portos, cargas e operações. | Alta       | 5 pontos   |
| US5 | Como analista de dados, quero implementar filtros avançados (período, tipo de carga), para análises personalizadas. | Média      | 3 pontos   |
| US6 | Como analista de dados, quero criar painéis interativos com ranking de eficiência dos portos, para identificar portos mais produtivos. | Alta       | 5 pontos   |
| US7 | Como analista de dados, quero testar dashboards em diferentes resoluções de tela, para identificar ajustes de responsividade. | Média      | 3 pontos   |
| US8 | Como analista de dados, quero ajustar layouts do Power BI para versão mobile, para que usuários possam acessar via celular. | Média      | 3 pontos   |
| US9 | Como coordenador de operações, quero validar dashboards em notebook, tablet e celular, para garantir boa visualização para todos os stakeholders. | Alta       | 5 pontos   |
| US10 | Como gestor de operações, quero acompanhar o tempo médio de operação por porto, para identificar gargalos e otimizar processos. | Alta       | 5 pontos   |
| US11 | Como coordenador de logística, quero comparar desempenho mensal de cada porto, para ajustar alocação de recursos. | Alta       | 5 pontos   |
| US12 | Como diretor de logística, quero analisar tendências de carga ao longo do ano, para planejar investimentos estratégicos. | Alta       | 5 pontos   |


## Sprints Relacionadas 📅

| Sprint | Entregas Principais                                               | Status      |
|--------|--------------------------------------------------------------------|-------------|
| 01     | Integração com a ANTAQ, normalização e limpeza de dados, cálculo de tempos médios de operação | Concluído   |
| 02     | Criação de dashboards no Power BI, filtros avançados, ajustes para dispositivos móveis | Em andamento |
| 03     | Validação de dashboards em diferentes dispositivos, análise de eficiência dos portos | Em andamento |


## Critérios de Aceitação  📊 

O MVP deve permitir que o usuário acesse e baixe dados atualizados da ANTAQ, realize a normalização e limpeza da base de dados com eficiência e obtenha insights sobre a eficiência portuária por meio de dashboards interativos e filtros avançados. Além disso, o sistema registrará o tempo médio de operação por porto, a quantidade de dados processados e eventuais falhas, enquanto as métricas coletadas incluirão o tempo de resposta nas consultas, a taxa de uso dos dashboards e o feedback qualitativo dos usuários finais, como analistas, coordenadores e gestores.


## Métricas de Validação  📈

## 📂 Anexos / Evidências

- Prints de tela
<img src="" width="400">

- Vídeo (MVP)
<video src="https://www.youtube.com/watch?v=giK-YLXdSvg" controls width="600"></video>
