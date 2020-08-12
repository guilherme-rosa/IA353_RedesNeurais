# IA353 - Redes Neurais (1S2020)

- Este repositório contém os Exercícios de Fixação de Conceitos - EFC - da disciplina de pós-graduação de Redes Neurais ministrada pelo professor Fernando von Zuben.
- O material do curso pode ser acessado em [IA353 - Redes Neurais](http://www.dca.fee.unicamp.br/~vonzuben/courses/ia353.html).
- As atividades computacionais são implementados em Jupyter notebooks com a linguagem Python.

### Tópicos:
#### EFC1
- **Questão 1 - Síntese de modelos lineares para classificação de padrões:**
    - Modelo: regressão linear com regularizão do tipo Ridge Regression.

- **Questão 2 - Síntese de modelos não-lineares para classificação de padrões, mas lineares nos parâmetros ajustáveis:**
    - Modelo: Extreme Learning Machine (ELM) com regularização do tipo Ridge Regression.

- **Base de dados utilizada nas atividades: MNIST.**
#### EFC2
- **Questão 3 - Síntese de um classificador de padrões com Redes Neurais MLP.**
    - Investigação do impacto de variações nos seguintes hiperparâmetros: número de camadas intermediárias, tipo de função de ativação, tipo de algoritmo de otimização e taxa de Dropout.
- **Questão 4 - Síntese de um classificador de padrões com Redes Convolucionais.**
    - Investigação do impacto de variações nos seguintes hiperparâmetros: número de camadas intermediárias, dimensão do filtro convolutivo, número de filtros, operação de pooling.
- **Base de dados utilizada nas atividades: MNIST.**

#### EFC3
- **Questão 5 - Síntese e análise de autoencoders:**
    - Bases de dados: MNIST e CIFAR10.
    - Implementação de Deep Autoencoders e Convolutional Autoencoders.

- **Questão 6 - Estudo de séries temporais e síntese de preditores linear e não-linear:**
    - Bases de dados: NYSE: The New York Stock Exchange, Série temporal artificial estacionária e não-linear e Série de temperatura mínima diária referente à cidade de Melbourne, Austrália, no período de 1981 a 1990.
    - Implementação de preditor linear.
    - Implementação de preditores não-linear: fully-connected, simpleRNN, LSTM GRU e convolucional (conv1D).
    
- **Questão 7 - Interpretabilidade de redes neurais treinadas:**
    - Base de dados: MNIST.
    - Uso das bibliotecas innvestigate e keras-vis.

#### EFC4
- **Questão 8 - Aprendizado por reforço para definição de percursos em labirintos:**
    - Algoritmo utilizado: Deep Q-Learning.

- **Questão 9 - Síntese de redes GANs (Generative Adversarial Networks):**
    - Bases de dados: MNIST e CIFAR10.

- **Questão 10 - Processamento de linguagem natural - Word Embedding:**
    - Base de dados: OpinRank Data – Reviews From TripAdvisor & Edmunds.
    - Implementação de word2vec com a biblioteca GENSIM.
