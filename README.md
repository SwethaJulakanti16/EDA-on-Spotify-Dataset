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
![Image](https://github.com/user-attachments/assets/44e64159-6732-42f2-b63b-6792f2de1b4c)
---

### 🌟 Distribution of Track Popularity
> Most tracks have low popularity scores (0–20), with very few high-popularity tracks. This skew suggests that high popularity is rare and potentially hard to achieve.
![Image](https://github.com/user-attachments/assets/af37dd50-7ecc-49c4-93ba-26071b8f706c)
---

### ⏱️ Track Duration Distribution
> Most tracks are between 2 to 5 minutes. A few outliers exceed 10 minutes, which are likely live or instrumental tracks. The distribution shows a long right tail.
![Image](https://github.com/user-attachments/assets/fee5d175-0b03-4572-ad88-914b5f88f23b)
---

### 🔗 Correlation Matrix (Popularity vs Duration)
> The correlation heatmap reveals a negligible correlation (0.023) between track duration and popularity, meaning longer songs are not necessarily more popular.
![Image](https://github.com/user-attachments/assets/9e5356bd-733a-496d-9cf5-7dbe526009e9)
---

### 🔞 Explicit vs Non-Explicit Track Count
> Majority of tracks are non-explicit. Explicit content appears in only a smaller proportion of the dataset.
![Image](https://github.com/user-attachments/assets/1cf0a49e-fb11-43db-9b51-456ad8939375)
---

### 📈 Popularity by Explicit Content
> While explicit tracks show a slightly higher median popularity, the overall distribution is similar between explicit and non-explicit tracks.
![Image](https://github.com/user-attachments/assets/6f70b048-c84e-4ffd-b094-6124248c4a6d)
---

### 👑 Top Artists by Popularity & Count
- **By Average Popularity:** Features artists like Harry Styles, The Weeknd, and David Guetta.
- **By Track Count:** Highlights prolific contributors like Metallica and ONE OK ROCK.
- **By Unique Albums:** Shows artists with diverse discographies.
![Image](https://github.com/user-attachments/assets/07163808-d058-45e6-b8ed-cfbfb924b0d0)

![Image](https://github.com/user-attachments/assets/afa1d514-638b-4047-aaa0-9cfd649b0e6d)

---

### 🔥 Top 5 Genres by Average Popularity and Top 10 artists by unique album
> Genres like rock, dance, and pop consistently rank higher in average popularity.
>  "Metallica" stands out with the highest number of distinct albums, reflecting a diverse and sustained music production over time.
![Image](https://github.com/user-attachments/assets/0e8b3d8f-cedf-4626-92e4-c642e309927b)

![Image](https://github.com/user-attachments/assets/307b428a-48c2-41fe-b9c7-031b6f543812)

---

## 🧰 Tools & Technologies

- Python
- Pandas & NumPy
- Seaborn & Matplotlib
- Jupyter Notebook

---


