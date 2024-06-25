# Desafio de Projeto: Sistema de Recomendação por Imagens Digitais

Este projeto visa desenvolver um sistema de recomendação de categorias de produtos com base em imagens digitais. Utilizando técnicas de aprendizado de máquina e processamento de imagens, o sistema é capaz de classificar diferentes categorias de produtos e gerar recomendações com base em imagens de entrada. A linguagem de programação utilizada será Python, aproveitando bibliotecas populares para tarefas de visão computacional e aprendizado de máquina.

# Tecnologias Utilizadas


1.**Linguagem de Programação**
  *  **Python**: Linguagem principal utilizada para desenvolvimento do projeto.

2. **Bibliotecas e Frameworks de Visão Computacional e Aprendizado de Máquina**
  *  **TensorFlow**: Framework de aprendizado de máquina e redes neurais.
  * **Keras**: API de alto nível para construção e treinamento de modelos de aprendizado de máquina, integrada ao TensorFlow.
  * **OpenCV**: Biblioteca de visão computacional utilizada para processamento de imagens.
  * **scikit-learn**: Biblioteca de aprendizado de máquina utilizada para a implementação do K-Nearest Neighbors (KNN).

3. **Manipulação e Visualização de Dados**
  * **NumPy**: Biblioteca para manipulação de arrays e operações matemáticas.
  * **Pandas**: Biblioteca para manipulação e análise de dados estruturados.
  * **Matplotlib**: Biblioteca para visualização de dados.

4.**Ferramentas de Pré-processamento e Aumentação de Dados**
  * **Google Colab**: Ambiente de desenvolvimento colaborativo para a execução de notebooks Jupyter. O Colab permite o upload de arquivos e a execução de código interativo.

5. **Desenvolvimento da Interface de Usuário**
  * Google Colab

6. **Manipulação de Imagens**
  * **Pillow**: Biblioteca para processamento de imagens, utilizada para abrir e manipular arquivos de imagem.

7. **Armazenamento de Dados**
  * **Google Drive**

# **Etapas do Projeto**

1. **Coleta e Armazenamento de Dados**

  * **Coleta de Imagens**: Obter um conjunto de dados de imagens de produtos de fontes como Kaggle.
  * **Armazenamento no Google Drive**: Organizar e armazenar as imagens no Google Drive para fácil acesso e gerenciamento.

2. **Configuração do Google Colab**
  * **Montar Google Drive**: Conectar o Google Colab ao Google Drive para acessar os dados armazenados.
  * **Upload e Pré-processamento de Imagens**: Carregar imagens do Google Drive, redimensionar, normalizar e, se necessário, aplicar aumentação de dados.

3. **Análise Exploratória de Dados (EDA)**

  * Visualização das imagens e distribuição das categorias.
  * Estatísticas básicas para entender a composição do conjunto de dados.

4. **Construção do Modelo de Classificação de Imagens**

  * **Arquitetura do Modelo**: Seleção de um modelo adequado para classificação de imagens (e.g., CNNs como ResNet, VGG, ou modelos mais leves como MobileNet).
  * **Treinamento do Modelo**: Divisão do conjunto de dados em treinamento e teste, configuração dos hiperparâmetros e treinamento do modelo.
  * **Avaliação do Modelo**: Métricas de desempenho como acurácia, precisão, recall e F1-score.

5. **Sistema de Recomendação**

  * **Estratégia de Recomendação**: Desenvolver um sistema que recomenda categorias de produtos baseados na similaridade das imagens.
  * **Implementação**: Uso de técnicas como K-Nearest Neighbors (KNN) para encontrar imagens similares no espaço das características aprendidas pelo modelo de classificação.

6. **Interface de Usuário**

O ideal seria a criação de uma interface simples (pode ser uma aplicação web usando Flask ou Django) onde o usuário pode fazer upload de uma imagem e receber recomendações de categorias. Porém camos usar a biblioteca de upload do Google Colab

7. **Validação e Testes**

  * Testar a precisão do sistema de recomendação com imagens novas.
  * Coletar feedback e ajustar o modelo conforme necessário.    
