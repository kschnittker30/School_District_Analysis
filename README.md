# School District Analysis Overview
## The State Board of Education has resquested detail analysis on student funding and standarized testing scores to help the board determine budget allocations. The following key metrics have been requested:
### -Top 5 and bottom 5 performing schools, based on the overall passing rate
### -The average math score received by students in each grade level at each school
### -The average reading score received by students in each grade level at each school
### -School performance based on the budget per student
### -School performance based on the school size 
### -School performance based on the type of school
## The school board has found evidence of academic dishonesty in the students_complete.csv file; specifically, reading and math grades for Thomas High School ninth graders. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards. The analysis with the key metrics will be repeated with the math and reading scores for Thomas High School ninth graders excluded. The key metrics before and after the exclusion will be compared to determine the affect of changes in the overall analysis.

# Resource
## -Data Source: schools_complete.csv and students_complete.csv, -Software: Jupyter Notebook

# Summary
## District Summary:
### -The % Passing Math, % Passing Reading and % Overall Passing slightly decreased by less than 0.5%.
#### Original
# ![image](https://user-images.githubusercontent.com/99636479/159835260-406fde1b-1fbb-47ff-9c16-4c04feb0c6d3.png)

#### Adjusted
# ![image](https://user-images.githubusercontent.com/99636479/159835341-c36dfec5-3f06-4a9c-8682-073cd4cd03fc.png)


## School Summary (provides top 5 and bottom 5 performing schools and school spending per student)
### -The % Passing Math, % Passing Reading and % Overall Passing for Thomas High School slightly decreased by less than 0.5%. The top 5 and bottom 5 schools did not change nor the school spending per student.
#### Original
# ![image](https://user-images.githubusercontent.com/99636479/159834590-c7eedd74-7d46-491e-b5ff-d0741856e13c.png)

#### Adjusted
# ![image](https://user-images.githubusercontent.com/99636479/159834184-49791ddc-6cb5-462a-acc7-23ff3bfe8cf6.png)

  
## Math scores by grade.
### -The math scores shows "nan" for Thomas High School ninth graders.
#### Original
# ![image](https://user-images.githubusercontent.com/99636479/159834704-7dfe6da4-1ec5-4684-be9d-25a1f05d2bbf.png)

#### Adjusted
# ![image](https://user-images.githubusercontent.com/99636479/159833557-6e5f8692-1bce-4db2-9a53-11cc73aee8dd.png)
 
 
## Reading scores by grade.
### -The reading scores shows "nan" for Thomas High School ninth graders.
#### Original
# ![image](https://user-images.githubusercontent.com/99636479/159834751-bfb1c805-1bda-49e0-b87e-4ad5f9644ef1.png)

#### Adjusted
# ![image](https://user-images.githubusercontent.com/99636479/159833503-9affd85c-6b48-4f30-9570-3f5720987ca3.png)


## Scores by School Size
### There was a slight change for medium sized schools and % pass reading.
#### Original
# ![image](https://user-images.githubusercontent.com/99636479/159835186-cd3874e9-d95b-4a94-8631-b87fa568107c.png)

#### Adjusted
# ![image](https://user-images.githubusercontent.com/99636479/159837442-7429f1f8-d44f-4d08-a7b1-ce1be51665dd.png)


## Scores by School Type
### There was no notable changes based on school type.
#### Original
# ![image](https://user-images.githubusercontent.com/99636479/159835039-a0fa7eae-2a9e-4639-802f-cef88aac35ba.png)

#### Adjusted
# ![image](https://user-images.githubusercontent.com/99636479/159837678-b97f6d5b-4701-41a2-8d55-58f73b76e12e.png)


## Summary Analysis
### There were 461 student accounts math and reading scores removed from the analysis representing the ninth graders from Thomas High School. After recalculating the perecentages for passing math, reading and overall, there was a slight decrease of less than 0.5% for the district summary and Thomas High School summary.  The math and reading scores by grade changed with "nan" appearing for the Thomas High School ninth graders.  
