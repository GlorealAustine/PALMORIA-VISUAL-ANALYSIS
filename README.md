##### PALMORIA-VISUAL-ANALYSIS

#### INTRODUCTION 

Palmoria Group is a manufacturing company based in Nigeria that has an embroided issues about gender inequality in its 3 regions where there businesses are located. Unfortunately, the media recently published in the news with the headline “Palmoria, the Manufacturing Patriarchy” this doesn’t look good to the owner of the business on their ambition to scale the business to other regions and even overseas. Disclaimer: All datasets and reports do not represent any company, institution or country, but just a dummy datasets to demonstrate capabilities of Power BI

This documentation outlines the data cleaning process for the Palmoria Group HR Analysis. Three sets of data was given to work on and to know about the issues the company is currently facing. The datasets are given below;

The Palmoria Group emp-data: this contains the employees details I looked into the data set and the data cleaning process was completed using Power Query, a powerful data transformation tool and I analyzed and generate an insights the management team need to address

The bonus rules : this contains the rule for making payments to the employees in the company and their work rating

The bonus mapping: This contains the rule for making payments to the employees in the company and their work rating

#### PROBLEM STATEMENT

1. What is the gender distribution in the organization? Distil to regions and departments

2. Show insights on ratings based on gender

3. Analyse the company’s salary structure. Identify if there is a gender pay gap. If there is, identify the department and regions that should be the focus of management

4. A recent regulation was adopted which requires manufacturing companies to pay employees a minimum of $90,000

   • Does Palmoria meet this requirement?  
   • Show pay distribution of employees grouped by a band of $10,000. For example;  
   • How many employees fall into a band of $10,000 - $20,000, $20,000 -$30,000, etc.?  
   • Also visualize this by regions

#### DATA DESCRIPTION

The Palmoria Group manufacturing company gave out a data set of 3 different tables which are; the Palmoria Group emp-data, bonus rules and the bonus mapping. The bonus mapping and bonus rules consists of 12 rows and 6 columns while the DSF_emp_data consists of 6 columns and 1015 rows.. The DSF_emp_data tables contains a range of the employees details related to the Palmoria company staffs, such as Employees name, Gender, department, salary, location and rating While the bonus rules and mappings which are the same consist of 12 rows and 6 columns .The columns consists of the department and the ratings ie very poor, poor, very good, good and average.

#### DATA DESCRIPION

The Palmoria Group manufacturing company gave out a data set of 3 different tables which are the Palmoria Group emp-data, bonus rules and the bonus mapping. The Palmoria Group emp-data consists of 6 columns and 1016 rows, the Bonus rules and the bonus mapping consists of 13 rows and 6 columns. Palmoria Group emp-data tables contains a range of the employees details related to the Palmoria company staffs, such as Employees name, Gender, department, salary, location and rating While the bonus rules and mappings which are the same  consists of the department and the ratings i.e. very poor, poor, very good, good and average.

#### CORE DATA ANALYSIS SKILLS

### Data Cleaning & Preparation

- Handling missing values in salary, ratings, or department columns
- Replacing the empty spaces in Gender columnn with a generic term (e.g. Undisclosed)
- Converting data types (e.g., salaries to numeric, dates, text columns)
- Trimming and cleaning the name column to delete trailing or leading spaces

### Data Transformation

- Creating calculated columns (e.g., bonus amounts, total pay, Average Male and Female Salary, Average Total Salary, Bonus % e.t.c)
- Creating personcount measure which is representing the number of people in each category i am analyzing. This is Because there was no employee ID
- Binning salaries into $10,000 bands
- Merging datasets (e.g., employee data with bonus rules) using joins. Used BonusKey to join the Palmoria Group emp-data and the Bonus Rule data to get Many to one relationship

### Exploratory Data Analysis (EDA)

- Analyzing gender distributions across departments and regions
- Summarizing salary ranges and distributions
- Showing insights based on rating
- Analying employees salary band by regoion
- Visualizing gap by department and region
- Creating KPIs such as Average salry using gauge, Total employees, Total salary, Average bonus salary and Total average salary.

### Statistical Analysis

- Comparing average salaries between genders → helps detect pay gaps
- Calculating proportions of employees below or above the $90,000 threshold
- Aggregating bonus payouts by gender

### Data Visualization

- Creating Stacked column charts of gender distribution by department and clustered bar chart for region
- Using clustered bar chart for salary bands
- Designing dashboards or summary visuals for management insights

### Compliance & Business Rule Checks

- Evaluating whether all employees earn at least $90,000
- Highlighting departments or regions not meeting regulatory requirements

### Data Interpretation & Communication

- Translating findings into actionable recommendations
- Writing clear documentation (e.g., your problem statement, README)
- Presenting insights to stakeholders (graphs, tables, narratives)

### Tools & Techniques Likely Used
- Power BI for cleaning, EDA, calculations, and visuals  
- Formulas like `DAX` for dynamic calculations (e.g., bonuses),`IF`
- Charts (bar, pie, gauge) for distributions and comparisons  

  




   


