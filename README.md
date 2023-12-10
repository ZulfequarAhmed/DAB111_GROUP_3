# DAB111_GROUP_3

Project Name: DAB111_project_Group_3

Group Members:
1.Anagha Paul-0826455

2.Siril Kumar Reddy Kandula-0851953

3.Zulfequar Ahmed Syed-0851593

## Project Objective
This project involves the usage of BeautifulSoup,Python,Pandas,SQLite, and Flask.Using BeautifulSoup , we have extracted data from the website and store it in a database using the SQLite3 package.
Flask is used to present the stored data from the database on the web.The website contains mainly three pages: Home, About, and Dataset.The About Us page provides details about each variable definition
The website displays the list of best selling books.

## Overview
This project revolves around scrapping the data from the website using BeautifulSoup,integrating this data into an SQLite database using the sqlite3 package in Python, and subsequently visualizing these records within a table.
Utilizing Python's SQLite integration for data storage, Flask for web development, HTML for content structure, CSS for styling, this project aims to create an interactive website that showcases and allows exploration of the list of best selling books in a user-friendly manner.

## Source of data
The data is Scrapped from the website https://en.wikipedia.org/wiki/List_of_best-selling_books.

## Features
Website is Scrapped using BeautifulSoup
Data collection and storage in an SQLite database.
Website presentation using Flask which includes basic formatting.
The About page provides information about the data source and variable definitions.
Data page displays the data or a sample thereof.

## Structure
app.py: Main Flask application file.
main_file.py: File for database creation and data insertion.
templates/: Directory containing HTML templates for the website.

## Running the Application
Install dependencies using pip install -r requirements.txt.
Run the Flask application: python app.py.
