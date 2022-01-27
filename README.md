# Implement-kNN-in-Python

Implement kNN in Matlab or Python for handwritten digit classification and submit all codes and plots:

(a) Download MNIST digit dataset (60,000 training and 10,000 testing data points) and the starter code from the course page. Each row in the matrix represents a handwritten digit image. The starter code shows how to visualize an example data point in Matlab. The task is to predict the class (0 to 9) for a given test image, so it is a 10-way classification problem.

(b) Write a Matlab or Python function that implements kNN for this task and reports the accuracy for each class (10 numbers) as well as the average accuracy (one number).
[acc acc av] = kNN(images train, labels train, images test, labels test, k)
where acc is a vector of length 10 and acc av is a scalar. Look at a few correct and wrong predictions to see if it makes sense. To speed it up, in all experiments, you may use only the first 1000 testing images.

(c) For k = 1, change the number of training data points (30 to 10,000) to see the change in perfor- mance. Plot the average accuracy for 10 different dataset sizes. You may use command logspace in Matlab. In the plot, x-axis is for the number of training data and y-axis is for the accuracy.

(d) Show the effect of k on the accuracy. Make a plot similar to the above one with multiple colored curves on the top of each other (each for a particular k in [1 2 3 5 10].) You may use command legend in Matlab to name different colors.

(e) Choose the best k for 2,000 total training data by splitting the training data into two halves (the first for training and the second for validation). You may plot the average accuracy wrt k for this. Note that in this part, you should not use the test data. You may search for k in this list: [1 2 3 5 10].
