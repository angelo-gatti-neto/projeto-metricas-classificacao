{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": []
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "source": [
        "# 📊 Calculadora de Métricas de Avaliação para Modelos de Classificação\n",
        "\n",
        "Este projeto é um notebook interativo, desenvolvido em Google Colab, que serve como uma ferramenta prática para calcular e entender as principais métricas de performance para modelos de classificação em Machine Learning.\n",
        "\n",
        "[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SEU-USUARIO-GITHUB/NOME-DO-SEU-REPOSITORIO/blob/main/calculadora_metricas.ipynb)\n",
        "\n",
        "---\n",
        "\n",
        "## 🎯 Objetivo\n",
        "\n",
        "O objetivo principal é fornecer uma implementação clara e didática das fórmulas de avaliação, permitindo que estudantes e profissionais da área possam:\n",
        "- Validar os resultados de seus próprios modelos.\n",
        "- Entender o impacto de Falsos Positivos e Falsos Negativos nas métricas.\n",
        "- Visualizar como cada métrica reflete um aspecto diferente da performance do modelo.\n",
        "\n",
        "---\n",
        "\n",
        "## 🛠️ Como Utilizar\n",
        "\n",
        "Para usar esta calculadora, siga os passos abaixo:\n",
        "\n",
        "1.  **Abra o Notebook:** Clique no botão \"Open in Colab\" acima para carregar o projeto diretamente no ambiente do Google Colaboratory.\n",
        "2.  **Insira os Dados da Matriz de Confusão:** Na segunda célula de código do notebook, você encontrará as seguintes variáveis. Altere seus valores para refletir a saída do seu modelo:\n",
        "    - `VP`: Verdadeiros Positivos\n",
        "    - `VN`: Verdadeiros Negativos\n",
        "    - `FP`: Falsos Positivos\n",
        "    - `FN`: Falsos Negativos\n",
        "3.  **Execute o Código:** Execute as células do notebook em sequência para que os cálculos sejam realizados e os resultados exibidos.\n",
        "\n",
        "---\n",
        "\n",
        "## 📖 Métricas Calculadas\n",
        "\n",
        "O notebook calcula as seguintes métricas fundamentais:\n",
        "\n",
        "| Métrica | Descrição |\n",
        "| :--- | :--- |\n",
        "| **Acurácia** | Percentual geral de acertos do modelo. |\n",
        "| **Precisão** | De todas as previsões positivas, quantas estavam corretas. |\n",
        "| **Sensibilidade (Recall)**| De todos os exemplos que eram realmente positivos, quantos o modelo acertou. |\n",
        "| **Especificidade** | De todos os exemplos que eram realmente negativos, quantos o modelo acertou. |\n",
        "| **F-score** | Média harmônica entre Precisão e Sensibilidade, útil para dados desbalanceados. |\n",
        "\n",
        "### Fórmulas Utilizadas\n",
        "\n",
        "As métricas são calculadas de acordo com as seguintes fórmulas:\n",
        "\n",
        "| Métrica | Fórmula em LaTeX |\n",
        "| :--- | :--- |\n",
        "| **Sensibilidade** | $$ \\frac{VP}{VP+FN} $$ |\n",
        "| **Especificidade** | $$ \\frac{VN}{FP+VN} $$ |\n",
        "| **Acurácia** | $$ \\frac{VP+VN}{VP+VN+FP+FN} $$ |\n",
        "| **Precisão** | $$ \\frac{VP}{VP+FP} $$ |\n",
        "| **F-score** | $$ 2 \\times \\frac{Precisão \\times Sensibilidade}{Precisão + Sensibilidade} $$ |\n",
        "\n",
        "---\n",
        "\n",
        "## 🔧 Tecnologias\n",
        "\n",
        "- **Python 3**\n",
        "- **Google Colab**\n",
        "\n",
        "---\n",
        "\n",
        "## ✍️ Autor\n",
        "\n",
        "Angelo Gatti Neto"
      ],
      "metadata": {
        "id": "15Mve5InmDwL"
      }
    }
  ]
}