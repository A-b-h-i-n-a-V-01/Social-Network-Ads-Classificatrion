# Social Network Ads Classification

## Overview

This machine learning project predicts whether a user will purchase a product based on demographic information such as age, gender, and estimated salary.

The project demonstrates a complete classification workflow, including data preprocessing, feature encoding, feature scaling, model training, and performance evaluation using multiple machine learning algorithms.

---

## Dataset Features

| Feature | Description |
|----------|-------------|
| Gender | User gender |
| Age | User age |
| EstimatedSalary | User estimated salary |
| Purchased | Target variable (0 = No, 1 = Yes) |

---

## Project Workflow

1. Load and explore the dataset
2. Remove unnecessary features (User ID)
3. Handle categorical variables using One-Hot Encoding
4. Perform train-test split
5. Train classification models
6. Apply Min-Max Scaling on numerical features
7. Retrain models on scaled data
8. Compare model performance

---

## Machine Learning Models Used

### Logistic Regression
- Baseline classification model
- Evaluated before and after feature scaling

### K-Nearest Neighbors (KNN)
- Tested multiple K values
- Selected optimal K based on accuracy score

### Support Vector Machine (SVM)
- Linear Kernel
- Polynomial Kernel
- RBF Kernel

### Decision Tree Classifier
- Entropy criterion

### Random Forest Classifier
- Ensemble learning approach

---

## Evaluation Metrics

The models were evaluated using:

- Accuracy Score
- Precision Score
- Recall Score
- F1 Score
- Confusion Matrix

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn

---

## Libraries

```bash
pip install numpy pandas matplotlib scikit-learn
```

---

## Project Structure

```
social-network-ads-classification/
│
├── day3_classification.py
├── Social_Network_Ads.csv
├── README.md
```

---

## Learning Outcomes

- Data preprocessing techniques
- One-Hot Encoding
- Feature Scaling
- Classification Algorithms
- Model Evaluation
- Hyperparameter Selection
- Comparing Multiple Models

---

## Author

**Abhinav Krishna C S**
