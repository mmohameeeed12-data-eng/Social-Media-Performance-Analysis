# Social Media Performance Analysis Dashboard

An end-to-end Data Analytics project developed during my summer training at the **National Telecommunication Institute (NTI)**. This project evaluates social media engagement across multiple accounts, channels, and content formats to help stakeholders make data-driven strategy adjustments.

---

## 📌 Project Overview

Understanding performance patterns across various social media platforms is crucial for maximizing reach and engagement. This project transforms raw social media interaction data into an interactive, multi-page Power BI dashboard that uncovers:
* Peak days for content reach and audience interaction.
* Performance comparison across content categories (e.g., Entertainment, Education, Sports).
* Distribution of engagement metrics (Reach, Likes, Comments, Shares, Organic vs. Sponsored).

---

## 🏗️ Data Architecture & Modeling

The project utilizes a **Star Schema** data model built in Power BI to ensure efficient querying, scalability, and clear analytical relationships.

### Schema Structure:
* **`Fact_Table`**: Central fact table storing transactional performance metrics (`Impressions`, `Reach`, `Likes`, `Comments_Count`, `Shares`, `Followers_At_Post`, `Is_Sponsored`).
* **`Dim_Date`**: Dimension table managing time-based attributes (`Date`, `Day`, `Day of Week`, `Month`, `Quarter`, `Year`, `Is_Weekend`).
* **`Dim_Platform`**: Dimension table storing channel details (`Platform_id`, `Platform`).
* **`Dim_Account`**: Dimension table tracking creator and brand accounts (`Account_id`, `Account_Name`).
* **`Dim_PostType`**: Dimension table categorizing post formats (`PostType_ID`, `Post_Type`).

---

## 📊 Key Findings & Business Insights

1. **Optimal Posting Days:**
   * Mid-week days, specifically **Day 4** (~21.49K avg. reach) and **Day 3** (~21.14K avg. reach), yield the highest performance.
2. **Top Content Categories:**
   * **Entertainment (ترفيه)** generated the highest total reach (~11.8M) and share rates, followed by **Education (تعليم)** and **Sports (رياضة)**.
3. **Strategic Recommendations:**
   * Implement a **40/30/30 content distribution strategy**: Allocate 40% of production effort to Entertainment, 30% to Education, and 30% across other verticals.
   * Focus production efforts on short-form interactive video formats to optimize user shareability.

---

## 🛠️ Tools & Technologies Used

* **Power BI**: Data modeling, DAX measures, and dashboard visualization.
* **Power Query**: Data cleaning, transformation, and attribute profiling.
* **Data Modeling**: Relational Star Schema architecture.
