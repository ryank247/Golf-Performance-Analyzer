Golf Performance Analyzer

A personal data science project that analyzes golf performance across 39 rounds to identify which performance metrics are most strongly associated with scoring differential.

Project Overview

I built this project to answer this question: Which part of my golf game is highly correlated to scoring differential, and what can I improve?

The dataset contains 39 golf rounds from June 2025 through July 2026, including both 9-hole and 18-hole rounds. Each round contains scoring, ball-striking, short-game, putting, penalty, handicap, and date information.

The analysis was completed in Python using data cleaning, exploratory data analysis, correlation analysis, and linear regression.

Key Findings

GIR % had the strongest correlation with scoring differential at approximately -0.69 (absolute correlation shown in the notebook: 0.685).

GIR alone explained about 46.9% of the variation in scoring differential in this dataset, where as Penalties was around 27.5%.

A multiple linear regression using GIR % and penalties produced 55.1% explanation of the variation.

In the multiple regression, a 1 percentage-point increase in GIR was associated with approximately 0.155 fewer strokes in scoring differential and each additional penalty was associated with approximately 1.25 additional strokes in scoring differential, holding GIR constant.

The comparison with the pro-level benchmark showed approximately 6.7 strokes differential, suggesting that GIR and penalties do not capture performance.

Limitations

This is a relatively small, personal dataset with 39 observations, so the results are not widespread and only personal. There is also a lot of variation with a small amount of data. For the future I would include way more data, but I would need to golf more, which is a time issue.

Technologies

Python · Pandas · NumPy · Matplotlib · Scikit-learn · Jupyter Notebook · Git/GitHub

I used these to help clean data, analyze data, and create visualizations to help predict and evaluate my golf game.

Author

Ryan Koester
UW–Madison — Computer Science & Data Science