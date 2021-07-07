## Modelo Classificação de Imagens de Sementes 

**TensorFlow Lite Model Maker vs Modelo sem dilatamento e com strides > 1** 

*Comparação entre um modelo a partir da API Maker e outro montado por mim* 

- O modelo com Model Maker faz aproveitamento dos pesos da parte de extração de características do modelo EfficientNet-B0.
- Eu testo o efeito de aumentar os strides quanto ao tempo de treinamento e nível de acurácia. Aproveito e testo também tamanhos de reigões receptivas diferentes.
