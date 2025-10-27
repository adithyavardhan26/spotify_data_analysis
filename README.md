# spotify_data_analysis
This project analyzes Spotify music data using Python to discover insights into song attributes, popular artists, and user listening behaviors. The analysis leverages exploratory data analysis (EDA) techniques and a variety of visualizations to reveal music trends and consumer preferences over time.

Project Objective
Analyze Spotify song data to uncover trends in features like tempo, danceability, energy, and acousticness.

Identify patterns in genre and artist popularity.

Offer actionable insights for the music industry.

Dataset
Consists of song features such as Name, Artist, Genre, Popularity, Danceability, Energy, Tempo, Acousticness, Loudness, and Valence.

Collected from Spotify API/online repositories, containing comprehensive metadata.

Steps in the Project
1. Data Preparation
Loaded song and artist datasets using Pandas.

Cleaned data by handling missing values and removing incomplete entries. No nulls identified in the primary table.

Normalized features such as danceability and energy.

Created new columns for enhanced analysis, such as song popularity ranks and genre-based aggregations.

2. Exploratory Data Analysis (EDA)
Descriptive statistics computed for all main song attributes.

Univariate/bivariate analysis to highlight distributions and correlations.

Outlier detection for features like tempo and loudness.

3. Data Visualization
Histograms, bar charts, boxplots, heatmaps, and scatter plots created using Matplotlib and Seaborn.

Visualized top 10 most popular songs and top genres by aggregated features.

4. Musical Trend Analysis
Time series analysis of popularity, energy, and genre preference trends over release years.

Genre and artist trend analysis showing changes in popularity and production volume.

5. Insights & Recommendations
Provided actionable recommendations: prioritize popular features for playlist curation, target genres on the rise, and suggest song characteristics likely to enhance popularity.

6. Interactivity
Jupyter notebook is designed to allow users to filter data, generate interactive charts, and explore trends by artist, genre, or release year.

How to Use
Run spotify_data_analysis.ipynb in Jupyter or Google Colab.

Follow the step-by-step notebook cells for insights and visualization.

Users can modify filters (genre, year, artist) to drill into specific details.

Requirements
Python 3.x

pandas, numpy, matplotlib, seaborn

Business Value
Enables music companies and content creators to identify rising genres, ideal playlist features, and evolving consumer preferences.
