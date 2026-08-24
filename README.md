# Social Media Performance Analysis Dashboard

An end-to-end Data Analytics project developed during my summer training at the **National Telecommunication Institute (NTI)**. This project evaluates social media engagement across multiple accounts, channels, and content formats to help stakeholders make data-driven strategy adjustments.

---

## 📌 Main Dashboard Overview

<img width="1416" height="799" alt="Social Media Performance Dashboard" src="https://github.com/user-attachments/assets/2e3cfaeb-86f4-4b01-a91d-ebc3219e10b4" />

Understanding performance patterns across various social media platforms is crucial for maximizing reach and engagement. This project transforms raw social media interaction data into an interactive, multi-page Power BI dashboard that uncovers:
* Peak days for content reach and audience interaction.
* Performance comparison across content categories (e.g., Entertainment, Education, Sports).
* Distribution of engagement metrics (Reach, Likes, Comments, Shares, Organic vs. Sponsored).

---

## 🏗️ Data Architecture & Modeling (Star Schema)

<img width="1089" height="687" alt="Star Schema Data Model" src="https://github.com/user-attachments/assets/5de5df74-5ff4-40fc-a553-089204bb80e8" />

The project utilizes a **Star Schema** data model built in Power BI to ensure efficient querying, scalability, and clear analytical relationships.

### Schema Structure:
* **`Fact_Table`**: Central fact table storing transactional performance metrics (`Impressions`, `Reach`, `Likes`, `Comments_Count`, `Shares`, `Followers_At_Post`, `Is_Sponsored`).
* **`Dim_Date`**: Dimension table managing time-based attributes (`Date`, `Day`, `Day of Week`, `Month`, `Quarter`, `Year`, `Is_Weekend`).
* **`Dim_Platform`**: Dimension table storing channel details (`Platform_id`, `Platform`).
* **`Dim_Account`**: Dimension table tracking creator and brand accounts (`Account_id`, `Account_Name`).
* **`Dim_PostType`**: Dimension table categorizing post formats (`PostType_ID`, `Post_Type`).

---

## 📊 Executive Summary & Business Insights

<img width="1417" height="799" alt="Executive Summary & Recommendations" src="https://github.com/user-attachments/assets/45b53f1f-2c33-4e6b-b852-d992c6e1e460" />

1. **Optimal Posting Days:**
   * Mid-week days, specifically **Day 4** (~21.49K avg. reach) and **Day 3** (~21.14K avg. reach), yield the highest performance.
2. **Top Content Categories:**
   * **Entertainment (ترفيه)** generated the highest total reach (~11.8M) and share rates, followed by **Education (تعليم)** and **Sports (رياضة)**.
3. **Strategic Recommendations:**
   * Implement a **40/30/30 content distribution strategy**: Allocate 40% of production effort to Entertainment, 30% to Education, and 30% across other verticals.
   * Focus production efforts on short-form interactive video formats to optimize user shareability.

---

## 📋 Granular Data View (Details Table)

<img width="1407" height="788" alt="Detailed Data Table View" src="https://github.com/user-attachments/assets/c55f3ad8-d305-48ed-8b33-80adc488f6f9" />

* Dedicated table view allowing granular inspection of raw post-level metrics, post categories, and platforms across years.

---

## 🛠️ Tools & Technologies Used

* **Power BI**: Data modeling, DAX measures, and dashboard visualization.
* **Power Query**: Data cleaning, transformation, and attribute profiling.
* **Data Modeling**: Relational Star Schema architecture.

---

## 🤝 Acknowledgments

Special thanks to the **National Telecommunication Institute (NTI)** for providing this training opportunity, as well as my instructor for their guidance throughout the program.
