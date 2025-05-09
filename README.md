# Prevendo Vendas de Sorvete usando Machine Learning  - Projeto DIO
Machine Learning para prever vendas de sorvetes com base na temperatura do dia. 

## Cenário
O proprietário de uma sorveteria chamada Gelato Mágico, localizada em uma cidade litorânea, deseja  otimizar sua produção, reduzindo desperdícios e maximizando seus lucros. 
A quantidade de sorvetes vendidos diariamente tem uma forte correlação com a temperatura ambiente. 
No entanto, sem um planejamento adequado, pode-se acabar produzindo mais sorvetes do que o necessário e ter prejuízos com desperdícios ou, ao contrário, produzir menos e perder vendas.

Para solucionar esse problema, opta-se por usar Machine Learning para prever quantos sorvetes serão vendidos com base na temperatura. 
Com esse modelo, será possível antecipar a demanda e planejar a produção de maneira eficiente.

## Objetivo
O objetivo deste projeto é desenvolver um modelo de regressão preditiva que permita: 

✅ Treinar um modelo de Machine Learning para prever as vendas de sorvete com base na temperatura do dia.

✅ Registrar e gerenciar o modelo usando o MLflow.

✅ Implementar o modelo para previsões em tempo real em um ambiente de cloud computing.

✅ Criar um pipeline estruturado para treinar e testar o modelo, garantindo reprodutibilidade.


![ChatGPT Image 25 de abr  de 2025, 16_41_11](https://github.com/user-attachments/assets/135b737e-3c93-4068-a61f-8e1177d213ba)

# Obtendo conjunto de dados via ChatGPT
Temperatura (°C) | Vendas de Sorvete

20 | 40

22 | 50

24 | 65

26 | 75

28 | 90

30 | 105

32 | 120

34 | 135

36 | 150

38 | 165

https://github.com/sijacinto/RegressaoLinearSorvetes/blob/main/Inputs/sorvete_dataset.csv

# Análise de dados via ChatGPT (Regressão linear)
![image](https://github.com/user-attachments/assets/7b16c22c-d0fe-4ca8-99af-405eb5445f83)

# Análise de dados via Excel (Regressão linear)
![image](https://github.com/user-attachments/assets/d7025efa-f82d-4a98-90cf-a7059044a991)

# Obtendo novo conjunto de dados referentes a Vendas de Sorvete x Temperatura
https://www.kaggle.com/datasets/sakshisatre/ice-cream-sales-dataset

# Obtenção e análise de dados. Geração do modelo usando Notebook Python via Google Colab
![image](https://github.com/user-attachments/assets/fc697436-f0cd-4df7-8745-6032979c4d68)

# Preparando o ambiente no Azure Machine Learning
![image](https://github.com/user-attachments/assets/606dc012-9855-404a-be8b-275156bd13af)

# Utilizando o ambiente Azure Machine Learning (AML)
![image](https://github.com/user-attachments/assets/7b69284d-102f-440f-89c2-d70e8ed90d97)

## Criando Cluster e instância de computação no AML
![image](https://github.com/user-attachments/assets/c3c74fd8-87dd-4eae-8059-eb4a03c663e1)

## Carregando os dados para o AML
![image](https://github.com/user-attachments/assets/16e2890e-9e4a-40c2-a8cb-9732cc5c2e14)
## Usando o Automated ML para treinar modelo de regressão linear
![image](https://github.com/user-attachments/assets/bfe0b2b5-71d9-4bc8-925e-33d0d49bb2ff)
### Configurações
![image](https://github.com/user-attachments/assets/b2e5563d-ca97-4431-8166-b41e6d39b99a)

![image](https://github.com/user-attachments/assets/2a7909e2-84d1-4250-8bb5-b1540b4ef4fc)

![image](https://github.com/user-attachments/assets/94c10002-02b7-49c2-a8a5-4ccf5dfae983)

![image](https://github.com/user-attachments/assets/665c3f3d-41a3-4a63-85be-a38912994bbb)

![image](https://github.com/user-attachments/assets/3cfad66f-e973-4026-a4cf-25cb265b765f)

## Rodando os jobs
![image](https://github.com/user-attachments/assets/b947f76b-b545-4903-9918-5cf85d033260)

![image](https://github.com/user-attachments/assets/0b3eca19-0258-4435-926b-90ca62ce6977)

## Registro e deploy de modelos preditivos

![image](https://github.com/user-attachments/assets/744fede6-acb1-40e5-8ad9-3c497d032bbe)


![image](https://github.com/user-attachments/assets/c5f4cf30-f4cb-4559-83dc-393fa1e3a1fb)


![image](https://github.com/user-attachments/assets/0da582bf-e268-471f-9471-90c3206ce4a9)
















