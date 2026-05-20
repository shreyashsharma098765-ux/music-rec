# Music Recommendation System 🎵

This project is a Machine Learning-based Music Recommendation System that recommends songs similar to the user's selected music.

## Project Overview

The recommendation system uses **TF-IDF Vectorization** and similarity-based techniques to suggest songs based on music features and metadata.

The model processes song data, converts text information into numerical vectors, and recommends the most relevant songs using similarity matching.

## File Descriptions

* **main.py**
  Main application file used to run the recommendation system.

* **recommend.py**
  Contains the recommendation logic and similarity calculation functions.

* **preprocess.py**
  Handles data cleaning and preprocessing before model training.

* **df_cleaned.pkl**
  Stores the cleaned dataset used for recommendations.

* **tfidf_matrix.pkl**
  Contains the TF-IDF vectorized matrix generated from the dataset.

* **spotify_millsongdata.csv**
  Original dataset containing song information and lyrics.

* **recommend.log**
  Stores logs generated during recommendation execution and debugging.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* TF-IDF Vectorizer

## Features

* Song recommendation based on similarity
* Text preprocessing and cleaning
* TF-IDF vectorization
* Fast recommendation generation

## How to Run the Project

1. Install the required libraries:

```bash id="b2f9q1"
pip install -r requirements.txt
```

2. Run the project:

```bash id="w91kz3"
python main.py
```

## Future Improvements

* Add a Streamlit frontend UI
* Deploy the project online
* Add Spotify API integration
* Improve recommendation accuracy

---

⭐ If you like this project, consider giving it a star on GitHub!



RECOMMENDS SIMILAR SONGS WHILE SEARCHING

<img width="1918" height="1077" alt="image" src="https://github.com/user-attachments/assets/c8f765e8-76ea-4ceb-99be-b95367502e6f" />


RECOMMENDING 5 SIMILAR SONGS RELATED TO THE SEARCHED SONG 


<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/03cc0a61-44d6-42ff-bf98-1736b7fbe7b2" />
