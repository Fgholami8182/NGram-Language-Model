# NGram-Language-Model
Statistical N-gram Language Models (Unigram, Bigram, Trigram and Quadrigram) implemented from scratch in Python.
# N-Gram Language Model from Scratch

A Python implementation of **Statistical Language Models** using **N-Gram** techniques (Unigram, Bigram, Trigram, and Quadrigram) built entirely from scratch as part of the **Special Topics in Artificial Intelligence** course.

The objective of this project is to understand how statistical language models work by implementing every stage manually without relying on NLP frameworks.

---

## Project Overview

Language models estimate the probability of a sequence of words and are one of the fundamental concepts in Natural Language Processing (NLP).

In this project, different N-Gram models are implemented to learn the statistical structure of a text corpus and generate new sentences based on learned probabilities.

The implementation includes:

* Text preprocessing
* Sentence segmentation
* Tokenization
* Vocabulary construction
* Frequency counting
* Unigram model
* Bigram model
* Trigram model
* Quadrigram model
* Random sentence generation using learned probabilities

---

## Dataset

The corpus used in this project is:

**Pride and Prejudice** by **Jane Austen**

The text is used as the training corpus for building statistical language models.

---

## Project Pipeline

```
Text Corpus
      │
      ▼
Text Cleaning
      │
      ▼
Sentence Segmentation
      │
      ▼
Tokenization
      │
      ▼
Vocabulary Construction
      │
      ▼
N-Gram Extraction
      │
      ▼
Probability Calculation
      │
      ▼
Sentence Generation
```

---

## Models Implemented

* Unigram Language Model
* Bigram Language Model
* Trigram Language Model
* Quadrigram Language Model

Each model estimates the probability of the next word using different lengths of context.

---

## Technologies Used

* Python
* NumPy
* Jupyter Notebook

---

## Repository Structure

```
NGram-Language-Model/
│
├── projectSpecial.ipynb
├── pride_prejudice.txt
├── README.md
├── requirements.txt
└── .gitignore
```

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/NGram-Language-Model.git
```

2. Install the required packages

```bash
pip install -r requirements.txt
```

3. Place the dataset (`pride_prejudice.txt`) in the project directory.

4. Open the notebook

```bash
jupyter notebook
```

5. Run all notebook cells.

---

## Learning Outcomes

This project demonstrates practical implementation of:

* Statistical Language Modeling
* Probability Estimation
* N-Gram Modeling
* Text Preprocessing
* Natural Language Processing Fundamentals

---

## Future Improvements

Possible extensions include:

* Laplace Smoothing
* Good-Turing Smoothing
* Kneser-Ney Smoothing
* Perplexity Evaluation
* Beam Search
* Top-k Sampling
* Temperature Sampling
* Interactive Text Generation

---

## Author

**Fatemeh**

M.Sc. Student in Artificial Intelligence

University of Arak
