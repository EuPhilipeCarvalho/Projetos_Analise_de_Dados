# 📊 Previsão de Churn – Telco Customer Churn

Este projeto tem como objetivo prever o **churn** (cancelamento de serviço) de clientes de uma empresa de telecomunicações usando machine learning.  

A solução foi desenvolvida em **Python** dentro de um **notebook Jupyter**, explorando o conjunto de dados **Telco Customer Churn** e aplicando técnicas de análise exploratória, pré-processamento e modelagem preditiva.



## 📌 Etapas do Projeto

1. **Entendimento dos dados**  
   - Carregamento do dataset  
   - Análise exploratória e verificação das variáveis  

2. **Preparação dos dados**  
   - Separação da variável-alvo (churn) e das features  
   - Tratamento de dados categóricos e numéricos  
   - Divisão em conjuntos de treino e validação  

3. **Treinamento do modelo**  
   - Aplicação de algoritmos de classificação  
   - Ajuste de hiperparâmetros  

4. **Avaliação de desempenho**  
   - Métricas utilizadas: `precision`, `recall`, `f1-score`, `support`  
   - Interpretação dos resultados do modelo  

---

## 📊 Análise Exploratória

Distribuição da variável alvo (**Churn**):

![Distribuição do Churn](imgs/distribuicao_churn.png)

---

## 🧠 Importância das Features

Análise das variáveis que mais impactaram a previsão do churn:

![Importância das Features](imgs/importancia_features.png)



## 📈 Resultados

O modelo treinado apresentou desempenho satisfatório, conseguindo identificar boa parte dos clientes com maior probabilidade de cancelamento, o que pode ser usado para estratégias de retenção.

---


