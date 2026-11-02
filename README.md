
# Wine Quality Classification

## 1. Objetivo

Desenvolver modelos de Machine Learning para classificar
a qualidade de vinhos a partir de suas características
físico-químicas.

A classificação foi definida como:

- 0: Baixa/Média qualidade (nota inferior a 7).
- 1: Alta qualidade (nota igual ou superior a 7).

## 2. Base de dados

Foi utilizada a base WineQT.csv, contendo 1.143
amostras e 11 características físico-químicas,
além da nota de qualidade e do identificador.

## 3. Análise exploratória

Foram analisadas:
- Distribuições das variáveis.
- Correlações.
- Valores extremos.
- Integridade dos dados.
- Balanceamento das classes.

## 4. Pré-processamento

Foram realizadas a definição da variável-alvo,
a exclusão do identificador das variáveis preditoras,
a divisão entre treinamento e teste e a padronização
das variáveis utilizadas na Regressão Logística.

## 5. Modelagem

Foram desenvolvidos dois modelos:

- Regressão Logística.
- Random Forest.

## 6. Avaliação

Os modelos foram avaliados por meio de:

- Acurácia.
- Precisão.
- Recall.
- F1-score.
- ROC-AUC.
- Matrizes de confusão.

## 7. Resultados

Os resultados detalhados e os gráficos estão disponíveis
na pasta results e no notebook.

## 8. Estrutura do projeto

- data/: base de dados.
- notebooks/: análise e modelagem.
- src/: scripts auxiliares.
- results/: gráficos e resultados.
- requirements.txt: bibliotecas utilizadas.

## 9. Apresentação executiva

Consulte o arquivo apresentacao_executiva.pdf
para conhecer os principais insights e conclusões
do estudo.

## 10. Limitações

O modelo apresenta limitações relacionadas ao tamanho
da base, ao desbalanceamento das classes e à utilização
de variáveis físico-químicas para prever uma classificação
originalmente baseada em avaliação sensorial.

Os resultados devem ser interpretados como apoio
complementar à tomada de decisão.
