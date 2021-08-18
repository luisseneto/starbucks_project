# Starbucks Capstone Challenge
[Udacity Machine Learning Engineer](https://www.udacity.com/course/machine-learning-engineer-nanodegree--nd009t)   

## Project Overview
This document has the purpose of offering a solution for the Starbucks Capstone Challenge. 
Starbucks is an American multinational company, with the largest chain of coffee shops in the world. 
For this project, was given a set of customer information that simulates the customer behavior on the 
Starbucks rewards mobile app. The mobile app has a feature that sends promotional offers or just 
advertisements to the clients, but they are categorized in 3 topics:
- Informational offer
- Discount offer
- Buy one get one free (BOGO) offer
  


## Problem Statement / Metrics 
Sending several offers to clients can be expensive when we don't know how our public behave. 
Basically we need to improve the way we communicate with our clients, by doing that, we can improve 
ROI (Return of Investment). Using information about demographics and transactions we can explore how the 
clients that respond to our campaigns usually behave and we can formulate better offers for the clients. 
Using a clustering model, we can identify patterns in the clients that convert to an offer, patterns that
we can’t identify just by observing in exploratory analysis. In this project, we are going to use the 
[K-Prototype](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.15.4028&rep=rep1&type=pdf) model 
and use the [elbow plot](https://en.wikipedia.org/wiki/Elbow_method_(clustering)) method to identify the best number of clusters 
(in our case, [personas](https://blog.hubspot.com/marketing/buyer-persona-definition-under-100-sr)).
  

## Results Summary
 
In this project, the objective is to do a first step on a advanced analysis in how the 
Starbucks customers behave under  

## Files  
- Starbucks_Capstone_notebook.ipynb  
  - [Jupyter notebook](https://jupyter.org/) that performs all the tasks described in the capstone proposal.
- proposal.pdf
  - Project description
- README.md  
  - [Markdown](https://guides.github.com/features/mastering-markdown/) file that summarizes this repository  
	
## Python Modules 
[Python Data Analysis Library](https://pandas.pydata.org/)  
[Numpy](http://www.numpy.org/)  
[Matplotlib](https://matplotlib.org/)  
[seaborn: Statistical Data Visualization](https://seaborn.pydata.org/)
[os — Miscellaneous operating system interfaces](https://docs.python.org/3/library/os.html)  
[scikit-learn: Machine Learning in Python](https://scikit-learn.org/stable/)  
[Joblib: running Python functions as pipeline jobs](https://joblib.readthedocs.io/en/latest/)  
[tqdm: A Fast, Extensible Progress Bar for Python](https://tqdm.github.io/)
[K-Protorypes](https://github.com/nicodv/kmodes)

  
## References
- [The k-prototype as Clustering Algorithm for Mixed Data Type (Categorical and Numerical)](https://towardsdatascience.com/the-k-prototype-as-clustering-algorithm-for-mixed-data-type-categorical-and-numerical-fe7c50538ebb)  
- [K-Prototypes - Customer Clustering with Mixed Data Types](https://antonsruberts.github.io/kproto-audience/)  
- [Marketing Analytics - What it is and why it matters](https://www.sas.com/en_us/insights/marketing/marketing-analytics.html)
- [Tutorial: How to determine the optimal number of clusters for k-means clustering](https://blog.cambridgespark.com/how-to-determine-the-optimal-number-of-clusters-for-k-means-clustering-14f27070048f)