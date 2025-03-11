# IMDB Movie Genre Prediction

A machine learning project that predicts movie genres using IMDB dataset. This project uses natural language processing and machine learning techniques to analyze movie titles and other features to predict their genres.

## Features

- Multi-label genre classification
- Uses IMDB's extensive movie database
- Natural Language Processing (NLP) for title analysis
- Machine learning models for prediction
- Performance metrics evaluation

## Dataset

The project uses IMDB's public dataset, specifically:
- title.basics.tsv.gz: Contains basic movie information including titles, genres, and release years

## Requirements

- Python 3.x
- pandas
- scikit-learn
- nltk
- gensim
- numpy

## Installation

1. Clone the repository:
```bash
git clone https://github.com/BhaskarAdhikari/IMDB-Movie-Genre-Prediction.git
cd IMDB-Movie-Genre-Prediction
```

2. Install required packages:
```bash
pip install pandas scikit-learn nltk gensim numpy
```

3. Download the IMDB dataset and place it in the project directory.

## Usage

1. Run the Jupyter notebook:
```bash
jupyter notebook "Movie Genre Prediction.ipynb"
```

2. Follow the notebook cells for:
   - Data preprocessing
   - Feature engineering
   - Model training
   - Evaluation

## Model Performance

- Includes precision, recall, and F1-score metrics
- Evaluated on validation and test sets
- Handles multi-label classification

## Acknowledgments

- IMDB for providing the dataset
- scikit-learn documentation
- Natural Language Processing community
