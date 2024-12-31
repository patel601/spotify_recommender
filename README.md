# Spotify Recommender

This project is a music recommendation system that leverages Spotify's API to suggest songs based on user preferences.

## Features

- **User Authentication**: Authenticates users via Spotify's OAuth to access personalized data.
- **Data Retrieval**: Fetches user's top tracks and audio features using Spotify's API.
- **Recommendation Engine**: Analyzes user data to recommend similar tracks.

## Technologies Used

- **Programming Language**: Python
- **Data Analysis**: Pandas
- **Machine Learning**: Scikit-learn
- **API Interaction**: Spotipy (a lightweight Python library for the Spotify Web API)
- **Notebook Environment**: Jupyter Notebook

## Machine Learning Methods

- **K-Nearest Neighbors (KNN)**: Implemented to find songs similar to the user's top tracks based on audio features.

## Setup and Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/patel601/spotify_recommender.git

2. Install Dependencies: Ensure you have Python installed. Then, install the required packages:
   ```bash
    pip install pandas scikit-learn spotipy jupyter

3. Obtain Spotify API Credentials:

  - Create a Spotify Developer account.
  - Register an application to get your Client ID and Client Secret.
  - Set the redirect URI in your Spotify Developer Dashboard.

4. Run the Jupyter Notebook: Navigate to the project directory and start the Jupyter Notebook:
    ```bash
    jupyter notebook Spotify_Recommender.ipynb


5. Notes: 
  - Ensure that your Spotify account has sufficient listening history for accurate recommendations.
  - The quality of recommendations may improve with more user data and further tuning of the algorithm.
