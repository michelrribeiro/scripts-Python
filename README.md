
### Descrição dos documentos deste repositório:

Aqui se encontram os scripts escritos com linguagem python para resolver
problemas de negócio com uso de machine learning e outras bibliotecas
que possam ser necessárias.

Os arquivos foram enumerados conforme a data de criação, pois assim a
evolução no conhecimento também pode ser sentida. Novos scripts serão
inclusos conforme novos projetos forem feitos.

**1-dsa-customer-churn-operadoras-telecom.ipynb:**  
Origem: projeto proposto pelo curso “Big Data Real-Time Analytics com
Python e Spark” da Data Science Academy.

Fonte dos dados: disponibilizados juntamente com a proposta de projeto.

Objetivo: criar um modelo de aprendizado de máquina que possa prever a
probabilidade de um cliente cancelar seu plano atual.

Tarefas com pacotes e funções utilizadas:  
+ Análise exploratória: pandas, numpy, scipy.stats, re, seaborn.  
+ Balanceamento de classes: imblearn.oversampling.ADASYN.  
+ Criação do modelo: sklearn.linear_model_LogisticRegression,
sklearn.model_selection.GridSearchCV.  
+ Avaliação do modelo: sklearn.metrics_confusion_matrix,
sklearn.metrics.accuracy_score.

**2-dio-modelo-previsao-evolucao-covid.ipynb:**  
Origem: projeto proposto pelo bootcamp “Geração Tech Unimed-BH - Ciência
de Dados” da Digital Innovation One. Projeto com acompanhamento dos
vídeos.

Fonte dos dados: disponibilizados juntamente com a proposta de projeto.
Dados de janeiro a maio de 2020.

Objetivo: avaliar a série temporal do crescimento de casos de covid-19 e
as mortes causadas pela doença. Além disso, criar um modelo para
projeção da curva de crescimento no Brasil.

Tarefas com pacotes e funções utilizadas:  
+ Análise exploratória: pandas, numpy, scipy.stats, re, plotly.express,
plotly.graph_objects.  
+ Decomposição da série: statsmodels.tsa.seasonal.seasonal_decompose.  
+ Criação do modelo: pmdarima.arima.auto_arima, prophet.Prophet.

**3-dsa-satisfacao-clientes-santander.ipynb:**  
Origem: projeto proposto pelo curso “Big Data Real-Time Analytics com
Python e Spark” da Data Science Academy.

Fonte dos dados: disponibilizados juntamente com a proposta de projeto.
Objetivo: criar um modelo de aprendizagem de máquina que possa prever a
probabilidade de um cliente cancelar seu plano atual.

Tarefas com pacotes e funções utilizadas:  
+ Análise exploratória: pandas, numpy, scipy.stats, re, seaborn,
matplotlib.ticker.PercentFormatter.  
+ Pré-processamento: sklearn.preprocessing.StandardScaler,
sklearn.decomposition.PCA, sklearn.feature_selection.SelectFromModel.  
+ Balanceamento de classes: imblearn.oversampling.ADASYN.  
+ Criação do modelo: sklearn.linear_model_LogisticRegression,
sklearn.ensemble.RandomForestClassifier,
sklearn.model_selection.GridSearchCV.  
+ Avaliação do modelo: sklearn.metrics_confusion_matrix,
sklearn.metrics.accuracy_score.
