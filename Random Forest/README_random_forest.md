# 🏡 Predição de Preços de Casas com Random Forest e Decision Tree

## 📌 Descrição
Este projeto aplica **Machine Learning (Regressão)** para prever preços de imóveis utilizando o dataset `train.csv`.  
O objetivo é comparar a performance entre o **Random Forest Regressor** e o **Decision Tree Regressor** com diferentes números de folhas (`max_leaf_nodes`).  

Além de treinar os modelos, o notebook também apresenta uma **análise visual (linha e barras)** do **Erro Médio Absoluto (MAE)** em função do número de folhas, explorando conceitos de **underfitting e overfitting**.

---

## 🎯 Objetivos
- Entender o funcionamento de **árvores de decisão** e **ensembles (Random Forest)**.  
- Avaliar o impacto do número de folhas na performance de uma Decision Tree.  
- Comparar a capacidade de generalização entre modelos simples e ensembles.  
- Praticar o uso de **Pandas** e **Scikit-learn** para regressão supervisionada.  

---

## 🛠 Tecnologias Utilizadas
- Python 3  
- Pandas  
- Scikit-learn  
- Matplotlib  

---

## 📂 Estrutura
- `random_forest_regressor.ipynb` → Notebook principal do projeto.  
- `train.csv` → Dataset de preços de casas (House Prices).  

---

## 🚀 Como Executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repo.git
   cd nome-do-repo
   ```
2. Instale as dependências:
   ```bash
   pip install pandas scikit-learn matplotlib
   ```
3. Abra o notebook no Jupyter ou PyCharm e execute célula por célula:
   ```bash
   jupyter notebook random_forest_regressor.ipynb
   ```

---

## 📊 Resultados
- **Random Forest** apresentou bom desempenho, com menor MAE em relação a árvores de decisão muito simples ou muito complexas.  
- A **Decision Tree com 50 folhas** apresentou o **melhor resultado entre as árvores**, superando configurações com 5, 500 e 5000 folhas.  

### Visualização (exemplo de saída):
#### 📈 Gráfico de Linha
Mostrando o comportamento do MAE em função do número de folhas:  
- Poucas folhas → **underfitting** (erro alto).  
- Muitas folhas → **overfitting** (erro volta a subir).  
- Número intermediário (~50) → **melhor equilíbrio**.  

---

## 📈 Aprendizados
- **Underfitting:** modelos simples demais não capturam padrões (5 folhas).  
- **Overfitting:** modelos muito complexos memorizam os dados (5000 folhas).  
- **Trade-off viés x variância:** o melhor ponto está no meio (~50 folhas).  
- O **Random Forest** tende a generalizar melhor, mas uma Decision Tree bem configurada pode chegar próximo.  


