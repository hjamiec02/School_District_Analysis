# School_District_Analysis
## Overview of the School District Analysis
An intial anaylsis was performed on a school district's standardized test scores, as well as the school's funding. The test scores were used in a variety of models to compare the how the schools performed across grade level, based on school's budget, size of the school and type of school (charter or district).  Once the initial analysis was complete, the school board discovered Thomas High school ninth grade test scores had be altered, resulting in the removale of math and reading scores and the analysis had to be repeated after the removal of the altered scores. 
## Results
After performing the anaylsis the second time, the overall results changed only a small amount.  This was to be expected, as there were only a small number of ninth grader's from Thomas High school compared to the overall number of students in the dataset. Below is a comparison of how the dataset looked from the initial analysis to the updated anaylsis:
  - District summary did not change at all.
  <img width="992" alt="Screen Shot 2022-06-05 at 1 29 42 PM" src="https://user-images.githubusercontent.com/105119531/172062944-2ee0035c-ed0f-449d-a254-307e80a5b61a.png">

  - School Summary - Very little change in the % Overall Passing category, as seen below.
  
  Intial analysis
  <img width="1022" alt="Screen Shot 2022-06-05 at 1 32 10 PM" src="https://user-images.githubusercontent.com/105119531/172062952-4131748b-2cf6-49fd-93df-471fcbf5b616.png">

  Updated analyis
  <img width="1010" alt="Screen Shot 2022-06-05 at 1 31 39 PM" src="https://user-images.githubusercontent.com/105119531/172062953-e788666b-b9c2-4498-b339-783d566ea435.png">
 
  - Replacing the scores for Thomas High school ninth grader's had very little affect, as Thomas High School remained in the top 5 performing schools in second place.

  Intial analysis
  <img width="1023" alt="Screen Shot 2022-06-05 at 1 49 07 PM" src="https://user-images.githubusercontent.com/105119531/172063680-cbcd1932-7029-4634-95f2-a66db2ff809c.png">

  Updated analysis
<img width="1026" alt="Screen Shot 2022-06-05 at 1 49 43 PM" src="https://user-images.githubusercontent.com/105119531/172063683-9135c7ad-a95a-4c8e-b9c2-c7137d77f42f.png">

  - Replacing the math and reading scores by grade had no significant affect due the the Thomas High School ninth grades scores being replaced with NaN.
  
  - Score by School Spending did not change at all. 

  - Score by School Size did not change at all.

  - Score by School Type did not change at all.

## Summary
Four changes that can be noted after the updated analysis:
- The total number of students at Thomas High School
- The total number of students in the district
- The school summary % Overall Passing
- The addition of NaN for the 9th graders at Thomas High School

Due to the fact that the total number of students in the district changed relative to the total number of students at Thomas High school, there was very little affect on the % Overall Passing for the district with the addition of the NaNs.
