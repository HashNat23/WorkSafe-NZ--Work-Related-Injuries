# WorkSafe-NZ--Work-Related-Injuries
![WorkSafeNZ](https://github.com/HashNat23/WorkSafe-NZ--Work-Related-Injuries/blob/main/Worksafe%20logo.png)
<br>
<br>
## Introduction
WorkSafe is primarily responsible for overseeing workplace health and safety in New Zealand. More than 500 employees, led by their Chief Executive Officer Phil Parker, aim to enable New Zealanders' return home to work in a safe and healthy manner. According to the Health and Safety at Work Act of 2015 (HSWA), it is their duty to ensure the health and safety of their employees as well as any other workers it influences or has control over.
## Business Scenario
WorkSafe find it unacceptable as every year an estimated 700-900 people are reported death because of work-related injuries. The organization have following questions on basis of which I would do my analysis.
 <br>
 <br>
•	What are the top 3 locations that result into most injuries? 
<br>
•	How much was the time taken to recover looking at the injury type?
<br>
•	Which are the most common injuries?
<br>
•	Which are the most common severe injuries?
<br>
•	Which industries have got more fatality rate?
<br>
•	What is the severity of the injury as per sector
<br>
•	What is the trendline for severity of injury as per sector
<br>
<br>
They have a target and set as priorities to rebuild New Zealand’s workplace health and safety performance which also includes the Government’s target to drop workplace injuries and fatalities by 25% by 2020. Moreover, the social and economic cost of injuries, illnesses and deaths arising from work is estimated at $3.5 billion a year

## Business Problem
WorkSafe would like to understand the impact of work-related disease. This will help them determine the effective ways to improve worker health that includes managing mental as well as physical health risks. 
<br>
They would also like to measure the quality and length of life lost to injuries and illnesses, with the help of work-related health estimates.
<br>
From the above business problem, I would like to analyze work-related injuries that occurred to people employed by New Zealand organizations. With this analysis, it will solve the issues for workers particularly those that have the potential to cause serious injury or illness. The organizations can provide information, training to workers on how they can take safety measures on their own where possible. The company can put instructions on hazardous areas such as power board, stairs, wet areas and so on.
<br>
The data will be analyzed looking:
* By Industry
* Severity of injury
* Location
<br>
In the analysis, though the data is people related, there is no sensitive information such as User ID, phone number, email address used that can affect the cultural and ethical aspects. Another reason is as it does not include ethnicity of people or shows or cultural background. 

## Data Sourcing
The dataset for the analysis is taken from Figure.nz site. The data is available to public from the website. It saved on my machine and will be shared with anyone. The data is just used for my analysis purposes.
<br>
<br>
The dataset contains useful information that would be very helpful for my analysis, such as Location, Industry, Injury Type and Severity of Injury. With the help of these variables, I believe the organization will have a clear understanding of why work-related injuries are increasing and which are the areas that are at risks for workers. Looking at the outcome, the organizations can take precautions for safety of their employees. Moreover, the dataset also contains Industry type, so we can focus on which industry has higher number of cases for serious injuries and illnesses. 
<br>
<br>
However, the dataset contains not relevant data that I would require for the analysis. The Industry Code, Value Unit and Value Label variables are not required for the analysis in relation to the business problems 
## Business Questions
1. What are the top 3 locations that result into most injuries?
2. How much was the time taken to recover looking at the injury type?
3. Which are the most common injuries?
4. Which are the most common severe injuries?
5. Which industries have got more fatality rate?
6. What is the severity of the injury as per sector?
7. What is the trendline for severity of injury as per sector?
## Target Audience
![Target Audience](https://github.com/HashNat23/WorkSafe-NZ--Work-Related-Injuries/blob/main/Screenshot%202025-07-04%20123317.png)
## Data Wrangling
The below are the steps of data wrangling means cleaning the unwanted data from the dataset.
<br>
* The below is the original dataset
## Techniques Applied
* Performed EDA (Exploratory Data Analysis) with the help of Histogram, pie-chart and line-chart, and bar chart. 
* These analysis shows there is decrease in number of injuries over time.
* Diagnostic Analysis was done through Chi-square test and ANOVA Single Factor test. 
* The result of Chi-square tests shows that we reject the null hypothesis and accept the alternative, that means the two variables Industry and Injury Type are related to each other.
* The result tells us that the greater number of claims does not relate with these two locations.

![Techniques Applied](https://github.com/HashNat23/WorkSafe-NZ--Work-Related-Injuries/blob/main/Techniques_applied.png)
## Dashboard
![Dashboard](https://github.com/HashNat23/WorkSafe-NZ--Work-Related-Injuries/blob/main/Dashboard.png)
## Business Insight
The top three places, top three industries, and unsafe industries where the most injuries occurred have been identified after doing EDA and diagnostic analysis based on the business questions. 
Based on these analyses, organizations can take the necessary actions to lower injuries and maintain a safe workplace for their employees. 
Chi-square studies have also shown that the industry and severity of injury variables have an impact on the injury, which in turn raises the number of claims that WorkSafe receives. 
According to an ANOVA test, location is not a significant influence in the rise in workplace injuries.







