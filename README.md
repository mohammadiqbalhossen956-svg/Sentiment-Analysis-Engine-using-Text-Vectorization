# NLP-based Sentiment Analyzer (Positive, Negative, Neutral)

## Project Overview
This project implements a **Natural Language Processing (NLP)** engine to analyze and classify the sentiment of text data, such as reviews or social media posts. The goal was to build a lightweight yet effective classifier that can run in resource-constrained environments like **Pydroid 3**.

## Key Features
* **Text Embedding (Vectorization):** Successfully implemented the **Bag of Words (BoW)** model using `CountVectorizer` to convert raw text strings into numerical matrices.
* **Classification Model:** Leveraged the **Multinomial Naive Bayes** algorithm, which is highly effective for text classification and sentiment analysis.
* **Sentiment Categories:** The model is trained to distinguish between three distinct categories: **Positive 😃, Negative 😠, and Neutral 😐**.
* **Zero-Framework Logic:** Built the entire pipeline using core data science libraries, demonstrating a deep understanding of NLP workflows without relying on high-level DL frameworks.

## Tech Stack
* **Language:** Python
* **Libraries:** Scikit-Learn (NLP & ML), Pandas (Data Management), NumPy
* **Environment:** Developed and tested on **Pydroid 3**

## Learning Outcomes
* Understanding the concept of **Word Embeddings** and how computers "read" human language.
* Implementing a complete NLP pipeline: Preprocessing -> Vectorization -> Training -> Prediction.
