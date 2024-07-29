# Credit-Card-Fraud-Detection-Using-Transactions-Data
This project focuses on detecting fraudulent credit card transactions using advanced machine-learning techniques. By leveraging various classification models, including Logistic Regression, Linear Discriminant Analysis (LDA), and Gaussian Naive Bayes (GNB), this project aims to identify potentially fraudulent activities with high accuracy.

## Key Components:

### Data Preparation:
#### Data Loading: 
Imported and explored the dataset to understand its structure and characteristics.
#### Preprocessing: 
Applied normalization techniques to preprocess the data for effective model training.
#### Resampling: 
Utilized SMOTE for balancing the dataset to address the class imbalance.

### Model Building:
#### Train-Test Split: 
Divided the dataset into training and testing sets (80% training, 20% testing) to ensure robust model evaluation.
#### Logistic Regression: 
Implemented and evaluated the Logistic Regression model using 10-fold cross-validation, achieving a mean score of 0.9536.
#### Linear Discriminant Analysis (LDA): 
Applied LDA for classification and assessed its performance with a mean score of 0.9259.
#### Gaussian Naive Bayes (GNB): 
Evaluated the GNB model, which achieved a mean score of 0.9035.

### Model Evaluation:
#### Accuracy and Metrics: 
Evaluated the best-performing model (Logistic Regression) using accuracy score, confusion matrix, and classification report, resulting in an accuracy of 0.95.
#### Final Prediction: 
Tested the model on sample data to classify transactions as either fraudulent or normal.

### Technologies Used:
Python, 
Scikit-learn, 
Pandas, 
NumPy
