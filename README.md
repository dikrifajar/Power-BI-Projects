# Professional-Survey-Dashboard

## Problem Statement

This dashboard helps organizations understand the professional satisfaction and career trends of their workforce. By analyzing metrics such as happiness levels, programming language preferences, average salaries, and career-switching tendencies, companies can identify areas that need improvement.  

For example, satisfaction with **management** and **upward mobility** scores lower compared to other factors, highlighting critical areas for organizational development. Additionally, the majority of career switches come from **Data Analysts**, who also earn lower average salaries compared to Data Scientists, suggesting a link between compensation and retention.  

The demographic breakdown shows that most respondents are from the **United States**, which means insights are heavily influenced by that region.

---

### Steps Followed

- **Step 1**: Loaded survey data into Power BI Desktop (CSV format).  
- **Step 2**: Checked data quality in Power Query Editor (column distribution, quality, and profile).  
- **Step 3**: Enabled profiling for the entire dataset, not just the default 1000 rows.  
- **Step 4**: Null values were minimal and excluded from average calculations.  
- **Step 5**: Created donut chart to visualize happiness factors (Work-Life Balance, Salary, Management, etc.).  
- **Step 6**: Added bar charts for programming language preferences, career switches by role, average salary per role, and country distribution.  
- **Step 7**: Inserted card visuals for total participants (630), male (468), female (162), and average age (29.87).  
- **Step 8**: Added slicers for Education, Ethnicity, and Industry.  
- **Step 9**: Applied a consistent theme for readability.  
- **Step 10**: Published the dashboard to Power BI Service.

---

## Insights

### [1] Demographics
- Total participants: **630**  
- Male: **468** (74%)  
- Female: **162** (26%)  
- Average age: **29.87 years**

### [2] Happiness Ratings (Scale 1–10)
- Work-Life Balance: **5.61 (22%)**  
- Salary: **5.74 (22%)**  
- Management: **4.76 (19%)**  
- Upward Mobility: **4.27 (17%)**  
- Learn New Things: **5.33 (21%)**

--> **Management** and **Upward Mobility** are the weakest areas.

### [3] Programming Language Preferences
- Python: **420**  
- R: **101**  
- Other: **95**  
- C/C++: **7**  
- JavaScript: **6**  
- Java: **1**

--> Python dominates overwhelmingly.

### [4] Career Switching by Role
- Data Analyst: **381**  
- Data Engineer: **38**  
- Data Scientist: **25**  
- Database Developer: **5**  
- Data Architect: **3**

--> Most career switches occur among **Data Analysts**.

### [5] Average Salary by Role
- Data Scientist: ~90K USD  
- Data Architect: ~70K USD  
- Data Engineer: ~60K USD  
- Other: ~55K USD  
- Data Analyst: ~50K USD  
- Database Developer: ~40K USD  

--> Significant salary gap between Data Scientists and Data Analysts.

### [6] Country Distribution
- United States: **261**  
- Other: **224**  
- India: **73**  
- United Kingdom: **40**  
- Canada: **32**

--> Majority of respondents are from the **United States**.


# Snapshot of Dashboard (Power BI Service)

<img width="2157" height="1220" alt="image" src="https://github.com/user-attachments/assets/71acc328-4fbd-4746-b725-ca37a301bd2a" />

