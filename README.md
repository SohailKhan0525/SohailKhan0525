<h1 align="center">👋 Hi, I'm Sohail Khan</h1>

<p align="center">
  🎓 Self-taught Python Developer from Hyderabad &nbsp;|&nbsp; 🤖 Aspiring AI Engineer<br/>
  Passionate about Machine Learning, Automation & Full-Stack Web Development
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
</p>

---

## 🧠 Skills & Technologies

| Category | Tools / Libraries |
|---|---|
| **Languages** | Python, JavaScript |
| **ML / Data Science** | scikit-learn, pandas, NumPy, Matplotlib, Seaborn |
| **Web Frameworks** | Streamlit, FastAPI, React 18, Tailwind CSS |
| **Core Python** | OOP, File Handling, JSON, pathlib, random, string |
| **Tools** | Google Colab, Jupyter Notebook, joblib, Git |
| **Auth / Security** | bcrypt, JWT, OAuth 2.0 (GitHub & Google) |

---

## 💼 Projects

### 🤖 AutoML — Automated Machine Learning for Everyone
> Full-stack SaaS ML platform · Python · FastAPI · React · Tailwind CSS · scikit-learn

Upload any CSV and the platform automatically analyses your data, detects whether it's a classification or regression problem, trains multiple models side-by-side, returns a ranked leaderboard, and exports a ready-to-run Jupyter Notebook — all in your browser.

- Drag-and-drop CSV upload with client + server-side validation
- Auto EDA: missing values, correlation matrix, dataset quality score
- Trains Logistic Regression, Decision Tree & Random Forest (classification) / Linear Regression, Decision Tree & Random Forest (regression)
- Feature importance, plain-language auto-insights
- Pro plan: 5-fold CV, RandomizedSearchCV hyperparameter tuning, extended metrics
- Full auth system: email/password + GitHub & Google OAuth
- Security: CORS, GZip, rate limiting, CSP headers, input length limits

🔗 [View on GitHub](https://github.com/SohailKhan0525/AutoML)

---

### 🫀 Heart Disease Prediction (Logistic Regression)
> Machine Learning · Python · scikit-learn · Streamlit · Pandas

Predicts the likelihood of heart disease using 15 medical attributes with Logistic Regression trained on real-world patient data. Outputs **Low Risk (0)** or **High Risk (1)**.

- Feature engineering with one-hot encoding & StandardScaler
- Serialised model artifacts (`.pkl`) for production inference
- Full end-to-end prediction pipeline: raw input → preprocessing → prediction

🔗 [View on GitHub](https://github.com/SohailKhan0525/HeartDiseaseML) &nbsp;|&nbsp; 🚀 [Try the Live App](https://heartdiseaseml-4zrcurmudxpfxbwygcuyyt.streamlit.app/)

---

### 🌍 Global Earthquake & Tsunami Prediction
> Machine Learning · Python · scikit-learn · pandas · Seaborn · Google Colab

Classifies whether a seismic event will trigger a **tsunami** using global earthquake records.

- Full ML pipeline: EDA → cleaning → feature importance → modelling → evaluation → tuning
- Baseline Random Forest achieved **93.6% accuracy** on the test set
- Hyperparameter tuning with GridSearchCV & RandomizedSearchCV

🔗 [View on GitHub](https://github.com/SohailKhan0525/Global-Earthquake-Prediction)

---

### 🏠 House Price Prediction
> Machine Learning · Python · scikit-learn · pandas · Streamlit

End-to-end ML regression workflow for predicting house prices (in lakhs).

- Extensive text-to-numeric preprocessing (carpet area, floor, price columns)
- Unit normalisation (sqft / sqm / sqyard → unified SQFT)
- Trained & compared Random Forest, Gradient Boosting, and Decision Tree regressors
- Deployed with Streamlit

🔗 [View on GitHub](https://github.com/SohailKhan0525/HousePricePrediction)

---

### 🎓 Student Pass/Fail Predictor
> Machine Learning · Python · scikit-learn · Logistic Regression

Binary classifier that predicts whether a student will PASS or FAIL based on demographic and academic background features.

- One-hot encoding of 5 categorical features (12 encoded columns)
- Logistic Regression with `class_weight='balanced'` to handle class imbalance
- Model persistence with `joblib` (`.pkl` artifacts)

🔗 [View on GitHub](https://github.com/SohailKhan0525/StudentFailPassPredictor)

---

### 🎓 Student Management System (Python + Streamlit)
> OOP · Python · Streamlit · JSON · pathlib

A complete student records management system with both CLI and web versions.

- Auto-generates unique student IDs (letters + digits + special chars)
- Full CRUD: add, update, view, delete, search, filter by age & course
- Import / export records as JSON
- Atomic file writes to prevent data corruption

🔗 [View on GitHub](https://github.com/SohailKhan0525/StudentManagementProject) &nbsp;|&nbsp; 🚀 [Try the Live App](https://studentmanagementproject-ulj54ytmcyj55upzakbzhn.streamlit.app/)

---

### 🏦 Bank Management System (Python + Streamlit)
> OOP · Python · Streamlit · JSON · pathlib

A complete banking system with both CLI and Streamlit web versions.

- Create accounts, deposit/withdraw money, update details, delete accounts
- Auto-generated unique account numbers (letters + digits + special chars)
- Secure PIN login, balance validation, deposit limits
- JSON file-based persistent storage

🔗 [View on GitHub](https://github.com/SohailKhan0525/BankManagementProject) &nbsp;|&nbsp; 🚀 [Try the Live App](https://bankmanagementproject-brt9pt282uavy8ddzzy7ql.streamlit.app/)

---

### 💱 Currency Converter
> Python · Streamlit · requests

A web app that converts currencies in real time using live exchange rates via the `requests` library.

🔗 [View on GitHub](https://github.com/SohailKhan0525/ConvertCurrency)

---

### 📁 File Handling Project (Python CLI)
> Python · pathlib · os

A menu-driven CLI tool for creating, reading, and deleting files with recursive directory listing.

- Context-manager-based file I/O (`with open(...)`)
- Safe checks using `Path.exists()` and `Path.is_file()`
- First ever Python project — demonstrates mastery of core file I/O concepts

🔗 [View on GitHub](https://github.com/SohailKhan0525/File_Handling_Project)

---

## 🌱 Goals

- 🚀 Continue expanding **AutoML** with XGBoost/LightGBM, SHAP explainability, and Stripe billing
- 📊 Deepen expertise in Machine Learning, Data Analysis, and Model Deployment
- 🌐 Build more full-stack AI-powered web applications

---

<p align="center">
  <a href="https://github.com/SohailKhan0525?tab=repositories">
    <img src="https://img.shields.io/badge/View%20All%20Repos-%23181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>
