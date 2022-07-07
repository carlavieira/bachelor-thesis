#  Avaliação de Aprendizagem de Máquina para Classificação de Requisitos em Termo de Qualidade

## Aluna responsável

* Carla d'Abreu Martins Vieira

## Professores responsáveis

* Jose Laerte Pires Xavier Junior
* Lesandro Ponciano dos Santos

## Introdução

1. A área da Engenharia de Software tratada neste trabalho é Engenharia de Requisitos.
2. O problema que este trabalho busca resolver nessa área é a falta de análises empíricas do emprego de algoritmos de classificação automática de requisitos de software escritos em linguagem natural em diferentes classes de qualidade de requisitos utilizando técnicas de Aprendizagem de Máquina.
3. Resolver este problema é relevante por que a definição de requisitos é uma etapa fundamental para a garantia do desenvolvimento do software e sua estrutura como  texto escrito em linguagem natural dificulta a padronização e avaliação automática da qualidade dos requisitos.
4. O objetivo geral deste trabalho é avaliar o emprego da classificação automática de requisitos de software expressos em linguagem natural em termos de qualidade utilizando técnicas de Aprendizagem de Máquina.
5. Os *três* objetivos específicos deste trabalho são: 1) classificar a base de dados de requisitos pela característica de qualidade; 2) treinar os modelos de classificação automática; e 3) analisar as precisões dos modelos, comparando-as entre si e com o resultado da classificação manuais de requisitos.

## Fundamentação Teórica

1. O conceito/teoria principal associado a este trabalho é Engenharia de Requisitos. A sua definição neste trabalho  é a área que fornece o mecanismo apropriado para entender o que o cliente deseja, analisar necessidades, avaliar a viabilidade, negociar uma solução razoável, especificar a solução, validar a especificação e gerenciar os requisitos à medida que são transformados em um sistema funcionalconforme definido no trabalho "Software Requirements Engineerings" pelo autor Thayer, Richard H. and Bailin, Sidney C. e Dorfman, M.
2. O conceito/teoria secundário associado a este trabalho é Inteligência Artificial. A sua definição neste trabalho é o estudo de como fazer os computadores realizarem tarefas em que, no momento as pessoas são melhores conforme definido no trabalho "Artificial Intelligence (Sie)" pelo autor Elaine Rich.
3. O conceito/teoria terciário associado a este trabalho é Aprendizado de Máquina. A sua definição neste trabalho é uma disciplina da AI, composta por um conjunto de técnicas que permitem aos computadores aprender dados, faça generalizações e previsões a partir de deles, o que facilita a tomada de decisões, conforme definido no trabalho "Seizing Requirements Engineering Issues through Supervised Learning Techniques" pelo autor Gramajo, Maria and Ballejos, Luciana e Ale, Mariel.
4. O conceito/teoria terciário associado a este trabalho é Aprendizagem Supervisionada. A sua definição neste trabalho é uma técnica de ML que usa dados rotulados, chamados de dados de treinamento, para construir um modelo preditivo para prever o rótulo de dados não rotulados, conforme definido no trabalho "Seizing Requirements Engineering Issues through Supervised Learning Techniques" pelo autor Gramajo, Maria and Ballejos, Luciana e Ale, Mariel.

## Trabalhos Relacionados

1. O trabalho mais relacionado é _"An automatic methodology for the quality enhancement of requirements using genetic algorithms"_, publicado no ano 2021, por que cria uma metodologia que possa modificar requisitos pobres, extraindo as principais características de cada requisito, avaliando sua qualidade com alto nível de especialidade e, então, aprimorando o qualidade dos requisitos
2. O segundo trabalho mais relacionado é _ "Hacia la Evaluacion Automatica de la Calidad de los Requerimientos de Software usando Redes Neuronales Long Short Term Memory"_  , publicado no ano 2020, por que utiliza de redes neurais, do tipo Long Short-Term Memory (LSTM), para prever se os requisitos são singulares ou não, uma das características dos requisitos
3. O terceiro trabalho mais relacionado é _"Speculative requirements: Automatic detection of uncertainty in natural language requirements"_, publicado no ano 2012,  por que foi um dos primeiros artigos a analisar o grau de incerteza de requisitos por meio de algorítmos de aprendizado de máquina.

## Materiais e Métodos

1. O tipo de pesquisa adotado neste trabalho é aplicada, descritiva e quantitativa, por que objetiva trazer a viabilidade em valores quantitativos da previsão automática da qualidade dos requisitos de software expressos em linguagem natural utilizando técnicas de Inteligência Artificial.
2. Os materiais utilizados neste trabalho são Google Compute Engine e Python 3.10
Dados:
* Lima, M.; Valle, V.; Costa, E.; Lira, F.; Gadelha, B. Software Engineering Repositories: Expanding the PROMISE Database; XXXIII Brazilian Symposium on Software Engineering; SBC: Porto Alegre, Brasil, 2020; pp. 427–436. [Google Scholar](https://dl.acm.org/doi/abs/10.1145/3350768.3350776)
* Ferrari, A., Spagnolo, G. O., & Gnesi, S. (2017, September). PURE: A dataset of public requirements documents. In 2017 IEEE 25th International Requirements Engineering Conference (RE) (pp. 502-505). IEEE.
https://ieeexplore.ieee.org/abstract/document/8049173
3. Os métodos empregados neste trabalho são: BoW e TF-IDF (_Feature Extraction_) e SVM, MNB, kNN e LR (algoritmos).
4. As métricas de avaliação são:
  1) Equação de precisão;
  2) Equação de recuperação (_Recall_);
  3) Equação de medida F.
5. As etapa de execução do trabalho são: 
  1) Coleta da base de dados de requisitos; 
  2) Classificação requisitos da base de dados por característica de qualidade e incrementação da base de dados; 
  3) Normalização: limpeza dos dados, onde todas as palavras irrelevantes, como pronomes e artigos, são removidas. Verbos e substantivos flexionados são convertidos para sua forma original;
  4) _Feature Extraction_: transformação do texto em uma informação numérica. Neste estudo, é utilizado BoW e TF-IDF para realizar a conversão;  
  5) Treinamento: vetores obtidos na fase de _Feature Extraction_ são usados para treinar e predizer os modelos de classificação dos quatro algoritmos usados neste trabalho: SVM, MNB, kNN e LR;
  6) Avaliação: resultados das previsões dos rótulos dos requisitos e os rótulos verdadeiros desses requisitos são usados para calcular as medidas de desempenho descritas na Seção 4.2.
