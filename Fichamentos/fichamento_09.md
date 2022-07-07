# Speculative requirements: Automatic detection of uncertainty in natural language requirements

H. Yang, A. De Roeck, V. Gervasi, A. Willis and B. Nuseibeh, "Speculative requirements: Automatic detection of uncertainty in natural language requirements," 2012 20th IEEE International Requirements Engineering Conference (RE), 2012, pp. 11-20, doi: 10.1109/RE.2012.6345795.

## 1. Fichamento de Conteúdo

As partes interessadas freqüentemente usam linguagem especulativa quando precisam transmitir seus requisitos com algum grau de incerteza. Devido à imprecisão intrínseca da linguagem especulativa, os requisitos especulativos correm o risco de ser mal interpretados e a incerteza relacionada negligenciada, e podem se beneficiar de um tratamento cuidadoso no processo de engenharia de requisitos. No artigo em questão, é apresentada uma abordagem orientada linguisticamente para a detecção automática de incerteza em requisitos de linguagem natural (NL). A abordagem é compreendividida em duas etapas. Primeiro, são identificadas sentenças especulativas aplicando um algoritmo de aprendizado de máquina chamado Campos Aleatórios Condicionais (CRFs) para identificar pistas de incerteza. O algoritmo explora um rico conjunto de recursos lexicais e sintáticos extraídos de sentenças de requisitos. Em segundo lugar, a abordagem tenta determinar o escopo da incerteza. É utilizada uma abordagem baseada em regras que se baseia em um conjunto de heurísticas linguísticas feitas à mão para determinar o escopo da incerteza com a ajuda das estruturas de dependência presentes na árvore de análise sintática da frase.

## 2. Fichamento Bibliográfico

- A incerteza é uma possível característica dos requisitos que pode ter sido incluída deliberadamente, para evitar o comprometimento com declarações factuais sobre as quais o autor não tem certeza, ou incluída de forma semi-intencional, por exemplo, ao transcrever uma entrevista, como a expressão de uma incerteza inerente aos requisitos.
- As dicas de incerteza típicas são construções sintáticas que podem sinalizar para um incerteza, e se enquadram nas seis seguintes categorias, que são classificadas com base na generalização tag de classe gramatical (POS) da sugestão.
- _Word-token Features_ é um recurso que inclui o lema da palavra, a tag da parte do discurso (PoS) e a tag do trecho da palavra, que são obtidos do Genia Tagger5.

## 3. Fichamento de Citações

- _"Uncertainty in natural language may be realised through various linguistic cues and is marked by a variety of syntactic constructions"_
- _" Moreover, regardless of whether speculative language is seen as an undesirable attribute of requirements [3] or whether it is seen as having a positive role in the elicitation process, we suggest that correctly identifying and classifying instances of uncertainty in requirements is important."_
- _" In fact, one could have speculative indicative statements (i.e. uncertainty in the state of the domain) and speculative optative statements (i.e. uncertainty about the desired behaviour), in addition to the factual versions which the literature commonly considers"_
