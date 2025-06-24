## 📊 Visualizations

### 1. Distribution of Reviews (Train/Test Splits)
![Train-Test Review Distribution](images/train_test_split_distribution.png)

Distribution of negative and positive reviews over the years for both training and testing datasets.  
A consistent pattern confirms balanced splitting, ensuring reliability in model evaluation.  
Many movies reviewed indicate density clusters near zero, while some generate significant volumes.

---

### 2. Model Evaluation Curves
![Model Evaluation](images/model_evaluation_curves.png)

- **F1 Score**: Test max = 0.87 at threshold 0.45  
- **ROC AUC**: Train = 0.98 | Test = 0.94  
- **PRC**: Train = 0.98 | Test = 0.93  

These plots demonstrate strong classifier performance, with TF-IDF successfully transforming text into vector representations.
