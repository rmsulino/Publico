# Análise da qualidade do vinho

## a. Como foi a definição da sua estratégia de modelagem?

Considerando a característica dos dados e da análise (uma variável "quality" influenciada por diversas outras variáveis), iniciei identificando a correlação entre as variáveis e a qualidade do vinho. Ao identificar a variável "alcohol" como de maior influência, utilizei a Regressão Linear para analisar essa variável específica. Posteriormente testei diversos modelos de machine learning para uma análise multivariada, pois outras variáveis além de "alcohol" influenciam na qualidade do vinho. Foi verificada a acurácia de cada modelo, de modo a oferecer parâmetros para a escolha do modelo final. O modelo Random Forest se mostrou o melhor para os dados analisados.


## b. Como foi definida a função de custo utilizada?

A função de custo foi definida por meio da diferença no valor predito na hipótese compadara ao valor alvo. Essa diferença é elevada ao quadrado  e calculada para cada saída, em seguida somada e dividida por 2, de modo a fornecer o erro médio ao quadrado.

![equation](https://latex.codecogs.com/gif.latex?J%28%5Ctheta%29%20%3D%20%5Cfrac%7B1%7D%7B2%7D%5Csum_%7Bi%3D0%7D%5E%7Bm%7D%28h_%7B%5Ctheta%7D%28x%5E%7B%28i%29%7D%29-y%5E%7B%28i%29%7D%29%5E%7B2%7D)



## c. Qual foi o critério utilizado na seleção do modelo final?

O critério utilizado foi a acurácia dos modelos. Testei vários modelos, obtendo como melhor acurácia Random Forest e Decision Tree. 


## d. Qual foi o critério utilizado para validação do modelo? Por que escolheu utilizar este método?

O critério utilizado foi a acurácia do modelo em predizer a qualidade do vinho. Escolhi este método por atender ao objetivo da análise, que é predizer com eficiência a qualidade do vinho.


## e. Quais evidências você possui de que seu modelo é suficientemente bom?

Ao avaliar o modelo escolhido (Random Forest), o mesmo apresentou uma acurácia de 86% para estimar a qualidade do vinho.
