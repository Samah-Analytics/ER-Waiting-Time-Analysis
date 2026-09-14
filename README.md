# 🏥 Emergency Room Waiting Time & Patient Admission Analysis

## ⚠️ Operational Challenges & Problem Statement
The hospital is facing severe operational gaps in the Emergency Room, leading to heavy crowding and long patient delays. Management knows there is an efficiency issue but lacks the visibility to pinpoint exactly where the operational bottlenecks are occurring.

## 🎯 Project Objective
This dashboard was built to map out patient flow, compare admission rates, and highlight specific gaps so leadership can take direct, data-backed action to fix the ER system.

## 📊 Key Insights
* **Admission Volume:** Total emergency room traffic reached 9.21K patients, consisting of 4,612 admitted and 4,604 non-admitted individuals (an almost exact 50/50 split).
* **ER Patient Satisfaction:** The overall average patient satisfaction score for the Emergency Room stands at 1.36 out of 5.
* **Average Wait Duration:** The average baseline waiting duration for an incoming ER patient is 35.26 minutes.
  
<img width="768" height="429" alt="dashboard_preview" src="https://github.com" />

## 🛠️ Tech Stack & Tools
* **Data Visualization:** Power BI Desktop
* **Data Source:** Mock Healthcare Dataset (CSV)
* **Documentation:** GitHub & Markdown

## 🔄 The Workflow
1. **Data Gathering:** Structured ER patient logs including timestamp data, patient status, and triage scores.
2. **Data Transformation:** Cleaned dates, calculated waiting durations, and grouped ages using Power Query.
3. **Dashboard Design:** Developed interactive visuals focused on patient flow metrics and volume trends.

## 🚀 Strategic Recommendations & Next Steps
* **Investigate Wait Time Mismatches:** Launch a deep data audit to investigate the severe logical mismatch between the recorded 35-minute average wait time and the critically low 1.40 patient satisfaction rate. Because a 35-minute wait time is operationally efficient, the low satisfaction score suggests that this metric strictly captures "time-to-triage" and completely hides massive downstream delays (such as waiting hours for a physician, lab results, or an open bed).
* **Audit Non-Admission Volumes:** Investigate why non-admitted patient volume is disproportionately high. I recommend gathering direct feedback from the ER front desk staff and conducting a deeper system review to uncover the underlying operational reasons behind why so many patients are sent home without admission.
* **Revamp Patient Feedback Surveys:** Redesign the patient satisfaction tracking system. Instead of a single raw score, we need targeted feedback metrics that allow patients to rate specific touchpoints, including the quality of service, actual wait durations, and whether their care expectations were met.
* **Engage Frontline ER Staff:** Gather ideas and feedback directly from the ER medical and administrative teams. Listening to the frontline staff will provide crucial operational context to help optimize workflows, reduce patient waiting times, and boost overall ER efficiency.

