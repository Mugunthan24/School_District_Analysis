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
        - Has increased slightly from 83.35 to 83.42
    - Average Reading Score
        - Has decreased slightly from 83.9 to 83.85
    - % Passing Math
        - Has increased slightly from 93.19% to 93.27%
    - % Passing Reading
        - Has decreased slightly from 97.02% to 97.31%
    - % Overeall Passing
        - Has increased slightly from 90.63% to 90.95%