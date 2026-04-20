# Machine-learning-and-AI
## Transfer Learning em Deep Learning com Python

Este projeto foi desenvolvido como objetivo de aplicar a técnica de **Transfer Learning** utilizando uma rede neural pré-treinada para classificar imagens.

## Objetivo
Demonstrar a eficácia do reaproveitamento de pesos de modelos treinados em grandes datasets (ImageNet) para tarefas específicas, reduzindo tempo de processamento e volume de dados necessários.

## Tecnologias Utilizadas
- Python 3
- TensorFlow / Keras
- Google Colab (Ambiente de desenvolvimento)
- Matplotlib (Visualização de resultados)

## Estrutura do Modelo
- **Modelo Base:** MobileNetV2 (pré-treinado no ImageNet)
- **Camadas Adicionais:** GlobalAveragePooling2D e Dense (Sigmoid)
- **Técnica:** Congelamento de camadas base seguido de Fine-Tuning.

## Resultados
Neste projeto eu utilizei o método de transfer learning, utilizando um treinamento de 5 épocas para ter maior eficiência, chegando a uma acurácia de 98.07%. Coclui-se que a aplicação de Transfer Learning foi fundamental para obter uma alta performance em um tempo computacional reduzido. Com apenas 5 épocas de treinamento, o modelo atingiu uma acurácia de 98,07%, o que evidencia a eficiência de reaproveitar pesos pré-treinados em grandes bases de dados, como o ImageNet.

A alta taxa de acerto sugere que os recursos extraídos pelo modelo base (como MobileNetV2 ou ResNet) são altamente transferíveis para o problema de classificação binária. Para projetos futuros, esse método se mostra ideal por permitir o desenvolvimento de sistemas robustos mesmo quando não se dispõe de um dataset massivo ou de hardware de alto desempenho para treinamento do zero." 

## Como rodar o projeto
Para quem quiser rodar o projeto e implementar outro tipo de dataset:
1. Abra o arquivo `.ipynb` no Google Colab.
2. Ative a GPU em 'Ambiente de Execução'.
3. Execute todas as células.
