💳 Credit Card Fraud Detection using Machine Learning
This project focuses on building a robust machine learning model to detect fraudulent credit card transactions. With the increasing number of digital payments, fraud detection has become a vital application of machine learning in the finance industry. The objective is to accurately classify transactions as legitimate or fraudulent and reduce financial losses due to unauthorized activity.

📊 Dataset
The dataset used is from Kaggle and contains 284,807 credit card transactions by European cardholders, out of which only 492 are fraudulent, making the data highly imbalanced. The features are numerical, obtained through PCA transformation, ensuring privacy and reducing dimensionality.

🧠 Approach
Given the imbalance in the dataset, we used preprocessing techniques like SMOTE (Synthetic Minority Oversampling Technique) to balance the classes. After cleaning and scaling the data, multiple machine learning models were implemented and compared:

Logistic Regression

Decision Tree

Random Forest

XGBoost

Support Vector Machine (SVM)

To enhance model performance, GridSearchCV was used for hyperparameter tuning. The focus was not only on accuracy but also on Recall, Precision, F1-score, and AUC-ROC, as catching fraudulent transactions (True Positives) is more important than overall accuracy.

📈 Results
The best model (e.g., Random Forest/XGBoost) achieved high recall and AUC-ROC, which means it could successfully identify most of the fraudulent transactions with minimal false negatives. Various evaluation plots like the confusion matrix, ROC curve, and precision-recall curve were used to interpret results.

🛠️ Tools & Libraries
Python (Jupyter Notebook)

Pandas, NumPy

Scikit-learn

Imbalanced-learn (SMOTE)

Matplotlib & Seaborn for data visualization

✅ Key Takeaways
Tackled real-world class imbalance in fraud detection

Built interpretable models suitable for production

Focused on reducing false negatives to minimize fraud risk

This project showcases the importance of applying the right preprocessing techniques and evaluation metrics in sensitive domains like financial fraud detection.


