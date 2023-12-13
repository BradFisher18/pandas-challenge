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
Upon running the code, it will first merge the two files before outputting the following dataframes:
* Local government summary showing the overall statistics of the whole area
* Summary grouped per school
* Top 5 performing schools by % students passing overall
* Bottom 5 performing schools by % students passing overall
* 

# VBA-Challenge
# Summary
This code is targeted for analysts wanting to evaluate the performance of a company's stock value over time, and compare it to that of other companies. The code is written to be run using VBA, with the data presented in a Microsoft Excel Workbook 
# Inputs
This code requires the following data to be inputted into the workbook prior to running it, split into a new worksheet for each year:
* company ticker
* date of stock information
* daily opening stock price
* daily highest value of stock price
* daily lowest value of stock price
* daily closing stock price
* daily stock volume
# Outputs
By runnning this code, it will produce the following outputs:
* yearly change of stock price for each company, including formatting showing if it is a positive or negative change
* yearly change as a percentage
* each companies total stock volume for the year
* In a seperate table, it will print the best and worst performing companies determined by percent yearly change, as well as the company with the greatest total stock volume.
# Installation and Running Code
To commence running this code, in your Microsoft Excel workbook ensure that the 'Developer' tab on the ribbon is selected and Macros is enabled (if they are not, refer to the links below for steps to do this). Select Visual Basic in the Code section of the Developer tab. This will open a window where you can create a new Module in the workbook. Insert the code from this repository there, and then run the code!

Steps to display Developer tab: (https://support.microsoft.com/en-us/office/show-the-developer-tab-e1192344-5e56-4d45-931b-e5fd9bea2d45)

Steps to enable Macros: (https://support.microsoft.com/en-au/office/enable-or-disable-macros-in-microsoft-365-files-12b036fd-d140-4e74-b45e-16fed1a7e5c6)
