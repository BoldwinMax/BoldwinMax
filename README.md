<img width="25%" align="right" alt="Quantitative Analysis GIF" src="https://github.com/BoldwinMax/BoldwinMax/blob/main/data-analyst.gif" />

# Hi, I'm Boldwin Mweemba 👋

**MSc Mathematical Sciences (AIMS Ghana) · Mastercard Foundation Scholar · MSc Financial Engineering Candidate (WorldQuant University)**

I build quantitative models that answer questions institutions haven't yet thought to ask — forecasting Zambia's maize floor price before the government announces it, modelling when load-shedding returns before ZESCO does, and decomposing what actually drove the Kwacha's collapse and recovery when the explanations in circulation didn't fully add up.

My work sits at the intersection of rigorous mathematical theory and high-stakes decision intelligence. I source the data, build the pipeline, run the model, and deliver something a policymaker, analyst, or executive can open and act on — not just a notebook, but a verdict backed by evidence.

My academic foundation is in system dynamics and signal processing — specifically how feedback loops respond to oscillatory inputs — which I now apply to financial markets and macroeconomic systems. I am extending this into an MSc in Financial Engineering at WorldQuant University, focused on derivative pricing, risk management, and portfolio optimisation.

📬 **Find me online**:
  <a href="https://linkedin.com/in/boldwin-mweemba" target="_blank">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>
  <a href="mailto:boldwin@aims.edu.gh">
    <img alt="Email" src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white">
  </a>

---

# 📜 Professional Certifications & Credentials

### 🏆 Core Professional Certifications
* **[Microsoft Certified: Power BI Data Analyst Associate (PL-300)](https://learn.microsoft.com/en-us/users/boldwin-2312/credentials/12f8c48c8b1e470a)** — Microsoft *(Apr 2026)*
* **[Microsoft SQL Server](https://www.coursera.org/account/accomplishments/specialization/ZFUVD41QPADS)** — Microsoft *(May 2026)*
* **[IBM Data Science Professional Certificate](https://www.coursera.org/account/accomplishments/specialization/7T1Y9GXETAKF)** — IBM *(Jun 2026)*

### 🏦 Financial Engineering & Risk
* **[Foundations of Financial Engineering](https://www.credly.com/badges/35f8acc6-ca62-4a9f-9a98-2b9549831ece)** — WorldQuant University *(May 2026)*
* **[Financial Engineering and Risk Management](https://www.coursera.org/account/accomplishments/specialization/H33EPKLU2JGO)** — Columbia University *(Jun 2026)*
* **[Risk Management](https://www.coursera.org/account/accomplishments/specialization/QZA98R5M6U1F)** — New York Institute of Finance *(Jun 2026)*
* **[Financial Markets](https://www.coursera.org/account/accomplishments/verify/WQ691PY94CHB)** — Yale University *(Jun 2026)*

### 📊 Quantitative Modeling & Analytics
* **[Modeling Risk and Realities](https://www.coursera.org/account/accomplishments/verify/XBDREDROMJG7)** — University of Pennsylvania *(Mar 2026)*
* **[Decision-Making and Scenarios](https://www.coursera.org/account/accomplishments/verify/JFRGHCT3ISP4)** — University of Pennsylvania *(Apr 2026)*
* **[Fundamentals of Quantitative Modeling](https://www.coursera.org/account/accomplishments/verify/63X50A2QH1K8)** — University of Pennsylvania *(Mar 2026)*
* **[Linear Regression for Business Statistics](https://www.coursera.org/account/accomplishments/verify/U1A18LDC0W7J)** — Rice University *(Feb 2026)*
* **[Business Applications of Hypothesis Testing](https://www.coursera.org/account/accomplishments/verify/CXQ3GKN9KAE6)** — Rice University *(Feb 2026)*
* **[Statistical Distributions & Business Decisions](https://www.coursera.org/account/accomplishments/verify/SGKF13IN4IWQ)** — Rice University *(Feb 2026)*

### 💼 Business, Tools & Strategy
* **Business Management** — ESMT Berlin & iiAfrica, Industry Immersion Programme *(Aug 2025)*
* **[Excel Skills for Business Specialization](https://www.coursera.org/account/accomplishments/specialization/certificate/3LD8H4AOHOVQ)** — Macquarie University *(Feb 2026)*
* **[Mindware: Critical Thinking for the Information Age](https://www.coursera.org/account/accomplishments/verify/E4FI69UMZ82B)** — University of Michigan *(Feb 2026)*
* **[Introduction to Spreadsheets and Models](https://www.coursera.org/account/accomplishments/verify/XZ12M0VQJO48)** — University of Pennsylvania *(Mar 2026)*

---

## 🔬 Research & Projects

### **MSc Thesis: Decoding Feedback Loop Response to Oscillatory Signals**
*Completed at AIMS Ghana (2025)*

My research focused on the mathematical mechanics of biological regulatory pathways and system stability:
- **Oscillatory Dynamics:** Analysed how negative feedback loops respond to periodic signals — a concept directly applicable to modelling financial market cycles and asset volatility.
- **Mathematical Modelling:** Applied differential equations to evaluate system stability and signal processing within biochemical networks.
- **System Analysis:** Studied how timing and degradation rates determine the success of oscillations in repressive feedback networks.

---

### ⚡ [Zambia Energy Security Risk Model](https://github.com/BoldwinMax/Zambia-Energy-Security-Risk-Model)
*Motivated by conflicting signals: ZESCO's no-load-shedding assurances vs renewed El Niño warnings from climate scientists.*

Built a quantitative risk model answering two questions: what actually drives load-shedding in Zambia, and how bad could it get at any given reservoir level?

- Assembled **25 years of data** — Lake Kariba satellite water levels, NOAA El Niño index, ERB generation statistics, GDP, and a carefully sourced load-shedding record.
- Compared OLS regression, a Kariba-only specification, and quantile regression to capture tail risk.
- **Key finding:** one equation explains 53% of variation: `Load-shedding ≈ 16.1 − 0.21 × (Kariba % full)`
- El Niño is the root cause, but Kariba is the mechanism — once reservoir level is known, the climate index adds almost no predictive power.
- Risk is asymmetric: at 20% full, a typical year means ~8 hours of daily cuts, but a bad year reaches 18+.
- **Verdict:** the 2025–26 solar build-out has reduced exposure, but with hydro dominating capacity, a severe El Niño would still bite. The risk has been reduced, not removed.

---

### 🌽 [Zambia FRA Maize Floor Price Predictor](https://github.com/BoldwinMax/Zambia-FRA-Maize-Price-Prediction) — [Live App ↗](https://zambia-fra-maize-price.streamlit.app/)
*Forecasting Zambia's annual FRA maize floor price ahead of the official government announcement.*

<!-- REPLACE the line below with your actual GIF filename once uploaded to this repo -->
![App Demo](https://github.com/BoldwinMax/Zambia-FRA-Maize-Price-Prediction/blob/main/demo.gif?raw=true)

- Built a **Ridge regression model** trained on 24 years of historical FRA pricing decisions.
- Integrates **live World Bank and FRED APIs** (exchange rate, inflation, global maize prices) with embedded crop forecast data.
- Model achieves **MAE = K14.5 per 50 kg bag, R² = 0.93** via leave-one-out cross-validation.
- Dominant drivers: previous year's price (standardised coefficient +57) and kwacha/USD exchange rate (+35).
- Deployed as an interactive **Streamlit app** — users adjust key assumptions via sliders and see the predicted price update in real time.
- **2026 prediction:** K356 per 50 kg bag (range K341–K371) under ZMW 28/USD assumption; revised to K310–330 under current market rate of ZMW 17–19.

---

### 💱 [Zambia Kwacha Exchange Rate Forecasting](https://github.com/BoldwinMax/zambia-exchange-rate-forecasting)
*What drives the Kwacha/USD rate — and can it be forecast?*

- Built a trend-volatility decomposition model using genuine monthly data from the **Bank of Zambia, CSO Zambia, and IMF**.
- Applied **Gradient Boosting with pinball loss** for quantile forecasting, producing prediction intervals rather than single-point forecasts.
- **Central finding:** FX reserves explain ~50% of Kwacha movements — the single strongest predictor in the model.
- Covers macroeconomic drivers including copper prices, inflation, and current account balance.

---

### 📊 [Zambia Macroeconomic Recovery Analysis (2015–2025)](https://github.com/BoldwinMax/Zambia-Macroeconomic-Recovery-2015-2025)
*Was Zambia's post-2020 recovery driven by the copper price supercycle, the 2023 G20 debt restructuring deal, or both?*

- Built an interactive **6-page Power BI report** structuring the recovery into four distinct phases (2015–2024), with a Q1 2026 update.
- Data sources: Bank of Zambia, Ministry of Finance, Zambia Statistics Agency, World Bank, IMF.
- **Key findings:** copper prices nearly doubled 2020–2021 ($5.5K → $9.3K/mt); current account swung from -3.6% to +11.9% of GDP; mineral rents rose from 3% to ~28% of GDP; FDI surged to 9.32% of GDP in 2024 following Eurobond restructuring.
- **Verdict:** copper triggered the recovery; the 2023 debt deal sustained it.
- Includes five strategic recommendations and a 2026 scenario outlook.
- Accompanied by a **[3-page executive summary PDF](https://github.com/BoldwinMax/Zambia-Macroeconomic-Recovery-2015-2025/blob/main/Zambia-Recovery-Executive-Summary.pdf)**.

---

### 👥 [Customer Churn Prediction — Machine Learning](https://github.com/BoldwinMax/customer-churn-prediction)

Built and compared churn prediction models to identify at-risk customers:
- Implemented **XGBoost and Logistic Regression** with engineered features and RobustScaler preprocessing.
- Applied **SMOTE** for class imbalance and recursive feature elimination for feature selection.
- XGBoost improved recall from **0.22 to 0.52** and ROC-AUC from **0.80 to 0.84** — correctly identifying more than twice as many at-risk customers.

---

### 📦 Integrated Sales & Supply Chain Optimization
Consolidated disparate monthly sales datasets into a unified data model for NorthWind Outfitters:
- Used **Power Query and XLOOKUP** to track revenue trends, profit margins, and regional performance.
- Optimised inventory control by monitoring stock levels, reorder points, and supplier lead times.
- Built evidence-based visual frameworks to diagnose operational inefficiencies.

---

## 🎓 Teaching & Mentorship

### **Mathematics Teaching Assistant | Levy Mwanawasa Medical University (LMMU)**
*Jul 2022 – Feb 2024*
- Taught mathematics to cohorts of **400+ IBBS students per intake**, combining lecture-based instruction with one-on-one tutoring for students struggling with core concepts.
- Improved **pass rates by 15%** through targeted one-on-one support.
- Supported coursework grading and maintained academic records for assigned cohorts.

---

### 💼 Professional Experience

#### **Data Analyst Trainee | FSI Outsourcing** — *Lusaka, Zambia | Feb 2026 – Present*
- Collaborated with stakeholders to translate data needs into **5 Power BI and Excel dashboards**, delivering on a weekly cadence using real company data.
- Performed data quality checks and end-to-end cleaning and transformation to produce reliable, decision-ready reporting.
- Presented findings and recommendations directly to stakeholders each week, supporting data-driven business decisions.

---

## 🛠 Tech Stack

#### 💻 Programming & Databases
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/sql-%23007ACC.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)

#### 🤖 Machine Learning & Statistical Modelling
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-0079C1?style=for-the-badge)
![Statsmodels](https://img.shields.io/badge/Statsmodels-Statistical%20Modeling-blue?style=for-the-badge)

#### 📊 Data Manipulation & Visualization
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-44a8a1?style=for-the-badge)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-ffffff?style=for-the-badge&logo=python&logoColor=black)

#### 📈 Business Intelligence
![Power BI](https://img.shields.io/badge/Power%20BI-PL--300-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-VBA%20%2F%20Macros-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

#### ⚙️ Tools
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

---

## 📊 GitHub Activity
<table>
  <tr>
    <td>
      <img src="https://github-readme-stats.vercel.app/api?username=BoldwinMax&show_icons=true&theme=dark&hide_border=true&include_all_commits=true&count_private=true" />
    </td>
    <td>
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=BoldwinMax&theme=dark&hide_border=true" />
    </td>
    <td>
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=BoldwinMax&layout=compact&theme=dark&hide_border=true" />
    </td>
  </tr>
</table>
