# 311-Service-Requests-Project-
 
Project Overview

This project focuses on analyzing the 311 Service Request dataset to understand complaint patterns, response times, and service efficiency. The analysis helps identify how different complaint types are handled and how long it takes to resolve them.

---

Objectives

- Analyze different types of complaints
- Calculate request closing time
- Compare response time across complaint types
- Perform statistical analysis (ANOVA test)
- Visualize results using graphs

---

Dataset

The dataset contains information about:

- Complaint Type
- Created Date
- Closed Date
- Location details

---
Technologies Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

---
Key Steps Performed

1. Data Cleaning

- Converted date columns into datetime format
- Handled missing values

2. Feature Engineering

- Created a new column: request_Closing_Time
- Calculated time taken to resolve complaints

3. Exploratory Data Analysis (EDA)

- Checked distribution of complaints
- Visualized average response time

4. Statistical Analysis

- Applied ANOVA test using SciPy
- Checked significance using p-value

---

 Results

- Response time varies across complaint types
- Statistical test confirms whether differences are significant

---
 Visualization

- Bar charts for average closing time
- Distribution plots for complaint types

---

Conclusion

This project helps in understanding service efficiency and identifying areas for improvement in complaint resolution.

---

