# Matrix-Factorization
I have used this Matrix Factorization for predicting the rating the unrated movies using the rating of the previously rated movies. 


the ratings of the previous rated movies(i) by the users(j) is used to predict the new ratings for (i,j) which are not seen before using the Matrix Factorization. Matrix factorization is a way to generate latent features when multiplying two different kinds of entities.Here we assume the matrices to be a low rank matrices.Collaborative filtering is the application of matrix factorization to identify the relationship between items and users’ entities. With the input of users’ ratings on the items, we would like to predict how the users would rate the items so the users can get the recommendation based on the
prediction.

Since not every user gives ratings to all the movies, there are many missing values in the matrix and it results in a sparse matrix. Hence, the null values not given by the users would be filled with 0 such that the filled values are provided for the multiplication. For example, two users give high ratings to a certain move when the movie is acted by their favorite actor and actress or the movie genre is an action one, etc.

