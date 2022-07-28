# School_District_Analysis

## Overview
The purpose of this analysis is to use schools and students data containing the budget per school and students' performance in math and reading. By analyzing this data we will be able to analyze the schools' overall performance and compare the performance according to the budget. Reading and math grades for Thomas High School ninth graders appear to have been altered, therefore, this data was removed from the analysis, since the school board does not know the full extent of the academic dishonesty.


## Results

#### District Summary:

- Including Thomas High School ninth grader data:

![image](https://user-images.githubusercontent.com/108500573/181567100-736fd48f-f3a3-4f3a-a558-ee0057c9fb21.png)

- Excluding Thomas High School ninth grader data:

![image](https://user-images.githubusercontent.com/108500573/181546156-c332c288-9e04-4068-9e71-ebaf30a014b1.png)


#### Per School Summary

- Including Thomas High School ninth grader data:

![image](https://user-images.githubusercontent.com/108500573/181571967-b8d90059-7019-44a4-a6e0-c4ddc01731c5.png)

- Excluding Thomas High School ninth grader data:

![image](https://user-images.githubusercontent.com/108500573/181571851-05e24652-cc5b-4fd5-aa8c-d913874f56e1.png)


#### Scores by school spending

- Including Thomas High School ninth grader data:

![image](https://user-images.githubusercontent.com/108500573/181571294-77d8a8a9-0a45-4135-a393-0330a49e77ed.png)

- Excluding Thomas High School ninth grader data:

![image](https://user-images.githubusercontent.com/108500573/181571632-422017a4-e288-4671-b43e-d1d3ed87d9e8.png)


#### Scores by school size

- Including Thomas High School ninth grader data:

![image](https://user-images.githubusercontent.com/108500573/181570751-05347e45-d8a3-445d-9f31-bd6c619d0be9.png)

- Excluding Thomas High School ninth grader data:
![image](https://user-images.githubusercontent.com/108500573/181570576-d08ba146-f185-49c3-82b3-48904a8ef669.png)


#### Scores by school type
- Including Thomas High School ninth grader data:
![image](https://user-images.githubusercontent.com/108500573/181572163-3fb6a823-5572-4324-a51b-1b5d6b221c2c.png)


- Excluding Thomas High School ninth grader data:
![image](https://user-images.githubusercontent.com/108500573/181572110-e506df84-7d9d-42ea-8e87-b224b8ac0651.png)


## Analysis
- In the district summary report, math, reading, and overall percentage passing are lower after excluding the Thomas High School ninth grader data.
- Only Thomas High School was affected in the per school summary, the scores and percentages are lower after excluding the ninth grader data.
- Although the overall performance of Thomas High School was reduced after excluding the ninth grader data, the performance is still high compared to other schools.
- Thomas High School is the in $631-645 per student spending. There was no impact in the school spending report after excluding the ninth graders' data.
- Thomas High School is included in Medium (1000-1999) school size class. There was no impact in the scores by school sizes after excluding the ninth grader data.
- Thomas High School is a charter school. There was no impact in the scores by school type after excluding the ninth grader data.


## Summary
A few reports were impacted after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs:
- District summary report
- Per shool summary report
- Math scores by grade
- Reading scores by grade

Reports that contain a larger combination of data were not impacted.
