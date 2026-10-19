# sms-spam-detector
# SMS Spam Detector

## Project Overview
SMS Spam Detector is a Machine Learning and Natural Language Processing (NLP) project that classifies text messages as Spam or Not Spam (Ham).

## Features
- Classifies SMS messages.
- Uses TF-IDF to convert text into numerical features.
- Uses a trained Machine Learning model to predict message categories.
- Includes a Gradio web interface for testing messages.

## Project Files
- `spam_detector_app.zip` — Application files.
- `spam_model.pkl` — Trained Machine Learning model.
- `tfidf.pkl` — Saved TF-IDF vectorizer.
- `requirements.txt` — Required Python libraries.

## Technologies Used
- Python
- Machine Learning
- Natural Language Processing (NLP)
- TF-IDF
- Gradio

## How to Run
1. Download and extract `spam_detector_app.zip`.
2. Install the required libraries listed in `requirements.txt`.
3. Make sure the model and TF-IDF files are available at the paths expected by the application.
4. Run the application using its Python entry-point file.

## How It Works
1. The user enters an SMS message.
2. TF-IDF converts the text into numerical features.
3. The trained model predicts whether the message is Spam or Not Spam.
4. The application displays the prediction.

## Author
Aqsa Soomro
