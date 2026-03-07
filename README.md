# Insurance Fraud Detection System

A Machine Learning based web application that predicts whether an **insurance claim is fraudulent or legitimate** based on multiple parameters. The system uses data preprocessing, feature engineering, and classification models to identify suspicious claims and help insurance companies reduce financial losses.

---

# Project Overview

Insurance fraud is a significant challenge for insurance companies, causing large financial losses every year. Fraud occurs when a claimant intentionally provides false information to obtain benefits they are not entitled to.

This project aims to **detect fraudulent insurance claims using machine learning algorithms** and provide a **web interface** where users can input claim details and receive predictions instantly.

The system analyzes multiple attributes related to policy details, customer information, and incident data to determine whether a claim is **Fraudulent or Legitimate**.

---

# Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature encoding and scaling
- Multiple Machine Learning models comparison
- Fraud prediction using trained model
- Flask web application for user interaction
- Real-time prediction through UI

---

# Technologies Used

### Programming Language

- Python

### Libraries

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Pickle

### Web Framework

- Flask

### Frontend

- HTML
- CSS

---

# Machine Learning Models Used

The following models were implemented and compared:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Naive Bayes
- Decision Tree
- Random Forest

The **Decision Tree Classifier** was selected as the final model due to its good performance.

---

# Project Structure

```
Insurance-Fraud-Detection
│
├── FraudDetectionModel.ipynb
├── app.py
├── dtc_model.pkl
├── Std_Scaler.pkl
│
├── templates
│   └── index.html
│
├── dataset
│   └── insurance_fraud_dataset.csv
│
└── README.md
```

---

# Dataset Information

The dataset contains insurance claim details such as:

- Customer information
- Policy details
- Incident details
- Claim amounts
- Vehicle information

Target variable:

```
fraud_reported
```

- 0 → Legitimate Claim
- 1 → Fraudulent Claim

---

# Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Handling Missing Values
4. Exploratory Data Analysis
5. Encoding Categorical Features
6. Feature Scaling
7. Train-Test Split
8. Model Training
9. Model Evaluation
10. Model Deployment using Flask

---

# Installation & Setup

### Clone the repository

```
git clone https://github.com/YOUR_GITHUB_USERNAME/Insurance-Fraud-Detection.git
```

### Navigate to the project directory

```
cd Insurance-Fraud-Detection
```

### Install dependencies

```
pip install -r requirements.txt
```

### Run the Flask Application

```
python app.py
```

### Open Browser

```
http://127.0.0.1:5000
```

---

# Example Prediction

Input claim parameters through the web interface and the system predicts:

```
Legal Insurance Claim
or
Fraud Insurance Claim
```

---

# Future Improvements

- Use Deep Learning models
- Add API integration
- Improve UI/UX
- Deploy using Docker
- Deploy on cloud platforms (AWS / Render)

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
