# MOVIES_ETL

# Overview
The purpose of this project is to clean a very large dataset and trim it down to the data we need. I am working with the kaggle data which stores movie data (i.e reviews, ratings etc.). Since the kaggle data is a very very large dataset, using ETL I am able to take out the data I need, clean it so its more readable and then export the data into a database.

# Resources
- Software: Python 3.8, Anaconda 3.4.10, PGAdmin 4 version 5.2, Microsoft Excel for Mac
- Languages Used: Python, SQL

# Results
After cleaning the data, I was able to import the results into the PGAdmin software. This produced a table showing the tally for [movies](https://github.com/somtoesomeju/movies_ETL/blob/main/Movies_query.png) and [ratings](https://github.com/somtoesomeju/movies_ETL/blob/main/ratings_query.png). The initial data from the ratings_csv was so large that I initially had trouble uploading the file to my Github. From the image of the refractored data, it shows that the data has been trimmed down to keep only the files that we need. This can be seen from the count of the ratings data.
