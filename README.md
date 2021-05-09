# Recommendations with IBM

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name ='installation'></a>
Besides the libraries coming with Python 3.6 the following libraries had been included in this project:
* pandas
* numpy
* matplotlib
* progressbar

## Project Motivation <a name ='motivation'></a>
This project was initiated as part of my Udacity Data Science Nano Degree Course.

In this project a dataset from IBM Watson Studio platform was used to make recommendations to them. 
This project can be broken down into the following parts:

### 1. Exploratory Data Analysis
Via the EDA the data structure and the interdependencies between the raw data files had been analyzed. 
### 2. Rank Based Recommendations
Based on the interactions with the articles a ranking had been created to use as one recommendation method. 
### 3. User-User Based Collaborative Filtering
By measuring the similarity of the users to each others a recommendation system based on the articles interactions with more similar users had been created. 
### 4. Content Based Recommendations (EXTRA - NOT REQUIRED)
As this task is not required for the project submission, this task has not been executed. 
### 5. Matrix Factorization
Using Single Value Decomposition (SVD) an recommendation system has been created. Based on the data structure and given the fact, that there was hardly overlap of users between train and test dataset, this recommender system might not result a practical significant improvement. 

## File Descriptions <a name ='files'></a>
* Recommendations_with_IBM.ipynb
This is the project file, where the analysis had been performed
* Recommendations_with_IBM.html
This is an html export of the project ipynb-file
* project_tests.py, top_5.p, top_10.p, top_20.p
These files includes the test mechanisms used in the project notebook created by Udacity
* user_item_matrix.p
This file is a copy of the user_item matrix created within this notebook.

## Licensing, Authors, and Acknowledgements <a name ='licensing'></a>
I am grateful for the opportunity testing my knowledge within this challenging project provided by Udacity and IBM. For anyone I was able to inspire by my code, feel free to use the code here as you would like!
