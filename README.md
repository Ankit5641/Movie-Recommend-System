

🎬 Movie Recommendation System

A Movie Recommendation Web App built using Python, Streamlit, and Machine Learning that recommends movies based on similarity scores and displays posters using the TMDB API.

🚀 Live Demo

🔗 (Add your deployed Streamlit link here)


📌 Features :

🎥 Recommends movies based on similarity matrix

🧠 Content-based filtering using Machine learning (vectorization)

🖼 Fetches movie posters from TMDB API

⚡ Fast & interactive Streamlit UI

🔍 Dropdown-based movie search

☁️ Deployed online for free

🛠 Tech Stack

Python

Streamlit

Pandas

Pickle

Machine Learning

TMDB API

GitHub

Streamlit Cloud

📂 Project Structure
movie-recommendation-system/
│
├── app.py
├── movie_dict.pkl
├── similarity.pkl
├── requirements.txt
└── README.md

⚙️ How It Works

User selects a movie from the dropdown

The system finds similar movies using a cosine similarity matrix

Top 5 recommended movies are selected

Posters are fetched dynamically using the TMDB API

Results are displayed in a clean web UI

🧠 Machine Learning Logic

The recommendation system uses content-based filtering, where:

Movie metadata is vectorized

Similarity between movies is computed

Movies with the highest similarity scores are recommended

▶️ How To Run Locally
1️⃣ Install Dependencies
pip install -r requirements.txt

2️⃣ Run the App
streamlit run app.py

🔑 API Used

TMDB (The Movie Database) API

You need an API key from:
👉 https://www.themoviedb.org/settings/api

Add it in app.py:

API_KEY = "your_api_key_here"


👨‍💻 Author

Ankit Kumar Singh
B.Tech in Information Technology

GitHub: https://github.com/your-username

LinkedIn: (optional)
