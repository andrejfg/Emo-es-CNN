# Emocoes-CNN

Modelo de reconhecimento de emoções

O modelo foi treinado com a base de imagens FER-2013 do Kaggle (https://www.kaggle.com/msambare/fer2013).

Esta base de imagens é composta por imagens preto e branco de tamanho (48x48) pixels. Já é separada entre treino e teste e possui 6+1 emoções sendo elas:

*    Raiva
*    Nojo
*    Medo
*    Alegria
*    Tristeza
*    Surpresa
*    Neutro

O modelo foi montado a partir de uma variação da arquitetura VGG-16, apenas com adições de camadas de Batch Normalization e Dropout para afim de evitar overfitting cedo durante o treino.
