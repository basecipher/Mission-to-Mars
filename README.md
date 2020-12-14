# Mission-to-Mars
Written with Python

## Overview of Project

Robin's web app is looking good and functioning well, but she wants to add more polish to it. She had been admiring images of Mars’s hemispheres online and realized that the site is scraping-friendly. She would like to adjust the current web app to include all of the hemisphere images. To do this, you’ll use BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images, store the scraped data on a Mongo database, use a web application to display the data, and alter the design of the web app to accommodate these images.

### Purpose
1. Scrape Full-Resolution Mars Hemisphere Images and Titles
2. Update the Web App with Mars Hemisphere Images and Titles
3. Add Bootstrap 3 Components


## Resources
* Python 3.7.6, Visual Studio Code 1.50.1, MongodB, Splinter dependency and Flask.

## Summary
* Code is written that retrieves full-resolution images and titles of the four hemisphere images with full-resolution images are added to the dictionary with all four hemisphere image titles are added to the dictionary.
* The dictionary that contains full-resolution image URLs and image titles is added to a list while the scraping.py file is updated and retrieves of the full-resolution image URLs and titles. 
* The mongo database is updated to contain all of the full-resolution image URLs and titles with index.html file containing code that displays the full-resolution image URLs and titles. 
* The web app contains all of the information from this module and as well as full-resolution images and titles of the four hemisphere images and the webpage is mobile responsive and additional Bootstrap 3 components are used to style the webpage.

## Challenge Overview
It was a bit challenging differentiating code between div tags in html but using builtin in browser inspection tools helped focus on section of webpage code at a time.

