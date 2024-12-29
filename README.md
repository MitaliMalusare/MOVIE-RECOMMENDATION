# MOVIE-RECOMMENDATION-SYSTEM

## Overview
This project focuses on building a movie recommendation system using Natural Language Processing (NLP) techniques. The goal is to suggest movies based on their similarity in features like plot, genre, and cast, ensuring personalized recommendations for users.

## Technology Used
We employed various techniques to process and prepare the data for recommendations:

1. **Data Cleaning:** 
   - Removed irrelevant information.
   - Handled missing values.
   - Ensured the data was ready for further processing.

2. **Combining Features:** 
   - Key features like movie descriptions, genres, and cast information were combined to form a single text-based feature for each movie.

3. **Stemming (PorterStemmer):** 
   - Used the PorterStemmer to normalize text data by reducing words to their root form, ensuring consistent analysis across word variations.

4. **Vectorization (CountVectorizer):** 
   - Converted textual features into numerical format using CountVectorizer.
   - Created a matrix of token counts, forming the basis for calculating similarity between movies.

## Calculating Similarity
- Calculated cosine similarity between the vector representations of the movies.
- This method determines how closely related two movies are based on shared features.
- Based on the computed similarity scores, movies with the highest similarity were selected as recommendations.

## Streamlit API Interface
To provide a user-friendly interface, we integrated Streamlit to build a simple API. Users can:
- Interact with the system.
- Explore movie recommendations.
- Receive movie suggestions based on the closest similarity to the selected movie.


![image](https://github.com/user-attachments/assets/96f13940-8e22-495c-8c4f-5a57b8978fc7)

![image](https://github.com/user-attachments/assets/d97d05d2-a023-49d5-932f-b2e5640a42ff)


