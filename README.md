# Book-Recommendation-System

 ## Abstract 

  In this project, we proposed a Item-Based collaborative-filtering "Books Recommendation System" using the Kaggle dataset. The goal of this recommendation project is to provide the top 5 books which are similar to the particular book using Item-Based CF, KNNBasics, and SVD. Measure of the Similarity used in this project are Cosine similarity, Manhattan distances, and Euclidean distances. Further, to evaluate the models used in this project are RMSE and MAE. 
  The project involves several stages including data preprocessing, feature extraction, similarity calculation, recommendation generation, and performance evaluation. Python programming language, Jupyter Notebook, and relevant libraries such as pandas, numpy, surprise and scikit-learn are utilized for implementing the recommendation system.


### Goal of the project

The goal of the project is to develop a collaborative recommendation system by merging these datasets. The project aims to create a system that can recommend books to users based on the items themselves. 
By analyzing the features such as Book-Title, Book-Author, Book-Rating, and other features available in the book dataset : 
 - Recommend books to the specific user
 - Recommend books based on similarity measures.

The key objectives of the project include:

<b>Data Exploration:</b> Conduct an in-depth analysis of the book dataset to understand its structure, features, and relationships between different attributes.

<b>Feature Extraction:</b> Extract relevant information from the dataset, including Age, Book-Title, Location, user-ratings, and Year-of-publication, to build a comprehensive representation of books.

<b>Algorithms</b> In this project, we have used KNNbasic and SVD for recommending the items. For KNNbasic - Basic KNN, Pearson Correlation, Pearson-Baseline Correlation these parameters are used.

<b>Similarity Calculation:</b> We implemented an Item-User matrix to calculate similarities to find the similar books. Similarity measures such as cosine similarities, Manhattan and euclidean distances are used.

<b>Recommendation Generation:</b> Implement the recommendation algorithm that utilizes the Item-based CF approach to generate personalized recommendations for users and find similar books. The system will consider the user's profile and the similarity between items to suggest relevant books that match their interests.

<b>Evaluation:</b> Different evaluation metrics are used such as - Root Mean Square Error(RMSE) and Mean Absolute Error(MAE)


    
