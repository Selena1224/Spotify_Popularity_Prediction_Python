# Spotify Popularity Prediction and Music Segmentation Analysis

**Skills:** Python, Machine Learning, Predictive Analytics, Marketing Analytics, Clustering, Data Visualization, Statistical Modeling

## Overview

This project analyzes how Spotify audio features influence song popularity and demonstrates how predictive analytics can support marketing and promotional decision-making in the music streaming industry.

Using over 230,000 Spotify tracks, this project:

- Identifies the key drivers of song popularity
- Predicts whether a song is likely to become a hit
- Segments tracks into meaningful audience groups
- Provides actionable insights for streaming platforms and record labels

## Business Objectives

- Predict song popularity using audio characteristics
- Classify songs as Hit or Non-Hit
- Identify audience segments through clustering
- Support playlist placement and promotional strategies

## Dataset

**Dataset:** Ultimate Spotify Tracks DB (Kaggle)

- 232,725 Spotify tracks
- 18 variables
- Final cleaned dataset: 176,773 tracks

**Key Features**
- Danceability
- Energy
- Loudness
- Acousticness
- Valence
- Speechiness
- Tempo
- Popularity

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Methodology

### Exploratory Data Analysis (EDA)
- Popularity distribution analysis
- Correlation analysis
- Feature relationship exploration

### Multiple Linear Regression
Predicted continuous popularity scores and identified the strongest popularity drivers.

### Logistic Regression
Classified songs as Hit or Non-Hit to support promotion and release decisions.

### K-Means Clustering
Segmented tracks based on shared audio characteristics to identify potential audience groups and marketing opportunities.

## Key Findings

- Danceability, energy, and loudness were the strongest positive indicators of popularity.
- Song popularity is influenced by combinations of audio features rather than a single variable.
- Distinct song segments emerged that may support targeted marketing and playlist strategies.
- Predictive analytics can help streaming platforms and record labels make more informed promotional decisions.

## Repository Contents

- `Predicting_Spotify_Track_Popularity_Using_Marketing_Analytics_and_Machine_Learning.pdf`
- `Marketing_Analytics_Final_Presentation_Spotify.pdf`

## Future Enhancements

Potential improvements include incorporating:

- Playlist inclusion data
- Artist popularity metrics
- Social media engagement
- Release timing information
- Listener demographic data
