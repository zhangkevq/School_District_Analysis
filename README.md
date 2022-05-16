# School_District_Analysis


## Project Overview
  In this project, we seek to remove all 9th graders' math and reading scores at Thomas High School and replace them with "NaN". This is due to the evidence of academic dishonesty found in the [students_complete.csv](https://github.com/zhangkevq/School_District_Analysis/blob/main/Resources/students_complete.csv) file. Using Python, we removed the records and observed the effects on the performance accross all schools in the district.
  
### Project Deliverables:
  1) Effect on district summary
  2) Effect on school summary
  3) Effect on Thomas High School's perfomance relative to other schools
  4) Effect on school grades vs. logistics

## Effect on District Summary
  This is the original district summary:  <br>  
  ![original district summary](https://github.com/zhangkevq/School_District_Analysis/blob/main/Resources/district_analysis_original.png)
  
  And here is the updated district summary after removing 9th grader scores:  <br>  
  ![updated district summary](https://github.com/zhangkevq/School_District_Analysis/blob/main/Resources/district_analysis_updated.png)
  
  As we can see, there is very little change in the overall district summary stats. Average math score and % passing math/reading/overall categories have all gone down around 0.1-0.3 (points or percent, depending on category). The subraction in all categories is noticeably consistent.
  
## Effect on School Summary
  The original school summary: <br>  
  ![original school summary](https://github.com/zhangkevq/School_District_Analysis/blob/main/Resources/school_analysis_original.png)
  
  The updated school summary: <br>  
  ![updated school summary](https://github.com/zhangkevq/School_District_Analysis/blob/main/Resources/school_analysis_updated.png)

#### Effect on Thomas High School's Performance Relative to Other Schools

  For every school except Thomas High School, all metrics remained the same. And once again, the updated school summary has a slightly lower score and percent passing average after updating the 9th grader scores. These changes are similar to the ones from changes in the district summary.

  
## Effect on Other Logistics
### Math and Reading Scores by Grade
  Original math and reading scores by grade: <br>  
  ![](https://github.com/zhangkevq/School_District_Analysis/blob/main/Resources/scores_by_grade_original.png)
  
  Updated math and reading scores by grade: <br>  
  ![](https://github.com/zhangkevq/School_District_Analysis/blob/main/Resources/scores_by_grade_updated.png)
  
  
### Scores by School Spending
  Original scores by school spending: <br>  
  ![](https://github.com/zhangkevq/School_District_Analysis/blob/main/Resources/spending_summary_original.png)
  
  Updated scores by school spending: <br>  
  ![](https://github.com/zhangkevq/School_District_Analysis/blob/main/Resources/spending_summary_updated.png)
  
  
### Scores by School Size
  Original scores by school size: <br>  
  ![](https://github.com/zhangkevq/School_District_Analysis/blob/main/Resources/scores_by_size_original.png)
  
  Updated scores by school size: <br>  
  ![](https://github.com/zhangkevq/School_District_Analysis/blob/main/Resources/scores_by_size_updated.png)
  
  
### Scores by School Type
  Original scores by school type: <br>  
  ![original scores by school type](https://github.com/zhangkevq/School_District_Analysis/blob/main/Resources/scores_by_school_type_original.png)
  
  Updated scores by school type: <br>  
  ![updated scores by school type](https://github.com/zhangkevq/School_District_Analysis/blob/main/Resources/scores_by_school_type_updated.png)

#### Summary of Above stats
  Just like in the distrcit and school summary charts, there is no change to the statistics of grades in other schools, but Thomas High School has changed scores all around after dropping all 9th grade scores. Following the trends in previous charts, they are all changes in the negative direction.
