*** HR ANALYTICS- MICROSOFT FABRIC AND POWER BI*** 

***Business Scenario***

A mid sized IT company wants to understand the reason behind the High Attrition rates in their company. The HR Department lacks visibility in:

•	Which department/Roles have high Attrition rates ?

•	Joining Trends OverTime 

•	Avg Ratings and Absent days by Department and Gender

•	Total employee and Total Resignations

In This project, 

I fetched data from ADLS Storage using a data pipeline into the fabric lakehouse. 

<img width="813" height="147" alt="data pipeline" src="https://github.com/user-attachments/assets/ab9da76d-a63a-40d2-a56e-450151bf4c88" />

I used data flows to clean and prepare the silver layer tables and finally merged all the silver layer tables into one gold layer data for final Analysis. 

***FINAL TABLE CLEANED AND PREAPARED WITH DATAFLOWS AND VISUAL QUERY***

<img width="809" height="287" alt="DATFLOWS VIEW FINAL  QUERY" src="https://github.com/user-attachments/assets/d8392fd5-24d3-4c8b-924a-16187949d9e9" />

***BI DASHBOARD***

<img width="890" height="500" alt="BI REPORT" src="https://github.com/user-attachments/assets/e0b79952-c74c-415f-894f-4f23e88ec25c" />

***HR ANALYTICS – KEY INSIGHTS***

***1. Workforce Status***

•	Total Employees: 23

•	Total Resignations: 23

***INSIGHTS***

o	This indicates 100% attrition for the selected date range.

o	Either the organization rehired people later, or this is historical data showing a full churn cycle.

o	Extremely high attrition → serious retention concerns.

 ***2. Absence Insights***
 
  ***Department***	      ***Avg Absence***
   
     IT	              16.17 days
   
    Marketing   	    16.00 days
    
     HR	              14.20 days
    
    Sales   	        12.00 days
   
    Finance         	11.71 days

***INSIGHTS***

•	IT and Marketing have the highest absence days → potential workload, stress, or engagement issues.

•	Finance shows the lowest absenteeism → stable or maybe under-reported.

***3. Performance Ratings by Department & Gender***

•	Finance (Female) shows the highest rating: 4.0

•	Marketing (Female): 3.0

•	IT (Female): 3.0

•	Sales (Male) and HR (Male) both at 2.0

•	Male ratings are generally slightly lower than female.

***INSIGHTS***

•	Finance female employees are top performers.

•	Sales and HR need improvement → could be training or process inefficiencies.

***4. Gender Distribution***

•	Male: 10 (43.48%)

•	Female: 13 (56.52%)

***INSIGHTS***

•	Female representation is slightly higher.

•	Distribution is fairly balanced → no immediate gender diversity concern.
 
 ***5. Absent Days by Department & Gender***

•	IT Females: 77 days → very high

•	Finance Females: 54 days

•	HR Females: 38 days

•	Marketing Females: 48 days

•	Sales Females: 16 days

***INSIGHTS***

•	Female absenteeism is significantly higher across all departments.

•	IT female absenteeism is unusually high → need deeper root cause analysis.

***6. Salary Insights by Gender***

•	Female Avg Salary: 71.95K (51.04%)

•	Male Avg Salary: 69K (48.96%)

***INSIGHTS***

•	Female employees earn slightly more on average.

•	Suggests no pay-gap issue; if anything, females are rewarded slightly higher—possibly aligned with their higher performance scores.

 ***7. Joining Trends Over Time***

•	Peak hiring occurred in 2019 (5 hires).

•	Hiring dropped sharply in 2022 (1 hire).

•	Possibly linked to resignations, budget cuts, or economic impact.

***Executive Summary***
 
 ***Operational Issues***

•	Absenteeism is high in IT & Marketing, especially among female staff.

•	Sales & HR show lower performance ratings → requires training or leadership review.

***Talent Management Issues***

•	100% attrition over the analyzed period is alarming.

•	Decline in hiring from 2020–2022 shows possible hiring freeze or cost-cutting.

***Strategic HR Recommendations***

1.	Investigate high absenteeism in IT (stress, workload, burnout).

2.	Launch retention initiatives – exit interviews, engagement programs.

3.	Improve performance in Sales & HR through targeted training.

4.	Review hiring strategy to restore workforce stability.

5.	Monitor gender-based absenteeism → explore flexible schedules, wellness programs.


