# Regressão linear


Utilizando bibliotecas externas pude plotar os graficos para analize da dispersão e regressão a qual podemos ver o consumo de bebidas visto as condições analisadas e comparadas.

```python

# funções graficas
    sns.pairplot()
    sns.jointplot()
    sns.lmplot()
    sns.scatterplot()
```

## Machine leaerning

Utilizamos o sklearning para processar 30% dos dados para teste e 70% para treino podendo analizar como foi o resultado.
```python
from sklearn.model_selection import train_test_split
```