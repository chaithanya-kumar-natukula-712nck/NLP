# NLP Practice – Tokenization using NLTK

This repository contains my practice and exploration of **Natural Language Processing (NLP)** concepts using the **NLTK (Natural Language Toolkit)** library in Python.

The main goal of this notebook is to understand how different tokenization techniques work and how they split text into meaningful components such as sentences, words, or phrases.

---

## What is Tokenization?

Tokenization is the process of breaking a piece of text into smaller units called **tokens**.
These tokens may represent:

* sentences
* words
* punctuation
* phrases

Tokenization is one of the **first and most important preprocessing steps in NLP**, because machine learning models cannot directly process raw text.

---

## Tokenizers Demonstrated

The notebook demonstrates and compares several tokenizers available in **NLTK**:

* Sentence Tokenizer (`sent_tokenize`)
* Word Tokenizer (`word_tokenize`)
* WordPunct Tokenizer
* Treebank Word Tokenizer
* Regexp Tokenizer
* Tweet Tokenizer
* Toktok Tokenizer
* Whitespace Tokenizer
* Punkt Sentence Tokenizer
* Multi Word Expression Tokenizer (MWETokenizer)
* Blankline Tokenizer

Each tokenizer is applied to the same text so that the differences in tokenization behavior can be clearly observed.

---

## Repository Structure

```
NLP
│
├── Tokenization.ipynb
└── README.md
```

* **Tokenization.ipynb** – Jupyter/Colab notebook demonstrating various tokenization methods using NLTK.
* **README.md** – Documentation explaining the purpose of the repository.

---

## Technologies Used

* Python
* NLTK (Natural Language Toolkit)
* Google Colab / Jupyter Notebook

---

## Learning Outcome

By working through this notebook, I learned:

* Different tokenization techniques available in NLTK
* How various tokenizers handle punctuation and whitespace
* How tokenization affects text preprocessing in NLP pipelines
* When to use different tokenizers depending on the text type

---

## Future Work

This repository will be expanded with additional NLP preprocessing techniques such as:

* Stopword Removal
* Stemming
* Lemmatization
* Part-of-Speech Tagging
* Named Entity Recognition

---

## Author

**Chaithanya Kumar Natukula**

