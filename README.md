Sentiment Analysis Web Application Using Flask and TextBlob

Project Overview-This project is a sentiment analysis web application developed using Python and the Flask web framework. The application analyzes user-entered text and classifies it as Positive, Negative, or Neutral. In addition to sentiment classification, the application displays polarity and subjectivity scores generated using the TextBlob library.

This project fulfills the Slab 2 (Intermediate) Sentiment Analysis task requirements.

-Technologies Used
-Python
-Flask
-TextBlob
-HTML
-CSS

Project Structure
sentiment_analysis_flask_textblob/
│── app.py
│── README.md
└── templates/
    └── index.html

Application Workflow-The user enters text through the web interface.The input text is processed using the TextBlob library.

TextBlob calculates:

Polarity (range: -1.0 to +1.0)

Subjectivity (range: 0.0 to 1.0)

Based on the polarity value:

Positive polarity indicates positive sentiment.

Negative polarity indicates negative sentiment.

Zero polarity indicates neutral sentiment.

The sentiment classification along with polarity and subjectivity values is displayed on the webpage.

Installation and Execution
Step 1: Install Dependencies
python -m pip install flask textblob

Step 2: Run the Application
python app.py

Step 3: Access the Application

Open a web browser and navigate to:

http://127.0.0.1:5000

Example Outputs
Input Text	Sentiment	Polarity	Subjectivity
I love this product	Positive	> 0	High
I hate this service	Negative	< 0	High
Today is Monday	Neutral	0	Low
Key Concepts Demonstrated

Flask routing and request handling

Integration of TextBlob for sentiment analysis

Polarity and subjectivity interpretation

Clean separation of logic and presentation

Web-based input processing

Limitations

The application does not handle sarcasm or complex contextual sentiment.

Accuracy depends on the language patterns recognized by TextBlob.

Assignment Compliance

Flask-based web application

TextBlob used for sentiment analysis

Sentiment classification into positive, negative, and neutral

Polarity and subjectivity scores displayed.