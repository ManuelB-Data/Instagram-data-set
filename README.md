# 📊 Instagram Top Accounts & Audience Concentration Analysis

## 📌 Project Overview
This project explores global social media influence by analyzing **38,071 records** across **11,998 unique top Instagram accounts** tracked between **September and October 2026**. 

The objective of this analysis is to clean, standardize, and visualize audience distribution across account types (Individuals vs. Organizations/Brands), content categories, and geographical markets to uncover where global digital reach is concentrated.

---

## 🛠️ Tools & Skills Applied
* **Microsoft Excel:** Data cleaning, null value imputation, duplicate inspection, text standardization, and Pivot Table modeling.
* **Looker Studio:** Interactive Business Intelligence dashboard design and visual storytelling.
* **Data Quality Assurance (QA):** Schema validation, anomaly detection, and multi-market attribute preservation.

---

## 🧹 Data Cleaning & Transformation Process
Before building the visualizations, the raw dataset underwent a structured quality assurance and cleaning workflow in Excel:

1. **Structural Cleanup:** Inspected and removed empty/unused worksheets to ensure a clean, single-source tabular structure (`38,071 rows × 10 columns`).
2. **Data Type Standardization:** Formatted timestamps into standard date formats and verified numerical constraints on followers and rankings.
3. **Geographic Imputation (`countries`):** Identified missing country values for accounts operating across borderless markets and systematically imputed **`Global`** to accurately reflect worldwide reach rather than discarding valuable records.
4. **Multi-Category Preservation (`also_in`):** Retained secondary niche attributes to preserve cross-industry visibility for accounts spanning multiple categories (e.g., *Music* and *Film & TV*).
5. **Entity Classification (`type`):** Validated the binary segmentation between individual creators (`person`) and corporate/institutional entities (`org`).

---

## 💡 Key Analytical Insights

* **Individuals Dominate Total Reach:** While individual creators (`person`) represent **62.6%** of unique accounts, they capture nearly **80% of the total follower audience**, significantly outperforming organizations and brands (`org`).
* **Top Performers:** **Instagram's official account** leads the platform (~686.4M followers), closely followed by sports icons **Cristiano Ronaldo** (~679.8M) and **Leo Messi** (~517.6M), alongside top music and entertainment stars.
* **Category Concentration:** **Music**, **Film & TV**, and **Sports** are the top three categories by follower volume, far ahead of corporate brands and fashion.
* **Geographic Distribution:** The **United States (US)** holds the largest share of top-account audience concentration, followed by major global hubs like **India (IN)**, the **United Kingdom (GB)**, **South Korea (KR)**, and accounts with a truly **Global** footprint.

---

## 📈 Dashboard & Files

* 📊 **Interactive Looker Studio Dashboard:** [View Live Dashboard Here] https://datastudio.google.com/s/vM1GrWLBse8
* 📂 **Cleaned Dataset:** You can check the processed Excel file (`instagram-data-set.xlsx`) directly in the `data/` folder of this repository.

---

## 📁 Repository Structure
```text
├── README.md
├── data/
│   └── instagram-data-set.xlsx  # Cleaned dataset ready for analysis
