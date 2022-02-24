# [Naive Bayes Classifier](./multinomial_naive_bayes.ipynb)

## Definição

O algoritmo de classificação *naive bayes* é baseado no Teorema de Bayes. É um dos mais simples modelos de aprendizado supervisionado, porém é rápido, acurado e confiável. Em grandes datasets, a técnica tem alta acurácia e velocidade de processamento.

O [_Naive Bayes Classifier_](./naive_bayes_classifier.ipynb) ou [_Multinomial Naive Bayes Classifier_](./multinomial_naive_bayes.ipynb), para uma ou multiplas classes, respectivamente, assume que o efeito de determinada _feature_ em uma classe é independente de outras _features_. Esse pressuposto simplifica a computação e por isso que é considerado "_naive_".

O Teorema de Bayes é um modelo de probabilidade condicional, que é utilizado pelo classificador, tem a seguinte definição:

<br />

$P(h|D) = \frac{P(D|h)P(h)}{P(D)}$

<br />

Onde:

- $P(h)$: é a probabilidade da hipótese $h$ ser verdadeira (independente dos dados). É conhecido como probabilidade anterior de $h$;

- $P(D)$: é a probabilidade do dados (independentemente da hipótese). É conhecido como probabilidade anterior dos dados;

- $P(h|D)$: É a probalidade da hipótese $h$ ser verdadeira, com base nos dados. É conhecido como probabilidade posterior de $h$;

- $P(D|h)$: é a probabilidade de $D$ ser verdadeiro, quando a hipótese $h$ é verdadeira. É conhecido com probabilidade posterior de $D$;

## Vantagens:

A seguir pode-se ver algumas vantagens do _Naive Bayes Classifier_ e do _Multinomial Naive Bayes Classifier_:

- Abordagem rápida e precisa para predição;

- Baixo custo computacional;

- Eficiente para grandes datasets;

- Pode ser usado em problema de predição multi-classe;

- Tem boa performance em problemas analíticos;

- Quando o requisito da independência é satisfeito, o _Naive Bayes_ tem desempenho superior quando comparado à técnicas como regressão logística e necessita de menos dados.

- Pode ser usado em dados categóricos;

- Pode ser usado em predições de tempo real pois tem rápida inferência;

## Desvantagens:

A seguir pode-se ver algumas desvantagens do _Naive Bayes_:

- Se algum dado do _dataset_ de teste conter uma categoria que não existe no _dataset_ de treino, o _Naive Bayes_ não consegue classificar o dado. Esse problema é conhecido como "Zero Frequency".

## Aplicações:

Algumas das aplicações mais comuns do _Naive Bayes_ são:

- Sistemas de recomendação;

- Filtros de Spam;

- Classificação de textos;

- Análise de sentimentos.

## Referencias

- [Analytics Vidhya](https://www.analyticsvidhya.com/blog/2017/09/naive-bayes-explained/#:~:text=In%20simple%20terms%2C%20a%20Naive,about%203%20inches%20in%20diameter.)

- [Datacamp](https://www.datacamp.com/community/tutorials/naive-bayes-scikit-learn?utm_source=adwords_ppc&utm_medium=cpc&utm_campaignid=1455363063&utm_adgroupid=65083631748&utm_device=c&utm_keyword=&utm_matchtype=&utm_network=g&utm_adpostion=&utm_creative=278443377092&utm_targetid=aud-299261629574:dsa-429603003980&utm_loc_interest_ms=&utm_loc_physical_ms=1001552&gclid=Cj0KCQiA09eQBhCxARIsAAYRiyn2fnLYo2aliKsyXGaqEYQ320Cbw38jZYqlahgZNlKpJObpZeIQJFUaAtS8EALw_wcB)