# News Article Summarizer and Sentiment Analyzer
## Overview
This project is a Python-based application that summarizes news articles and performs sentiment analysis on them. It features a custom GUI built with Tkinter, allowing users to input a URL, retrieve the article's summary, and analyze its sentiment.

## Features
**Article Summarization:** Automatically summarizes the content of a news article.<br>
**Sentiment Analysis:** Analyzes the sentiment of the article, categorizing it as positive, negative, or neutral based on the text's polarity.<br>
**Custom GUI:** Provides a user-friendly interface to input URLs and display the results.<br>
## Requirements
Python 3.x<br>
nltk<br>
textblob<br>
newspaper3k<br>
tkinter (Usually comes with Python by default)<br>
## Installation
**Clone the repository:**<br>
git clone https://github.com/yourusername/news-summarizer.git<br>
cd news-summarizer<br>
**Install the required libraries:**<br>
pip install nltk textblob newspaper3k<br>
**Download NLTK data:**<br>
import nltk<br>
nltk.download('punkt')<br>
## Usage
**Run the application:**<br>
python main.py<br>
**Input the URL:**<br>
Paste the URL of the news article you want to summarize into the text field labeled "URL."<br>
Click the "Summarize" button.<br>
**View the results:**<br>
The title, authors, publication date, summary, and sentiment analysis of the article will be displayed in the GUI.<br>
## Example
After entering the URL of a news article and clicking the "Summarize" button, the application will display:

**Title:** The title of the article.<br>
**Authors:** The names of the authors.<br>
**Publication Date:** The date the article was published.<br>
**Summary:** A concise summary of the article.<br>
**Sentiment Analysis:** The sentiment polarity and a corresponding sentiment label (positive, negative, or neutral).<br>
