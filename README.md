# CodeAlpha Sentiment Analysis Project

##  Project Title

**Sentiment Analysis of Product Reviews using Python, NLTK VADER and Plotly**

##  Project Objective

The objective of this project is to analyze textual product reviews and classify them into three sentiment categories: Positive, Neutral, and Negative.

The project demonstrates how Natural Language Processing (NLP) and sentiment analysis can be used to convert customer feedback into meaningful insights.

##  Dataset

The project uses a sample dataset containing **30 product reviews**.

### Dataset Columns

- **Review** – Original product review
- **Cleaned_Review** – Preprocessed review text
- **Sentiment_Score** – VADER compound sentiment score
- **Sentiment** – Positive, Neutral, or Negative classification

> **Note:** The reviews used in this project are sample reviews created for demonstration and analysis purposes.

##  Technologies Used

- Python
- Pandas
- NLTK
- VADER Sentiment Analyzer
- Plotly
- Google Colab

##  Project Workflow

**Review Dataset → Text Cleaning → Sentiment Analysis → Sentiment Classification → Visualization → Insights**

##  Data Preprocessing

The review text was cleaned before performing sentiment analysis.

The preprocessing steps include:

- Converting text to lowercase
- Removing URLs
- Removing special characters
- Removing unnecessary spaces

##  Sentiment Analysis

NLTK's **VADER (Valence Aware Dictionary and sEntiment Reasoner)** was used to calculate the sentiment score of each review.

The compound sentiment score was used for classification:

- **Score ≥ 0.05 → Positive**
- **Score ≤ -0.05 → Negative**
- **Between -0.05 and 0.05 → Neutral**

##  Visualizations

The project includes the following visualizations:

### 1. Sentiment Distribution

A bar chart showing the number of Positive, Neutral, and Negative reviews.

### 2. Sentiment Score Distribution

A histogram showing the distribution of sentiment scores across the reviews.

### 3. Overall Sentiment Percentage

A donut-style pie chart showing the percentage of reviews belonging to each sentiment category.

##  Key Findings

- Product reviews can be classified into Positive, Neutral, and Negative categories using VADER.
- Positive reviews represent favorable customer opinions.
- Negative reviews indicate dissatisfaction or unfavorable experiences.
- Neutral reviews represent balanced or less emotionally expressed opinions.
- Sentiment scores indicate both the direction and strength of the sentiment.
- Visualizations make it easier to understand the overall sentiment pattern.

##  Business Insights

Sentiment analysis can help businesses:

- Understand customer opinions efficiently.
- Identify aspects appreciated by customers.
- Detect negative feedback and improvement areas.
- Monitor overall customer sentiment.
- Support data-driven decision making.

##  Project Files

- `CodeAlpha_SentimentAnalysis.ipynb` – Complete sentiment analysis notebook
- `reviews.csv` – Review dataset
- `README.md` – Project documentation

##  Internship Task

**CodeAlpha Data Analytics Internship – Task 4: Sentiment Analysis**

##  Conclusion

This project demonstrates the complete process of sentiment analysis using Python and VADER.

The reviews were cleaned, analyzed, assigned sentiment scores, classified into Positive, Neutral, and Negative categories, and visualized using Plotly.

The project provided practical experience in text preprocessing, Natural Language Processing, sentiment classification, data visualization, and interpretation of customer feedback.
