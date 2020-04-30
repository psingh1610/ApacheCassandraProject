# ApacheCassandraProject

Sparkify is a music streaming app which has been collecting songs and user activity data.
They want to analyze the user's song listining activity. But in order to analyze it, they want it to only the relevant data for song analysis to be extracted. 
For this we need to create a database schema and break it down to different dimension tables and finally building ETL
pipeline to extract data from the two song and log files to our analytical database for better analysis.


1. Create a new data file which is denormalized to answer given questions.
2. Create Cluster, keyspace and then set keyspace to start creating tables.
3. create tables and load data to answer each question.
4. Test all the results to check if data was loaded and the query is giving the correct answers
