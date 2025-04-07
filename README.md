# Projeto Final - Transformer com MLM e Comparação com Cadeias de Markov

## Integrantes:
- Ana Carolina Aguiar - Mat.: 20210024326
- Cassiano Sabino - Mat.: 20210025806
- Geovana Lima - Mat.: 20210024729

## Descrição

Este repositório contém o projeto final da disciplina de Sistemas Baseados em Conhecimento. O objetivo do projeto é explorar o uso de arquiteturas **Transformer** utilizando o método de treinamento **semissupervisionado** conhecido como **MLM (Masked Language Modeling)**.  

A base para o projeto foi o exemplo oficial da Keras disponível neste [link](https://keras.io/examples/nlp/masked_language_modeling/#create-bert-model-pretraining-modelfor-masked-language-modeling).

### Etapas do Projeto:

- Rodar e comentar detalhadamente o código fornecido pela Keras.
- Adaptar o código para outro conjunto de dados, selecionado pelo grupo.
- Resolver o mesmo problema usando **Cadeias de Markov**.
- Comparar os resultados entre o modelo baseado em Transformer e o modelo baseado em Markov.
- Realizar uma análise crítica das diferenças de desempenho, vantagens e limitações de cada abordagem.

---

## Dataset Utilizado

**DBpedia Classes Dataset**  
Link: [DBpedia on Kaggle](https://www.kaggle.com/datasets/danofer/dbpedia-classes/data)

> O DBpedia é um projeto que visa extrair conteúdo estruturado da Wikipédia. Este dataset contém categorias hierárquicas (classes) para mais de 340 mil artigos, distribuídas em 3 níveis: 9, 70 e 219 classes.  
>  
> Essa versão do dataset é bastante desafiadora e amplamente utilizada como benchmark em tarefas de classificação de texto hierárquica e multilabel.

---

## Tecnologias Utilizadas

- Python 3.10+
- TensorFlow / Keras
- Scikit-learn
- Numpy / Pandas
- Cadeias de Markov (implementação manual)
- Jupyter Notebook

---

## Estrutura do Repositório
📁 SBC-Final-Project
├── L1/ 
│ ├── BERT_Classificação_DBPedia_L1.ipynb 
│ ├── bert_mlm_dbpedia.keras 
│ └── Markov_Classificação_DBPedia_L1.ipynb 
├── L2/ 
│ ├── BERT_Classificação_DBPedia_L2.ipynb 
│ ├── bert_mlm_dbpedia-l2.keras 
│ └── Markov_Classificação_DBPedia_L2.ipynb 
├── L3/ 
│ ├── BERT_Classificação_DBPedia_L3.ipynb 
│ ├── bert_mlm_dbpedia-l3.keras 
│ └── Markov_Classificação_DBPedia_L3.ipynb 
├── original_notebook/ 
│ └── masked_language_modeling.ipynb 
├── .gitignore 
├── .python-version 
└── README.md

