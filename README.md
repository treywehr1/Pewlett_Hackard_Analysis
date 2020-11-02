# Pewlett Hackard Analysis
## Overview of Analysis: 

Multiple employee and department data sets for Pewlett Hackard were joined and manipulated using SQL in Postgres so that information regarding retiring employees and older employees could be evaluated and considered for company operations moving forward.

## Results: 
### Initial findings from SQL queries.

 - There are 1,940 employees eligible for mentorship positions.
 - 90,398 employees are eligible to retire across departments at Pewlett Hackard.
 - 32.54% of these eligible retirees are current senior engineers.
 
 ![Imgur](https://imgur.com/jWBlN2h.png)
 
 - 65,534 total employees are eligible for retirement due to the "silver tsunami"

## Summary: 
### What to make of the data...

 - Eventually, 90,398 employees will be needed to be replaced due to the "silver tsunami". This of course will happen over the course of multiple years due to birth dates differing across 1955-58.

 - In regards to the departments with the highest amount of turnover due to the "silver tsunami" - there may not be enough department members eligible for mentorship positions to usher in a new era of employee. With just 356 senior engineers in place to mentor those who need to eventually fill the shoes of 29,414 soon to retire employees, that would equate to about 80 pupils per mentor as plans to replace retirees go underway. This is shown by the new supplmental "mentoring_titles" sheet and query script below.
 
 ![Imgur](https://imgur.com/BWS4Zdx.png)
 
 ![Imgur](https://imgur.com/hWJC0jD.png)
 
  - According to the attached table relative to our "retiring_titles" table - no department would have a pupil to mentor ratio less than approximately 24 to 1.
