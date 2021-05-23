# school-district-analysis

# Overview of Project
This project re-evaluates the performance metrics of a city school district due to newly found errors in the data of Thomas High School's 9th grade exam scores. This project removes the data for Thomas High School's 9th grade exam scores, and then analyzes all the schools' information across seven different metrics. 

## Purpose
The goal of this project is to build an overview of student performance on standardized tests for each school, and to see if there are any correlations between student performance and their school's budget, size, or type. This information is designed to help the school district's superintendent and board of directors to make decisions about the schools' budgets and priorities. This project also examines how the removal of Thomas High School's 9th grade data may have affected each metric to help inform the school district's leaders if there were any important changes to the data caused by the errors.

# Results
- **District Summary**
  - Overall metrics for entire school district as a whole: [[Link to NEW Chart]](Resources/1_district_summary.PNG) --- [[Link to OLD Chart]]("Resources/Old_Charts/OLD_1_district_summary.PNG")
  - With the removal of Thomas' 9th grade data, there was a very marginal change for the scores of the entire school district. The percentage of students passing math decreased by roughly 0.2%, while the percent of students passing reading dropped by about 0.1%. The overall percentage of students who passed both subjects dropped by about 0.3%.
- **School Summary**
  - Metrics broken down by school: [[Link to NEW Chart]](Resources/2_school_summary.PNG) --- [[Link to OLD Chart]](Resources/Old_Charts/OLD_2_school_summary.PNG)
  - The only row affected by the changes is the row for Thomas High School. Even here the changes are very small, with both the percentages of students passing math and reading decreasing by less than 1%.
- **High and Low Performing Schools**
  - 5 highest performing schools: [[Link to NEW Chart]](Resources/3_highest_performing_schools.PNG) --- [[Link to OLD Chart]](Resources/Old_Charts/OLD_3_highest_performing_schools.PNG)
  - 5 lowest performing schools: [[Link to NEW Chart]](Resources/3_lowest_performing_schools.PNG) --- [[Link to OLD Chart]](Resources/Old_Charts/OLD_3_lowest_performing_schools.PNG)
  - No significant changes here either. Only Thomas High School's scores were affected, with passing percentages dropping by less than 1%, but the still ranks as #2 in the city school district as before.
- **Math and Reading Scores by Grade**
  - Math scores for each grade by school: [[Link to NEW Chart]](Resources/4_math_scores_by_grade.PNG) --- [[Link to OLD Chart]](Resources/Old_Charts/OLD_4_math_scores_by_grade.PNG)
  - Reading scores for each grade by school: [[Link to NEW Chart]](Resources/4_reading_scores_by_grade.PNG) --- [[Link to OLD Chart]](Resources/Old_Charts/OLD_4_reading_scores_by_grade.PNG)
  - With the exception of Thomas' 9th grade's scores being turned to "NaN", these charts are unaffected by the change.
- **Scores by School Spending**
  - Student performance by school budget: [[Link to NEW Chart]](Resources/5_scores_by_school_spending.PNG) --- [[Link to OLD Chart]](Resources/Old_Charts/OLD_5_scores_by_school_spending.PNG)
  - There is no change to this chart.
- **Scores by School Size**
  - Performance by student population: [[Link to NEW Chart]](Resources/6_scores_by_school_size.PNG) --- [[Link to OLD Chart]](Resources/Old_Charts/OLD_6_scores_by_school_size.PNG)
  - There is no change to this chart.
- **Scores by School Type**
  - Performance by school type (charter or district): [[Link to NEW Chart]](Resources/7_scores_by_school_type.PNG) --- [[Link to OLD Chart]](Resources/Old_Charts/OLD_7_scores_by_school_type.PNG)
  - There is no change to this chart.

# Summary
On the whole, not very much was impacted by the removal of Thomas High School's 9th grade scores. The main points of impact were in the first four metrics used to analyze the school district -- the District Summary, the School Summary, the High and Low Performing Schools, and the Math and Reading Scores by Grade. In the District Summary, the removal of the data caused the percentages of passing students to decrease by a small amount, but by no more than 0.3%. In the School Summary and in the High and Low Performing Schools charts, only Thomas High School's measurements were affected with scores decreasing by less than 1%, but the school still maintained its #2 rank in the district's top 5 schools. Finally, for the charts of the Math and Reading Scores by Grade, Thomas High School's 9th grade scores were simply removed and replaced with "NaN", and there were no other changes to the rest of the two charts.
