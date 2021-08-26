# Installation
Spark Python API is used in code. To install PySpark run the following:

    pip install pyspark

All other libraries used in the code should be in Anaconda distribution of Python 3.8.
Jupyter notebook was run on Udacity workspace with Spark pre-installed. Output of the code may be different in other environments. 
# Project Motivation
In today's dynamic world, we are seeing a growing number of large data, and manipulate these large data on personal computer can be a problem due to lack of memory. This is a perfect opportunity to experiment Spark, a big data analytics tool, on a dataset of music streaming application. Churn rate is what most service businesses pay attention to, and this project analyzes user behaviors in the music streaming app, Sparkify, and build machine learning models to predict churn. 
# Dataset
Dataset is user activity log, which includes user information, browser, account level, location, song, artist, and timestamp. 
# File Descriptions
Sparkify.ipynb - Jupyter notebook that includes code, plots and outputs related to exploratory data analysis and steps in data preprocessing and machine learning model building. 

PageVisualization.PNG, StayChurn.PNG - plots for data visualizations

Sparkify.PNG - Sparkify logo
 # Statistical Models
 Logistic Regression, Random Forest, and Linear Support Vector
 # Result
 Findings of this project was published on Medium available [here](https://edwinhung.medium.com/predicting-churn-rate-on-a-music-streaming-example-sparkify-325caea280e9).
 
 Interesting insights about Sparkify user behavior were discovered in the analysis, including number of songs listened and roll advertistements shown to groups of users who stayed and churned. Three machine learning models implemented all achieved more than 83% accuracy on predicting churn. 
 # Acknowledgements
 This project is the capstone project in Udacity Data Scientist nanodegree with collaboration from Insight Data Science. Data is only available in workspace provided by Udacity.