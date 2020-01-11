# Pandas Challenge

Data analysis of district-wide standardized test results for math and reading. Used the pandas library to aggregate and manipulate data to help uncover trends and improve school performance.

## Background

I started with 2 csv files. Both of these files can be found [here](./PyCitySchools/Resources). One csv file includes information about the students in the district, such as, name, grade, school name, reading score, and math score. The other csv file includes information about the schools in the district, such as, type, size, and budget. For this analysis, I loaded the two csv files into pandas dataframes. I merged these two dataframes based on school name to create a combined dataframe. I used the combined dataframe to analyze and find trends in school performance.

## Jupyter Notebook

For this project, I used jupyter notebook to render and display the results of this analysis. You can view the notebook here:

<https://nbviewer.jupyter.org/github/philipstubbs13/pandas-challenge/blob/master/PyCitySchools/school_test_scores_analysis.ipynb>

The notebook is also available inside this repository [here](./PyCitySchools/school_test_scores_analysis.ipynb).

In this notebook, you will find the following:

* District Summary
  * The district summary is a high level snapshot (in table form) of the district's key metrics, including:
    * Total schools.
    * Total students.
    * Total budget.
    * Average math score.
    * Average reading score.
    * Percent passing math.
    * Percent passing reading.
    * Overall passing rate (the average of the above two).
* School Summary
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
  * Top Performing Schools (By Passing Rate)
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
  * Bottom Performing Schools (By Passing Rate)
    * This is a table that highlights the bottom 5 performing schools based on overall passing rate. It includes the same metrics as the table for top performing schools based on overall passing rate.
  * Math Scores By Grade
    * This is a table that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.
  * Reading Scores By Grade
    * This is a table that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.
  * Scores by School Spending
    * This is a table that breaks down school performances based on average spending ranges (per student), which includes:
      * Average math score.
      * Average reading score.
      * Percent passing math.
      * Percent passing reading.
      * Overall passing rate (Average of the above two).
  * Scores by School Size
    * This is a table that breaks down school performances based on school size (small, medium, and large). It includes the same metrics as the table for scores by school spending.
  * Scores by School Type
    * This is a table that breaks down school performance based on school type (District vs Charter). It includes the same metrics as the table for scores by school spending.

## Technologies Used

* Python
* Pandas library
* Jupyter Notebook