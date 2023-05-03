# Fama-French-Model

Algo idea:
- uses Fama-French 5 factor model to find the estimated factor exposure for each individual stock
- done through regression (using sklearn)
- use the model to estimate the expected weekly rolling return
- if the weekly rolling return is greater than the actual return to a certain degree
  - buy a set amount of shares of that stock
- if the weekly rolling return is less than the actual return to a certain degree
  - sell a set amount of shares of that stock

Analysis:
- check how well the Fama-French model estimates stock prices
- check how the portfolio will perform vs other trading strategies
