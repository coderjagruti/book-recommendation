# Book Recommender System

This is a **machine learning project** that implements a collaborative filtering-based book recommender system. The project helps users find books similar to their favorites by analyzing user-book ratings and making personalized recommendations.

## Demo

- The web app displays the top-50 most popular books (based on average rating with at least 250 votes).
- Users can enter the name of a book and get a list of similar recommended books.

## Features

- Popularity-based recommendations
- Collaborative filtering for personalized suggestions
- Simple web interface for user queries

## Dataset

- The system uses the [Book Recommendation Dataset](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset)

  - These three files are required:
    - `Books.csv`: Book metadata
    - `Users.csv`: User information
    - `Ratings.csv`: User-book ratings

## How to Run

1. Clone this repository.
2. Download the dataset from Kaggle and place the files in the project directory.
3. Install required dependencies:
4. Run the notebook or main script:
5. For the web app:

## Requirements

- Python 3.x
- pandas, numpy, scikit-learn, streamlit, etc.
- See `requirements.txt` for full list.

## Project Structure

├── app.py                  # Streamlit web app ├── Book-Recommender.ipynb  # Jupyter notebook with step-by-step walkthrough ├── data/                   # Folder containing dataset files │   ├── Books.csv │   ├── Users.csv │   └── Ratings.csv ├── requirements.txt        # Python dependencies ├── README.md └── .gitignore

## Deployment

-  deployed to Heroku.


## License

MIT
