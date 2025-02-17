# Fatty-liver-grading
Machine learning-based classification of fatty liver disease into five grades using clinical and laboratory data. The best-performing model is selected through a feature selection process.

🔹 Project Objective:
This project focuses on automated grading of fatty liver disease using machine learning algorithms. The dataset consists of clinical and laboratory features from patients, aiming to classify them into different grades of fatty liver disease.

📂 Project Structure:

🔹 EDA/ → Exploratory data analysis (EDA) of the dataset.

🔹 Data_Augmentation/ → Data preprocessing and augmentation technique.

🔹 Machine_Learning_Models/ → Includes three phases of model training:

1-Training 11 machine learning models using all available features.

2-Selecting the top 3 models and training them on the 7 most important features.

3-Training the top 3 models on the 4 most important features (excluding class 4).

🩺 Fatty Liver Disease Classes
The classification system assigns patients into five categories (Class 0 to Class 4):

Class 0 → Healthy individuals.

Class 1 → Patients with mild (Grade 1) fatty liver disease.

Class 2 → Patients with moderate (Grade 2) fatty liver disease.

Class 3 → Patients with severe (Grade 3) fatty liver disease.

Class 4 → Final stage (Grade 4) fatty liver disease.

The goal of this project is to develop a robust model capable of accurately predicting fatty liver disease severity based on clinical and laboratory data.
