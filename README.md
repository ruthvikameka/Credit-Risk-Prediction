# Credit Risk Prediction 

This repository contains a complete end-to-end credit risk classification pipeline implemented in `MAIN.ipynb`. It walks through data loading, exploratory data analysis (EDA), preprocessing, model training and evaluation. The models included are commonly used ML algorithms such as Logistic Regression, Random Forest, XGBoost, LightGBM, AdaBoost, Neural Networks, etc.

---

## 📁 Repository Structure

.
├── MAIN.ipynb # Main Jupyter notebook with EDA, preprocessing & ML pipeline
├── .CSV file/ # Placeholder for input datasets (CSV, Excel, etc.)
└── README.md # Project overview and instructions

yaml
Copy code

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
Install dependencies
It should contain standard ML dependencies like pandas, numpy, scikit-learn, xgboost, lightgbm, imbalanced-learn, and shap.

bash
Copy code
pip install -r requirements.txt
Place your dataset in the data/ folder (e.g. credit_data.csv), matching the loading path in the notebook.

Launch the notebook

bash
Copy code
jupyter notebook MAIN.ipynb
Or use Google Colab by uploading the notebook there.

🧪 Usage
Data Exploration

Inspect dataset balance, numeric distribution, and correlations

Feature Processing & Balance

Encode categorical variables

Scale numeric features

Apply resampling (e.g. SMOTE to address class imbalance)

Model Training & Tuning

Train and evaluate multiple classifiers (logistic regression, tree-based, boosted, neural networks)

Evaluate

Compare using metrics (ACCURACY, PRECISION, RECALL, F1, ROC-AUC, MCC)

Visualize performance (ROC curve, confusion matrix, feature importance)

Model Interpretation

Use SHAP or feature importances to investigate crucial predictors

🧭 Insights from Literature
Studies show that XGBoost and LightGBM often outperform other models in credit risk tasks, sometimes achieving up to 99% accuracy and very high AUC scores.

Feature importance is frequently driven by demographic variables such as age, income, employment months, and family members.

Model evaluation should include robust metrics like ROC-AUC and Matthews Correlation Coefficient (MCC), especially in imbalanced settings.

📌 Future Enhancements
Integrate explainable AI tools such as SHAP or LIME for improved interpretability

Use hyperparameter tuning (GridSearchCV, RandomizedSearchCV)

Extend to deep learning frameworks (Keras or PyTorch), or recent architectures like interpretable neural networks

Validate model robustness over time using multiple time-split datasets

Deploy best model via sample web app or API endpoint

📄 References
“Credit Risk Prediction Using Machine Learning and Deep Learning” – highlights importance of boosted methods such as XGBoost, demographic features, and performance metrics.

Literature reviews on credit risk ML methods and feature usage, with emphasis on algorithm families and imbalance handling.
