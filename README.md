# School_District_Analysis

## Analysis Overview
* define the purpose of this analysis

## Resources
* Data source: students_complete.csv, schools_complete.csv
* Software: Python 3.9.12, Jupyter Notebook 3.1

## Results
### After comparing the revised data against the original we find:
* how is the district summary is affected… not affected, only 461 out of 39170 grades affected, or .011%... district_summary_df

* how is the school summary affected…. 461 out of 1635 or 28.1%, however, nan’s aren’t taken into account in summary data… school_summary_df

* how does replacing the 9th grade math and reading scores affect Thomas High's school performance relative to the other schools. Does not…top_schools

* how does replacing the 9th grade scores affect
1. math and reading scores by grade… only affects 9th grade grade_summary_math/reading
2. scores by school spending… because scores were barely affected, it did not affect the scores based on school spending break down….per_school_spending
3. scores by school size… we know that there are 1635 students so Thomas is considered a medium school, score were not affected …. Size_summary
4. scores by school type… we also know that Thomas is a charter school… not affected… school_type


## Summary
* summarized 4 changes in the updated school district analysis after the scores were updated
