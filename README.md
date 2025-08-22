# 📊 Calculadora de Métricas de Avaliação para Modelos de Classificação

Este projeto é um notebook interativo, desenvolvido em Google Colab, que serve como uma ferramenta prática para calcular e entender as principais métricas de performance para modelos de classificação em Machine Learning.

---

## 🎯 Objetivo

O objetivo principal é fornecer uma implementação clara e didática das fórmulas de avaliação, permitindo que estudantes e profissionais da área possam:
- Validar os resultados de seus próprios modelos.
- Entender o impacto de Falsos Positivos e Falsos Negativos nas métricas.
- Visualizar como cada métrica reflete um aspecto diferente da performance do modelo.

---

## 🛠️ Como Utilizar

Para usar esta calculadora, siga os passos abaixo:

1.  **Abra o Notebook:** Clique no botão "Open in Colab" acima para carregar o projeto diretamente no ambiente do Google Colaboratory.
2.  **Insira os Dados da Matriz de Confusão:** Na segunda célula de código do notebook, você encontrará as seguintes variáveis. Altere seus valores para refletir a saída do seu modelo:
    - `VP`: Verdadeiros Positivos
    - `VN`: Verdadeiros Negativos
    - `FP`: Falsos Positivos
    - `FN`: Falsos Negativos
3.  **Execute o Código:** Execute as células do notebook em sequência para que os cálculos sejam realizados e os resultados exibidos.

---

## 📖 Métricas Calculadas

O notebook calcula as seguintes métricas fundamentais:

| Métrica | Descrição |
| :--- | :--- |
| **Acurácia** | Percentual geral de acertos do modelo. |
| **Precisão** | De todas as previsões positivas, quantas estavam corretas. |
| **Sensibilidade (Recall)**| De todos os exemplos que eram realmente positivos, quantos o modelo acertou. |
| **Especificidade** | De todos os exemplos que eram realmente negativos, quantos o modelo acertou. |
| **F-score** | Média harmônica entre Precisão e Sensibilidade, útil para dados desbalanceados. |

### Fórmulas Utilizadas

As métricas são calculadas de acordo com as seguintes fórmulas:

| Métrica | Fórmula em LaTeX |
| :--- | :--- |
| **Sensibilidade** | $$ \frac{VP}{VP+FN} $$ |
| **Especificidade** | $$ \frac{VN}{FP+VN} $$ |
| **Acurácia** | $$ \frac{VP+VN}{VP+VN+FP+FN} $$ |
| **Precisão** | $$ \frac{VP}{VP+FP} $$ |
| **F-score** | $$ 2 \times \frac{Precisão \times Sensibilidade}{Precisão + Sensibilidade} $$ |

---

## 🔧 Tecnologias

- **Python 3**
- **Google Colab**

---

## ✍️ Autor

Angelo Gatti Neto
