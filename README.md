* Projeto de Séries Temporais (Cesar School) - Professor : Domingos Sávio de Oliveira
* Aluno: Ricardo José Nunes Fernandes
* Dataset - Mapa de Estações - Aeroporto de São Paulo / https://mapas.inmet.gov.br/

## Overview

Foi solicitado como projeto de conclusão da cadeira de Séries Temporais, a escolha de uma Série na internet, uma análise de Auto Correlação e Auto Correlação Parcial, separando os últimos 10% dos dados para teste, juntamente a uma aplicação de um Modelo Auto-Arima, um modelo de Machine Learning e um Ensemble. Como modelo de ML foi escolhido o MLPRegressor e no Ensemble foram escolhidos os modelos Random Forest + Gradient boosting realizando um Grid search de parâmetros.

## Dependencies

* Google Coolab - Python versão 3.7.12

## Notebook

https://colab.research.google.com/drive/1XdcJSRUa24QW3JudIw5_yl3Vs6c-6nXZ#scrollTo=-QIV10r0HYSy

No notebook está o código de tudo descrito no overview, como o modelo Auto-Arima, o Modelo MLPRegressor e um ensemble Random Forest + Gradient boosting com Grid Search para otimização de parâmetros. Tudo avaliação na base de teste ( 10% dos dados ). Ao final as métricas e plots dos modelos utilizados.

Conjunto de dados

A base de dados foi extraida do site Inmet - Instituno Nacional de Meteorologia, na API Mapa das Estações no site https://mapas.inmet.gov.br/. Foi escolhido a série do Aeroport de São Paulo, de código "83780", entre as datas - 01/01/2015 até 01/01/2022.
