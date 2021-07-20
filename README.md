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
**Before**
<img width="617" alt="Capture top and bottom schools before" src="https://user-images.githubusercontent.com/85860367/126268884-dc82b714-8fb3-4ae3-9066-f58ad7a4fc3e.PNG">

 **After**
<img width="617" alt="Capture top and bottom schools after" src="https://user-images.githubusercontent.com/85860367/126269197-4fdda38e-8c7a-441c-ac56-495f0e4dc427.PNG">

The average math score for each grade level from each school


The average reading score for each grade level from each school

 
The scores by school spending per student, by school size, and by school type
 

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

How does replacing the ninth-grade scores affect the following:

Math and reading scores by grade:

Scores by school spending:

Scores by school size:

Scores by school type:

Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
