# HR-Employee-Attrition

Dashboard Link: https://app.powerbi.com/view?r=eyJrIjoiMjk3ZDhmY2YtM2ZmNC00NzUxLThhYmEtOGU2NzFlZmM2YTQ4IiwidCI6ImFmNDNjZjcxLTY2NWItNDYzMC1iZDcyLTI5MjQ1NTVkNDA1MiJ9 
____________________________________________________________________________________________________________________________________________________________________________
1.0 Project Overview  
This project was developed to apply data analysis skills using SQL Server and Power BI, based on a public HR dataset from Kaggle. The main objective is to understand the reasons behind voluntary employee turnover, which results in high costs related to dismissals and new hires. The insights gained aim to support strategic decision-making for talent retention.

2.0	Problem Statement   
Many companies struggle to understand why high-performing employees leave, often incurring substantial costs due to leavers and recruitment. This project aims to identify patterns and key factors contributing to employee attrition, enabling the design of more effective retention strategies.

3.0	Exploratory Data Analysis (SQL Server)

3.1 Identify the Employee Count in the company and the Attrition rate.  

![image](https://github.com/user-attachments/assets/27fcef98-3cf1-496e-ab65-5d19749229b5)


 

There are 1.470 employees with 237 cases of attrition. 

3.2	Attrition by Department 

![image](https://github.com/user-attachments/assets/b30f5228-e86f-4483-8d5b-6cda2b4d3099)

 

R&D is the most affected department with 133 cases, followed by Sales (92) and Human Resources (12).

3.3- Attrition by Age Group  

![image](https://github.com/user-attachments/assets/d765cab4-7bea-46eb-902a-1dc52a9a7f38)

 

The age range 21–40 years represents the highest attrition rate (169 employees), highlighting a critical demographic for retention strategies.  



3.4	Performance Rating x Attrition    

![image](https://github.com/user-attachments/assets/27216a63-bc25-45b1-ae11-0827fcccd214)

 

A significant proportion (22.84%) of employees with lower performance ratings also showed higher attrition rates, indicating a potential area for development and support.

3.5	Years at Company x Department  

![image](https://github.com/user-attachments/assets/237182e4-cd7f-4e24-94e1-23f02ce609c4)



The average tenure across the three main departments is approximately 5 years.

3.6	Previous Employment Experience  

![image](https://github.com/user-attachments/assets/f742b584-d512-4243-8128-080b83ce03a1)

 

Most employees who left had limited previous professional experience, typically having worked for only one company prior.

4.0 Modelagem e Visualização no Power BI  

•	Data model creation with relationships and DAX measures.  
•	Interactive dashboard built to enable intuitive exploration and strategic insight generation.

5.0  Key Findings & Insights   
The analysis revealed that the company has an overall attrition rate of approximately 16%, a significant figure that indicates potential instability in its workforce. The departments most affected by voluntary turnover were Research & Development, Sales, and Human Resources, with R&D bearing the highest number of exits. A notable pattern emerged among the employees who left the company: they were predominantly male, between the ages of 21 and 40, with limited prior work experience, often having worked at only one other company, and typically remained with the organisation for up to five years. Salary also appeared to be a critical factor, as the majority of attrition cases occurred among employees earning between 2K and 5K per month, which may reflect dissatisfaction with compensation or a perceived lack of growth opportunities. Additionally, roles such as Laboratory Technician, Sales Executive, and Research Scientist showed higher rates of turnover. Another important insight was the strong correlation between lower performance evaluations and higher attrition, suggesting that underperformance may be both a cause and a consequence of disengagement, and pointing to the need for more proactive feedback and employee development programs.



6.0 Suggested Solutions  

•	Develop retention programs focused on young talent, emphasising career paths and training.  
•	Reassess compensation and benefits for lower salary grades.  
•	Implement performance improvement initiatives, such as regular feedback and upskilling.  
•	Introduce structured onboarding and mentoring programs for new hires.  

7.0 Used Tools  

•	Power BI: Data modelling, DAX, interactive dashboards.   
•	SQL Server: Data exploration and insight generation through advanced queries

8.0  Key Learnings  

This project provided hands-on experience with data analysis by combining SQL Server for in-depth data exploration and Power BI for impactful data visualisation. The study of the Kaggle HR dataset revealed meaningful patterns related to employee attrition, helping to identify key risk groups and the underlying causes of turnover. These insights can drive data-informed decisions for more effective talent management and retention. 


