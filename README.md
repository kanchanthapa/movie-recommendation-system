# Movie Recommendation System

This project is a Movie Recommendation System that uses two main techniques:

- **Content-Based Filtering**: Recommends movies by comparing features like genre, cast, and plot.
- **Collaborative Filtering**: Recommends movies by analyzing user preferences and behavior.

## Why This Project?

With so many movies available online, it's hard for users to decide what to watch. This system helps by giving personalized suggestions based on either the content of the movies or the behavior of similar users.

## Dataset

We use the [TMDB Movie Metadata](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata/data) from Kaggle, which includes information like movie titles, genres, overviews, cast, crew, and keywords.

## Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn
- NLTK
- Jupyter Notebook

## Project Structure

- **Content-Based Filtering**: Works with movie metadata to recommend similar movies.
- **Collaborative Filtering**: Works with user ratings to suggest movies liked by similar users.

Each approach is implemented in its own notebook for clarity.

## Getting Started

1. Clone the repository
2. Install the required libraries
3. Open the notebooks to explore recommendations

## Future Plans

- Combine both methods into a hybrid system
- Build a simple web interface
- Add live movie search and input features
