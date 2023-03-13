# Analyzing Big Data Using SQL and RDBMS Systems

## Description of the Project 

The objectives of the project are to help us understand in:
1. Appreciating the power of SQL in extracting and analyzing useful information from real datasets
2. Practicing andapplying the data systems concepts, mainly modeling, storing, and querying datasets on large
3. Appreciating the power of SQL in extracting and analyzing big datasets.
4. Comparing the differences between SQL and NoSQL. 

## Technologies used 
- Our team decided to use **PostgreSQL** with **pgadmin4** as the technologies used to use SQL for extracting and analyzing useful information from the Anime datasets.
- For NoSQL, **Couchbase** was used for extracting useful information of the crime dataset. 

## Description of the SQL dataset

This dataset contains information about 17 562 Animes and the preference from over 300 000 different users. In particular, this dataset contains: 

1. **anime_list.csv**: Contains the list of unique animes per user. For each anime the user has given a rating, watched episodes and ‘watching status’. (1 - Currently watching, 2 - Completed, 3 - On Hold, 4 - Dropped, 6 - Plan to watch)

2. **ratings_completed.csv**: CSV that contains the list of ratings given by the user to animes with watching status = 2 (complete) 
(note: this file is very large which caused us to disregard this table altogether at the end)

3. **anime.csv**: Information of anime scrapped of main page and stats page.

Total size of dataset: (2.87GB) 
https://www.kaggle.com/datasets/hernan4444/anime-recommendation-database-2020?select=anime.csv

## Description of the NoSQL dataset 

The dataset used pertained to reported incidents of crime in the City of Chicago from 2001 and onward. The actual csv file is approximately 1.5GB while its jsoncounterpart is 4.7GB. The size of the bucket within Couchbase Server is approximately ~4.7GB (unsurprisingly about the size of the json file). 

https://www.kaggle.com/datasets/chicago/chicago-crime





