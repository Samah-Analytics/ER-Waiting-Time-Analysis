# 🏥 Emergency Room Waiting Time & Patient Admission Analysis

## 📌 Project Overview
I built this Power Bi dahsbaord to analyze Emergncy Room patient data. The dashbaord looks at patient volume, waiting time, satisfaction, and admission patterns.

The goal was to identify possible operational bottlenecks and areas for further investigation. 

## 📊 Key Insights
* **Admission Volume:** Total emergency room traffic reached 9.21K patients, consisting of 4,612 admitted and 4,604 non-admitted individuals (an almost exact 50/50 split).
* **ER Patient Satisfaction:** The overall average patient satisfaction score for the Emergency Room stands at 1.36 out of 5.
* **Average Wait Duration:** The average baseline waiting duration for an incoming ER patient is 35.26 minutes.
  
## 📈 Visualized Dashboards & Charts

| Dashboard Preview | Admission Volume | Patient Referral |
| :---: | :---: | :---: |
| <img src="Asstest/Dashboard%20Preview.png" width="260" height="180" /> | <img src="Asstest/Admitted%20Vs%20Not%20Admitted.png" width="260" height="180" /> |  |
 

## 🛠️ Tech Stack & Tools
* **Data Visualization:** Power BI Desktop
* **Data Source:** Mock Healthcare Dataset (CSV)
* **Documentation:** GitHub & Markdown

## 🔄 The Workflow
1. **Data Gathering:** Structured ER patient logs including timestamp data, patient status, and triage scores.
2. **Data Transformation:** Cleaned dates, calculated waiting durations, and grouped ages using Power Query.
3. **Dashboard Design:** Developed interactive visuals focused on patient flow metrics and volume trends.

##🔎 **Recommendations**

1. **Clarify the waiting-time data**
The reported average waiting time is 35.26 minutes, but the dataset does not clearly explain what this waiting time represents. Before using it to make operational decisions, I would verify whether it measures time to triage, first assessment, treatment, or another stage of the ER process.

2. **Improve the data available for analysis**
More detailed timestamps would make the analysis much more useful—for example, arrival, triage, first assessment, treatment, admission/discharge, and total ER stay. This would help identify exactly where delays occur rather than relying on one overall waiting-time measure.


