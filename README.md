# Content-Based Movie Recommendation System using NLP

## Overview
This project is a content-based movie recommendation system developed using Natural Language Processing (NLP) and cosine similarity techniques. The system recommends movies similar to a selected movie based on genres, keywords, cast, crew, and movie overview.

The recommendation engine analyzes movie metadata and suggests the most similar movies to users.

---

## Features
- Content-based movie recommendation
- NLP-based text preprocessing
- Cosine similarity calculation
- Movie similarity analysis
- Data visualization using charts
- Recommendation function for similar movies

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- NLP
- Cosine Similarity

---

## Dataset
TMDB 5000 Movies Dataset

Dataset Link:  
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

---

## Workflow
1. Data collection and preprocessing
2. Feature engineering
3. Combining movie metadata into tags
4. Text vectorization using CountVectorizer
5. Similarity calculation using cosine similarity
6. Recommendation generation

---

## Recommendation Example

### Input
```python
recommend("Avatar")
```

### Output
- John Carter
- Guardians of the Galaxy
- Star Trek
- Aliens
- The Fifth Element

---

## Data Visualizations

### Top Genres Chart
Attached in screenshots folder

### Recommendation Output
Attached in screenshots folder

---

## Future Improvements
- Add collaborative filtering
- Deploy using Streamlit
- Integrate TMDB API for movie posters
- Improve recommendation accuracy using deep learning
- Add user-based recommendations

---

## Conclusion
This project successfully demonstrates how NLP and similarity-based techniques can be used to build an effective movie recommendation system. The system recommends movies based on content similarity and provides personalized recommendations to users.

---

## Author
Durga Velamala
