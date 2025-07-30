Este projeto tem como objetivo analisar o comportamento da variável gorjeta (tip) e prever a renda (renda) de indivíduos, aplicando diferentes modelos de regressão linear e técnicas de transformação para melhorar a performance e a interpretação dos resultados.

Bases de Dados
tips: disponível via seaborn, contém dados sobre gorjetas, conta, dia, horário, etc.

previsao_de_renda.csv: conjunto fictício com dados demográficos e socioeconômicos.

Etapas do Projeto
1. Exploração e Criação de Variáveis
Criação de net_bill e tip_pct no dataset tips.

Criação de resíduos (res) e valores ajustados (fitted values) para análise gráfica.

2. Modelagem com Regressão Linear
Modelos com múltiplas variáveis explicativas (categóricas e contínuas)

Aplicação de transformações logarítmicas e polinomiais

Ajuste com statsmodels.OLS e fórmulas com patsy

3. Avaliação de Resíduos
Gráficos de resíduos vs. valores ajustados

QQ-Plot (normalidade dos resíduos)

Boxplots para análise de resíduos por grupos

4. Aplicação em outro conjunto (previsão de renda)
Modelos com tempo_emprego e renda, explorando diferentes transformações

Regressão múltipla com variáveis categóricas e contínuas

Ferramentas Utilizadas
pandas, numpy: manipulação de dados

statsmodels, patsy: regressão linear e avaliação estatística

matplotlib, seaborn: visualizações (resíduos, boxplots, QQ-plot)

