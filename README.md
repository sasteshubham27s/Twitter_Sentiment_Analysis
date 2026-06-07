# Twitter Sentiment Analysis Using Django

## Project Overview

Twitter Sentiment Analysis is a web-based application developed using Django and Python that analyzes the sentiment of tweets and classifies them into Positive, Negative, or Neutral categories. The project uses Natural Language Processing (NLP) techniques to process textual data and provide meaningful insights into public opinions expressed on Twitter.

The system allows users to analyze tweet data, visualize sentiment distribution through graphs, and understand overall public sentiment regarding a topic, product, service, or event.

---

## Objectives

* To analyze tweets collected from Twitter.
* To classify tweets into Positive, Negative, and Neutral sentiments.
* To provide graphical visualization of sentiment results.
* To demonstrate the use of Natural Language Processing in social media analytics.
* To develop a user-friendly web application using Django.

---

## Features

* User-friendly web interface.
* User authentication and login system.
* Tweet sentiment classification.
* Positive, Negative, and Neutral sentiment detection.
* Graphical representation of sentiment analysis results.
* Data preprocessing and cleaning.
* Real-time sentiment analysis support.
* Dashboard for displaying analysis results.

---

## Technology Stack

### Frontend

* HTML
* CSS
* JavaScript
* Bootstrap

### Backend

* Python
* Django Framework

### Libraries Used

* Pandas
* NumPy
* Matplotlib
* Seaborn
* TextBlob
* NLTK

### Database

* SQLite

### Development Tools

* Visual Studio Code
* Jupyter Notebook
* GitHub

---

## System Requirements

### Hardware Requirements

* Processor: Intel i3 or above
* RAM: 4 GB or higher
* Storage: 500 MB free space

### Software Requirements

* Windows/Linux/MacOS
* Python 3.x
* Django
* VS Code
* Web Browser (Chrome, Edge, Firefox)

---

## Project Structure

```text
Twitter_Sentiment_Analysis_Django/
│
├── Twitter_Django/
│   ├── templates/
│   ├── static/
│   ├── utils/
│   ├── views.py
│   ├── urls.py
│   └── models.py
│
├── manage.py
├── db.sqlite3
├── requirements.txt
└── README.md
```

---

## Installation Steps

### Step 1: Clone Repository

```bash
git clone https://github.com/yourusername/Twitter-Sentiment-Analysis.git
```

### Step 2: Move to Project Directory

```bash
cd Twitter-Sentiment-Analysis
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Run Database Migrations

```bash
python manage.py migrate
```

### Step 5: Start Development Server

```bash
python manage.py runserver
```

### Step 6: Open Browser

```text
http://127.0.0.1:8000/
```

---

## Working Process

1. User logs into the system.
2. User enters a tweet or uploads tweet data.
3. The system preprocesses the text by removing:

   * URLs
   * Special characters
   * Stop words
4. NLP techniques are applied to extract sentiment information.
5. Sentiment is classified as:

   * Positive
   * Negative
   * Neutral
6. Results are displayed to the user.
7. Graphs are generated for visualization.

---

## Sentiment Categories

### Positive Sentiment

Tweets expressing happiness, satisfaction, appreciation, or positive opinions.

**Example:**

> "This product is amazing and works perfectly."

### Negative Sentiment

Tweets expressing dissatisfaction, complaints, or negative opinions.

**Example:**

> "The service was terrible and disappointing."

### Neutral Sentiment

Tweets containing factual statements without emotional tone.

**Example:**

> "The event starts at 10 AM tomorrow."

---

## Output Screens

* Home Page
* Login Page
* User Dashboard
* Tweet Analysis Page
* Sentiment Prediction Result
* Graphical Analysis Dashboard

---

## Advantages

* Easy to use.
* Fast sentiment classification.
* Provides visual analytics.
* Useful for market research.
* Supports social media monitoring.
* Helps understand public opinion.

---

## Applications

* Product Review Analysis
* Brand Monitoring
* Political Campaign Analysis
* Customer Feedback Analysis
* Market Research
* Social Media Analytics

---

## Future Scope

* Integration with live Twitter API.
* Deep Learning-based sentiment analysis.
* Multilingual sentiment detection.
* Real-time dashboard updates.
* Advanced data visualization.
* Cloud deployment support.

---

## Results

The system successfully analyzes tweets and classifies sentiments with good accuracy. It provides meaningful insights through graphical reports and helps users understand public opinion trends effectively.

---

## Conclusion

The Twitter Sentiment Analysis project demonstrates the practical application of Natural Language Processing and Machine Learning techniques in social media analytics. The system efficiently processes tweet data, identifies sentiment polarity, and presents results through an intuitive web interface. This project highlights the importance of sentiment analysis in understanding customer opinions, market trends, and public perceptions.

---

## Author

**Shubham**

### Project

Twitter Sentiment Analysis Using Django and NLP

### Academic Project

Bachelor of Engineering / Computer Engineering

---

## License

This project is developed for educational and academic purposes.
