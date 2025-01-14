# Medicare_Inpatient_hospitals-Analysis/Visual report


## **Project Objective**
This project analyzes Medicare inpatient hospital discharges and payment data (2017–2022) to uncover trends in healthcare costs, provider performance, and geographic payment distributions. The goal was to provide actionable insights for understanding Medicare payment efficiency and patient cost trends using a dataset of over **1M records** from the [CMS (Centers for Medicare & Medicaid Services) website](https://data.cms.gov/provider-summary-by-type-of-service/medicare-inpatient-hospitals/medicare-inpatient-hospitals-by-provider-and-service/data).

## **Dataset Description**
The dataset contains comprehensive information on inpatient hospital discharges, including:
- Diagnosis-related group (DRG) codes
- Total Medicare payments
- Average provider charges
- Out-of-pocket patient costs
- Geographic locations of providers

It serves as a vital resource for understanding healthcare utilization and financial metrics. 

### **Key Characteristics**
- **Update Frequency**: Updated annually to include the latest discharge data.
- **Format**: CSV files of each year.
- **Focus**: The analysis uses data from **2017 to 2022** to identify trends and insights in Medicare inpatient hospital services.

---

## **Tools & Techniques Used**

### **Technologies Used**
- **Microsoft Excel**: Power Query Editor for data merging and cleaning.
- **SQL**: Advanced query handling and validation.
- **Tableau**: Interactive dashboards for visual analysis.

### **Techniques Employed**
- Data cleaning, transformation, and quality checks.
- Exploratory analysis, statistical methods, and time-series analysis.

---

## **Pipeline Design**
- Data is extracted from the CMS Medicare Inpatient Hospitals [portal](https://data.cms.gov/provider-summary-by-type-of-service/medicare-inpatient-hospitals/medicare-inpatient-hospitals-by-provider-and-service/data) and stored locally.
- Excel Power Query Editor is used for merging, cleaning, and adding custom columns.
- SQL is utilized for advanced data cleaning and preparation.
- Tableau is used for visualizations to analyze KPIs, trends, and geographic insights.


---

## **Challenges**
- **Data Understanding**: Interpreting the complex dataset and its attributes to uncover meaningful patterns and relationships.
- **Data Transformation**: Applying effective cleaning, merging, and transformation techniques to ensure data accuracy and consistency for analysis.
- **Visualization**: Crafting intuitive Tableau visualizations by selecting relevant insights and presenting them with clear visual themes and color schemes.

---

## **Key Findings**

### **Trends Over Time**
- Medicare payments and patient out-of-pocket expenses showed a steady increase from **2017 to 2022**, reflecting rising healthcare costs.
- While patient discharges remained stable initially, a **decline was observed post-2018**, indicating a shift in care delivery or reduced inpatient utilization.
- The number of participating providers also decreased during this period, signaling potential **industry consolidation** or reduced program participation.

### **Diagnosis Groups and Costs**
- **Infectious and Parasitic Diseases** accounted for the highest costs, with **$403M in Medicare payments** and **$450M in total costs**, emphasizing their financial impact.
- **Sepsis-related cases** were the most frequent diagnosis group, with over **3.5M discharges**, while **Tracheotomy with Mechanical Ventilation (>96 hours)** had the lowest, reflecting its specialized nature.
- The average Medicare payment per discharge varied significantly across diagnosis groups, highlighting the differences in treatment complexities and resource needs.

### **Geographic Disparities**
- States like **California ($47.9B)**, **New York ($37.15B)**, and **Florida ($30.59B)** had the highest Medicare payments due to larger populations and healthcare demand.
- **Wyoming ($0.43B)** and **Alaska ($0.11B)** reported the lowest expenditures, consistent with smaller populations and healthcare infrastructure.
- High-cost claims were concentrated in **metropolitan areas with populations exceeding 50,000**, underlining urban healthcare demand disparities.

### **Provider Performance**
- **New York Presbyterian Hospital** led Medicare payments at **$64.81M across 145,000 discharges**, showcasing its financial contribution to the program.
- **AdventHealth Orlando** reported the highest discharges (**149,000**), with **$27M in payments**, indicating cost efficiency for its case mix.
- Leading providers like **Massachusetts General Hospital**, **Mayo Clinic**, and **NYU Langone Hospitals** balanced discharge volumes and payments, highlighting their operational effectiveness.

---
