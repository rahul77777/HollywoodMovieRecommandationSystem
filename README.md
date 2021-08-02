# HollywoodMovieRecommandationSystem

Required libraries: Flask, gunicorn, MarkupSafe, numpy, scipy, nltk, scikit-learn, pandas, jsonschema, tmdbv3api, lxml, urllib3, requests, pickleshare.

We need an api , you can get API key from https://www.themoviedb.org/. (follow the steps given in this site to get API key)

# Steps to Run project

Clone or download this repository to your local machine Installed Required libraries: copy this code into yoy main.py and replace your api key.

  from tmdbv3api import Movie

  tmdb = TMDb()
  tmdb.api_key = 'API Key'
