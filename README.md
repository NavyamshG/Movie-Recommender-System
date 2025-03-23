# 🎬 Movie Recommender System

An interactive web application that suggests movies based on a selected title using content-based filtering. This project leverages cosine similarity to recommend movies with similar content features, offering a user-friendly interface built using Streamlit.

---

## 🔍 Project Overview

This movie recommender system is built using a content-based approach. It takes a movie selected by the user and finds similar movies by comparing feature vectors derived from movie metadata.

### Key outcomes include:

- **Recommendation Engine**: Uses cosine similarity scores to identify and rank similar movies.
- **Interactive Interface**: Built with Streamlit for seamless user interaction.
- **Scalable Backend**: Uses precomputed similarity matrix and serialized movie metadata for fast recommendations.

---

## 📦 Prerequisites

Ensure you have Python installed along with the following libraries:

- `streamlit`: For building the web application interface  
- `pickle`: For loading serialized data  
- `pandas`: For handling movie data  
- `requests`: (Optional) For fetching additional movie metadata (commented out in code)

---

## 📂 Project Structure

### Recommendation Logic  
- `movie_dict.pkl`: Serialized dictionary containing movie metadata  
- `similarity.pkl`: Precomputed similarity matrix  
- `recommend()`: Function to fetch top 5 recommended movies based on cosine similarity  

### Streamlit Interface  
- Dropdown to select a movie  
- Button to generate recommendations  
- Display of recommended titles in five columns  

---

## 🚀 Steps to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-recommender-system.git
   ```

2. Navigate to the project directory:
   ```bash
   cd movie-recommender-system
   ```

3. Launch the Streamlit app:
   ```bash
   streamlit run app.py
   ```

---

## 🖼️ Visualization

The interface allows you to:

- Select a movie from a dropdown  
- View five recommended titles displayed horizontally  
- (Optionally) Enhance the app to show posters using TMDB API  

---

## 📊 Key Features

- Lightweight and fast movie recommendations  
- Streamlit-based intuitive front-end  
- Easy scalability with enhanced metadata or collaborative filtering  

---

## 🤝 Conclusion

This project demonstrates how simple content-based filtering techniques can be used to build scalable, real-time recommender systems. It's a great starting point for expanding into hybrid or collaborative recommenders.
