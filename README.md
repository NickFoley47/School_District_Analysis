# School_District_Analysis

## Project Overview
The purpose of the school data audit was to evaluate whether purported academic dishonesty among Thomas High School impacted the results of the original analysis of the school district. The school board has asked us to replace the math and reading scores for Thomas High School with NaN (not a number) while we kept the rest of the data intact. 

## Resources
-Data Source: schools_complete.csv, students_complete.csv
-Software: Jupyter, Python 3.6.1
	
## Results

-The average math scored changed from 78.9 to 79.0 in the new school district summary. The average reading score stayed the same. The % passing math change from 74.8% to 75%. The % passing reading change from 85.7% to 86%. The % overall passing changed from 64.95 to 65%. These changes were small but noticeable. 
Old District Summary: 
![Old_dist_sum](https://github.com/NickFoley47/School_District_Analysis/blob/main/Resources/Old_dist_sum.PNG)
New District Summary: 
![New_dist_sum](https://github.com/NickFoley47/School_District_Analysis/blob/main/Resources/New_dist_sum.PNG)

-The school summary had some major changes when we replaced the 9th grader scores for math and reading. The % passing math dropped from 93.27% to 66.91%. The % passing reading dropped from 97.30% to 69.66%. 
Old School Summary:
![per_school_sum_older_old_data](https://github.com/NickFoley47/School_District_Analysis/blob/main/Resources/per_school_sum_older_old_data.PNG)
New School Summary: 
![per_school_sum_new_old_data](https://github.com/NickFoley47/School_District_Analysis/blob/main/Resources/per_school_sum_new_old_data.PNG)
-Replacing the 9th graders scores and only then only counting 10th – 12th grade did not affect the test scores as much when we still included Nans in the data. The average math score changed from 83.41 to 83.35. The average reading score changed from 83.84 to 84.89. Thomas high School had an 90.63% overall passing after removing the 9th grader data which brought it up from the 65.07% overall passing when we included the 9th graders Nans in the data. 
Thomas High School Performance updated with grades 10th–12th:
![per_school_sum_new_new_data1](https://github.com/NickFoley47/School_District_Analysis/blob/main/Resources/per_school_sum_new_new_data1.PNG)


 The effect of replacing 9th grade scores: 
- The math and reading scores were updated with NaN since the 9th grade data was altered and thus 9th grade data for Thomas High School was removed.
Math grades by grade:
![math_grades_by_grade1](https://github.com/NickFoley47/School_District_Analysis/blob/main/Resources/math_grades_by_grade1.PNG)
Reading grades by grade:
![reading_grades_by_grade](https://github.com/NickFoley47/School_District_Analysis/blob/main/Resources/reading_grades_by_grade.PNG)
- Scores by school spending

- Scores by school size
- Scores by school type


 ## Summary Challenge Overview


