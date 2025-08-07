# Credit Risk Fairness
Este repositório contém os códigos utilizados para os experimentos do estudo sobre **justiça algorítmica em modelos de previsão de inadimplência**, com foco na análise do impacto de técnicas de oversampling sobre métricas de desempenho e equidade.

## Estrutura do Projeto

- `preprocessing.ipynb`: notebook com o tratamento e preparação dos dados, incluindo definição de variáveis sensíveis e criação dos cenários experimentais.
- `modeling.ipynb`: notebook responsável pela modelagem, aplicação das estratégias de oversampling, avaliação de desempenho e cálculo das métricas de justiça.

## Tecnologias Utilizadas

- Python 3
- Pandas, NumPy
- Scikit-learn, xgboost
- Fairlearn
- Matplotlib

## Objetivo do Estudo

O estudo investiga como diferentes algoritmos de oversampling (como SMOTE, RandomOverSampler, entre outros) impactam:

- O desempenho dos modelos (acurácia, recall, precisão, F1-score)
- A justiça algorítmica (paridade demográfica, igualdade de oportunidades, etc.)

Foram analisados modelos lineares e não lineares, incluindo **Logistic Regression, SVM (RBF)** e **XGBoost**.

---
