# Pandas Challenge - Academy of Py

Data analysis of district-wide standardized test results for math and reading. Used the pandas library to aggregate and manipulate data to help uncover trends and improve school performance.

* [Background](#background)
* [Observable Trends Based on the Data](#trends)
* [Jupyter Notebook](#nb)
* [Technologies Used](#technologies)

##  <a name="background"></a>Background

For this project, I started with 2 csv files. Both of these files can be found [here](./PyCitySchools/Resources). One [csv file](./PyCitySchools/Resources/students_complete.csv) includes information about the students in the district, such as name, grade, school name, reading score, and math score. The other [csv file](./PyCitySchools/Resources/schools_complete.csv) includes information about the schools in the district, such as type, size, and budget. For this analysis, I loaded the two csv files into pandas dataframes. I merged these two dataframes based on the school name field they share to create a combined dataframe. I used the combined dataframe to analyze and find trends in school performance.

## <a name="trends"></a>Observable Trends Based on the Data

* Scores By School Type
  * In general, charter schools have higher average math (83.47) and higher average reading (83.89) scores compared to the average math (76.95) and average reading (80.96) scores for district schools.
  * Also, the percentage of students passing math (93.62) and passing reading (96.58) for charter schools is higher than the percentage of students passing math (66.54) and passing reading (80.79) for district schools.
  * Charter schools have a higher overall passing rate (95.10) than district schools (73.67).
* Scores By School Size
  * Small (< 1000) and medium sized schools (1000 - 2000) are relatively the same in terms of average math score, average reading score, percentage of students passing reading, percentage of students passing math, and overall passing rate.
  * Large schools (2000 - 5000) have a lower average math score (77.74), lower average reading score (81.34), lower percentage of students passing reading (82.76), and a lower overall passing rate (76.36) than small and medium sized schools.
* Scores By School Spending
  * Schools that spend less per student generally have higher average math score, higher average reading score, higher percentage of students passing math, higher percentage of students passing reading, and higher overall passing rate.
* Math and Reading Scores By Grade
  * Looking at the average reading and math score for students of each grade level (9th, 10th, 11th, 12th) at each school, the average math and reading scores are generally (more or less) the same going from 9th grade all the way up to 12th. That is, there is little increase or decrease as a student goes from 9th grade to 12th.
* Bottom Performing Schools (By Passing Rate)
  * The 5 worst performing schools were all district schools and had more total students.
* Top Performing Schools (By Passing Rate)
  * The top 5 best performing schools were all charter schools and had fewer total students.



##  <a name="nb"></a>Jupyter Notebook

For this project, I used jupyter notebook to render and display the results of this analysis. You can view the notebook here:

<https://nbviewer.jupyter.org/github/philipstubbs13/pandas-challenge/blob/master/PyCitySchools/school_test_scores_analysis.ipynb>

The notebook is also available inside this repository [here](./PyCitySchools/school_test_scores_analysis.ipynb).

In this notebook, you will find the following:

* [District Summary](#district_summary)
* [School Summary](#school_summary)
* [Top Performing Schools](#top_performing_schools)
* [Bottom Performing Schools](#bottom_performing_schools)
* [Math Scores By Grade](#math_scores_by_grade)
* [Reading Scores By Grade](#reading_scores_by_grade)
* [Scores By School Spending](#scores_by_school_spending)
* [Scores By School Size](#scores_by_school_size)
* [Scores By School Type](#scores_by_school_type)

### <a name="district_summary"></a>District Summary

* The district summary is a high level snapshot (in table form) of the district's key metrics, including:
  * Total schools.
  * Total students.
  * Total budget.
  * Average math score.
  * Average reading score.
  * Percent passing math.
  * Percent passing reading.
  * Overall passing rate (the average of the above two).

### <a name="school_summary"></a>School Summary

* The school summary is an overview table that summarizes key metrics about each school, including:
  * School name.
  * School type.
  * Total students.
  * Total school budget.
  * Per student budget.
  * Average math score.
  * Average reading score.
  * Percent passing math.
  * Percent passing reading.
  * Overall passing rate (the average of the above two).

### <a name="top_performing_schools"></a>Top Performing Schools (By Passing Rate)

* This is a table that highlights the top 5 performing schools based on overall passing rate. It includes:
  * School name.
  * School type.
  * Total students.
  * Total school budget.
  * Per student budget.
  * Average math score.
  * Average reading score.
  * Percent passing math.
  * Percent passing reading.
  * Overall passing rate (Average of the above two).

### <a name="bottom_performing_schools"></a>Bottom Performing Schools (By Passing Rate)

* This is a table that highlights the bottom 5 performing schools based on overall passing rate. It includes the same metrics as the table for top performing schools based on overall passing rate.

### <a name="math_scores_by_grade"></a>Math Scores By Grade

* This is a table that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### <a name="reading_scores_by_grade"></a>Reading Scores By Grade

* This is a table that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### <a name="scores_by_school_spending"></a>Scores by School Spending

* This is a table that breaks down school performances based on average spending ranges (per student), which includes:
  * Average math score.
  * Average reading score.
  * Percent passing math.
  * Percent passing reading.
  * Overall passing rate (Average of the above two).

### <a name="scores_by_school_size"></a>Scores by School Size

* This is a table that breaks down school performances based on school size (small, medium, and large). It includes the same metrics as the table for scores by school spending.

### <a name="scores_by_school_type"></a>Scores by School Type

* This is a table that breaks down school performance based on school type (District vs Charter). It includes the same metrics as the table for scores by school spending.

##  <a name="technologies"></a>Technologies Used

* Python
* Pandas library
* Jupyter Notebook