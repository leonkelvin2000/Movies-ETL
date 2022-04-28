# Movies-ETL

## Analysis Overview
- Amazing Prime loved the dataset and wants to keep it updated on a daily basis. Britta needed my help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. We are helping with the ETL process - Extract data from sources, Transform data and the Load to a database for storaage and analysis (in this case we are using SQL).

## Results
- After Extracting, Transforming and Loading the Kaggle and Wikipedia data, we have a fairly robust file for teams in the Hackathon to more efficiently be able to analyze data to help Amazing Prime with their project. The table we ended up with has 6,077 movies to analyze.

<img width="728" alt="movies_query" src="https://user-images.githubusercontent.com/98680133/165666313-aaa92e7c-26f9-4ecb-ba4d-fe189232df3e.png">

- We also retrieved, transformed and loaded another table which contains ratings about movies to further help teams with analysis - this created a total count for rating of 26,024,289.

<img width="728" alt="ratings_query" src="https://user-images.githubusercontent.com/98680133/165666342-0617197c-7e34-4754-9e08-5f10078f0f82.png">

## Summary

- While using refactored code to accomplish this task, it still required time but it felt good to have accomplished that. Here is a view of how much time it took (in seconds) when uploading all the different chunks of rattings table.

<img width="668" alt="extract_transfomration" src="https://user-images.githubusercontent.com/98680133/165666396-b929a9f8-2a4d-4acc-92fb-fe2c3fe3da5a.png">
