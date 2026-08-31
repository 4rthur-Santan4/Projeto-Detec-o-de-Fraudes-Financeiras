# 💳 Detecção de Fraudes em Transações Financeiras

Projeto desenvolvido durante o **Bootcamp Bradesco - GenAI, Dados & Cyber**, em parceria com a **DIO**.

## 🎯 Sobre o projeto

O objetivo deste projeto é aplicar técnicas de **Machine Learning para identificar transações fraudulentas** em um conjunto de dados de cartões de crédito.

Como o dataset possui um forte desbalanceamento entre transações normais e fraudulentas, foram exploradas diferentes técnicas para melhorar a identificação da classe minoritária.

## 🛠️ Tecnologias

- Python
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn
- XGBoost
- SHAP
- Matplotlib
- Jupyter Notebook

## 🔎 O que foi desenvolvido

Durante o projeto foram exploradas:

- Análise e preparação dos dados
- Feature Engineering
- Regressão Logística
- Random Forest
- XGBoost
- Undersampling
- SMOTE
- Ajuste do threshold de classificação
- Avaliação com Precision, Recall, F1-Score e ROC-AUC
- Análise de importância das variáveis
- Ajuste de hiperparâmetros
- Explicabilidade do modelo utilizando SHAP

## 📊 Dataset

Foi utilizado o dataset **Credit Card Fraud Detection**, contendo informações sobre transações de cartão de crédito.

A variável `Class` indica se uma transação é:

- `0` → Normal
- `1` → Fraudulenta

## 🚀 Como executar

Clone o repositório e instale as dependências:

```bash
pip install pandas numpy scikit-learn imbalanced-learn xgboost shap matplotlib jupyter
```

Depois, execute o notebook:

```text
Projeto_deteccao_anomalias.ipynb
```

O dataset é carregado diretamente no notebook.

## 🧠 Aprendizados

O projeto possibilitou colocar em prática conceitos de **Machine Learning, classificação desbalanceada, avaliação de modelos e explicabilidade**, aplicados a um problema real de detecção de fraudes.

## 🎓 Bootcamp

Projeto desenvolvido durante o **Bootcamp Bradesco - GenAI, Dados & Cyber** em parceria com a **DIO**.

---

👨‍💻 **Autor:** Arthur Pateis Santana de Oliveira
