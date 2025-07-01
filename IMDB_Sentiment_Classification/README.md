# IMDB Sentiment Classification

This project explores sentiment analysis on IMDB movie reviews using text preprocessing and machine learning models. The primary goal was to accurately classify reviews as positive or negative based on their content.

---

## 📌 Objective

Classify IMDB reviews into **positive** or **negative** sentiments using natural language processing (NLP) techniques and evaluate multiple models to maximize F1 score.

---

## 📊 Dataset Overview

- Large corpus of IMDB reviews labeled as `positive` or `negative`.
- Reviews span multiple decades.
- Texts were preprocessed and vectorized using **TF-IDF**.

---
IMDB_Sentiment_Classification/images/split_distribution.png
IMDB_Sentiment_Classification/images/evaluation_curves.png

## 🧪 Train-Test Split Distribution

![Train-Test Distribution](Train_test_split_distribution.png)

> A consistent pattern between the train and test sets confirms balanced splitting, ensuring reliable model evaluation. Many movies received few reviews, while others generated significant review volumes.

---

## 📈 Model Performance

![Model Evaluation Curves](model_evaluation_curves.png)

- **Test Accuracy**: `0.86` – solid generalization.
- **Test F1 Score**: `0.87` – balanced precision and recall.
- **TF-IDF** successfully transformed reviews into numerical vectors.

---

## ⚙️ Tools Used

- Python
- Scikit-learn
- NLTK
- Matplotlib, Seaborn

---

## ✅ Results Summary

| Metric        | Train | Test |
|---------------|-------|------|
| F1 Score      | 0.92  | 0.87 |
| ROC AUC       | 0.98  | 0.94 |
| Precision-Recall AUC | 0.98 | 0.93 |

---

## 📚 Future Improvements

- Explore LSTM/BERT for deeper semantic understanding.
- Tune hyperparameters via GridSearchCV.
- Incorporate review length and metadata.

---

## 📁 File List

- `Sentiment_analysis.ipynb`: Main notebook
- `Train_test_split_distribution.png`: Data distribution plots
- `model_evaluation_curves.png`: Evaluation charts

---

## ✍️ Author

Lanin Chowdhury  
Data Science Portfolio Project
