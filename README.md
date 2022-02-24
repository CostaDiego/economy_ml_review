# Revisão de Técnicas de _Machine Learning_ Aplicáveis no Contexto de Econômia

Este repositório é uma revisão técnica a respeito de técnicas de _Machine Learning_ cuja aplicação pode ser vantajosa no contexto do processamento de dados econômicos. O objetivo é ajudar a entender como cada técnica pode ser aplicada, quais a classes de problemas elas se encaixam melhor e, por consequência, quais não são viáveis à determinados casos.

A revisão foi dividada em duas partes: A primeira compreende as **Técnicas Supervisionadas**; Já a segunda compreende as **Técnicas Não-Supervisionadas**. A seguir há um breve resumo de cada técnica mas, ao clicar no link, uma pasta com mais detalhes será aberta. Estas pastas podem conter:

- Descrição completa da técnica;
- Situações onde seu uso pode ser útil;
- Situações onde seu uso pode não indicado;
- Casos de uso; e,
- Um exemplo de código com a implementação em notebook Jupyter;

## Aprendizado Supervisionado

### [Modelos de Regressão](./modelos_regressao/)

A [Regressão Linear](./modelos_regressao/) é um modelo de análise que pode ser usado quando se modela a relação linear entre uma variável de desfecho contínua e variáveis preditoras (uma ou mais) que podem ser contínuas ou categóricas.

A principal diferença entre a Regressão Linear Múltipla e a Simples, é que na simples só usamos uma variável preditora, enquanto na múltipla usamos mais de uma variável preditora.

### [_K-Nearest Neighbors_](./k_nearest_neighbors/)

O [_K-Nearest Neighbors_](./k_nearest_neighbors/) (KNN) é um algoritmo de classificação baseado em vizinhança que utiliza a distância euclidiana para classificar um novo ponto. É um modelo de análise que pode ser usado quando se deseja estimar a distância entre um conjunto de pontos e um ponto de referência.

### [_Naive Bayes Classifiers_](./naive_bayes_classifiers/)

O algoritmo de classificação [*Naive Bayes*](./naives_bayes_classifiers/) é baseado no Teorema de Bayes. É um dos mais simples modelos de aprendizado supervisionado, porém é rápido, acurado e confiável. Em grandes datasets, a técnica tem alta acurácia e velocidade de processamento.

### Ávores de Decisão e _Ensembles_ de Árvores de Decisão

### [_Support Vector Machines_](./support_vector_machines/)

[_Support Vector Machines_](./support_vector_machines/) (SVM) é um algoritmo que oferece alta acurácia para classificação de dados quando comparado com outros métodos, tais quais regressão logística, árvores de decisão e etc. Normalmente é considerado um algoritmo de classificação, mas pode ser usando tanto para classificação quanto para problemas regressão.

### Redes Neurais

## Aprendizado Não-Supervisionado

### [_Principal Component Analisys_](./PCA)
[_Principal Component Analysis_](./PCA) (PCA) é um algoritmo que permite a redução da dimensionaliade de uma amostra de dados, de modo a condensar as variáveis com a menor perca possível de informação.

### [_AutoEncoder_](./AutoEncoder)
[_Autoencoder_](./AutoEncoder) é uma técnica de aprendizado não supervisionado que permite com que dados sejam compactados e descompactados atráves de redes neurais.

### _K-Means Clustering_

### _Agglomerative Clustering_

### _DBSCAN_
