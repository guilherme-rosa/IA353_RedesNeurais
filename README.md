# IA353 - Redes Neurais (1S2020)

- Este repositório contém os Exercícios de Fixação de Conceitos - EFC - da disciplina de pós-graduação de Redes Neurais ministrada pelo professor Fernando von Zuben.
- O material do curso pode ser acessado em [IA353 - Redes Neurais](http://www.dca.fee.unicamp.br/~vonzuben/courses/ia353.html).
- As atividades computacionais são implementados em Jupyter notebooks com a linguagem Python.
- Os modelos de redes neurais são implementados com as bibliotecas Tensorflow e Keras. 

### Exercícios:

- **Questão 1 (EFC1) - Síntese de modelos lineares para classificação de padrões:**
    - Modelo: regressão linear com regularizão do tipo Ridge Regression.
- **Questão 2 (EFC1) - Síntese de modelos não-lineares para classificação de padrões, mas lineares nos parâmetros ajustáveis:**
    - Modelo: Extreme Learning Machine (ELM) com regularização do tipo Ridge Regression.
- **Questão 3 (EFC2)- Síntese de um classificador de padrões com Redes Neurais MLP.**
    - Investigação do impacto de variações nos seguintes hiperparâmetros: número de camadas intermediárias, tipo de função de ativação, tipo de algoritmo de otimização e taxa de dropout.
- **Questão 4 (EFC2) - Síntese de um classificador de padrões com Redes Convolucionais.**
    - Investigação do impacto de variações nos seguintes hiperparâmetros: número de camadas intermediárias, dimensão dos filtros convolutivos, número de filtros, operação de pooling.
- **Questão 5 (EFC3) - Síntese e análise de autoencoders:**
    - Implementação de deep autoencoders e convolutional autoencoders.
- **Questão 6 (EFC3) - Estudo de séries temporais e síntese de preditores linear e não-linear:**
    - Modelos de preditores não-lineares: fully-connected, simpleRNN, LSTM GRU e convolucional (conv1D).
- **Questão 7 (EFC3) - Interpretabilidade de redes neurais treinadas:**
    - Estudo das técnicas de interpretabilidade baseadas em gradiente e LRP com a biblioteca innvestigate e da técnica activation maximization com a biblioteca keras-vis.
- **Questão 8 (EFC4) - Aprendizado por reforço para definição de percursos em labirintos:**
    - Algoritmo de treinamento: Deep Q-Learning.
- **Questão 9 (EFC4) - Síntese de redes GANs (Generative Adversarial Networks):**
    - Treinamento de rede generativa para síntese de dígitos manuscritos (base MNIST) e de imagens de carros (base CIFAR10).
- **Questão 10 (EFC4) - Processamento de linguagem natural - Word Embedding:**
    - Implementação de word2vec com a biblioteca GENSIM e explicação das técnicas CBOW, Skip-Gram e t-SNE.

- **Base de dados utilizadas nas atividades:**
    - EFC1: Imagens de dígitos manuscritos do dataset MNIST.
    - EFC2: Imagens de dígitos manuscritos do dataset MNIST.
    - EFC3: MNIST, CIFAR10, The New York Stock Exchange, série temporal artificial estacionária e não-linear e Série de temperaturas mínimas diárias referente à cidade de Melbourne, Austrália, no período de 1981 a 1990.
    - EFC4: MNIST, CIFAR10 e OpinRank Data – Reviews From TripAdvisor & Edmunds.

