# Education-Salary-Regression-Analysis
This course project looks into how duration could affect career success.

- [Education-Salary-Regression-Analysis](#education-salary-regression-analysis)
    - [Project Summary and Introduction](#project-summary-and-introduction)
    - [Why is this Question/Analysis Important?](#why-is-this-questionanalysis-important)
    - [Potential Business Implications](#potential-business-implications)
    - [About the Dataset](#about-the-dataset)


### Project Summary and Introduction
In this project, we evaluate the impact of education on career success using salary as a proxy. Specifically, we research how the relevancy of one's education field and education level affect their salary. 

"Salary" (Monthly Income) is used as our dependent variable as a proxy of workplace success and progression. 

"Education" being our independent variable, is evaluated from two main perspectives. The first one being the education level's impact on career success. Would a graduate degree result in a higher average salary? Secondly, we look at the relevancy of education background or field with the employee's job role. Would having an education in a relevant field yield a better salary?

### Why is this Question/Analysis Important?
Education is commonly considered as a key factor when determining the personal attainment of a candidate or employee. Job roles typically prefer or even require specific education levels or fields of study, yet we lack empirical evidence to understand the true impact education has on career success.

### Potential Business Implications
Gaining insight into this topic could potentially be very valuable especially from a Human Resources standpoint. Having a data driven approach to guide hiring and employee promotion decisions could mean better prospects and career progression for an employee within a company.

A more streamlined allocation of budget that accounts for the different impacts that an employee's education background has on each functional role in a company could ensure employees with higher relevant skillsets and productivity are rewarded accordingly.

A possible benefit from these would mean lower attrition rates, as employees might have a higher motivation to leave when they are not paid adequately or feel stagnated in their career paths. With lower attrition rates, a company could reduce wastage on the expensive process of onboarding and training.


### About the Dataset
Source : [Dataset Link](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset)

We chose to go with a single dataset by IBM that contains information on employee satisfaction, income, seniority, and demographics like age and education background. It includes data for 1,470 employees.

Of the 35 columns, we use the following:
| Column      | Description |
| ----------- | ----------- |
| MonthlyIncome       | The monthly salary for the employee, which is used as the gauge for career success.       |
| Gender              | Whether the employee is Male or Female.        |
| JobRole             | The name of the role held by the employee, which we use to determine the relevant field.        |
| Department          | The department the employee works in, which we use to group employees and also to determine a manager's relevant field.        |
| Education           | The employee's education level, from Level 1 to 5, including Below College, College, Bachelor, Master, Doctorate.        |
| EducationField      | The field that the employee received education in, including Human Resources, Life Sciences, Marketing, Medical Sciences, Others, and Technical.|
| TotalWorkingYears   | The total number of years worked.|
