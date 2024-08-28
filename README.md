# Flask Meme Website

This project is a simple web application built using Flask that fetches random memes from an API and displays them on a webpage.
The webpage automatically refreshes every 15 seconds to show a new meme, along with the name of the subreddit from which the meme was sourced.

• Features

1. Fetches a random meme from the Meme API.

2. Displays the meme along with the associated subreddit.

3. Auto-refreshes every 15 seconds to show a new meme.

• Installation:

Clone the repository:
  
    git clone https://github.com/raulyug/flask-meme-site.git
    cd flask-meme-website

Set up a virtual environment (optional but recommended):
   
    py -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

Install the required dependencies:
    
    pip install Flask requests

• Usage

Run the Flask application:
  
    py meme_flask.py
  
Access the application:
  
Open your web browser and navigate to http://127.0.0.1:80/ to view the website.
