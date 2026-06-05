# Movie Rating Prediction using Collaborative Filtering

## Project Overview

This project builds a Movie Rating Prediction System using the MovieLens dataset. The goal is to predict how a user might rate a movie they have not watched yet based on historical rating patterns from other users.

The project implements a Collaborative Filtering approach using the Singular Value Decomposition (SVD) algorithm from the Surprise library.

---

## Objective

The main objectives of this project are:

- Load and explore movie rating data
- Preprocess the dataset
- Build a collaborative filtering recommendation model
- Predict unseen movie ratings
- Evaluate model performance using RMSE
- Visualize rating distributions

---

### Dataset Files

| File | Description |
|--------|-------------|
| movies.csv | Movie titles and genres |
| ratings.csv | User ratings for movies | too large to upload | refer to the link below
| tags.csv | User-generated movie tags (not used in this project) |

### Dataset Statistics

- 20 million ratings
- 138,493 users
- 27,278 movies

### Dataset Source

https://www.kaggle.com/datasets/ashukr/movie-rating-data

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-Surprise

---

## Model Used

### Singular Value Decomposition (SVD)

SVD is one of the most popular collaborative filtering algorithms used in recommendation systems.

It works by:

- Learning hidden relationships between users and movies
- Identifying rating patterns
- Predicting ratings for unseen movies

---

## Results

The model successfully predicts movie ratings for movies that users have not rated yet.

### Evaluation Metric

**RMSE (Root Mean Squared Error)**

Lower RMSE values indicate better prediction accuracy.

```
RMSE: 0.9420

```


## Visualization

The project includes a histogram showing the distribution of movie ratings.

## Project Structure

```
Movie-Rating-Prediction/
│
├── Movie_Rating_Prediction.ipynb
├── movies.csv
├── README.md

```

## How to Run

### Open Notebook

Open:

```text
Movie_Rating_Prediction.ipynb
```

in Google Colab or Jupyter Notebook.

### Run All Cells

Run all notebook cells from top to bottom.

---

## Future Improvements

- Train on the complete 20 million ratings dataset
- Hyperparameter tuning
- Deep Learning recommendation systems
- Hybrid recommendation systems
- Movie recommendation web app using Streamlit

---

## Learning Outcomes

Through this project, the following concepts were learned:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Collaborative filtering
- Recommendation systems
- Model evaluation using RMSE
- Data visualization
- Working with large datasets

---

## Author

**Anum Fatima Awan**

Data Science Project – Movie Rating Prediction using Collaborative Filtering (SVD)


## Repository Description

```
Movie Rating Prediction System using Collaborative Filtering (SVD) on the movie rating dataset. Built with Python, Pandas, Scikit-Surprise, and Google Colab.
```
