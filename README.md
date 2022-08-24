# School_District_Analysis
## Purpose
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty. This is specifically with reading and math grades for Thomas High School ninth graders as there appears to have been grades altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked us to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once we have replaced the math and reading scores, Maria would like us to repeat the school district analysis that we did in this module and write up a report to describe how these changes affected the overall analysis.

## Overview

This Analysis is going to show us how exactly was the data set of the district analysis and the school analysis affected when we consider the academic dishonesty of 9th Grade students in Thomas High School. The first step in this process was to remove the Math and Reading grades from just that criteria of students. 
#### Data is removed from one of the 9th Grade Students

![NAN](https://github.com/Andrew-E-Walters/School_District_Analysis/blob/main/Resources/Photos/NaN_One_example.png)

#### When we filter to the 9th Graders at Thomas High School we see all grades are removed

![NAN](https://github.com/Andrew-E-Walters/School_District_Analysis/blob/main/Resources/Photos/NaN_Thomas.png)


Once we were able to remove just the relevant data, we could then redo our District and School analysis. It will be interesting to see how exactly this data was impacted by the removal of that subsection of students from the overall data. 

## Results

Once everything was gathered, we could then look at how the new summaries differed from the PyCitySchools analysis we had done for the module. 



#### District Summary Original 
![PY CITY SCHOOLS ORIGINAL](https://github.com/Andrew-E-Walters/School_District_Analysis/blob/main/Resources/Photos/PYCitySchoolsDist.png)

#### District Summary New
![SCHOOL SUMMARY AFTER REMOVAL](https://github.com/Andrew-E-Walters/School_District_Analysis/blob/main/Resources/Photos/District_Summary_All_Students.png)

We immediately see a few examples of how this changes the data for the district summary:
- Lower Passing Math %
- Lower Passing Reading %
- Lower Overall Passing %

####  School Summary Original
![PY CITY SCHOOLS ORIGINAL](https://github.com/Andrew-E-Walters/School_District_Analysis/blob/main/Resources/Photos/PycitySchoolSummary.png)

#### School Summary New 
![SCHOOL SUMMARY AFTER REMOVAL](https://github.com/Andrew-E-Walters/School_District_Analysis/blob/main/Resources/Photos/THOMASwithUpdatedData.png)

#### How School District Metrics were effected
Because of the Analysis we did, it had impacts on the metrics
- Lower Average Math Score
- Lower Average Reading Score
- Lower % Passing Math 
- Lower % Passing Reading
- Lower Overall Passing %
- For the last two metrics "Total Students" and "Total Budget", they in some cases will change, and in other cases remain the same. It depends on the criteria asked for the anaylsis. Since in some sections we were tasked with ommitting only grades, the changes we did only impacted the grade calculations while the student count and budget remained the same. However in some sections the budget and students could change if we were omitting every metric of the 9th Graders from Thomas High School. 

#### School Count if Thomas Nith Grade is Not included.
![SCHOOL COUNT UPDATE](https://github.com/Andrew-E-Walters/School_District_Analysis/blob/main/Resources/Photos/If%20Using%20New%20School%20Count/District_Summary.png)



### Relative impact
While Thomas High School still is in the top of the pack for High School Performance this does bring them down in overall metrics. They are still in the Top 5 Schools for the District. 

#### Top Schools After Analysis
![SCHOOL SUMMARY AFTER REMOVAL](https://github.com/Andrew-E-Walters/School_District_Analysis/blob/main/Resources/Photos/TopSchoolsAfterAnalysis.png)

#### School Grade by Population
![Schools by Size](https://github.com/Andrew-E-Walters/School_District_Analysis/blob/main/Resources/Photos/New_Grade%20by%20Size.png)

The School metrics impacted were the medium schools since Thomas High School is in that grouping. 

#### School Grade by Per Capita Spending
![Schools by Spend](https://github.com/Andrew-E-Walters/School_District_Analysis/blob/main/Resources/Photos/New_Grades_by_Budget.png)


The School metrics impacted were the schools that spend $631-645 per student since Thomas High School is in that grouping. 

#### School Groups by Type
![Schools by Type](https://github.com/Andrew-E-Walters/School_District_Analysis/blob/main/Resources/Photos/Charter_updated.png)

The School metrics impacted were the charter schools since Thomas High School is in that grouping. 

## Summary 
### Four Changes 
There are some take aways from this analysis and it seems that the largest factors to consider are:
- Lower overall Grades for the Thomas High School 
- Lower Overall Grades for the District as a whole
- Lower Overall Grades for the 9th Grade
- Lower Overall Grades for the Charter Schools 

