## Implementing of K-means for clustering from scratch and using Sklearn 

# Introduction
This is an implementation of K-means clustering algorithm using Scikit-learn, a popular machine learning library for Python. Scikit-learn provides an efficient implementation of K-means algorithm that can be easily used for clustering tasks.

# Files
k_means_sklearn.py: Python script that contains the implementation of K-means clustering algorithm using Scikit-learn.
data.csv: Sample dataset for clustering.
Dependencies
Python 3.x
Scikit-learn
Matplotlib
Usage
Clone the repository to your local machine.
Navigate to the repository directory.
Open the terminal and run the command python k_means_sklearn.py.
The script will load the sample dataset from data.csv and apply the K-means algorithm with K=3 using Scikit-learn.
The script will plot the resulting clusters and save the plot as output.png in the same directory.
Customization
You can customize the K-means algorithm by changing the following parameters in the k_means_sklearn.py file:

n_clusters: The number of clusters.
max_iter: The maximum number of iterations to perform.
tol: The tolerance for convergence.
Limitations
The limitations of the K-means algorithm using Scikit-learn are the same as those of the K-means algorithm from scratch. In addition, Scikit-learn has some limitations:

It requires the data to be in the form of a NumPy array or a Pandas dataframe.
It assumes that the number of clusters is known beforehand.
