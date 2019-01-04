# Machine-Learning-Programming-Assignment-1

K-Nearest-Neighbour-using-MNIST-Dataset:

K Nearest neighbors is method for classification and regression process. An object is to classify by a majority of its neighbors. 
For example for K=1 the object assign to the class of that single nearest neighbor. 
For K=3 class is assigned based on majority of label. 
Choice of K depends on the data.


Pseudo Code for KNN:
euclideanDistance (train_final, test_final, length){
#finding Euclidean distance
}
getNeighbour(entire train data, one row of test data, passing k) {
#Finding Euclidean distance with of one test data with train data.
#Computing Euclidean distance (train_final,test_final,length)
# Selecting minimum value distance.
}
accuracy(passing test data result_test ,prediction obtained){
#Finding accuracy based on predicted neighbors.
}
getResponse(neighbors){
#Finding neighbors which occurs maximum time.
}
Main() {
# Read training and test data from MNIST dataset.
# Modifying train and test data by converting to integers values.
For (int i = 0 to I = 10000){
# Finding neighbors
neighbors = getNeighbour (entire train data, one row of test data, passing k)
#Checking neighbors
result = getResponse( neighbors)
}
#finding accuracy
accuracy1 =accuracy(passing test data result_test ,prediction obtained)
}
KNN Accuracy: 96.88%
