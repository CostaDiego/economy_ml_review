[SVM Hyperplane]: ./docs/svm_hyperplan.png "SVM Hyperplanes"
[SVM Non Linear]: ./docs/svm_non_linear_data.png "SVM Handling Non-Linear Data"
# [_Support Vector Machines_](./support_vector_machines.ipynb)

## Definição

[_Support Vector Machines_](./support_vector_machines.ipynb) (SVM) é um algoritmo que oferece alta acurácia para classificação de dados quando comparado com outros métodos, tais quais regressão logística, árvores de decisão e etc. Normalmente é considerado um algoritmo de classificação, mas pode ser usando tanto para classificação quanto para problemas regressão.

A sua idéia base se baseia em conceitos relativamente simples. O classificador separa os pontos de dados usando um hiperplano, que é escolhido levando em conta qual tem a maior marge de distância grupos de dados.

Durante seu processo de treinamento, gera-se multiplos hiperplanos para separar as classes. Aqueles com a maior marge de distância são escolhidos como os melhores, baseado nos vetores suportes que são os mais proximos de cada hiperplano.

![SVM Hyperplane]

Quando há dados não lineares, que são aqueles que não podem ser separados usando hiperplanos lineares o _kernel_ aplica uma transformação para os pontos de dados os levando para um espaço de dimenionalidade aumentada.

![SVM Non Linear]

## Vantagens

A seguir, pode-se ver algumas das vantagens de se usar SVM:

- Relativamente boa acurácia (levando em conta os itens a seguir);

- Menor tempo de predição, quando comparado com o algoritmo Naive Bayes;

- Menor uso de memória, pois usa um subconjunto dos dados de treinamento na fase de decisão;

- Trabalho bem com conjunto de dados com alta dimenionalidade, conseguindo estabelecer uma boa margem de separação.

## Desvantagens

A seguir, pode-se observar algumas das desvantagens de se usar SVM:

- Não indicada para grandes conjuntos de dados por causa do seu elevado tempo de treinamento;

- Demora mais tempo para ser treinado quando comparado com algoritmos como Naives Bayes;

- Não performa bem em conjunto de dados cujas classes se superpoem;

- É sensível ao tipo de kernel usado (linear, polinomial, de base radial).

## Aplicações

A seguir pode-se observar alguns exemplos de aplicações de SVM, todavia sua aplicação não se resume a apena esta lista:

- Detecção de rostos;

- Classificação de email;

- Classificação de páginas web;

- Classificação de genes;

- Reconhecimento de escrita.

## Referências

- [Datacamp](https://www.datacamp.com/community/tutorials/svm-classification-scikit-learn-python)