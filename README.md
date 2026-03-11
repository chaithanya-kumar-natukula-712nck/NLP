# NLP Text Preprocessing using NLTK

This repository contains my practice and exploration of **Natural Language Processing (NLP)** preprocessing techniques using the **NLTK (Natural Language Toolkit)** library in Python.

The notebooks demonstrate how raw text is prepared for NLP tasks by applying **tokenization** and **stemming** techniques.

---

# Repository Structure


```
NLP
│
├── Tokenization.ipynb
├── Stemming.ipynb
└── README.md
```


• **Tokenization.ipynb** – Demonstrates multiple tokenization techniques available in NLTK.  
• **Stemming.ipynb** – Implements and compares different stemming algorithms.

---

# Tokenization Techniques Implemented

The **Tokenization.ipynb** notebook demonstrates several tokenizers provided by NLTK:

- Sentence Tokenizer (`sent_tokenize`)
- Word Tokenizer (`word_tokenize`)
- WordPunct Tokenizer
- Treebank Word Tokenizer
- Regexp Tokenizer
- Tweet Tokenizer
- Toktok Tokenizer
- Whitespace Tokenizer
- Punkt Sentence Tokenizer
- Multi Word Expression Tokenizer (`MWETokenizer`)
- Blankline Tokenizer

Each tokenizer is applied to the same text to observe how different tokenization strategies split text into tokens.

---

# Stemming Algorithms Implemented

The **Stemming.ipynb** notebook demonstrates and compares the following stemming algorithms:

- **Porter Stemmer**
- **Snowball Stemmer**
- **Lancaster Stemmer**
- **Regexp Stemmer**

A comparison table is generated to observe how each algorithm reduces words to their root form.

Example:

| Word | Porter | Snowball | Regexp | Lancaster |
|-----|-----|-----|-----|-----|
| running | run | run | runn | run |
| studies | studi | studi | studi | study |
| happiness | happi | happi | happines | happy |

---

# Technologies Used

- Python
- NLTK (Natural Language Toolkit)
- Jupyter Notebook / Google Colab

---

# Learning Outcomes

Through this project I explored:

- Different tokenization techniques in NLP
- Sentence and word segmentation
- Handling punctuation and whitespace during tokenization
- Differences between stemming algorithms
- How preprocessing affects text representation in NLP pipelines

---

# Future Improvements

This repository may be expanded with additional NLP preprocessing techniques such as:

- Stopword Removal
- Lemmatization
- Part-of-Speech Tagging
- Named Entity Recognition
- Text Vectorization

---

# Author

**Chaithanya Kumar Natukula**
