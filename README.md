# 💼 Intelligent Personal Finance Advisor with Predictive Analytics

An end-to-end AI-powered personal finance management system that helps users track expenses, predict financial trends, and gain actionable insights using machine learning and data analytics.<hr>

# 📌 Overview

Managing personal finances is often reactive and unstructured. This project transforms it into a data-driven, predictive system that helps users make smarter financial decisions.

# 🚀 Features
## 📊 Core Functionalities
* Expense & income tracking
* Budget management system
* Financial dashboard with insights
* Emergency fund planning
* Goal-based financial planning

## 🤖 AI & Machine Learning
* Predictive analytics for financial forecasting
* Multiple ML models trained for better accuracy
* Smart insights generation
* Explainable recommendations

## 💬 Chatbot Assistant
* Interactive financial chatbot
* Personalized suggestions
* Real-time query handling

## 📈 Advanced Insights
* Spending pattern analysis
* Risk detection
* Budget optimization suggestions<hr>

# 🛠️ Tech Stack
## Backend
* Python (Flask)
* MySQL
* Scikit-learn (ML models)
## Frontend
* HTML, CSS, JavaScript
* Responsive UI
## AI Components
* Predictive models (train_models.py)
* Insights engine (insights.py)
* Chatbot module (chatbot.py)<hr>

# 📁 Project Structure

```
FinancePRO_Upgraded/
├── app.py                  ← Main Flask backend (upgraded)
├── db_config.py            ← MySQL connection config
├── database.sql            ← Full schema with new tables
├── requirements.txt        ← Python dependencies
│
├── ml/
│   ├── __init__.py
│   └── train_models.py     ← Dataset generation + model training
│
├── models/                 ← Saved ML model files (auto-created)
│   ├── goal_model.pkl
│   └── expense_model.pkl
│
├── utils/
│   ├── __init__.py
│   ├── predictor.py        ← ML inference + Explainable AI
│   ├── insights.py         ← Rule-based insights + health score
│   └── chatbot.py          ← AI financial chatbot engine
│
├── templates/              ← All HTML pages
│   ├── index.html          ← Login / Signup
│   ├── dashboard.html      ← ✨ Upgraded: health score, insights
│   ├── budget.html
│   ├── transactions.html
│   ├── goals.html
│   ├── prediction.html     ← ✨ New: ML results + XAI + what-if
│   ├── emergency.html      ← ✨ New: Emergency fund module
│   └── chatbot.html        ← ✨ New: AI financial chatbot
│
└── static/
    ├── style.css
    └── script.js

```

# ⚙️ Installation & Setup
## 1️⃣ Clone Repository
* git clone https://github.com/your-username/finance-advisor.git
* cd finance-advisor

## 2️⃣ Install Dependencies
* pip install -r requirements.txt

## 3️⃣ Setup Database
* Open MySQL
* Run: source database.sql;
* Update credentials in: db_config.py

## 4️⃣ Run Application
* python app.py
* Open in browser: http://127.0.0.1:5000

<hr>

# 🧪 Machine Learning Pipeline
* Data preprocessing & cleaning
* Feature engineering
* Model training using multiple algorithms
* Model evaluation (accuracy comparison)
* Best model selection
* Deployment via Flask endpoints

# 📸 Screenshots
## Login
  <img width="1919" height="1079" alt="Screenshot 2026-04-28 165704" src="https://github.com/user-attachments/assets/28a7de77-9b7d-4615-8cd3-fd065c07609d" />

## Dashboard
  <img width="1918" height="1079" alt="Screenshot 2026-04-28 165752" src="https://github.com/user-attachments/assets/33033213-7429-41c1-88a9-57dbeaec3494" />

## Prediction Page
  <img width="1919" height="1079" alt="Screenshot 2026-04-28 165936" src="https://github.com/user-attachments/assets/0d95f275-3c0f-47f2-b71d-538de7ae4cb3" />

## Chatbot Interface
  <img width="1917" height="1079" alt="Screenshot 2026-04-28 165901" src="https://github.com/user-attachments/assets/09fd0659-91a8-4886-b671-aae8510d9287" />

## Emergency Fund
  <img width="1919" height="1079" alt="Screenshot 2026-04-28 165830" src="https://github.com/user-attachments/assets/f2917153-70a4-4fe9-b3f3-cef89102ed36" />

<hr>

# 📌 Future Enhancements
* 🔐 User authentication (JWT / OAuth)
* 📱 Mobile-friendly UI
* ☁️ Cloud deployment (AWS / Render)
* 📊 Advanced visual analytics (charts & graphs)
* 🧾 PDF financial reports
* 🔎 Explainable AI (SHAP / LIME)<hr>

# 📜 License
* This project is open-source for educational and personal use.<hr>

