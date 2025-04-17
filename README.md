# 📱 Amazon Cell Phones Data Analysis

This project analyzes Amazon product reviews in the *Cell Phones and Accessories* category to uncover insights about customer sentiment, review trends, and product performance.

## 📊 Project Overview

The notebook performs exploratory data analysis (EDA) and visualization on a dataset of Amazon reviews. Key steps include:

- Data cleaning and preprocessing
- Exploratory visualizations (ratings distribution, review lengths, etc.)
- Text analysis of review content
- Word clouds and sentiment analysis

## 📁 Dataset

The dataset used in this project is from [Amazon Review Data (2018)](https://nijianmo.github.io/amazon/index.html), specifically the **Cell Phones and Accessories** category.

## 🚀 Running the Notebook

This notebook is designed to run on **Google Colab**. No setup required on your local machine!

### ▶️ Open in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/your-repo-name/blob/main/AmazonCellPhones_DataAnalysis.ipynb)

> Replace the link above with your actual GitHub file path.

### 📦 Required Libraries

The following libraries are used in the notebook (most are pre-installed in Colab):

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from wordcloud import WordCloud
import nltk
from sklearn.feature_extraction.text import CountVectorizer

!pip install wordcloud
!pip install nltk
🧠 Key Insights
Majority of reviews are highly positive

Text analysis shows frequent terms related to battery life, screen quality, and delivery

Word clouds highlight the most common review phrases
