# 1. Nome do Projeto
Ensaio de Machine Learning
# 2. Problema de Negócio
## 2.1 Descrição
A empresa Data Money acredita que a expertise no treinamento e ajuste fino dos algoritmos, feito
pelos Cientistas de Dados da empresa, é a principal motivo dos ótimos resultados que as
consultorias vem entregando aos seus clientes.
## 2.2 Objetivo
O objetivo desse projeto será realizar ensaios com algoritmos de Classificação, Regressão e
Clusterização, para estudar a mudança do comportamento da performance, a medida que os
valores dos principais parâmetros de controle de overfitting e underfitting mudam.
# 3. Planejamento da solução
## 3.1 Produto final
O produto final será 7 tabelas mostrando a performance dos algoritmos, avaliados usando múltiplas
métricas, para 3 conjuntos de dados diferentes: Treinamento, validação e teste.
## 3.2 Algoritmos ensaiados
### Classificação:
Algoritmos: KNN, Decision Tree, Random Forest e Logistic Regression 

Métricas de performance: Accuracy, Precision, Recall e F1-Score
### Regressão:
Algoritmos: Linear Regression, Decision Tree Regressor, Random Forest Regressor, Polinomial
Regression, Linear Regression Lasso, Linear Regression Ridge, Linear Regression Elastic Net,
Polinomial Regression Lasso, Polinomial Regression Ridge e Polinomial Regression Elastic Net

Métricas de performance: R2, MSE, RMSE, MAE e MAPE

### Agrupamento:
Algoritmos: K-Means e Affinity Propagation

Métricas de performance: Silhouette Score
##3.3 Ferramentas utilizadas:
 Python 3.8 e Scikit-learn
# 4. Desenvolvimento
## 4.1 Estratégia da solução
Para o objetivo de ensaiar os algoritmos de Machine Learning, eu vou escrever os códigos
utilizando a linguagem Python, para treinar cada um dos algoritmos e vou variar seus principais
parâmetros de ajuste de overfitting e observar a métrica final.
O conjunto de valores que fizerem os algoritmos alcançarem a melhor performance, serão aqueles
escolhidos para o treinamento final do algoritmo.
## 4.2 O passo a passo
Passo 1: Divisão dos dados em treino, teste e validação.
Passo 2: Treinamento dos algoritmos com os dados de treinamento, utilizando os parâmetros
“default”.
Passo 3: Medir a performance dos algoritmos treinados com o parâmetro default, utilizando o
conjunto de dados de treinamento.
Passo 4: Medir a performance dos algoritmos treinados com o parâmetro “default”, utilizando o
conjunto de dados de validação.
Passo 5: Alternar os valores dos principais parâmetros que controlam o overfitting do algoritmo até
encontrar o conjunto de parâmetros apresente a melhor performance dos algoritmos.
Passo 6: Unir os dados de treinamento e validação
Passo 7: Retreinar o algoritmo com a união dos dados de treinamento e validação, utilizando os
melhores valores para os parâmetros de controle do algoritmo.
Passo 8: Medir a performance dos algoritmos treinados com os melhores parâmetro, utilizando o
conjunto de dados de teste.
Passo 9: Avaliar os ensaios e anotar os 3 principais Insights que se destacaram.
# 5. Os top 3 Insights
## 5.1 Insight Top 1
Os algoritmos baseado em árvores possuem uma performance melhores em todas as métricas,
quando aplicados sobre os dados de teste, no ensaio de Classificação
## 5.2 Insight Top 2
A performance dos algoritmos de classificação sobre os dados de validação ficou bem próxima da
performance sobre os dados de teste.
## 5.3 Insight Top 3
Todos os algoritmo de regressão não apresentaram boas métricas de performance, o que mostra
uma necessidade de uma seleção de atributos e uma preparação melhor das variáveis
independentes do conjunto de dados.
# 6. Resultados

#Ensaio de Classificação:
## 6.1 Sobre os dados de treinamento
![image](https://github.com/user-attachments/assets/565f2654-87f6-430c-8b0d-a4ba97ed36a9)

## 6.2 Sobre os dados de validação
![image](https://github.com/user-attachments/assets/eb02e667-c5a6-434e-9892-07985d6816fa)

## 6.3 Sobre os dados de teste

![image](https://github.com/user-attachments/assets/f09e85c2-0762-4cce-8ac5-09217dc631ae)

# Ensaio de Regressão:

## 6.4 Sobre os dados de treinamento
![image](https://github.com/user-attachments/assets/9438d824-1d18-4e2e-9ba7-019711a71482)

## 6.5 Sobre os dados de validação
![image](https://github.com/user-attachments/assets/98123e15-6f23-41f6-87e7-e04b366af64f)

## 6.6 Sobre os dados de teste
![image](https://github.com/user-attachments/assets/38ec0b22-28ab-4e65-bf2b-87fcbe415d12)


# Ensaio de Clusterização:

## 6.7 Sobre os dados de treinamento
![image](https://github.com/user-attachments/assets/561d8642-5c97-47d4-939b-5e9823ee5ef1)

# 7. Conclusões

Nesse ensaio de Machine Learning, consegui adquirir experiência e entender melhor sobre os limites
dos algoritmos entre os estados de underffiting e overfitting

Algoritmos baseados em árvores são sensível quanto a profundidade do crescimento e do número de
árvores na floresta, fazendo com que a escolha correta dos valores desses parâmetros impeçam os
algoritmos de entrar no estado de overfitting.

Os algoritmos de regressão, por outro lado, são sensíveis ao grau do polinômio. Esse parâmetro
controla o limite entre o estado de underfitting e overfitting desses algoritmos.
Esse ensaio de Machine Learning foi muito importante para aprofundar o entendimento sobre o
funcionamento de diversos algoritmos de classificação, regressão e clusterização e quais os principais
parâmetros de controle entre os estados de underfitting e overfitting.

# 8. Próximos passos
 
Como próximos passos desse ensaio, pretendo ensaiar novos algoritmos de Machine Learning e usar
diferentes conjuntos de dados para aumentar o conhecimento sobre os algoritmos e quais cenários são
mais favoráveis para o aumento da performance dos mesmos.





