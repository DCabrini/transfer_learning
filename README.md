# transfer_learning
Classificação de imagens de gatos e cachorros utilizando Transfer Learning.

## Classificador de Gatos e Cães com Transfer Learning

### Descrição
Este projeto tem como objetivo classificar imagens de gatos e cães utilizando a técnica de *transfer learning*. Um modelo pré-treinado na base de dados ImageNet foi adaptado para a tarefa de classificação de imagens de animais domésticos.

### Dados
A base de dados utilizada foi a popular *Cats vs Dogs*. As imagens foram pré-processadas para adequar-se ao modelo.

### Modelo
* **Base:** ImageNet
* **Pré-treinamento:** O modelo base foi treinado em um vasto conjunto de imagens, aprendendo características visuais genéricas.
* **Fine-tuning:** As últimas camadas do modelo foram re-treinadas com os dados de gatos e cães para adaptar o modelo à nova tarefa.

