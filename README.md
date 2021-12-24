# NewsScrapper

### What is Web Scraping?
Web scraping refers to the extraction of data from a website.This information is collected and then exported into a format that is more useful for the user. 

### Libraries Used
1. __Beautiful Soup__ : Beautiful Soup provides simple methods for navigating, searching, and modifying a parse tree in HTML, XML files. It transforms a complex HTML document into a tree of Python objects. It also automatically converts the document to Unicode, so you don’t have to think about encodings. This tool not only helps you scrape but also to clean the data. 

    __To install Beautiful Soup run the following command in your conda environment :__ pip install beautifulsoup4

2. __Flask__ : Flask is Python’s micro-framework for web app development.Flask consists of Werkzeug WSGI toolkit and Jinja2 template engine.Web Server Gateway Interface (WSGI) is the standard for Python web application development and  Jinja 2 renders the web pages for the server with any specified custom content given to it by the webserver. Flask renders its HTML based templates using Jinja 2. 

    __To install Flask run the following command in your conda environment  :__ pip install Flask


## About the Project

In this project , News are Scrapped from 3 different websites and displayed on our own designed html page.

The three websites used for scrapping news are :

1. Hindi News website - [AmarUjala](https://www.amarujala.com/)
2. Cricket website - [Cricbuzz](https://www.cricbuzz.com/)
3. Technology News website - [Gadget360](https://gadgets.ndtv.com/)

After Scrapping the news from websites these news are displayed on html page.

This project can be deployed on Cloud Platforms like Heroku , AWS , GCP , Azure etc.
Link for app hosted on [Heroku](https://news-scapper-site.herokuapp.com/)
