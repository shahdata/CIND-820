# CIND-820
CIND820 Insurance Fraud Data Analysis Final Project
Project Overview
Insurance fraud detection is a challenging machine learning problem due to the highly imbalanced nature of insurance claim datasets, where fraudulent claims represent only a small portion of total claims.
This project develops and evaluates machine learning models to predict fraudulent insurance claims using historical claim data. The project covers the complete machine learning workflow, including:
- Exploratory Data Analysis (EDA)
- Data preprocessing and feature engineering
- Feature selection and statistical analysis
- Machine learning model development
- Handling class imbalance using SMOTE
- Model evaluation and comparison

The goal of this project is to determine how effectively machine learning algorithms can identify fraudulent claims based on customer, policy, vehicle, and accident-related information.

---

# Dataset

The dataset contains automobile insurance claim records with features related to:

- Customer demographics
- Policy information
- Vehicle characteristics
- Accident details
- Claim history

The target variable is:
- FraudFound


CIND-820/
│
├── README.md
│
├── Dataset/
│ └── claims_oracle.csv
│
├── Notebooks/
│ ├─ CIND820Initalcoding.ipynb
│
└── Reports/
└── Project_Report.pdf 

# How to Run the Project

## 1. Clone Repository
```bash
git clone https://github.com/shahdata/CIND-820.git

2. Navigate into the project folder:
cd CIND-820

3. Install required Python libraries
4. Open Jupyter Notebook:
jupyter notebook

Requirements

Create an environment with:
pandas
numpy
matplotlib
seaborn
scikit-learn
imbalanced-learn
scipy
jupyter

Future Improvements
Future enhancements include:
Random Forest and XGBoost models
Hyperparameter optimization
Advanced feature engineering
Cost-sensitive learning
Explainable AI using SHAP/LIME
Real-time fraud prediction deployment


