### 📌 **Mixed Code Sentiment Mining on Financial Social Media Interactions**

**Date:** Oct 2023
**Domain:** Natural Language Processing (NLP) · Sentiment Analysis · Deep Learning

#### 📝 **Project Overview**

This project focuses on building a **sentiment analysis system for Hinglish (Hindi-English mixed)** financial social media text. It addresses the challenges of **code-mixing**, **domain-specific vocabulary**, and **contextual ambiguity** to generate accurate sentiment predictions in the financial domain.

#### 🧠 **Key Features**

* Custom **Hinglish financial dataset** created and annotated using AI tools (ChatGPT, Claude.ai).
* Complete **data preprocessing pipeline**: cleaning, tokenization, stopword removal, stemming, lemmatization.
* Explored multiple **vectorization techniques** — TF-IDF, Word2Vec, and GloVe.
* Designed and trained **deep learning models** including Bi-LSTM, LSTM with Word2Vec, and Siamese LSTM with Triplet Loss.
* Achieved **~89% accuracy**, **88% precision**, and **91% recall**, demonstrating robust performance on mixed-language text.

#### 🧰 **Tech Stack**

* **Languages:** Python
* **Libraries & Frameworks:** TensorFlow, Keras, NLTK, Scikit-learn, NumPy, Pandas
* **Models:** Bi-LSTM, LSTM + Word2Vec, Siamese LSTM (Triplet Loss)

#### 📊 **Model Evaluation**

* Used **confusion matrix**, **precision**, **recall**, **F1-score**, and **accuracy** for evaluation.
* Compared performance with baseline mono-linguistic sentiment models.

#### 🚀 **Future Work**

* Real-time sentiment analysis from streaming financial data.
* Integration of multimodal data (e.g., stock charts + text).
* Expansion to diverse financial perspectives (traders, analysts, investors).

