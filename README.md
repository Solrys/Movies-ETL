# Movies-ETL
## Background
Creating an Algorithm To Predict Successful Streaming Content 

ETL Extract transform and load
A core concept to insure the data is consistent and maintains its integrity
Data stores more efficiency. Using ETL to create data pipelines and transform the data so that we can analyze. 

* Extract
* Transform
* Load

## Sources
Wikipedia
Kaggle
Movielens

I gathered data from both Wikipedia and Kaggle, combined them, and saved them into a SQL database. To do this I followed the ETL process: 
1)Extracting the Wikipedia and Kaggle data from their respective files. 
2)Transforming the datasets by cleaning them up and joining them together. 
3)Loading the cleaned dataset into a SQL database.

(Raw data exists in multiple places and needs to be cleaned and structured before it can be analyzed. ETL breaks this problem into three steps, or phases: Extract, Transform, and Load.)

## Objective
The objective of this project is to create a comprehensive dataset with movie information and ratings for the Amazon sponsored hackathon. I will extract movie data from publicly available sources, transform it into a concise and readable dataset, and load the data into a SQL database.


## Results

### Final Movie Dataset
![final](https://github.com/Solrys/Movies-ETL/blob/main/resources/movies_df.png)


### Final Ratings Dataset
![final](https://github.com/Solrys/Movies-ETL/blob/main/resources/movies_with_ratings_df.png)

![final](https://github.com/Solrys/Movies-ETL/blob/main/resources/Screen%20Shot%202021-03-02%20at%203.25.52%20PM.png)
![final]

### Summary
The final dataset contains 6,052 movies with 26,024,289 ratings. With these new results of the hackathon Amazing Prime Video will be able to make deciscions about upcoming movie rights to purchase for their streaming platform.
