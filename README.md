# 4th Down, Should You Go For It?

A data science final project for CMSC320 at the University of Maryland (2021), by Rishi Nangia and Rikhin Bhuta.

**The question:** when should a team go for it on 4th down instead of kicking a field goal?

## What we did

- Used a public NFL play-by-play dataset (regular seasons 2009 to 2018, originally collected by the nflscrapR researchers and shared on Kaggle and GitHub), trimmed to the fields we needed.
- Cleaned and prepared the data with pandas.
- Charted 4th down attempts and conversion rates by season, by yards to go, and by yard line.
- Fit linear regression models of conversion rate against yard line and distance to the first down. They explained only a modest share of the variation (R² around 0.16), so we stopped short of calling it a prediction tool.
- Compared conversion odds with field goal odds across field position and distance, and pointed out the zones where going for it looked better than kicking.

## Tools

Python, pandas, NumPy, Matplotlib, seaborn, scikit-learn, statsmodels, SciPy, Jupyter.

## Read it

[The full write-up](https://rikhin99.github.io/nfl-4th-down-analysis/)

*This is a student project from 2021, published as the course's final-project deliverable. It shows how we approached the question, not a production model.*
