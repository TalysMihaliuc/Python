# Anáslise de Ativos da B3 com base na fórmula de grandes investidores

Esse script faz um WebScraping nos sites  [status Invest](http://www.statusinvest.com.br) e [fundamentus](http://www.fundamentus.com.br) para obter esses dados, 
e usa a Biblioteca Fundamentus, gerando um arquivo de excel com o ranking de acordo com as 2 formulas selecionando 10 ações em cada

## Etapas

0. [X] Fazer Webscraping dados no site www.statusinvest.com.br
1. [X] Fazer Webscraping dados de Proventos no site www.fundamentus.com.br
2. [X] Capturar setores da bolsa usando a biblioteca fundamentos
3. [X] Calcular ranking de acoes com base na fórmula Magic Formula Joel Greenblatt
4. [X] Calcular ranking de acoes com base na fórmula de Decio Bazin
5. [X] Interpretação dos resultados (Conclusão)







## Requerimentos
Python >= 3

## Bibliotecas
* import warnings
* import requests
* import pandas as pd
* import numpy as np
* import json
* import fundamentus
* import ast


