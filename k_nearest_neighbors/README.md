[knn]:./docs/knn.png "K-Nearest Neighbors"

# K Nearest Neighbors

## Definição

O algoritmo de [_K-Nearest Neighbors_ (KNN)](k_nearest_neighbors.ipynb) pode ser classificado com um tipo de algoritmo supervisiona de _machine learning_. É um algoritmo relativamente fácil de implementar na sua forma mais básica e, ainda sim, consegue realizar tarefas de classificação complexa.

É considerado um algoritmo "preguiçoso", já que nao tem uma fase especializado no treinamento. Basicamente, é um algoritmo de classificação baseado em vizinhança que utiliza a distância euclidiana para classificar um novo ponto.

O KNN assume que não uma correlação implicita entre os dados, o que pode ser considerado bastante útil pois há uma parcela grande de dados que não são correlacionados.

O seu funcionamento é um dos mais simples de todos os algoritmos supervisionados. Primeiro ele calcula a distância entre um novo ponto e todos os outros pontos dos _dataset_ de treinamento. A distância pode ser calculado com qualquer técnica, sendo as mais comuns a distância euclidiana e distância de manhattan. Depois, seleciona os K pontos mais próximos, sendo que  K pode ser qualquer valor inteiro. Por fim, atribui uma classe ao novo ponto, baseado na maioria dos K pontos atribuídos ao mesmo.

![K Nearest Neighbors][knn]

## Vantagens
A seguir temos algumas das vantages de se usar este algoritmo:

- O KNN é um algoritmo de classificação que é bastante simples de implementar.

- Como é classificado como um algoritmo "preguicoso" não requer nenhum treinamento antes de se fazer as predições reis, o que o KNN um algoritmo muito mais rápido para se usar do que aqueles que requerem treinamento anterior.

- como não requer treinamento anterior, novos dados podem adicionados ao dataset de treinamento sem que nenhum alteração seja necessária.

- Há apenas dois parametros a serem definidos, o K e a função de cálculo de distância.

## Desvantagens
A seguir temos algumas das desvantagens de se usar este algoritmo:

- O algoritmo KNN não funciona bem com dados de alta dimensionalidade, porque com o aumento da dimensionalidade se torna cada vez mais difícil de calcular a distância em cada dimensão.

- Tem um alto custo de predição para _datasets_ grandes. Isso ocorre porque em _datasets_ maiores o custo de calcular a distância entre cada novo ponto e todos os outros se torna muito alto.

- Por fim, KNN não é indicado para trabalhar com dados categóricos já que não se é possével calcular a distância entre as categorias.


## Abordagem inndicadas

Como o KNN não faz de pré-treinos, o mesmo é indicado para casos onde:

- Não se há grandes volumes de dados;

- Se tenha bom conhecimento do problema e dos dados, já que o mesmo não considera correlação entre os dados;

- Para dados onde se possa calcular a distância entre os pontos existentes no dataset de treinamento e novos a serem inseridos.

## Referencias

- [Stack Abuse](https://stackabuse.com/k-nearest-neighbors-algorithm-in-python-and-scikit-learn/)


- [Towards Data Science](https://towardsdatascience.com/knn-algorithm-what-when-why-how-41405c16c36f)