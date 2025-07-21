# ML-Projects
A curated collection of small-scale Machine Learning projects built for learning, experimentation, and skill enhancement. Includes classification, regression, clustering, and more—powered by Python, scikit-learn, and other essential ML tools.

## 🪨 Rock vs Mine Prediction using Machine Learning

This project focuses on building a binary classification model to distinguish between rocks and mines using sonar frequency data. It uses supervised learning techniques to train and evaluate the model effectively.

---

### 📁 Project Structure
SONAR-Rock-vs-Mine-Prediction/
│
├── Copy_of_sonar_data.csv # Dataset file (e.g., sonar.csv)
├── Rock-vs-Mine-Prediction.ipynb # Jupyter notebook for EDA & modeling
├── README.md
└── requirements.txt

---

### 📊 Dataset

- **Source**: UCI Machine Learning Repository  
- **Features**: 60 sonar signal attributes  
- **Target**: `R` (Rock) or `M` (Mine)

[Dataset Link 🔗](https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+(Sonar,+Mines+vs.+Rocks))

---

### 🛠️ Tools & Libraries Used

- Python 🐍
- Pandas & NumPy
- scikit-learn
- Jupyter Notebook

---

### 🚀 Project Highlights

- Exploratory Data Analysis (EDA)
- Data preprocessing and label encoding
- Train-test split and model evaluation
- Trained classifier (Logistic Regression)
- Performance comparison using accuracy and confusion matrix

---

### 📈 Model Accuracy

| Model                 | Accuracy |
|---------------------- |----------|
| Logistic Regression   |    85%   |

---

### 📌 How to Run

```bash
# Clone the repository
git clone https://github.com/tanushree-c/ml-projects.git

# Navigate to the project folder
cd ml-projects/SONAR-Rock-vs-Mine-Prediction

# Install dependencies
pip install -r requirements.txt

# Run the notebook or script
jupyter notebook Rock-vs-Mine-Prediction.ipynb
