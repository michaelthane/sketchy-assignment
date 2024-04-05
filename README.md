# Sketchy assignment
### Required python packages
pandas
pandasql
jupyter
matplotlib

### Problem Statement
Sketchy is a visual learning company serving medical students among other programs. Some of the data engineering needs we are tasked with are supporting the internal teams with data driven analysis and reporting.Your task is to produce a report showing a penetration analysis of each medical school class. Penetration is defined as the number of paid subscribers enrolled in each school.

Medical school with respective enrollment information can be found at this link where the most current file would be “Total Enrollment by U.S. Medical School and Gender, 2019-2020 through 2023-2024” https://www.aamc.org/data-reports/students-residents/data/2023-facts-enrollment-graduates-and-md-phd-data#

Attached are several csv files to help in your analysis related to users and subscription status. Users - registration with self selected school option
Subscriptions - Status
Universities - lookup table

Your task is to show how you would ingest these files and join the data to facilitate such a report. You may use any language, but SQL or python solutions are preferred. The output is the code that you use to join the data with a focus on the university matching and determining user subscription status. The task should not take more than a few hours to complete.

### Observations
1. Not all users will be subscribed.
2. Users can have multiple entries for each program year. (user_name = "Aaron Allen")
3. From the Facts Table, enrollment is defined as students in medical school on October 31.
4. Users can have multiple records in subscription table. (i.e user_id = 237187)
5. During EDA, seeing that updated_at is the timestamp
6. Some "FREE_TRIAL" rows go backwards in time

### Deliverables
1. Report of number of students enrolled in each university per year and if they are paying or not.

### Questions
1. Why are there created_at fields in the users table?
