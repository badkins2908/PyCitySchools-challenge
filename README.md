# PyCitySchools-challenge

## Project Overview
This project was to use Jupyter Notebook to carry out Pandas analysis via Python coding on fake school district data. The first analysis looked at overall reading and math scores across all schools, without altering any scores information. In order to determine if possible adacemic dishonesty was taking place, a second analysis was conducted after replacing all 9th grader math and reading scores at Thomas High School. This second analysis was then compared to the first analysis, to determine the impact of removing the scores and the level of possible academic dishonesty.

This project introduced how to utilize Jupyter Notebook to carry out pandas analysis on various dataframes created from original datasets imported via CSV files.

Process carried out:
1. Analyze school and student data as is.
2. Conduct analysis on school and student data again, after removing all 9th grader scores from Thomas High School.
3. Determine if removing the 9th graders scores made a significant difference in the final school district summary. 
4. Conclude whether scores should be altered or kept as is.

## Resources
- Original Analysis: PyCitySchools.ipynb
- Altered Scores Analysis: PyCitySchools_Challenge.ipynb
- Original Datsets: schools_complete.csv, students_complete.csv

## Results
Overall, there wasn't much change between the two analsyes. Since only 9th graders information for Thomas High School was altered, there is only a difference in overall scores for THS and 9th graders overall. 

Looking at results from the first analysis vs second analysis, which can be found by looking at the output from the code in Resources Folder:
|            | First Analysis (data not altered) | Second Analysis (data altered) |
| ------------ | ------------ | ------------- |
|District's Avg Math Score | 79.0 | 78.9 |
|District's Avg Reading Score | 81.9 | 81.9 |
|District's Overall Passing | 65.2% | 64.1% |
|Charter School Avg Math Score| 83.5 | 83.5 |
|Charter School Avg Reading Score| 83.9 | 93.9 |
|Charter School Overall Passing | 90% | 90% |
|Thomas High's Avg Math Score | 83.41 | 83.35 |
|Thomas High's Avg Reading Score | 83.84 | 83.89 |
|Thomas High's Overall Passing | 90.94% | 90.63% |
|Thomas High's Overall Passing Ranking | 2nd | 2nd |
|Avg 9th Grade Math Score | 80.35 | 80.12 |
|Avg 9th Grade Reading Score | 82.51 | 82.42 |

After removing the scores for the 9th graders at Thomas High School, the District's scores and overall passing percentage decreased, but not by a significantly amount. When looking at the school types within the District, Thomas High School is considered a Charter School. There was no effect on the overall Charter Schools scores and overall passing percentage. There was a decrease in Thomas High School's scores and overall passing percentage by a non-significant amount. And lastly, the average scores for 9th grades decreased by a minimal amount.

It is important to note, that while removing the 9th grader math and reading scores at Thomas High School did decrease scores at the district, school, and grade specific level - implying that the scores for 9th graders at Thomas High could have been inflated - these decreases where no where near significant enough to confirm any implications of inflation of scores. 

## Summary
In conclusion, there doesn't seem to be any academic dishonesty happening within the 9th graders at Thomas High School since removing the 9th graders reading and math scores did not drastically change the district, school, or grade specific scores and overall passing percentages. Therefore, it is recommended leave Thomas High's 9th grader scores in the analysis to show the District's testing score summaries in their entirety.
