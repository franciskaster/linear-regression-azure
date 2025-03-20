# Vendas Preditivas de Picolés com Linear Regression no Azure ML

## Visão Geral
Este projeto foi desenvolvido para prever a quantidade de picolés vendidos com base na temperatura do dia.

## Contexto do Projeto
O projeto busca prever quantos picolés um vendedor vai vender no dia, de acordo com a temperatura do dia, para evitar desperdícios ou perdas.

## Tecnologias Utilizadas
- **Azure**  – Base do projeto.
- **MLflow** – Para gerenciamento e registro de experimentos.


## Projeto
Para desenvolver o modelo de previsão de vendas de picolés, foi utilizado um dataset contendo a quantidade de vendas registradas para cada dia do mês, além da temperatura correspondente a esses dias. A construção da pipeline no Azure Machine Learning foi a seguinte:

![2025-03-18_21-28_1](https://github.com/user-attachments/assets/1a116d3c-bfb6-4a2f-9dc2-b447058a460a)

Nessa pipeline, os dados são carregados e divididos em dois conjuntos: um para o treinamento do modelo de regressão linear e outro para a comparação dos resultados obtidos.

Após rodar o modelo, obtemos os resultados do Score, onde encontramos a previsão de quantos picolés serão vendidos no dia 


![2025-03-18_21-27](https://github.com/user-attachments/assets/d1339ef5-74cf-407e-b239-cabcd95f317c)
