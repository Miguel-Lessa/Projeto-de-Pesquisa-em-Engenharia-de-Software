# Towards Automatically Addressing Self-Admitted Technical Debt: How Far Are We?

Mastropolo, Antonio; Di Penta, Massimiliano; Bavota,  Gabriele. "Towards Automatically Addressing Self-Admitted Technical Debt: How Far Are We?", in 2023 38th IEEE/ACM International Conference on Automated Software Engineering (ASE), doi: [10.1109/ASE56229.2023.00103](https:://doi.org/10.1109/ASE56229.2023.00103)

## 1. Fichamento de Conteúdo

O artigo investiga se o método de pagar automaticamente(em código fonte) a dívida técnica auto-admitida(SATD) é viável,utilizando modelos generativos, uma ressalva aos modelos de transformadores pré-treinados, ajustando eles para poder corrigir as dívidas de uma forma automática. A pesquisa criou um conjunto de dados de 5.039 casos de remoção de SATD em 595 projetos de código aberto, sendo testados 7 configurações de modelos, incluindo o CodeT5 e também experimentos com o Chat GPT.  O resultado apresentado mostrou que a automatização é desafiadora, uma vez que o modelo mais eficaz corrigiu entre 2% e 8% dos casos. Foi identificado que o pré-treinamento dos modelos foi essencial para aumentar o desempenho. A presença de comentários SATD também foi importante para a eficiência do modelo. Foi destacado quão grande é o desafio do pagamento automático do SATD e que isso pode gerar pesquisas futuras para conseguir um melhor desempenho.


## 2. Fichamento bibliográfico

- _Dívida técnica auto-admitida(SATD):_ 
- _Pre-trained transformers(Transformadores pré-treinados):_
- _SATD Comments(Comentários SATD:_
- _Deep Learning(Aprendizagem profunda):_

## 3. Fichamento de Citações

- _"SATD refers to instances of technical debt documented (e.g., through code comments) by developers"_
- _"Removing SATD is an essential activity in software maintenance, with most SATD instances eventually being removed, often when source code is refactored or improved"_
- _"Considering the diversity of SATD, its repayment would require approaches that go beyond what has been developed for related tasks like code repair or bug fixing"_
- _"Among the different experimental configurations, models combining both self-supervised and supervised pre-training show slight performance improvement"_
- _"The need for additional research is evident as current models can only handle simpler SATD cases effectively, with complex SATDs requiring multiple code edits beyond the models’ current capabilities"_


