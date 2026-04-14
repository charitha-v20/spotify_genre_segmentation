# Spotify Songs Genre Segmentation & Recommendation

## Overview
This project analyzes Spotify song data to group similar songs based on audio features and build a basic recommendation system. It demonstrates how machine learning can be used in music streaming platforms for personalization.

---

##  Dataset
- ~32,000 Spotify tracks
- Features include:
  - Danceability, Energy, Loudness
  - Acousticness, Tempo, Valence
  - Duration, Popularity

---

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

##  Project Workflow

### 1. Data Preprocessing
- Removed duplicates and handled missing values
- Selected relevant numerical audio features
- Applied feature scaling using `StandardScaler`

### 2. Exploratory Data Analysis
- Visualized:
  - Genre distribution
  - Popularity trends
  - Feature relationships (e.g., energy vs tempo)
- Generated correlation heatmap

### 3. Clustering (Unsupervised Learning)
- Used **K-Means clustering**
- Determined optimal clusters using **Elbow Method**
- Segmented songs into 5 clusters

### 4. Dimensionality Reduction
- Applied **PCA** for visualization
- Plotted clusters in 2D space

### 5. Recommendation System
- Built a **content-based recommendation system**
- Used **cosine similarity** on audio features
- Recommended songs with similar sound profiles

---

##  Results
- Successfully grouped songs with similar characteristics
- Observed meaningful relationships between clusters and genres
- Built a working prototype for music recommendation

---

##  Key Learnings
- Unsupervised learning (K-Means clustering)
- Feature scaling and dimensionality reduction
- Real-world application of recommendation systems

---

## Future Improvements
- Improve recommendation accuracy using hybrid models
- Incorporate user listening behavior
- Deploy as a web-based recommendation app

---

## Author
V Charitha
