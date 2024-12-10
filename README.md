# Book-Recommendation-System

 ## Abstract 

  In this project, I proposed a Item-Based collaborative-filtering "Books Recommendation System" using the Kaggle dataset. The goal of this recommendation project is to provide the top 5 books which are similar to the particular book using Item-Based CF, KNNBasics, and SVD. Measure of the Similarity used in this project are Cosine similarity, Manhattan distances, and Euclidean distances. Further, to evaluate the models used in this project are RMSE and MAE. 
  The project involves several stages including data preprocessing, feature extraction, similarity calculation, recommendation generation, and performance evaluation. Python programming language, Jupyter Notebook, and relevant libraries such as pandas, numpy, surprise and scikit-learn are utilized for implementing the recommendation system.


### Goal of the project

The goal of the project is to develop a collaborative recommendation system by merging these datasets. The project aims to create a system that can recommend books to users based on the items themselves. 
By analyzing the features such as Book-Title, Book-Author, Book-Rating, and other features available in the book dataset : 
 - Recommend books to the specific user
 - Recommend books based on similarity measures.

# Introduction about the data

We chose this book dataset: https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset/data

## Dataset
I took the dataset from the Kaggle which consists of the 3 files. 
    1. Users - User-ID, Location, Age
    2. Books - ISBN, Book-Title, Book-Author, Year-Of-Publication, Publisher, Image-URL-S, Image-URL-M, Image-URL-L
    3. Ratings - User-ID, ISBN, Book-Rat803X4

The key objectives of the project include:


## Data Pipeline

The Data Pipeline Involves :

<b>Data Loading:</b>  We loaded the files and converted them to pandas dataframe. <br> 
    -User dataset - 278858 rows<br>
    -Ratings - 1149780 rows<br>
    -Books - 271360 rows

<b>Data Cleaning:</b> A lot of missing values in the Age column (40%), have been changed to the median value because of the data was skewed. 
column name - Year-of-publication column datatype has been changed to the int type. The Location column have changed to the city and country columns. 2 columns have been removed from dataframe Image-URL-M, Image-URL-L. 

<b>Data Exploration:</b> Conduct an in-depth analysis of the book dataset to understand its structure, features, and relationships between different attributes.

<b>Data Exploration and Visualization:</b> For visualization we used plotly library for getting insights about the features using histogram, pie chart and bar chart

<b>Building Recommendation System:</b> KNNbasic and SVD.

<b>Feature Extraction:</b> Extract relevant information from the dataset, including Age, Book-Title, Location, user-ratings, and Year-of-publication, to build a comprehensive representation of books.

<b>Algorithms</b> In this project, I have used KNNbasic and SVD for recommending the items. For KNNbasic - Basic KNN, Pearson Correlation, Pearson-Baseline Correlation these parameters are used.

<b>Similarity Calculation:</b> I implemented an Item-User matrix to calculate similarities to find the similar books. Similarity measures such as cosine similarities, Manhattan and euclidean distances are used.

<b>Recommendation Generation:</b> Implement the recommendation algorithm that utilizes the Item-based CF approach to generate personalized recommendations for users and find similar books. The system will consider the user's profile and the similarity between items to suggest relevant books that match their interests.

<b>Evaluation:</b> Different evaluation metrics are used such as - Root Mean Square Error(RMSE) and Mean Absolute Error(MAE)


    
