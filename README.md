# Netflix Prize

([Dana Kaner](https://github.com/danakaner)),
([Dor Bank](https://github.com/dorbank)),
([Aviv Navon](https://github.com/avivnavon))

## Statistical Learning, Spring 2017, TAU - Class competition

The Netflix Prize was a competition to predict user ratings of movies. Netflix provided ratings of 17770 movie titles by 480189 users, along with the date of each rating. The task was to predict ratings for 282000 user-movie-date triples that are not in the training set.  For more details: www.netflixprize.com

This class competition is a simplified version of the original Netflix Prize:   
The training data provide the ratings of 10,000 users for 99 movies, along with the dates at which the ratings were made. The outcome is the rating that each user gave to a further movie ("Miss Congeniality", 2000).

The task is to predict the rating for this movie by a further 2931 users in the test set. 

As with the Netflix Prize, performance will be measured by root mean squared error (RMSE) on the test set.

We where the winners at 0.7591 (RMSE).
