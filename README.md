# twitoff_ds36
This app sees a project from end to end. Using Flask, this app also makes use of the Twitter API and builds a database for it's users and tweets. Using a built-in LogisticRegression model, this app is able to predict which of two users was more likely to have said a tweet that you type into it. In order to work, you must first look up two users you would like to compare and add them to the database. After that, you type in a blurb of text which the app then compares to all the tweets of the two chosen users and in turn returns the user it would hypothetically most likely pertin to.

*Note: HTML was provided for us, rest of the project was guided.

# Main Features
* Word Embedding: Passes tweet text through pre-trained NLP Model--Word2Vec that turns tweet text into numeric representation
* Twitter API: makes use of Twitter API to retrieve tweets and respective users
* Flask: utilizes Flask to deploy simple application
* Logistic Regression: makes use of sklearn's LogisticRegression model to make classification predictions
* Heroku: uses Heroku's service to launch application based on their cloud services.

# Where to get it
Link to application: https://twitoff-ds366.herokuapp.com/

# Dependencies
* **Flask**: render_template, request
* **SQLAlchemy** to create database
* **Numpy** to make arrays of tweets
* sklearn to import LogisticRegression for predictions
* **os**: getenv for API keys

# License
License can be found in Twitoff folder