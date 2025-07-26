# Heart Disease Prediction Using Machine Learning

This repository presents a machine learning project aimed at predicting the presence of heart disease in patients based on clinical features. It compares multiple classification models and evaluates their performance to determine the most accurate algorithm.

## Project Objective

To develop and evaluate supervised learning models that can effectively classify whether a patient is likely to suffer from heart disease, based on health-related features.


## Dataset Information

The dataset used contains 14 clinical attributes and one target variable indicating the presence (1) or absence (0) of heart disease.

**Attributes include:**
- Age
- Sex
- Chest Pain Type (cp)
- Resting Blood Pressure (trestbps)
- Serum Cholesterol (chol)
- Fasting Blood Sugar (fbs)
- Resting ECG (restecg)
- Max Heart Rate (thalach)
- Exercise Induced Angina (exang)
- ST Depression (oldpeak)
- ST Slope (slope)
- Number of Vessels (ca)
- Thalassemia (thal)
- Target (0 or 1)

**Dataset Source**:  
[UCI Machine Learning Repository - Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)

> This dataset is in the public domain and is freely available for educational and research use. Proper attribution is provided above.

## Machine Learning Models Used

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- Naive Bayes

## Evaluation Metrics

Each model is evaluated using:
- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)
- ROC-AUC Curve

## Data Visualization

Data exploration is performed using:
- Correlation Heatmaps
- Countplots & Histograms
- Boxplots for outlier detection
- Pairplots for feature relationships

## Installation & Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Heart-Disease-Prediction-ML.git
   cd Heart-Disease-Prediction-ML
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate      # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch the notebook:
   ```bash
   jupyter notebook Heart_Disease_Prediction_DAM.ipynb
   ```


