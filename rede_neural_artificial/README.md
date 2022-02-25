[comparacao_neuronios]: ./docs/neuron_bio_art.png "Comparação entre Neurônios Naturais e Artificiais"
# Rede Neural Artificial

## Definição

As [redes neurais artificiais](./rede_neural_artificial.ipynb) são algoritmos bio-inspirados nas conexões entre os neuronios naturais do cerebro. Esta tecnologia apesar de parecer simples, tem se mostrado extremamente eficiente na resolução de diversos problemas atuais (classificação, regressão, detecção, etc). Seu emprego em conjunto com outras técnicas, como filtros convolucionais, entre outras, atingiu o nível mais avançado de desempenho em diversos tarefas, conhecido como Estado da Arte.

![alt text][comparacao_neuronios]

Se observando da esquerda para a direita, pode-se indentificar as cinco estruturas que compoem um neurônio artificial:

1. **Nós de entrada**: Assim como nos neurônios naturais que contam com um estrutura de captação de impulsos, os neuronios artificiais tem nós responsáveis pela entrada de dados.

2. **Conexões**: De forma similar ao que acontece com os estímulos transportados pelos neurônios naturais, as conexões são responsáveis por transmitir os dados dos nós de entrada, além de associar (multiplicar) os dados recebidos com os pesos de cada conexão.

3. **Somador**: O somador é responsável por somar os valores de cada conexão, já multiplicados pelos pesos, de forma ponderada e compilar toda os estímulos recebidos pelas entradas dos dados em um único valor.

4. **Função de Ativação**: A função de ativação, assim como no neurônio natural, que só reage quando seu estímulo supera algum limiar, é a responsável definir o comportamento do neurônio artificial. Sua atuação é definida por uma função, que pode ser linear, logística, tangente hiperbólica, etc., que confere a capacida de reagir ou não e, reagindo, qual o valor de sua saída.

5. **Nó de Saída**: O nó de saída é responsável por transmitir o valor da saída do neurônio artificial para o nó de entrada de outro ou para a solução final.

Perceba que as implicações dessa arquitetura é que apenas consegue trabalhar com dados numéricos e aqueles que possam ser traduzidos para este formato.

## Vantagens

A seguir pode-se ver algumas das vantagens de quando se usam Redes Neurais Artificiais:

- São flexíveis e pode ser usadas para uma gama de problemas. Exemplo: Classficação, regressão, reconhecimento de padrões, etc.;

- Qualquer dado que possa ser representado numericamente pode ser usado como entrada. Exemplo: Números, textos, imagens, etc.;

- Lidam bem com dados não lineares e que tenha um grande número de entradas, por isso é bastante confiável para problemas com muitas _features_;

- Uma vez treinado, o tempo de predição é muito pequeno, podendo até ser usado em aplicações em tempo real.

- Lida muito bem com grandes volumes de dados.

## Desvantagens

A seguir pode-se ver algumas desvantagens de quando se usam Redes Neurais Artificiais:

- Redes Neurais Artificiais são conhecidas por serem "caixas pretas", o que significa que não se pode ter ideia do quanto cada variável independente influencia a saída;

- É computacionalmente cara e consome muito tempo para treinar um modelo;

- Depende de um grande volume de dados para treinar o que pode, se não for satisfeito, leva à problemas de _overfitting_. ;

## Aplicações

- Reconhecimento de voz;

- Classificação de dados;

- Análise de sentimentos;

- Detecção de objetos;

- Segmentação semântica de imagens;

## Referências

- [Datacamp](https://www.datacamp.com/community/tutorials/deep-learning-python)

- [Machine Learning Mastery](https://machinelearningmastery.com/tutorial-first-neural-network-python-keras/)