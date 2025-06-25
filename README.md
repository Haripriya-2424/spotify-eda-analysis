
## Spotify Songs EDA & Trends Analysis

This project presents a comprehensive Exploratory Data Analysis (EDA) of over 180,000 Spotify tracks, aiming to uncover key patterns and insights behind song popularity.

Using Python (Pandas, Matplotlib, Seaborn) and Google Colab, the analysis explores various audio features such as energy, danceability, valence, instrumentalness, and more along with metadata like artist, language, and release year.

Whether you're a data enthusiast, aspiring analyst, music lover, or someone exploring data-driven storytelling, this project offers valuable insights into:

* What audio features are common in hit songs

* How music characteristics have evolved over time

* Which artists and languages dominate the charts

* Trends across genres, popularity, and song traits



---

### Dataset

**Source**: [Spotify Tracks Dataset (Kaggle)](https://www.kaggle.com/datasets/gauthamvijayaraj/spotify-tracks-dataset-updated-every-week/data)

**Description**: Contains metadata and audio features of songs such as popularity, energy, valence, danceability, acousticness, artist, album, year, language, duration, and more.

---

### Tools & Libraries

* Python
* Pandas
* Matplotlib
* Seaborn
* Google Colab + Google Drive integration

---

### EDA Visualizations

#### Key Graphs & Insights

* **Popularity Distribution**: Most songs are unpopular; hits are rare.
* **Feature Correlation Heatmap**: Energy and valence are strongly correlated with danceability.
* **Valence vs Hits (Violin Plot)**: Hit songs tend to have slightly higher valence (happier mood).
* **Yearly Trends**: Songs have become more energetic over time, while valence (happiness) has dropped.
* **Danceability vs Popularity**: More danceable songs tend to be more popular.
* **Instrumentalness vs Popularity**: Highly instrumental songs are less likely to be hits.
* **Top Artists by Popularity**: Shows the artists with the highest average popularity.
* **Most Active Artists**: Highlights artists with the most songs in the dataset.
* **Language vs Hit Ratio**: Korean and English songs dominate the hit charts.
* **Key Distribution**: Most songs are in C, D, and G keys with no strong influence on popularity.
* **Songs Released per Year**: Song releases spiked after 2010 and peaked in 2023.

---

### Possible Use-Cases

* Predicting hit songs based on audio features
* Analyzing music trends for producers and marketers
* Building recommendation systems or mood-based playlists


---

### How to Run

1. Open the notebook in Google Colab
2. Mount Google Drive and upload `spotify_tracks.csv`
3. Run the notebook cells to view analysis and charts

---

###  Author

**Haripriya Penchikalapati**

Data Analyst & ML Enthusiast

---

