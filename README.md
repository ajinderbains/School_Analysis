# School_Analysis
## Project Overview
School boared noticed that Thomas High School has misreported reading and math scores for 9th grade so boared has asked to re analysis following reports 
- District Summary
- School Summary
- Top 5 Performing Schools
- Bottom 5 Performing Schools
- Math and Reading scores for each  gradefrom each School
- Scores by Spending per student,school size and school type.

To perform analysis all reading and math score for 9th grade for Thomas High School will be replaced with Null values.
Comparison analysis will be performed with and without Null values of 9th grade for Thomas High School for above mentioned reports.

## Results
Replacing reading and math score for 9th grade for Thomas High School(461 rows are identified and replaced with Null value) has impacted mostly all School Summary reports but little impact on District summary.
- ### District Summary Report
  - By replacing reading and math score for 9th grade for Thomas High School has impacted district summary by **1%** of Average reading,math score,% passing math,reading and overall scores.After replacing to null values it is decreased to 78.0 ,80.9 74, 85, 64. As it is clear in following screenshots of with given original data and after replacing scores of 9th grade for Thomas High School with null values.
  - Total School countTotal student count and Total Budget remains same.
  #### Without NaN values
  ![districtrep](https://github.com/ajinderbains/School_Analysis/blob/master/Screenshots/school_district_nonNaN.PNG)
  #### With NaN values
  ![distrepnan](https://github.com/ajinderbains/School_Analysis/blob/master/Screenshots/DistrictSummary_Nan.png)
- ### School Summary Report
  - Replacing reading and math score for 9th grade of Thomas High School has impacted significantly school summary (for each school) to Thomas High school and other schools remain unaffected .
  - **Average reading,math scores** has dropped significantly for Thomas high school from **83.85 to 60.24** and **83.42 to 59.85** respectively. 
  - **% Passing reading ,math** scores has dropped significantly for Thomas high school from **97 to 69.66** and **93 to 66.91** respectively. 
  - **Overall passing** has dropped for Thomas high school from **91% to 65%**.
  #### Without NaN values
  ![schoolrep](https://github.com/ajinderbains/School_Analysis/blob/master/Screenshots/School_summary_nonNaN.PNG)
  #### With NaN values
  ![schrepnan](https://github.com/ajinderbains/School_Analysis/blob/master/Screenshots/SchoolSummary_Nan.png)
- ### Top 5 Performing Schools

  - Replacing reading and math score for 9th grade of Thomas High School has impacted the **top 5 performing** list of schools also. Before replacement **Thomas High school** was on **2nd place** with around **91% overall passing**.But after replacement Thomas High school is out of the top 5 performing school and new list has new entry of **Wright High School**.
  #### Without NaN values
  ![top5rep](https://github.com/ajinderbains/School_Analysis/blob/master/Screenshots/top5_nonNaN.PNG)
  #### With NaN values
  ![top5repnan](https://github.com/ajinderbains/School_Analysis/blob/master/Screenshots/top5_Nan.png)
 - ### Bottom 5 Performing Schools
  
   - It has not impacted the lowest 5 performing schools.Thomas High school's overall performance with NaN values is 65% which is higher than bottom 5 schools's.
  #### With and Without NaN values
  ![bot5rep](https://github.com/ajinderbains/School_Analysis/blob/master/Screenshots/Bottom5_schools.PNG)
 
•	Replacing reading and math score for 9th grade of Thomas High School has impacted the Thomas High School for Math and reading ,Scores by school spending,Scores by school size,Scores by school typeas follow
o	Math and Reading score for Thomas High School for 9th grade is 0 or null and it did not impacted the scores of other grades scores.Replacement to null values did not impacted the 9th grade scores because change was for 9th grade and Thomas High School only.
o	After replacement the Average scores has been dropped for spending range $630-644 . Other school spending ranges remained unchanged because It is because Thomas High School falls in this spending range.
o	After replacement the Average scores and %age passing scores has been dropped for Medium (1000-2000) size schools. Other school sizes remained unchanged because Thomas High School falls in this range.
o	Afer replacement the Average scores and %age passing scores also dropped for Charter School type and District school type remain unchaged because Thomas High School is Charter school type.
## Summary
Replacing reading and math score for 9th grade of Thomas High School with null values following are major changes for School District Analysis:
1.	Overall Passing,Average Math and reading scores for Thomas Hogh School have fallen significantly.
2.	Thomas High School has been dropped from top 5 performing schools list. New school Wright High School has been added at rank 5 and Griffin,Wilson and Pena High Schools have been ranked up to 2nd,3rd and 4th respectively.
3.	Average scores and %age passing scores also dropped for Charter School type.
4.	Average scores and %age passing scores also dropped for Spending Range ( $630-644) and Medium sized( Medium (1000-2000)) Schools .


