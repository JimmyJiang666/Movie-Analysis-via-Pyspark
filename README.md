# Movie-Analysis-via-Pyspark
This is a project assignment from "Algorithmic Foundation of Data Science". Here is a description of the requirement for this project.

Download ml-latest-small.zip from https://grouplens.org/datasets/movielens/latest/
and unzip it into a folder. Read the corresponding README.html file in the above website to
understand the format of the files contained in the folder. The first line in each csv file is
the header and the rest of lines contain data. Remove the first line from each of the csv files
manually to make programming easier.
Write a Spark program to compute the following:
1. The average number of users a movie is rated by.
2. For each genre, the average rating of all movies in that genre.
3. The names of the top three movies (by average user rating) in each genre.
4. Top ten movie watchers ranked by the number of movies they have rated.
5. Top ten pairs of users ranked by the number of movies both of them have rated.
When considering the ratings for a movie, we only consider the users that have rated the
movie. For instance, to compute the average rating for a movie we add all the ratings of the
movie and divide by the number of users that have rated the movie.
Your program should assume that the csv files are located in the same directory as your
program. Along with your code give brief explanations for the algorithm used for each of the
above tasks.
