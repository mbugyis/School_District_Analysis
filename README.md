# School_District_Analysis

## Overview of the school district analysis

### The purpose of the school district analysis is to examine different aspects of the school district (type, size, budget, etc.) and see if there are any correlations or relationships with the other data in the data set.

## Results

How is the district summary affected?
- The district summary was first created by combining school and student data. Next, the 9th grade Thomas High School students were removed from the summary. This lowered the overall student population along with several metrics such as grade, % passing, etc.

How is the school summary affected?
- The school summary uses the scores, and passing percentages of the Thomas High School 10th-12th graders. The prior data in the DataFrame was replaced with the 10th-12th information. This significantly affected the data for Thomas High School

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- Replacing the scores greatly altered the schools performance. Prior to replacing the values, Thomas High School had averages in both math and reading in the 80s. After replacing the values, the averages where in the 90s. This also had an affect on the % passing for math and reading as well. They became one of the highest performing schools.

How does replacing the ninth-grade scores affect the following:
1. Math and reading scores by grade - There was Nan in Thomas HS, the following averages were between 83-84
[Scores by Grade DataFrame](https://github.com/mbugyis/School_District_Analysis/blob/main/Resources/scores_by_grade.png)
2. Scores by school spending - scores with lower spending had the highest averages and passing percentages
[School Spending DataFrame](https://github.com/mbugyis/School_District_Analysis/blob/main/Resources/school_spending.png)
3. Scores by school size - schools loew than 2500 had significantly higher averages and passing percentages. Almost 30% more likely to pass math and almost 40% passing overall
[School Size DataFrame](https://github.com/mbugyis/School_District_Analysis/blob/main/Resources/school_size.png)
4. Scores by school type - eliminating the ninth graders, especically Thomas, which was a Charter school saw an increase in overall data metrics. The most significant jump was % passing math.

[School Type DataFrame](https://github.com/mbugyis/School_District_Analysis/blob/main/Resources/school_type.png)


## Summary
After replacing the ninth grade scores. There was a significant increase in data. One can assume that the ninth grade scores for Thomas High School were not the best. 
First, the averages for reading and math scores increased by approximately 10 points.
Second, the % percentages for both math and reading, and obviously for the overall passing percentage increased. As most of the ninth grade scores were not passing initially.
Third, Thomas was in the second bucket of school size (just over 1500 ppl). The Thomas HS data increased the overall averages of this data bin. It is the highest performing size, with the highest passing percentages across the other sizes
Fourth, the same is said for the school type. Thomas was a Charter school and the averages for them increased as well. With the ninth grade data, it would decrease the averages but not significantly enough to where Charter and District schools were the same
