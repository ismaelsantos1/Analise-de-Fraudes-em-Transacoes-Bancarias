
## 🔍 **Project Purpose**  
The main goal of this project is to identify suspicious transactions that could be fraudulent using **Machine Learning**, specifically unsupervised learning algorithms.  

## ⚙️ **Methodology**  
The project follows a structured flow of analysis and modeling:  

1️⃣ **Exploratory Data Analysis (EDA)**  
   - Understanding the dataset (statistics, missing values, duplicates).  
   - Visualization of distributions and transaction patterns.  

2️⃣ **Data Preprocessing**  
   - Handling missing values and normalizing data.  
   - Converting categorical variables into a numerical format.  
   - Splitting the data into training and test sets.  

3️⃣ **Machine Learning Algorithms Applied**  
   - **K-Means Clustering**: Groups transactions based on similar characteristics.  
   - **DBSCAN**: A density-based clustering algorithm useful for identifying outliers.  
   - **Hierarchical Clustering**: Segments transactions into categories.  
   - **Isolation Forest**: A specialized anomaly detection algorithm that classifies transactions as normal or fraudulent.  

## 🎯 **Expected Results**  
- **Efficient fraud pattern identification** without requiring a labeled dataset.  
- **Reduction of financial losses** by detecting fraud before it causes significant impact.  
- **Improvement in banking security**, enabling financial institutions to use these models to enhance their fraud prevention systems.  

## 🏆 **Conclusion**  
This project demonstrates how **Machine Learning techniques** can be applied to **automatically detect fraudulent transactions**, helping financial institutions **make quick and effective decisions** in identifying suspicious activities. 🚀  
"""
<!--## 1. Entendimento do Conjunto de Dados
A primeira etapa do notebook envolve a exploração inicial dos dados:

- **Importação das bibliotecas**: O código importa `pandas`, `matplotlib.pyplot`, `numpy` e `seaborn`, essenciais para análise de dados e visualização.
- **Carregamento dos dados**: O conjunto de dados é carregado a partir de um arquivo CSV (`bank_transactions_data_2.csv`).
- **Visualização inicial**: O método `head()` exibe as primeiras linhas para uma visão geral.
- **Informações sobre o dataset**: `info()` mostra os tipos de dados e valores nulos.
- **Estatísticas descritivas**: `describe().round(2)` fornece informações como média e desvio padrão.
- **Verificação de valores nulos e duplicados**: 
  - `isnull().sum()` para identificar valores ausentes.
  - `duplicated().sum()` para encontrar registros duplicados.
- **Análise da coluna 'Location'**: `value_counts()` examina a distribuição das transações por localização.

## 2. Análise Exploratória de Dados (EDA)
Nesta fase, o notebook analisa os dados por meio de visualizações e estatísticas:

- **Uso da biblioteca `summarytools`** para análises detalhadas.
- **Criação de visualizações**:
  - Distribuição das transações por localização.
  - Gráficos de dispersão para identificar padrões.
  - Histogramas para analisar a distribuição dos valores das transações.

## 3. Pré-processamento dos Dados
Antes de aplicar Machine Learning, os dados são preparados:

- **Tratamento de valores nulos**.
- **Codificação de variáveis categóricas**.
- **Normalização ou padronização dos dados**.
- **Divisão em conjuntos de treinamento e teste** (`train_test_split()`).

## 4. Implementação de Modelos de Machine Learning
O notebook utiliza técnicas de aprendizado não supervisionado para detectar fraudes.

### 4.1 K-Means Clustering
- **Preprocessamento**: Escalonamento das colunas `TransactionAmount` e `CustomerAge` com `StandardScaler()`.
- **Agrupamento**: K-Means é aplicado com `n_clusters=3`.
- **Detecção de Fraudes**: Transações no top 5% mais distantes dos centroides são marcadas como suspeitas.
- **Visualização**: Gráfico de dispersão mostrando clusters, centroides e fraudes.

### 4.2 DBSCAN
- **Agrupamento baseado em densidade**: Identifica grupos densos e classifica pontos isolados como fraudes.
- **Resultados**: As transações são classificadas como "Normal", "Fraud" ou grupos suspeitos.

### 4.3 Agrupamento Hierárquico
- **Segmenta transações em três grupos**: "Normal", "High Amount" e "Older Age Group".
- **Visualização**: Gráfico colorido representando os clusters.

### 4.4 Isolation Forest
- **Detecção de anomalias**: Algoritmo que isola pontos fora do padrão.
- **Classificação**: Transações como "Normal" ou "Potential Fraud".
- **Visualização**: Gráfico destacando transações suspeitas.

## 5. Conclusão
O notebook aplica diferentes técnicas para detecção de fraudes:

- **K-Means**: Eficiente para segmentação, mas pode falhar em padrões complexos.
- **DBSCAN**: Identifica outliers, mas depende da escolha dos parâmetros.
- **Hierarchical Clustering**: Fornece uma visão estruturada das transações.
- **Isolation Forest**: Destaca-se na identificação de outliers.

Cada abordagem tem vantagens e limitações, podendo ser combinadas para melhores resultados.-->
