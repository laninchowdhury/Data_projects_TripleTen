# IMDB Sentiment Classification

This project classifies IMDB movie reviews as **positive** or **negative** using Natural Language Processing (NLP) techniques.

## 🎯 Problem

Businesses want to understand customer sentiment from reviews. Manual analysis is slow and subjective. We use machine learning to automate this.

## 🛠️ Tools & Technologies

- Python, pandas, NumPy  
- NLTK (Natural Language Toolkit)  
- scikit-learn, matplotlib, seaborn

## 🔄 Process Overview

1. **Text Cleaning** – Removed stopwords, punctuation, and HTML tags  
2. **Tokenization** – Broke text into meaningful words  
3. **Vectorization** – Used TF-IDF to convert text to numbers  
4. **Modeling** – Naive Bayes, Logistic Regression  
5. **Evaluation** – Accuracy, Precision, Recall

## 📈 Results

- Best Model: Logistic Regression with 87% accuracy  
- Learned which words are strong indicators of sentiment

## 📁 Files

- `imdb_sentiment.ipynb` – Main notebook  
- `data/` – Dataset and cleaned files
