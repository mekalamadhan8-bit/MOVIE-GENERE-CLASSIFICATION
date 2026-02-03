Movie Genre Prediction Using Machine Learning


#Project Overview :
This project builds a machine learning model that predicts the genre of a movie based on its plot summary.
It uses Natural Language Processing (NLP) techniques to convert text into numerical features and then applies classification algorithms to identify the genre.


#Objective :
To automatically classify movies into genres (such as Action, Drama, Comedy, Romance, etc.) using only their plot descriptions.

#Technologies Used :
Python
Pandas
Scikit-learn
NLTK
TF-IDF Vectorizer
Machine Learning Classifiers

#Dataset :
wiki_movie_plots_deduped.csv

#Project Workflow :
Movie-Genre-Prediction/
│
├── data/
│   └── wiki_movie_plots_deduped.csv
│
├── notebook/
│   └── movie_genre_prediction.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── feature_extraction.py
│   ├── model_training.py
│   └── prediction.py
│
├── results/
│   ├── accuracy.txt
│   └── confusion_matrix.png
│
├── README.md
├── requirements.txt
└── main.py
#Evaluation Metrics :
Accuracy
Precision
Recall
F1-score
Confusion Matrix

#Example Prediction :
Input Plot:

A fearless smuggler rises to power while fighting powerful enemies and the system.

Predicted Genre:

Action
