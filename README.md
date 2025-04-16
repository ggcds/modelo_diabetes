# Predição de Diabetes com Machine Learning

Este projeto utiliza algoritmos de aprendizado de máquina para prever a presença de diabetes em pacientes, com base em um conjunto de dados contendo informações clínicas. O objetivo é aplicar técnicas de classificação para auxiliar no diagnóstico precoce da doença.

## 📊 Sobre o Projeto

O notebook `modelo_diabetes.ipynb` inclui:

- **Carregamento e exploração do dataset**: Análise das variáveis do conjunto de dados de diabetes.
- **Pré-processamento**: Tratamento de valores ausentes, normalização dos dados e separação em conjuntos de treino e teste.
- **Modelagem**: Treinamento de modelos de classificação como Random Forest, SVM, KNN, entre outros.
- **Avaliação**: Métricas de desempenho como acurácia, matriz de confusão e ROC AUC.

## 📁 Estrutura do Projeto

```
📦modelo-diabetes
 ┣ 📜modelo_diabetes.ipynb
 ┣ 📜README.md
 ┗ 📜requirements.txt
```

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/modelo-diabetes.git
   cd modelo-diabetes
   ```

2. Crie um ambiente virtual e ative:
   ```bash
   python -m venv venv
   source venv/bin/activate  # ou .\venv\Scripts\activate no Windows
   ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

4. Rode o notebook:
   ```bash
   jupyter notebook modelo_diabetes.ipynb
   ```

## 🧪 Requisitos

Você pode instalar todas as dependências usando o arquivo `requirements.txt`. Aqui estão as principais bibliotecas utilizadas:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## 📚 Dataset

Este projeto utiliza o dataset **Pima Indians Diabetes Database**, disponível em:  
[https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

## 📌 Objetivo Educacional

Este repositório faz parte das atividades práticas do curso de Inteligência Artificial, com foco no uso de técnicas supervisionadas de classificação.

---

👨‍💻 Desenvolvido por Guilherme Caldas
