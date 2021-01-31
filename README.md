# Classificacao básica REDE_NEURAL

# <font color='red'>Treinando a nossa primeira rede neural: classificação básica</font>

**Índice:**
* Importe a base de Dados Fashion MNIST
* Exploreos Dados
* Pré-processe os Dados
* Construindo o modelo
  * Montar as camadas
  * Compile o modelo
* Treine o modelo
* Avalie a acurácia
* Faça predições


Este tutorial treina um modelo de rede neural para **classificação de imagens de roupas**, como tênis e camisetas. Tudo bem se você não entender todos os detalhes; 
este é uma visão geral de um programa do ``TensorFlow`` com detalhes explicados enquanto progredimos.
O guia usa [tf.keras](https://www.tensorflow.org/guide/keras?hl=pt_br), uma API alto-nível para construir e treinar modelos no TensorFlow.

Esse tutorial usa a base de dados **Fashion MNIST** que contém $70\,000$ imagens em tons de cinza em $10$ categorias. As imagens mostram artigos individuais de 
roupas com baixa resolução ($28$ por $28$ pixels).

**Usaremos $60\,000$ imagens para treinar nossa rede e $10\,000$ imagens para avaliar quão precisamente nossa rede aprendeu a classificar as imagens**. 
Você pode acessar a **Fashion MNIST directly** diretamente do TensorFlow. Importe e carregue a base Fashion MNIST diretamente do TensorFlow.


Thanks God!

