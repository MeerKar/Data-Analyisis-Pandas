# Background


As a Data Analyst , helping the school board and mayor make strategic decisions regarding future school budgets and priorities.As a first task, is to analyze the district-wide standardized test results. With the access of  every student's math and reading scores, as well as various information on the schools they attend the task is to aggregate the data to showcase obvious trends in school performance.In this project used datasets in csv format called school_complete.csv file which includesStudent ID, School_name,type,size,budget and the other datast students_complete.csv file which includes Student ID,student_name,gender,grade,school_name, reading_score and mathe_score.For these analysis both datasetsimported, merged and the aggregate data displayed into python pandas dataframe.this project is conducted in Jupyter Noebook and the link is as follows.
(http://localhost:8888/notebooks/Desktop/Panda/Data-Analyisis-Pandas/PyCitySchools/Starter_Code/PyCitySchools/PyCitySchools_starter.ipynb)
	
<img width="816" alt="image" src="https://user-images.githubusercontent.com/116701851/210693028-2d08aa3b-6b44-4ee7-b359-346b087ccae3.png">


Observations

1. District Summary

Necessary calculations were given to create a high-level snapshot of the district's key metrics in a DataFrame.

Include the following:

Total number of unique schools

Total students

Total budget

Average math score

Average reading score

% passing math (the percentage of students who passed math)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed math AND reading)


The output for the following were a total of 15 schools and 39170 students.The total students average math score is 78.98 and the reading score is 81.87 which is higher than math score.The passing percentage of math is 74.98% and the reading percentage is 85.80% which is higher again.The overall passing percentage is 65.17%. These findings conclude that the students score more in reading than math.


<img width="789" alt="image" src="https://user-images.githubusercontent.com/116701851/210701255-23067e2c-ca14-4049-9480-a6df35ccd8d3.png">


2.School Summary

Performed the necessary calculations and then created a DataFrame that summarizes key metrics about each school.
Include the following:

School name

School type

Total students

Total school budget

Per student budget

Average math score

Average reading score

% passing math (the percentage of students who passed math)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed math AND reading)

The results showed that 7 0f 15 schools are district level and 8 are at the charter level.The number of students ranged from 427 to 4976 students.These findings showed that district level have more students than charter level.

<img width="1009" alt="image" src="https://user-images.githubusercontent.com/116701851/211126841-f8f8c60b-c562-456f-a279-8cc7f3b28e61.png">



Highest-Performing Schools (by % Overall Passing)

in this a table is created based on percentage overall passing in descending order which includes the above metrics .The results shows as below

<img width="995" alt="image" src="https://user-images.githubusercontent.com/116701851/211127373-6d3cd6c2-4b9f-4106-86c0-34814b2168c4.png">


