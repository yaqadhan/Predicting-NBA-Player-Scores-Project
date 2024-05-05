## Predicting NPA Scores
### A Comparison of the Ability of Regression Models to Predicting Total Points BY NBA Player


### STAT 451 - Sports Statistics and Analytics II Spring 2024 - Final Project

### Created by Alyaqadhan Alfahdi



Overview
-------------------

In this project, we looked at data from NBA Statistics in 2023 to see if we could predict how many points players would score in the next season. We used a smart statistics trick called Principal Component Analysis to make the data easier to work with by focusing on the most important factors affecting the total points. Then, we tried out different ways of predicting scores, like making many decision trees with Random Forest, looking at the nearest neighbors with KNN, and drawing the best line with SVM. In the end, the SVM way was the best at predicting the player's scores. The SVM model outperformed others, achieving the lowest RMSE (0.088) and the highest R-squared value (0.991), indicating its superior predictive ability. These results show the possibility of using statistics and machine learning to predict sports performance and provide insight into the significance of proper data processing and modeling selection in predicting athletic performance. The work will be beneficial to teams and sports analysts in their decision-making process that is based on data.

-------------------


Project Structure
-------------------

project.Rmd: detailing exploratory data analysis, model creation, and all evaluation metrics

2023_nba_player_stats.csv: Dataset utilized within our project sourced from https://www.kaggle.com/datasets/amirhosseinmirzaie/nba-players-stats2023-season

NPA presentation.pdf: Our slide deck for presentation

-------------------
