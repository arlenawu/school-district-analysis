# school-district-analysis

# Overview of Project
In light of a newly found error in the raw data, this project re-analyzes data from a city school district in order to build an overview of student performance on standardized tests for each school, and to see if there are any correlations between student performance and their school's budget, size, or type.

## Purpose
The purpose of this project is to re-evaluate performance metrics of a city school district due to potential errors in the data of Thomas High School's 9th grade exam scores. This project removes the erroneous data and analyzes all the schools' information across seven different metrics in order to help the school district's superintendent and board of directors to make decisions about the school budgets and priorities. It also examines how the removal of Thomas High School's 9th grade data may have affected each metric.

# Results
- **District Summary**
  - Overall metrics for entire school district as a whole: [[Link to NEW Chart]](Resources/1_district_summary.PNG)
  - With the removal of Thomas' 9th grade data, there was a very marginal change for the scores of the entire school district. The percent of students passing math decreased by roughly 0.1 points, while the percent of students passing reading had a nearly imperceptible change, dropping by less than 0.1 points. Verdict: the District Summary was not significantly affected.
- **School Summary**
  - Metrics broken down by school: [[Link to NEW Chart]](Resources/2_school_summary.PNG)
  - The only row affected by the changes is the row for Thomas High School. Even here the changes are very small, with both the percentages of students passing math and reading decreasing by less than 1%.
- **High and Low Performing Schools**
  - 5 highest performing schools: [[Link to NEW Chart]](Resources/3_highest_performing_schools.PNG)
  - 5 lowest performing schools: [[Link to NEW Chart]](Resources/3_lowest_performing_schools.PNG)
  - No significant changes here either. Thomas High School still ranks as #2 in the city school district.
- **Math and Reading Scores by Grade**
  - Math scores for each grade by school: [[Link to NEW Chart]](Resources/4_math_scores_by_grade.PNG)
  - Reading scores for each grade by school: [[Link to NEW Chart]](Resources/4_reading_scores_by_grade.PNG)
  - With the exception of Thomas' 9th grade's scores being turned to "NaN", these charts are unaffected by the change
- **Scores by School Spending**
  - Student performance by school budget: [[Link to NEW Chart]](Resources/5_scores_by_school_spending.PNG)
  - There is no change to this chart.
- **Scores by School Size**
  - Performance by student population: [[Link to NEW Chart]](Resources/6_scores_by_school_size.PNG)
  - There is no change to this chart.
- **Scores by School Type**
  - Performance by school type (charter or district): [[Link to NEW Chart]](Resources/7_scores_by_school_type.PNG)
  - There is no change to this chart.

# Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
