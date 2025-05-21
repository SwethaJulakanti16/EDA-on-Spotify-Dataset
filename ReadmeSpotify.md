# 🎵 Spotify – Exploratory Data Analysis (EDA)

The goal of this project is to perform an in-depth exploratory data analysis on a curated Spotify dataset comprising top tracks across various genres. The analysis aims to uncover meaningful insights into music preferences by evaluating factors such as genre distribution, track popularity, explicit content, artist contribution. Through visual storytelling, the project provides a clearer understanding of the composition and characteristics of popular music on Spotify.

---

## 📁 Dataset Summary

The dataset includes detailed information about Spotify tracks:

- **Attributes include:**  
 'name', 'genre', 'artists', 'album','popularity', 'duration_ms', 'duration_min',' explicit' .
  
---

## 📊 Key Visual Insights

### 🎼 Top 15 Genres by Track Count
> This bar chart shows the top 15 genres with the highest number of tracks. Each genre is equally represented with 50 tracks, indicating a balanced genre sampling.

---

### 🌟 Distribution of Track Popularity
> Most tracks have low popularity scores (0–20), with very few high-popularity tracks. This skew suggests that high popularity is rare and potentially hard to achieve.

---

### ⏱️ Track Duration Distribution
> Most tracks are between 2 to 5 minutes. A few outliers exceed 10 minutes, which are likely live or instrumental tracks. The distribution shows a long right tail.

---

### 🔗 Correlation Matrix (Popularity vs Duration)
> The correlation heatmap reveals a negligible correlation (0.023) between track duration and popularity, meaning longer songs are not necessarily more popular.

---

### 🔞 Explicit vs Non-Explicit Track Count
> Majority of tracks are non-explicit. Explicit content appears in only a smaller proportion of the dataset.

---

### 📈 Popularity by Explicit Content
> While explicit tracks show a slightly higher median popularity, the overall distribution is similar between explicit and non-explicit tracks.

---

### 👑 Top Artists by Popularity & Count
- **By Average Popularity:** Features artists like Harry Styles, The Weeknd, and David Guetta.
- **By Track Count:** Highlights prolific contributors like Metallica and ONE OK ROCK.
- **By Unique Albums:** Shows artists with diverse discographies.

---

### 🔥 Top 5 Genres by Average Popularity
> Genres like rock, dance, and pop consistently rank higher in average popularity.

---

## 🧰 Tools & Technologies

- Python
- Pandas & NumPy
- Seaborn & Matplotlib
- Jupyter Notebook

---


