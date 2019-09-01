# DogsCatsTraining

Esse foi um processo de treinamento de uma Rede Neural Convolucional simples com a finalidade de prática.

Nesse processo foi utilizado:
- Google Colab
- TensorFlow
- Keras

A arquitetura utilizada foi a mesma do exemplo no livro [Deep Learning Book - Cap 47](http://deeplearningbook.com.br/reconhecimento-de-imagens-com-redes-neurais-convolucionais-em-python-parte-4/), a diferença básica foi a utilização do próprio Google Colab ao invés da minha máquina local com jupyter notebook (devido a questões de processamento) e os arquivos nesse repositório ao invés de utilizar o [dataset do Kaggle](https://www.kaggle.com/c/dogs-vs-cats/data) de cães e gatos, que também é uma ótima opção com 25000 imagens de cães e 25000 imagens de gatos.

Nesse dataset temos os seguintes arquivos:
- 7000 imagens de gatos para treino
- 7000 imagens de cachorros para treino
- 20 imagens para teste

O modelo foi treinado de forma simples e com apenas 5 épocas.
Como no próprio capitulo do Deep Learning Book, deixo aqui algumas sugestões de melhorias adicionais para o modelo:
-    Aumentar o número de épocas para 25 para uma aprendizagem mais profunda.
-    Além disso, aumentar o redimensionamento da imagem de 64x64 para 256x256 deve levar a melhores resultados devido à resolução mais alta.
-    Aumentar o tamanho do lote de 32 para 64 também pode levar a melhores resultados.
-    Usar imagens sintéticas rotacionando a imagem principal, técnica conhecida como Dataset Augmentation.
-    Alterar a arquitetura da rede incluindo mais uma camada convolucional.
-    Avaliar outras métricas do modelo e ajustar os hiperparâmetros de acordo.
-    Experimentar outros algoritmos de otimização.
