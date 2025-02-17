Full Feature Set (22 Features) 

This folder contains the implementation of 11 machine learning models trained on the full set of 22 features to classify fatty liver disease into different stages.

🔍 Feature Set (22 Features)

The dataset includes 22 clinical and laboratory features, which were selected based on their medical significance in diagnosing fatty liver disease:

✔ Demographic & Basic Health Metrics:

Age, BMI, Gender

✔ Lipid Profile & Liver Enzymes:

Cholesterol, Triglycerides, ALT, AST, AST/ALT Ratio

✔ Blood & Metabolic Indicators:

Fasting Blood Glucose, Total Bilirubin, Alkaline Phosphatase, Albumin, Ferritin, Vitamin D

✔ Cardiovascular & Iron Metabolism Markers:

LDL-C, TIBC, Diabetes Status

✔ Blood Cell Counts & Coagulation Markers:

Hemoglobin, White Blood Cell Count, Platelets, INR, Creatinine

🏆 Machine Learning Models Used

The following 11 models were trained using the full feature set:

✅ Single models:

Decision Tree

Random Forest (RF)

Support Vector Machine (SVM)

xgboost (XGB)

Multi-Layer Perceptron (MLP)

✅ Hybrid models (Ensemble Methods):

SVM + Random Forest

Random Forest + xgboost

xgboost + SVM

🛠 Model Evaluation & Next Steps

Accuracy and performance metrics were compared to identify the top-performing models.

The best three models were later retrained using feature selection (7 and 4 most important features).

🚀 This phase establishes a benchmark performance using all available features before applying feature selection and optimization.

