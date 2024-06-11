Building a Music Hybrid Recommendation System Using Spotify API

Introduction
In this project, we developed a comprehensive hybrid recommendation system for music enthusiasts, leveraging the powerful Spotify API. This system combines both music audio features and weighted popularity to provide personalized music recommendations.

Key Steps in the Project

User Credentials Generation:
Generated user credentials using the Spotify Developer Dashboard.

Access Tokens Generation:
Utilized the Spotify API to generate access tokens for authentication.

Data Retrieval:
Retrieved playlist and album information using playlist IDs and access tokens.

Data Processing:
Assigned weights to the latest releases to prioritize new music.
Normalized music features using Min-Max Scalers for consistent data processing.

Hybrid Recommendation System
Recommendation System Using Music Audio Features:
Leveraged Spotify's detailed audio features such as tempo, danceability, and energy.
Created personalized recommendations based on similarities in these features, ensuring users get music that aligns with their preferences.

Recommendation System Using Weighted Popularity:
Combined music popularity metrics with weights assigned to recent releases.
Ensured that popular and trending music is highlighted, but new releases are also given significant consideration.

Project Highlights

Credential Management:
Efficiently managed user credentials and access tokens through the Spotify Developer Dashboard.

Playlist and Album Data Extraction:
Successfully retrieved and processed comprehensive playlist and album data using Spotify's API.

Feature Normalization:
Applied Min-Max Scalers to normalize music features, ensuring consistent input for the recommendation algorithms.

Hybrid Recommendation Engine:
Developed a dual approach to recommendations, combining both audio features and popularity metrics.
Balanced user preferences with trending and new music, offering a diverse and engaging music experience.

Conclusion
This project showcases the effective use of the Spotify API to build a sophisticated hybrid recommendation system. By integrating detailed audio features and popularity weights, we created a robust platform that caters to diverse user preferences, ensuring a dynamic and personalized music discovery journey.
