# Airline_Booking_Recommendation

In this repo I worked with project partner Brendan Jenkins in a kaggle competition that tasked us with writing models in order to predict implicit ratings. In this real world data from booking.com, we have users (travelers) and items (cities) and our goal was to predict how likely travelers were to voyage to a given destination. We were able to achieve a log loss of 0.4100 and ranked 9th in the Kaggle competition among 55+ teams.

Techniniques Used:

We used negative sampling in order to randomly put negative weights on some items(cities) that a user has not visited.
We then tried different models such as matrix factorization and neural networks, and found our best results with the former.
We used embedding methods to represent users, items, and features as a dense vector.
During this project we worked on hyperparameter tuning in order to achieve the most optimized models. Hyperparameters such as embedding size, learning rate, weight decay, number of epochs and more.
