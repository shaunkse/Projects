# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Testing, Statistical Summaries and Inference


### Overview
The first project is to use basic python programming concepts to do vidualization with given datasets, EDA and some basic statistics

### Datasets

#### Provided Data
For this project, two datasets were given:

- [2017 SAT Scores]
- [2017 ACT Scores]

After cleaning the data, a new version of data is being compiled:
- [combined_2017]
- [combined 2018]
- [combined 1718]

The following data dictionary is for the file [combined_1718]

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*String*|ACT/SAT|States in US|
|**participation_act_2017**|*Float*|ACT 2017|Percentage of students took act in 2017|
|**participation_sat_2017**|*Float*|ACT 2017|Percentage of students took sat in 2017|
|**english_act_2017**|*Float*|ACT 2017|Mean score range: 1 to 36|
|**math_act_2017**|*Float*|ACT 2017|Mean score range: 1 to 36|
|**reading_act_2017**|*Float*|ACT 2017|Mean score range: 1 to 36|
|**science_act_2017**|*Float*|ACT 2017|Mean score range: 1 to 36|
|**composite_act_2017**|*Float*|ACT 2017|Mean Score of mean scores of the 4 ACT Subjects, range: 1 to 36|
|**evidence-based reading and writing_sat_2017**|*Float*|SAT 2017|Score range: 200 to 800|
|**math_sat_2017**|*Float*|SAT 2017|Score range: 200 to 800|
|**total_sat_2017**|*Float*|SAT 2017|Score range: 400 to 1600|
|**percentage_of_students_tested_act_2018**|*Float*|ACT 2018|Percentage of students took act in 2018|
|**participation_sat_2018**|*Float*|ACT 2018|Percentage of students took sat in 2018|
|**average_english_score_act_2018**|*Float*|ACT 2018|Mean score range: 1 to 36|
|**average_math_score_act_2018**|*Float*|ACT 2018|Mean score range: 1 to 36|
|**average_reading_score_act_2018**|*Float*|ACT 2018|Mean score range: 1 to 36|
|**average_science_score_act_2018**|*Float*|ACT 2018|Mean score range: 1 to 36|
|**average_composite_score_act_2018**|*Float*|ACT 2018|Mean Score of mean scores of the 4 ACT Subjects, range: 1 to 36|
|**evidence-based_reading_and_writing_sat_2018**|*Float*|SAT 2018|Score range: 200 to 800|
|**math_sat_2018**|*Float*|SAT 2018|Score range: 200 to 800|
|**total_sat_2018**|*Float*|SAT 2018|Score range: 400 to 1600|

### Problem/Question & statistical finding(s)
The problem statement is:
'Is the participation rate justified with the funds that the governments in US have provided?'

With this, a data science problem is form by:
'What is the trends in the increase/decrease in participation rate in SAT/ACT in 2017 and 2018'

There were hypothesis testing done to see if there
1) is any significant difference between participation rate for ACT 2017 and participation rate for SAT 2017, and 
2) is any significnat difference between participation rate for ACT 2018 and participation rate for SAT 2018. 

The result was that both the differences are significant but we are unable to to tell in which direction is the difference headed to. 

with extra and external researches, it is found that there is a high probability that the differences is towards having more people participating in the SAT exam than in the ACT exam. 

### Analysis and with external research
There seem to be a trend of colleages accepting SAT exam results. 
Ability to participate and scoring well in SAT seem to be linked to household income and quality of life of the state

### Recommendations
Suggesting the government body that regulate the education diretion of the state to provide more funding and free waiver for students to participate in SAT exams. 

---

