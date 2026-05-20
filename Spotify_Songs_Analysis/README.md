# Spotify Songs Analysis
## Objective: The goal of this project is to analyze how features such as energy, danceability, and loudness relate to song popularity, while also examining how energy distributions vary across different music genres.

## Methodology
- Handled missing values and dropped duplicate track_id rows
- Used scatter plots and correlation analysis to examine relationships between energy, danceability, loudness, and popularity.
- Applied box plots and violin plots to compare energy distributions across different music genres and identify outliers.
- Created custom energy categories (Low, Medium, High) for grouped popularity analysis

## Key Findings
- A song's energy level does not guarantee popularity. Energy actually showed a weak negative correlation (-0.10) with popularity.
- Danceability and Loudness showed weak positive correlations with a track's popularity.
- EDM and Rock tracks rigidly clustered around high energy levels, whereas R&B maintains a much wider, lower-energy distribution.
- High-energy songs were generally associated with higher loudness values.
- Danceability remained distributed across all energy tiers, suggesting that highly danceable tracks can exist regardless of energy category.

## Files
- [Spotify_Songs_Analysis.ipynb](./Spotify_Songs_Analysis.ipynb) -> Main notebook

## Dataset Source
- [30000 Spotify Songs](https://www.kaggle.com/datasets/joebeachcapital/30000-spotify-songs)

[Open in Colab](https://colab.research.google.com/drive/1fUu6csJYzQTao5wwM0dcT2-6Q6aPf4Am?usp=sharing)


