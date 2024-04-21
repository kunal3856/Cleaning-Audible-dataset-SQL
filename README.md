# Cleaning Audible Dataset Using SQL
We found this web scrapped data from Kaggle which contains information about the audible dataset, but the information was so messy and not so easy to handle for data analysis, this dataset contains over **80,000** rows which are almost impossible to clean manually, But with the help of PostgreSQL **query editor** it was not that hard of the job, I have attached an pdf file of all the SQL queries that i have used for cleaning this messy data.

### Uncleaned Preview of Data

This dataset has few corrections to made like 

-  Clean the **time** column to show only minutes rather than information of hours and minutes in text format that too in integer format for comparitive analysis.
-  Update **price** column to handle 'free' text rows.
-  Handle the **stars** column to show clear picture of stars obtained and number of **ratings** that will help to identify top picks while analysis.
-  Update the **author** and **narrator** columns to show only the names of people.

  
![image](https://github.com/kunal3856/Cleaning-Audible-dataset-SQL/assets/65026671/56a6e5a5-d0c5-47c3-96ab-b339eb83fe91)

### After Data Processing in SQL

I have added an pdf that contains all the SQL queries with their functionality that have been used in cleaning the data!

![image](https://github.com/kunal3856/Cleaning-Audible-dataset-SQL/assets/65026671/bd223c9a-80fe-4eef-88fe-411848d5bf99)
