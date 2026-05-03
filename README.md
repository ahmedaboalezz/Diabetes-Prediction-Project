

## 📌 Project Overview
This project aims to predict the likelihood of diabetes in patients based on specific health metrics. By leveraging a dataset from **Kaggle**, I performed a complete Data Science workflow, from Exploratory Data Analysis (EDA) and Preprocessing to building and evaluating multiple Machine Learning models.

## 📊 Dataset Features
The dataset includes several medical predictor variables and one target variable (`Outcome`):
*   **Pregnancies**: Number of times pregnant.
*   **Glucose**: Plasma glucose concentration.
*   **BloodPressure**: Diastolic blood pressure (mm Hg).
*   **BMI**: Body mass index.
*   **Age**: Patient's age.
*   ...and more.

## 🛠️ Workflow

### 1. Exploratory Data Analysis (EDA)
*   Analyzed data distributions using **Histograms** and **Boxplots**.
*   Explored feature relationships using a **Correlation Heatmap**.
*   Identified key factors influencing diabetes (e.g., Glucose and BMI).

### 2. Data Preprocessing
*   Handled missing/zero values in critical columns.
*   Feature scaling to ensure balanced model training.
*   Train-Test split for unbiased evaluation.

### 3. Machine Learning Modeling
I implemented and compared four different classification algorithms:
1.  **Logistic Regression**
2.  **Support Vector Classifier (SVC)**
3.  **Random Forest Classifier**
4.  **Gradient Boosting Classifier**

## 📈 Performance Evaluation
The models were evaluated using multiple metrics to ensure reliability in a medical context:
*   **Accuracy**: Overall correctness.
*   **Recall**: Ability to identify all positive cases (Crucial for healthcare).
*   **F1-Score**: The harmonic mean of Precision and Recall.

| Algorithm | Accuracy | Recall | F1-Score |
| :--- | :---: | :---: | :---: |
| Logistic Regression | 0.74 | 0.65 | 0.64 |
| SVC | 0.74 | 0.65 | 0.64 |
| Random Forest | 0.74 | 0.65 | 0.64 |
| Gradient Boosting | 0.74 | 0.65 | 0.64 |

> *Note: Performance metrics based on current model iteration.*

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/YourUsername/diabetes-prediction.git](https://github.com/YourUsername/diabetes-prediction.git)
