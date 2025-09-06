🏥 Hospital Readmission Prediction
📌 Project Overview

Hospital readmission within 30 days is a critical challenge for healthcare providers, impacting patient outcomes, operational efficiency, and costs.
This project builds a machine learning pipeline to predict whether a patient will be readmitted within 30 days based on their medical and demographic data.

🎯 Objectives

Predict 30-day hospital readmissions with high accuracy.

Identify key factors influencing readmissions (age, length of stay, prior visits, comorbidities, etc.).

Support healthcare organizations in proactive care planning and resource allocation.

🛠️ Tech Stack

Languages: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Techniques: Data preprocessing, Feature engineering, Logistic Regression, Random Forest, Gradient Boosting

Metrics: Accuracy, Precision, Recall, ROC-AUC

📂 Dataset

Source: Hospital Readmission Dataset
 (UCI Repository)

~100,000 patient records from U.S. hospitals (1999–2008).

Features include patient demographics, admission type, comorbidities, medications, and outcomes.

📊 Key Results

Achieved ~85% accuracy in predicting 30-day readmissions.

Identified top features contributing to readmission risk (e.g., number of inpatient visits, diabetes diagnosis, discharge type).

Reduced false negatives (missed readmission cases), enabling hospitals to target interventions more effectively.

🚀 Project Workflow

Data Cleaning & Preprocessing – handling missing values, encoding categorical variables, feature scaling.

Exploratory Data Analysis (EDA) – distribution plots, correlation heatmaps, outlier detection.

Model Building – trained Logistic Regression, Random Forest, and Gradient Boosting models.

Evaluation – compared models using ROC-AUC, Precision, Recall, and F1-Score.

Deployment (Optional) – Streamlit app for real-time predictions (future scope).

📈 Business Impact

Helps hospitals reduce readmission rates, saving significant costs.

Improves quality of care by identifying at-risk patients earlier.

Scalable framework for predictive healthcare analytics.

📎 Repository Structure
├── data/                # Dataset (link or instructions to download)
├── notebooks/           # Jupyter notebooks for EDA & modeling
├── src/                 # Source code for preprocessing & models
├── results/             # Output metrics, charts, confusion matrix
└── README.md            # Project documentation

🔗 Links

UCI Dataset

GitHub Repository

👩‍💻 Author

Vidhi Shaw
LinkedIn
 | GitHub
