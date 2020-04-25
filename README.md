# School_District_Analysis


## Challenge Overview
A Py School District employee has given me the following tasks to evaluated an analyze based on the recently collect school and student data that was provided to understand the impact on the District and School analsysi after the Thompas High School 9th grade math and reading grades are removed from the analysis.

1) How is the district summary affected?
2) How is the school summary affected?
3) How does removing the ninth graders’ math and reading scores affect Thomas High School’s
performance, relative to the other schools?
4) How does removing the ninth grade scores affect the following?
    - Math and Reading Scores by Grade
    - Scores by School Spending
    - Scores by School Size
    - Scores by School Type

## Resources
- Data Source:  schools_complete.csv, students_complete.csv
- Software:  Python 3.7.7, Jupyter Notebook 6.0.3

## Challenge Summary
The analysis of the student and school data shows the following impact from removing the Thomas High School's 9th grade class math and reading grades:

Score impact measured by taking uncorrected scores without the Thomas High School grades removed and subtracting the corrected scores.  For example the District Average Math Score before the correction was 79.0% and after was 78.9%.  Therefore the District Average Math score was 0.1% lower after the change or -0.1%.

- District Summary: 
    - Average Math Score: - 0.1%
    - Average Reading Score: Unchanged
    - % Passing Math: - 1%
    - % Passing Reading: - 1%
    - % Ovarall Passing: - 1%

- School Summary:
    - 

- Thomas High School performance relative to other schools:
    - Thomas HS was ranked as #2 in the top performing schools; however, after the correction they fell #8.

- 9th grade scores:
    - Math score:  was 83.6% now NaN
    - Reading score: was 83.7% now NaN

- Scores by School Spending
    - In the $630-644 Spending Range (all other ranged were unimpacted):
        - % Passing Math:  -6%
        - % Passing Reading:  -7%
        - % Overall Passing:  -7%

- Scores by School Size
    -  In the Medium (1000-2000) student count range (all other ranges were unimpacted):
        - % Passing Math:  -6%
        - % Passing Reading:  -6%
        - % Overall Passing:  -6%       

- Scores by School Type
    -In the Charter School type (District was unimpacted):
        - % Passing Math:  -4%
        - % Passing Reading:  -4%
        - % Overall Passing:  -3%              
