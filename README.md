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

The main objective of this project is to create a Book recommendation system that best predicts user interests and recommend the suitable/appropriate books to them ,using various approaches.

![Screenshot_20230618_044311](https://github.com/HajaraCM/Book-Recommendation-System/assets/117503246/a5578499-9329-4cb3-9102-8e452e3af2a3)
![Screenshot_20230618_044428](https://github.com/HajaraCM/Book-Recommendation-System/assets/117503246/9c16b29a-2f83-4ec1-a84d-dd2cb500c28b)


## Problem Statement
In some industries, the use of recommender systems is crucial because, when implemented well, they can be extremely profitable and set themselves apart from their competitors. Online book selling websites nowadays are competing with each other by many means.One of the most effective strategies for increasing sales,enhancing customer experience and retaining customers is building an efficient Recommendation system. The book recommendation system must recommend books that are of interest to buyers. Popularity based approach and Collaborative filtering approach are used in this project to build book recommendation systems.

## Dataset information
Dataset used in this project is the Amazon Book-crossing dataset.This dataset has been compiled by Cai-Nicolas Ziegler in 2004, and it comprises of three file.They are:

**Users**

* User-ID: A unique identification number for each user
* Location:It contains city,state and country to which the user belongs ,separated by commas
* Age:The age of the user

**Books**

* ISBN:International Standard Book Number unique to each edition of the book
* Book-Title:Title of the book
* Book-Author:Author of the book(incase of several authors only the first is provided)
* Year-of-Publication:The year in which the particular edition of the book was published
* Publisher:Name of the Book Publishing company
* Image-URL-S: URL link to a small version of the book cover displayed on the Amazon website
* Image-URL-M: URL link to Medium version image of the book cover displayed on the Amazon website
* Image-URL-L: URL link to Large sized image of the book cover displayed on the Amazon website

**Ratings**

* User-ID:as mentioned above
* ISBN:as mentioned above
* Book-Rating: The rating given by the user (identified by User-ID) for the book (identified by ISBN). It is either explicit,expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit,expressed by 0.

## Tools and Technologies used
The programming language used in this project is Python . The following libraries were used for data analysis and data visualization and to build a classifier to predict the price range of mobile phones.

* **Pandas**: For loading the dataset and performing data wrangling
* **Matplotlib**: For data visualization.
* **Seaborn**: For data visualization.
* **NumPy**: For some math operations in predictions.
* **Statsmodels**: For statistical computations
* **Sklearn**: For the purpose of analysis,prediction and evaluation.

## Steps involved
* **Data Preprocessing** : Checked for outliers, incorrect values, missing values, duplicate, performed data type correction and string formatting.
* **Merging of datasets** : In this project, recommender systems were built utilizing only explicit ratings . So finally,a new dataframe by merging the books dataset ,explicit ratings dataset and users dataset.
* **Feature Extraction**: Created new columns such as age_group by binning the 'Age' column and extracted the country name from the 'Location' column .
* **Exploratory Data Analysis** : Performed Univariate, Bivariate, and Multivariate analysis with various graphs and plots to better understand the distribution of features and their relationships.
* **Implementation of  Recommender System**.

##  Approaches used
The approaches used in this project are:

* Popularity Based recommendation system
It is a type of recommendation system that bases choices on factors like popularity and/or current trends. These systems determine which item (in this case,books) are in the trending list or are the most well-liked by users and then directly recommend them.

* Collaborative Filitering Based recommendation system
The Collaborative Filtering approach first investigates the user’s behaviors, interests, and searches for similar users. It recommends items to users based on the ratings of similar users on various items and by predicting the missing ratings of the items.

## Conclusion
* The Lovely Bones: A Novel and Wild Animus are the two most read books.
* Stephen King is the most popular book author based on the number of ratings.
* Ballantine Books and Pocket are the top publishers based on the number of ratings that their books have received.
* The majority of readers are between the ages of 25 and 40.
* The majority of readers who have given the books ratings are from the United States and Canada.
* Regardless of the age group, The Lovely Bones and Wild Animus appear on lists of the top-rated books.
* Cosine similarity based recommendation system performs better at recommending books.
