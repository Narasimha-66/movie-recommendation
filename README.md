Movie Recommendation System
  This is a simple movie recommendation system built using python, developed in Google colab.
  It recommends similar based on the users input using "Content-based filtering".

Features:
  Accepts user input for a movie title.
  Uses 'difflib.get_close_matches()' to find matching movie names.
  Calculates similarity using cosine similarity.
  Recommends top similar movies based on descriptions or genre.
  
How it works:
  1. Load and preprocess the dataset
  2. Transform movie descriptions into feature vectors using 'TfidfVectorizer'
  3. Compute cosine similarity between all movies
  4. Match user input with movie titles using 'difflib'
  5. Return top N most similar movies

Files:
  'movierecommendation.ipynb': Main notebook containing the code
  'ReadMe.md': This file

Contact:
   Author: Narasimha Jaladurgam
   Github: [Narasimha-66](https://github.com/Narasimha-66)

