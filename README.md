# RESTAURANT-RATING-ANALYSIS

### PROJECT OVERVIEW
This project analyzes employee satisfaction survey data to identify key factors influencing employee engagement, satisfaction, and workplace experience. The analysis focuses on employee responses conducted by Pierce County WA and completed voluntarily by government employees across different departments and roles to uncover trends, strengths, and areas requiring improvement.

### OBJECTIVE
The primary objectives of this analysis are:
-	Identify survey questions with the highest agreement and disagreement levels.
-	Analyze satisfaction patterns across departments 
-	Measure overall employee satisfaction.
-	Provide actionable recommendations to improve employee experience and retention.


### TABLE OF CONTENT
* [Project Overview](#project-overview)
* [Objectives](#objectives)
* [Dataset Overview](#dataset-overview)
* [Tools](#tools)
* [Key Skills Applied](#key-skills-applied)
* [Visualization](#visualization)
* [Key Insight](#key-insight)
* [Interactive Analysis](#interactive-analysis)
* [Recommendation](#recommendation)
* [Data Source](#data-source)
* [Conclusion](#conclusion)



### DATASET OVERVIEW

COLUMNS:
- Response ID
- Status
- Department
- Director
- Manager
- Supervisor
- Staff
- Question
- Response
- Response Text


##### DATASET SAMPLE PREVIEW

|Response ID|	Status|	Department|	Director|	Manager|	Supervisor|	Staff| Question| Response| Response Text|
|-----------|-------|-----------|---------|---------|-----------|------|---------|---------|--------------|
|1|	Complete|	Human Resources|	0|	1|	0|	0|	1. I know what is expected of me at work|	4|	Strongly Agree|
|2|	Complete|	Communications Office|	0|	0|	0|	0|	1. I know what is expected of me at work|	4|	Strongly Agree|
|3|	Complete|	Parks and Recreation|	0|	1|	0|	0|	1. I know what is expected of me at work|	0|	Not Applicable|
|4|	Complete|	Human Resources|	0|	1|	0|	0|	1. I know what is expected of me at work|	3|	Agree|
|5|	Complete|	Communications Office|	0|	0|	0|	0|	1. I know what is expected of me at work|	0|	Not Applicable|
|6|	Complete|	Prosecuting Attorney's Office|	0|	0|	0|	0|	1. I know what is expected of me at work|	4|	Strongly Agree|


[Dataset file showing the pivot tables][Employee Survey Dataset.xlsx](https://github.com/user-attachments/files/29397006/Employee.Survey.Dataset.xlsx)




### TOOLS 
-	Microsoft Excel
-	Power Query
-	Data Visualization

### KEY SKILLS APPLIED
-	Data Cleaning and Transformation
  > I transform the data in power query, then I removed duplicate and empty values and I also replace a question “This year, I have the opportunities to learn & grow” to “This year, I have the opportunities to learn and grow” 
-	Survey Analytics
-	KPI Design
-	Data Storytelling
-	Business Intelligence
-	Excel Visualization


### VISUALIZATION

KPI (Key Performance Indicator Metrics)
1. Total Responses
Measures the total number of survey responses received which is 14,575
2. Positive Responses
Measures the number of respondents who selected:
-	Strongly Agree: 5,229
-	Agree : 5731
Total Positive Responses: 10960
3. Negative Responses
Measures the number of respondents who selected:
-	Disagree: 2160
-	Strongly Disagree : 1061
-	Not Applicable : 394 
Total Negative Responses : 3615

4. Employee Satisfaction Rate (54%)
Measures the percentage of positive responses out of total responses.
Formula used : Positive Responses / Total Responses * 100  = 54%



##### DASHBOARD


<img width="954" height="537" alt="Restaurant Dashboard 2" src="https://github.com/user-attachments/assets/983ee88c-e8d2-4991-b540-05a318129d08" />


### KEY INSIGHT
1.  Agree and Disagree response by Questions 
> The question respondents agree  with the most is:
- My department is inclusive and demonstrate support of a diverse workforce with total number of 663 
> The question respondents disagree with the most is:
- I  have a best friend at work, with total number of  469 




2. Department Response Trend Analysis (Top 5 Response Trend by Department) 
> Yes, there are noticeable patterns across departments.
- The Planning and Public Works Department recorded the highest number of survey responses (48%), indicating the highest level of participation among all departments. This department also showed the highest levels of both positive and negative responses, suggesting that employees have strong opinions about their workplace experiences.
- The Sheriff’s Department and Human Services also contributed a significant number of responses and generally displayed more positive responses (Agree and Strongly Agree) than negative responses, indicating relatively higher employee satisfaction.
> Across most departments, employees agree with statements related to:
- Understanding what is expected of them at work.
- Understanding the organization’s mission and purpose.
- Having supportive workplace relationships.
> However, a recurring trend across departments was dissatisfaction with:
- Career advancement opportunities.
- Recognition and rewards.
- Overall job satisfaction.
> This suggests that while employees generally understand their roles and work well with colleagues, there are organization-wide concerns regarding employee development, recognition, and long-term career growth.

Top 5 Departments include:
-	Finance and Performance Management 
-	Human Services 
-	Planning and Public Works ( has the highest across all response types)
-	Prosecuting Attorney's Office 
-	Sheriff’s Department




3. As an Employer, the steps I  would take to improve employee satisfaction based  on the survey results. I will take the following steps;
> (A) Improve Career Development Opportunities
-	Provide training programs, mentorship, and clear promotion pathways to help employees grow professionally. 
> (B) Enhance Employee Recognition
-	Introduce reward and recognition programs to acknowledge employees’ hard work and achievements.
> (C ) Review Compensation and Benefits
-	Evaluate salaries and benefits to ensure they are competitive and aligned with employee expectations.
> (D) Strengthen Leadership and Communication
-	Train managers to communicate effectively, provide regular feedback, and support employees’ needs.
> (E) Increase Employee Engagement
-	Conduct regular surveys, feedback sessions, and team-building activities to ensure employees feel heard and valued.



  
4.  Top 5 Department  by Response
 > Shows top 5 departments with the highest number of survey questions response  that Shows positive, neutral, and negative responses for each department.
- The department with highest response is Planning and Public works with 48% 
-	Finance and Performance Management (11%)
-	Human Services (10%)
-	Planning and Public Works (48%)
-	Prosecuting Attorney's Office ( 12%)
-	Sheriff’s Department ( 19%)



5. Response Type Distribution
Displays the proportion of:
-	Strongly Agree ( 36%)
-	Agree (39%)
-	Not Applicable (3%)
-	Disagree (15%)
-	Strongly Disagree (7%)
Insight
Approximately 75% of respondents provided positive feedback (Agree or Strongly Agree), indicating generally favorable employee sentiment despite concerns in specific areas.


### INTERACTIVE ANALYSIS
The dashboard includes two interactive slicers that allow users to dynamically filter and explore survey responses . 
The interactive slicers provide flexibility for users to drill down into specific departments and response text, making it easier to identify trends, compare employee perceptions, and support data-driven decision-making.
1. Response Text Slicer
This slicer enables users to filter survey responses based on response categories:
-	Agree
-	Strongly Agree
-	Disagree
-	Strongly Disagree
-	Not Applicable
Purpose: Helps stakeholders analyze employee sentiment and identify areas of satisfaction or dissatisfaction across the organization.
2. Department Slicer
This slicer allows users to filter the dashboard by specific departments, including:
-	Finance and Performance Management
-	Human Service
-	Planning and Public Works
-	Prosecuting Attorney’s Office
-	Sheriff’s Department
-	Other departments in the dataset
Purpose: Enables comparison of employee satisfaction levels and response patterns across departments.


### RECOMMENDATION
1. Improve Career Growth Opportunities
-	Create transparent promotion pathways.
-	Offer professional programs.
-	Introduce mentorship initiatives.
2. Strengthen Employee Recognition
-	Implement employee recognition programs.
-	Celebrate outstanding performance regularly
-	Introduce performance-based incentives.
3. Enhance Leadership Effectiveness
-	Provide leadership and communication training
-	Encourage frequent manager-employee feedback sessions.
-	Improve supervisor accountability.
4. Increase Employee Engagement
-	Conduct quarterly employee surveys.
-	Organize team-building activities.
-	Create channels for anonymous employee feedback.
5. Monitor Departmental Satisfaction
-	Focus interventions on departments with higher negative response rates
-	Develop department-specific engagement strategies.

