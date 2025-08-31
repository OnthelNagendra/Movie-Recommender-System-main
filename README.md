#### Movie Recommender System

This project is a content-based movie recommendation system built using Python. It suggests movies to a user based on the similarity of a given movie's features, such as genre, keywords, cast, and crew. The model is trained and tested using the TMDb 5000 Movie Dataset.



###### Features

Content-Based Filtering: Recommends movies by analyzing the characteristics of a specific movie.



Data Processing: Cleans and preprocesses raw movie data to create a combined feature set.



Similarity Scoring: Uses cosine similarity to calculate a similarity score between movies based on their combined features.



###### Technologies Used

Python: The core programming language.



Jupyter Notebook: For interactive development and exploration of the data.



Pandas: For data manipulation and analysis.



NumPy: For numerical operations.



Scikit-learn: For machine learning functionalities, specifically CountVectorizer and cosine\_similarity.



NLTK: For text processing, including stemming.



###### Dataset

This project utilizes the TMDb 5000 Movie Dataset, which consists of two CSV files: tmdb\_5000\_movies.csv and tmdb\_5000\_credits.csv. These files contain detailed information about 5000 movies, including their budget, genres, cast, crew, and a brief overview.



###### Getting Started

Prerequisites

To run this project, you will need to have Python installed along with the following libraries:



###### Bash



pip install pandas numpy scikit-learn nltk ast

You'll also need to download the NLTK data for stemming:



###### Python



import nltk

nltk.download('punkt')

Installation

Clone the repository to your local machine:



###### Bash



git clone https://github.com/your-username/movie-recommender-system.git

cd movie-recommender-system

Place the tmdb\_5000\_movies.csv and tmdb\_5000\_credits.csv files into the project directory.



###### Run the Jupyter Notebook:



###### Bash



jupyter notebook movie-recommender-system.ipynb

Usage

Open and run the cells in the movie-recommender-system.ipynb notebook to see how the data is processed and how the recommendation function is implemented. You can use the recommend() function at the end of the notebook to get recommendations for any movie in the dataset.

