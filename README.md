# 🎵 Music Recommendation System

A content-based **Music Recommendation System** that suggests songs based on similarity between tracks.
The system leverages **machine learning**, **vector similarity**, and **Flask** to provide real-time song recommendations through a web interface.

---

##  Features

* Content-based music recommendation
* Cosine similarity for accurate song matching
* Interactive web interface
* Fast response using precomputed similarity matrices
* Clean and modular backend architecture

---

##  Tech Stack

### Languages & Libraries

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge\&logo=pandas\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge\&logo=numpy\&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge\&logo=scikit-learn\&logoColor=white)

### Web & Deployment

![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge\&logo=flask\&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge\&logo=html5\&logoColor=white)

### Tools

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white)

---

## 📂 Project Structure

```
├── app.py
├── songdata.csv
├── df.pkl
├── similarity.pkl
├── templates/
│   └── index.html
├── static/
│   └── style.css
├── Song_Recommendation System.ipynb
└── README.md
```

---

##  How It Works

1. Song metadata is processed and vectorized
2. **Cosine similarity** is calculated between songs
3. A similarity matrix is stored for fast lookup
4. User selects a song
5. System recommends the most similar tracks

---

##  Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/your-username/song-recommendation-system.git
cd song-recommendation-system
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the application

```bash
python app.py
```

### 4. Open in browser

```
http://127.0.0.1:5000/
```
### Results 
![img_alt](https://github.com/sanjanabh127/Music-Recommendation-System/blob/2bff79f8634d3e39535e7d2c2f4c82a98430a918/Images/Screenshot%202026-01-17%20155504.png)
![img_alt](https://github.com/sanjanabh127/Music-Recommendation-System/blob/2bff79f8634d3e39535e7d2c2f4c82a98430a918/Images/Screenshot%202026-01-17%20155550.png)
![img_alt](https://github.com/sanjanabh127/Music-Recommendation-System/blob/2bff79f8634d3e39535e7d2c2f4c82a98430a918/Images/Screenshot%202026-01-17%20155612.png)
![img_alt](https://github.com/sanjanabh127/Music-Recommendation-System/blob/2bff79f8634d3e39535e7d2c2f4c82a98430a918/Images/Screenshot%202026-01-17%20155642.png)

---
