# 📄 AI-Powered Resume Analysis

## 🚀 Project Overview
This project is an **AI-powered resume analysis system** that helps automate the process of evaluating resumes. It consists of two main phases:

1. **Category Classification:** Automatically classifies resumes into predefined categories.
2. **Resume Analysis:** Assigns a score to each resume based on key factors like skills, experience, education, and readability.

The project uses **Machine Learning** models to improve resume evaluation, making the process more efficient for HR professionals and job recruiters.

---

## 📌 Features
✅ **Resume Categorization** - Classifies resumes into categories using NLP techniques.  
✅ **Resume Scoring** - Calculates a weighted score for each resume based on predefined metrics.  
✅ **ML-Based Tier Prediction** - Uses **Random Forest** to predict resume tiers (A, B, or C).  
✅ **Feature Importance Analysis** - Visualizes the most important features affecting resume quality.  
✅ **Cross-Validation** - Ensures model reliability and performance.

---

## 🛠️ Installation & Setup
### Prerequisites
Make sure you have Python installed (preferably **Python 3.8+**) along with the following libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk
```

---

## 🔄 Usage
### 1️⃣ Run the Jupyter Notebook
Launch Jupyter Notebook and open the `resume.ipynb` file:
```bash
jupyter notebook resume.ipynb
```

### 2️⃣ Load and Preprocess Data
The project starts by extracting and cleaning resume data, ensuring it is structured for analysis.

### 3️⃣ Perform Resume Categorization
The first phase classifies resumes into specific categories.

### 4️⃣ Score and Rank Resumes
The second phase calculates a **final resume score** and assigns a **tier label** (A/B/C).

### 5️⃣ Train Machine Learning Model
Instead of rule-based scoring, an ML model (Random Forest) predicts resume quality dynamically.

### 6️⃣ Evaluate Model Performance
- **Accuracy score**
- **Classification report**
- **Feature importance analysis**
- **Cross-validation results**

---

## 📊 Model Performance
- **Training Accuracy:** 100%  
- **Test Accuracy:** 100%  
- **Cross-Validation Accuracy:** 100% (No variance detected)  

---

## 📈 Results & Insights
- The **Random Forest model** perfectly classified resumes into tiers.
- The **feature importance plot** shows which resume aspects contribute the most to scoring.
- **Cross-validation** confirmed high model reliability with no signs of overfitting.

---

## 🔥 Future Improvements
🔹 Expand dataset for better generalization.  
🔹 Experiment with other ML models (Logistic Regression, XGBoost).  
🔹 Improve text preprocessing techniques.  

---

## 🤝 Contributing
Feel free to fork the repository and submit pull requests!

---

## 📝 License
This project is open-source and available under the **MIT License**.
