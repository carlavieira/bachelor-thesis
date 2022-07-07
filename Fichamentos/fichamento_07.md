# A Machine Learning-Based Approach for Demarcating Requirements in Textual Specifications

S. Abualhaija, C. Arora, M. Sabetzadeh, L. C. Briand and E. Vaz, "A Machine Learning-Based Approach for Demarcating Requirements in Textual Specifications," 2019 IEEE 27th International Requirements Engineering Conference (RE), 2019, pp. 51-62, doi: 10.1109/RE.2019.00017.

## 1. Fichamento de Conteúdo

Durante uma análise de uma especificação textual de requisitos que é necessário determinar quais declarações na especificação representam os requisitos do sistema. Nsse processo pode ocorrer falhas de na presença ou na aplicação das convensões adequadas de escrita e marcação. No artigo em questão é proposto uma abordagem automatizada para demarcação de requisitos em especificações de requisitos de forma livre. A abordagem, que se baseia no aprendizado de máquina, poderia ser aplicada em diferentes especificações, diferentes domínios e com diferentes estilos de escrita.
As perguntas definidas foram: RQ1. Qual algoritmo de classificação de ML produz mais resultados precisos?; RQ2. Quais são os recursos de ML mais influentes para exigir demarcação de mentos?; RQ3. Quão útil é nossa abordagem na prática?; RQ4. Qual é o tempo de execução da nossa abordagem?; RQ5. Existe alguma compensação boa para reduzir o tempo de execução sem um grande impacto negativo na qualidade da demarcação?
A abordagem foi treinada e avaliada em um conjunto de dados rotulado de forma independente, composto por 30 especificações de requisitos industriais. O conjunto de dados da abordagem produziu uma precisão média de 81,2% e um recall médio de 95,7%. Em comparação com linhas de base simples que demarcam requisitos com base na presença de verbos modais e identificadores, a abordagem leva a um ganho médio de 16,4% na precisão e 25,5% na memória.

## 2. Fichamento Bibliográfico

- As especificações de requisitos (RS, do inglês _Requirements specifications_) são indiscutivelmente os artefatos mais centrais para o processo de engenharia de requisitos. Um RS apresenta as características, capacidades e qualidades necessárias a existência de um sistema.
- Demarcação de requisitos (do inglês _requirements demarcation_) é reconhecer e delimitar com precisão os segmentos de texto que representam requisitos e não-requisitos.
- ML supervisionado (do inglês _supervised Machine Learning_)significa que requer dados rotulados para o treinamento.

## 3. Fichamento de Citações

- _"Our approach is based on supervised ML, meaning that it requires labeled data for training. Our labeled data is made up of RS whose different segments have been marked by human experts as being requirements or non-requirements. Supervised techniques are categorized into classification and regression [9]; the former is aimed at predicting categorical outputs, and the latter – at predicting real-valued outputs. What we are concerned with, namely distinguishing between requirements and non-requirements, is a binary classification problem. In our evaluation (Section IV), we empirically examine several alternative ML classification algorithms in orderto determine which one is the most accurate for our purpose."_
- _"Natural language processing (NLP) is concerned with the computerized understanding, analysis, and production of human-language content [11], [12]."_
- _"The tokens may be words, numbers, punctuation marks, or symbols."_
