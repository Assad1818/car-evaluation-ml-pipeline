# 🚗 Esteira de Aprendizado de Maquina — Car Evaluation

Notebook Python com pipeline completo de Machine Learning para classificacao de veiculos, usando o **Car Evaluation Dataset** do UCI Machine Learning Repository.

## Dataset

**Car Evaluation — UCI Machine Learning Repository**
- 1.728 instancias, 6 atributos categoricos ordinais
- Problema: classificacao multiclasse (unacceptable / acceptable / good / vgood)
- Fonte: https://archive.ics.uci.edu/dataset/19/car+evaluation

## Resultado

- **Acuracia no Teste: 96.15%**
- **Modelo:** Random Forest Classifier (300 arvores)

## Etapas da Esteira

| # | Etapa |
|---|---|
| 1 | Carregamento dos dados |
| 2 | Estatisticas descritivas e visualizacoes |
| 3 | Transformacoes em colunas (Ordinal Encoding + Feature Engineering) |
| 4 | Transformacoes em linhas (duplicatas + inconsistencias) |
| 5 | Divisao treino/validacao/teste 70/15/15 estratificada |
| 6 | Treinamento Random Forest Classifier |
| 7 | Matriz de Confusao e Acuracia |
| 8 | Predicao de novos carros com probabilidades |

## Como Reproduzir

```bash
# 1. Clone o repositorio
git clone https://github.com/SEU_USUARIO/car-evaluation-ml-pipeline.git
cd car-evaluation-ml-pipeline

# 2. Instale as dependencias
pip install pandas numpy matplotlib seaborn scikit-learn notebook

# 3. Abra o notebook
jupyter notebook car_evaluation_ml_pipeline.ipynb

# 4. Execute todas as celulas
# Kernel > Restart & Run All
```

## Stack

- **Linguagem:** Python 3
- **Bibliotecas:** scikit-learn, pandas, numpy, matplotlib, seaborn
- **Ambiente:** Jupyter Notebook
