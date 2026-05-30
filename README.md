# Twitter Sentiment Analysis

## Overview

Social media platforms generate massive amounts of user opinions and feedback every day. Analyzing these sentiments helps organizations, brands, and researchers understand public perception, customer satisfaction, and emerging trends.

This project performs Exploratory Data Analysis (EDA) and Sentiment Analysis on a Twitter Sentiment Analysis Dataset. The objective is to identify sentiment patterns across various topics and brands, visualize public opinions, and uncover meaningful insights from social media conversations.

---

## Task Objective

Analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes towards specific topics or brands.

---

## Dataset Information

### Dataset Name

Twitter Sentiment Analysis Dataset

### Dataset Description

This is an entity-level sentiment analysis dataset collected from Twitter. Given a tweet and an associated entity (topic/brand), the goal is to determine the sentiment expressed towards that entity.

### Sentiment Categories

* Positive
* Negative
* Neutral
* Irrelevant

### Dataset Features

| Column    | Description                    |
| --------- | ------------------------------ |
| ID        | Unique identifier              |
| Topic     | Topic or brand being discussed |
| Sentiment | Sentiment label                |
| Text      | Tweet content                  |

### Dataset Availability

The dataset CSV file is included directly in this repository.

---

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* WordCloud

---

## Project Workflow

### 1. Importing the Necessary Libraries

Imported Python libraries required for data preprocessing, analysis, and visualization.

### 2. Data Loading

Loaded the Twitter sentiment dataset into a Pandas DataFrame.

### 3. Data Exploration

Performed:

* Dataset shape analysis
* Data type inspection
* Summary statistics
* Unique sentiment identification

### 4. Data Cleaning

* Handled missing values
* Removed duplicate records
* Verified data consistency

### 5. Exploratory Data Analysis

#### Topic Analysis

* Topic frequency distribution
* Most discussed topics

#### Sentiment Analysis

* Overall sentiment distribution
* Sentiment percentages
* Topic-wise sentiment comparison

#### Brand Analysis

Analyzed sentiment distributions for:

* Google
* Microsoft

#### Message Analysis

* Tweet length distribution
* Message length by sentiment category

### 6. Data Visualization

Generated:

* Bar Charts
* Pie Charts
* Count Plots
* Heatmaps
* Word Clouds
* Box Plots
* Distribution Plots

---

## Project Structure

```text
Twitter-Sentiment-Analysis/
│
├── twitter_training.csv
├── Twitter_Sentiment_Analysis.ipynb
├── README.md
└── requirements.txt
```

---

## Key Findings

### Most Discussed Topic

* TomClancyRainbowSix emerged as the most frequently discussed topic.

### Overall Sentiment Distribution

* Negative Sentiment: 30.3%
* Positive Sentiment: 27.5%
* Neutral Sentiment: 24.7%
* Irrelevant Sentiment: 17.5%

### Brand Sentiment Analysis

* Google discussions were predominantly Neutral.
* Microsoft discussions were predominantly Neutral.

### Message Length Analysis

* Most tweets contained fewer than 400 words.
* Users generally expressed opinions concisely.

### Topic-Specific Insights

* Sentiment distribution varied significantly across topics.
* Certain topics generated more negative discussions compared to others.

---

## Visualizations Included

* Topic Frequency Analysis
* Overall Sentiment Distribution
* Topic-wise Sentiment Analysis
* Top Positive Topics
* Top Negative Topics
* Top Neutral Topics
* Top Irrelevant Topics
* Google Sentiment Analysis
* Microsoft Sentiment Analysis
* Tweet Length Distribution
* Topic vs Sentiment Heatmap
* Topic Word Cloud
* Tweet Text Word Cloud

---

## Learning Outcomes

Through this project, I gained experience in:

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Sentiment Analysis
* Data Visualization
* Text-Based Data Analysis
* Insight Generation from Social Media Data

---

## Future Enhancements

* NLP-based Text Preprocessing
* Sentiment Classification using Machine Learning
* Real-Time Twitter Sentiment Tracking
* Interactive Dashboard using Streamlit or Power BI
* Topic Modeling and Trend Detection

---

## Author

Mandrita Dasgupta

Data Analytics | Data Science | Machine Learning | NLP
