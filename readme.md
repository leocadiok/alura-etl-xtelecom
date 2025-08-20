# Análise de Evasão de Clientes (Churn) - X-Telecom

-----

### 📝 Sobre o Projeto

Este repositório contém um projeto completo de análise de dados e modelagem preditiva para a X-Telecom, com o objetivo de identificar os fatores que levam à **evasão de clientes (Churn)**. A análise explora o comportamento dos clientes, constrói modelos de Machine Learning para prever a evasão e identifica as variáveis mais relevantes para o negócio.

O conjunto de dados, fornecido pela empresa fictícia X-Telecom, inclui informações demográficas, detalhes do plano de serviço e o status de evasão de cada cliente.

-----

### 📈 Análises e Metodologia

O projeto segue um pipeline de Data Science, abrangendo as seguintes etapas:

  * **Análise Exploratória de Dados (EDA):** Investigação inicial dos dados para entender a estrutura, identificar valores nulos e visualizar a distribuição das variáveis.
  * **Pré-processamento de Dados:** Tratamento de valores ausentes, limpeza da base e transformação de variáveis categóricas em numéricas, usando codificação binária e One-Hot Encoding.
  * **Análise de Correlação e Visualização:** Avaliação da relação entre as variáveis, com foco especial na variável alvo (`Churn`), utilizando matrizes de correlação e gráficos como boxplots e scatter plots.
  * **Modelagem Preditiva:** Construção de dois modelos de classificação, um sensível à escala (`Regressão Logística`) e outro não sensível (`Árvore de Decisão`), para prever a probabilidade de evasão.
  * **Avaliação do Modelo:** Utilização de métricas robustas (Acurácia, Precisão, Recall, F1-Score e Matriz de Confusão) para comparar o desempenho dos modelos em um cenário de desequilíbrio de classes.
  * **Análise de Variáveis Relevantes:** Identificação das variáveis mais importantes para a previsão de evasão, usando os coeficientes do modelo de Regressão Logística e a importância das variáveis da Árvore de Decisão.

-----

### 🎯 Principais Conclusões

A análise e os modelos revelaram insights cruciais sobre o churn de clientes da X-Telecom:

  * A **taxa de evasão é de aproximadamente 26.5%**, um valor considerável que merece atenção.
  * O **tempo de permanência (`tenure`)** é a variável mais influente para a evasão. Clientes que estão na empresa há mais tempo são significativamente menos propensos a sair.
  * Os **planos de contrato `Month-to-month`** apresentam uma taxa de evasão muito maior do que os contratos de longo prazo (um ou dois anos).
  * Os **valores de cobrança mensal mais altos** estão correlacionados com a evasão.
  * A **Regressão Logística** e a **Árvore de Decisão** foram capazes de prever a evasão com desempenho satisfatório, servindo como uma base sólida para modelos futuros.

-----

### 🛠️ Tecnologias Utilizadas

  * **Python**
  * **Pandas:** Manipulação e análise de dados.
  * **Numpy:** Suporte para operações numéricas.
  * **Scikit-learn:** Pré-processamento, modelagem e avaliação de machine learning.
  * **Matplotlib & Seaborn:** Visualização de dados.

-----

### 🚀 Como Executar o Projeto

Para replicar a análise, siga os passos abaixo:

1.  Clone este repositório:
    ```bash
    git clone https://github.com/leocadiok/alura-etl-xtelecom.git
    ```
2.  Instale as bibliotecas necessárias:
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn
    ```
3.  Abra o notebook `analise_churn.ipynb` (nome a ser confirmado) e execute as células sequencialmente para reproduzir a análise.

-----

### 🧑 Autor

  * @leocadiok