# Previsão de Renda com Dados do Censo

Este projeto tem como objetivo prever se a renda de uma pessoa excede US$50.000 por ano com base em dados demográficos do censo. É um problema de classificação binária com aplicações em marketing direcionado, análise de crédito e planejamento estratégico.

## 📌 Visão Geral

- **Objetivo**: Construir um modelo de machine learning para prever se a renda de um indivíduo excede US$50K/ano
- **Dataset**: Dados do Censo Income Dataset do UCI Machine Learning Repository
- **Técnicas**: Análise exploratória, pré-processamento, múltiplos modelos de classificação, otimização de hiperparâmetros
- **Melhor Modelo**: XGBoost com AUC de 0.92 no conjunto de teste

## 📊 Principais Insights

1. **Anos de estudo** é o fator mais importante para prever alta renda
2. **Idade** e **horas trabalhadas por semana** também são altamente relevantes
3. Estado civil **casado** e relacionamento **marido** estão associados a maior renda
4. O dataset apresenta desbalanceamento (76% <=50K vs 24% >50K)
5. Diferenças significativas foram encontradas por gênero e raça

## 🛠️ Tecnologias Utilizadas

- Python 3
- Bibliotecas: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost
- Jupyter Notebook

## 📋 Metodologia

1. **Análise Exploratória**: Compreensão dos dados, identificação de padrões e correlações
2. **Pré-process
