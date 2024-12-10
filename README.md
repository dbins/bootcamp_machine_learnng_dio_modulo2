# Treinamento de Redes Neurais com Transfer Learning

![DIO(modulo2.jpg)

No desafio do segundo módulo do Bootcampo BairesDev - Machine Learning Practitioner promovido pela DIO chamado "Treinamento de Redes Neurais com Transfer Learning" foi aplicado o método de Transfer Learning em uma rede de Deep Learning na linguagem Python no ambiente COLAB.  

Bibliotecas utilizadas:

Keras
Numpy
Matplotlib

Foram feitas duas versões do código. Uma treinando uma rede neural do zero (arquivo modulo2_final_2) e outra treinando uma rede neural fazendo transfer learning (arquivo modulo2_final).

Ambos os arquivos tomaram como base um modelo de notebook fornecido pelo curso (arquivo transfer-learning) 

## VGG16 

Para o transfer learning foi utilizada a rede VGG16. Este rede é um tipo de CNN (Rede Neural Convolucional) considerada um dos melhores modelos de visão computacional. Os criadores deste modelo avaliaram as redes e aumentaram a profundidade utilizando uma arquitetura com filtros de convolução muito pequenos (3 × 3), o que apresentou uma melhoria significativa nas configurações da técnica anterior. Eles aumentaram a profundidade para 16–19 camadas de peso, tornando-a aproximadamente 138 parâmetros treináveis.

VGG16 é um algoritmo de detecção e classificação de objetos capaz de classificar 1.000 imagens de 1.000 categorias diferentes com 92,7% de precisão. É um dos algoritmos populares para classificação de imagens e é fácil de usar com aprendizagem por transferência.

## Dataset

O dataset utilizado para o treinamento consiste em imagens de 2 tipos de foguetes. Os testes após o treinamento conseguiram identificar o que era um foguete em relação a outros objetos. Mas apesar do sucesso, os testes não conseguiram distinguir corretamente qual o modelo do foguete.
