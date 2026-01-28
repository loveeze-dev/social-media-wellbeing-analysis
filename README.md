# Social Media Usage and Emotional Well-Being Analysis

## Overview
This project explores the relationship between social media engagement patterns and emotional well-being, focusing on how daily usage time, platform choice, and interaction metrics (likes, comments, messages) correlate with happiness and anxiety levels.

Using statistical analysis and machine learning techniques, the study uncovers actionable insights into healthier digital habits across different age groups and platforms.

This project was completed as part of my **MSci in Data Science** and demonstrates applied data analysis, statistical modelling, and data storytelling skills.

---

## What I Did
- Cleaned and preprocessed a real-world social media dataset
- Performed exploratory data analysis (EDA) and statistical correlation testing
- Built and evaluated regression models to quantify emotional outcomes
- Interpreted results to produce actionable, real-world insights

---

## Skills & Tools
- **Languages & Libraries**: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, SciPy  
- **Techniques**: Exploratory Data Analysis (EDA), Statistical Testing (Pearson & Spearman), Linear Regression, Feature Engineering  
- **Data Skills**: Data cleaning, outlier handling, correlation analysis, demographic segmentation  

---

## Key Findings

### Usage Patterns
- The majority of users spend 1–3 hours daily on social media
- Younger users (18–35) show the highest engagement (median >2.5 hours/day)
- Older users (35+) exhibit more moderate usage (<1.5 hours/day) and more stable emotional outcomes

### Emotional Insights
- Happiness is strongly correlated with engagement metrics:
  - Likes received: r = 0.68
  - Comments received: r = 0.64
  - Messages sent: r = 0.59
- Anxiety shows minimal correlation with likes/comments but increases with excessive messaging behaviour
- A weak negative correlation between happiness and anxiety (-0.23) suggests users oscillate between emotional states

### Platform-Specific Patterns
- **Instagram**: Highest daily usage and stronger association with anxiety
- **Twitter**: Mixed emotional responses (boredom to happiness)
- **Facebook**: Balanced usage with relatively neutral emotional outcomes

---

## Statistical Models

| Emotion   | R²    | RMSE | Key Predictors |
|----------|-------|------|----------------|
| Happiness | 0.461 | 0.294 | Likes, Comments (positive effect) |
| Anxiety   | 0.037 | 0.369 | Messages Sent (positive), Posts (negative) |

**Total Interactions Analysis**
- Happiness: Statistically significant relationship (p < 0.001, coefficient = 0.068)
- Anxiety: No statistically significant relationship (p = 0.879)

---

## Visualisations
The notebook includes:
- Distribution of daily social media usage time
- Emotion–platform heatmaps
- Age-group comparisons of usage and emotional responses
- Correlation matrices highlighting engagement–wellbeing relationships

---

## Project Structure
├── social-media-wellbeing-analysis.ipynb
├── train.csv
└── README.md

---

## How to Run
1. Clone this repository
2. Install dependencies: pip install pandas numpy seaborn matplotlib scikit-learn scipy
3. Open `social-media-wellbeing-analysis.ipynb` in Jupyter Notebook or JupyterLab
4. Run all cells to reproduce the analysis

---

## Dataset
Source: *Social Media Usage and Emotional Well-Being*  
Author: Emirhan Bulut (2024)

Key variables include:
- Daily usage time (minutes)
- Dominant emotion (happiness, anxiety, boredom, anger)
- Platform (Instagram, Twitter, Facebook, TikTok)
- Engagement metrics (likes, comments, messages, posts)
- Demographics (age, gender)

---

## Key Takeaways
This analysis shows that social media engagement can enhance happiness through interaction and validation, but excessive or compulsive use—particularly messaging—correlates with increased anxiety.

The findings highlight the importance of:
- Moderation in daily usage
- Mindful engagement over passive consumption
- Age-aware interventions for younger users
- Platform design that promotes positive interaction

---

*This project demonstrates end-to-end data analysis skills, including data cleaning, exploratory analysis, statistical testing, regression modelling, and data-driven storytelling.*