# Wireless Indoor Localization
The Wireless Indoor Localization problem comprises of using WiFi signal strengths to determine the indoor location of a user. The Wireless Indoor Localization data set consists of WiFi signals from an indoor WiFi system that has 7 WiFi routers at various locations. Our goal with this dataset is to predict the location of a user who is in one of four rooms based on the WiFi signal strength received from the 7 routers. The dataset consists of measured signal strength (dB, integers) at 7 wireless sensors (WS1-WS7) and the user location. Thus, there are 7 input variables (features) and 4 classes (user locations). We employ the Wireless Indoor Localization data set to predict the location of a user who is in one of four rooms based on the WiFi signal strength received from seven routers. 
Refer 'data' folder to get the train and test datasets.

# Implementation
Implemented seven classification techniques - Naïve Bayes Classifier, Logistic Regression, Support Vector Machine(SVM), XGBoost, K-Nearest Neighbors, Random Forest and Multi-Layer Perceptron(MLP) classifier models. For each of these models, different hyper parameters are applied using GridSearchCV and the best hyper parameters are selected. 

# Feature Engineering
New features are created and then the best are used for training, validation and testing purposes.

# Results 
Note: Training and Validation split is kept 90 is to 10. And a different dataframe for testing.
The performance of these classifiers are compared by analyzing metrics such as training accuracy, validation accuracy and mean cross validation accuracy. Results were visualized using the confusion matrix for each classifier result. The model with the highest mean cross validation accuracy in each approach was chosen as the final system to classify the test-set samples. 



