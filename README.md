# 👋 Hello World! I'm Zeyad Elshenawy

<div align="center">
  
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=todoist&logoColor=white)](https://my-portfolio-weld-eta-67.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/zeyad-elshenawy)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ZeyadElshenawy)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:zeyadelshenawy1@gmail.com)

</div>

> [!TIP]
> ### 🌐 [Visit my live portfolio →](https://my-portfolio-weld-eta-67.vercel.app/)
> **Glassmorphism** in light mode · **terminal/matrix** in dark mode — toggle between them. Built with Astro + compiled Tailwind, deployed on Vercel.

---

## 📊 About Me

Computer Science graduate looking for a junior data scientist or ML engineer role. Strongest in supervised learning on tabular data — feature engineering, gradient boosting and model evaluation — with a solid grounding in statistics and hypothesis testing. I also build LLM features and test them the same way I test models: against a baseline and a labelled dataset.

B.Sc. in Computer Science (Software Engineering) from King Salman International University, **graduated July 2026, GPA 3.8**.

📍 **Location:** Cairo, Egypt  

---

## 🛠️ Skills

**Programming & data:**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=for-the-badge&logo=microsoft&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=for-the-badge&logo=yandex&logoColor=black)

- **Models:** linear and logistic regression (L1/L2), KNN, Naive Bayes, SVM, decision trees, random forests, gradient boosting (LightGBM, CatBoost), K-Means, hierarchical clustering, DBSCAN, PCA, anomaly detection
- **Evaluation:** time-based and k-fold validation, leakage checks, imbalanced metrics (PR-AUC, recall at a threshold), probability calibration (Brier score), hyperparameter search, learning curves
- **ML engineering:** scikit-learn pipelines, SHAP, MLflow experiment tracking, model serving through a REST API (FastAPI), drift monitoring and retraining
- **Deep learning:** TensorFlow / Keras, PyTorch; CNNs, transfer learning, attention and Transformers
- **LLM applications:** structured outputs with Pydantic, LLM-as-judge and grounding checks, pgvector
- **Statistics & maths:** descriptive statistics, probability distributions, hypothesis testing, confidence intervals, linear algebra, gradient-based optimisation

---

## 📈 GitHub Stats

<div align="center">
  
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=ZeyadElshenawy&theme=radical&hide_border=true&background=0D1117)

</div>

---

## 🚀 Featured Projects

### ✈️ AeroPredict IO — Flight Departure Delay Prediction *(personal project, Oct 2026)*
[![Repo](https://img.shields.io/badge/GitHub-View_Repository-blue?style=flat-square&logo=github)](https://github.com/ZeyadElshenawy/AeroPredict-IO)

Predicts whether a US domestic flight leaves 15+ minutes late, using only data available **2 hours before departure**: **5.4M flights** at the 50 busiest US airports in 2025, joined with hourly airport weather.

- Date-based train / validation / test split; historical delay rates are Bayes-smoothed and computed only from earlier days
- A Carrier × Airport × Hour lookup table beat schedule-only models; runway-traffic and weather features are what moved past it. LightGBM reached **PR-AUC 0.41 vs 0.36** for the lookup on an 885K-flight Nov–Dec holdout
- Alert threshold (0.21) set on validation F1 after rejecting the cost-optimal cut-off, which flagged over 65% of flights. Each prediction is served with SHAP explanations in about 15 ms

**Stack:** Python, SQL, PostgreSQL, LightGBM, CatBoost, scikit-learn, SHAP, FastAPI

---

### 🤖 SmartCV — AI Career Assistant *(graduation project, Apr 2026)*
[![Repo](https://img.shields.io/badge/GitHub-View_Repository-blue?style=flat-square&logo=github)](https://github.com/ZeyadElshenawy/SmartCV)

Upload a CV and a job description to get a skill-gap analysis, a tailored resume with an ATS score, and a networking plan.

- Gap analysis runs in two passes: the LLM labels each required skill, then fuzzy matching in code reconciles the labels so no skill is dropped (**99.9% coverage** over 150 CV–job pairs)
- Every LLM step is benchmarked against labelled fixtures: skill extraction **F1 0.85**, personal-info parsing accuracy **0.96**

**Stack:** Python, Django, PostgreSQL + pgvector, Llama 4 (Groq), Pydantic

---

### 🎯 Customer Segmentation — RFMT + K-Means *(Dec 2025)*
[![Repo](https://img.shields.io/badge/GitHub-View_Repository-blue?style=flat-square&logo=github)](https://github.com/ZeyadElshenawy/customer-segmentation-rfmt)

Segmented customers of the UCI Online Retail dataset (~541K transactions) on Recency, Frequency, Monetary value and Tenure.

- Log-transformed and standardized the features, then picked **K=3** with the elbow method and silhouette score (0.351 vs 0.298 for K=4)
- The highest-value segment (38% of customers) drives **84% of revenue**; each segment gets a retention recommendation

**Stack:** Python, pandas, scikit-learn

---

## 🧩 Other Work

- **[Stroke Prediction](https://github.com/ZeyadElshenawy/healthcare-prediction-depi)**: DEPI team capstone. My part: data cleaning and EDA.
- **[Brain Tumor Classification](https://github.com/ZeyadElshenawy/the-magnificent-three)**: university team project. My part: data processing and the ML models.
- **[HR Analytics Dashboard](https://github.com/ZeyadElshenawy/hr-analytics-dashboard)**: Power BI practice project.

---

## 💼 Experience

### 🔄 Digital Transformation Intern | Almansour Automotive
*August 2025 · Giza, Egypt* — [Certificate ↗](https://drive.google.com/file/d/1r9tqi6OWlP2_XQrcC5Roxa3Fraq0A6BC/view?usp=sharing)

- Rotated through the IT, SAP, Digital Transformation and Network Security departments, observing how a large automotive distributor runs its ERP and IT operations

---

## 🎓 Certifications & Training

**19 verified certificates** across DataCamp, WE Telecom, MCIT/DEPI, and Coursera. Full list with verification links is on the [portfolio site](https://my-portfolio-weld-eta-67.vercel.app/#certifications).

### DataCamp — 14 tracks (~495 hrs)
- 🧬 [Machine Learning Scientist](https://www.datacamp.com/completed/statement-of-accomplishment/track/0e0322e5c975f9732a4743154ff0a4ea0d5abba7) (85 hrs)
- 📊 [Associate Data Scientist](https://www.datacamp.com/completed/statement-of-accomplishment/track/bd301feefedc66ab6876c15ab3f3d66ce79e117c) (90 hrs)
- 🤖 [Associate AI Engineer for Data Scientists](https://www.datacamp.com/completed/statement-of-accomplishment/track/9aa442f8f784f6cdc26542338f6a192c611445a9) (40 hrs)
- Plus 5 more career tracks (Data Analyst, Python Developer, …) and 6 skill tracks (SQL, Power BI, ML Fundamentals, …) — [full list ↗](https://my-portfolio-weld-eta-67.vercel.app/#certifications)

### WE Telecom Egypt — Training Academy
- 🤖 [AI Professional Level — Deep Learning & Computer Vision](https://drive.google.com/file/d/1eqkde1X3q17eUBFuMCKfgGzt4wdGJ4QZ/view?usp=sharing) (40 hrs)

### MCIT · Digital Egypt Pioneers Initiative (DEPI)
- 📊 [AI & Data Science — Data Scientist Track](https://drive.google.com/file/d/1j7RXsZiYr8MfCafV9_MLUK_lY2rc5VD7/view?usp=sharing) (4 months)

### Coursera
- 🧠 [Neural Networks and Deep Learning](https://coursera.org/verify/HYT51PF7WQGV) — *DeepLearning.AI*
- 🤖 [Applied Machine Learning in Python](https://coursera.org/verify/BUYFU9ADFMIQ) — *University of Michigan*
- ☕ [Database Management with Java and SQL](https://coursera.org/verify/3P34H669GT2I) — *Amazon*

---

## 📫 Let's Connect!

<div align="center">

🌐 **Portfolio:** [my-portfolio-weld-eta-67.vercel.app](https://my-portfolio-weld-eta-67.vercel.app/)  
📧 **Email:** zeyadelshenawy1@gmail.com  
💼 **LinkedIn:** [zeyad-elshenawy](https://www.linkedin.com/in/zeyad-elshenawy)  

</div>

---

<div align="center">
  
![Profile Views](https://komarev.com/ghpvc/?username=ZeyadElshenawy&color=blueviolet&style=flat-square)

</div>
