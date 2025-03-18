# 🎵 Spotify Music Analysis  

## 📌 Project Overview  
The music streaming industry has grown exponentially, with **Spotify** as a key player. This project analyzes **Spotify track data** to uncover patterns in **song popularity, audio features, and listener engagement**.  

---

## 🎯 Objectives  
✔ Identify **factors influencing song popularity**  
✔ Explore **trends in song attributes** (tempo, danceability, energy, etc.)  
✔ Analyze the **impact of genres, artists, and track duration** on listener preferences  

---

## 📊 Dataset Overview  
The dataset contains multiple attributes related to Spotify tracks, including:  

| Column | Description |
|--------|------------|
| `Track Name` | Song title |
| `Artist` | Performing artist(s) |
| `Album Name` | Album where the song is featured |
| `Popularity` | Spotify-assigned score (0-100) |
| `Danceability` | Suitability for dancing (0-1) |
| `Energy` | Intensity and activity of the track |
| `Loudness` | Volume level (in decibels) |
| `Speechiness` | Presence of spoken words (0-1) |
| `Acousticness` | Acoustic composition of the track (0-1) |
| `Instrumentalness` | Presence of instrumental parts (0-1) |
| `Liveness` | Probability of being a live recording (0-1) |
| `Valence` | Positivity of the track (0-1) |
| `Tempo` | Speed of the track (BPM) |
| `Genre` | Music category |

---

## 🛠️ Tools & Technologies Used  
- 🐍 **Python**  
- 📊 **Pandas**  
- 🎨 **Matplotlib & Seaborn**  
- 🧪 **Data Visualization & Analysis**  
- 📓 **Jupyter Notebook**  

---

## 🔬 Hypothesis Testing  

### 📍 Hypothesis 1: **Higher energy songs tend to be more popular**  
✅ **Validation**: Moderate positive correlation between **energy & popularity**. Songs with **energy above 80** generally rank higher.  

### 📍 Hypothesis 2: **Shorter songs (under 3 minutes) are more popular**  
✅ **Validation**: Trending songs typically have **short durations (~3 minutes or less)**, while **longer tracks (>5 min) show lower popularity scores**.  

### 📍 Hypothesis 3: **Danceability is a key factor in song popularity**  
✅ **Validation**: Danceable tracks (score **> 0.7**) show **higher engagement**. Genres like **pop & electronic** tend to perform better.  

### 📍 Hypothesis 4: **Explicit tracks have higher energy than non-explicit tracks**  
✅ **Validation**: Explicit songs often **have higher energy levels**, making them more engaging.  

### 📍 Hypothesis 5: **Older songs tend to have lower loudness levels**  
✅ **Validation**: Songs **before the 2000s** are **quieter on average**, showing a **negative correlation between loudness and release year**.  

---

## 📊 Key Insights from EDA  

✔ **Energy, danceability, and tempo** significantly impact a song’s popularity.  
✔ **Shorter songs (~3 minutes)** gain **higher engagement & streams**.  
✔ **Pop & electronic genres** dominate streaming platforms.  
✔ **Older songs (pre-2000s)** have **lower loudness levels**, possibly due to different recording standards.  

---

## 📢 Recommendations  

📌 **For Music Producers & Artists**  
✔ Focus on **high-energy & danceable tracks** to maximize engagement.  
✔ Keep songs under **3-4 minutes** for better streaming performance.  

📌 **For Spotify & Streaming Platforms**  
✔ Use **popularity trends** to improve song recommendations.  
✔ Optimize **playlist curation** based on listener preferences.  

📌 **For Marketers & Music Labels**  
✔ Promote **high-energy tracks** for **better playlist placements**.  
✔ Leverage **genre-based insights** for **targeted promotions**.  

---

## 📌 Conclusion  
🔹 **Energy, danceability, and tempo** play a crucial role in song popularity.  
🔹 **Shorter tracks (~3 min)** tend to perform better on streaming platforms.  
🔹 **Pop & electronic genres** gain the highest engagement.  
🔹 These insights help **artists, labels, and streaming services** improve music promotion strategies.  

---

## 📁 Repository Structure  

📂 Spotify-Music-Analysis

│── 📜 spotify_project.ipynb # Jupyter Notebook with analysis

│── 📄 Spotify Analysis - Project.pptx # Project presentation

│── 📄 README.md # Project documentation (this file)

---

## 🤝 Connect with Me  
💼 [LinkedIn](https://www.linkedin.com/in/shivamgupta-da)  
📧 Email: shivamguptacpl@gmail.com  

🚀 If you found this project useful, give it a ⭐ on GitHub!  
