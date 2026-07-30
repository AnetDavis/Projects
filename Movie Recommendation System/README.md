# Movie Recommendation System

## Objective

This project develops a content-based Movie Recommendation System that suggests movies similar to a user's selected movie. The recommendation engine analyzes movie genres using machine learning techniques to provide accurate and relevant movie suggestions through a simple Flask web application.

## Dataset

- **Dataset:** MovieLens Latest Small Dataset
- **Source:** GroupLens Research
- **Data Includes:**
  - Movie Titles
  - Genres
  - Ratings
- **Recommendation Type:** Content-Based Filtering

## Project Workflow

### 1. Data Collection
- Load the MovieLens dataset.
- Read movie information using Pandas.

### 2. Data Preprocessing
- Remove missing values.
- Select relevant movie features.
- Combine and clean genre information.

### 3. Feature Extraction
- Convert movie genres into numerical vectors using TF-IDF Vectorization.
- Generate feature vectors for similarity comparison.

### 4. Similarity Calculation
- Compute Cosine Similarity between all movies.
- Store similarity scores for recommendation generation.

### 5. Recommendation System
- Accept a movie selected by the user.
- Find similar movies based on cosine similarity.
- Display the top recommended movies through the Flask interface.

## Technologies Used

- Python
- Flask
- Pandas
- NumPy
- Scikit-learn
- HTML
- CSS
- Gunicorn

## Installation

Clone the repository:

```bash
git clone <repository-url>
```

Navigate to the project directory:

```bash
cd Movie-Recommendation-System
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the Flask application:

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

## Recommendation Method

The system uses a **Content-Based Filtering** approach.

Steps followed:

- Load the movie dataset.
- Extract genre information.
- Apply TF-IDF Vectorization.
- Calculate Cosine Similarity.
- Recommend the five most similar movies.

## Results

The application recommends movies with similar genres based on the selected movie. The recommendation process is fast, accurate, and provides users with relevant movie suggestions through an interactive web interface.

## Conclusion

This project demonstrates how content-based recommendation techniques can be used to build an effective movie recommendation system. By combining TF-IDF Vectorization with Cosine Similarity, the application generates meaningful recommendations while maintaining a simple and user-friendly interface.

## Author

**Name:** Anet Davis

**Registration Number:** 23BHI10146

**Application Number:** IN26011852

**Batch Number:** 1A

**Email ID:** anet.23bhi10146@vitbhopal.ac.in
