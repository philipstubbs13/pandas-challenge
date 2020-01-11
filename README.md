# Pandas Challenge

Data analysis of district-wide standardized test results for math and reading. Used the pandas library to aggregate and manipulate data to help uncover trends and improve school performance.

* [Background](#background)
* [Jupyter Notebook](#nb)
* [Technologies Used](#technologies)

##  <a name="background"></a>Background

For this project, I started with 2 csv files. Both of these files can be found [here](./PyCitySchools/Resources). One [csv file](./PyCitySchools/Resources/students_complete.csv) includes information about the students in the district, such as name, grade, school name, reading score, and math score. The other [csv file](./PyCitySchools/Resources/schools_complete.csv) includes information about the schools in the district, such as type, size, and budget. For this analysis, I loaded the two csv files into pandas dataframes. I merged these two dataframes based on the school name field they share to create a combined dataframe. I used the combined dataframe to analyze and find trends in school performance.

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
* [scores By School Type](#scores_by_school_type)

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