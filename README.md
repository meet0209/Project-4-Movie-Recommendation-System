# Movie Recommendation System

A simple movie recommendation system using TF-IDF and cosine similarity to find similar movies based on their overviews.

## Prerequisites

- Python
- pandas
- sklearn

## Installation
```bash
pip install pandas sklearn
```


## Usage

Run the script `Grand finale.py` with Python. The function `get_recommendations()` takes a movie title as input and outputs the 10 most similar movies.

```
python
print(get_recommendations('The Dark Knight Rises'))
```

This will print the 10 movies that are most similar to 'The Dark Knight Rises' based on their overviews.
