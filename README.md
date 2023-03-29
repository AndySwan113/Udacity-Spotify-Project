# Udacity-Spotify-Project
https://github.com/AndySwan113/Udacity-Spotify-Project/

## Introduction:
For this project, I'm going to use a dataset that uses spotify's API 'spotipy' that has gathered data on artists over a variety of years. The dataset includes data about the artist genres and popularity as well as song run time and audio features etc.

My aim is to produce an artist recommendation from an inputted artist, by finding which artists have the most similar genres. I would then try another method to rank these similar artists to return the best recommendations. This would be done via a artist-genres matrix.

I also aim to produce a song recommendation from an inputted song, by finding songs that are most similar using spotipys audio meta data. This data will need to be normalised. Then, I aim to improve it by including the song genres, which will use td-idf to hopefully produce more optimal recommendations.


## File Descriptions:
Data:
The dataset was gathered from: https://www.kaggle.com/datasets/mrmorj/dataset-of-songs-in-spotify
spotify_genre_final.xlsx - xlsx file containing all the raw data use for my analysis

DataScienceCapstone.ipynb - Notebook that was used for my analysis

DataScienceCapstone.html - html file of my analysis





## Libraries Used:
import pandas as pd
import numpy as np
from sklearn.preprocessing import MinMaxScaler
from sklearn.feature_extraction.text import TfidfVectorizer
import matplotlib.pyplot as plt
import seaborn as sb
import plotly.express as px

## Licenses
Kaggle - Provided the datasets
