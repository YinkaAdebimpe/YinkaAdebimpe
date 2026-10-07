# Hi, I'm Yinka 👋

**Data Scientist | Customer Analytics & Predictive Modelling**

I turn messy customer data into business decisions — churn models, lifetime value forecasts, and claims severity predictions. I care as much about **why a model works** as whether it does.

📍 United Kingdom · 📧 adebimpey@gmail.com · 💼 [LinkedIn](https://www.linkedin.com/in/yinka-adebimpe/)

---

## Portfolio — GuardianShield Insurance

A three-engagement consulting series for a fictional UK insurer. Each engagement is a complete deliverable: reproducible data pipeline, PostgreSQL backend, notebooks, trained models, and business-facing reports.

| # | Engagement | Question answered | Result |
|---|-----------|-------------------|--------|
| 1 | **[Customer Renewal Prediction](https://github.com/YinkaAdebimpe/guardianshield-renewal)** | Which customers will lapse at their next renewal? | ROC-AUC **0.81** |
| 2 | **[Customer Lifetime Value](https://github.com/YinkaAdebimpe/guardianshield-clv)** | What is each customer worth over the next 12 months? | Portfolio CLV **£3.33M** |
| 3 | **[Claims Severity Prediction](https://github.com/YinkaAdebimpe/guardianshield-claims)** | How much will each claim cost? | MAE **£1,937** |

### 🔍 What makes these projects different

**1. Honest modelling decisions.** In Engagement 2, I evaluated BG/NBD — the industry-standard CLV model — and **rejected it**. Insurance renewals are contractual, not continuous-time purchases, so the model collapsed to degenerate parameters. I documented the negative result and switched to survival analysis. The rejected-model notebook is retained in the repository.

**2. Iteration over polish.** Engagement 1's first model scored ROC-AUC 0.70 — barely above random. Rather than accept it, I diagnosed the problem (missing behavioural features), added four new signals (`missed_payments`, `payment_method_change`, `days_since_last_contact`, `previous_renewals_count`), and lifted ROC-AUC to **0.81**.

**3. Business framing throughout.** Every engagement ships with an Executive Summary written for a non-technical audience, plus a Technical Report for reviewers who want the details.

---

## Technical Skills

| Area | Tools |
|------|-------|
| **Languages** | Python, SQL, R |
| **Data** | pandas, numpy, PostgreSQL, SQLAlchemy |
| **Machine Learning** | scikit-learn, XGBoost, `lifelines` (survival analysis), `lifetimes` (BG/NBD) |
| **Visualisation** | matplotlib, seaborn, Power BI, Tableau |
| **Tools** | Git, GitHub, JupyterLab, VS Code |

---

## Background

- **Diploma in Data Analytics** — Pitman Training (SQL, Tableau, Python, R, statistics)
- **Expert Data Scientist Course** — Stackwissr London (Power BI, SQL, ML, Deep Learning, NLP, Feature Engineering)
- **Professional experience** — Amazon and Concentrix UK, in customer-facing roles. This is where I learned that the hardest part of analytics isn't the model — it's understanding what question the business actually needs answered.

I'm looking for a **data scientist or analyst role** where I can keep building models that solve real problems, and keep documenting why each one works.

---

*If you'd like to discuss any of the engagements — the modelling choices, the limitations, the iterations — [reach out on LinkedIn](https://www.linkedin.com/in/yinka-adebimpe/) or email me at adebimpey@gmail.com. I enjoy talking through the "why".*
