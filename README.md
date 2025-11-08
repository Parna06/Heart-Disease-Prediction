# ❤️ Heart Disease Prediction using Machine Learning

### 🧠 Overview
This project aims to predict the likelihood of heart disease in patients based on clinical and demographic data using supervised machine learning algorithms. The goal is to assist healthcare professionals in early diagnosis and prevention by leveraging data-driven insights.

---

## 🚀 Features
- Data cleaning and preprocessing of the **Heart Disease dataset (`heart.csv`)**
- Exploratory Data Analysis (EDA) with **Seaborn** and **Matplotlib**
- Model training and comparison using:
  - 🌲 **Random Forest Classifier**
  - 🌿 **Decision Tree Classifier**
  - 👥 **K-Nearest Neighbors (KNN)**
- Model evaluation using **Accuracy Score** and visualizations like confusion matrices and heatmaps
- Insights into key features influencing heart disease prediction

---

## 📊 Dataset
The dataset used in this project is the **UCI Heart Disease Dataset**, containing various medical attributes such as:
- Age, Sex
- Chest Pain Type (cp)
- Resting Blood Pressure (trestbps)
- Cholesterol (chol)
- Fasting Blood Sugar (fbs)
- Maximum Heart Rate Achieved (thalach)
- Exercise Induced Angina (exang)
- and more...

📁 **Filename:** `heart.csv`  
📈 **Target Variable:** `target` (1 = Disease Present, 0 = No Disease)

---

## 🧩 Technologies Used
- **Python 3.x**
- **NumPy**, **Pandas** — Data processing
- **Matplotlib**, **Seaborn** — Visualization
- **Scikit-learn** — Model building and evaluation

---

## ⚙️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/yourusername/heart-disease-prediction.git
cd heart-disease-prediction

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook "Heart Disease Prediction.ipynb"
```

---

## 📈 Results
After training multiple models, the following observations were made:
- **Random Forest** achieved the highest accuracy among all models.
- **Decision Tree** provided interpretable results, suitable for feature analysis.
- **KNN** showed moderate accuracy but was sensitive to feature scaling.

---

## 🌟 Visualizations
Some of the plots included in the notebook:
- Correlation Heatmap
- Feature Distributions
- Model Comparison Graphs

---
