#  MVP - Sprint 1📌

## Objetivo do MVP 🎯

### Qual problema resolve?
O MVP resolve a necessidade de acesso, limpeza e análise eficiente dos dados da ANTAQ, proporcionando uma visão clara sobre o desempenho dos portos e operações logísticas. Ele permite que analistas e gestores obtenham insights para melhorar a eficiência dos processos e otimizar a alocação de recursos.

### Qual hipótese será validada?
A hipótese a ser validada é que, ao centralizar e analisar os dados de operações portuárias e cargas, será possível identificar portos mais produtivos, otimizar processos logísticos e tomar decisões estratégicas baseadas em dados precisos.

### Qual valor será entregue ao usuário final?
O MVP proporcionará aos analistas de dados e gestores acesso a dashboards interativos e customizáveis, com filtros avançados e métricas de desempenho dos portos, permitindo uma tomada de decisão mais rápida e fundamentada, além de possibilitar ajustes operacionais em tempo real.


## Descrição da Solução 📝 

### Breve explicação do que será desenvolvido e entregue nesta etapa.
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

### Escopo reduzido (somente o essencial para validar a ideia)
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

- **O MVP deve permitir que o usuário**:
  - Acesse e baixe dados atualizados da ANTAQ para análise.
  - Realize a normalização e limpeza da base de dados com eficiência.
  - Obtenha insights sobre a eficiência portuária por meio de dashboards interativos e filtros avançados.

- **O sistema deve registrar**:
  - O tempo médio de operação por porto.
  - A quantidade de dados processados e eventuais falhas no processo.

- **Métricas coletadas**:
  - Tempo de resposta nas consultas de dados.
  - Taxa de uso dos dashboards.
  - Feedback qualitativo dos usuários finais (analistas, coordenadores e gestores).


## Métricas de Validação  📈

- Número de usuários que testaram o MVP.
- Feedback qualitativo (positivo/negativo) sobre a usabilidade dos dashboards e a precisão dos dados.
- Indicadores de negócio: 
  - % de adesão ao uso das ferramentas de análise.
  - Redução de tempo gasto para coleta e análise de dados.
  - Eficiência operacional medida pela redução de gargalos identificados nas operações portuárias.


## Próximos Passos 🚀 

- **Melhorias planejadas após feedback**:
  - Refinar os filtros de análise com base no feedback dos usuários.
  - Melhorar a performance do sistema de integração com a ANTAQ.

- **Ajustes de usabilidade**:
  - Melhorar a responsividade dos dashboards para diferentes dispositivos e resoluções.
  - Ajustar os layouts de Power BI para versão mobile com base nos testes.

- **Expansão de funcionalidades para próximo incremento**:
  - Adicionar mais métricas e KPIs nos dashboards.
  - Implementar alertas automáticos de desempenho para portos específicos.
