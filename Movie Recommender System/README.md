Project Title: Movie Recommender System

Language: Python

Libraires used: 
	Pandas
	Sklearn
	surprise
 
Project Description: 
This project uses the small MovieLens data set to create a recommender system that allows users to input a movie they like (in the data set) and recommends ten other movies for them to watch.

Files Needed:
		ratings.csv
		movies.csv

How to Run:
Download the files needed, see list above, and ensure they are saved in the same directory. Open Jupyter Notebook and navigate to the directory where the files are stored. Run the notebook, no alterations to code should need to be made.

Summary:
SVD is a matrix factorization algorithm which attempts to predict missing interactions from the matrix via factorization producing user latent and item/movie latent factors. In this case it is predicting movies based on rating. In this case we use the 100k dataset from Movielens which includes a movie database and ratings database. A reader for the ratings is created followed by the SVD model and 5-fold cross validation. A function takes in the given movie title, model, movie data frame, merged movie and ratings data frame, given user ID, and the number of recommendations in this case 10. Some precautions were accounted for by creating a column in the movies data frame that is only the title. This allows the user to type in the movie title without the year. In the event there are multiple movies with the same title the year is then requested. For each movie in the merged data set the model is used to predict the rating based on the user and movie. The recommended movies are found by taking the first/top 10 sorted predictions by movie rating descending.
