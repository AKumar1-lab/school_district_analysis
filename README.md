## School District Analysis
Module 4: PyCitySchools 
## Objective: 
Use Python and the Pandas Library to analyze school district data and showcase trends in school performance.
## Resources: 
Data Source:  PyCitySchools.ipynb; PyCitySchools_Challenge.ipynb; schools_complete.csv; students_complete.csv

Software: Anaconda 3.8.8, Python, Pandas Library, Jupyter Notebook
## Background: 
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards.
## Overview of the project:
## Deliverable 1: Replace Ninth-Grade Reading and Math Scores

Using the Pandas loc method with conditional statements and comparison and logical operators, select the ninth grade reading and math scores for Thomas High School. Then, use the Pandas NumPy module to change the reading and math scores to NaN.

<img width="435" alt="Deliverable 1 THS 9th Grade" src="https://user-images.githubusercontent.com/85860367/126257104-e94282a2-6704-4821-9e77-7d27ae9d6db8.png">

## Deliverable 2: Repeat the school district analysis
Reformating the following after the 9th grade students from Thomas High School are removed or replaced by NaN._ 

### The District Summary
<img width="617" alt="District Summary" src="https://user-images.githubusercontent.com/85860367/126254681-0b3cb8b3-0cf4-41bd-86d5-3d00637a1db2.png">

**How is the district summary affected?** 
The district is impacted with little or no impact as far as the average scores at the district level. 
We had removed **461** 9th graders from Thomas high school from the original count of **39,170 students** which reduced the number of students to **38,709 students** that had tested in both subjects. 
The average reading score for all schools stayed at **79.0**; The average math score for all schools stayed at **81.9**;
The variance in % Passing Math was **0.2%**; The variance in % Passing Reading was **0.1%**; and the variance in % Overall Passing was **0.3%** at the district level.
At the individual school level the story was different.
### The School Summary

<img width="617" alt="Before School Summary tail" src="https://user-images.githubusercontent.com/85860367/126258433-885e11bf-09e9-4290-8768-def8cf61e791.PNG">

<img width="617" alt="School Summary after Reformat" src="https://user-images.githubusercontent.com/85860367/126258809-0f107277-fc92-4b6b-b41b-4eef1299ef96.png">

**How is the school summary affected?**  Thomas High School was originally in 13th place; and once the reformating occurred; they had moved to 2nd place.  The number of students was **reduced from 1,635 to 1,174** since we removed 461 Thomas High School 9th graders from the profile. 
The amounts for % Passing Math changed from 93.27% to 93.18%, this means that 1,094 students passed math at Thomas High School. 
The amount for % Passing Reading changed from 97.30% to 97.02%, this means that 1,139 student passed reading at Thomas High School. 
The amount for % Overall Passing changed from 90.94% to 90.63%, this means that 1,064 students overall passed math and reading at Thomas High School.  

### The top 5 and bottom 5 performing schools, based on the overall passing rate.
   ### Before
   
<img width="617" alt="Capture top and bottom schools before" src="https://user-images.githubusercontent.com/85860367/126271467-4c82117e-8821-4254-93d1-e6d78699be53.PNG">
   ### After
   
<img width="617" alt="Capture top and bottom schools after" src="https://user-images.githubusercontent.com/85860367/126271549-24b96426-b630-475f-b3d8-c5aeec458a36.PNG">

The average math score for each grade level from each school

<img width="480" alt="Before and After Math Scores" src="https://user-images.githubusercontent.com/85860367/126272190-b9996a59-9bb7-4725-ac3a-40b92eb3f308.png">

The average reading score for each grade level from each school
<img width="480" alt="Before and After Reading Score" src="https://user-images.githubusercontent.com/85860367/126272963-e40051f7-15f7-4755-a979-fd4d8836ddcd.png">

The scores by school spending per student, by school size, and by school type

<img width="617" alt="Before spending range" src="https://user-images.githubusercontent.com/85860367/126273970-13ccc92e-34bd-425a-8e4d-5b1477cc9eb1.PNG">

<img width="617" alt="Capture school range after" src="https://user-images.githubusercontent.com/85860367/126273789-17217826-3b53-465e-89de-d475e5bdceca.PNG">

### Size
<img width="544" alt="After Spending" src="https://user-images.githubusercontent.com/85860367/126274100-cffdaa93-3cae-4577-bbbc-1ce0e5d5830b.PNG">

**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**
Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
How does replacing the ninth-grade scores affect the following:

**Math and reading scores by grade:**  
The math and reading scores for all 9th graders at Thomas High School's affected the performance.  The scores were "Nan" or Null and were dropped from their profile.  This affected 461 9th grade students, it also reduced the number of student that passed from 1,635 to 1,174.  The % changes in Passing Math, Passing Reading and Overall Passing were very minimal for the school.  There was no impact to the other schools.

**Scores by school spending:**  
The school spending appeared to be the same when the script was processed; it appears that there was only 0.3% change in the % Overall Passing from 90.94% to 90.63%  It still appears that it is still within the $630-$644 range.

**Scores by school size:**
![image](https://user-images.githubusercontent.com/85860367/126277493-bd63d7c7-5db8-46d4-b099-598e367c4833.png)
Thomas High School was in the range of 1,174 to 1,635 students, it is still within the Medium range in Size. The % Overall Passing is equal to 91% and Thomas High School is relatively close to meeting all criterias for the school size range.

**Scores by school type:**
Thomas High School is a mid-range Charter School. In this criteria there were very minimal changes in the results and the Math, Reading and Overall Passing is still within range.  

In summary, If we were to change the number from 1,635 to 1,174, and the budgetted amount remained constant at $1,043,130, this results in $888.52/per student and may be overstating which would cause more scrutiny and audit.  This would also change the portfolio and Thomas HS will be at the top and scores may be at or below the average. At the moment Thomas High School is perfectly aligned with Cabrera HS and Griffin HS, Shelton and Wilson High Schools in student size, school type and scores.  

