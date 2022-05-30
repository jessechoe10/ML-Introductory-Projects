I decided to experiment with different n_neighbors or the "K" in K-nearest neighbors, and I found out that K = 9 is a good value for K. 

However, an unprecedented result occured when my accuracy was 100%. Was this possibly due to overfitting? 10% test data is typically good enough.

Then, I decided to do experiment with the training data, and I realized that the high accuracy wasn't that much of a problem since sometimes I got
around 98-99% accuracies which shows that my model ran well without errors.

Before implementing this project using scikit-learns' built in algorithm for K-Nearest Neighbors, I decided to learn how KNN works mathematically
and algorithmically by reading through this tutorial: https://www.techwithtim.net/tutorials/machine-learning-python/k-nearest-neighbors-2/.

To test my algorithm I used a Car Evaluation Dataset and used it to classify cars as unacceptable, acceptable, good, or very good. 
You can find the dataset here: https://www.kaggle.com/datasets/elikplim/car-evaluation-data-set.
