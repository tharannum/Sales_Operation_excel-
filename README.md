
# 📈 Excel Sales Data Analysis Project

This project demonstrates how to use **Pivot Tables**, **Slicers**, and **interactive reporting techniques** in Microsoft Excel to analyze sales performance across sectors, locations, and time periods. The goal is to transform raw transactional sales data into actionable business intelligence for decision-making.

---

## 🎯 Project Objectives

* **Data Aggregation:** Summarize large volumes of sales transactions efficiently using Pivot Tables.
* **Interactive Reporting:** Build dynamic and filterable reports using Slicers and Timelines.
* **Sector & Regional Trend Analysis:** Identify performance patterns across countries, quarters, and industry sectors.
* **Deal Metrics:** Calculate KPIs like **Deal Won**, **Average Deal Won**, and **Price Realization**.

---

## 📁 Raw Data (Dataset Overview)

The analysis is built on a dataset containing detailed sales records. Key columns include:

| Column          | Description                                       |
| --------------- | ------------------------------------------------- |
| **Sales Agent** | Name of the sales representative                  |
| **Region**      | Region of the sale (Central, East, West)          |
| **Sector**      | Industry sector (Retail, Medical, Software, etc.) |
| **Location**    | Country where the deal closed                     |
| **Deal Stage**  | Status of the deal (Closed, Engaging, etc.)       |
| **Close Date**  | Date the deal was finalized                       |
| **Deal Won**    | Value of the deal won                             |
| **Close Value** | Potential full value of the deal                  |

---

# 🛠️ Key Components and Techniques

The workbook contains **three main reporting sheets**, all linked via the same Pivot Table data model.

---

## 1️⃣ **Account Report**

Focuses on overall profitability and deal value.

**Metrics Included:**

* **Total Deal Won**
* **Price Realization** (Deal Won ÷ Close Value)

**Interactivity:**

* Location Slicer
* Quarter/Year Timeline Slicer

---

## 2️⃣ **Stage of Funnel Report**

Shows the total value of deals that reached the **Closed** stage.

**Setup:**

* Rows: *Deal Stage*
* Value: *Sum of Deal Won*
* Filtered for *Closed* deals
* Sector Slicer for industry-specific analysis

---

## 3️⃣ **Sales Manager Report**

Compares performance across sales managers.

**Metrics Included:**

* **Count of Opportunity ID**
* **Average Deal Won**

**Custom Formatting:**

* Conditional Formatting (Color Scales) to visualize high and low performers.

**Filters:**

* Sector Slicer

---

# 📊 Project Outcomes

## 🧑‍💻 Technical Output (For Data Analysts)

| Sheet                    | Rows/Columns          | Measures                           | Customizations          |
| ------------------------ | --------------------- | ---------------------------------- | ----------------------- |
| **Account Report**       | Account Name          | Sum of Deal Won, Price Realization | Location & Date Slicers |
| **Stage of Funnel**      | Deal Stage (“Closed”) | Sum of Deal Won                    | Sector Slicer           |
| **Sales Manager Report** | Sales Manager         | Avg Deal Won, Count Opportunities  | Conditional Formatting  |

---

## 👩‍💼 Business Outcome (For Stakeholders)

The workbook provides **instant, self-service reporting** across:

* Sector
* Country
* Quarter/Year
* Sales Manager

This eliminates manual effort and reduces time spent preparing performance reviews.

> **Deliverable:** A dynamic, interactive sales analysis system suitable for business intelligence reporting.

---

# 🔍 Insights & Recommendations

## 1. **Sector Performance Insights**

| Insight                                                                                  | Recommendation                                           |
| ---------------------------------------------------------------------------------------- | -------------------------------------------------------- |
| Software & Telecom sectors show high deal values but high variance in price realization. | Implement stricter discount controls to protect margins. |
| Medical & Retail sectors show stable performance and consistent price realization.       | Focus on scaling and increasing deal volume.             |

---

## 2. **Geographic & Time-Based Insights**

| Insight                                                                              | Recommendation                                                        |
| ------------------------------------------------------------------------------------ | --------------------------------------------------------------------- |
| The **United States** leads in total deal value, especially in Q3–Q4 2017.           | Increase resource allocation to maintain momentum.                    |
| **China** & **Philippines** show high price realization (60–80%) despite low volume. | Increase lead generation in these markets to leverage strong margins. |

---

# 🔍 Sales Performance Metrics (From Video Demonstration)

## 1️⃣ **Account Report – Philippines (Q4 2017)**

*Filtered at timestamp 0:13*

| Metric                | Value          |
| --------------------- | -------------- |
| **Total Deal Won**    | **$18,046.00** |
| **Price Realization** | **60.08%**     |

✔ High price realization indicates efficient pricing strategy.

---

## 2️⃣ **Stage of Funnel Report – Total Closed Deals**

*Shown at 0:39 before applying any slicers*

| Metric                    | Value      |
| ------------------------- | ---------- |
| **Total Sum of Deal Won** | **$4,238** |

---

## 3️⃣ **Sales Manager Report – Sector: Software**

*Filtered at 0:58*

| Sales Manager   | Count of Opportunity ID | Avg Deal Won |
| --------------- | ----------------------- | ------------ |
| Top Manager     | 203                     | **67%**      |
| Second Manager  | 747                     | **63%**      |
| Third Manager   | 345                     | **63%**      |
| …               | …                       | …            |
| **Grand Total** | **3512**                | **63%**      |

✔ The top performer exceeds the sector average by a strong margin.

---

# ✅ Conclusion

This project demonstrates how Excel Pivot Tables and Slicers can transform raw sales data into actionable insights.
It helps:

* Understand sector profitability
* Compare sales manager performance
* Identify regional trends
* Improve pricing and resource allocation strategies
 

---
 
