# Moosic-Spotify-Playlist
## Unsupervised Machine Learning approach for creating playlist on Spotify
A CSV file with audio features of about 5000 songs sourced from Spotify is gievn, the goal is to create playlists, ensuring the features within each playlist are as similar as possible. This is a clustering problem, approachable with unsupervised machine learning, as predefined clusters are not given.

Major steps followed for this project are as follows.

### Data cleaning
- Clean and preprocessing data set
- Drop unused columns
- Remove outliers
- Clean column names

### Data Scaling
MinMaxScalar or StandardScalar or RobustScaler

### K-mean clustering
Use “Elbow-Method” to define amount of clusters (=playlists)
Use Silhouette score to decide on best scaler
Check different song-features for each cluster to name playlists!

<!--### Cluster Analysis
Univariate and bivariate analysis of clusters
Manual categorization and labeling of clusters-->
