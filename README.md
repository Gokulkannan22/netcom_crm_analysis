# 📊 Netcom CRM Business Trend Analysis

A complete exploratory data analysis (EDA) of Netcom Service CRM leads dataset, focusing on lead quality, source performance, sales funnel efficiency, and actionable business insights. Built using Jupyter Notebook and visualized in Power BI.

---

## 🧠 Project Objective

To analyze the customer lead data from Netcom Service CRM and extract valuable business insights that help improve conversion rates, optimize lead sources, and strengthen sales performance.

---

## 📌 Key Highlights

- ✅ Cleaned and transformed raw CRM data 
- 🛠️ Feature engineering: Lead timing, status standardization, priority encoding, remark quality scoring
- 📊 Generated 360° lead funnel insights with clear scoring logic
- 💡 Identified high- and low-performing lead sources and sales stages
- 🧼 Final cleaned dataset reduced to 353 valid and complete entries
- 📈 Created a Power BI dashboard for business users

---

## 🔍 EDA Summary

| Category                | Insight |
|------------------------|---------|
| **Status Distribution** | Most leads are `Closed` or in `Follow Up`. Significant `Dropped` leads indicate friction in pipeline. |
| **Lead Source Quality** | `Google` & `Cold Call` performed best. `Events` & `Partner Referral` need improvement. |
| **Sales Funnel**        | Drop-offs observed between `#3 Quoted` → `#4 Hot` → `#5 Sold`. |
| **Priority Leads**      | `Urgent` leads had higher conversion — but many were also dropped. |
| **Temporal Trends**     | Most leads came in March and during mid-week (Tue–Thu). |
| **Remarks Quality**     | Leads with meaningful remarks converted better. |
| **Category Performance**| Online sources performed best in both quantity and quality. |

---

## 📂 Files Included

| File                          | Description |
|------------------------------|-------------|
| `final_netcom_analysis.ipynb`| Full cleaned and annotated EDA notebook |
| `netcom_powerbi.pdf`         | Exported Power BI dashboard (read-only) |

> 🚫 **Note:** Original CRM Excel files have been excluded for privacy and security reasons.

---

## 🛠️ Tech Stack

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Jupyter Notebook
- Power BI (Business dashboard)
- Git & GitHub

---
