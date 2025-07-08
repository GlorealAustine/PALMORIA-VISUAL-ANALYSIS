### PALMORA GROUP HR ANALYTIC DASHBOARD


## 📑 Table of Contents

- [About the Project](#about-the-project)  
- [Objective](#objective)  
- [Data Source](#data-source)  
- [Tools Used](#tools-used)  
- [Data Cleaning & Modeling](#data-cleaning--modeling)  
- [Dashboard Overview](#dashboard-overview)  
- [Key Insights](#key-insights)  
- [Conclusion](#conclusion)  
- [Recommendations](#recommendations)  
- [Screenshots](#screenshots)  
- [Deliverables](#deliverables)  
- [Author](#author)

---

## About the Project

This project is a Human Resources (HR) analytics dashboard developed to help Palmoria Group evaluate and understand their employee salary structure, gender distribution, and bonus distribution. It also investigates the gender pay gap and provides data-driven recommendations for strategic HR decisions.

## Introduction

Palmoria Group is a manufacturing company based in Nigeria that has an embroided issues about gender inequality in its 3 regions where their businesses are located. Unfortunately, the media recently published in the news with the headline “Palmoria, the Manufacturing Patriarchy” this doesn’t look good to the owner of the business on their ambition to scale the business to other regions and even overseas. Disclaimer: All datasets and reports do not represent any company, institution or country, but just a dummy datasets to demonstrate capabilities of Power BI. You can download Power BI Desktop here:  [Download Power BI Desktop (Official Microsoft Link)](https://www.microsoft.com/en-us/download/details.aspx?id=58494)

This documentation outlines the data cleaning process for the Palmoria Group HR Analysis. Three sets of data was given to work on and to know about the issues the company is currently facing. The datasets are given below;

- The Palmoria Group emp-data: 
  a. This contains the employees details.  

- The Bonus rules: 
  a. This contains the rule for making payments to the employees in the company.  
  b. It includes their work rating same as the bonus mapping

## PROBLEM STATEMENT

1. What is the gender distribution in the organization? Distil to regions and departments

2. Show insights on ratings based on gender

3. Analyse the company’s salary structure. Identify if there is a gender pay gap. If there is, identify the department and regions that should be the focus of management

4. A recent regulation was adopted which requires manufacturing companies to pay employees a minimum of $90,000

   • Does Palmoria meet this requirement?  
   • Show pay distribution of employees grouped by a band of $10,000. For example;  
   • How many employees fall into a band of $10,000 - $20,000, $20,000 -$30,000, etc.?  
   • Also visualize this by regions

---

## Objective

• Analyze the salary structure across departments and regions.  
• Evaluate gender representation within the organization.  
• Identify any gender pay disparities.  
• Provide HR insights for bonus allocations and salary bands.  
• Support decision-making with clear, interactive visuals.

---

## Data Source

The project is based on fictional employee data provided for analysis, including:  
• Employee demographics (Gender, Region, Department)  
• Salary and Bonus information  
• Performance ratings

---

## Tools Used

• Power BI (Dashboard creation, visuals, modeling)  
• Power Query (Data cleaning and transformation)  
• DAX (Custom measures and KPIs)  
• Excel (Raw data manipulation and pre-cleaning)

---

## Data Cleaning & Modeling

• Removed duplicates and null values in Power Query.  
• Created dimension tables for Gender, Region, Department, and Rating.  
• Built a star schema model linking dimension tables to the Fact table.  
• Used DAX measures to calculate:  
  • Average Salary  
  • Total Salary  
  • Average Bonus  
  • Gender counts  
  • Salary band distributions  
  • Salary gap by gender and region

---

## Dashboard Overview

The dashboard includes the following sections:  
• Average Salary Gauge  
• Total Employees  
• Total Salary and Bonus  
• Gender Distribution (Department & Region)  
• Bonus Distribution by Gender  
• Salary Bands by Region  
• Ratings based on Gender  
• Salary Gap by Department & Region  
• Employee Pay Summary Table

---

## Key Insights

• Average salary across the company is ₦73.7K, below the target benchmark of ₦90K.  
• Gender distribution is fairly balanced across most departments.  
• Female employees slightly out-perform male counterparts in bonus received (₦1.06M vs ₦1.03M).  
• The ‘Average’ rating is the most common, especially among both male and female staff.  
• Some departments (e.g., Marketing, Accounting) show noticeable salary variations by region.

---

## Conclusion

• The organization demonstrates near parity in gender distribution and bonus payments.  
• There is no significant gender pay gap at an aggregate level.  
• Salary structure, however, needs realignment as the average is still below the expected target of ₦90K.  
• Regional salary differences are evident and should be reviewed.

---

## Recommendations

1. Review & Adjust Salary Bands  
   Raise pay in underperforming regions/departments to meet targets.

2. Promote Gender Diversity in Key Roles 
   Encourage balance in departments like Marketing and Engineering.

3. Align Bonuses with Performance Ratings  
   Reward “Very Good” and “Excellent” more clearly to drive better outcomes.

4. Eliminate Undisclosed Gender Entries 
   Improve data quality with mandatory reporting fields.

5. Monitor Salary Equity Continuously  
   Run quarterly analytics to detect emerging gaps.

---

## Screenshots

![Dashboard Screenshot](images/dashboard.png)

![PALMORA GROUP HR ANALYTIC DASHBOARD (2)](https://github.com/user-attachments/assets/20065a74-21b7-45e2-a426-396fd6eef1d2)

## Delivearbles

Link To Interactive Dashboard : https://drive.google.com/file/d/1oK0EJoaT6KuJB0P5E9MYvQiJQXAsufNW/view?usp=drive_link

## Author

## Augustine Glory Chinyere  
**Data Analyst | Power BI Enthusiast**

- Email: glorealaustine@gmail.com  

