# 🚀 Predição de Churn com Machine Learning (PySpark)

## 📝 O que é este projeto?

Projeto desenvolvido para previsão de evasão de clientes (churn) utilizando PySpark e técnicas de Machine Learning.

O objetivo é identificar padrões de cancelamento e gerar insights que apoiem estratégias de retenção de clientes.

---

## 📊 Gráfico de Importância das Features



![Importância das Features](importancia_features_v2.png)



[Gráfico de Importância](importancia_features_v2.png)




## 🛠️ Etapas do Projeto

### 🔹 Tratamento e Preparação dos Dados
- Conversão de variáveis categóricas em numéricas (Dummies)
- Limpeza e padronização dos dados

### 🔹 Engenharia de Features
- Vetorização de 24 características em vetor esparso  
- Otimização para processamento em larga escala  

### 🔹 Modelagem
- Regressão Logística  
- Árvore de Decisão  
- Random Forest  

---

## 📊 Resultados

- Modelo final: **Random Forest**  
- Acurácia: **77,12%**  
- Dataset balanceado (50% churn / 50% não churn)

---

## 🧠 Insights de Negócio

A análise de importância das variáveis revelou os principais fatores de cancelamento:

- Meses de contrato → clientes novos apresentam maior risco de churn  
- Valor cobrado → impacto direto na retenção  
- Segurança online → serviços adicionais aumentam fidelização  

---
## 🎯 Diferencial do Projeto

Este projeto vai além da modelagem preditiva, focando na geração de insights de negócio e demonstrando como dados podem apoiar decisões estratégicas de retenção de clientes.

---

## 💻 Tecnologias Utilizadas

- Python  
- PySpark  
- Spark MLlib  
- Pandas  
- Matplotlib  
- Google Colab  

---

## 🔎 Observação

Projeto desenvolvido como parte da minha evolução prática em Engenharia de Dados e Machine Learning, com foco na aplicação real dos conceitos.
