# Customer Shopping Behavior Analysis
## Developed by: Shreesha Shetty

---

## 📊 1. Project Overview
This project delivers an end-to-end data analytics solution evaluating customer shopping behavior using transactional records across multiple product categories. The core objective is to architect an automated data pipeline that ingests raw retail logs, cleans and normalizes anomalies, performs deep relational querying via SQL, and visualizes macro operational indicators through an interactive Power BI business intelligence dashboard. These insights are targeted toward optimization of customer retention frameworks, subscription funnel conversion, and structural logistics refinement.

### 📂 Repository File Architecture
* `Customer_Shopping_Behaviour_Analysis.ipynb`: Python data engineering, preprocessing, and ETL pipeline.
* `Customer_Shopping_Behavior.sql`: Production-grade SQL script containing advanced analytical views.
* `Customer_Behavior_Dashboard.pbix`: Native Power BI application containing interactive data models.
* `customer_shopping_behavior.csv`: Cleaned dataset utilized for production deployment.
* `Customer Shopping Behavior Analysis.pdf`: Comprehensive project report presentation.
* `dashboard.png`: Screenshot of the core data visual layer.

---

## 🛠️ 2. Technology Stack & Environment
* **Data Engineering & ETL:** Python (Pandas, NumPy, SQLAlchemy)
* **Relational Database Layer:** MySQL Server
* **Business Intelligence & Analytics:** Power BI Desktop
* **Documentation & Storage:** Markdown, Git

---

## 🐍 3. Data Engineering & Preprocessing Pipeline (Python)
The project initial phase focused on building a clean ETL pipeline in Python to convert unstructured raw transaction entries into a strict relational format:
* **Data Auditing & Schema Validation:** Imported core datasets using Pandas, conducting validation checks via `df.info()` and statistical metrics profiles.
* **Statistical Imputation:** Identified 37 structural missing records localized in the review rating attribute. These null records were programmatically resolved by applying a median rating calculation mapped to each specific product category.
* **Database Optimization:** Standardized column naming structures into a consistent `snake_case` taxonomy to maintain system readability and support rapid query execution across database joins.
* **Feature Engineering Tiers:** Designed explicit
