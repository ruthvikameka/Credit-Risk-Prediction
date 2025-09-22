# Credit Risk Prediction 

This repository contains a complete end-to-end credit risk classification pipeline implemented in `MAIN.ipynb`. It walks through data loading, exploratory data analysis (EDA), preprocessing, model training and evaluation. The model includes commonly used ML algorithms such as Logistic Regression, Random Forest, XGBoost, LightGBM, AdaBoost, Neural Networks, etc.

---

## 📁 Repository Structure
├── MAIN.ipynb # Main Jupyter notebook with EDA, preprocessing & ML pipeline

├── .CSV file/ # Placeholder for input datasets (CSV, Excel, etc.)   

└── README.md # Project overview and instructions


---

## ✅ Features

- **Data Loading & EDA**: Summary statistics, missing values, correlations, distributions, class imbalance insights  
- **Preprocessing**: Encoding categorical features, scaling numerical values, handling missing data, balancing (SMOTE, etc.)  
- **Feature Engineering & Selection**: Correlation analysis and feature importance visualizations  
- **Model Training**: Compare models such as Logistic Regression, Random Forest, XGBoost, LightGBM, AdaBoost, Neural Networks  
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score, ROC-AUC, Matthews Correlation Coefficient (MCC)  
- **Best-model selection**: Based on model performance consistency and interpretability  
- **Visual Analysis**: Confusion matrix, ROC curves, SHAP or feature importance plots  

---

## 💻 Installation & Setup

1. **Clone the repository**  
   ```bash
   git clone https://github.com/ruthvikameka/Credit-Risk-Prediction.git
   cd Credit-Risk-Prediction
2.**Install dependencies**
It should contain standard ML dependencies like pandas, numpy, scikit-learn, xgboost.
  pip install -r requirements.txt




  
3.**Place your dataset**

place your in the data/ folder (e.g. credit_data.csv), matching the loading path in the notebook.

4.**Launch the notebook**

 ``bash
 jupyter notebook MAIN.ipynb

Or use Google Colab by uploading the notebook there.

