# 🏅 Olympic Data Analysis: Gender, Performance, and National Trends

## 🔍 Project Overview

This project analyzes over 120 years of Olympic Games data to explore trends in athlete demographics, gender participation, and national dominance in medal-winning across disciplines. The analysis uses Python, SQL, and data visualization techniques to test several hypotheses around performance drivers and systemic trends.

---

## 📌 Initial Hypotheses

1. Gender Shift: Female athlete participation has increased significantly in traditionally male-dominated sports post-2000.
2. Body Attributes & Success: Athletes with above-average height and weight are more likely to win medals in strength-based sports (e.g., weightlifting, rowing).
3. National Dominance: Wealthier or historically dominant Olympic nations (e.g., USA, China, Russia) consistently outperform smaller nations in overall medal counts.

## 🧭 Analytical Approach
**Data Exploration**<br>
Track Olympic participation over time:<br>
- Number of NOCs
- Number of events
- Number of athletes
- Visualize distributions of age, height, and weight via boxplots and histograms.
- Identify outliers and data irregularities.

**Hypothesis Testing**<br>
Gender Participation Trends:<br>
- Stacked bar charts of male vs. female participation per year.
- Identify sports with the most growth in female representation (1996–2016) via SQL/Python.
Logistic Regression Models:<br>
- Assess if age, height, and weight significantly predict medal success.
- Run both overall and sport-specific analyses.
Country-Sport Dominance:<br>
- Use SQL and treemaps to explore which nations dominate in Athletics, Swimming, Rowing, Fencing, and Ice Hockey.
- Analyze medal progression trends (1988–2016).
---

## 📈 Key Findings

**Gender Participation**<br>
- Steady Growth: Female athlete participation increased from near 0% in 1896 to nearly 45% in 2016.
Leading Sports (1996–2016 growth):<br>
- 🥇 Cycling: +66.9%
- 🥈 Synchronized Swimming: +63.9%
- 🥉 Football: +63.7%

**Physical Attributes vs. Medal Success**<br>
- Low Correlation: Age, height, and weight showed minimal predictive power for medal-winning.
- Sport-Specific Nuance: Slight advantages for taller/heavier athletes in power sports, but not universally significant.

National Trends
	•	USA Dominance:
	•	Swimming: Consistent leader; nearly 70 medals in 2016.
	•	Athletics: Fluctuations, but top rank held since 1988.
	•	Rising Nations:
	•	Great Britain in Rowing: Strong medal growth post-2000.
	•	Highly Competitive Disciplines:
	•	Ice Hockey: Ongoing Canada-USA rivalry since 2010.
	•	Fencing: No consistent leader—Italy saw a decline post-2012.
---

## 📊 Dashboard Visuals

| Visual | Description |
|--------|-------------|
| 🔁 Donut Chart | Churned vs Non-Churned Customers |
| 📊 Bar Chart | Revenue Loss by Churn|
| 📊 Bar Chart | Contract Type of Churn|
| 📊 Bar Chart | Tenure Length of Churn|
| 📊 Bar Chart | Payment and Billing Preference for Churned Customers |
| 🔁 Donut Chart | Churned Customers Demographic|
| 🔁 Donut Chart | Services Churned|
| 🧠 Tooltip Page| Key Insights |

---

## 🔍 Key Insights

**🧠 No Dependents = Higher Churn:**
- Only 17% of churned customers have dependents.

**📉 Tenure < 6 Months = Risk Zone:**
- 42% of churn happens within first 6 months.

**🧬Non Senior Citizens = Higher Churn:**
- Around 75% of churn are non-Senior Citizens. 

**💸 Electronic Check = Risky:**
- Nearly 46% of churned customers paid via electronic check.

---

## 🛠 Tools Used

- Power BI
- DAX
---

## 📁 Files

- [Download Power BI File](Power%20BI/SaaS%20Customer%20Churn%20Analysis.pbix)
- [Download pdf](pdf/SaaS_Customer_Churn_Analysis.pdf)
- [Download Raw Data File](data/WA_Fn-UseC_-Telco-Customer-Churn.csv)
- [Download Dashboard image](images/dashboard_overview.png)
- `README.md`

![Dashboard Preview](images/dashboard_overview.png)
---

