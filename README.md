
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
- SciPy: implements computations and optimization using NumPy’s functionality
- Skit-learn: simple tools for predictive analytics and modeling
- Tensorflow:  modeling and deployment of ML algorithms
- Nltk: tool for text processing
- Pytorch: o machine learning library used for developing and training neural network

*Pandas data structures*   
- DataFrame: 2-dimensional structure which can reference by column or row.  
- Series: 1-dimensional array. Represents a single column. 

A DataFrame is a collection of Series. 
Possible datatypes for a column in a DataFrame: int,float, datetime, bool, category. To the common types it is added the 'category' type, which represents different values for the classes.  

## Environment
Jupyter Notebook is used for the execution of the examples. 
You can create a virtualenv with all the necessary dependencies executing the following commands.  
```console
virtualenv -p python3 ml-training  
cd ml-training  
source bin/activate  
pip3 install -r requirements.txt   
jupyter notebook   
```
If you want to close the environment execute: 
```console
deactivate
```

## Data cleaning
This is an example to apply data cleaning techniques. The main objective is to prepare the data to apply a prediction over the sales variable. 
Dataset: https://www.kaggle.com/kyanyoga/sample-sales-data/data. 
It is important to notice that it might not be the only way of cleaning the data. It will depend on the needs and the meaning of each variable for your analysis.
The notebook for tis example is *data_cleaning.ipynb*.  

## Data visualization  
Several visualization methods are used in order to ilustrate examples of how to show results and analyze the data available. In this way it is easier to understand the data and the graphs can also help you to explain and support your assumptions. 

## Linear Regression
This example uses the dataset from the cleaning process, which contains information about Sales. An example of linear regression is provided in order to predict the sales. In the notebook *linear_regression.ipynb* you will find the excecution of the example and the comparation between the predicted and real values of the sales variable. 

## Classification  
This examples uses the dataset which is output of the data cleaning process. This notebook *classification_example.ipynb* contains models of classification. The main idea is to classify the Sales according to DEALSIZE variable. 

## Clustering
Some clustering methods are executed over a dataset for the Corruption Perception Index to see how countries are grouped according this index. You can find the data in gapminder website: https://www.gapminder.org/data/. This dataset is very simple, but the examples are just to get an idea of how the methods are used. Of course it gets more interestiong when you have more variables!.   
The notebook with the examples is *clustering_example.ipynb*.

## Neural Network
Neural networks have many applications. Different application of neural networks are shown in these examples. One of the dataset used is the output from the cleaning process. The notebook in this case is *neural_network_example.ipynb*.

## Dimension Reduction  
An example for dimension reduction is provided, appling Principal Components Analysis. It is explained how to choose the number of components and how to interpret the results. In order to better understanding of the results some graphs can be donde. The notebook for this example is *dimension_reduction.ipynb*. The dataset can be found in https://www.kaggle.com/unsdsn/world-happiness.
Another example using digits data is presented, applying TSNE to visualize high dimensional data into a 2-dimensional graph.   


## Recommendation system
An example for recommendation system is provided for content-based filtering. You can download the data from https://s3-api.us-geo.objectstorage.softlayer.net/cf-courses-data/CognitiveClass/ML0101ENv3/labs/moviedataset.zip. 



