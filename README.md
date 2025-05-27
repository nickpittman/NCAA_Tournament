# NCAA Tournament Analysis in Python

Every year, the top 68 teams in college basketball compete in a postseason tournament, otherwise known as March Madness. Each team is given a ranking from 1 to 16 and is divided into one of four regions. The tournament is single-elimination, allowing for lower-ranked teams to potentially “upset” their opponents. Using a Jupyter Notebook, this analysis determines which statistics are most important for a team to perform well, why Cinderella teams are so prevalent, and predicts each team’s success using multiple machine learning models. The models determined that simpler algorithms perform better, with a linear regression generating the highest out-of-sample performance. The most important features aligned with season-long statistics, including BARTHAG (the chance of beating an average Division 1 team), WAB (wins above bubble teams), and adjusted offensive efficiency.

**Machine Learning Summary (Max R-Squared)**
 1. Linear Regression: 46.06%
 2. kNN: 42.11%
 3. Weighted kNN: 41.85%
 4. Random Forest: 39.22%
 5. Decision Tree: 38.99%

Data was sourced from [Andrew Sundberg on Kaggle](https://www.kaggle.com/datasets/andrewsundberg/college-basketball-dataset)
