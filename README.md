# Houses-pricing
Kaggle challenge: Predict the prices of different houses. 

Competition description:

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

Strategy:

For that algorithm, I created a model based on decision trees using mean squared error as a lost function. Initially, I used tensorflow’s implementation of decision trees, but once I realized the bad performance, I adopted a new strategy. I decided to improve the model’s accuracy through the random forest ensemble learning technique, in which separate decision trees would be created from uniformly sampled data from my data set. Then, after averaging out the predictions of these trees, I got a better accuracy score in the Kaggle Challenge.
