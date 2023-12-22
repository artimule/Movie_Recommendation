
![Screenshot 2023-09-17 175155](https://github.com/Artimule/Movie_Recommendation/assets/53312100/c6da4891-07c1-4955-b00c-acb488f3eed7)
# Movie Recommender System

## Overview
This Movie Recommender System is built using Streamlit and recommends movies based on similarity scores. It utilizes the [TMDB (The Movie Database) API](https://www.themoviedb.org/documentation/api) to fetch movie details and posters.

## Features
- **Recommendation Algorithm**: The system uses a similarity matrix to recommend movies similar to the user's selection.
- **Interactive UI**: Built with Streamlit, providing an interactive user interface for selecting and viewing movie recommendations.
- **Movie Posters**: Fetches movie posters using the TMDB API to enhance the visual experience.

## How to Use
1. Select or type a movie title from the dropdown menu.
2. Click the "Show Recommendation" button to view recommended movies.
3. Explore the recommended movies with their titles and posters.

## Files
- `movie_list.pkl`: Pickled file containing a list of movies.
- `similarity.pkl`: Pickled file containing the similarity matrix.

## Requirements
- Python
- Streamlit
- Requests

## Usage
1. Install the required dependencies:
    ```bash
    pip install streamlit requests
    ```
2. Run the Streamlit app:
    ```bash
    streamlit run your_script_name.py
    ```

## Sample Output
![Movie Recommender System](sample_output.png)

## Acknowledgments
- Movie data is fetched from the [TMDB API](https://www.themoviedb.org/documentation/api).
- Similarity scores are calculated using a precomputed similarity matrix.

Feel free to customize this README according to your specific needs and provide any additional details that may be helpful for users.
