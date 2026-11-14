# ecommerce-customer-experience-analysis

An end-to-end data analytics project analyzing **5,000 e-commerce transaction records** to evaluate customer experience patterns, delivery performance, and rating distributions across product categories.

---

## 🚀 Project Overview
This project simulates an operational data workflow—starting from database setup and management in **MySQL**, exploratory data analysis and statistical validation in **Python**, to executive dashboard design in **Looker Studio**. 

The main objective is to identify the key factors influencing customer satisfaction, evaluate the impact of delivery lead times on user ratings, and uncover actionable insights to improve the overall customer journey.

---

## 🛠️ Tech Stack & Tools
* **Database Management:** MySQL / MariaDB (`ecommerce_db`)
* **Data Processing & Analysis:** Python (`pandas`, `sqlalchemy`, `matplotlib`, `seaborn`)
* **Data Visualization & Dashboarding:** Looker Data Studio
* **Version Control:** Git & GitHub

---

## 🔄 Data Pipeline & Workflow
1. **Database Setup & SQL Operations:**
   * Created and structured the relational database (`ecommerce_db`).
   * Performed initial data verification (`SELECT *`) and table standardization (`sales_analytics`).
2. **Exploratory Data Analysis (Python):**
   * Extracted data directly from MySQL using `SQLAlchemy` and `pandas`.
   * Conducted descriptive statistical summaries (`describe()`) across ratings, delivery days, discounts, and revenue.
   * Evaluated customer satisfaction across product categories and analyzed correlations between numerical variables.
3. **Dashboard & Reporting (Looker Studio):**
   * Designed an executive KPI scorecard layout (*Total Revenue*, *Avg. Cust Rating*, *Avg. Delivery Days*, *Total Orders*) with date range controls.
   * Built visual charts illustrating the impact of delivery durations on customer satisfaction and category-level rating distributions.

---

## 💡 Key Findings & Insights
* **Suboptimal Overall Rating:** Across 5,000 records, the average customer rating stands at **2.97 / 5.0**, indicating systemic customer experience issues below the neutral threshold.
* **Absence of Correlation Between Delivery Speed & Ratings:** Boxplot and correlation matrix analyses revealed a uniform distribution of ratings across all delivery lead times (1 to 11 days). Faster shipping (1–3 days) does not inherently yield higher satisfaction scores, nor do longer shipping windows (9–11 days) significantly degrade them.
* **Strategic Recommendation:** Management should redirect focus away from purely optimizing delivery speed and prioritize qualitative improvements—such as product quality, listing accuracy, packaging, and post-purchase customer support.

---

## 📊 Dashboard Preview
*(Upload your Looker Studio screenshot into the `assets/` folder and link it here)*

👉 **[View Live Looker Studio Dashboard](https://datastudio.google.com/reporting/358a4fae-5f1c-4fb7-8e32-39a0dcc2ed78)**

---

## 📁 Repository Structure
```text
├── E-commerce Customer Experience Analysis.ipynb  # Jupyter Notebook containing EDA & statistical analysis
├── query.sql                                       # SQL scripts used for database creation & setup
└── assets/                                         # Dashboard screenshots & images
