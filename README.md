# Installations

All required packages contained in:

conda 4.8.3

Python 3.7.6


## Project Motivation

Music Producers often needs to define the track genre, tempo and key as first step when starting a new project. 

This analysis offers an alternate to get that information based in historical data collected from Spotify.


## File Descriptions

Project 1 - Music Genre Cheat Sheet.ipynb :  Analysis documentation and reproducible code.
songDb.csv -  Spotify track historical data with required features.

## Project insights
The result of the analysis is a four-blocker able to represent the main tempo, key's and the most similar genres to the one of interest.

Feature engineering for Main parameters was required. Tempo switched to integer value, Genre standardized to particular main genres and Key improved by adding the mode and textual definition.

Genre similarity metrics based in percentage of shared features needed to be created to display the closest genres list.

All relevant data findings and current version limitations accessible via a dedicated medium post: [The Music Genre Cheat Sheet.](https://medium.com/the-music-genre-cheat-sheet/the-music-genre-cheat-sheet-fb57abf74301)

## Authors, Acknowledgements
Raw data stored at [Kaggle](https://www.kaggle.com/grasslover/spotify-music-genre-list)

Work by [Aratz Hernandez](https://www.linkedin.com/in/aratz-ulil-hernandez-solis-56355a50/)
