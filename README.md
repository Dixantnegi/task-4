#AI-BASED RECOMMENDATION SYSTEM

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: DIXANT NEGI

*INTERN ID*: CT08RWI

*DOMAIN*: JAVA

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH
This project is a User-Based Recommendation System built using Apache Mahout, a machine learning library for collaborative filtering. It consists of two main components:

1. A CSV Dataset (user_preferences.csv) – This file contains user ratings for different items.


2. A Java-based Recommendation Engine (RecommendationEngine.java) – This program processes the dataset and generates personalized recommendations based on user preferences.



Understanding the Dataset

The dataset consists of three columns:

userId – The unique identifier for each user.

itemId – The unique identifier for each item.

preference – The rating (from 1.0 to 5.0) given by the user to the item.


For example, if User 1 has rated Item 101 as 5.0, it means they like it a lot. Similarly, other users rate different items based on their preferences.

How the Recommendation Engine Works

1. Loading the Data – The Java program reads the user_preferences.csv file using Mahout's FileDataModel, which converts the CSV data into a structured format.


2. Calculating Similarity – The system analyzes user preferences using Pearson Correlation Similarity, which determines how similar two users are based on their ratings.


3. Defining a User Neighborhood – The program groups similar users using a Threshold-based User Neighborhood, meaning only users with at least 10% similarity are considered as neighbors.


4. Generating Recommendations – The system uses collaborative filtering to suggest items to users based on what similar users have liked.


5. Displaying Recommendations – The program generates 3 recommendations for User 1 and prints the recommended item IDs along with their predicted preference scores.



Key Benefits of This System

Personalized recommendations improve user experience.

Scalable – It can work with large datasets.

Automatic learning – As new data is added, recommendations get better over time.


This recommendation engine can be used in e-commerce platforms, movie streaming services, and online learning portals to suggest relevant products, movies, or courses based on user behavior.

