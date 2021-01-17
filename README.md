# School_District_Analysis
## Overview 
Maria initially asked us to run an analysis on reading and math exam scores acorss various high schools in a school district to uncover any trends and decide how to allocate their budget for the following year. However, it was discovered that there was academic dishonesty and the reading and math scores for ninth graders at Thomas High School had been altered. Because of this, we had to erase Thomas High School's scores for reading and math and re-run the analysis.

## Results

- How is the district summary affected?: The percentages of students who passed math, reading, and both went slightly down, less than 1% per category. The average scores, however, stayed relatively the same. The math score average went down .1 points while the reading remained the same.<br/><br/>
District Summary Before<br/>
![District Summary Before](https://github.com/cailynjmiller/School_District_Analysis/blob/main/Resources/district%20summary%20OLD.png)<br/><br/>
District Summary After<br/>
![Distrit Summary After](https://github.com/cailynjmiller/School_District_Analysis/blob/main/Resources/district%20summary%20NEW.png)<br/><br/>
- How is the school summary affected?: To adjust for getting rid of all of the 9th grade scores, we adjusted the caulculations for Thomas High School to only include 10th-12th grade for the average math and reading scores, as well as passing percentages for each category. All of these numbers stayed relatively the same, only fluctuating less than 1 percentage point per category.<br/><br/>
School Summary Before<br/>
![School Summary Before](https://github.com/cailynjmiller/School_District_Analysis/blob/main/Resources/school%20summary%20OLD.png)<br/><br/>
School Summary After<br/>
![School Summary After](https://github.com/cailynjmiller/School_District_Analysis/blob/main/Resources/School%20Summary%20NEW.png)<br/><br/>
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools: Replacing the math and reading scores for ninth graders at Thomas High School did not affect their performance relative to other high schools at all. Thomas High School still sits as the second best school for overall passing rates for math and reading exams.<br/><br/>
Top 5 Schools Before<br/>
![Top 5 Schools Before](https://github.com/cailynjmiller/School_District_Analysis/blob/main/Resources/top%20schools%20OLD.png)<br/><br/>
Top 5 Schools After<br/>
![Top 5 Schools After](https://github.com/cailynjmiller/School_District_Analysis/blob/main/Resources/Top%20Schools%20NEW.png)<br/><br/>
- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade: It does not affect any of the average math and reading scores by grade, except for the ninth grade at Thomas High School where it is marked as "NaN" since all of the scores have been removed. This is because changing the ninth grade scores to Nan does not impact any of the scores for the other grades at Thomas High School or the grades at any other schools.<br/><br/>
Math Score Summary Before<br/><br/>
![Math Score Summary Before](https://github.com/cailynjmiller/School_District_Analysis/blob/main/Resources/math%20scores%20OLD.png)<br/><br/>
Math Score Summary After<br/>
![Math Score Summary After](https://github.com/cailynjmiller/School_District_Analysis/blob/main/Resources/math%20scores%20NEW.png)<br/><br/>
Reading Score Summary Before<br/>
![Reading Score Summary Before](https://github.com/cailynjmiller/School_District_Analysis/blob/main/Resources/reading%20scores%20OLD.png)<br/><br/>
Reading Score Summary After<br/>
![Reading Score Summary After](https://github.com/cailynjmiller/School_District_Analysis/blob/main/Resources/reading%20scores%20NEW.png)<br/><br/>
   - Scores by school spending: It does not affect any of the scores by spending for any cateogory except for the $630-644/student bin, where Thomas High School sits. In this bin, the average scores and percentage passing changes so minimally that when the data is formatted to only one decimal points, there appears to be no changes at all.<br/><br/>
Scores by Spending Before<br/>
![Scores by Spending Before](https://github.com/cailynjmiller/School_District_Analysis/blob/main/Resources/spending%20bin%20OLD.png)<br/><br/>
Scores by Spending After<br/>
![Scores by Spending After](https://github.com/cailynjmiller/School_District_Analysis/blob/main/Resources/Spending%20Bin%20New.png)<br/><br/>
  - Scores by school size: It does not affect any of the scores by spending for any cateogory except for the Medium Size school bin (1000-2000), where Thomas High School sits. In this bin, the average scores and percentage passing changes so minimally that when the data is formatted to only one decimal points, there appears to be no changes at all.<br/><br/>
Scores by Size Before<br/>
![Scores by Size Before](https://github.com/cailynjmiller/School_District_Analysis/blob/main/Resources/size%20bin%20OLD.png)<br/><br/>
Scores by Size After<br/>
![Scores by Size After](https://github.com/cailynjmiller/School_District_Analysis/blob/main/Resources/size%20bin%20NEW.png)<br/><br/>
  - Scores by school type: It only affects the Charter School cateogry, where Thomas High School sits. In this bin, the average scores and percentage passing changes so minimally that when the data is formatted to only one decimal points, there appears to be no changes at all.<br/><br/>
Scores by Type Before<br/>
![Scores by Type Before](https://github.com/cailynjmiller/School_District_Analysis/blob/main/Resources/school%20type%20OLD.png)<br/><br/>
Scores by Type After<br/>
![Scores by Type After](https://github.com/cailynjmiller/School_District_Analysis/blob/main/Resources/school%20type%20NEW.png)<br/><br/>

## Summary
- One major change to the analysis was the number of students being analyzed. The number of students in the analysis went down around 400 students (~39100 to ~38700). However, I did not changes the student count in any of the analyses.
- Another major change is the amount of null values in the dataset, there were no null values in the original data. Having lots of null values can lead to an inaccurate analysis, however, this does not appear to be the case here because many parts of the analysis remained unchanged.
- Another change of this analysis is that Thomas High School performed worse in average math and reading scores and passsing rates. However, this did not change the fact that Thomas High School sits in the second spot for the highest overall passing rates.
- The final change was that, when comparing 3 different categories for schools, spending per student, type, and size, the bins that Thomas High School is in changed so the averages were slightly lower, but not enough to affect their placement in comparison to the other bins.
