Developed a content-based song recommendation system using Spotify audio features to recommend five similar songs based on a selected track and artist.

Key work:
- Conducted exploratory data analysis on 5,000 Spotify songs, identifying missing values, duplicate records, categorical inconsistencies, and relationships among audio features.
- Preprocessed the dataset by handling missing values, removing duplicate songs, extracting album release years, and encoding multi-valued artist genres using binary encoding.
- Applied StandardScaler and RobustScaler to selected numerical features based on their distribution and skewness.
- Built a recommendation system using cosine similarity across song audio features, including danceability, energy, acousticness, instrumentalness, valence, tempo, and other musical characteristics.
- Implemented a Python recommendation function that accepts a song title and artist and returns the five most similar tracks.
- Tested the system with multiple songs to examine whether the generated recommendations aligned with the musical characteristics of the input tracks.
