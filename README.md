
## 📌 Overview

Given a song you like, this system recommends the most similar tracks by analysing Spotify audio features — danceability, energy, tempo, valence, acousticness, and more — using **cosine similarity** across a normalized feature matrix.

---

## 🗂️ Dataset

`spotify_tracks.csv` — Spotify track metadata and audio features including `danceability`, `energy`, `tempo`, `valence`, `acousticness`, `instrumentalness`, `speechiness`, and `popularity`.

---

## 🔧 Tech Stack

`Python` · `pandas` · `NumPy` · `scikit-learn` · `Matplotlib / Seaborn` · `Jupyter Notebook`

---

## 🏗️ How It Works

```
Load & Clean Data → Normalize Features → Compute Cosine Similarity → Return Top-N Recommendations
```

Cosine similarity measures the angle between audio feature vectors, making it effective for comparing songs across multiple dimensions regardless of scale.

---

## 🚀 Getting Started

```bash
git clone https://github.com/IAN-RIUA/Spotify_recommender_system.git
cd Spotify_recommender_system
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook index.ipynb
```

---

## 💡 Future Improvements

- Integrate live data via the **Spotify Web API**
- Add **collaborative filtering** based on listening history
- Deploy as a **Flask/FastAPI web app**

---

## 🧑‍💻 Author

**Ian Riua** · Data Analyst & Data Scientist. 
