# MLP Multilayer Perceptron

A porta de entrada para redes neurais. O MLP é uma rede neural artificial com pelo menos uma camada oculta entre a entrada e a saída, cada neurônio recebe os valores da camada anterior, aplica uma função de ativação e passa o resultado pra frente. É o conceito base de tudo que existe em deep learning hoje.

Exercício focado em entender como a rede aprende ajustando os pesos via backpropagation.

# No notebook


Pré-processamento e normalização dos dados
Definição da arquitetura com MLPClassifier do scikit-learn (camadas, neurônios, função de ativação)
Treinamento e acompanhamento da curva de loss ao longo das épocas
Avaliação com métricas de classificação e comparação com modelos anteriores
Experimentos com diferentes configurações de hidden_layer_sizes e activation



Durante o treino, a rede faz uma passagem pra frente calculando a predição, mede o erro com uma função de loss, e então propaga esse erro de volta camada por camada (backpropagation) ajustando os pesos via gradiente descendente. Esse ciclo se repete por várias épocas até o erro convergir, ou até overfittar, o que também acontece bastante.
