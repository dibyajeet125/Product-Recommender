# Product-Recommender
Developed a product recommender system using sentiment analysis on Amazon's Home and Kitchen dataset (551,682 reviews), achieving 89.49% accuracy in predicting overall ratings. The system successfully identified 5 nearest neighbors for personalized product recommendations.


This project involves developing a Product Recommender System that leverages Sentiment Analysis to suggest products based on customer reviews. The system utilizes Amazon's Home and Kitchen reviews dataset, which contains 551,682 reviews.

Key Features:

Sentiment Analysis:

Implemented TF-IDF vectorization to convert review texts into numerical representations.

Trained a KNN classifier to predict overall ratings based on review sentiments, achieving an accuracy of 89.49% and a mean squared error of 0.105.

Recommender System:

Developed a KNN-based recommender system to suggest products based on review similarities.

Successfully identified the 5 nearest neighbors for each product, providing personalized recommendations.

Visualization:

Created word clouds to visualize common themes in reviews for different rating groups, enhancing understanding of customer sentiments.

Dataset Overview:

Dataset Size: 551,682 reviews

Variables: Reviewer ID, Product ID, Review Text, Overall Rating, Summary, Unix Review Time, Review Time, Helpful Rating

Project Structure:

Data Preprocessing: Cleaning and preprocessing of review data.

Sentiment Analysis: TF-IDF vectorization and KNN classification for sentiment analysis.

Recommender System: KNN-based product recommendation.

Visualization: Word cloud generation for review themes.

DATASET LINK: https://www.kaggle.com/datasets/nikhileshkos/home-kitchen-review-dataset
