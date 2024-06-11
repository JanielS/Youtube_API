# Descrição do projeto

O objetivo do projeto é obter informações detalhadas de todos os videos de vários canais do Youtube. Em sequida, esses dados serão tratados e armazenados em um Banco de dados para futuras análises.

## Inspiration
Esse projeto dará início a outro maior que objetiva analisar se o crescimento dos diferentes meios de comunicação sobre finanças tem de fato impactado o comportamento das pessoas com relação ao dinheiro ou servem apenas como mais uma forma de entreterdimento.

## Etapas
![image](https://github.com/JanielS/Youtube_API/blob/main/Images/Diagram_YoutubeAPI.png)<br>
*fonte: autor*
<br>
<br>

Os canais selecionados para realizar a raspagem foram:
1. [Me Poupe!](https://www.youtube.com/@MePoupe)
2. [Clube de Valor](https://www.youtube.com/@ClubedoValor)
3. [Gustavo Cerbasi](https://www.youtube.com/@GustavocerbasiBr)


## Requirements
A linguagem dinâmica escolhida foi Python, para IDE eu optei pelo jupyter lab e para armazenamento o MySQL.

## Packages
Instale os seguintes pacotes

``` Python
import numpy as np
import pandas as pd
import seaborn as sns 
import matplotlib.pyplot as plt
from IPython.display import JSON
from sqlalchemy import create_engine
from googleapiclient.discovery import build
from getpass import getpass  # Não exibir a senha
```

## Autor
> Janiel Santos. - [Github](https://github.com/JanielS) - Maio 2024
<br>
<br>
<br>

![image](https://github.com/JanielS/Youtube_API/blob/main/Images/Loading.png)

