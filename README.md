#  Netcom CRM Business Trend Analysis

A complete exploratory data analysis (EDA) of Netcom Service CRM leads dataset, focusing on lead quality, source performance, sales funnel efficiency, and actionable business insights. Built using Jupyter Notebook and visualized in Power BI.

---

##  Project Objective

To analyze the customer lead data from Netcom Service CRM and extract valuable business insights that help improve conversion rates, optimize lead sources, and strengthen sales performance.

---

##  Key Highlights

-  Cleaned and transformed raw CRM data 
-  Feature engineering: Lead timing, status standardization, priority encoding, remark quality scoring
-  Generated 360° lead funnel insights with clear scoring logic
-  Identified high- and low-performing lead sources and sales stages
-  Final cleaned dataset reduced to 353 valid and complete entries
-  Created a Power BI dashboard for business users

---

##  EDA Summary

|  **Category**         |  **Insight**                                                                                                                            |  **Business Recommendation**                                                                              |
| ----------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| **Status Distribution** | Majority of leads are `Closed` or `Follow Up`, indicating good pipeline activity. However, significant `Dropped` leads point to friction. | Investigate reasons for drop-offs. Strengthen lead nurturing and follow-up SOPs.                            |
| **Lead Source Quality** | `Google` and `Cold Call` showed best performance in both volume and conversion quality. `Events` and `Partner Referral` underperformed.   | Increase focus and budget on top-performing sources; re-evaluate or optimize weak lead channels.            |
| **Sales Funnel Stages** | Drop-offs observed at `#3 Quoted` → `#4 Hot` → `#5 Sold`, indicating bottlenecks in mid-to-late sales stages.                             | Improve quoting process with offers, training, or automated follow-ups to push leads further in the funnel. |
| **Priority Tagging**    | `Urgent` leads had higher close rates, but also a high drop rate — possibly due to misclassification.                                     | Refine the criteria for tagging leads as Urgent. Use validation steps to avoid false urgency.               |
| **Temporal Trends**     | Highest lead volume occurred in **March**, especially mid-week (Tuesday–Thursday).                                                        | Plan major campaigns around high-traffic periods. Optimize staffing during peak weekdays.                   |
| **Remarks Quality**     | Leads with rich, detailed remarks had better follow-through and conversions. Poor remarks correlated with low-quality leads.              | Encourage agents to write meaningful notes. Use automation/NLP to flag and improve low-quality remarks.     |
| **Source Category**     | Online channels outperformed offline and referrals in both volume and quality of leads.                                                   | Prioritize digital channels in marketing spend. Reassess the ROI of offline/referral programs.              |


---

##  Files Included

| File                          | Description |
|------------------------------|-------------|
| `final_netcom_analysis.ipynb`| Full cleaned and annotated EDA notebook |
| `netcom_powerbi.pdf`         | Exported Power BI dashboard (read-only) |

>  **Note:** Original CRM Excel files have been excluded for privacy and security reasons.

---

##   Tech Stack

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Jupyter Notebook
- Power BI (Business dashboard)
- Git & GitHub

---
