CodSoft Team,

I wanted to take a moment to express my sincere gratitude for the remote internship experience in machine learning. Working independently on each project provided a unique opportunity to develop my technical skills and gain hands-on exposure to real-world applications. The guidance and support I received were invaluable in helping me navigate challenges and deepen my understanding.

Thank you for this opportunity, which has greatly contributed to my growth. I look forward to applying what I've learned in future projects.

Dwaipayan Dasgupta
-------------------------------------------
# Codsoft1
Intership Project
Movie Genre Prediction using Machine Learning
This project aims to predict the genre(s) of a movie based on its plot summary using Natural Language Processing (NLP) and machine learning techniques. This model leverages TF-IDF vectorization to process the text and uses logistic regression for classification.
Introduction
The goal of this project is to classify movie genres based on plot summaries. This can help in automated tagging of genres for new movies, personalized recommendations, and organization of movie databases.

Dataset
The dataset used in this project, Genredata.csv, contains movie plots and corresponding genres. Each plot is a string of text, while genres are provided as a comma-separated list. The genres are binarized for multi-label classification.

Features
TF-IDF Vectorization: Converts textual data (plot summaries) into a numerical format that the machine learning model can process.
Multi-Label Classification: Some movies belong to multiple genres, requiring a classifier that can handle multiple labels for each input.
Model
The model pipeline includes:

TF-IDF Vectorizer: Converts plot summaries into TF-IDF vectors.
Logistic Regression with One-vs-Rest Strategy: Classifies each movie plot into one or more genres.
Evaluation Metrics: Reports classification metrics, including precision, recall, and F1-score.
![image](https://github.com/user-attachments/assets/64b7eeac-1720-4566-8686-50380ffd50d2)
Results
The model's performance is evaluated using classification metrics, and the confusion matrix visualizes the accuracy across various genres.

Contributing
Contributions are welcome. Please feel free to submit a Pull Request.
