# pandas-challenge
## Summary
This repository imports data from csv files containing school budget and student data from a local government area, do display them into dataframes to assist with understanding the relationship between the school type and budget and the performance of the students.
## Inputs
This code draws from two seperate csv, in this case labelled schools_complete and student_complete.
The schools csv file shall include columns containing the following:
* School name
* School type (government or independent)
* School size (number of students)
* School budget

The student csv shall include columns containing the following:
* Student Name
* Gender
* Year at school
* School name
* Reading score
* Maths score
## Output
Upon running the code, it will first merge the two files before outputting the following:
The code calculates average maths and reading score, percentage of students passing maths, reading and overall. From this data, it then displays the dataframes described below:
* Local government summary showing the overall statistics of the whole area
* Summary grouped per school
* Top 5 performing schools by % students passing overall
* Bottom 5 performing schools by % students passing overall
* Maths scores by year group
* Reading scores by year group
* Scores by school spending
* Scores by school size
* Scores by school type
## Installation and running the code
For this code to run successfully, python is required to be installed along with the pandas tool library and either Jupyter lab or Jupyter notebook. One method to install these programs is to download Anaconda - link below. To run this code, open the file within Jupyter, ensure that the input files are directed correctly and run!
Anaconda install: https://docs.anaconda.com/free/anaconda/install/
