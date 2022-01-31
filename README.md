# School_District_Analysis
Analyzing student funding and student standardized test scores to finds trends in school performance using Python and Jupyter Notebook

## Overview of the School District Analysis:
Maria, the Chief Data Scientist for a school district needs assistance analyzing student funding and students standardized test scores. We are tasked to aggreagate the data and showcase trends in school performance. This analysis will aid the school board and superintendant regarding the school budget and priorities. Upon completing the orginal analysis, it has come to the schoolboards attention that the grades in the csv file for ninth grade students at Thomas High School appears to have been altered. Although, the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and Maria has requested that the grades for ninth graders at Thomas High School be replaced with "NaNs," while keeping the rest of the data intact. Once the math and reading scores have been replaced, Maria would like you to repeat the school district analysis and write up a report to describe how these changes affected the overall analysis.

## Results
The subsequent paragraphs will compare and contrast the initial results of the analyis against the new results which accounting for the academic dishonesty associated with ninth graders math and reading grades at Thomas High School.

### District Summary
District Summary - Original
![image_name](https://github.com/Mugunthan24/School_District_Analysis/blob/main/Resources/District_Summary_Original.PNG)

District Summary - Revised 
![image_name](https://github.com/Mugunthan24/School_District_Analysis/blob/main/Resources/District_Summary_Revised.PNG)

- The only noteable change is the Total Students which has decreased after removing our hundred and sixty one rows of data for ninth grade students attending Thomas High School


### School Summary
School Summary - Orginal
![image_name](https://github.com/Mugunthan24/School_District_Analysis/blob/main/Resources/School_Summary_Original.PNG)

School Summary - Revised
![image_name](https://github.com/Mugunthan24/School_District_Analysis/blob/main/Resources/School_Summary_Revised.PNG)

- The only differences between the 2 tables can be found when looking at the row for Thomas High School. Specifically the differences can be found in the columns below:
    - Average Math Score
        - Has decreased slightly from 83.42 to 83.35
    - Average Reading Score
        - Has increased slightly from 83.85 to 83.9
    - % Passing Math
        - Has decreased slightly from 93.27% to 93.19%
    - % Passing Reading
        - Has decreased slightly from 97.31% to 97.02%
    - % Overeall Passing
        - Has decreased slightly from 90.95% to 90.63%

### Thomas High School’s performance Relative to other Schools
Top Schools - Original
![image_name](https://github.com/Mugunthan24/School_District_Analysis/blob/main/Resources/Top_Schools_Original.PNG)

Top Schools - Revised
![image_name](https://github.com/Mugunthan24/School_District_Analysis/blob/main/Resources/Top_Schools_Revised.PNG)

- Thomas High School still ranks second place in terms of its % Overall Passing despite % Passing Math, % Passing Reading, % Overall Passing falling from 90.95% to 90.63%

### Math Scores by Grade
Math Scores - Original

![image_name](https://github.com/Mugunthan24/School_District_Analysis/blob/main/Resources/Math_Scores_Original.PNG)

Math Scores - Revised

![image_name](https://github.com/Mugunthan24/School_District_Analysis/blob/main/Resources/Math_Scores_Revised.PNG)

Reading Scores - Original

![image_name](https://github.com/Mugunthan24/School_District_Analysis/blob/main/Resources/Reading_Scores_Original.PNG)

Reading Scores - Revised

![image_name](https://github.com/Mugunthan24/School_District_Analysis/blob/main/Resources/Reading_Scores_Revised.PNG)

- The information between both tables is exactly the same, but since we have gotten rid of the grade information for ninth graders at Thomas High School, the 9th grade information for Thomas High School will be blank for Math and Reading Scores per Grade.

### Scores by School spending

Spending Ranges per Student - Original
![image_name](https://github.com/Mugunthan24/School_District_Analysis/blob/main/Resources/Spending%20Ranges%20per%20Student_Original.PNG)

Spending Ranges per Student - Revised
![image_name](https://github.com/Mugunthan24/School_District_Analysis/blob/main/Resources/Spending%20Ranges%20per%20Student_Revised.PNG)

- There are no notable changes

### Scores by School size
School Size - Original
![image_name](https://github.com/Mugunthan24/School_District_Analysis/blob/main/Resources/School%20Size%20Original.PNG)

School Size - Revised
![image_name](https://github.com/Mugunthan24/School_District_Analysis/blob/main/Resources/School%20Size%20Revised.PNG)

- There are no notable changes

### Scores by School Type
School Type - Original
![image_name](https://github.com/Mugunthan24/School_District_Analysis/blob/main/Resources/School%20Type%20Original.PNG)

School Type - Revised
![image_name](https://github.com/Mugunthan24/School_District_Analysis/blob/main/Resources/School%20Type%20Revised.PNG)