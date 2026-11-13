LearnSmart — Learning Gap Detection & Personalized Study Recommendations




A Streamlit prototype for the academic project: AI-Based Learning Gap Detection and Personalized Study Recommendation System Using Machine Learning

Features

Student details
subject selection
 attendance and weekly study hours
Topic-wise quiz score entry
Configurable threshold for identifying topics that need revision
Personalized revision suggestions based on topic score bands
Topic performance chart
Downloadable CSV learning report
Session progress history


Run locally

Install Python 3.10 or later.
Open a terminal in this folder.
Install dependencies:
pip install -r requirements.txt
Start the app:
streamlit run app.py
Open the local URL shown in the terminal (usually http://localhost:8501).


Important project note

This is a working first prototype. The current topic-gap detector uses a transparent score threshold and recommendation rules. It does not claim to be a trained machine-learning model, and it does not display fabricated model accuracy.
For the ML stage, collect real, anonymized, topic-level assessment records with features such as attendance, study hours, attempts, topic quiz score and a clearly defined target label (for example, whether a topic needs intervention). Then train and evaluate a classifier using a held-out test set, compare suitable models, and report actual metrics. Avoid using generated or illustrative accuracy values as experimental results.



Suggested next development steps
Add secure student and teacher login.
Store assessments in a database.
Add a teacher dashboard for class-level topic gaps.
Train and validate a model on real labelled data.
Deploy the app so students can access it online.
New in this increment: ML Lab
Upload anonymized, labelled topic-level CSV data.
Train a Random Forest classifier with a stratified train/test split.
Review held-out accuracy, confusion matrix and feature importance.
Enter a student's topic data to try a prediction.
Download a blank CSV template from inside the app.

