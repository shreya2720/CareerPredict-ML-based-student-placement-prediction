# CareerPredict — ML-Based Student Placement Prediction

## 📌 Overview

CareerPredict is a machine learning project that predicts whether a student is likely to be placed based on academic performance, aptitude, internships, projects, soft skills, and other placement-related factors.

## 🎯 Objective

The objective of this project is to build a machine learning classification model that can predict student placement outcomes using historical student data.

## 📊 Dataset

The dataset contains student academic and placement-related information.

### Features

- CGPA
- Internships
- Projects
- Workshops/Certifications
- Aptitude Test Score
- Soft Skills Rating
- Extracurricular Activities
- Placement Training
- SSC Marks
- HSC Marks

### Target

- `0` → Not Placed
- `1` → Placed

## 🤖 Machine Learning Models

The following classification algorithms were evaluated:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Tuned Random Forest

## 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 69.0% | 69.6% | 78.4% | 73.7% |
| Decision Tree | 62.5% | 68.8% | 59.5% | 63.8% |
| **Random Forest** | **73.0%** | **71.8%** | **84.7%** | **77.7%** |
| Tuned Random Forest | 72.0% | 71.0% | 83.8% | 76.9% |

### Final Model

Random Forest was selected as the final model because it achieved the highest test accuracy of **73%** among the evaluated models.

The model's 5-fold cross-validation accuracy was approximately **63.1%**.

## 🔍 Important Features

The Random Forest model identified the following as the most influential features:

1. CGPA
2. Aptitude Test Score
3. Internships
4. HSC Marks
5. Soft Skills Rating

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Joblib

## 📁 Project Files

- `Student_Placement_Prediction_ML (1).ipynb` — Complete machine learning workflow
- `student_placement_model.pkl` — Trained Random Forest model

## ⚠️ Note

The model is intended for educational and analytical purposes. Predictions should not be treated as guaranteed placement outcomes.

## 👩‍💻 Author

Shreya Patra
