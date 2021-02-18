# Machine-Learning-Comparison-Between-a-Polynomial-and-Logistic-Approach-to-Predicting-Game-Results
In this REPO we use Machine Learning to Predict results of a game between team 1 and team 2, based on who's home and who's away, and on whether or not the game is friendly.

A. Specifying the Data Analytic Question:
  Predict results of a game between team 1 and team 2, based on who's home and who's away, and on whether or not the game is friendly (include rank in your training).

B. Defining the Metric for Success:
  i. Achieve OPTIMUM accuracy in modelling
  ii. Achieve an R.M.S.E. Score less than 10% of the mean of the actual data

C. Understanding the context:
We have two possible approaches given the datasets we have:
Input: Home team, Away team, Tournament type (World cup, Friendly, Other)

  Approach 1: Polynomial approach:

  What to train given:
    i. Rank of home team 
    ii. Rank of away team 
    iii. Tournament type 
    
Model 1: Predict how many goals the home team scores
Model 2: Predict how many goals the away team scores

  Approach 2: Logistic approach:
    Feature Engineering: 
    Figure out from the home team’s perspective if the game is a Win, Lose or Draw (W, L, D)
