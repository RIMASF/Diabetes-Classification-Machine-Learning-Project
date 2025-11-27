# 🩺 Diabetes Classification ML Project

A machine learning project for classifying patients into Diabetic, Non-Diabetic, and Predict-Diabetic categories based on medical indicators. The system includes full data preprocessing and a Decision Tree model trained for accurate medical risk assessment.

## ✨ Features
- **Data Cleaning** – Handling missing values and duplicates
- **Categorical Encoding** – Standardizing Gender and Class fields  
- **Stratified Splitting** – Balanced Train/Validation/Test sets
- **Decision Tree Model** – Tuned to reduce overfitting
- **High Accuracy** – Achieved 0.98 accuracy on test data

## 🛠️ Technologies
- Python
- Pandas / NumPy
- Scikit-Learn
- Jupyter Notebook

## 📁 Files
- `Data Preparation.ipynb` – Preprocessing workflow
- `Training_Evaluation.ipynb` – Model training and testing
- `DatasetDiabetes.csv` – Original dataset
- `X_train.csv` / `y_train.csv` – Training data
- `X_test.csv` / `y_test.csv` – Testing data

## 🚀 How It Works

### Data Preparation:
1. Loads dataset
2. Cleans missing values  
3. Encodes categorical fields
4. Splits into Training / Validation / Testing sets
5. Saves processed files

### Model Training:
1. Builds Decision Tree with max_depth=5
2. Evaluates performance using Accuracy + Confusion Matrix
3. Produces final predictions and visualization

## 📊 Model Output
- **Accuracy**: 0.98
- **Confusion Matrix**: Correct predictions across all 3 classes
- **Key Features**: HbA1c, BMI, Cholesterol levels

## 👥 Medical Applications
- Early diabetes detection
- Risk stratification for patients
- Clinical decision support system
- Preventive healthcare monitoring

---

**Dataset**: 1,000 patient records with 13 medical features  
**Target**: 3-class classification (Diabetic/Predict-Diabetic/Non-Diabetic)  
**Status**: ✅ Ready for deployment and clinical validation
