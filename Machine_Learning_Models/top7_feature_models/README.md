Top 3 Models with 7 Selected Features 

This folder contains the implementation of the top 3 machine learning models trained on the 7 most important features selected using Permutation Importance.

🔍 Feature Selection Process

Feature selection is a crucial step in machine learning, reducing data dimensionality, preventing unnecessary complexity, and improving model efficiency. In this study, Permutation Importance was applied to all models to determine which features had the highest impact on model performance.

✅ Permutation Importance Method:

1-The permutation_importance function from Scikit-learn was used to measure how much each feature affects the model’s accuracy.

2-Features were ranked based on their importance across all models.

3-The 7 most significant features identified were:

BMI

Triglycerides

Fasting Blood Glucose

Ferritin

Platelets

Alkaline Phosphatase

Creatinine & INR

🏆 Top 3 Selected Models

The three best-performing models from the initial phase (trained on all features) were selected:

✔ MLP (Multi-Layer Perceptron)

✔ XGBoost-SVM (Hybrid of XGBoost and Support Vector Machine)

✔ Random Forest

These models were retrained using only the 7 most important features, ensuring better generalization and reduced computational complexity.
