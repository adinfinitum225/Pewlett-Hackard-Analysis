# Pewlett-Hackard-Analysis

## Overview

This project is a basic analysis of employee data in a PostgreSQL database. Given the number of records involved, the data from our csv files was imported into Postgres in order to quickly and efficiently manipulate the data. Using SQL queries we selected the data we were interested in, and exported it to csv using the pgAdmin export tool.

### Purpose

The purpose of this analysis is to get information on the upcoming 'silver tsunami' at the company Pewlett-Hackard (PH). PH is a mature company and has been around for quite some time. Many employes are getting close to retirement age, and the leadership at PH needs information on those employees. Additionally, they need to get an overview of how many job positions and titles will be opening up so they can be prepared to fill those vacancies. The leadership at PH also brought up the idea of starting a mentorship program to help soon-to-be-retiring employees train the ones that will be taking their places. 

## Results

### Background

>![Fig1. A count of how many employees are eligible for retirement by job title](resources/retiring_titles.png) 
>Figure 1.

>![Fig2. A list of employees eligible for mentorship.](resources/mentorship_elegibility)
>Figure 2.
<!-- Provide a bulleted list with four major points from the two deliverables -->

* Two managers are retiring, which will leave PH with no currently employed managers
* As is expected, most of the employees retiring are in senior level positions. 
* The number of employees eligibility for mentoship is quite small
*

## Summary
<!-- Provide high level responses to these questions, and provide two additional queries or tables that may provide more insight into the upcoming 'silver tsunami' -->

<!-- How many roles will need to be filled as the "silver tsunami" begins to make an impact? -->

<!--  Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees? -->

Brainstorming additional queries :
- Number of employees by title that AREN'T retiring.
- Number of non-senior employees eligible for promotion
- Salaries for 
