# Food Recommendation System Project

This project aims to build a recommender system using the Food.com Recipes and Reviews dataset. The dataset contains user reviews. The goal is to analyze the data, understand its characteristics, and develop a system that can recommend recipes to users based on their preferences.

## Project Steps
1. **Data Loading:** Get the dataset from Kaggle: [Food.com - Recipes and Reviews](https://www.kaggle.com/datasets/irkaal/foodcom-recipes-and-reviews) and generate train and test sets
1. **Data Analysis:** Explore the dataset to understand its structure, user and item statistics, sparsity, and the type of feedback provided.
2. **Modeling:** Build and evaluate different recommendation algorithms.
3. **Evaluation:** Assess the performance of the recommender system using appropriate metrics.

# Project Structure

Here is the repository structure and the purpose of the main files:

- `data/`: Contains datasets (raw, cleaned, train/test splits).
  - `recipes.csv`, `recipes.parquet`: Recipe data.
  - `reviews.csv`, `reviews.parquet`: User review data.
  - `clean_reviews.csv`, `filtered_clean_reviews.csv`: Cleaned/filtered versions of the reviews.
  - `train_reviews.csv`, `test_reviews.csv`: Training and test sets for reviews.
- `data_getter.ipynb`: Downloading and initial preparation of the data.
- `data_loader.ipynb`: Loading and preprocessing data for analysis and modeling.
- `data_analysis.ipynb`: Exploratory data analysis (statistics, visualizations, etc.).
- `User-based Collaborative Filtering.ipynb`: Implementation and evaluation of a user-based collaborative filtering algorithm.
- `README.md`: Project overview, steps, and structure.
- `LICENSE`: Project license.