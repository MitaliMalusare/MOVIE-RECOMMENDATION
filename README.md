# MOVIE-RECOMMENDATION


Movie Recommendation System
This project focuses on building a movie recommendation system using Natural Language Processing (NLP) techniques. The goal is to suggest movies based on their similarity in features like plot, genre, and cast, ensuring personalized recommendations for users.

Technology Used
We employed various techniques to process and prepare the data for recommendations:

Data Cleaning: This involved removing irrelevant information, handling missing values, and ensuring the data was ready for further processing.

Combining Features: Key features like movie descriptions, genres, and cast information were combined to form a single text-based feature for each movie.

Stemming (PorterStemmer): To normalize the text data, we used the PorterStemmer to reduce words to their root form, making the analysis more consistent across variations of words.

Vectorization (CountVectorizer): The textual features were then converted into numerical format using the CountVectorizer, which creates a matrix of token counts. This matrix forms the basis for calculating similarity between movies.

Calculating Similarity
We calculated the cosine similarity between the vector representations of the movies. This method helps in determining how closely related two movies are based on the features they share. Once the similarity was computed, the movies with the highest similarity scores were selected as recommendations.

Streamlit API Interface
To provide a user-friendly interface, we integrated Streamlit to build a simple API. Users can interact with the system, explore movie recommendations, and receive movie suggestions based on the closest similarity to the selected movie.
