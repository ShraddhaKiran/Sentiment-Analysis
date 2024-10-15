# Sentiment-Analysis

# Overview
This project aims to perform Sentiment Analysis on product reviews to identify and classify the sentiment (positive, negative, or neutral). The analysis is based on Natural Language Processing (NLP) techniques using Python libraries.

# Project Structure
- **Data Exploration**: Perform Exploratory Data Analysis (EDA) to understand the distribution of reviews, their sentiment scores, and text characteristics.
- **Text Preprocessing**: Tokenization, lemmatization, and removal of stop words.
- **Sentiment Classification**: Utilize pre-trained models like VADER from nltk for sentiment scoring.
- **Visualization**: Insights are visualized using matplotlib and seaborn to display trends and patterns in the data.

# Key Libraries Used
- **pandas**: Data manipulation and handling.
- **numpy**: Numerical operations.
- **matplotlib & seaborn**: Data visualization.
- **nltk**: Natural Language Processing toolkit for text analysis and sentiment scoring.

# Dataset
The dataset consists of product reviews, including the following fields:

**ProductId**: Unique identifier for the product.
**UserId**: Unique identifier for the user.
**ProfileName**: Name of the reviewer.
**Score**: Rating given by the user.
**Summary**: Short description of the review.
**Text**: Full review text.


# Steps
**Data Preprocessing**:

- Tokenization of text data.
- Removal of stop words and punctuation.
- Lemmatization to reduce words to their base form.
- 
**Sentiment Analysis:**
- Using nltk's VADER lexicon to classify the sentiment as positive, neutral, or negative.
- Explore sentiment distribution using various visualizations.
- 
**Exploratory Data Analysis (EDA)**:
- Visualize the distribution of review scores, helpfulness, and sentiments.
- Identify key patterns in text data.
  
**Visualizations**
- Sentiment distribution across reviews.
- Relationship between review scores and sentiment.
- Word clouds showcasing frequently used words in positive and negative reviews.
  
**Results**
The project results in a clear understanding of customer sentiments based on textual reviews. It provides insights into how product reviews align with ratings and helps identify common themes in positive or negative reviews.

