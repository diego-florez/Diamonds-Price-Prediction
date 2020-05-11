# Diamonds-Price-Prediction

# 1 Intro:
In this repository you will find 5 notebooks:
  - Descriptive Analysis: a detailed descriptive analysis of the dataset
  - Linear Models Dummies: the cleaned dataset enconded with dummy variables and trained and tested in linear regression models
  - Linear Models Ordinal: the cleaned dataset enconded with ordinal variables and trained and tested in linear regression models
  - Non Linear Models Dummies: the cleaned dataset enconded with dummy variables and trained and tested in non linear regression models
  - Non Linear Models Ordina: the cleaned dataset enconded with ordinal variables and trained and tested in non linear regression models

# 2 Goals:
The goal of the project is to predict the price of diamonds based in its carat, cut, color, clarity, depth%, table and volume/size. The measure unit is rmse

# 3 Steps:
To fulfil the previous goals the next steps have been done:

INPUT (2 datasets from Kaggle (1 to train, 1 to test))
src (additional info as diamond images, diamond variables schema and possible models to implement)
main (the 5 notebooks explained previously)
OUTPUT (the predicted price of the diamonds of the best models)

# 4 Final Output:
The final output are the predicted prices of the best models. The best score (in rmse) was achieved with an Extra Trees Model, with a previous dummy encoding (one hot encoding). The score was: rmse = 532.01097
