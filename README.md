# 🌲 Classificação de Cobertura Florestal - Covertype com Naive Bayes e KNN

Este projeto tem como objetivo aplicar os algoritmos de **Naive Bayes** e **KNN (K-Nearest Neighbors)** à base de dados **Covertype**, com foco em resolver um problema de **classificação supervisionada** de tipos de cobertura florestal. O trabalho faz parte da disciplina de Aprendizado de Máquina da graduação em Tecnologia da Informação.

---

## 🎯 Objetivos

- Aplicar dois algoritmos de **aprendizado supervisionado**: Naive Bayes e KNN.
- Comparar os resultados obtidos por ambos os modelos.
- Avaliar o desempenho utilizando métricas adequadas.
- Realizar **pré-processamento**, **divisão dos dados**, **treinamento**, **teste** e **avaliação** dos modelos.
- Entender a eficácia de cada modelo na classificação de tipos de solo com base em variáveis ambientais.

---

## 📚 Base de Dados

- **Nome**: Covertype
- **Fonte**: `sklearn.datasets.fetch_covtype`
- **Descrição**: A base contém atributos cartográficos e ambientais (como elevação, inclinação, distância à água, tipo de solo etc.) com o objetivo de prever a cobertura florestal entre 7 diferentes tipos.

---

## 🛠️ Tecnologias e Bibliotecas

- Python 3.12
- Jupyter Notebook
- Scikit-learn (`sklearn`)
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## ⚙️ Etapas do Projeto

1. **Importação dos Dados**
   - Uso da função `fetch_covtype` do Scikit-learn.

2. **Pré-processamento**
   - Separação de variáveis preditoras (X) e alvo (y).
   - Divisão dos dados em treino (80%) e teste (20%).
   - Aplicação opcional de técnicas de redução de dimensionalidade (ex: PCA).

3. **Treinamento**
   - Algoritmo 1: Naive Bayes (`GaussianNB`)
   - Algoritmo 2: KNN (`KNeighborsClassifier`)

4. **Avaliação**
   - Acurácia
   - Precisão, Recall e F1-Score
   - Matriz de Confusão
   - Relatório de Classificação

5. **Comparação dos Resultados**
   - Análise crítica sobre qual modelo apresentou melhor desempenho com base nos dados e métricas obtidas.

---

## 📊 Resultados Esperados

- Métricas individuais para cada modelo.
- Visualização da matriz de confusão.
- Discussão sobre as limitações e vantagens de cada algoritmo aplicado.

---

## 📌 Observações

- O projeto foi desenvolvido como parte das atividades práticas da disciplina.
- O código está disponibilizado em formato de **notebook `.ipynb`**.
- A apresentação do trabalho será feita em forma de **arguição** com base nos resultados e análises do notebook.

---

## 📝 Licença

Este projeto é acadêmico e de uso educacional.
