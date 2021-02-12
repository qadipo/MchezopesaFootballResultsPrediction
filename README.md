# MchezopesaFootballResultsPrediction

**Introduction**

This problem considers the role of a football analyst at Mchezopesa who has been tasked with the role of prediction of the result of a game between Team 1 and Team 2. The prediction shall be based if who’s home and who is away, and whether or not the game is a friendly.
To solve this, two approaches shall be considered:

**1.	Polynomial Approach** – The input in this case shall be Home Team, Away Team and the Tournament Type. In this approach the following shall be trained:
a)	Rank of home team
b)	Rank of away team
c)	Tournament type

Under the polynomial approach we shall consider two models with the following outputs:

  **Model 1:** Prediction of how many goals the home team scores
  **Model 2:** Prediction of how many goals the away team scores
  
**2.	Logistic Approach** – Here Feature Engineering will be considered. We will figure out from the home team’s perspective if the game is a Win, Lose or Draw (W, L, D)
