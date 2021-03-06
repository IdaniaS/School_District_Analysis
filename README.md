# School_District_Analysis
## PyCity Schools

### Overview of school district anaylsis
Maria would like to analyze the district-wide standardized test results for Reading and Math. Specifically comparing data for Thomas High School ninth graders. Collecting all the data and providing the school board with an evaluation of reading and math grades for schools in the district.
- Scores by school spending per student, by school size, and by school type
- Total School Budget
- Average Math Score for each grade level
- Average Reading Score for each grade level
- % Passing Math
- % Passing Reading
- % Overall Passing

### Purpose of this anaylsis
Produce and analyze trends in school performance testing in subjects Math and Reading. Maria would also like an analysis on how replacing the math and reading scores for Thomas High School with NaNs affected the overall analysis.

### Results
#### How is the district summary afftected?
- The district summary was negatively impacted by replacing the ninth-grade reading and math scores. The overall number of students was not drastically changed but decreased from 39,170 to 38,709. The average reading and math scores along with the overall students passing was impacted negativly.

![Note7](https://user-images.githubusercontent.com/86635590/127786109-7bc6f97b-b6a9-4518-9f5f-081111981c80.JPG)

#### How is the school summary affected?
- There was a decrease in math and reading scores when the ninth-grade class was omitted from the Thomas High School's overall average scores and percentage passing.

![Note11](https://user-images.githubusercontent.com/86635590/127786450-30992602-f8e5-42ce-be9b-717777ea7ed5.JPG)
![Note12](https://user-images.githubusercontent.com/86635590/127786472-c0cb38b1-2f71-4dc5-91a1-24f990029a6b.JPG)


#### How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
- In the image below Thomas High school's performance is ranked second in the top five highest scoring schools. The overall ninth-grade scores have impacted the district and school but have not drastically changed the standing of the Thomas High School's performance to the other schools.

![Note13](https://user-images.githubusercontent.com/86635590/127786557-528e92a9-8004-459d-a0a3-2e03c54a94a7.JPG)

#### How does replacing the ninth-grade scores affect the following:
##### Reading and Math scores by grade
- The calculations for passing rates with the "clean_student_data" produced a passing math percentage of 74.76% while the percentage passing for reading was about 85.66%.
- Listed nan for Thomas High School under the ninth-grade scores.

- Reading:
![Note19](https://user-images.githubusercontent.com/86635590/127786650-19234e5c-eb3d-406b-b034-8e1c50e7cde6.JPG)
- Math:
![Note18](https://user-images.githubusercontent.com/86635590/127786629-28635bba-7201-4372-befb-4ef4dd51f2f2.JPG)

##### Scores by school spending
- Average Math and Reading score
- Percent passing Math and percent passing reading
- Percent of overall students passing Math and Reading
- The overall percentage of students passing is negatively impacted by the correlation of the school spending.

![Note20](https://user-images.githubusercontent.com/86635590/127786725-12a6b88b-7859-4ee3-9ae9-7e30e03dafb3.JPG)
![Note22](https://user-images.githubusercontent.com/86635590/127786735-723533a8-15a6-4802-baf2-764448a15706.JPG)

##### Scores by school size
- The largest of the schools had the lowest overall passing percentage at under 60% it is significantly lower than the other schools. The medium schools had the highest overall percent of students passing and in close competition with small schools, both with 90%+ passing.

![Note23](https://user-images.githubusercontent.com/86635590/127786754-ebb03947-43d1-4f23-9037-7f704a2c8a34.JPG)
![Note25](https://user-images.githubusercontent.com/86635590/127786765-48e2a090-1d05-4b0e-8410-147d65576278.JPG)

##### Scores by school type
The top five schools classified by top performance fall under the Charter classification, whereas the bottom five schools are established as District.
![Note27](https://user-images.githubusercontent.com/86635590/127786771-1cd40173-8f7f-45c8-a3fa-dff4c86e1d12.JPG)

#### Top Performing Schools
- Top performance based on percent of overall students passing
![Note13](https://user-images.githubusercontent.com/86635590/127786791-087fde7f-b6d7-4991-8357-af3d8ac7c09c.JPG)

#### Bottom Performing Schools
- Bottom performance based on percent of overall students passing
![Note14](https://user-images.githubusercontent.com/86635590/127786797-cef5ff9e-6237-4dc8-a49f-79fbc7ab1e52.JPG)

### Summary
- With the modified results removing the ninth-grade scores the average for Thomas High School and the distrct decreased. The Thomas High School still ranked above most schools based on the student performance.
- The potential for academic dishonesty is shown in the data and should be evaluated by the school board for future reference when comparing class grades in each school.
- The school board should analyze how the size and classification of the school have impacted the scores. With the large schools falling short in comparison to small and medium size schools. Along with the District schools ranking in the bottom 5 based on student performance. When replacing the ninth-grade math and reading scores the trend continues. There are 461 students in the ninth-grade at Thomas High School out of the 1635 students in total. The smaller school along with its classification as a Charter school should be analyzed in the fial decision as both these allow for the school to condinue to produce its high ranking performance numbers.
- Thomas High School is negatively impacted by the ninth-grade scores being redacted.
- Thomas High School has a mid-range budget that allows the school to capably focus how the money can be spent to benefit all students attending the school. The spending ranges per student directly impacts student performance.
