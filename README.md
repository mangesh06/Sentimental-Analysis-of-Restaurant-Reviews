# README: Yelp Dataset Analysis

## Overview
This project analyzes Yelp reviews to understand food trends and customer preferences in California, specifically comparing pre-COVID (2018) and post-COVID (2021) data. The analysis aims to assist a food critic in publishing a blog post for business owners in the food industry, providing insights into evolving customer satisfaction and preferences.

## Project Phases
1. **Data Cleaning**
2. **Exploratory Data Analysis**
3. **Sentiment Analysis**
4. **BERT Topic Modelling**

## Data Cleaning
- **Filtering Criteria**: 
  - Only included data from California.
  - Focused on restaurant categories.
  - Compared data from the years 2018 (pre-COVID) and 2021 (post-COVID).
- **Resulting Dataset**:
  - Columns: 23
  - Rows: 42,422

## Exploratory Data Analysis (EDA)
- **Time Series Analysis**: Monthly distribution of reviews showed a decrease in 2021 due to COVID-19.
- **Box Plot & Bar Chart Analysis**: Correlation analysis found no significant insights between most columns.
- **Summary Statistics**: Added columns for sentiment score and text length for further analysis.

## Sentiment Analysis
- **Text Preprocessing**:
  - Lowercasing
  - Removing special characters and punctuations
  - Tokenization
  - Removing stop words
  - Lemmatization
- **Sentiment Scores**:
  - Positive: Polarity score >= 0.5
  - Negative: Polarity score <= -0.5
  - Neutral: -0.5 < Polarity score < 0.5
- **Findings**: 
  - Reviews decreased in 2021 compared to 2018.
  - Sentiment distribution remained similar across both years.

## BERT Topic Modelling
- **Length Distribution**:
  - 2018: Longest review length was 470 words with 133 topics.
  - 2021: Longest review length was 510 words with 103 topics.
- **Topic Analysis**:
  - Notable change: Introduction of Japanese cuisine as a popular topic in 2021.
  - Time Series Analysis: Peak review periods were from May to July, with noticeable differences in coffee shop reviews.

## Key Findings and Conclusion
- **Review Decline**:
  - Overall, restaurant patronage decreased in 2021.
  - Specific drop in coffee shop reviews due to a shift towards working from home.
- **Changes from 2018 to 2021**:
  - Increased popularity of Japanese food, likely due to its association with freshness and healthfulness.
- **Future Steps**:
  - Identify restaurant categories with the most significant drop in reviews.
  - Further explore market preferences post-COVID.

## Conclusion
The analysis provided valuable insights into the food industry trends in California, pre- and post-COVID. This information can help business owners understand changing customer preferences and improve their offerings accordingly.

For detailed information and visualizations, please refer to the attached presentation: [Yelp Dataset Analysis.pptx]