# Software Requirements Classification Using Machine Learning Algorithms

Dias Canedo E, Cordeiro Mendes B. Software Requirements Classification Using Machine Learning Algorithms. Entropy. 2020; 22(9):1057. https://doi.org/10.3390/e22091057

## 1. Fichamento de Conteúdo

O artigo em questão desenvolve um estudo sobre a comparação entre as técnicas de extração de recursos de texto e algoritmos de aprendizado de máquina para o problema de classificação do engenheiro de requisitos. As pertundas principais definidas pelo artigo foram: “Qual funciona melhor (_Bag of Words (BoW)_ vs. _Term Frequency – Inverse Document Frequency (TF -IDF)_ vs. _Qui Quadrado (CHI2)_) para classificar os Requisitos de Software em Requisitos Funcionais (FR) e Requisitos Não Funcionais (NF), e as subclasses de Requisitos Não Funcionais? ” e “Qual Algoritmo de Aprendizado de Máquina fornece o melhor desempenho para a tarefa de classificação de requisitos?”. O dado utilizado para realizar a pesquisa foi o PROMISE_exp, uma expansão do repositório PROMISE que contém requisitos de software rotulados. Todos os documentos do banco de dados foram limpos com um conjunto de etapas de normalização e as duas extrações de recursos e as técnicas de seleção de recursos utilizadas foram BoW, TF-IDF e CHI2, respectivamente. Os algoritmos utilizados para classificação foram Regressão Logística (LR), Máquina de Vetores de Suporte (SVM), Multinomial Naive Bayes (MNB) e k-vizinhos mais próximos (kNN). As inovações aboradas no artigo foram os dados utilizados para a realização do experimento, o detalhamento das etapas utilizadas para reproduzir a classificação e a comparação entre BoW, TF-IDF e CHI2 para este repositório, que ainda não tinha sido abordada por outros estudos. Como resultado final, foi notado que o uso de TF-IDF seguido do uso de LR teve um melhor resultado de classificação para diferenciar os requisitos, com uma medida F de 0,91 na classificação binária (vinculação com SVM nesse caso), 0,74 na classificação NF e 0,78 na classificação geral..

## 2. Fichamento Bibliográfico

- A tarefa de Classificação de Requisito de Software (SRC, do inglês _Software Requirement Classification_), consiste em especificar a categoria a que pertence um determinado Requisito de Software (SR), entre Requisitos Funcionais e Não Funcionais.
- Requisitos Funcionais (FRs, do inglês _Functional Requirements_) são requisitos que descrevem os serviços, comportamento ou funções que um sistema fornece
- Requisitos Não Funcionais (NFRs, do inglês _Non-Functional Requirements_) são requisitos que incluem os atributos (como qualidade, usabilidade, segurança, privacidade, etc.), ou restrições na aplicação a ser desenvolvida ou no processo de desenvolvimento de software.

## 3. Fichamento de Citações

- _"The correct classification of requirements has become an essential task within software engineering."_
- _"Even with the software requirements being well known and well described, the automatic classification of requirements written in natural language into functional requirements and the subcategories of non-functional requirements is still a challenge"_
- _"A requirement it’s a need, functionality or characteristic of a system. Three are mainly three definitions for requirements [15]: 1. A condition or capability needed by a user to solve a problem or achieve an objective; 2. A condition or capability that must be met or possessed by a system or system component to satisfy a contract, standard, specification, or other formally imposed documents; 3. A documented representation of a condition or capability as in (1) or (2)."_
