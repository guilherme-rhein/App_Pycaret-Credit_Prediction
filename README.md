<h1 align="center">
    💲 Aplicativo Classificador para Concessão de Crédito 💲</a>
</h1>

<p align="center"> A proposta do projeto é um modelo de machine learning baseado em informações de bons ou maus clientes, abrangendo todo o pipeline de processamento dos dados para prever quais clientes poderão utilizar do crédito. </p>

---
<h3 align="center">
    🏆 Teste Aqui: <a href="https://app-pycaret-credit-prediction.onrender.com">Aplicativo para Classificação de Crédito 🏆 </a>
</h3>

---


https://github.com/guilherme-rhein/App_Pycaret-Credit_Prediction/assets/88910779/b4d5bbe9-781f-41aa-8d31-67fa4b05eaa5


## Base do Projeto 💻

Solução para um problema de concessão de crédito, utilizando uma amostra de 15 safras coletadas entre Jan/15 e Mar/16. A técnica de machine learning utilizando Pycaret é prever a possibilidade do cliente ser classificado como inadimplência, sendo assim os clientes inadimplentes são definidos como "maus" no conjunto de dados.

Os dados coletados são explorados para gerar conhecimento de sua estrutura, distribuição, correlações e padrões, além de passar pelo processo de tratamento de dados com a correção de valores faltantes, categorização, normalizar variáveis numéricas entre outras transformações necessárias.

Finalmente após os ajustes e validações, salvamos o modelo em um arquivo que é utilizado dentro do aplicativo desenvolvido no Streamlit objetivando um acesso interativo e autoexplicativo ao usuário. Para todo e qualquer modelo existe um tempo de vida, seja por mudanças econômicas, política, sazonalidade e até mesmo questões mais sensíveis e difíceis de serem explicadas. Quando chegar o momento de atualizar o modelo preditivo será muito mais fácil todo trabalho gerado pelos desenvolvedores para que seja atualizado no aplicativo quando necessário. 

Sua utilização sempre que seja necessária a análise dos relatórios internos da empresa será possível carregando no aplicativo de predição, este retornará suas previsões com base no modelo em um arquivo Excel.


## Desenvolvimento do Projeto 🛠️

Acesse os detalhes sobre o desenvolvimento no jupyter notebook, clicando no ✅ abaixo:
- [✅](https://github.com/guilherme-rhein/EBAC---DATA-SCIENCE/tree/main/M%C3%B3dulo%2038%20-%20Streamlit%20VI%20e%20Pycaret) Módulo 38 - Streamlit VI e Pycaret


## Bibliotecas Utilizadas 📚

```bash
import joblib
import requests
import xlsxwriter
import pandas as pd
import streamlit as st
from io import BytesIO
from pycaret.classification import load_model, predict_model
```
