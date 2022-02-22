# Modelos de Regressão

## Definição

A análise de regressão linear é usada para prever o valor de uma variável com base no valor de outra. A variável que deseja prever é chamada de variável dependente. A variável que é usada para prever o valor de outra variável é chamada de variável independente.

Essa forma de análise estima os coeficientes da equação linear, envolvendo uma ([Regressão Linear Simples](regressao_linear_simples.ipynb)) ou mais variáveis ([Regressão Linear múltipla](regressao_linear_multipla.ipynb)) independentes que melhor preveem o valor da variável dependente. A regressão linear se ajusta a uma linha reta ou superficial que minimiza as discrepâncias entre os valores de saída previstos e reais.

## Problemas indicados

Antes de se aplicar regressão linear, é importante entender quais os problemas que podem ser enfrentados. Os problemas devem se encaixar nos seguintes pressupostos:

- **Linearidade**: A relação entre as variáveis deve ser linear;

- **Homoscedasticidade (ou Homogeneidade de Variância)**: os termos de erro deve ter variância constante, independente dos valores das variáveis preditoras. Quebramos esse pressuposto quando as variáveis preditoras tem mais ou menos erro dependendo de seus valores;

- **Independência de erros**: Os erros nas variáveis preditoras não devem estar correlacionados;

- **Não multicolinearidade**: as variáveis preditoras não podem ser próximas de uma correlação perfeita;

- **Baixa exogeneidade**: os valores das variáveis preditoras não devem estar contaminados com erros de medida. Este pressuposto não é muito realístico para a Psicometria. Ainda assim, é importante conhecê-lo. Erros de medida podem levar estimativas inconsistentes e superestimação dos coeficientes de regressão.

## Exemplos de problemas

Os problemas a seguir ilustram algumas das aplicações dos modelos de regressão linear e múltipla:

- Projetar a nota de língua portuguesa em uma turma à partir da quantidade de exercícios de casa resolvidos, horas de estudo, número de faltas e quantidade de livros lidos no último ano;

- Descobrir qual variável mais impacta a nota de língua portuguesa: seriam os exercícios de casa, horas de estudo, número de faltas ou a quantidade de livros lidos no último bimestre? Sabendo a importância destas variáveis, podemos planejar uma intervenção;

- Queremos entender que variáveis tem impacto sobre a qualidade de vida de um país à partir de um censo com dezenas de variáveis;

- Entender se a quantidade horas de aula matemática é uma boa variável preditora para a nota da prova de matemática, quando também observamos se os alunos fazem os exercícios em sala de aula.