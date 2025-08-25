# 🏦 Credit Risk Modelling

A comprehensive machine learning-powered credit risk assessment application built with Streamlit. This project enables financial institutions to evaluate loan default probability and assign credit scores to potential borrowers.

## 🎯 Features

- **Interactive Web Interface**: User-friendly Streamlit dashboard for real-time risk assessment
- **Advanced ML Models**: Trained using XGBoost and Logistic Regression for accurate predictions
- **Comprehensive Risk Analysis**: Calculates default probability, credit score, and risk rating
- **Data-Driven Insights**: Built on extensive customer, loan, and bureau datasets
- **Real-time Predictions**: Instant risk assessment based on customer inputs

## 🚀 Live Demo

🌐 **[Access the Application](https://credit-risk-modelling-27.streamlit.app/)**

## 📊 Application Interface

The application evaluates the following parameters:

- **Personal Information**: Age, Income
- **Loan Details**: Loan Amount, Tenure, Purpose, Type
- **Credit History**: Credit Utilization Ratio, Delinquency Metrics
- **Financial Profile**: Number of Open Accounts, Residence Type

### Output Metrics:

- **Default Probability**: Percentage likelihood of loan default
- **Credit Score**: Numerical credit assessment
- **Risk Rating**: Categorical risk classification

## 🛠️ Technology Stack

- **Frontend**: Streamlit
- **ML Framework**: scikit-learn, XGBoost
- **Data Processing**: pandas, numpy
- **Visualization**: matplotlib, seaborn
- **Model Handling**: joblib
- **Statistical Analysis**: statsmodels

## 📁 Project Structure

```
Credit Risk Modelling/
├── app/
│   ├── main.py                 # Streamlit web application
│   ├── prediction_helper.py    # ML prediction utilities
│   └── artifacts/
│       └── model_data.joblib   # Trained model and preprocessors
├── artifacts/
│   └── model_data.joblib       # Model backup
├── dataset/
│   ├── bureau_data.csv         # Credit bureau information
│   ├── customers.csv           # Customer demographics
│   └── loans.csv              # Loan transaction data
├── Credit_risk.ipynb          # Model development notebook
├── requirements.txt           # Python dependencies
└── README.md                 # Project documentation
```

## 🚀 Quick Start

### Prerequisites

- Python 3.8+
- pip package manager

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/Abi27052000/Credit-Risk-Modelling.git
   cd Credit-Risk-Modelling
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**

   ```bash
   streamlit run ./main.py
   ```

4. **Access the app**
   Open your browser and navigate to `http://localhost:8501`

## 📈 Model Development

The machine learning pipeline includes:

1. **Data Preprocessing**:

   - Feature engineering and selection
   - Handling missing values and outliers
   - Data scaling and normalization

2. **Model Training**:

   - XGBoost Classifier
   - Logistic Regression
   - Hyperparameter optimization

3. **Model Evaluation**:

   - Cross-validation
   - ROC-AUC analysis
   - Feature importance assessment

4. **Model Deployment**:
   - Streamlit integration
