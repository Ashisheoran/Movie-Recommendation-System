# 🎬 Movie Recommendation System

A content-based movie recommendation system built using Machine Learning and Python.  
This project recommends movies similar to a selected movie by analyzing textual features such as genres, keywords, cast, and crew using cosine similarity.


---

## 🚀 Features

- Content-based movie recommendation
- Uses TMDB 5000 Movies dataset
- Fast recommendations using a precomputed similarity matrix
- Interactive web interface built with Streamlit
- Clean and modular project structure

---

## 🗂️ Project Structure

```
movie-recommender/
│
├── datasets/
│   ├── tmdb_5000_movies.csv
│   └── tmdb_5000_credits.csv
│
├── models/
│   ├── movies.pkl
│   └── similarity.pkl
│
├── .venv/
├── .env
├── .gitignore
├── app.py
├── movie_recommender.ipynb
├── requirements.txt
└── README.md
```

---

## 🧠 How It Works

1. Movie and credit datasets are merged into a single dataframe  
2. Important features such as genres, keywords, cast, crew, and overview are extracted  
3. Text data is converted into numerical vectors using CountVectorizer  
4. Cosine similarity is calculated between movie vectors  
5. Processed data and similarity matrix are stored using Pickle  
6. Streamlit interface allows users to select a movie and receive recommendations  

---

## ⚙️ Installation and Usage

### Clone the Repository
```bash
git clone https://github.com/your-username/movie-recommender.git
cd movie-recommender
```

### Create Virtual Environment (Optional)
```bash
python -m venv .venv
source .venv/bin/activate      # Linux / Mac
.venv\Scripts\activate         # Windows
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Run the Application
```bash
streamlit run app.py
```

---

## 📦 Dataset

- TMDB 5000 Movies Dataset  
- Source: Kaggle  
- Files used:
  - tmdb_5000_movies.csv  
  - tmdb_5000_credits.csv  

> Large dataset and model files may be excluded from deployment due to size limitations.

---

## 🛠️ Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- NLTK  
- Streamlit  

---

## 🔮 Future Enhancements

- Add collaborative filtering  
- Integrate TMDB API for movie posters  
- Improve recommendation accuracy  
- Enhance UI/UX  
- Docker-based deployment  

---

## 👤 Author

Ashish  
Aspiring Data Scientist | Machine Learning Enthusiast  

GitHub: https://github.com/Ashisheoran 

Portfolio: https://ashisheoran.github.io/portfolio/

---

## ⭐ Acknowledgements

- TMDB for the dataset  
- Streamlit for the web framework  
- Scikit-learn for machine learning utilities  

---

⭐ If you find this project useful, please give it a star!
