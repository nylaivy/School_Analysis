#School District Analysis

##Overview Of Project
The purpose of this project was to prepare standardized test data for analysis, reporting, and presentation to provide insights on performance trends and patterns for a city school district. I analyzed data on student spending and standardized test scores by aggregating the data and showcasing trends in school performance, which can eventually help with budget decisions for the school district. In addition to this there had been evidence of academic dishonesty regarding reading and math grades for Thomas High School ninth graders. Therefore, as an attempt to uphold state-testing standards, I had to omit these dishonest reading and math scores from the analysis while keeping the rest of the data intact.

##Results
- The district summary was affected when changes to the analysis were made to accommodate for dishonest students by a slight decrease average math scores, percentage passing math, percentage passing reading, and overall passing percentage. This can be seen in the before and after data frames displayed below.


![district_before](/Resources/district_before.png) 
This is the district summary before replacing scores for Thomas High School 9th graders with NaNs

![district_after](/Resources/district_after.png) 
This is the district summary before replacing scores for Thomas High School 9th graders with NaNs


- The school summary was not as affected when changes to the analysis were made to accommodate for dishonest students. Only Thomas High School was affected.
- Replacing the ninth graders’ math and reading scores from Thomas High School did not significantly change the percentage of students who passed both math and reading respectively, and therefore the overall passing percentage. Thomas High School was still one of the highest performing schools as seen in the table showing the top five schools below

![top_five](/Resources/top_five.png) 
These are the top five highest performing schools in the district

- Replacing the ninth grader’s math and reading scores from Thomas High School showed up as “nan” when doing analysis on scores by grade but did not significantly affect the data when organized by scores by school spending, school size, or school type. Schools that spent less had higher overall passing percentages, larger schools had significantly less students passing, and Charter schools had significantly more students passing than District schools.

![spending](/Resources/spending.png) 
Results based on school spending per student

![school_size](/Resources/school_size.png) 
Results based on school size

![school_type](/Resources/school_type.png) 
Results based on school type

##Summary
In summary adjusting the analysis for dishonest students by replacing scores for Thomas High School with NaNs did not significantly change the outcomes of that school in terms of where they stood relative to other schools but did slightly decrease passing percentages for the district. Conclusions regarding standardized test scores relative to school spending, size and type were able to be made: schools that spent less had higher overall passing percentages, larger schools had significantly less students passing, and Charter schools had significantly more students passing than District schools.
