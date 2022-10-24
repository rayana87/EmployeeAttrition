# EmployeeAttrition

### Introduction
Machine Learning (ML) has the ability to explore the algorithms that can learn from and make predictions on a given data. Organizations, due to their strategic demands, invest much time and effort in workforce hiring. When employee’s attrition, the companies not only lose a productive staff member but also the resources and funds, in particular, the efforts of HR staff by hiring and selecting certain staff members and training them for their related tasks is invested in them. 

##### This work considers the prediction and analysis of employee attrition using Machine Learning models. Applying on IBM dataset, five main tests were conducted to predict employee attrition using classifiers such as KNN, SVM, DT, RF classifiers, and Multilayer Perceptron (MLP). 

### Algorithms
* The KNN algorithm scans the TR set for the K nearest samples for each sample X_test in the TS set. As a result, the KNN computes the distances between X_test and all of TR's samples using Euclidean distance which is the most common measure for this purpose or Manhattan distance. The k value chosen can have an effect on the technique's efficiency and noise tolerance.

* SVM: by changing the distance between the data points, creating a hyper-plane that will isolate the classes as far as possible. Suppose N is the total number of vectors given separable sample sets (x_i,y_i),1≤i≤N as training samples. The input vectors x_i are the training vectors, and D is the input space dimension where x_i∈R D. The hyperplane separation using the equation w. x + b = 0, where w represents the weight in the vector, the dot (.) represent the inner product in the vector, and the bias expression is denoted by the letter b.
* The Decision Tree reaches a high level of performance with minimal effort and time. Decision trees are a type of data mining methods that incorporates mathematical and computational techniques to help in the classification, categorization, and generalization of a collection of data. Creating  a Decision Tree in which each data point is assigned a class attribute. Through breaking the source set into subsets based on an attribute value test, a tree could " learned ". This process is repeating on each subset recursively, and this process known as a Recursive partitioning.
* The Random Forest similar to Decision Trees. It generates a forest of trees, with each tree being made up of a random collection of features from the total set. A decrease of variation can be achieved by averaging these uncorrelated trees, making the final result less complex and more stable. 
* The Neural Network (NN) is a basic form of Artificial Neural Network (ANN) that is inspired by the human brain and consists of signal processing nodes, where these nodes are connected to one another. One of the most basic NN topology is Multi-Layer Perceptron (MLP). Each artificial neuron could have a range of inputs as well as a single output.
 
### Dataset
The dataset provided by Kaggle’s website can be founded on the following link:  kaggle.com/colara/human-resource.
There are 14,999 samples in this dataset, with ten features (6 integer, 2 floats, and 2 objects). There are no null/missing values in any variable column.

The dataset was tested on random examples for unknown cases. Then, increasing the size of the minority class while decreasing the size of the majority class. 

### The file with named "Employees behaviour analysis based on Random forest and Decision Tree":
Contain data visualization and analysis to enable further analysis, we have to determine what factors/features have the greatest impact on our target (Attrition), what features have deep correlations to one another, as well as a deep examination of these features. By using a decision tree classifier, it could rank the features used for the prediction and choose the top three features. This is helpful in creating our model for logistic regression because it’ll be more interpretable to understand what goes into our model when we utilize less features.
Then, evaluating the models, not only based on accuracy have to know the different errors that we care about and correct decisions, due to the imbalance of the classes. Accuracy alone does not measure an important concept that needs to be taken into consideration in this type of evaluation: False Positive and False Negative errors. 



