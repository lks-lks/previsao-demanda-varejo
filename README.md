# Previsão de Demanda no Varejo com Machine Learning

Este projeto demonstra como prever a demanda de vendas com base em variáveis como preço, estoque e datas. Utilizamos Machine Learning para modelar padrões de compra com foco em simplicidade, interpretabilidade e aplicação prática.

Mesmo com uma base relativamente simples, é possível obter informações que são de grande ajuda.

---

## Objetivo

Prever a quantidade de vendas com base em dados históricos, ajudando na **tomada de decisão**, **planejamento de estoque** e **otimização de recursos**.

---

## Tecnologias

- `Python` | `Pandas` | `NumPy`
- `Matplotlib` | `Seaborn`
- `Scikit-learn` (Random Forest)
- Ambiente: Google Colab

---

## Processo

1. **Leitura e exploração dos dados** (`mock_kaggle.csv`)  
2. **Criação de novas variáveis temporais** (ano, mês, dia, dia da semana)  
3. **Modelagem preditiva** com Random Forest Regressor  
4. **Avaliação com MAE** (erro absoluto médio)  
5. **Visualizações para interpretação do modelo**

---

## Resultado

- Modelo alcançou um **MAE satisfatório**, mesmo com variáveis simples.  
- Os gráficos dentro do notebook ajudam a entender o comportamento da previsão:
