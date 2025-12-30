# Movie Recommendation System  
**Item-Based Collaborative Filtering**

## Overview
Built an item-based movie recommendation system that suggests similar movies based on how users rate them. Created a user–movie interaction matrix and used cosine similarity to measure how closely movies are related.

Worked with real-world datasets using **Pandas and NumPy**, handled missing values in sparse rating data, and ranked movies based on similarity scores. The system returns top-N movie recommendations for a selected title, similar to techniques used by platforms like Netflix.

This project highlights hands-on experience with **collaborative filtering, data preprocessing, similarity metrics, and recommendation system design**, with opportunities for future improvements such as user-based recommendations and performance optimization.

## How It Works
- Loads movie metadata and user rating data  
- Builds a user–movie interaction matrix  
- Computes cosine similarity between movie vectors  
- Ranks and returns top-N similar movies for a given title  

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Item-Based Collaborative Filtering  
- Cosine Similarity

## Dataset
- MovieLens dataset ('movies.csv', 'ratings.csv')

## Future Improvements
- Implement user-based collaborative filtering  
- Normalize ratings to reduce user bias  
- Optimize similarity computation using vectorized operations  
