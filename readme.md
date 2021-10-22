# Predicting Covid-19 Vaccine Hesitancy
This is the official repository associated with the paper "Predicting Zip Code-Level Vaccine Hesitancy in US Metropolitan Areas Using Machine Learning Models on Public Tweets".

## Setup
Required languages and libraries:
- Python 3.0+
- scikit-learn ([sklearn](https://scikit-learn.org/stable/install.html))
- Natural Language Toolkit ([nltk](http://www.nltk.org))
- [fastText](https://fasttext.cc)

Use ```pip install``` to download packages.

## File Overview
```tweet_embeddings```: Contains the code for creating text embeddings using [fastText](https://fasttext.cc).

```modeling```: Contains the code used for building the machine learning models.

```sample_data```: Contains 100 sample tweets (text only embedding) along with example zip code-level data.

## Data
The data used in this project comes from [A Geo-Tagged COVID-19 Twitter Dataset for 10 North American Metropolitan Areas Over a 255-Day Period](https://www.mdpi.com/2306-5729/6/6/64).

## Contact
Email: melotte@usc.edu