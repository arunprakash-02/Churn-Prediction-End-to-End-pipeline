# **WSDM 2018 KKBOX Churn Prediction – ETL & MLOps Pipeline**  

## **📌 Project Overview**  
This project aims to predict customer churn using the **WSDM 2018 KKBOX dataset**. It implements an **end-to-end machine learning pipeline**, from **ETL (Extract, Transform, Load)** to **model training, deployment, and MLOps practices**.

💼 Business Problem & Objective
🎯 Problem Statement
Customer churn is a major challenge for subscription-based businesses. KKBOX wants to identify users at risk of churning (not renewing their subscription) so they can take preventive actions like personalized offers or targeted marketing campaigns.

🔗 Kaggle Competition: WSDM - KKBOX’s Churn Prediction Challenge

📊 Business Impact
Reduce revenue loss by predicting and retaining high-value customers.
Optimize marketing costs by focusing retention efforts on the right users.
Improve user experience by understanding churn behavior.
🔍 Key Business Questions
Who are the users most likely to churn?
What factors contribute to customer churn?
Can early detection help in preventing churn?

## **🛠️ Tech Stack & Tools**  
- **Programming Language:** Python  
- **ETL & Data Processing:** Pandas, NumPy, Dask, Apache Spark  
- **Model Training & Experiment Tracking:** Scikit-learn, XGBoost, MLflow  
- **Deployment & MLOps:** MLflow Serve, Flask, Docker  
- **Automation & CI/CD:** GitHub Actions, Prefect/Airflow, AWS/GCP  

## **📂 Project Structure**  
```
📦 kkbox-churn-prediction
├── data/                  # Raw & Processed data
├── notebooks/             # Exploratory data analysis (EDA)
├── src/
│   ├── etl.py             # Data extraction & transformation
│   ├── train.py           # Model training & evaluation
│   ├── deploy.py          # Model deployment script
│   ├── config.yaml        # Configuration settings
├── models/                # Saved models
├── tests/                 # Unit tests
├── Dockerfile             # Containerization setup
├── requirements.txt       # Dependencies
├── README.md              # Project documentation
└── .github/workflows/     # CI/CD pipelines
```

## **🚀 Setup & Installation**  
1. **Clone the repository:**  
   ```bash
   [git clone https://github.com/your-username/kkbox-churn.git](https://github.com/arunprakash-02/Churn-Prediction-End-to-End-pipeline.git)
   cd kkbox-churn
   ```

2. **Create a virtual environment & install dependencies:**  
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. **Run the ETL pipeline:**  
   ```bash
   python src/etl.py
   ```

4. **Train the model:**  
   ```bash
   python src/train.py
   ```

5. **Deploy the model:**  
   ```bash
   python src/deploy.py
   ```

## **🔍 Key Features & Workflow**  
✅ **ETL Pipeline:** Data extraction, transformation, feature engineering  
✅ **Model Training:** Hyperparameter tuning, evaluation, experiment tracking with MLflow  
✅ **Model Deployment:** API service for predictions using Flask/MLflow  
✅ **MLOps Practices:** Version control, automated training & deployment  
✅ **CI/CD:** GitHub Actions for continuous integration  

## **📊 Results & Performance**  
- **Best Model:** XGBoost  
- **Accuracy:** XX%  
- **AUC-ROC Score:** XX%  
- **Feature Importance Visualization**  

## **🛠️ Troubleshooting & Common Issues**  
- **Dependency issues?** Run `pip install -r requirements.txt` again.  
- **Out of memory errors?** Try enabling Dask/Spark for large datasets.  
- **Deployment issues?** Ensure Docker is running properly.  

## **📜 License**  
[MIT License](LICENSE)  


