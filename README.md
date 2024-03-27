# Recommendation_System

Implementation of the research paper - Neural Collaborative Filtering (https://arxiv.org/abs/1708.05031) , which is used for recommendation system. Trained Neural Collaborative Filtering layer with concatenation of Matrix Factorization and MLP layers with 65% accuracy on anime rating dataset.
First a implicit dataset is created using the available rating dataset with dimension 2 * 131262 for the train data and 2 * 138493 test data.
Second train a matrix factorization method.
Third train a MLP method
and finally train a model which is in concatenation of all the three models.

