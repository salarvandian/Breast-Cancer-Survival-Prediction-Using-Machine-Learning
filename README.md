# Breast-Cancer-Survival-Prediction-Using-Machine-Learning
This project aims to predict whether a breast cancer patient will survive after surgery by analyzing various clinical and biological features. It uses machine learning techniques, specifically the Support Vector Classifier (SVC), to classify patients into "Alive" or "Dead" categories based on their medical data.

# Breast Cancer Survival Prediction

## Overview
This project focuses on predicting the survival status of breast cancer patients after surgery using machine learning. The dataset includes clinical and biological features such as age, gender, protein levels, tumor stage, histology, ER/PR/HER2 status, and surgery type. A Support Vector Classifier (SVC) model is trained to make predictions.

## Dataset
The dataset used in this project contains the following features:
- **Patient_ID**: Unique identifier for each patient.
- **Age**: Age of the patient.
- **Gender**: Gender of the patient (0: Female, 1: Male).
- **Protein1, Protein2, Protein3, Protein4**: Protein expression levels.
- **Tumor_Stage**: Stage of the tumor (0: Stage I, 1: Stage II, 2: Stage III).
- **Histology**: Histological type of the tumor.
- **ER status**: Estrogen receptor status (0: Negative, 1: Positive).
- **PR status**: Progesterone receptor status (0: Negative, 1: Positive).
- **HER2 status**: HER2 receptor status (0: Negative, 1: Positive).
- **Surgery_type**: Type of surgery performed.
- **Date_of_Surgery**: Date of surgery.
- **Date_of_Last_Visit**: Date of the last visit.
- **Patient_Status**: Survival status of the patient (0: Dead, 1: Alive).

## Key Steps
1. **Data Preprocessing**: 
   - Handling missing values.
   - Encoding categorical variables.
   - Converting date columns to datetime format.
2. **Exploratory Data Analysis (EDA)**:
   - Visualizing distributions of key features using pie charts.
   - Analyzing correlations between features.
3. **Model Training**:
   - Splitting the dataset into training and testing sets.
   - Training a Support Vector Classifier (SVC) model.
4. **Prediction**:
   - Making predictions on new data points.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/breast-cancer-survival-prediction.git
