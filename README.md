# Just How Profitable Are BlumHouse Movies?

## Project Overview

This project aims to explore and analyze key trends related to Blumhouse Productions, a film production company known for its low-budget horror films with significant box office returns. The analysis focuses on various aspects like production budgets, return on investment (ROI), and how movie characteristics such as ratings, directors, and release years influence profitability. By conducting both exploratory data analysis (EDA) and more advanced analysis, the project seeks to answer questions about budget allocation, box office performance, and other business insights for Blumhouse movies.

The dataset was scraped from various sources using BeautifulSoup and contains details about Blumhouse movies such as their production budgets, worldwide box office earnings, and IMDB and Tomatometer scores.

## Tools Used
Python 3.x
Pandas: For data manipulation and analysis
Matplotlib/Seaborn: For data visualization
BeautifulSoup: For web scraping the dataset
JupyterLab: For interactive data exploration and documentation

## Dataset Description
The dataset used for this project contains information about Blumhouse movies, including:

Movie Title: Name of the film
Production Budget: The budget allocated to the movie
Worldwide Box Office: Total box office earnings worldwide
IMDB Rating: User ratings from IMDB
Tomatometer Score: Critic ratings from Rotten Tomatoes
MPAA Rating: The MPAA classification of the film (e.g., R, PG-13)
Director: Name of the movie's director
Lead Actor/Actress: The main cast of the movie
Release Year: The year the movie was released
ROI: Return on Investment, calculated as (Worldwide Box Office - Production Budget) / Production Budget
Additional Columns Created:
Budget Range: The budget categorized into ranges for further analysis.
Complete Data: A flag indicating if the movie has complete data for critical columns (production budget, box office, and ROI).

## Project Structure
