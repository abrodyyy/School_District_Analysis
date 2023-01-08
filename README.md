# School_District_Analysis
## Project Overview
We've been tasked with assisting the chief data scientist for a city school district in preparing and analyzing standardized test scores and school funding to provide insights about student performance. These insights are used to inform discussions and strategic decisions at the school and district level.


This new assignment consists of five technical analysis deliverables and a written report to deliver the results:
Deliverable 1: Collect the student data into a DataFrame.
Deliverable 2: Prepare a cleaned version of the DataFrame.
Deliverable 3: Summarize key pieces of the data.
Deliverable 4: Drill down into the data to analyze specific subsets.
Deliverable 5: Compare and contrast the data through grouping and aggregation functions.
Deliverable 6: A written analysis of your results (README.md).
_The deliverables can be found in the jupyter notebook xyz_

## Resources
Data Source: newstudentdata.csv
- Software: Python 3.9.12, Visual Studio Code, 1.70.2, Jupyter Notebook 6.4.8
## Results

School Type | Avg. Reading Score | Avg. Math Score | School Budget
----------- | ------------------ | --------------- | -------------
Charter	    | 72.45	             | 66.76           | $872,625.66
Public	    | 72.28	             | 62.95           | $911,195.56

School Name            | Student Count
---------------------- | -------------
Montgomery High School | 2038
Green High School	   | 1961
Dixon High School	   | 1583
Wagner High School	   | 1541
Silva High School	   | 1109
Woods High School	   | 1052
Sullivan High School   | 971
Turner High School     | 846
Bowers High School     | 803
Fisher High School     | 798
Richard High School    | 551
Campos High School     | 541
Odonnell High School   | 459
Campbell High School   | 407
Chang High School      | 171

School Type | Grade | Avg. Reading Score | Avg. Math Score
----------- | ----- | ------------------ | ---------------
Charter     | 9     | 68.68	             | 70.08
Charter     | 10    | 69.63 	         | 66.44
Charter     | 11    | 80.60 	         | 68.02
Charter     | 12    | 70.48 	         | 60.21
Public      | 9     | 69.69	             | 63.77
Public      | 10    | 73.16 	         | 63.76
Public      | 11    | 73.49 	         | 59.31
Public      | 12    | 73.34 	         | 63.57


## Summary
Our analysis demonstrates that Charter and public schools average a higher reading score than math score. While Charter schools do have a slightly higher math average than public schools, it’s still below a passing grade for both school types. The budget difference between Charter and Public schools is not significant. Public schools to get more funding, however the charter schools average higher scores across the board, which leads us to infer that the budget does not correlate to an increase or decrease in student scores. Public schools do see a slight increase in reading scores after Freshman year, while Charter schools reading scores increase until Junior year and then drop. Public schools math scores are relativley the same throughout all 4 years, there is a slight decrease Junior year. Charter schools math scores fluctuate throughout all for years. Based on our reasearch so far, I would advise both Public and Charter schools to review and make improvements to their math curriculum. Some additional analysis could be done to review the number of students at each school in comparison to their grade averages. It's possible that smaller classes may correlate to higher scores. 