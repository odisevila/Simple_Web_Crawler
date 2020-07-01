# Simple_Web_Crawler
Web crawler that gets the summaries of the top 50 links from google search. 

How it works:

1. Takes a search term as input
2. Gets the top 50 links from Google
3. Scrapes the html to find the paragraphs with the text
4. Gets a summary of the text using tokenisation and scoring
5. Returns a CSV file with Title, Full Text, Link, and Summary
