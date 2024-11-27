# Chronic Kidney Disease Classification

This project focuses on analyzing and classifying Chronic Kidney Disease (CKD) data using machine learning algorithms. The dataset is preprocessed, visualized, and multiple classification models are applied to predict whether a patient has CKD or not.

---

## Table of Contents
- [Dataset Overview](#dataset-overview)
- [Project Purpose](#project-purpose)
- [Data Preprocessing](#data-preprocessing)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Technologies Used](#technologies-used)
- [Key Findings](#key-findings)
- [How to Run](#how-to-run)

---

## Dataset Overview
- **Source:** Chronic Kidney Disease dataset.
- **Columns:** The dataset contains 25 features including:
  - Patient demographics (e.g., Age, Blood Pressure)
  - Lab measurements (e.g., Hemoglobin, Blood Urea)
  - Symptoms (e.g., Anemia, Pedal Edema)
  - Target variable: `Class` (1 = CKD, 0 = Not CKD)

---

## Project Purpose
1. **Data Cleaning:** Handle missing values and inconsistent data.
2. **Visualization:** Explore relationships among features using heatmaps and plots.
3. **Classification:** Apply machine learning models to classify CKD status.

---

## Data Preprocessing
- Converted categorical variables into numeric values for model compatibility.
- Imputed missing values using mean and mode methods.
- Performed data standardization where necessary.
- Correlation analysis to identify important features.

---

## Model Training and Evaluation
Applied the following machine learning algorithms:
- **Decision Tree**
- **Random Forest**
- **K-Nearest Neighbors (KNN)**
- **Naive Bayes**
- **Support Vector Machine (SVM)**

### Metrics Used:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **Confusion Matrix**

---

## Technologies Used
- **Programming Language:** Python
- **Libraries:** 
  - Pandas, NumPy (Data Analysis)
  - Seaborn, Matplotlib (Visualization)
  - Scikit-learn (Machine Learning)

---

## Key Findings
- Decision Tree and Random Forest showed high accuracy in predicting CKD status.
- Correlation analysis helped identify features highly related to CKD, improving model performance.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
