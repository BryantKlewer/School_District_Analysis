# School_District_Analysis

## Project Overview
* The purpose of this project is to clean potential fraudulent data for a local school board which previously had an analysis of 15 high schools in their district completed. To begin, all Math and Reading scores need to be omitted from all 9th graders at Thomas High School and their values in the data frame replaced with "NaN" values. Next, the previous analysis will be rerun and the findings of the new analysis summarized in comparison to the former analysis. The data being analyzed includes school name, size, type, budget, student data, test scores for math and reading, and pass/fail percentages.  

## Resources
* Data source: students_complete.csv, schools_complete.csv
* Software: Python 3.9.12, Jupyter Notebook 3.1

## Results
### After comparing the revised analysis against the original, we find:
___Note: in all screen shots below, the left output is the original analysis and the right output is the revised analysis___
* The district summary as a whole was only minimally affected. Once all nineth grade math and reading scores for Thomas High School were removed and replaced with "NaN" values, 461 out of 39170 students are affected, or .011%. The revised district finding are not statistically significant. ___district_summary_df___

* We find that school summary for Thomas High School is only minimally affected even though 461 out of 1635, or 28.1%, of students in this summary are affected. This is due to the fact that NaN values aren’t taken into account in the mathematical equations. ___school_summary_df___

* Replacing the 9th grade math and reading scores, again, does not affect Thomas High's school performance relative to the other schools. Thomas High School remains in the same second place position relative to all 15 schools when measured by percentage of students with an overall passing grade in both math and reading. ___top_schools___

* How does replacing the Thomas High School 9th grade scores affect:
1. Math and reading scores: Math and reading scores by grade are only affected for 9th grade because Thomas High School does not have any applicable scores. ___summary_math and reading___
2. Scores by school spending: because scores were only minimally affected, there was no statistically significant difference in the scores based on school spending summary. ___per_school_spending___
3. Scores by school size: We know that there are 1635 students that attend Thomas High School, therefore, it is considered a medium sized school. Scores were not affected and there was no difference in output in the measurable metrics based on school size. ___Size_summary___
4. Scores by school type: We additionally know that Thomas High School is a charter school. In the summary based on school type, there was no change in output between the original annalysis and the revised annalysis. ___school_type___


## Summary
* To summarize the findings, there are four changes to note in the updated school district analysis when compared to the original after updating all of Thomas High Schools' 9th grade math and reading scores with NaN's. 
1. All average 9th grade math scores for Thomas High School in the per grade summary are not applicable in the revised analysis. Therefore, no 9th grade performance can be measured.
2. The same is true for average reading scores for 9th graders attending Thomas High School. There are no measurable metrics for these students.
3. In the district summary data frame, the average math score as well as passing percentages for both math and reading are slightly lower in the revised analysis when compared to the original. This does indicate that there may have been possible cheating which netted higher passing grades and therefore higher passing percentages at Thomas High School in the original analysis. There is no change noted in the average reading score in the revised analysis.
4. In the school summary data frame the average math score, percent of students with passing math scores, percent of students with passing reading scores, and overall percent of students passing are all slightly lower in the revised analysis. However, the average reading score is slightly higher in the revised analysis after removing the 9th grade student scores at Thomas High School.
