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

_________________________________________________________________________________________________________________________________________________________

## Employeee Retention Analysis

In order to get answers for this analysis, I asked the following questions, and got answers using the queries below:

<img width="755" height="264" alt="Screenshot 2025-07-03 182005" src="https://github.com/user-attachments/assets/51b6f13b-3a60-498d-bed6-497bcabf7ee3" />


<img width="705" height="427" alt="Screenshot 2025-07-03 182821" src="https://github.com/user-attachments/assets/374f05d8-7da8-4ad5-bd41-67a254cbe95f" />

The top 5 highest serving employees are:

1. David Moore (Highest)
2. John Johnson
3. Frank Johnson
4. Jane Lee
5. Eve Wilson

_______________________________________________________________________________________________________________________________________________________

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

Majority (39%) of the employees on the turnover table left due to personal reasons.
This may include health, family obligations, relocation, or work-life balance.
Indicates a potential need for flexible work policies or wellness programs.
7 employees (25%) left after finding another job. This could be due to job dissatisfaction, better offers elsewhere or lack of internal advancement
Career Growth reasons (18%) shows some employees left for better long-term prospects. This may point to limited internal mobility or a lack of self-development opportunities. 

The remaining 18% retired (natural occurrence).

## Recommendations

:large_blue_diamond: Investigate the Marketing department’s turnover immediately.

:large_blue_diamond: Conduct exit interviews or employee surveys.

:large_blue_diamond: Review leadership, workload, and role satisfaction.

:large_blue_diamond: Support Engineering with retention strategies.

:large_blue_diamond: Evaluate career growth paths, compensation, and team workload.

:large_blue_diamond: Develop clearer career paths and promotion plans to reduce exits due to career growth elsewhere.

:large_blue_diamond: Since many leave for personal reasons, explore flexible work schedules like hybrid or remote work.

:large_blue_diamond: For those leaving to “find another job”, evaluate how job packages compare to market rates.

## Performance Analysis

Below are the questions along with queries I used for the performance analysis:

<img width="624" height="173" alt="Screenshot 2025-07-03 225347" src="https://github.com/user-attachments/assets/14eab9ef-2a89-42ae-9fc1-c8d6eb336508" />
<img width="430" height="323" alt="Screenshot 2025-07-03 225547" src="https://github.com/user-attachments/assets/81c6b8fe-df2e-4bc2-a60b-e22e8533a2e4" />

28 employees have left the company. 

This represents about 47% which is almost half of the company’s employees. 

<img width="782" height="494" alt="Screenshot 2025-07-03 230314" src="https://github.com/user-attachments/assets/26b3ab70-d950-4a1a-a7e8-354534c0e2d2" />
<img width="630" height="321" alt="Screenshot 2025-07-03 230426" src="https://github.com/user-attachments/assets/cd32a9af-d124-485a-bfce-e82f7101642c" />

A total of 9 employees have a performance score of 5.0.
While 45 employees have a score below 3.5.

This shows there is plenty room for improvement.

<img width="931" height="510" alt="Screenshot 2025-07-03 231607" src="https://github.com/user-attachments/assets/d223e846-502b-4a65-9b06-814e68d9838a" />
<img width="534" height="216" alt="Screenshot 2025-07-03 231823" src="https://github.com/user-attachments/assets/17eace77-e316-4858-ad64-0da1e9b6946e" />
<img width="570" height="213" alt="Screenshot 2025-07-03 231932" src="https://github.com/user-attachments/assets/0e1cee51-cc84-4e53-a070-92100ad278d4" />

The Marketing department had the most employees with a 5.0 performance score, yet almost all left the company. This suggests that there may be issues with the salary not matching performance.
They also topped the list of employees with a score below 3.5, alongside Engineering.

<img width="764" height="255" alt="Screenshot 2025-07-04 000241" src="https://github.com/user-attachments/assets/5abe125e-c856-4a61-81ff-98724c5800ea" />
<img width="463" height="310" alt="Screenshot 2025-07-04 000413" src="https://github.com/user-attachments/assets/67bd9080-9b2a-4071-84fd-dd22e33aad8a" />

All departments are performing well.
Their average performance scores range from 4.00 to 4.13, suggesting overall strong employee performance across board.

Despite having the highest turnover, Marketing staff had the strongest average performance.

Again, this may suggest high-performing but overworked or under-supported employees.

Sales have the lowest average (4.00), still strong though.
Combined with lower turnover, this indicates a stable, consistent team.

## Recommendations

:large_blue_diamond: Recognize and reward top departments like Marketing and Engineering teams for their performance.

:large_blue_diamond: Support Sales with growth opportunities, even with their good score; explore coaching, skills development, or performance incentives to further enhance results.

## Salary Analysis
For Salary Analysis, I executed the following queries to answer key questions

<img width="872" height="180" alt="Screenshot 2025-07-04 010728" src="https://github.com/user-attachments/assets/c338dd1f-2af3-4770-98db-29e8c21c049f" />
<img width="426" height="312" alt="Screenshot 2025-07-04 010846" src="https://github.com/user-attachments/assets/855c3854-bbf0-45db-9f87-9cc8b57364af" />

Total salary expense for the company stood at $4,850,000.

<img width="874" height="253" alt="Screenshot 2025-07-04 011455" src="https://github.com/user-attachments/assets/d8106cd3-787b-402c-8412-2cd9f31be7ca" />
<img width="423" height="326" alt="Screenshot 2025-07-04 011629" src="https://github.com/user-attachments/assets/de19e505-e04e-437d-bb5d-098055b80f43" />

Sales Representative has the highest average salary at $84,286, possibly due to the inclusion of commissions or bonuses.

HR Specialists have a higher average salary than Engineers, which is unusual in many industries.

Marketing Specialists earn the least at $77,857. This is the lowest average salary despite Marketing having the highest average performance score (4.13). 
This may be the cause of the high turnover rate in the Marketing department.

<img width="893" height="211" alt="Screenshot 2025-07-04 020728" src="https://github.com/user-attachments/assets/2de5d5bf-2ed0-4637-aed5-7c80a10e6c80" />
<img width="416" height="324" alt="Screenshot 2025-07-04 020829" src="https://github.com/user-attachments/assets/57c35f97-907d-476c-aaa9-dad1037badce" />

26 employees earn above $80,000. 
This represents 43% of the entire employees.

<img width="878" height="313" alt="Screenshot 2025-07-04 021411" src="https://github.com/user-attachments/assets/dc321412-0ec8-4b1b-ad1e-eb6ddd2180fc" />
<img width="572" height="324" alt="Screenshot 2025-07-04 021452" src="https://github.com/user-attachments/assets/daba2d24-a072-4122-908b-4d5de0491c82" />

There seems to be a negative correlation between performance and salary across departments.

Departments with higher average performance scores (Marketing and Engineering) receive lower average salaries ($80,000).

While departments with lower performance scores (HR and Sales) have higher average salaries (above $82,000).

Marketing performs best but earns the least.
This could contribute to low morale and cause the high turnover being experienced at that department, because employees may feel undervalued.

## Recommendations

:large_blue_diamond: Review the Marketing team's compensation. Align salary packages with market rates and internal performance.

:large_blue_diamond: Consider incentives or bonuses to retain top-performing marketers.

:large_blue_diamond: Assess HR and Engineering salary balance. Evaluate role scope and ensure equity across technical and non-technical functions.

## Conclusion

NexGen Corp. HR department should conduct a strategic People and Performance Alignment Review to address clear gaps between employee performance, compensation, and retention outcomes. While all departments show strong average performance, high-performing teams such as Marketing and Engineering are underpaid relative to lower-performing peers, and Marketing especially is facing a critical turnover rate (92%). Furthermore, exit reasons such as career growth, found another job, and personal reasons suggest that employees may not feel adequately supported or rewarded for their contributions.

To improve retention, motivation, and long-term productivity, leadership should:

:white_check_mark: Align compensation more closely with performance, particularly in departments delivering strong results.

:white_check_mark: Enhance career development pathways to reduce exits related to growth opportunities.

:white_check_mark: Implement retention strategies such as stay interviews, flexible work options, and recognition programs, especially in departments with high attrition.

:white_check_mark: Regularly monitor workforce metrics via integrated dashboards to track the relationship between salary, performance, and turnover across departments.

This holistic approach will help the company retain top talent, promote fairness, and reinforce a culture that rewards high performance while addressing underlying drivers of turnover.

<img width="600" height="200" alt="Thank you" src="https://github.com/user-attachments/assets/0354aa2f-b780-4bee-a4b4-d1a2c5a60be9" />
