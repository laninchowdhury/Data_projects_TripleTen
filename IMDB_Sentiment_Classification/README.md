
# IMDB Sentiment Classification

This project analyzes IMDB movie reviews to classify sentiment (positive or negative) using natural language processing and machine learning techniques.

## 🎯 Objective
Build a reliable sentiment classification model with high F1 score, using TF-IDF and logistic regression.

## 🧰 Tools & Technologies
- Python, pandas, NumPy
- scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- matplotlib, seaborn

## 🔍 Process Overview
1. **Data Preprocessing** – Cleaned text, removed noise.
2. **EDA** – Visualized polarity distribution over time.
3. **Vectorization** – Used TF-IDF to convert text to features.
4. **Modeling** – Trained logistic regression.
5. **Evaluation** – Assessed using F1 Score, ROC AUC, PRC.

## 📊 Visualizations

![Train/Test Distribution](images/Train_test_split_distribution.png)

![Model Evaluation Curves](images/model_evaluation_curves.png)

## ✅ Results
- **Accuracy**: 0.86
- **Test F1 Score**: 0.87
- **ROC AUC**: 0.94
- TF-IDF vectorization effectively captured sentiment signals.
- Balanced train-test split ensured robust evaluation.

## 📁 Files
- `Sentiment_analysis.ipynb`: Main notebook with full analysis.
- `images/`: Contains visual charts used in the report.

---

