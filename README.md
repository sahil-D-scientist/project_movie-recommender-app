# 🎬 Movie Recommender System

Find the best movie recommendations instantly! 🎥🍿

## 🔍 Overview
This **Movie Recommender App** helps users discover the **top recommended movies** based on their likings. The system fetches **movie posters** from **TMDb API** to enhance the experience.

## 🚀 Features
- ✅ **Instant Movie Recommendations** – Get top-recommendations.
- ✅ **TMDb API Integration** – Fetches high-quality posters.
- ✅ **Fast & Easy to Use** – Built with **Streamlit**, providing an **interactive UI**.
- ✅ **Saves Your Time** – Quickly discover movies you might love.

## 🛠 How It Works
1. **Select a movie** from the dropdown list. 🎞️
2. Click **"Recommend"** to get **top 5 similar movies**. 🎥
3. The system displays **recommended movies** along with **posters** fetched from TMDb. 🖼️
4. Users can **instantly discover movies they might love** and save time searching! 🕒

## 📦 Installation

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-repo/movie-recommender.git
cd movie-recommender
```

### 2️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```
or manually install:
```sh
pip install streamlit pandas requests pickle5
```

### 3️⃣ Run the App
```sh
streamlit run app.py
```

## 🛠 Requirements (`requirements.txt`)
```
streamlit
pandas
requests
pickle5
```

## 📝 Configuration
- **API Key Setup**: Replace the placeholder in `app.py`:
  ```python
  api_key = 'YOUR_TMDB_API_KEY'
  ```
- Get your **TMDb API Key** from [TMDb Developer Portal](https://www.themoviedb.org/settings/api).



## 🛠 Built With
- **Python** 🐍
- **Streamlit** 🎨
- **TMDb API** 🎥
- **Pandas** 📊

## 📜 License
This project is open-source under the **MIT License**.

## 💬 Have Questions?
Feel free to open an **issue** or reach out! 🚀  

Happy Movie Watching! 🍿🎬✨
