# INCUBATOR_HUB_HR_DATA


### Project Overview 
The Incubator Hub HR Data Analysis aims to track the activity that goes on with the staff of the company as far as official duties are concern. The analysis covers various aspects such as attrition, attrition count, period of last leave, salary, age sort, business travel etc. The goal is to help the company acccess the efficiency rate of the employees.

### Data Sources 
The primary data sources used is excel worksheet, which is an open-source data.

### Tools Used
- Power Business Intelligence(Power BI) for cleaning and visualizing the data set


### CONTENT OF THE CUSTOMER DATA EXCEL SPREADSHEET
- Attrition
- Business Travel
- CF_age band
- CF_attrition label
- Department
- Education Field
- Employee Number
- emp no
- Gender
- Job Role
- Marital status
- Overtime
- Over18
- Training times last year
- Age
- CF_curent Employee
- Daily Rate
- Distance from home
- Educational qualification
- Employee count
- Environment Satisifaction
- Hourly Rate
- Job involvement
- Job level
- Job Satisifaction
- Monthly Income
- Monthly Rate etc.


Firstly, confirm the types of each of the columns whether they are text for letters, whole numers for figures, time/date for date etc. Correct accordingly where column type is incorrect. Then move on creating conditional columns for attrition, CF_age band and job satisfaction. 

For attrition, rename the column as attrition rate where:
- 'Yes' = 1  
- Else  = 0.

Also rename CF_age band to be age sort where:

- Under 25 = 1
- 25 - 34 = 2
- 35 - 44 = 3
- 45 - 54 = 4
- Else = 5

Lastly, conditional columns where created for job satisifacton where:
- 1 = very dissatisified
- 2 = Dissatisified
- 3 = Satisified
- Else = very satisified

After creating the conditional columns for each, ensure to check the column type and correct where necessary. 


![HR data](https://github.com/user-attachments/assets/db22c20b-fc50-4a8b-8b12-1d2aa6c050ac)



Move over to your dashboard for visualization. We visualized the HR data with pie chart, doughnut, bar chart, tables, matrix etc. We also visualized:
- Total number of employees
- Attrition count
- Attrition rate
- Total number of current employees
- Average age
- Attrition by Educational field
- Attrition by Department
- Sum of attrition count by CF_age band and Gender etc.


![expirment](https://github.com/user-attachments/assets/f905a531-4f5a-499c-b5c3-aad4d68cb98f)



  ![HR data 2](https://github.com/user-attachments/assets/4a3c27ed-b8ef-4db9-b619-b5a481f06990)


