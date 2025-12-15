# 📈 Customer Behavior Analysis: An End-to-End Analytics Workflow

The live, interactive dashboard can be viewed here:
➡️ **[Dashboard Link](https://app.powerbi.com/view?r=eyJrIjoiODAwMmRiNWItYjZkMi00ODMyLWFmMDEtMDM3NzNiYTlmY2ZmIiwidCI6IjEzMjc0YTYzLTYzNDEtNDQ3Yi1iNTM0LTdkNzRhYWM2MTc5MSJ9)**

----
This repository showcases a complete, industry-standard data analytics project designed to reflect the real-world responsibilities of a professional data analyst. The workflow covers the full project lifecycle, from raw data ingestion and preparation to advanced modeling, insight generation, and executive reporting.

This project is a strong demonstration of proficiency across the modern analytical stack: **Python**, **SQL (PostgreSQL)**, and **Power BI**.

## 📌 Project Summary

The core objective of this project is to analyze raw retail customer transaction data to identify key purchasing patterns, segment the customer base, and translate these findings into strategic business intelligence.

**Key Deliverables:**

  * **Actionable Customer Segments:** Defined segments based on purchasing behavior (e.g., high-value, at-risk, loyal).
  * **Database Integration:** Scalable data storage and retrieval using PostgreSQL.
  * **Interactive Dashboard:** A Power BI report enabling stakeholders to monitor segment performance and key trends.
  * **Strategic Recommendations:** A formal report detailing findings and business recommendations for targeted marketing and retention strategies.

## 🛠️ Technical Stack

| Component | Technology | Role in Project |
| :--- | :--- | :--- |
| **Data Preparation & Modeling** | **Python** (Pandas, Scikit-learn) | Data cleaning, feature engineering, and applying machine learning or analytical methods for customer segmentation. |
| **Data Management** | **PostgreSQL** | Used for creating an Analytical Base Table (ABT), efficient storage of processed data, and complex transactional querying. |
| **Business Intelligence** | **Power BI** | Development of an interactive, drill-down dashboard for consumption by non-technical stakeholders. |

## 🚀 Analytical Workflow

The project follows a robust three-phase pipeline:

1.  **Data Ingestion & Transformation (Python):**
      * Load raw data, perform extensive Exploratory Data Analysis (EDA).
      * Handle missing values, outliers, and data type conversions.
      * Execute the segmentation model (e.g., RFM analysis or K-Means clustering) to assign segment labels.
2.  **Database Integration & Deep Dive Analysis (PostgreSQL):**
      * Export the cleaned and segmented dataset from Python into a dedicated PostgreSQL database.
      * Run complex SQL queries to simulate business transactions, extract loyalty metrics, and validate segment definitions.
3.  **Visualization & Reporting (Power BI):**
      * Connect Power BI directly to the PostgreSQL database for real-time data access.
      * Design a dashboard that visually communicates segment profiles, purchase drivers, and key performance indicators (KPIs).
      * Compile a final report summarizing all findings and presenting actionable business recommendations.

## 💻 Replication Guide

To replicate and explore this project locally, follow these steps:

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/mmgarg/customer_behavior_analysis.git
    cd customer_behavior_analysis
    ```
2.  **Execute Python Script:**
      * Open and run the steps in `Customer_Shopping_Behavior_Analysis.ipynb`.
      * This notebook handles data cleaning and connects to your local SQL server instance.
3.  **Load Data and Query:**
      * Create a database in your PostgreSQL instance.
      * Use the provided Python code to load the processed data.
      * Execute the analytical queries found in `customer_behavior_sql_queries.sql` to derive business insights.
4.  **Visualize Results:**
      * Open `customer_behavior_dashboard.pbix` in Power BI.
      * Update the data source connection to link to your local PostgreSQL database.
