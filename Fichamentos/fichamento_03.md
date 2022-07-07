# Hacia la Evaluación Automática de la Calidad de los Requerimientos de Software usando Redes Neuronales Long Short Term Memory

Gramajo, María Guadalupe; Ballejos,  Luciana; Mariel, Ale. "Hacia la Evaluación Automática de la Calidad de los Requerimientos de Software usando Redes Neuronales Long Short Term Memory," WER 2020

## 1. Fichamento de Conteúdo

Um dos desafios para a avaliação da qualidade de requisitos é por se tratar de um texto escrito em linguagem natural. O artigo propõe o estudo da qualidade de requisitos desenvolvidos por meio de redes neurais. Utilizando da definição de qualidade definida pela norma ISO/IEC/IEEE 29148:2018, o estudo foca em um dos tópicos de qualidade do requisito, a singularidade. Para isso, é proposto a utilização de redes neurais, do tipo _Long Short-Term Memory_ (LSTM), para prever se os requisitos são singulares ou não. Cada requisito é submetido a um processo de tokenização e rotulagem gramatical, a fim de obter uma sequência representativa que atua como uma entrada para o modelo neural. E então o modelo neural proposto é treinado com um conjunto de dados de 1000 requisitos. O conjunto de dados gerado foi particionado, considerando 80% da amostra para realizar o treinamento da rede neural. Enquanto, 10% da amostra foi usada para teste e os 10% restantes para validação. A técnica de validação cruzada é aplicada nesta proposta para evitar o _overfitting_ do modelo e a técnica de pesquisa de grade aleatória para otimizar os valores dos hiperparâmetros. O modelo neural atingiu seu desempenho máximo na época 26. Nesta última, a precisão alcançada é de 79%. Os resultados são apresentados como promissores e há o interesse em prosseguir a pesquisa com os demais tópicos de qualidade de um requisito.

## 2. Fichamento Bibliográfico 

* A proporiedade de qualidade é quanto o requisito inclui em sua especificação a definição de uma única funcionalidade, característica, restrição ou fator de qualidade (página 2).
* _Long short-term memory_ (LSTM) são um tipo de redes neurais recorrentes(RNN, do inglês _recurrent neural network_) apropriadas para processas informacaio sequencial (página 3).
* _Tokenizacíon_ (tokenização) é o processo  de estruturar os requisitos em um formato de entrada apropriado para o modelo neural proposto (página 4).
* _POS (Part Of Speech) tagging_  é o processo de associar os _tokens_ que compõem uma frase com seu rótulo gramatical correspondente (página 4).

## 3. Fichamento de Citações 

* _"En los  últimos años, la Inteligencia Artificial (IA) se ha posicionado como una herramienta poderosa y accesible, capaz de ser utilizada como un componente clave en el desarrollo de sistemas de software. Esto es así, debido al surgimiento de nuevas estrategias de aprendizaje, disponibilidad de mayores conjuntos de datos y el aumento de la capacidad de procesamiento en los ordenadores"_
* _"La flexibilidad y la naturaleza inherente del lenguaje hacen que los requerimientos estén propensos a inconsistencias, redundancias y ambigüedades y, consecuentemente, esto influye de manera negativa en las fases posteriores del ciclo de vida del software."_ 
* _"Dicho estándar establece que un requerimiento cumple con esta propiedad si incluye en su especificación la definición de una única funcionalidad, característica, restricción o factor de calidad."_ 
