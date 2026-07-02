# Sentiment Analysis Web Application

A Flask-based web application that analyzes user-provided text and classifies it as positive, negative, or neutral using a BERT-based sentiment analysis API.

---

## Project Overview

This project demonstrates how to connect a Python Flask backend with a simple HTML and JavaScript frontend to perform real-time Natural Language Processing (NLP).

Users enter text into the browser, and the application returns the predicted sentiment label and confidence score.

---

## Features

- Analyze text sentiment
- Classify input as positive, negative, or neutral
- Display confidence score
- Flask backend API endpoint
- HTML and JavaScript frontend
- Unit tests for sentiment classification

---

## Technologies Used

- Python
- Flask
- HTML
- JavaScript
- IBM Watson NLP API
- BERT-based sentiment analysis
- Requests
- unittest

---

## Repository Structure

```text
Sentiment-Analysis-Web-App/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── app/
│   ├── server.py
│   ├── SentimentAnalysis/
│   │   ├── __init__.py
│   │   └── sentiment_analysis.py
│   ├── templates/
│   │   └── index.html
│   └── static/
│       └── mywebscript.js
│
└── tests/
    └── test_sentiment_analysis.py
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Sentiment-Analysis-Web-App.git
cd Sentiment-Analysis-Web-App
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the virtual environment:

### Windows

```bash
venv\Scripts\activate
```

### macOS/Linux

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Application

```bash
python app/server.py
```

Open your browser and go to:

```text
http://localhost:5000
```

---

## Running Tests

```bash
python -m unittest tests/test_sentiment_analysis.py
```

---

## Example Input

```text
I love working with Python.
```

## Example Output

```text
The given text has been identified as positive with a score of 0.99.
```

---

## Skills Demonstrated

- Python programming
- Flask web development
- Natural Language Processing
- API integration
- BERT-based sentiment analysis
- Frontend/backend communication
- JavaScript
- HTML
- Unit testing

---

## Future Improvements

- Improve frontend styling
- Add sentiment history
- Add charts for sentiment scores
- Deploy the app online
- Add error handling for API failures
- Support batch text analysis

---

## Author

Samantha Aranibar
