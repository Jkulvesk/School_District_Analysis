# School District Analysis

## Overview of the school district analysis
This analysis helps prepare the school board for making important decisions about school funding. The initial analysis included math, reading and overall scores by spending per student, by school type and by size of school. The analysis had to be updated to remove Thomas HS 9th grader reading and math scores because there was evidence of acedemic dishonesty which skewed the overall results.

## Results
- **Impact of removing Thomas Hight School(THS) 9th grade scores on District Summary:**
  - Taking out the scores of the THS 9th grade students did not have much of an impact on the overall summary. It resuced the overall score by a tenth of a percent - from 65% overall passing percent to 64.9%. Removing the scores of the 9th grad at THS just removed 461 students from the overall analysis, which was around 1% of the total district population. 
  
    District summary with data as-is:
    [Screenshots](https://user-images.githubusercontent.com/72076683/97115435-b6ba5d00-16c4-11eb-9c8f-eb1250445c39.png)
    District summary with 9th grade Thomas High School data removed:
    [Screenshots](https://user-images.githubusercontent.com/72076683/97115456-d487c200-16c4-11eb-8c92-36f7bcb52fe0.png)
  
- Impact of removing THS 9th grade scores on School Summary:
  - Removing Thomas HS only impacted the score of Thomas HS. Removing 9th grade brought the HS scores down slightly for the highschool. The grades after were 93.18% passing math, 97.01% passing reading and 90.63% passing overall compared to 93.27% passing reading, 97.3% passing math and 90.9% passing overall. 
  
- THS performance impact when removing 9th grade scores:
  - The adjustment of removing 9th grade scores for Thomas Highschool did not impact the schools acedemic ranking - #2 highest overall passing score.
  
- Replacing 9th grade scores affects:
  -Math and reading scores by grade declined when replacing 9th grade scores by NaN. The grades after were 93.18% passing math, 97.01% passing reading and 90.63% passing overall compared to 93.27% passing reading, 97.3% passing math and 90.9% passing overall. 
  -Scores by school spending were not impacted.      
  -Scores by school size were not impacted
  -Scores by school type were not impacted.

## Summary
Replacing Thomas High School's reading and math scores with NaNs impacted the analysis by:
- It reduced the number of overall datapoints in the analysis by 461. If the 9th grade at this highschool was a lot larger, this could have had a more significant impact.
- It reduced the high school's passing reading percentage.
- It reduced the high school's passing math percentage.
- It resuced the high school's overall passing percentage, but not enough to impact the school's rank. 
