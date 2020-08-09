# School_Analysis
## Project Overview
School boared noticed that Thomas High School has misreported reading and math scores for 9th grade so board has asked to re analysis following reports 
- District Summary
- School Summary
- Top 5 Performing Schools
- Bottom 5 Performing Schools
- Math and Reading scores for each  grade from each School
- Scores by Spending per student,school size and school type.

To perform analysis all reading and math score for 9th grade for Thomas High School will be replaced with Null values.
Comparison analysis will be performed with and without Null values of 9th grade for Thomas High School for above mentioned reports.

## Results
Replacing reading and math score for 9th grade for Thomas High School(461 rows are identified and replaced with Null value) has impacted mostly all School Summary reports but little impact on District summary.
- ### District Summary Report
  - By replacing reading and math score for 9th grade for Thomas High School has impacted district summary by **1%** of Average reading,math score,% passing math,reading and overall scores.After replacing to null values it is decreased to 78.0 ,80.9 74, 85, 64. As it is clear in following screenshots of with given original data and after replacing scores of 9th grade for Thomas High School with null values.
  - Total School count ,Total student count and Total Budget remains same.
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
- ### After replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools
  - ### Top 5 Performing Schools

    - Replacing reading and math score for 9th grade of Thomas High School has impacted the **top 5 performing** list of schools also. Before replacement **Thomas High school** was on **2nd place** with around **91% overall passing**.But after replacement Thomas High school is out of the top 5 performing school and new list has new entry of **Wright High School**.
    - Thomas High School ranking slipped from **2nd to 8th** .
    - Average Math and Reading score are  **24 points less then  by  in comparison to Top 5 performing schools**.
    - Percentage math and reading scores are **27 points less than by in comparison to Top 5 performing schools**. 
  #### Without NaN values
  ![top5rep](https://github.com/ajinderbains/School_Analysis/blob/master/Screenshots/top5_nonNaN.PNG)
  #### With NaN values
  ![top5repnan](https://github.com/ajinderbains/School_Analysis/blob/master/Screenshots/top5_Nan.png)
    - ### Bottom 5 Performing Schools
  
      - It has not impacted the lowest 5 performing schools.Thomas High school's overall performance with NaN values is **65%** which is higher than bottom 5 schools's.
  #### With and Without NaN values
  ![bot5rep](https://github.com/ajinderbains/School_Analysis/blob/master/Screenshots/Bottom5_schools.PNG)
- ### Impact of replacing Math and Reading score of 9th Grade to NaN for Thomas High School by Grade,School Spending,School size and School type 
  - ### Math and Reading Scores for each School
    -	Replacing reading and math score for 9th grade of Thomas High School has not  impacted other schools except the Thomas High School for Math and reading scores .Math and reading scores for Thomas High School has dropped to **0** for **9th Grade**only
    -  Reading and Math scores for other grades remain same.
    - Reading and Math scores for other schools for each grade remain same. 
  #### Math Score Without NaN values
  ![mathrep](https://github.com/ajinderbains/School_Analysis/blob/master/Screenshots/mathscore_nonNan.png)
  #### Math Score With NaN values
  ![mathrepnan](https://github.com/ajinderbains/School_Analysis/blob/master/Screenshots/mathscore_Nan.png)
  #### Reading Score Without NaN values
  ![readrep](https://github.com/ajinderbains/School_Analysis/blob/master/Screenshots/readingscore_nonNan.png)
  #### Reading Score With NaN values
  ![readrepnan](https://github.com/ajinderbains/School_Analysis/blob/master/Screenshots/readingscore_Nan.png)
  - ### Scores by School Spending
    - After replacement the Average scores for math and reading  has been dropped for spending range **$630-644**  from **78.5 to 72.6** and **81.6 to 75.7** respectively
    - After replacement the % passing scores for math and reading dropped for spending range **$630-644**  from **73 to 67** and **84 to 77** respectively.
    - After replacement Overall performance is dropped from **63 to 56** for spending range **$630-644**.
    - Other school spending ranges remained unchanged because It is because Thomas High School falls in this spending range.
   #### Without NaN values
   ![spendrep](https://github.com/ajinderbains/School_Analysis/blob/master/Screenshots/schoolspendinf_nonNan.png)
   #### With NaN values
   ![spendrepnan](https://github.com/ajinderbains/School_Analysis/blob/master/Screenshots/Schoolspending_Nan.png)
    - ### Score by School size
       - After  replacement the Average math and reading  scores  has been dropped for **Medium (1000-2000)** size schools from **83.4 to 78.7** and **83.9 to 79.1**
       - After  replacement the % passing scores for math and reading dropped  for **Medium (1000-2000)** size schools from **94 to 88** and **97 to 91**.
       - After  replacement the overall performance  has been dropped for **Medium (1000-2000)** size schools from **91 to 85** .
       - Other school sizes remained unchanged because Thomas High School falls in this range.
    #### Without NaN values
   ![sizerep](https://github.com/ajinderbains/School_Analysis/blob/master/Screenshots/schoolsize_nonNan.png)
   #### With NaN values
   ![sizerepnan](https://github.com/ajinderbains/School_Analysis/blob/master/Screenshots/Schoolsize_Nan.png)  
  - ### Score by School Type
       - After  replacement the Average math and reading  scores  has been dropped for **Charter** schools from **83.5 to 80.5** and **83.9 to 80.9**
       - After  replacement the % passing scores for math and reading dropped for  **charter** schools from **94 to 90** and **97 to 93**
       - After  replacement the overall performance  has been dropped for **Charter** schools from **90 to 87** 
       - District school type remained unchanged because Thomas High School is **charter** scholl type .
    #### Without NaN values
   ![typerep](https://github.com/ajinderbains/School_Analysis/blob/master/Screenshots/schooltype_nonNan.png)
   #### With NaN values
   ![typerepnan](https://github.com/ajinderbains/School_Analysis/blob/master/Screenshots/Schooltype_Nan.png)  

## Summary
Replacing reading and math score for 9th grade of Thomas High School with null values following are major changes for School District Analysis:
1.	Overall Passing,Average Math and reading scores for **Thomas Hogh School have fallen significantly**.
2.	Thomas High School has been **dropped from top 5 performing schools** list. New school Wright High School has been added at rank 5 and Griffin,Wilson and Pena High Schools have been ranked up to 2nd,3rd and 4th respectively.
3.	Average math and reading scores and %age passing scores for math and reading  also dropped for **Charter** School type.
4.	Average math and reading scores and %age passing scores for math and reading  also dropped for **Spending Range ( $630-644)** and **Medium sized( Medium (1000-2000))** Schools .


