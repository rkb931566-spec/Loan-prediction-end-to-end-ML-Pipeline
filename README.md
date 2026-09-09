# End-to-End ML Pipeline for Loan Prediction

## 📌 Problem Statement
The goal of this project is to predict whether a loan application will be approved or not based on applicant details such as income, credit history, loan amount, and other demographic features.

---

## 🧠 What I Built
I developed a complete end-to-end machine learning pipeline that covers the full lifecycle of an ML system:

- Data ingestion
- Data preprocessing and cleaning
- Feature engineering
- Model training and hyperparameter tuning
- Model evaluation and selection
- Experiment tracking
- Model deployment using Docker and FastAPI

---

## 📊 Dataset
- Source: Analytics Vidhya Loan Prediction Dataset  
- Contains applicant information such as:
  - Gender, Education, Income
  - Loan Amount, Loan Term
  - Credit History
  - Property Area

---

## ⚙️ ML Pipeline Overview

### 1. Data Ingestion
Raw data is loaded and structured for further processing.

### 2. Data Preprocessing
- Handling missing values  
- Encoding categorical variables  
- Feature scaling  

### 3. Feature Engineering
- Creating meaningful features from raw data  
- Improving model performance through better inputs  

### 4. Model Training
- Multiple models trained (e.g., Random Forest, XGBoost, Logistic Regression)  
- Hyperparameter tuning using Optuna  

### 5. Experiment Tracking
- MLflow used to track:
  - model performance  
  - parameters  
  - experiments  

### 6. Model Evaluation
- Models compared using validation metrics  
- Best model selected using a robust selection strategy  

### 7. Deployment
- Model served using FastAPI  
- Containerized using Docker for easy deployment  

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Optuna  
- MLflow  
- Feast (Feature Store)  
- FastAPI  
- Docker  

---

## 🚀 Key Highlights
- Built a **modular ML pipeline (not just a notebook)**
- Implemented **automated training and evaluation workflow**
- Used **experiment tracking (MLflow)**
- Designed system with **production-level practices**

---

## 📂 Project Structure
- `src/feature/` → Data ingestion and preprocessing  
- `src/training/` → Model training and evaluation  
- `src/inference/` → Model serving (API + batch prediction)  
- `config/` → Configuration files  
- `notebooks/` → EDA and experimentation  

---

## 📈 Results
The pipeline successfully identifies the best-performing model and achieves strong predictive performance on loan approval classification.

---

## 🔮 Future Improvements
- Add more feature engineering  
- Improve model performance  
- Deploy on cloud (AWS/GCP)  