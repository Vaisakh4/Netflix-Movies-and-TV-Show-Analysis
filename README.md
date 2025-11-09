# Netflix-Movies-and-TV-Show-Analysis (Python)

# 🧾 Project Overview

This project performs a comprehensive data analysis of Netflix’s movie and TV show catalog using Python.
The goal is to uncover patterns, trends, and insights about content distribution, IMDb ratings, and audience engagement.

The analysis includes:

- Descriptive and exploratory data analysis (EDA)
- Univariate, bivariate, and multivariate exploration
- Data visualization using Matplotlib and Seaborn

# 📂 Dataset

File: Netflix TV Shows and Movies.csv
Source: Kaggle

The dataset includes the following key attributes:

- title – Name of the movie or show
- type – Movie or TV Show
- release_year – Year of release
- age_certification – Content rating (U, UA, PG-13, TV-MA, etc.)
- runtime – Duration in minutes
- imdb_score – IMDb rating
- imdb_votes – Number of IMDb votes

# ⚙️ Tools & Libraries

- Python 3.x
- pandas – Data manipulation and summarization
- matplotlib & seaborn – Visualization and exploration

# 📈 Key Visualizations

- 🍕 Pie Chart: Number of Movies vs TV Shows
- 🧁 Pie Charts: Age certification distributions for Movies and TV Shows
- 📊 Bar Plots:
  - Average IMDb Score and Votes by Type
  - Average IMDb Score and Votes by Age Certification
- 📦 Box Plot: Runtime comparison of Movies vs TV Shows
- 📉 Histogram: Distribution of IMDb Scores across titles
- 📆 Line Plot: IMDb Score trend over years (Movies vs TV Shows)
- 🎯 Scatter Plots:
  - IMDb Score vs Runtime
  - IMDb Score vs IMDb Votes
- 🔥 Correlation Heatmap: Relationship among key numeric variables

# 🧠 Key Insights

- Movies dominate Netflix’s catalogue, nearly twice as many as TV Shows.
- Mature content (R, TV-MA) is most common, showing Netflix’s focus on adult audiences.
- TV shows have slightly higher average IMDb scores, while movies receive more total votes.
- Average IMDb rating: 6.53 (median 6.6), showing good but not exceptional content quality.
= Ratings have declined post-2010, possibly due to content saturation or changing audience preferences.
- Runtime vs Rating: weak positive correlation — longer titles tend to perform marginally better.
- High-rated titles attract more votes, confirming engagement clusters around quality content.
= No strong linear correlations found — suggesting more complex, non-linear relationships.

# 💡 Recommendations / Next Steps

- Genre-Level Analysis: Identify which genres consistently achieve high IMDb scores.
- Time-Based Trends: Investigate rating drops post-2010 and their link to Netflix Originals.
- Sentiment Analysis: Analyze user reviews to understand audience perception.
- Predictive Modeling: Predict IMDb ratings or engagement using machine learning.
- Audience Segmentation: Understand demographic preferences for genres and certifications.
- Strategic Focus: Continue leveraging mature content while balancing with family-friendly shows.
