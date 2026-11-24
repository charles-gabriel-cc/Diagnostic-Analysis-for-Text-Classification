<p align="center">
  <img src=".github/banner.svg" alt="Diagnostic Analysis for NLP" width="100%" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter" />
  <img src="https://img.shields.io/badge/NLP-XAI-7C3AED?style=flat-square" alt="NLP XAI" />
  <img src="https://img.shields.io/badge/Dataset-Kaggle%20TSE-20BEFF?style=flat-square&logo=kaggle&logoColor=white" alt="Kaggle" />
</p>

## Sobre o Projeto

Estudo prático de **análise diagnóstica de técnicas de explicabilidade (XAI)** aplicadas à classificação de texto, baseado no artigo publicado na **EMNLP 2020** ([*A Diagnostic Study of Explainability Techniques for Text Classification*](https://aclanthology.org/2020.emnlp-main.263.pdf)).

O notebook avalia modelos neurais (**CNN** e **LSTM**) sobre o dataset [**Tweet Sentiment Extraction**](https://www.kaggle.com/competitions/tweet-sentiment-extraction/data) e compara o comportamento de diferentes métodos de atribuição de importância de tokens frente a um *baseline* aleatório.

## O que foi implementado

- 🧹 **Pré-processamento de texto:** limpeza, remoção de stopwords e tokenização com `NLTK` e `pandas`.
- 🧠 **Modelos avaliados:**
  - **CNN** (Rede Neural Convolucional para texto)
  - **LSTM** (Rede Recorrente Long Short-Term Memory)
- 🔍 **Técnicas de explicabilidade comparadas:**
  - **Saliency** *(baseada em gradiente)*
  - **InputXGrad** *(baseada em gradiente)*
  - **Guided Backpropagation** *(baseada em gradiente)*
  - **Occlusion** *(baseada em perturbação)*
  - **LIME** *(modelo substituto local)*
  - **Random Baseline** *(referência de comparação)*

## Estrutura

```text
Diagnostic-Analysis-for-Text-Classification/
└── Diagnostic_Analysis_for_Text_Classification.ipynb
```

## Como Executar

1. Baixe o dataset [**Tweet Sentiment Extraction**](https://www.kaggle.com/competitions/tweet-sentiment-extraction/data) (`train.csv` e `test.csv`).
2. Abra `Diagnostic_Analysis_for_Text_Classification.ipynb` no **Google Colab** (recomendado com GPU) ou **Jupyter Notebook**.
3. Ajuste os caminhos `data_dir` e `test_dir` nas células iniciais para apontar para os arquivos do dataset.
4. Execute as células em ordem.

## Autores

- **Charles Gabriel** (`cgcc`)
- **Paulo Henrique Leite** (`plthc`)
