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

**National Trends**<br>
USA Dominance:<br>
1. Swimming: Consistent leader; nearly 70 medals in 2016.
2. Athletics: Fluctuations, but top rank held since 1988.<br>

Rising Nations:<br>
1. Great Britain in Rowing: Strong medal growth post-2000. <br>

Highly Competitive Disciplines:<br>
1. Ice Hockey: Ongoing Canada-USA rivalry since 2010.
2. Fencing: No consistent leader—Italy saw a decline post-2012.<br>
---


## 💡 Insights & Implications
- Gender Equity: Strong evidence of progress in women’s participation. Policy and investment are paying off.
- Beyond Physical Metrics: Success is driven more by training, technique, and strategy than by age or physique alone.
- Strategic Investment Yields Results: Countries that back structured programs (e.g., GBR in rowing) see measurable performance gains.

---

## 🎯 Recommendations
For Olympic Committees: <br>
- Sustain funding in historically strong disciplines (e.g., USA in swimming).
- For emerging nations: Invest in female-focused programs and underdog sports with high ROI potential.

For Researchers:<br>
- Explore skill vs. physical-based predictors for medal outcomes.
- Analyze competitive density—does increased global participation correlate with more equitable medal distribution?

---

## 📂 Technologies Used
- Python (Pandas, Matplotlib, Seaborn, Scikit-learn)
- SQL (sq lite)
- Jupyter Notebooks
- Data Visualization (Treemaps, Line Charts, Stacked Bar Charts)
---

## 📁 Files

- [Download Jupyter Notebook](notebook/Olympics%20120%20Years%20Demographic%20.ipynb)
- [Download pdf](pdf/SaaS_Customer_Churn_Analysis.pdf)
- [Download Raw Data File](data/WA_Fn-UseC_-Telco-Customer-Churn.csv)
- [Download Dashboard image](images/dashboard_overview.png)
- `README.md`

![Dashboard Preview](images/dashboard_overview.png)
---
