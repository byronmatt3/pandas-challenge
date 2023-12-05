School District Analysis Report
This report analyzes school district data using Pandas and Jupyter Notebook. The analysis covers various metrics, including district summary, school summary, highest-performing and lowest-performing schools, average scores by grade, scores by school spending, scores by school size, and scores by school type.

District Summary
The district summary provides a high-level snapshot of key metrics for the entire school district. The metrics include:

Total number of unique schools
Total students
Total budget
Average math score
Average reading score
% passing math
% passing reading
% overall passing
School Summary
The school summary breaks down key metrics for each individual school. The metrics include:

School name
School type
Total students
Total school budget
Per student budget
Average math score
Average reading score
% passing math
% passing reading
% overall passing
Highest-Performing and Lowest-Performing Schools
The analysis identifies the top 5 highest-performing schools and the bottom 5 lowest-performing schools based on % overall passing.

Top Schools: Displayed in descending order of % overall passing.
Bottom Schools: Displayed in ascending order of % overall passing.
Math and Reading Scores by Grade
The analysis provides average math and reading scores for students in each grade level (9th, 10th, 11th, 12th) at each school.

Scores by School Spending
The analysis categorizes schools into spending ranges per student and calculates mean scores for each range. The spending ranges and metrics include:

Spending Ranges (Per Student):
<$585
$585-630
$630-645
$645-680
Metrics:
Average math score
Average reading score
% passing math
% passing reading
% overall passing
Scores by School Size
The analysis categorizes schools into size ranges and breaks down school performance based on size (small, medium, or large). The size ranges and metrics include:

Size Ranges:
Small (<1000)
Medium (1000-2000)
Large (2000-5000)
Metrics:
Average math score
Average reading score
% passing math
% passing reading
% overall passing
Scores by School Type
The analysis creates a DataFrame showing school performance based on school type. The metrics include:

Metrics:
Average math score
Average reading score
% passing math
% passing reading
% overall passing
Observations
Size Impact on Performance:

Smaller and medium-sized schools tend to have higher overall passing percentages compared to larger schools.
Type Influence:

Charter schools generally outperform district schools in both math and reading scores as well as overall passing percentages.
