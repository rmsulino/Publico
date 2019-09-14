## a. Como foi a definição da sua estratégia de modelagem?




## b. Como foi definida a função de custo utilizada?

A função de custo foi definida por meio da diferença no valor predito na hipótese compadara ao valor alvo. Essa diferença é elevada ao quadrado  e calculada para cada saída, em seguida somada e dividida por 2, de modo a fornecer o erro médio ao quadrado.

$$ J(\theta) = \frac{1}{2}\sum_{i=0}^{m}(h_{\theta}(x^{(i)})-y^{(i)})^{2}



## c. Qual foi o critério utilizado na seleção do modelo final?

O critério utilizado foi a acurácia dos modelos. Testei vários modelos, obtendo como melhor acurácia Random Forest e Decision Tree. 


## d. Qual foi o critério utilizado para validação do modelo? Por que escolheu utilizar este método?

O critério utilizado foi a acurácia do modelo em predizer a qualidade do vinho. Escolhi este método por atender ao objetivo da análise, que é predizer com eficiência a qualidade do vinho.


## e. Quais evidências você possui de que seu modelo é suficientemente bom?

Ao avaliar o modelo escolhido (Random Forest), o mesmo apresentou uma acurácia de 86% para estimar a qualidade do vinho.
