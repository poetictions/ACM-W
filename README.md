# ACM-W
Logistic Regression Approach:
•	The iris dataset has three classes: virginica, setosa and versicolor and four features: pedal length, pedal height, sepal length, sepal height.
•	X variable defined is for feature values 
•	Y variable defined is for the target values 
•	Logistic regression is basically linear regression + activation function. It basically assigns a class to the input variable. The final outcome is 1 for the positive class and 0 for the negative class. 
•	In this algorithm, we basically need to minimize the cost function by adjusting the values of weights and biases by optimization methods like gradient descent.
•	Activation function (sigmoid/softmax) transforms the weighted sum of the input features into a probability output. 
•	As the iris dataset has more than two classes (three), we use the multinomial logistic regression, in contrast to the binomial logistic regression. Here, we use the softmax function instead of the sigmoid function for some reasons:
  o	Sigmoid function compresses data significantly leading to data loss of more layers are present in the model. It also has a short range (0 and 1) or (-1 and +1)
  o	Probabilities produced by the sigmoid function are not constrained to sum to 1 as it looks at each raw data value separately.
  o	It is used for binomial logistic regression while softmax activation function is used for multinomial as it ensures that the probabilities sum up to 1, allowing us to      interpret the outputs as class probabilities. i.e is probability of one class increases, that of another class must decrease.
  
  
  
  
  KNN approach:
•	It is mainly used for pattern recognition, data mining, intrusion detection
•	It is a kind of supervised learning
•	It is a non-parametric supervised machine learning algorithm
•	Higher noise would imply higher value of k and usually odd k are selected to avoid ties in classification
•	Pandas is a library used for data manipulation and analysis.
•	Numpy provides support for large, multi-dimensional arrays 
•	Seaborn is a data visualization library based in matplotlib
•	Sklearn is an open-source machine learning library for python
•	After standardizing the features using ‘datasetX =   reprocessing.StandardScaler().fit_transform(X)’, we split the dataset into training data and testing data
•	We can find the most accurate value of k for maximum accuracy. But for this code, I’ve defined k as 3, while it can be varied 
•	We use distance metrics like Euclidian distance, Manhattan distance, hamming distance, minkowski distance
•	Then we chose the k nearest of neighbours of the new data point according to the calculated distance metric
•	Then we count the number of data points belonging to each category.
•	New data point is assigned to the category where we counted the most neighbours. 
•	


