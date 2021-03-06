# School_District_Analysis

## Project Overview
The purpose of the school data audit was to evaluate whether purported academic dishonesty among Thomas High School impacted the results of the original analysis of the school district. The school board has asked us to replace the math and reading scores for Thomas High School with NaN (not a number) while we kept the rest of the data intact. 

- The district summary
- The school summary
- The top 5 and bottom 5 performing schools, based on the overall passing rate
- The average math score for each grade level from each school
- The average reading score for each grade level from each school
- The scores by school spending per student, by school size, and by school type

## Resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: Jupyter, Python 3.6.1, pandas data analysis tool, conda 4.12.0
	
## Results

- The average math scored changed from 78.9 to 79.0 in the new school district summary. The average reading score stayed the same. The % passing math change from 74.8% to 75%. The % passing reading change from 85.7% to 86%. The % overall passing changed from 64.95 to 65%. These changes were small but noticeable. 
Old District Summary: 
![Old_dist_sum](https://github.com/NickFoley47/School_District_Analysis/blob/main/Resources/Old_dist_sum.PNG)
New District Summary: 
![New_dist_sum](https://github.com/NickFoley47/School_District_Analysis/blob/main/Resources/New_dist_sum.PNG)

- The school summary had some major changes when we replaced the 9th grader scores for math and reading. The % passing math dropped from 93.27% to 66.91%. The % passing reading dropped from 97.30% to 69.66%.

Old School Summary:
![per_school_sum_older_old_data](https://github.com/NickFoley47/School_District_Analysis/blob/main/Resources/per_school_sum_older_old_data.PNG)

New School Summary: 
![per_school_sum_new_old_data](https://github.com/NickFoley47/School_District_Analysis/blob/main/Resources/per_school_sum_new_old_data.PNG)
- Replacing the 9th graders scores and only then only counting 10th ??? 12th grade did not affect the test scores as much when we still included Nans in the data. The average math score changed from 83.41 to 83.35. The average reading score changed from 83.84 to 84.89. Thomas high School had an 90.63% overall passing after removing the 9th grader data which brought it up from the 65.07% overall passing when we included the 9th graders Nans in the data. 

Thomas High School Performance updated with grades 10th???12th:
![per_school_sum_new_new_data1](https://github.com/NickFoley47/School_District_Analysis/blob/main/Resources/per_school_sum_new_new_data1.PNG)

 The effect of replacing 9th grade scores: 
- The math and reading scores were updated with NaN since the 9th grade data was altered and thus 9th grade data for Thomas High School was removed.

Math grades by grade:

![math_grades_by_grade1](https://github.com/NickFoley47/School_District_Analysis/blob/main/Resources/math_grades_by_grade1.PNG)

Reading grades by grade:

![reading_grades_by_grade](https://github.com/NickFoley47/School_District_Analysis/blob/main/Resources/reading_grades_by_grade.PNG)

- The scores by school spending have had no change. They are still students thus the spending would remain the same for the 9th graders.

- The scores by school size have had very small changes. Due to the 9th graders not being counted. This change was so small, when we formatted our data the difference was eliminated. 

![scores_by_school_size_new](https://github.com/NickFoley47/School_District_Analysis/blob/main/Resources/scores_by_school_size_new.PNG)

- The scores by school type have had a very small change since the scores of the 9th graders were nulled due to data altering. The difference is so small when the formatting is fixed. The difference is eliminated. 


## Summary Challenge Overview
There have been small changes to the district analysis after the grades for the Thomas High School 9th graders have been replaced. The data would include on 10th-12th graders at Thomas High School.
1.	The average math score went from 83.41 to 83.35.
2.	The average reading score went from 83.84 to 83.89.
3.	The overall passing went from 90.94% to 90.63%
4.	The % passing math went from 93.27% to 93.18%.



