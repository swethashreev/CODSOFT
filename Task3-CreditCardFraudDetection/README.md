# Description

Built a Machine Learning model to identify fraudulent credit card transactions based on anonymized transaction features and amount.

# Dataset

- creditcard.csv
- 284,807 transactions
- 31 features (Time, Amount, V1–V28, Class)
- Highly imbalanced: 492 fraud cases (0.17%)

# Tools & Libraries Used

- Python
- Google Colab
- Pandas
- Scikit-learn
- Imbalanced-learn (SMOTE)

# Algorithm Used

- Random Forest Classifier

# Steps Involved

1. Data Collection
2. Data Preprocessing (Normalization of Time and Amount)
3. Train-Test Split (Stratified)
4. Handling Class Imbalance using SMOTE
5. Model Training
6. Model Evaluation

# Result

- Precision: 0.85
- Recall: 0.84
- F1-Score: 0.84
- Successfully identified fraudulent transactions despite extreme class imbalance
