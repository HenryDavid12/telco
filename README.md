
# Telco Customer Churn | Reduzindo cancelamentos com dados

*Visão Geral*:

Este projeto analisa o comportamento dos clientes de uma empresa de telecomunicações para entender os fatores que levam ao cancelamento dos serviços (churn). Através de análises exploratórias, modelagem preditiva e segmentação via clusterização, foram gerados insights que possibilitam reduzir a evasão de clientes e aumentar a fidelização.

Objetivo de Negócio:

Como prever e reduzir o cancelamento de clientes (churn) em uma empresa de telecomunicações, utilizando dados históricos para identificar perfis de risco e apoiar ações de retenção?

Principais Insights:

 Churn geral: Aproximadamente 26% dos clientes cancelaram o serviço.

 Clientes com tenure abaixo de 12 meses estão mais propensos ao churn.

 Contrato mensal é o mais comum entre clientes que cancelam.

Pagamentos com boleto estão fortemente associados ao churn.

 Ausência de serviços adicionais (segurança online, suporte técnico) aumenta o risco de cancelamento.

 Modelo preditivo com Random Forest obteve:

Acurácia: 75%

Recall da classe churn: 75%

Precisão da classe churn: 52%

 Clusterização com KMeans + PCA identificou grupos com diferentes perfis de risco:

Cluster 0: Baixo risco, clientes com contrato longo e serviços adicionais

Cluster 1: Alto risco, contrato mensal e poucos serviços

Cluster 2: Intermediário, pagamento automático e tempo médio de vínculo

 Metodologia:
 Etapas:
Pré-processamento dos dados

Conversão de variáveis categóricas, imputação e padronização

Análise Exploratória (EDA)

Visualizações com Plotly, Seaborn e Matplotlib

Análise do perfil dos clientes churn vs não churn

Modelagem Preditiva

Random Forest e XGBoost

Otimização de threshold para aumentar o recall

Clusterização com KMeans + PCA

Redução de dimensionalidade para visualização e interpretação dos grupos

Criação de Dashboard em Power BI

KPIs de cancelamento, perfil de clientes e segmentações interativas

 Tecnologias Utilizadas
Python 3.11

pandas, numpy, plotly, seaborn, matplotlib

scikit-learn, xgboost

Power BI

Dashboard com filtros dinâmicos, mapas e painéis comparativos

Jupyter Notebook

Git & GitHub

 Resultados Esperados

Antecipação de cancelamentos com base em perfil e comportamento

Redução de churn através de campanhas direcionadas

Segmentação inteligente de clientes com base em clusters de risco

Suporte à tomada de decisão com visualizações estratégicas no Power BI

 Dashboard (Power BI)


https://shre.ink/xlTX

KPIs principais: Churn Total, Perfil de Clientes em Risco, Tempo de Fidelização, Contratos por Tipo e Cluster Performance

 Sobre o Autor

Henry David |
Analista de Dados | Python • Power BI • SQL • Excel

📫 henryalvdavid@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/henryalvdavid

Medium: https://medium.com/@henryprojetos12

📂 Estrutura do Projeto


telco-churn-project/

├── data/    WA_Fn-UseC_-Telco-Customer-Churn              

├── notebooks/ telco_churn         

├── dashboards/        https://shre.ink/xlTX

└── requirements.txt:        Plotly graph objects, plotly express, pandas, numpy, scikit-learn, matplotlib, seaborn.

