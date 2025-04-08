# Previsão de Preços de Ações com RNN (LSTM)

![Python](https://img.shields.io/badge/Python-Linguagem-3776AB?style=flat-square&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Manipulação%20de%20Dados-150458?style=flat-square&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Computação%20Numérica-013243?style=flat-square&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualização%20de%20Dados-11557C?style=flat-square&logo=matplotlib)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Pré%20Processamento-F7931E?style=flat-square&logo=scikit-learn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter)

---

## Descrição

O objetivo principal é construir um modelo que consiga antecipar movimentos de preços utilizando sequências temporais de dados passados. A previsão é feita aplicando uma rede neural LSTM treinada em dados normalizados.

O pipeline do projeto inclui:
- Preparação e divisão dos dados em treino e teste.
- Normalização dos preços usando MinMaxScaler.
- Estruturação dos dados para sequências temporais.
- Treinamento de uma rede LSTM profunda.
- Geração de previsões futuras.
- Visualização dos resultados em gráficos.

O modelo foi desenvolvido em um Jupyter Notebook, permitindo visualizações intermediárias e reprodutibilidade fácil.

---

##  Funcionalidades

-  Importação e pré-processamento de dados históricos de ações.
-  Normalização dos dados financeiros.
-  Transformação de dados em janelas de tempo (Time Series).
-  Construção de uma Rede Neural Recorrente com camadas LSTM e Dropout.
-  Treinamento do modelo com ajustes de batch_size e epochs.
-  Previsão de preços futuros baseados em dados históricos.
-  Visualização gráfica da comparação entre preços reais e previstos.
-  Salvamento da arquitetura da rede em formato de imagem (.png).

---

##  Tecnologias Abordadas

- **Python 3.11**
- **Pandas** — Manipulação de dados tabulares.
- **NumPy** — Operações matemáticas e manipulação de arrays.
- **Matplotlib** — Criação de gráficos de comparação.
- **Scikit-Learn** — Pré-processamento de dados (MinMaxScaler).
- **TensorFlow** — Desenvolvimento e treinamento de modelos de deep learning.
- **Keras** — API de alto nível para construção das redes neurais.
- **Jupyter Notebook** — Ambiente interativo para experimentação.


