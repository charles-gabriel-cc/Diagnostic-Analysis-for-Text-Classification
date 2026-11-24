<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:312e81,50:6d28d9,100:ec4899&height=170&section=header&text=Diagnostic%20Analysis%20for%20NLP&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=40&desc=Estudo%20Comparativo%20de%20T%C3%A9cnicas%20de%20Explicabilidade%20(XAI)%20em%20Classifica%C3%A7%C3%A3o%20de%20Texto&descAlignY=65&descSize=14" width="100%" alt="Banner" />
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />
  <img src="https://img.shields.io/badge/NLP-XAI-7C3AED?style=for-the-badge" alt="NLP XAI" />
  <img src="https://img.shields.io/badge/Dataset-Kaggle%20TSE-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" />
</p>

---

## 📖 Sobre o Projeto

Estudo prático de **análise diagnóstica de técnicas de explicabilidade (XAI)** aplicadas à classificação de texto, baseado no artigo publicado na **EMNLP 2020** ([*A Diagnostic Study of Explainability Techniques for Text Classification*](https://aclanthology.org/2020.emnlp-main.263.pdf)).

O notebook avalia modelos neurais (**CNN** e **LSTM**) sobre o dataset [**Tweet Sentiment Extraction**](https://www.kaggle.com/competitions/tweet-sentiment-extraction/data) e compara o comportamento de diferentes métodos de atribuição de importância de tokens frente a um *baseline* aleatório.

---

## ✨ O que foi implementado

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

---

## 📂 Estrutura

```text
Diagnostic-Analysis-for-Text-Classification/
└── Diagnostic_Analysis_for_Text_Classification.ipynb
```

---

## 🚀 Como Executar

1. Baixe o dataset [**Tweet Sentiment Extraction**](https://www.kaggle.com/competitions/tweet-sentiment-extraction/data) (`train.csv` e `test.csv`).
2. Abra `Diagnostic_Analysis_for_Text_Classification.ipynb` no **Google Colab** (recomendado com GPU) ou **Jupyter Notebook**.
3. Ajuste os caminhos `data_dir` e `test_dir` nas células iniciais para apontar para os arquivos do dataset.
4. Execute as células em ordem.

---

## 👥 Autores

- **Charles Gabriel** (`cgcc`)
- **Paulo Henrique Leite** (`plthc`)
