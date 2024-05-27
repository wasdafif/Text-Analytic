# Sentiment Analysis of Steam Reviews

## Project Description

This project aims to develop a sentiment analysis system for user reviews on Steam, a popular gaming platform. By leveraging natural language processing (NLP) techniques and machine learning algorithms, the project seeks to automatically classify user reviews into positive, negative, or neutral sentiments. This analysis can help game developers and players gain insights into the general perception of games, identify key areas for improvement, and enhance overall user experience.

## Key Features

- **Data Collection**: Scraping and aggregating user reviews from various games on Steam.
- **Text Preprocessing**: Cleaning and preparing the review texts for analysis.
- **Sentiment Classification**: Using machine learning models to classify the sentiment of each review.
- **Visualization**: Presenting the sentiment distribution and trends through interactive visualizations.

## Technologies Used

- Python
- Natural Language Processing (NLP)
- Machine Learning (e.g., scikit-learn, TensorFlow)
- Data Visualization (e.g., Matplotlib, Seaborn)

## Task Planning

1. Data Collection
    - Extract 3 popular games which are CSGO 2, Helldivers 2 and Need For Speed Unbound.
    - Using [steamreviews@0.9.5](https://pypi.org/project/steamreviews/) package to call the Steam API for reviews.
    - Expected result: reviews in JSON file format
    - Using json and pandas library to convert JSON file to CSV file format
    - Finalized CSV reviews can be acessed [here](https://drive.google.com/drive/folders/1cyj5JmU34nXtflVEVaXNJtIfuJXq6U02?usp=sharing)

2. Text Preprocessing
3. Modeling & Evaluation
4. Visualization
5. Sentiment Analysis