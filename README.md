## Main Projects

This folder contains projects related to the following subjects:

### Sports Betting Market Tools

This project explores a wide range of sports betting markets through toy models. The goal is to showcase how market information can be used, how betting models can be evaluated, how betting strategies can be developed, and how market simulations can be performed.

The main sections of this project are:

1. **Using Betting Market Information**
   A model for estimating expected goals (xG) values for a match based on market prices, weighted by liquidity.

2. **Model Average ROI Estimator**
   A Bayesian mixture model used to estimate the ROI of a betting model, combined with the probability that the model is profitable given betting prices and model estimation data.

3. **Kelly Criterion Adjustments**
   An exploration of variations and different applications of the Kelly Criterion.

4. **Reactive Markets to Liquidity**
   A model for analyzing how betting markets adjust to liquidity and potential market manipulation.

---

### Football Statistical Modeling

The goal of this project is to build an advanced football prediction model by extracting as much information as possible from football data.

The process starts with models based only on match results, then moves to expected goals (xG) and expected threat (xT) models using action-level data. Finally, these models and sources of information are combined into a more advanced football prediction framework.

The projects included in this folder are:

1. **Match Result-Based Modeling**
   Creating models based on match result information using multiple approaches.

2. **Simple xG Model**
   Building a basic expected goals model.

3. **Advanced xG Model**
   Developing a more advanced expected goals model using richer football data.

4. **Expected Threat (xT) Model**
   Creating an expected threat model based on action-level data.

5. **Team and Player xG-Based Modeling**
   Building models based on teams’ and players’ expected goals information.

6. **Advanced Football Prediction Model**
   Combining previous models and information sources into a comprehensive football prediction model.

---

Simpler small projects:
1) Market_Efficiency.ipynb :
A oversimplified approach on top football leagues showing the main markets great accuracy, comparing opening lines with closing lines for testing if the markets are efficient predictors and proving that margins are correctly adjusted for ensuring long term profitability for bookies.

2) EURO_2024_SIM : Simulation of the European Championship 2024 based on the assumption that football games follow poisson distribution, given strength ratings for the
   participating teams.
