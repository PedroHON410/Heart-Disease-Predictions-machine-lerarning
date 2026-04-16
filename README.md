
# 🫀 Heart Disease Classification
Este projeto consiste em um pipeline de Machine Learning voltado para a classificação de pacientes, determinando se eles possuem ou não doenças cardíacas com base em parâmetros clínicos.

O objetivo principal é alcançar uma precisão de 95% na identificação de casos positivos para viabilizar o uso do modelo em diagnósticos preventivos.

## 📊 Sobre o Dataset
O conjunto de dados utilizado contém 303 amostras com 14 atributos clínicos, incluindo:

* age: Idade do paciente.

* sex: Sexo (1 = masc; 0 = fem).

* cp: Tipo de dor no peito (4 níveis).

* trestbps: Pressão arterial em repouso.

* chol: Colesterol sérico.

* thalach: Frequência cardíaca máxima atingida.

* target: Presença de doença (1 = doente, 0 = saudável).

## 🛠️ Tecnologias Utilizadas
``` Linguagem: Python

Bibliotecas de Manipulação e Visualização: Pandas, NumPy, Matplotlib, Seaborn.

Machine Learning: Scikit-learn.
```
## Modelos Implementados:

* Logistic Regression

* K-Nearest Neighbors (KNN)

* Random Forest Classifier 


## 📈 Etapas do Projeto
* Análise Exploratória de Dados (EDA): Visualização da distribuição das classes, correlações entre variáveis e frequência de doenças por sexo e idade.

* Pré-processamento: Limpeza e normalização dos dados.

* Treinamento de Modelos: Comparação entre diferentes algoritmos de classificação.

* Otimização de Hiperparâmetros: Uso de RandomizedSearchCV e GridSearchCV para extrair a melhor performance dos modelos.

* Avaliação: Uso de métricas como Matriz de Confusão, Relatório de Classificação (Precision, Recall, F1-score) e Curva ROC.

## 🚀 Como Executar
Clone o repositório.

Certifique-se de ter o arquivo heart.csv no mesmo diretório.

Instale as dependências:
```
Bash
pip install pandas numpy matplotlib seaborn scikit-learn
Abra o Jupyter Notebook ou Google Colab e execute as células do arquivo MLheart.ipynb.
```
# 📌 Resultados
O projeto detalha a comparação entre os modelos, destacando o impacto do ajuste de hiperparâmetros na acurácia final. Os relatórios de classificação permitem entender o equilíbrio entre precisão e sensibilidade para o diagnóstico médico
