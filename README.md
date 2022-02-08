# School_District_Analysis

# Overview 
In light of possoble grade tampering at Thomas High School, a new analysis has been requested. It was asked that we remove the 9th grade math and reading scores and rerun the analysis to acess the difference in student performance.

 -How is the district summary affected?

 -How is the school summary affected?

 -How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

 -How does replacing the ninth-grade scores affect the following:
  -Math and reading scores by grade
  -Scores by school spending
  -Scores by school size
  -Scores by school type

## Resources
 -Data Source: schools_complete.csv
 -Data Source: students_complete.csv
 -Sofware: Jupyter Notebook 6.4.5
 -Library: Pandas
 -Library: Numpy
 -Language: Python 3.10.1

## Results: 

 After the nullifiction of the 9th grade scores, the district summary remained relatively unchanged. Since the 9th grade population at Thomas High School is under 500 students, and the district population is almost 40,000, removal of the grades is rather insignificant to that data. 

 Replacing the 9th grade scores with NaN dropped the schools overall passing percentage down significantly from 90% to 65%.

 Even though the overall percentage dropped for Thomas High, after removing the 9th grade from the data frame, Thomas High remains second in the district.

  After removing Thomas's 9th grade scores we see that:
    -The math and reading scores by grade are unaffected with the exception of Thomas high.
    -We can also that the schools with the least budget per student have some of the highest overall passing scores. While the schools with the highest budget per student have the lowest overall passing scores in the district.
    -The large schools had the worst overall score, while the small and medium schools had similar overall passing scores.
    -The charter schools have a 90% overall passing rate and the district schools have a 54% overall passing rate.


## Summary:
 
  -District Analysis - There was little to no impact on the district summary after the removal of grades.

  -Top School Ranking - Although Thomas High School scores did change, there was no change to the top school rankings.

  -Scores by School Size -the smaller schools have better paasing scores than the larger schools.
  
  -Scores by School Type - the charter schools are out performing the district  schools.