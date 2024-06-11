# Recommendations Engine Project

This project aims to analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles

![image](https://github.com/cris-scheib/recommendations-engine/assets/61483993/9935900a-744c-474d-8695-0f6bffe398de)

-----------------------------------

1. [Installation](#installation)
2. [Project structure](#structure)
3. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
No installation, this code should run with no issues using Anaconda distribution of Python.
 
## Project structure <a name="structure"></a>

I. [Exploratory Data Analysis](#Exploratory-Data-Analysis)<br>
Before making recommendations of any kind, we will need to explore the data we are working with for the project. 
Dive in to see what we can find. 
There are some basic, required questions to be answered about the data we are working with. 

II. [Rank Based Recommendations](#Rank)<br>
To get started in building recommendations, we will first find the most popular articles simply based on the most interactions. 
Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. 
These are then the articles we might recommend to new users (or anyone depending on what we know about them).

III. [User-User Based Collaborative Filtering](#User-User)<br>
In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. 
These items could then be recommended to the similar users. 
This would be a step in the right direction towards more personal recommendations for the users.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to IBM Watson Studio platform for the data. 
You can create your own account to become a part of their community and get a better understanding of their data [here](https://www.kaggle.com/stackoverflow/so-survey-2017/data).  
Otherwise, feel free to use the code here as you would like! 
