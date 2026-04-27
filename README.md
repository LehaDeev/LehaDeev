<div align="center">

# 👋 Hi, I'm Aleksei Deev

### Machine Learning Engineer · Data Scientist · Python Developer

[![Telegram](https://img.shields.io/badge/Telegram-@LehaDeev-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/LehaDeev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-alekseideev-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alekseideev)
[![Email](https://img.shields.io/badge/Email-lehadeev@yandex.ru-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lehadeev@yandex.ru)

</div>

---

## 🧠 About Me

Data Scientist & ML Engineer with **production experience** in building end-to-end AI systems and a strong engineering background. I combine deep technical expertise in machine learning with real-world business acumen — having scaled an e-commerce business to **₽46M annual revenue** and built commercial SaaS products from scratch.

- 🔭 Currently working on ML systems, algorithmic trading bots, and AI-powered SaaS services
- 🎓 Completed **Yandex Practicum** — Advanced Data Science Specialist (2026)
- 💡 21 completed ML projects across classification, regression, NLP, CV, time series, and Big Data
- 🏭 9+ years of engineering background in nuclear, oil & gas, and defense industries
- 📍 Nizhny Novgorod, Russia · Open to **remote work**

---

## 🛠️ Tech Stack

**Machine Learning & Data Science**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat-square)
![LightGBM](https://img.shields.io/badge/LightGBM-2ECC71?style=flat-square)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square)

**NLP & Computer Vision**

![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![BERT](https://img.shields.io/badge/BERT-4A154B?style=flat-square)
![NLTK](https://img.shields.io/badge/NLTK-3C8DBC?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![ResNet](https://img.shields.io/badge/ResNet50-EE4C2C?style=flat-square)

**Data Engineering & MLOps**

![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Data Analysis**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-FF6F61?style=flat-square)

---

## 🚀 Featured Projects

### 📈 [we_trust_in_people](https://github.com/LehaDeev/we_trust_in_people) — Telegram Bot for Algo Trading (MOEX) via Tinkoff Invest API

- **Custom RankEnsemble:** LightGBM (quantile regression, alpha tuned by Optuna) + ExtraTrees (MSE) + HistGradientBoosting (MAE); three distinct loss functions for ensemble diversity; z-score normalization of predictions
- **Adaptive ensemble weights** via Spearman on OOS val-fold + softmax with temperature
- **62 technical features** (TA-Lib); per-ticker selection via OOS Permutation Importance → 30–45 features per ticker
- **Custom WalkForwardSplit** with gap=4 and embargo=4 — eliminates label leakage
- **HPO metric** — Spearman correlation (Sortino uninformative at 88% negative targets)
- **Target variable** — continuous net P&L; per-ticker threshold optimization via Optuna
- **Stack:** `Python` · `aiogram 3` · `LightGBM` · `scikit-learn` · `Optuna` · `TA-Lib` · `SQLAlchemy 2 async` · `PostgreSQL` · `Redis` · `gRPC` · `Docker`

---

### 📅 [Zapiska](https://t.me/my_zapiska_bot) — Commercial SaaS: Telegram Booking Bot
> Production booking service for appointment-based businesses (masters & clients)

- **Features:** Service configuration, schedule management, client booking, subscription system, Tinkoff payment integration
- **Architecture:** Repository pattern, FSM (aiogram States), fully async, clean layer separation, Redis caching, APScheduler for deferred tasks
- **Stack:** `Python` · `FastAPI` · `aiogram 3` · `PostgreSQL` · `SQLAlchemy async` · `AsyncPG` · `Redis` · `APScheduler` · `Docker Compose` · `Alembic`

---

### 🤖 [wb-parser](https://github.com/LehaDeev/wb-parser) — AI Review Auto-Responder for Wildberries
> Automated service that generates and posts AI-written replies to customer reviews

- **AI:** Dual LLM support — Yandex GPT and GigaChat; runs every 30 minutes via **GitHub Actions** (zero hosting cost)
- **Built from experience:** Developed based on personal e-commerce operations (200+ SKU portfolio, ₽46M peak revenue)
- **Stack:** `Python` · `Yandex GPT API` · `GigaChat API` · `Wildberries API` · `GitHub Actions CI/CD` · `aiogram` · `structlog`

---

### 🎓 [Yandex Practicum — 21 ML Projects](https://github.com/LehaDeev/yandex_practicum_projects)
> Full portfolio of academic and applied ML projects

| Domain | Projects |
|---|---|
| 🔵 Classification | 8 projects |
| 📊 Regression | 7 projects |
| 🧠 Deep Learning | 3 projects |
| 📝 NLP | 3 projects |
| 👁️ Computer Vision | 1 project |
| 📈 Time Series | 1 project |
| ⚡ Big Data (Apache Spark) | 1 project |
| 🗄️ SQL | 2 projects |

---

**Algorithms & Methods:**
`Gradient Boosting (XGBoost / LightGBM / CatBoost)` · `Random Forest` · `CNN` · `BERT / Transformers` · `Word2Vec / TF-IDF` · `ResNet50` · `Time Series (ARIMA, seasonal decomposition)` · `SHAP explainability` · `Optuna HPO`

---

## 💼 Professional Background

| Period | Role | Company |
|---|---|---|
| Nov 2024 – Present | **Data Science Specialist** | Freelance / Project work |
| Aug 2022 – Present | **Analyst / E-commerce Entrepreneur** | Wildberries Marketplace |
| Nov 2012 – Jul 2022 | **Design Engineer** | OKBM Afrikantov (Nuclear / Defense) |

**Engineering background** in designing PLC-based control systems for nuclear, oil & gas, and defense industries — brings systematic thinking and attention to reliability into every ML solution.

---

## 🎓 Education & Certifications

- 🏅 **Advanced Data Science Specialist** — Yandex Practicum, 2026
- 🎓 **B.Sc. Electrical Engineering** — Nizhny Novgorod State Technical University (NNSTU), 2012  
  *Faculty of Automation & Electromechanics*

---

## 📊 GitHub Statistics

<div align="center">

![](https://raw.githubusercontent.com/LehaDeev/LehaDeev/main/profile-summary-cards/profile-details.svg)

<a href="https://github.com/LehaDeev">
  <img src="https://raw.githubusercontent.com/LehaDeev/LehaDeev/main/profile-summary-cards/repos-per-language.svg" width="49%"/>
  <img src="https://raw.githubusercontent.com/LehaDeev/LehaDeev/main/profile-summary-cards/most-commit-language.svg" width="49%"/>
</a>

<a href="https://github.com/LehaDeev">
  <img src="https://raw.githubusercontent.com/LehaDeev/LehaDeev/main/profile-summary-cards/stats.svg" width="49%"/>
  <img src="https://raw.githubusercontent.com/LehaDeev/LehaDeev/main/profile-summary-cards/productive-time.svg" width="49%"/>
</a>

</div>

---

## 📬 Let's Connect

I'm actively looking for opportunities as a **Machine Learning Engineer** or **Data Scientist**.  
Open to remote positions. Ready for technical interviews and test assignments.

<div align="center">

[![Telegram](https://img.shields.io/badge/Message_me_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/LehaDeev)

</div>

---

<div align="center">
<sub>💡 "Fast to learn new domains. Passionate about solving ambitious problems."</sub>
</div>
