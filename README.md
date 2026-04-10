# movielens-mysql-analysis
MovieLens SQL Data Analysis using MySQL to explore user ratings, movie popularity, and genre trends.
Objective

To explore and analyze movie rating data using SQL in order to extract meaningful insights such as:

Most popular movies
User rating behavior
Genre-wise performance
Rating distribution trends

Tools & Technologies Used
MySQL
SQL (Joins, Aggregations, Group By, Subqueries)
MovieLens Dataset (Kaggle)

Dataset Description

The dataset contains three main tables:

Movies – Movie ID, title, and genres
Ratings – User ratings for movies
Tags (optional) – User-generated tags for movies

Key SQL Operations Performed
Data exploration and understanding table structure
Joins between movies and ratings tables
Aggregation queries for average ratings
Ranking movies using window functions
Filtering and grouping data by genres
Identifying active users and highly rated movies

Key Insights
• Comedy and Action are the most popular genres based on highest user engagement  
• Average ratings are consistent across genres, indicating stable user satisfaction  
• Documentary shows the highest average rating, but is based on a smaller sample size  
• User rating behavior varies significantly, with both strict and generous users present  
• Most popular movies are not always the highest rated, highlighting the difference between popularity and quality  
• User activity peaked in 2000, declined in the early 2010s, and rebounded strongly by 2017 — highlighting cyclical engagement trends over time
• Average ratings have remained stable over time, indicating consistent user sentiment  

Conclusion

The analysis shows that while user engagement and genre popularity fluctuate over time, overall rating behavior remains stable. By combining metrics such as rating counts and average scores, we gain a more accurate understanding of both movie performance and user preferences.
