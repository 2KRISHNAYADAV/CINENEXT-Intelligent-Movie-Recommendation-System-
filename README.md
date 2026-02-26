# 🎬 CINENEXT  
### Intelligent Movie Recommendation System  

<p align="center">
  <img src="https://media.giphy.com/media/l0HlBO7eyXzSZkJri/giphy.gif" width="600"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Python-3.10-yellow?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Streamlit-App-red?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/API-TMDB-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge"/>
</p>

---

## 🚀 About CINENEXT  

**CINENEXT** is an intelligent movie recommendation system built using Machine Learning.  
It recommends movies based on content similarity, user preferences, and emotional mood analysis.

The system analyzes movie metadata and suggests the most relevant movies using advanced similarity techniques.

---

## 🎥 Demo Preview  

> Add your project demo thumbnail here
https://www.linkedin.com/posts/krishna203ker_cinenext-machinelearning-ai-activity-7432902658786664448-m2A8?utm_source=share&utm_medium=member_desktop&rcm=ACoAAE0Ost4BV_DpsL1V4XCailPUkdNw3mvSG8g

## 📊 Dataset Used  

TMDB Movie Metadata Dataset from Kaggle:  
👉 [https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata](https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies)  

Dataset includes:
- Movie Titles  
- Genres  
- Keywords  
- Cast  
- Crew  
- Overview  
- Popularity & Ratings  

---

## 🧠 Machine Learning Approach  

### 🔹 Content-Based Filtering  
Each movie is transformed into a feature vector using:

- Text preprocessing  
- Feature engineering  
- Count Vectorizer / TF-IDF  
- Cosine Similarity  

The system calculates similarity scores between movies and recommends the top closest matches.

---

## 🔥 Key Features  

✅ Content-Based Recommendation Engine  
✅ Cosine Similarity Scoring  
✅ TMDB API Integration for Posters & Details  
✅ Interactive UI built with Streamlit  
✅ Login-Based Personalized System  
✅ Mood-Based Chatbot for Emotional Recommendations  
✅ Clean and Responsive Interface  

---

## 🎭 Mood-Based Chatbot  

Users can enter their mood like:

- "I feel happy today"
- "Suggest something thrilling"
- "I want a romantic movie"

The chatbot analyzes emotional tone and recommends movies accordingly.


---
## 🛠️ Technical Pipeline
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Streamlit  
- TMDB API  
- NLP Techniques  


### 1. Data Acquisition
The system fetches real-time data from The Movie Database (TMDB) API, including:
- Metadata (Title, Overview, Release Date)
- Features (Genres, Keywords, Cast, Crew)
- User Metrics (Popularity, Vote Average)
- 

### 2. Recommendation Engine
The hybrid model combines two primary approaches:

#### Content-Based Filtering
- **Vectorization**: Movie features (genres, keywords) are transformed into a feature vector.
- **Cosine Similarity**: We calculate the distance between movie vectors to find the most similar titles.
- **Logic**: If you like *Inception*, the system identifies other high-concept sci-fi thrillers with similar thematic tags.

#### Collaborative Filtering
- **User-Item Matrix**: Tracks user ratings and watchlist additions.
- **Pattern Matching**: Identifies "Users who liked this also liked..." patterns by calculating similarity between user profiles.

### 3. Frontend Architecture
- **React 18 + TypeScript**: For a robust, type-safe component architecture.
- **Tailwind CSS**: For high-performance, utility-first styling.
- **Motion**: For fluid, cinematic transitions and interactions.

## 📓 Data Science & Python Pipeline
For a deep dive into the mathematical models (TF-IDF, SVD, etc.), check the `/notebooks` directory which contains:
- `recommendation_engine.ipynb`: A Jupyter notebook demonstrating the hybrid model implementation in Python using Pandas and Scikit-Learn.
- `data_pipeline.py`: A script for processing and cleaning movie datasets.


## ⚙️ How It Works  

1. Data Cleaning & Preprocessing  
2. Feature Combination into Tags  
3. Text Vectorization  
4. Cosine Similarity Calculation  
5. Top-N Movie Recommendation  
6. API Call for Poster Fetching  
7. Personalized Filtering via Login System  

---

## 📂 Project Structure  

```
CINENEXT/
│
├── app.py
├── notebook.ipynb
├── dataset/
├── models/
├── assets/
└── README.md
```

---

## 💡 Personalization System  

- User Login  
- Preference Selection  
- Watch History Tracking  
- Custom Tag-Based Filtering  
- Hybrid Recommendation Logic  

---

## 📌 Installation  

```bash
git clone https://github.com/yourusername/CINENEXT.git
cd CINENEXT
pip install -r requirements.txt
streamlit run app.py
but i can`t give full app - inbuild now it will be soon....
```

---

## 🌟 Why CINENEXT?  

CINENEXT combines:
- Machine Learning  
- NLP  
- API Integration  
- Personalization  
- Interactive UI  

It is designed to simulate a real-world recommendation system like streaming platforms.

---

## 🤝 Contributing  

Contributions, suggestions, and feedback are welcome.

---

## 📬 Connect With Me  

LinkedIn: https://www.linkedin.com/in/krishna203ker/   

---

<p align="center">
  ⭐ If you like this project, give it a star!
</p>

<p align="center">
  Built with ❤️ by Krishna Yadav
</p>
