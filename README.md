
# Parkinson’s Disease Detection using Machine Learning

This project applies machine learning models to detect Parkinson's Disease using biomedical voice measurements.

## 🔍 Problem Statement
Parkinson’s Disease is a progressive neurological disorder that affects speech and motor function. Early diagnosis is crucial but challenging. This project explores machine learning techniques to support early detection based on voice data.

## 📁 Dataset
- Source: [UCI Machine Learning Repository – Parkinson’s Dataset](https://archive.ics.uci.edu/ml/datasets/parkinsons)
- The dataset includes biomedical voice measurements from 31 individuals, 23 of whom are diagnosed with Parkinson’s Disease.

## ⚙️ Features Used
- **Frequency Measures**: MDVP:Fo(Hz), MDVP:Fhi(Hz), MDVP:Flo(Hz)
- **Signal Variation**: Jitter, Shimmer
- **Noise Ratios**: NHR, HNR
- **Nonlinear Measures**: RPDE, DFA, PPE

## 🧠 Models Applied
- **Logistic Regression**
- **Random Forest**
- **Support Vector Machine (SVM)**

## ✅ Evaluation
- Evaluation Metric: `accuracy_score`
- Best Model: **SVM**
- **Highest Accuracy Achieved**: **87.1%**

## 📓 Notebook
See the full implementation here: [`Parkinson_Detection.ipynb`](Parkinson_Detection.ipynb)

## 🚀 Future Work
- Extend dataset with sensor or handwriting data
- Explore hyperparameter tuning and ensemble stacking
- Deploy the model with a Streamlit web interface

## 👩‍💻 Author
**Fahmida Faiza**  
[GitHub Profile](https://github.com/Fahmida10)
