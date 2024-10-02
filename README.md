# 🔍 Credit Card Fraud Detection: Unveiling the Hidden Patterns! 💳

## Project Overview
This project aims to detect credit card fraud using data analysis and machine learning techniques. By analyzing a real-world dataset of credit card transactions, the model uncovers patterns that indicate fraudulent activities.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn

## Dataset
The dataset used for this project is a collection of credit card transactions, including features such as:
- **Time**
- **Amount**
- **V1 to V28** (various features derived from PCA)
- **Class** (indicating fraud or genuine transaction)

## Steps Taken

### Data Loading
- Loaded the credit card transactions dataset using Pandas and examined its structure.

### Data Cleaning
- Handled missing values and normalized the 'Amount' feature for consistent scaling, dropping irrelevant columns.

### Feature Engineering
- **Identifying Features:** Selected key features to train the model, ensuring effective input for the algorithm.

### Data Splitting
- **Training & Testing Sets:** Divided the dataset into training and testing sets using a stratified approach for balanced class distribution.

### Handling Imbalance
- **SMOTE Application:** Implemented SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset, enhancing model training on minority classes.

### Model Training
- **Logistic Regression:** Trained the model on the resampled dataset to classify transactions as fraudulent or genuine.

### Model Evaluation
- **Performance Analysis:** Evaluated the model’s performance using confusion matrices and classification reports, analyzing accuracy, precision, recall, and F1-score.

## Key Learnings
- **Data Preprocessing:** Gained experience in cleaning and preparing data for analysis.
- **Feature Engineering:** Learned the importance of creating relevant features to improve model performance.
- **Model Evaluation:** Hands-on experience with training models and assessing their accuracy.
- **Visualization Skills:** Enhanced skills in data visualization to effectively communicate insights.
