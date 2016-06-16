# Movie-Recommendation-Engine
A Recommendation Engine for Movies using the Grouplens Movie rating dataset

This is a collaborative filtering algorithm for creating a movie recommendation engine. I have used the 100k dataset from Grouplens and added in my own ratings to it. 

In optimizing the predictive ability of the algorithm, I look at the R-squared fit of the training set for various model parameters. However, since overfitting could give a very high fit, I also sample some of the models to look at the predictions. Only the models which show reasonable recommendations are found to be suitable. This is a first pass. In the next iteration, I will look into dividing the data into training and a validation cuts.
