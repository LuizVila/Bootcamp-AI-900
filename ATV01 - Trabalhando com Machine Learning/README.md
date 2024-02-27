<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="60px" src="https://hermes.dio.me/lab_projects/badges/87d332d0-5198-4a2f-b159-38c8c2976954.png"></a>
    <span> Trabalhando com Machine Learning</span>
</h1>

## Criando modelo de previsão - Passo a passo

O passo a passo para ser seguido, é disponibilizado pela própria microsoft, através do link:

https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html

## Teste do modelo

![01](https://github.com/LuizVila/Bootcamp-AI-900/assets/50930798/31777a36-d724-40fa-b763-6bd34a219e48)

![02](https://github.com/LuizVila/Bootcamp-AI-900/assets/50930798/4d221620-6de0-497f-8e99-3a0f071661ab)

![03](https://github.com/LuizVila/Bootcamp-AI-900/assets/50930798/25503e93-6a6a-49f6-a20f-c571e31dd39a)

![04](https://github.com/LuizVila/Bootcamp-AI-900/assets/50930798/e82969a1-c4b9-4a0d-b207-72cf7cfa869c)

![05](https://github.com/LuizVila/Bootcamp-AI-900/assets/50930798/89696d57-4bdb-4a39-96c1-29472b2d7b20)


Para o teste, utilizei o json abaixo:

``` JASON
 {
   "Inputs": { 
     "data": [
       {
         "day": 1,
         "mnth": 1,   
         "year": 2022,
         "season": 2,
         "holiday": 0,
         "weekday": 1,
         "workingday": 1,
         "weathersit": 2, 
         "temp": 0.3, 
         "atemp": 0.3,
         "hum": 0.3,
         "windspeed": 0.3 
       }
     ]    
   },   
   "GlobalParameters": 1.0
 }
```

A previsão gerada foi:

{1 item
"Results":[1 item
0:float354.2802801444516
]
}

<img align="right" src="https://raw.githubusercontent.com/alexklenio/DIO-Microsoft-Azure-AI-Fundamentals/main/imagens/DP01%20-%20Machine%20Learning/18.png" width="/> 
