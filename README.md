
# Data Science in practice
Let’s get the hands dirty and put the theory in practice. Let yourself to explore and go further than the examples. 
These examples are just the tip of the iceberg!. In general in the examples provided in this guide the focus is not the performance of the algorith (if it predicts well or not), instead the goal is to show simple applications of each of the algorithms to get a general idea about how appling each tecnique. 

## Languages 
R, python and Scala are the most common languages used for data science and machine learning. Depending on the problem that you are trying to resolve, which one is the best to use. 
While R is good for visualization and data anylisis, Python is better for implementing machine learning algorithms since there are several libraries and it performs better. Scala is used for Big Data applications, for larger datasets, are good for parallel processing in a cluster. In this tutorial we will be using Python, since it is easy to understand and we will be handle small datasets, and performing different models with them.    

## Python Libraries
Here are mentioned the most common python libraries for data science.
- Pandas: provides easy-to-use data structures and data analysis tools 
- Numpy: it is used mostly for N-dimensional arrays and algebra functions
- Skit-learn: simple tools for predictive analytics and modeling
- Tensorflow:  modeling and deployment of ML algorithms
- Nltk: tool for text processing.

*Pandas data structures*   
- DataFrame: 2-dimensional structure which can reference by column or row.  
- Series: 1-dimensional array. Represents a single column. 

A DataFrame is a collection of Series. 
Possible datatypes for a column in a DataFrame: int,float, datetime, bool, category. To the common types it is added the 'category' type, which represents different values for the classes.  


## Data cleaning
This is an example to apply data cleaning techniques. The main objective is to prepare the data to apply a prediction over the sales variable. 
Dataset: https://www.kaggle.com/kyanyoga/sample-sales-data/data. 
It is important to notice that it might not be the only way of cleaning the data. It will depend on the needs and the meaning of each variable for your analysis.
The notebook for tis example is *data_cleaning.ipynb*.  

## Data visualization  
Several visualization methods are used in order to ilustrate examples of how to show results and analyze the data available. In this way it is easier to understand the data and the graphs can also help you to explain and support your assumptions. 

## Linear Regression
This example uses a datasets of information about Sales and a example of linear regression is provided in order to predict the sales. In the notebook *linear_regression.ipynb* you will find the excecution of the example and the comparation between the predicted and real values of the sales variable. 


## Clustering
Some clustering methods are executed over a dataset for the Corruption Perception Index to see how countries are grouped according this index. This dataset is very simple, but the examples are just to get an idea of how the methods are used. Of course it gets more interestiong when you have more variables!.   
The notebook with the examples is *clustering_example.ipynb*.

## Neural Network
Neural networks have many applications. Different application of neural networks are shown in these examples. 
The notebook in this case is *neural_network_example.ipynb*.

## Dimension Reduction  
An example for dimension reduction is provided, appling Principal Components Analysis. It is explained how to choose the number of components and how to interpret the results. In order to better understanding of the results some graphs can be donde. The notebook for this example is *dimension_reduction.ipynb*.   

## Recommendation system
Examples for recommendation system is provided, one for content-based filtering and another for collaborative filtering. 





