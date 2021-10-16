# Movies-ETL-Challenge
## Project Overview
Amazing Prime has requested a dataset that they can update daily.  In order to do this, code was refactored to create a single function that takes in three data files and performs the ETL process  by adding the data to a PostgreSQL database.

### Data Used:
 - Wikipedia Data
 - Kaggle Data
 - MovieLens Rating Data
 
 ### The Plan:
 1. Write/Create an ETL Function to read the data files (Total of 3)
 2. Extract and Transform (clean) and Merge the Wikipedia and Kaggle Datasets
 3. Merge Wikipedia, Kaggle and MicroLens Ratings datasets and load to PostgreSQL Database

 
 ### Examples of Code:
 ![Read_Data](https://user-images.githubusercontent.com/89044350/137567382-6d8bd2cd-35b9-47a8-b0f8-89996ffeb578.PNG)

Step 1: The above code pulls in the three data files, cleaning and then reading the .json file as a Pandas DataFrame

![Clean_Data](https://user-images.githubusercontent.com/89044350/137567651-826db2bc-1071-4359-9983-9f5a28b203e3.PNG)

Step 2: The above code cleans and merges the Wikipedia and Kaggle Data

![Merge_PostgreSQL_Database](https://user-images.githubusercontent.com/89044350/137567749-2b906c68-b1e7-42b2-b6d3-6829185c0c10.PNG)

Step 3: The above code merges the Wikipedia and Kaggle data with MicroLens Ratings data.  Once merged it is sent to PostgreSQL Database to query

## Summary
Three data files were Extracted, Transformed and then Loaded to a PostgreSQL database to provide Hackathon participants a nice, clean dataset to use.  The notebook files herein show our process based on three key steps: Plan, Inspect/Clean and Execute.  
