# 🌍 Global Job Layoffs Analysis (2020–2023)

## 📌 Project Overview
This project analyzes global job layoffs between 2020 and 2023 using a dataset sourced from Kaggle. The goal was to clean, transform, and analyze the data to uncover trends in layoffs across industries, regions, and time.

The analysis focuses on understanding how different sectors and countries were impacted, especially during the COVID-19 pandemic period.

---

## 🛠️ Tools & Technologies
- **MySQL** – Data cleaning, transformation, and analysis  
- **Advanced SQL** – Joins, CTEs, Window Functions  
- **Kaggle Dataset** – Layoffs dataset  

---

## 📂 Table of Contents
1. Dataset  
2. Methodology  
3. Analysis Process  
4. Results & Insights  
5. Technologies Used  
6. How to Use  
7. Conclusion  

---

## 📊 Dataset

**Source:** Kaggle – *Layoffs Dataset*  

### 📌 Columns:
- **Company** – Name of the company  
- **Location** – City/location of the company  
- **Industry** – Industry type (Tech, Healthcare, Crypto, etc.)  
- **Total_Laid_Off** – Number of employees laid off  
- **Percentage_Laid_Off** – Layoffs as a percentage of workforce  
- **Date** – Date of layoffs  
- **Stage** – Funding stage (Series A, B, C, etc.)  
- **Country** – Country of the company  
- **Funds_Raised_in_Millions** – Total funding raised  

📈 The dataset contains thousands of records across multiple industries and regions.

---

## ⚙️ Methodology

### 🧹 1. Data Cleaning
- Removed duplicate records  
- Handled missing values in key columns  
- Standardized and normalized numerical data  
- Ensured consistency across fields  

### 📊 2. Exploratory Data Analysis (EDA)
- Used **CTEs** for modular query building  
- Applied **Joins** to combine datasets  
- Leveraged **Window Functions** for ranking and trend analysis  

---

## 🔍 Analysis Process

### 1. Understanding the Data
- Explored structure and column types  
- Defined key business questions:
  - Which industries were most affected?
  - Which regions had the highest layoffs?
  - How did layoffs change over time?

### 2. Data Preparation
- Cleaned and standardized the dataset  
- Ensured data quality for accurate analysis  

### 3. SQL-Based Analysis

#### 📅 Temporal Trends
- Analyzed layoffs by year, quarter, and month  
- Identified peak layoff periods  

#### 🏭 Industry Analysis
- Compared layoffs across industries  
- Identified most impacted sectors  

#### 🌍 Regional Analysis
- Evaluated layoffs by country and region  
- Highlighted global patterns  

#### 💼 Company Stage Analysis
- Examined layoffs based on funding stage  
- Analyzed correlation between funding and layoffs  

---

## 📈 Results & Insights

### 🔥 Key Findings:

#### 🦠 Pandemic Impact
- Significant spike in layoffs in **2020 (Q2 & Q3)**  
- Driven by the global COVID-19 crisis  

#### 🏭 Industry Trends
- **Technology, Transportation, and Retail** were heavily impacted  
- **Healthcare** remained relatively stable  

#### 🌍 Regional Insights
- Highest layoffs in:
  - 🇺🇸 USA  
  - 🇬🇧 UK  
  - 🇩🇪 Germany  
- Asia showed faster recovery post-2021  

#### 💰 Company Stage Insights
- Late-stage companies (**Series D, E**) had higher layoffs  
- Likely due to operational costs and funding pressures  

---

## 🧪 Technologies Used

| Tool       | Purpose                          |
|------------|----------------------------------|
| MySQL      | Data storage & querying          |
| SQL        | Data cleaning & analysis         |
| Kaggle     | Dataset source                   |

---

## ▶️ How to Use

1. Import the dataset into MySQL  
2. Run the SQL scripts for:
   - Data cleaning  
   - Transformation  
   - Analysis  
3. Explore insights using the queries provided  

---

## 🧠 Conclusion

This project highlights how global events like COVID-19 significantly impacted employment trends across industries and regions.

Using SQL-based analysis, we uncovered:
- Key industry vulnerabilities  
- Regional disparities  
- Trends over time  

This analysis demonstrates the power of data-driven insights in understanding real-world economic shifts.

---

⭐ *If you found this project useful, feel free to star the repository!*
Conclusion

This project sheds light on the global impact of layoffs from 2020 to 2023. The analysis provided valuable insights into the industries and regions that were hit hardest, as well as trends over time. By leveraging advanced SQL queries and data-cleaning techniques, we gained a deeper understanding of the economic effects caused by the pandemic.
