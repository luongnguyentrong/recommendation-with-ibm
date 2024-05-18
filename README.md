# Recommendations with IBM Project (Udacity - Data Scientist Nanodegree Program)
## Table of Contents
1. [Introduction](https://github.com/louisteo9/recommendations-with-IBM#introduction)
2. [File Descriptions](https://github.com/louisteo9/recommendations-with-IBM#file-descriptions)
3. [Installation](https://github.com/louisteo9/recommendations-with-IBM#installation)
4. [Instructions](https://github.com/louisteo9/recommendations-with-IBM#instructions)
5. [Acknowledgements](https://github.com/louisteo9/recommendations-with-IBM#acknowledgements)

## Introduction
This project is part of the Udacity's Data Scientist Nanodegree Program in collaboration with IBM.

In this project, we will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles we think they will like. 

### Notebook Overview
The notebook in this project is divided into the following tasks:

#### i. Exploratory Data Analysis<br/>
Before recommending anything, we wil explore our dataset. We'll tackle some basic questions about the data, setting the stage for our recommendation system later on.

#### ii. Rank Based Recommendations<br/>
To begin, we'll identify the most popular articles solely based on interactions. Since we lack article ratings, we'll assume that articles with the highest interactions are the most popular. These will be our top recommendations for new users or anyone else based on their preferences.

#### iii. User-User Based Collaborative Filtering<br/>
To enhance recommendations on IBM's platform, we can identify users with similar interaction patterns and recommend items based on those patterns. This step will move us closer to providing personalized recommendations for users. We'll implement this next.

#### iV. Content Based Recommendations (EXTRA - not required for completing this project)<br/>
Not implemented

#### v. Matrix Factorization<br/>
Finally, we'll use machine learning to build recommendations. By decomposing user-item interactions, we'll assess our ability to predict new article interactions

## File Descriptions
**Recommendations_with_IBM.ipynb** - Jupyter Notebook for project<br/>
**project_test.py** - Python file contains solutions for test questions in the Jupyter Notebook.<br/>

**top_10.p** - P file contains top 10 articles.<br/>
**top_20.p** - P file contains top 20 articles.<br/> 
**top_5.p** - P file contains top 5 articles.<br/>
**user_item_matrix.p** - This is P file containing user item matrix that we will use to perform Singular Value Decomposition (SVD).<br/>

### Folder: data<br/>
**articles_community.csv** - articles available on the IBM platform<br/>
**user-item-interactions.csv** - list of articles that users interact with<br/>

## Installation
There should be no extra libraries required to install apart from those coming together with Anaconda distribution. There should be no issue to run the codes using Python 3.5 and above.

### Libraries Used
* Python 3.11 and above
* Pandas
* Numpy
* Matplotlib
* pickle
* RE
* NLTK
* Sklearn
* Jupyter

## Instructions
Run the codes inside Jupyter notebook to complete the project.

## Acknowledgements
* [Udacity](https://www.udacity.com/) for providing an excellent Data Scientist training program.
* [IBM](https://www.ibm.com/) for providing user interaction article dataset from IBM Watson Studio.
