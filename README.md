## Análise da Taxa SELIC e IPCA
📌 **Introdução**

Este repositório apresenta um estudo detalhado sobre a Taxa SELIC e o IPCA (Índice Nacional de Preços ao Consumidor Amplo), indicadores econômicos essenciais no Brasil. A análise abrange o período de 2000 a 2024 e explora como esses indicadores se comportam e interagem em diferentes cenários econômicos.

🎯 **Objetivos**
Limpar e preparar os dados brutos para análises comparativas.
Identificar eventos macroeconômicos que impactaram a SELIC e o IPCA.
Apresentar visualizações gráficas que ilustram os comportamentos individuais e a interação entre os indicadores.

📂 **Dados Utilizados**
Os dados foram obtidos do Sistema Gerenciador de Séries Temporais (SGS) do Banco Central do Brasil:

SELIC (código 11): Taxa de juros básica da economia, com periodicidade diária.
IPCA (código 433): Índice que mede a inflação oficial, com periodicidade mensal.

**🛠️ Metodologia**

1️⃣ Limpeza e Preparação
Carregamento dos Dados: Arquivos CSV foram importados e convertidos em DataFrames.

Conversões Realizadas:
Separadores decimais ajustados (vírgulas para pontos).
Datas padronizadas: dd/MM/yyyy (SELIC) e MM/yyyy (IPCA).
Exclusão de Inconsistências: Linhas inválidas foram removidas.


2️⃣ Visualizações

Gráfico 1: SELIC (Taxa Diária)
Representa a variação da SELIC ao longo do período analisado.

Gráfico 2: IPCA (Variação Mensal)
Demonstra a oscilação mensal do IPCA, destacando eventos econômicos críticos.

Gráfico 3: Sobreposição SELIC e IPCA
Mostra a interação entre os dois indicadores econômicos ao longo do tempo.


📊 **Análise de Resultados**
SELIC: Exibe movimentos graduais, refletindo decisões de longo prazo do Banco Central.
IPCA: Apresenta flutuações rápidas, influenciado por choques externos e fatores sazonais.
Interação: A SELIC é utilizada para controlar o IPCA, destacando o papel da política monetária no equilíbrio da economia.

📖 **Conclusão**
Este projeto evidenciou a relação dinâmica entre a Taxa SELIC e o IPCA, demonstrando como esses indicadores se influenciam mutuamente e refletem condições macroeconômicas. Compreender essa interação é essencial para interpretar o cenário econômico e prever mudanças nos ciclos financeiros.

🔗 **Referências**
Banco Central do Brasil - SGS.
