# Classificador de Árvore de Decisão para Diagnóstico de Câncer de Mama

Este projeto implementa um classificador de árvore de decisão para prever diagnósticos de câncer de mama (Maligno ou Benigno) usando o Breast Cancer Wisconsin (Diagnostic) Dataset. O modelo utiliza características extraídas de imagens de núcleos celulares obtidas de biópsias de tecido mamário.

## Conjunto de Dados

O conjunto de dados contém 569 amostras com 30 características numéricas que descrevem os núcleos celulares, como:
- Raio
- Textura
- Perímetro
- Área
- Suavidade
- Compacidade
- Concavidade
- Simetria
- Dimensão fractal
- A última coluna, Diagnosis, é a variável alvo, que pode ser:
  -M para Maligno
  -B para Benigno
  
## Informações sobre o arquivo

**Nome do arquivo:** breast_cancer_wisconsin_diagnostic.csv

**Linhas:** 569

**Colunas:** 31 (30 características + 1 variável alvo)

## Estrutura do Projeto
**modelo_arvore_decisao.ipynb:** Este notebook Jupyter contém todos os passos para construir, treinar e avaliar um classificador de árvore de decisão.

**Preparação dos Dados:** O conjunto de dados é carregado e dividido em conjuntos de treino e teste.

**Criação do Modelo:** Um classificador de árvore de decisão é criado usando a biblioteca scikit-learn.

**Avaliação do Modelo:** O modelo é avaliado com base em métricas de acurácia, recall e precisão.

## Como Executar o Projeto

**1. Clone o repositório:**

`git clone https://github.com/lucasanbe/breast-cancer-detection.git`

**2. Instale as dependências necessárias:**

`pip install -r requirements.txt`

**3. Execute o notebook Jupyter:**

`jupyter notebook decision_tree_classification_model.ipynb`

## Resultados

O modelo obteve o seguinte desempenho no conjunto de teste:
- Acurácia: 94,74%
- Recall: 93,02%
- Precisão: 93,02%

Esses resultados indicam que o modelo tem um bom desempenho na distinção entre casos benignos e malignos.

________________________________________________________________________________________________________________________________________________________________________________________________________

# Decision Tree Classifier for Breast Cancer Diagnosis

This project implements a decision tree classifier to predict breast cancer diagnoses (Malignant or Benign) using the Breast Cancer Wisconsin (Diagnostic) Dataset. The model uses features extracted from cell nuclei images obtained from breast tissue biopsies.

## Dataset

The dataset contains 569 samples with 30 numerical features describing the cell nuclei, such as:
- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Symmetry
- Fractal dimension
- The last column, Diagnosis, is the target variable, which can be:
	- M for Malignant
	- B for Benign
  
## File Information

**File name:** breast_cancer_wisconsin_diagnostic.csv

**Rows:** 569

**Columns:** 31 (30 features + 1 target variable)

## Project Structure
**decision_tree_classification_model.ipynb:** This Jupyter notebook contains all the steps to build, train, and evaluate a decision tree classifier.

**Data Preparation:** The dataset is loaded and split into training and testing sets.

**Model Creation:** A decision tree classifier is created using the scikit-learn library.

**Model Evaluation:** The model is evaluated based on accuracy, recall, and precision metrics.

## How to Run the Project

**1. Clone the repository:**

`git clone https://github.com/lucasanbe/breast-cancer-detection.git`

**2. Install the necessary dependencies:**

`pip install -r requirements.txt`

**3. Run the Jupyter notebook:**

`jupyter notebook decision_tree_classification_model.ipynb`

## Results

The model achieved the following performance on the test set:

- Accuracy: 94.74%
- Recall: 93.02%
- Precision: 93.02%

These results indicate that the model performs well in distinguishing between benign and malignant cases.
