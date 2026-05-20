Music Recommendation System 🎵

This project is a Machine Learning-based Music Recommendation System that recommends songs similar to the user's selected music.

Project Overview

The recommendation system uses TF-IDF Vectorization and similarity-based techniques to recommend songs based on music metadata and text features.

A simple and interactive frontend has been built using Streamlit to allow users to search songs and get recommendations instantly.

File Descriptions
main.py
Contains the Streamlit frontend application used to run the recommendation system.
recommend.py
Contains the recommendation logic and similarity calculation functions.
preprocess.py
Handles data cleaning and preprocessing of the dataset.
df_cleaned.pkl
Stores the cleaned and processed dataset.
tfidf_matrix.pkl
Contains the TF-IDF vectorized matrix used for similarity matching.
spotify_millsongdata.csv
Original dataset containing song and lyrics information.
recommend.log
Stores logs generated while running the recommendation system.
Technologies Used
Python
Streamlit
Pandas
NumPy
Scikit-learn
TF-IDF Vectorizer
Features
Music recommendation based on song similarity
Interactive Streamlit frontend
TF-IDF based recommendation engine
Fast and efficient recommendations
How to Run the Project
Install all required libraries:
pip install -r requirements.txt
Run the Streamlit application:
streamlit run main.py


RECOMMENDS SIMILAR SONGS WHILE SEARCHING

<img width="1918" height="1077" alt="image" src="https://github.com/user-attachments/assets/c8f765e8-76ea-4ceb-99be-b95367502e6f" />


RECOMMENDING 5 SIMILAR SONGS RELATED TO THE SEARCHED SONG 


<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/03cc0a61-44d6-42ff-bf98-1736b7fbe7b2" />
