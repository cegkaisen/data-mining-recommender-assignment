# Movie Recommender System - Data Mining Assignment

This project was developed for the Data Mining course.  
I built a movie recommendation system using collaborative filtering methods.

## Methods Used
- User-Based Collaborative Filtering (KNNBasic)
- Matrix Factorization (SVD)

## Evaluation Metrics
- RMSE (Root Mean Squared Error)
- Precision@10
- Recall@10

## Cold-Start Problem
Some users in the test set had no rating history.  
For these users, I used a popularity-based recommendation method by recommending movies with high average rating and enough number of ratings.

## Project Structure

data/ → Dataset files
notebooks/ → Jupyter Notebook (main code)
output/ → Generated recommendation files

## How to Run
The notebook is structured using a task runner.  
Each part of the project can be run independently by setting a task variable to `True` in the Task Runner section.

## Output Files
- `ratings_test_filled.csv` → Submission file
- `recommendations_readable.csv` → Recommendations with movie titles