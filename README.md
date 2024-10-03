# LITA-Class-Documentation
This is where I Documented my first project while learning Data Analysis with the Incubator Hub

### Project Title
-----

LITA_DB EMPLOYEE TABLE

### Table Outline for the Portfolio
-----
- Project Overview
- Data Sources
- Tool Used
- Data Cleaning and Preparations
- Data Analysis
- Data VIsualization

  ### Project Overview
-----
  The goal of this project is to provide meaningful insight into employee demographics, compensation strutures, and salary distribution  across different organization. By examining key elements such as job roles, industry differences, geographic regions, and experience levels, the project aims to identify trends in pay, including wages progression, gender pay disparities, and performance-based incentive. This analysis will enable organizations to make data-driven decisions about equitable and competitive compensation strategies, ultimately enhancing employee satisfaction, retention, and business outcomes.

  ### Data Sources
  -----
  The primary data sources used here is SQL QUREIES LITA_DB

  ### Tools Used
  -----
 
 -  SQL - Structured Query Language [DOWNLOAD HERE](https://www.microsoft.com)
     1. Data extraction from data bases
     2. Data cleaning and transformation
     3. Agregating data
     4.  Data analysis
 -  Github for portfolio  building

   ### Exploratory Data Analysis
   -----
   EDA involved the exploring of the data to answer some questions about the data such as;   
    
     1. What is the total amount of Department?
     2. What is the total Salary for Employee?
     3. What is the total number of Employee?

   ### Data Analysis
   ------
     This is where we includes some basic lines of code or queries;
      
   ````SQL
       select * from [dbo].[Employee]
       update employee
       set secondname = 'Endurance'
       where staffid = 'AB405'
       Select Sum(salary) As Totalsalary from salary
       select count(staffid) As employeecount
       from employee 
   ````
     
  
