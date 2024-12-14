# Diabetes_Prediction
This project implements and compares three different machine learning models for diabetes classification.
- Decision Tree Classifier
- Multi-layer Perceptron (MLP) Classifier
- XGBoost Classifier

# Dataset Features
- Age: Age of the patient
- Gender: Gender of the patient (Male/Female)
- Polyuria: Excessive urination (Yes/No)
- Polydipsia: Excessive thirst (Yes/No)
- Sudden weight loss: Sudden weight loss (Yes/No)
- Weakness: General weakness (Yes/No)
- Polyphagia: Excessive hunger (Yes/No)
- Genital thrush: Genital thrush (Yes/No)
- Visual blurring: Visual blurring (Yes/No)
- Itching: Itching (Yes/No)
- Irritability: Irritability (Yes/No)
- Delayed healing: Delayed healing of wounds (Yes/No)
- Partial paresis: Partial paresis (Yes/No)
- Muscle stiffness: Muscle stiffness (Yes/No)
- Alopecia: Hair loss (Yes/No)
- Obesity: Obesity (Yes/No)
- Class: Diabetes class (Positive/Negative)

# Data Preprocessing
- Label encoding for categorical variables
- Train-test split (70-30)
- Feature scaling

# Models Configuration
1. Decision Tree Classifier
   - Random state: 42
2. MLP Classifier
   - Hidden layers: (100, 50)
   - Maximum iterations: 1000
   - Activation: ReLU
   - Solver: Adam
   - Random state: 42
3. XGBoost Classifier
   - Number of estimators: 100
   - Learning rate: 0.1
   - Maximum depth: 4
   - Random state: 42

# Model Evaluation
- Accuracy Score
- AUC-ROC Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)

# Visualisation
- Correlation matrix heatmap showing feature relationships
- Confusion matrices for each model
- Combined ROC curves for model comparison
