# Music-Recommendation-System

A machine learning project that recommends music tracks based on their similarity using cosine similarity. This system processes and cleans a dataset of songs to build a content-based recommender model.

## Overview

This project implements a music recommendation system using Python. It takes a CSV file containing music data, pre-processes and cleans the dataset, and then calculates the cosine similarity between songs to recommend tracks that are similar to a user's input.

## Features

- **Data Pre-processing**: Load and clean music data from a CSV file.
- **Feature Extraction**: Extract relevant features necessary for computing similarity.
- **Cosine Similarity Calculation**: Compute similarity scores between songs.
- **Recommendation Engine**: Suggest similar songs based on the computed similarities.

## Dataset

Here's the link to the dataset:https://www.kaggle.com/datasets/notshrirang/spotify-million-song-dataset
The system uses a CSV file that includes details about various songs, such as:

- **Song Title**
- **Artist Name**
- **Song Lyrics**
- **Link**

## Technologies Used

- **Python 3**
- **Pandas** for data manipulation.
- **NumPy** for numerical computations.
- **Scikit-learn** for calculating cosine similarity.
- **Streamlit** for the frontend.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- Pip (Python package installer)
- Streamlit
- nltk
- spotipy
- pandas
- numpy
- scikit learn


## How It Works

1. **Data Loading and Cleaning**

   - The CSV file is read using Pandas.
   - Missing or irrelevant data is handled appropriately.
   - Data normalization is performed if necessary.

2. **Feature Extraction**

   - Select features that contribute to the similarity measure.
   - Create feature vectors for each song.

3. **Cosine Similarity Computation**

   - Calculate the cosine similarity between the feature vectors of songs.
   - Generate a similarity matrix.

4. **Generating Recommendations**

   - Upon receiving a song input from the user, locate it in the dataset.
   - Retrieve and sort the similarity scores.
   - Recommend the top N songs with the highest similarity scores.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements.
