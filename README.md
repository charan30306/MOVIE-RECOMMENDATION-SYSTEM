# MOVIE-RECOMMENDATION-SYSTEM
## Overview
This project implements a Movie Recommendation System using Collaborative Filtering and Singular Value Decomposition (SVD). The model learns hidden patterns in user rating behavior and recommends movies based on predicted user preferences.

## Features
- User-based movie recommendations
- Collaborative filtering using SVD
- Rating prediction for unseen movies
- Top-N movie recommendations
- Model evaluation using RMSE
- Exploratory Data Analysis (EDA)

## Dataset
The project uses the MovieLens dataset containing:
- Movies information (titles and genres)
- User ratings
- User-movie interactions

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Methodology
1. Load and preprocess movie and rating datasets.
2. Create a user-movie rating matrix.
3. Apply Truncated Singular Value Decomposition (SVD) for dimensionality reduction.
4. Reconstruct the rating matrix to predict missing ratings.
5. Generate personalized movie recommendations.
6. Evaluate model performance using RMSE.

## Results
The system successfully predicts user preferences and recommends movies that users are likely to enjoy based on historical rating patterns.

## Project Structure
```
├── movies.csv
├── ratings.csv
├── movie_recommendation.ipynb
├── requirements.txt
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/movie-recommendation-system.git
cd movie-recommendation-system
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Run the Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```bash
movie_recommendation.ipynb
```

and execute all cells to train the model and generate recommendations.

## Future Improvements
- Hybrid recommendation system using genres and ratings
- Deep learning-based recommendation models
- Web application deployment
- Real-time recommendation updates

## Author
Charan Reddy Padala
