[README.md.md](https://github.com/user-attachments/files/33413216/README.md.md)
# Projeto de Machine Learning — Previsão de consumo de combustível (MPG)

## Objetivo
Explorar um problema de regressão para prever o consumo de combustível (`mpg`) a partir de características numéricas de carros.

## O que foi praticado
- Inspeção e preparação de dados com pandas e Seaborn
- Separação entre variáveis explicativas (`X`) e variável-alvo (`y`)
- Divisão entre treino e teste
- Pipeline com imputação, padronização e regressão
- Métricas de regressão: MAE, MSE, RMSE, MAPE e R²
- Validação cruzada
- Comparação entre Ridge, Lasso e ElasticNet
- Comparação de hiperparâmetros (`alpha`)
- Inspeção dos coeficientes do Lasso

## Arquivos
- `Projeto_MPG_ML_Organizado.ipynb`: notebook com o código comentado e explicações em português.

## Como executar
1. Abra o notebook no Jupyter ou Google Colab.
2. Execute as células de cima para baixo.
3. Se o Seaborn não conseguir carregar o conjunto de dados, baixe/disponibilize o CSV `mpg` e substitua a célula de carregamento por `pd.read_csv("caminho/para/mpg.csv")`.

## Dependências
Veja `requirements.txt`.

## Observações
Este repositório representa um projeto de estudo. As métricas podem variar de acordo com versões das bibliotecas e configurações. O resultado de validação cruzada não substitui uma avaliação final cuidadosa em dados reservados.

O notebook organizado neste momento corresponde ao projeto MPG do arquivo de origem. Outros estudos (por exemplo, Titanic, Diamonds ou House Prices) devem ser adicionados em notebooks separados para manter cada projeto claro e reproduzível.
