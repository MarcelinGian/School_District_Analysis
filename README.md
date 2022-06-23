# School_District_Analysis
### Overview of the school district analysis:
##### The School Board believes there is evidence of academic dishonesty in the reading & math grades reported for Thomas High School ninth-graders. This analysis removes these scores while keeping the rest of the data intact. 

##### This report uncludes updates to the School Summary, Top & Bottom Performing schools (sorted by percentage of students passing Math and Reading), grade-by-grade Math & Reading scores (sorted to respective High Schools), Scores sorted by a range of Schools' Per-Student Budget, Scores by School Size, and finally- Scores by Type of School(District vs Charter).

### Results: 
- How is the district summary affected?
  - THere was very little change to the district summary as a whole. No more that 2 tenths of a decimal in either direction for average scores and percent passing.
- How is the school summary affected?
  - Thomas High School's percent passing for Math, Reading and Overall increases dramatically- by over 20 points for each if those indices.
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - This updated data makes Thomas high school one top performing schools in the district based on percentage of studenst passing.
- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
    - There is no change in the Math & Reading scores by grade DataFrames when 9th grade scores are zeroed out, other than that 'NAN' value
  - Scores by school spending
    - For the spending range bin containing Thomas HS, Average Math score decreases slightly while Average Reading increases slightly. % Passing Math, Reading, & Overall all decrease slightly.
  - Scores by school size
    - For the school size bin containing Thomas HS, % Overall Passing decreases from 90.62% to 90.56%
  - Scores by school type
    - For the charter school-type bin that contains Thomas HS, there is no change in numerical values when rounded down to a tenth decimal place.

### Summary:
##### Four changes can be observed in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
- A substantial increase in Thomas High School's percent passing for Math, Reading and Overall passing can be observed in the School Summary DataFrame.
- For the spending range bin containing Thomas HS, Average Math score decreases slightly while Average Reading increases slightly. 
- For the spending range bin containing Thomas HS, % Passing Math, Reading, & Overall all decrease slightly.
- For the school size bin containing Thomas HS, % Overall Passing decreases from 90.62% to 90.56%
