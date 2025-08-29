# Credit-Card-Fraud-Detection
# Credit Card Fraud Detection

This project applies **Machine Learning** techniques to detect fraudulent credit card transactions.  

## 📌 Features
- Exploratory Data Analysis (EDA) of transaction patterns  
- Handling **imbalanced dataset** with fraud cases (~0.02%)  
- Training a **Random Forest Classifier**  
- Evaluation using accuracy, precision, recall, F1-score, and MCC  
- Confusion Matrix visualization  

## ⚙️ Technologies Used
- Python (NumPy, Pandas, Matplotlib, Seaborn)  
- Scikit-learn (RandomForestClassifier, metrics)  

## 🚀 Results
- **Accuracy:** ~99.9% (note: accuracy is misleading in imbalanced datasets)  
- **Precision:** ~98%  
- **Recall:** ~79%  
- **F1-score:** ~88%  
- **MCC:** ~0.88  

## 📂 Dataset
The dataset contains **284,807 transactions** with 31 features:  
- `Time`, `Amount`  
- `V1` to `V28` (anonymized PCA features)  
- `Class` (0 = normal, 1 = fraud)  

---

