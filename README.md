# School_District_Analysis



## Overview of the school district analysis: Explain the purpose of this analysis.

The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

### How is the district summary affected?

District Summary is not significantly affected, results are virtually the same. 

![SchoolType1](Resources/SchoolType1.png)

![SchoolType2](Resources/SchoolType2.png)

### How is the school summary affected?

School Summary is not gnificantly affected by removing the 9th graders results. Since we are looking at significant amount of data by removing the 467 students on 9th grade , the effect is a very slight reduction on scores, barely affecting the overall passing from 65% to 64.9%

* Initial Analysis
![Summary1](Resources/Summary1.png)

* Updated Analysis 
![Summary2](Resources/Summary2.png)


### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?



How does replacing the ninth-grade scores affect the following:

Math and reading scores by grade:
*
Scores by school spending
Scores by school size
Scores by school type


##Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.



A high-level snapshot of the district's key metrics, presented in a table format
An overview of the key metrics for each school, presented in a table format
Tables presenting each of the following metrics:
Top 5 and bottom 5 performing schools, based on the overall passing rate
The average math score received by students in each grade level at each school
The average reading score received by students in each grade level at each school
School performance based on the budget per student
School performance based on the school size 
School performance based on the type of school
