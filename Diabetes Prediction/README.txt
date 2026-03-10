🧠 Diabetes Risk Prediction Model
A machine learning project that predicts the likelihood of diabetes using patient health indicators.
The goal is to identify high-risk individuals early using statistical analysis and predictive modelling.

📌 Project Objective
Diabetes is one of the fastest-growing health conditions globally. Early identification of high-risk patients can help healthcare providers implement preventive measures.


This project aims to:
- Analyse patient medical data
- Identify key health indicators contributing to diabetes
- Build a predictive machine learning model
- Evaluate model performance using classification metrics


📊 Dataset
The dataset contains medical diagnostic measurements for patients.
- Pregnancies	
- Glucose	
- BloodPressure	
- SkinThickness	
- Insulin	
- BMI	
- DiabetesPedigreeFunction	
- Age	
- Outcome


Dataset Size: 700+ patient records


⚙️ Project Workflow
1️⃣ Data Preprocessing
- Cleaned missing and zero values in medical measurements
- Checked distributions of features
- Prepared dataset for machine learning models

2️⃣ Exploratory Data Analysis (EDA)
- Performed analysis to understand patterns in the dataset.
- Key steps:
    1. Correlation heatmap
    2. Distribution plots
    3. Feature comparison with diabetes outcome

- Key Observations:
    1. The glucose level shows the strongest correlation with diabetes.
    2. BMI and Age significantly influence diabetes risk.
    3. Some features required cleaning due to invalid zero values.

3️⃣ Feature Engineering
Prepared data for modelling by:
  - Cleaning invalid entries
  - Scaling features where necessary
  - Selecting relevant predictors

4️⃣ Machine Learning Models
Two models were trained and evaluated:
  - Logistic Regression
      Used for baseline binary classification.
  - Decision Tree Classifier
      Used to capture nonlinear relationships between features.


📈 Model Performance
Accuracy ---> ~80% 
Precision --->	High for diabetes class
Recall ---> Balanced detection


Evaluation methods used:
1. Confusion Matrix
2. Accuracy Score
3. Classification Report


🔍 Key Insights
Important predictors of diabetes include:
    - Glucose Level
    - Body Mass Index (BMI)
    - Age
    - Family History Indicator
These insights demonstrate how machine learning can assist in early risk detection for healthcare applications.


🛠 Technologies Used
Programming:
Python

Libraries:
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn

Environment:
Jupyter Notebook

📂 Project Structure
Diabetes-Prediction/
│
├── Diabetes prediction.ipynb
├── dataset.csv
├── README.md
