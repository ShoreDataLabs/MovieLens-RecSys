# MovieLens Recommendation System

## Description
This repository contains the code for a movie recommendation system built using the MovieLens 32M dataset. The system uses a hybrid approach that combines collaborative filtering, content-based filtering and graph-based recommendations.

## Data Source
The MovieLens 32M dataset can be downloaded from:
https://grouplens.org/datasets/movielens/32m/

## Getting Started

1. **Clone the repository:**
```bash
git clone https://github.com/ShoreDataLab/MovieLens-RecSys
```

2. **Change to the project directory:**
```bash
cd MovieLens-RecSys
```

3. **Install required dependencies:**
```bash
pip install -r requirements.txt
```

## Scripts and Notebooks
The repository includes a variety of scripts and notebooks for building and evaluating different recommendation algorithms:

* **notebooks/01_eda.ipynb:** Preforming exploratory data analysis on the MovieLens dataset
* **02_features.ipynb:** Performing feature engineering for the model
* **models/movie_rec_model.ipynb.py:** Builds recommendation model and evaluates the performance

## Evaluation
The recommendation system's performance is evaluated using metrics like precision and recall.

## Further Development
This repository provides a foundation for building and evaluating movie recommendation systems. Consider the following for further development:

* Experimenting with different recommendation algorithms
* Tuning hyperparameters of recommendation models
* Incorporating additional data sources