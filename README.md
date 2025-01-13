# Projeto de Cálculo de Métricas de Avaliação

Este projeto tem como objetivo calcular as principais métricas de avaliação de modelos de classificação, como **acurácia**, **sensibilidade (recall)**, **especificidade**, **precisão** e **F-score**, com base em uma matriz de confusão.

## Métricas Calculadas

As métricas são calculadas usando as seguintes fórmulas:

- **Acurácia**: $\frac{\text{VP} + \text{VN}}{\text{VP} + \text{VN} + \text{FP} + \text{FN}}$
- **Sensibilidade (Recall)**: $\frac{\text{VP}}{\text{VP} + \text{FN}}$
- **Especificidade**: $\frac{\text{VN}}{\text{FP} + \text{VN}}$
- **Precisão**: $\frac{\text{VP}}{\text{VP} + \text{FP}}$
- **F-score**: $2 \times \frac{\text{Precisão} \times \text{Sensibilidade}}{\text{Precisão} + \text{Sensibilidade}}$

Onde:
- **VP**: Verdadeiros Positivos
- **VN**: Verdadeiros Negativos
- **FP**: Falsos Positivos
- **FN**: Falsos Negativos

## Como Usar

### Pré-requisitos

- Python 3.x
- Bibliotecas: `numpy`, `tensorflow`, `matplotlib`, `seaborn`, `pandas`

### Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/SilvanFelipe/projeto-metricas.git
