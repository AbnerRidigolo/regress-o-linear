# Regressão Linear com Python

Este projeto demonstra a aplicação de **regressão linear múltipla** para prever preços de imóveis com base em variáveis como renda média, idade média das casas, número de cômodos e população da área.

> Projeto desenvolvido como exercício prático para aprofundar conceitos de **análise de dados**, **machine learning supervisionado** e **avaliação de modelos**.

---

## Objetivos

- Explorar e visualizar dados de imóveis residenciais nos EUA  
- Preparar os dados para modelagem preditiva  
- Treinar um modelo de regressão linear com `scikit-learn`  
- Avaliar a performance do modelo e interpretar seus coeficientes  
- Visualizar resíduos e aplicar métricas de erro (MAE, MSE, RMSE)

---

##  Bibliotecas utilizadas

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split
from sklearn import metrics
```

---

##  Etapas principais

1. **Importação e análise exploratória dos dados**  
2. **Criação dos arrays X (features) e y (target)**  
3. **Divisão entre treino e teste (train_test_split)**  
4. **Treinamento do modelo com `LinearRegression()`**  
5. **Avaliação do modelo (coeficientes, erro médio, gráfico de resíduos)**  
6. **Visualização dos resultados e interpretação dos erros**

---

##  Avaliação do Modelo

Foram utilizadas três métricas principais:

- **MAE** (Erro Médio Absoluto)  
- **MSE** (Erro Quadrático Médio)  
- **RMSE** (Raiz do Erro Quadrático Médio)  

Além disso, foi gerado um histograma de resíduos, confirmando que a maior parte dos erros está concentrada próxima de zero — um bom indicativo de ajuste.

---

##  Conclusão

Apesar de o conjunto de dados ser fictício, o projeto permite entender com clareza os princípios da **regressão linear múltipla**, suas aplicações e como avaliar sua performance. O modelo conseguiu prever os preços com boa precisão, e as análises mostraram como cada variável influencia diretamente no resultado final.
