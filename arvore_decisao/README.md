[arvore_decisao]: ./docs/decision_tree.jpeg "Árvore de decisão"
# [Arvore de Decisão](./arvore_decisao.ipynb)

## Definição

Uma [árvore de decisão]((./arvore_decisao.ipynb)) é um algoritmo com estrutura parecida com um fluxograma do tipo que àrvore, onde os nós internos representam as características; os galhos as regras de decisão; e as folhas as classes.

O nó no topo da árvore é conhecido como nó raiz e, a partir dele, a árvore aprende como particionar os dados com base nos valores de cada característica. Essa subdivisão ocorre de maneira recursiva e cada subárvore  repete esse processo até que se alcançe um bom nível de acurácia.

![alt text][arvore_decisao]

A sua visualização em modo de diagrama de fluxo imita a forma com que os humanos pensam , por isso que são fáceis de entender e interpretar. Árvores de decisão são conhecida por serem algoritmos "caixas brancas", pois é possível visualizar seu funcionamento interno e sua cadeia lógica de decisão. Tal característica não pode ser obeservado em algoritmos do tipo "caixa preta", como é o caso da redes neurais.

## Vantagens

A seguir, algumas das vantagens de se utilizar árvores de decisão:

- São fáceis de se interpretar e visualizar.

- Consegue entender padrões não lineares.

- Requer pouco ou nehum pré-processamento de dados por parte do usuário. Exemplo: Não há necessidade de normalização dos dados.

- Pode ser usado para engenharia de _features_, escolha de variáveis importantes e também para predição de valores.

## Desvantagens

A seguir, algumas das desvantagens de se utilizar árvores de decisão:

- É sensível a ruídos.

- Pequenas variações de dados podem causar mudanças na decisão.

- Não lida bem com dados tendenciosos, é sempre recomendado balancear os datasets antes de utilizar árvores de decisão.


## Aplicações

A seguir, tem-se algumas das aplicações em que árvores de decisão pode ser utilizadas:

- Classficação de pessoas em grupos de "Com Diabetes" ou "Sem Diabetes", com base em um conjunto de características ([vide exemplo](./arvore_decisao.ipynb));

- Classificação de risco em se fazer empréstimos, com base no histórico econômico;

- Classificação de potenciais clientes;

## Referências

- [Datacamp](https://www.datacamp.com/community/tutorials/decision-tree-classification-python)