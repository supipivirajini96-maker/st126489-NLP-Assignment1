# st126489-NLP-Assignment1

# Word Embeddings from Scratch and with Gensim

This repository contains implementations and experiments related to **word embedding models**, including **Word2Vec** and **GloVe**, built both **from scratch** and using **Gensim**.

---

## 📂 Repository Structure

```
.
├── 01_Word2Vec_Without_Neg_Sample.ipynb
├── 02_Word2Vec_(Neg_Sampling).ipynb
├── 03_GloVe_from_Scratch.ipynb
├── 04_GloVe_(Gensim).ipynb
├── word_analogies_dataset.txt
├── wordsim353crowd.csv
├── Discussion.pdf
└── README.md
```

---

## 📘 Notebook Descriptions

### 1. `01_Word2Vec_Without_Neg_Sample.ipynb`

* Implements the **Word2Vec (Skip-gram)** model **from scratch**
* Uses **softmax** without negative sampling

### 2. `02_Word2Vec_(Neg_Sampling).ipynb`

* Implements **Word2Vec with Negative Sampling** from scratch
* More computationally efficient than full softmax
* Demonstrates how negative samples improve scalability

### 3. `03_GloVe_from_Scratch.ipynb`

* Full **GloVe (Global Vectors)** implementation from scratch
* Builds a co-occurrence matrix

### 4. `04_GloVe_(Gensim).ipynb`

* Uses **Gensim** to train GloVe-style embeddings

---

## 📊 Datasets

### `word_analogies_dataset.txt`

* Used for evaluating embeddings on **word analogy tasks**
* Example: *king − man + woman ≈ queen*

### `wordsim353crowd.csv`

* Contains human similarity judgments for word pairs
* Used for **semantic similarity and synthetic evaluation** (correlation analysis)

---

## 📄 Discussion

### `Discussion.pdf`

* Contains analysis, observations, and comparisons between models

---

