# sql_project_1
This very short project demonstrates the SQL skills I have for conducting relatively simple querying using a large dataset. This project was completed using the PostgreSQL flavor of SQL. 

# Documents in this repository

In this repository, besides this README document, there are two files. One of them is the students.csv file which contains data relating to a mental health study conducted in Japanese universities, considering international and domestic students. 

The other file is a notebook; in here there is the preamble and task provided by DataCamp. There is also some information relating to what the field names represent and the task I have been asked to complete. The instructions provided included the expected format for the output table to be created. 

The notebook also shows a preview of the original dataset, and **it shows the code I wrote to conduct the query**. 

# Results 

The query showed a table where each row represented the group of international students that had been at a Japanese university for that number of years (stay), and the mean (average) score for each of the mental health-related questionnaires they completed. 

There were some key findings presented by this table: 
1. As stay length increased, the mean score on the average_phq test increased (indicating higher levels of depression). However, it would be remiss to not acknowledge that this pattern is not consistent all the way through; this may be in part due to the small number of students that had been there for more than 4 years (with 3 students having been there for 6 years, and only one student had been there for each of 5, 7, 8 and 10 years, and 0 students for 9 years).
2. At a glance, there is little correlation between stay length and social connectedness.
3. The acculturative stress students experienced did relate somewhat to stay length. This kind of stress stems from students attempting to acclimate to their new society and the culture of that society, so it makes sense that the students who had been there for 5 years or fewer had a higher acculturative stress level. However, this findings were not linear.

# Next Steps 

Where I trying to find additional information based on these relationships, or quantify the extent to which the length of time a student had been in Japan correlated with the different mental health tests, the table created could be exported to R or Python. Here I could conduct correlational tests, or perhaps a multiple linear regression. (I would expect the statistical significance of these results to be low.) 
