# Credit-card-fraud-detection
This project builds a classification model to detect fraudulent credit card transactions using machine learning techniques. The focus is on minimizing false positives while maintaining high accuracy and addressing class imbalance using oversampling (SMOTE).
📂 Dataset
Source: creditcard.csv

Features include:

Time and Amount (preprocessed with StandardScaler)

Anonymized PCA components (V1 to V28)

Class: 0 for legitimate, 1 for fraud

🛠 Features
Data Preprocessing:

Scaling of Amount and Time

Removal of missing values

Class Imbalance Handling:

Synthetic Minority Oversampling Technique (SMOTE)

Feature Engineering Ideas (optional extensions):

Spending patterns

Transaction frequency

Location mismatch

Model Used:

Random Forest Classifier

Evaluation Metrics:

Confusion Matrix

Classification Report (Precision, Recall, F1-score)

ROC-AUC Score and Curve

📊 Visualizations
Confusion Matrix Heatmap

ROC Curve

(You can add more: class distribution, feature importance, etc.)

🧪 Results
ROC AUC Score: ~0.99 (varies slightly depending on train-test split)

High Recall on fraudulent transactions

Low False Positive Rate due to careful resampling and model tuning
