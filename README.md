# 🎬Filmception-Movie-Genre-Predictor-Multilingual-Audio-Converter
This project is an interactive, menu-driven system designed to process movie summaries, predict their genres using machine learning, and convert the summaries into audio in multiple languages.

Users can input a movie summary and choose between two options:

Predict Genre(s): The system uses a multi-label classification model trained on the CMU Movie Summary dataset to predict relevant genres such as Action, Drama, Comedy, etc.

Convert to Audio: The input summary is translated into Arabic, Urdu, and Korean, and then converted into speech using a text-to-speech engine. Users can select their preferred language to listen to the summary.

🔍 Features:
Text cleaning, tokenization, lemmatization, and preprocessing

Genre extraction and multi-label classification

Translation of summaries using NLP models or APIs

Audio generation in multiple languages

User-friendly menu-based interface

🛠 Technologies:
Python

Scikit-learn / Transformer-based models (BERT, etc.)

TextBlob / MarianMT / Google Translate API

gTTS / pyttsx3 for text-to-speech

Pandas, NumPy for data processing

📦 Dataset: https://www.kaggle.com/datasets/msafi04/movies-genre-dataset-cmu-movie-summary

Contributors: Vania Azeem and Abdullah Nadeem
