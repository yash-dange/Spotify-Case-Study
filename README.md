# Spotify Playlist Success: An Analytical Case Study

![Spotify Logo](https://storage.googleapis.com/pr-newsroom-wp/1/2018/11/Spotify_Logo_CMYK_Green.png)

## Overview

This repository presents an in-depth analysis of the characteristics that contribute to the success of Spotify playlists. By examining various features and metrics, we aim to identify patterns and insights that can inform the creation of popular and engaging playlists.

## Contents

- [Presentation](#presentation)
- [Notebooks](#notebooks)
- [Data Sources](#data-sources)
- [Methodology](#methodology)
- [Findings](#findings)
- [Conclusions](#conclusions)
- [Future Work](#future-work)
- [Requirements](#requirements)
- [Usage](#usage)
- [Acknowledgments](#acknowledgments)

## Presentation

For a visual summary of our findings and methodologies, please refer to the presentation:

[Spotify Case Study Presentation](https://www.canva.com/design/DAGfqSJY4KU/6E2UigvoEIAQ_DE3-0vJ8w/view?utm_content=DAGfqSJY4KU&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h0dbee80c5b)

## Notebooks

1. **Exploratory Data Analysis (EDA):** [Yash_Assignment_EDA.ipynb](Yash_Assignment_EDA.ipynb)
   - Initial data exploration and visualization.
   - Identification of key features influencing playlist success.

2. **Modeling:** [Yash_Assignment_Modeling.ipynb](Yash_Assignment_Modeling.ipynb)
   - Development and evaluation of predictive models.
   - Feature importance analysis.

## Data Sources

The analysis utilizes publicly available Spotify data, including:

- Playlist metadata (e.g., number of followers, creation date).
- Track features (e.g., danceability, energy, tempo).
- User interaction metrics.

## Methodology

1. **Data Collection:** Aggregated data from Spotify's API and third-party datasets.
2. **Data Cleaning:** Handled missing values, duplicates, and inconsistencies.
3. **Feature Engineering:** Created new features such as playlist age and average track popularity.
4. **Exploratory Analysis:** Visualized data distributions and relationships.
5. **Modeling:** Applied machine learning algorithms to predict playlist success metrics.

## Findings

- **Key Features:** Identified attributes like average track popularity and genre diversity as significant predictors of playlist success.
- **Trends:** Noted that playlists with a mix of popular and emerging tracks tend to attract more followers.

## Conclusions

The study highlights that both track selection and playlist curation strategies play vital roles in a playlist's success on Spotify. Curators should focus on balancing popular hits with lesser-known tracks to maintain listener engagement.

## Future Work

- Incorporate user demographic data to personalize playlist recommendations.
- Explore the impact of playlist cover art and descriptions on user engagement.
- Analyze temporal patterns in playlist popularity.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yash-dange/Spotify-Case-Study.git
