# 📊 Cálculo de Métricas de Avaliação de Classificação

Este projeto tem como objetivo implementar e compreender as principais **métricas de avaliação** utilizadas em modelos de classificação de dados.  
As métricas são calculadas a partir de uma **matriz de confusão** definida de forma arbitrária, apenas para fins didáticos.

---

## ⚡ Descrição do Projeto

Neste notebook você encontrará:
- Implementação das fórmulas de **Acurácia, Precisão, Sensibilidade (Recall), Especificidade e F1-Score**.
- Exibição dos resultados em formato de tabela.
- Visualização gráfica da **Matriz de Confusão**.
- Explicações didáticas sobre cada métrica.

---

## 📌 Métricas Calculadas

- **Acurácia** → Proporção de acertos sobre o total de previsões.  
- **Precisão** → Entre os exemplos classificados como positivos, quantos realmente eram positivos.  
- **Sensibilidade (Recall)** → Entre os exemplos realmente positivos, quantos foram identificados corretamente.  
- **Especificidade** → Entre os exemplos realmente negativos, quantos foram classificados corretamente.  
- **F1-Score** → Média harmônica entre precisão e recall (boa para dados desbalanceados).  

---

## 📊 Exemplo de Matriz de Confusão

         Classe Real
         P       N
Classe P [VP] [FN]
Prevista N [FP] [VN]


No notebook, utilizamos valores arbitrários:
- VP = 50  
- VN = 40  
- FP = 10  
- FN = 5  

---

## 🚀 Como Executar

1. Abra o projeto no **Google Colab** ou em seu ambiente local com Jupyter Notebook.  
2. Execute todas as células.  
3. Veja os resultados das métricas e a visualização da matriz de confusão.  

---

## 🛠️ Tecnologias Utilizadas

- Python 3  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 📚 Aprendizado

Este projeto é voltado para fins **didáticos**, com o objetivo de consolidar o entendimento sobre as métricas de avaliação de classificadores em **Machine Learning**.  

---

## 📎 Links Úteis

- [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/estevaoMG/Avaliacao-de-Aprendizado/blob/main/AvaliacaoDeAprendizado.ipynb)  
- [Repositório no GitHub](https://github.com/estevaoMG/Avaliacao-de-Aprendizado)

---

✍️ Autor: **Estevão Gouveia**
