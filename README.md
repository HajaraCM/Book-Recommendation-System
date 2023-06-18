# Book-Recommendation-System
Table of Content
* Introduction
* Problem Statement
* Dataset Information
* Tools and Technologies used
* Steps involved
* Approaches used
* Conclusion

##  Introduction
With an increasing amount of information on the internet and a considerable increase in the number of users, it is essential for companies to search, map, and offer relevant information based on the preferences of users. Aan important functional means of providing personalized service to users is Recommendation System. This system uses algorithms and data analysis techniques to suggest items,content, or services that should be of interest to customers based on their past choices or by analyzing the preferences of similar users. Companies like Netflix, Amazon, etc. use recommender systems to help their users to identify the correct product or content for them.

dart The main objective of this project is to create a Book recommendation system that best predicts user interests and recommend the suitable/appropriate books to them ,using various approaches.

## Problem Statement
In some industries, the use of recommender systems is crucial because, when implemented well, they can be extremely profitable and set themselves apart from their competitors. Online book selling websites nowadays are competing with each other by many means.One of the most effective strategies for increasing sales,enhancing customer experience and retaining customers is building an efficient Recommendation system. The book recommendation system must recommend books that are of interest to buyers. Popularity based approach and Collaborative filtering approach are used in this project to build book recommendation systems.

## Dataset information
Dataset used in this project is the Amazon Book-crossing dataset.This dataset has been compiled by Cai-Nicolas Ziegler in 2004, and it comprises of three file.They are:

Users

User-ID: A unique identification number for each user
Location:It contains city,state and country to which the user belongs ,separated by commas
Age:The age of the user
Books

ISBN:International Standard Book Number unique to each edition of the book
Book-Title:Title of the book
Book-Author:Author of the book(incase of several authors only the first is provided)
Year-of-Publication:The year in which the particular edition of the book was published
Publisher:Name of the Book Publishing company
Image-URL-S: URL link to a small version of the book cover displayed on the Amazon website
Image-URL-M: URL link to Medium version image of the book cover displayed on the Amazon website
Image-URL-L: URL link to Large sized image of the book cover displayed on the Amazon website
Ratings

User-ID:as mentioned above
ISBN:as mentioned above
Book-Rating: The rating given by the user (identified by User-ID) for the book (identified by ISBN). It is either explicit,expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit,expressed by 0.

## Tools and Technologies used
The programming language used in this project is Python . The following libraries were used for data analysis and data visualization and to build a classifier to predict the price range of mobile phones.

Pandas : For loading the dataset and performing data wrangling
Matplotlib: For data visualization.
Seaborn: For data visualization.
NumPy: For some math operations in predictions.
Statsmodels: For statistical computations
Sklearn: For the purpose of analysis,prediction and evaluation.
