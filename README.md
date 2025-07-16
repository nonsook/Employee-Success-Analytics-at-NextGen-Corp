# Employee-Success-Analytics-at-NextGen-Corp
Employee success analytics based on Employee Retention, Performance and Salary analysis at NextGen Corp.

<img width="1200" height="675" alt="image" src="https://github.com/user-attachments/assets/9f6cc084-6ad8-4b07-9346-cd57c32908b4" />

## Case Overview

NextGen Corp. is a growing technology company focused on developing innovative solutions in the software and hardware spaces. The company prides itself on attracting top talent and maintaining high employee satisfaction to drive growth. However, there are increasing concerns regarding employee turnover, performance variability, and salary disparities within departments. 

To ensure continued success, NextGen Corp. needs to optimize employee retention, track employee performance consistently, and maintain fair salary structures across departments. 


## Task

The HR department needs a data-driven approach to:

 :o: Identify trends and patterns in employee retention and turnover.  
 
 :o: Track and evaluate performance across different departments.
 
 :o: Assess the relationship between salary and performance to ensure fairness and employee satisfaction.

## Data Description

 - **Employees Table:** Contains essential employee details 
like name, job title, hire date, salary, performance score, 
attendance rate, and department affiliation.
 
- **Departments Table:** Contains the list of departments 
within NextGen Corp. (e.g., Engineering, Sales, HR, 
Marketing).
 
- **Performance Table:** Tracks monthly performance 
scores of employees, allowing you to analyze performance trends over time.

- **Attendance Table:** Tracks attendance records for 
employees, including whether they were present or absent.
 
- **Turnover Table:** Contains data on employees who left the company, including the reason for leaving.
 
- **Salaries Table:** Provides salary data, including historical salary changes for each employee.

## Methodology

NextGen Corp.’s database was loaded on PostgreSQL and queried accordingly to determine the answers to the questions raised by the company. The analysis was categorized into three sections:
  
:large_orange_diamond: Employee Retention Analysis

:large_orange_diamond: Performance Analysis

:large_orange_diamond: Salary Analysis

## Employeee Retention Analysis

In order to get answers for this analysis, I asked the following questions, and got answers using the queries below:

<img width="705" height="427" alt="Screenshot 2025-07-03 182821" src="https://github.com/user-attachments/assets/38dc77e9-b205-4a35-b084-268f2ef283fa" />

<img width="705" height="427" alt="Screenshot 2025-07-03 182821" src="https://github.com/user-attachments/assets/374f05d8-7da8-4ad5-bd41-67a254cbe95f" />

The top 5 highest serving employees are:

1. David Moore (Highest)
2. John Johnson
3. Frank Johnson
4. Jane Lee
5. Eve Wilson

<img width="865" height="339" alt="Screenshot 2025-07-03 193304" src="https://github.com/user-attachments/assets/aa389b32-e729-4824-ae7a-fa73e54ac2e2" />
<img width="742" height="322" alt="Screenshot 2025-07-03 193438" src="https://github.com/user-attachments/assets/10295abc-4170-4dcb-a80f-6922a5b7f3b8" />


The Marketing department has an extremely high turnover rate of 92%. Almost the entire department has left.
This could indicate low morale, management, or role-related issues, or external opportunities pulling employees away. 

Engineering has moderate to high turnover (66%).
This level suggests instability or possible issues in workload, culture, or retention incentives. Given the normal high demand for engineers, this may also reflect competitive poaching.

Sales and HR show healthy or manageable turnover (Both 27%). These departments are within a more typical industry range (10 - 30%, depending on the sector).

<img width="927" height="425" alt="Screenshot 2025-07-03 202528" src="https://github.com/user-attachments/assets/38a94da6-0c30-46b5-8d46-f43427cf38d4" />
<img width="913" height="284" alt="Screenshot 2025-07-03 202714" src="https://github.com/user-attachments/assets/43ed7064-e7c3-43a7-b1a5-4fa6e13f143e" />
<img width="912" height="317" alt="Screenshot 2025-07-03 202925" src="https://github.com/user-attachments/assets/f44874ea-f6d4-47b9-9841-f20a47e43e54" />

A deeper query on the turnover table shows that 21 out of the 28 employees who left all had an average performance score of  4.0 and above. 5 were retirees, while the remaining 16 people left for either personal reasons, career growth or they found another job.

So, it means that high performers are actually the ones with a high risk of leaving the company. 

This could be due to a feeling of not being adequately compensated for their hard work, or a poor work culture.

<img width="735" height="216" alt="Screenshot 2025-07-03 205850" src="https://github.com/user-attachments/assets/758bfb90-98fa-468b-9000-6ba3c9dcd892" />
<img width="1135" height="323" alt="Screenshot 2025-07-03 210018" src="https://github.com/user-attachments/assets/16872cda-8151-43f1-ae61-3cb6e0fd4623" />



