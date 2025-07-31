Mobile-price-prediction
Predict smartphone price ranges using machine learning algorithms (SVM, Decision Tree, KNN, Naive Bayes) with feature selection.

Overview
This project predicts the price range of smartphones (Low, Medium, High, Very High) based on hardware features like RAM, battery power, and screen resolution. It uses various machine learning algorithms and compares their performance to identify the most accurate model.

Objective
To build a machine learning model that classifies smartphones into price categories using selected features, helping:
- Customers make smarter buying decisions
- Businesses optimize pricing strategies

Technologies Used
- Python
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn

Feature Selection
From the 20 features, the top 4 were selected based on correlation:
- `ram`
- `battery_power`
- `px_width`
- `px_height`

 ML Algorithms Used
- Support Vector Machine (SVM)
- Decision Tree
- K-Nearest Neighbors (KNN)
- Naive Bayes

---

Evaluation Metrics

| Model                | Accuracy | Precision | Recall | F1 Score |
|---------------------|----------|-----------|--------|----------|
| **SVM**             | **87%**  | **87%**   | **87%**| **87%**  |
| Decision Tree       | 79%      | 79%       | 79%    | 79%      |
| K-Nearest Neighbors | 51%      | 54%       | 51%    | 52%      |
| Naive Bayes         | 80%      | 80%       | 80%    | 80%      |

SVM showed the highest performance and was selected as the best model.


Dataset Source:[Mobile Price Classification Dataset on Kaggle](https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification)
