# School District Analysis

## Overview of the school district analysis
Maria was asked to run an analysis on the school district's performance in math and reading. While completing the analysis, the school board told Maria that there is evidence that students from Thomas High School committed academic dishonesty. Maria asked for help removing the scores of the 9th grade students from Thomas High School. After removing these scores from the data set, the school board would like to run the analysis once more to determine the affects of these changes.

##Results
###District Summary
The district summary was slgihtly changed after the students from Thomas High School were removed. The average math score decreased by .1 and the reading scores remained the same. The percentage of students who passed math and reading also decreased. The percent of student passing reading decreased by .3 percentage points and the percent of students passing math decreased by .2 percentage points. The overall percentage of students who passed math and reading decreased by .1 percentage points.

###School Summary
Most of the results from the school summary remained the same after we removed the flagged test scores. The school with the only observed change in the school summary results is Thomas High School.

###Thomas High School's Performance
The percentage of students who passed math and reading from Thomas High School decreased drastically when we removed the flagged test scores. The percentage of students who are passing math and reading from Thomas High School was originally 91 percent. That percentage dropped down to 65 percent after we removed the 9th grade scores. Thomas High was ranked as one of the top five schools in our initial analysis, however, they dropped in their ranking when we removed the flagged scores. 

###Math and Reading Scores by Grade
When reviewing the results by grade, we see that the test scores for the 9th graders at Thomas High School have been changed to NaN values. These results indicate that we successfully changed the test scores for the students who were flagged by the school board.

###Scores by School Spending
The percentage of passing grades changed for the range of spending that includes Thomas High School, $631-645.

###Scores by School Size
Similarly, we see that the percentage of passing grades also decreased for the medium group, which is where Thomas High School is as well.

###Scores by School Type
Thomas High School is categorized as a charter school. This means that the Charter results were changed when we removed the test scores from the database. We can see that the math, reading, and overall percent of Charter students who are passing have each decreased by three percentage points.

##Summary
There are four main changes that are important to note when presenting the results to Maria and the school board. First, we can see that the changes have a slight affect on the school district analysis. These changes are less than 1 percent so it shouldn't affect their initial analysis and any broader decisions about the school district in general. 

Secondly, Thomas High School lost their position as one of the top five schools within the district. Although they are not one of the five lowest ranked schools, the removal of the flagged test scores drastically decreased Thomas High's overall passing percentage.

Next, we can see the changed test scores by looking at the results of each school by grade level. When running this analysis, we can see that the 9th grade test scores from Thomas High School have been replaced with the value NaN. This demonstrates that we accurately removed the data for these students.

Lastly, we can rerun our analysis to compare the test scores by the amount of money spent per student, the size of the school, and the type of school to see how the change impacted these results. When running this analysis, we can see that the average math and reading scores have not changed. The percent of students who are passing math, reading, and both have decreased depending on the group that includes Thomas High School. The only schools that were affected by this change were those who were grouped in the same bucket as Thomas High.
