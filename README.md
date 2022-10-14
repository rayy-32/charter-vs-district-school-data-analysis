# Charter Schools vs. District Schools - Data Analysis

A series of programs using Python, Pandas, and Jupyter Notebook to analyze sample data about schools, their students, and their test scores.

## About

The ipynb file in this repository will read the csv files in the 'Resources' folder, and return the following information:

* Names of all schools in a district
* Total number of students in each school
* Total budget of each school
* Average reading and math score of students, for each school and all schools
* Percentage of students who passed reading, math, and both subjects

Further comparison is made with this information, by comparing the type of school, the amount of budget a school spends on a student, etc.


## Report Analysis

**_Charter schools tend to perform better than district schools._**

There is a significant difference in performance between charter and district schools.  
When comparing the the two types of schools in all metrics, charter schools have higher scores, and higher numbers of students passing reading and math.


| School Type | Avg Reading Score | Avg Math Score | % Overall Passing |
| --- | --- | --- | --- |
| Charter   | 83.90 | 83.47 | 90.43
| District  | 80.96 | 76.96 | 53.67

A key factor that contribute to this outcome is the difference in size between these two school types.  
The table below shows the top 5 and bottom 5 performing schools in the district, showing that the best performers are all charter schools and the worst performing are all district schools. It also lists the total students in each school.


| School Name | Type | Total Students | % Overall Passing |
| --- | --- | --- | --- |
| Cabrera High   | Charter  | 1858 | 94.13
| Thomas High    | Charter  | 1635 | 90.95
| Griffin High   | Charter  | 1468 | 90.60
| Wilson High    | Charter  | 2283 | 90.58
| Pena High      | Charter  |  962 | 90.54
| .............. | ........ | .... | .....
| Johnson High   | District | 4761 | 53.54
| Hernandez High | District | 4635 | 53.53
| Huang High     | District | 2917 | 53.51
| Figueroa High  | District | 2949 | 53.20
| Rodriguez High | District | 3999 | 52.99

Charter schools have much fewer students to teach than district schools. This is important because the more students that a school has, the more spread out its budget and resources will be, which could result in a less thorough education.  

With this in mind, the average test scores of district schools will be lower, as a larger student body will have larger ranges of passing and failing students.  

Therefore, having fewer students in a school may result in a more concentrated and lasting education, which may contribute to higher test scores and passing rates.

  

**_Spending more resources on students doesn't necessarily result in higher scores._**

The table below shows the average amount of students passing sorted by how much a school spends on its students, assuming the entire budget is going towards them.


| Spending per Student | % Passing Reading | % Passing Math | % Overall Passing |
| --- | --- | --- | --- |
| under $580  | 96.54 | 93.87 | 90.58
| $580 - $610 | 96.34 | 93.69 | 90.26
| $610 - $640 | 87.46 | 77.14 | 68.48
| $640 - $670 | 80.67 | 66.70 | 53.71

At first, the data can seem contradictory. Generally, a student with more resources at their disposal will have more potential to succeed than one with fewer resources. Following that statement, the schools that spend the most amongst its student body should be showing more successful results.  

However, the opposite is the case with this data set. The highest spenders turn out to be the district schools, who need a larger budget to accomodate for their larger student body. Since district schools tend to score lower overall because they have so many students, it can be inferred that success is not correlated with spending more per student.  

This doesn't mean that their budgets should be cut, or that they should spend less overall. One possible explanation could be that schools that report spending less per student are finding better ways to use their resources.  

Although this is outside of the scope of this data set, a question to ask is to see if there could be more efficient ways for higher spending schools to utilize their budgets for instruction, supplies, etc., and then seeing if those changes affect overall student performance.