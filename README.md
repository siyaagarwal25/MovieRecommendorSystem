![INPUT](https://github.com/user-attachments/assets/b2a76d97-9290-47ef-ae54-b2b68e252bd2)
#  Movie Recommender System

A machine learning–based movie recommender system that suggests movies based on similarity in content and popularity trends. This project helps users discover new movies tailored to their preferences.

---

##  Overview

With thousands of movies released every year, choosing what to watch next can be overwhelming. This recommender system solves that problem by analyzing metadata (like genres, cast, and keywords) and suggesting movies similar to a given title.

This system supports:
- **Content-based filtering** – recommends similar movies based on metadata
- **Popularity-based filtering** – recommends trending/highly rated movies

The project is built purely in Python and works in a local Jupyter Notebook environment.

---

##  Features

-  **Movie Similarity Matching** using genres, keywords, cast, and crew
-  **Cosine Similarity** for content-based filtering
-  **Popularity Filtering** using vote counts and ratings
-  **Text Processing** with stemming and feature extraction
-  **Poster Integration** (optional via TMDb API)
-  Fully interactive notebook setup

---

##  Technology Stack

| Category       | Tools Used                                 |
|----------------|---------------------------------------------|
| Language       | Python 3                                    |
| Data Handling  | Pandas, NumPy                               |
| ML / NLP       | Scikit-learn, CountVectorizer, NLTK         |
| Visualization  | Jupyter Notebook (for interactive testing)  |
| API (optional) | TMDb API (for poster images)                |

---

## Installation

###  Prerequisites

- Python (v3.7 or higher)
- pip (Python package manager)
- [TMDb API Key](https://developer.themoviedb.org/)

---

###  Frontend Setup 

```bash
# Clone the repository
git clone https://github.com/your-username/MovieRecommendorSystem.git
cd MovieRecommendorSystem
```

---

### Backend Setup

```# Navigate to Project Directory


cd MovieRecommendorSystem
# Create a virtual environment
python -m venv venv

# Activate the environment
# On macOS/Linux:
source venv/bin/activate

# On Windows:
venv\Scripts\activate
streamlit run app.py
```
---
##  Screenshots

###  Home Page of Recommender
![INPUT](https://github.com/user-attachments/assets/b2a76d97-9290-47ef-ae54-b2b68e252bd2)

###  Sample Output
![Output](https://github.com/user-attachments/assets/a3b03e50-c224-49ff-ba88-c39d178bee08)




   





