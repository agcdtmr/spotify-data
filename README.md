# spotify-data

Exploratory Data Analysis project using Spotify dataset.


## To Do / To Fix:

- [x] Top 5 most popular artists
- [x] Top 5 loudest tracks
- [x] Artist with the most danceability song
- [x] Top 10 instrumental tracks
- [x] Multiple feature plots: tempo, loudness, acousticness, danceability, duration_ms, energy, instrumentalness, liveness, speechiness, valence
- [ ] Analize the histogram for: acousticness, danceability, duration_ms, energy, instrumentalness, liveness, speechiness, valence

## In this step-by-step project, I am learning how to:
- set up data environment
- how to use jupyter notebook
- how to import different library or utilities

import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt

- how to use seaborn style
- how to use pandas to read a csv file
- how to drop a column
- how to show first 5 rows using .head()
- how to check and clean data
- use of .describe() to summarize the central tendency, dispersion and shape of a dataset’s distribution, excluding NaN values. 
- use of .groupby()
- use of .count()
- use of .sort_values()
- how to get the top five using [:5]
- how to create pandas plot bar
- how to use matplotlib .figure()
- how to use seaborn bar plot
- the difference if we use .show() and not
- how to use matplotlib .pie() and its attributes like autopct, labels, etc
- how to use for loop in jupyter notebook
- how to use sns.displot()
- how to use the spotify web api documentation to analyze the data 

## Steps made building this project

1. Download needed datasets
https://www.kaggle.com/datasets/geomack/spotifyclassification
2. Open the documentation and read along: https://developer.spotify.com/documentation/web-api/reference/#/operations/get-audio-features



## Here are some ideas for additional features:
- [ ] Top 10 energetic tracks
- [ ] Most trending genre
- [ ] Most common durations
- [ ] Most popular artist
- [ ] Top 10 tracks with the most valence
