# 🧠 Parkinson's Disease Prediction

A machine learning project that predicts Parkinson's disease from biomedical voice measurements using the UCI Dataset.

## 📊 Dataset
- **Source:** UCI Parkinson's Disease Dataset
- **Samples:** 195 patients
- **Features:** 22 biomedical voice measurements
- **Target:** 1 = Parkinson's, 0 = Healthy

## 🤖 Models Compared
| Model | Accuracy |
|-------|----------|
| Random Forest | **94.87%** |
| Support Vector Machine | 89.74% |
| Logistic Regression | 89.74% |

## 📈 Best Model Results (Random Forest)
- **Accuracy:** 94.87%
- **ROC-AUC Score:** 0.91
- **F1 Score:** 0.97

## 🛠️ Libraries Used
- Python, NumPy, Pandas
- Scikit-learn, Matplotlib, Seaborn

## 📁 Project Structure
```
├── parkinsons.ipynb       # Main notebook
├── parkinsons.csv         # Dataset
└── parkinsons_results.png # Visualizations
```

## 🔍 Key Steps
1. Data Loading and Exploration
2. Feature Engineering and Scaling (StandardScaler)
3. Model Training and Comparison
4. Evaluation using Accuracy, ROC-AUC, F1 Score
5. Visualization of Results
