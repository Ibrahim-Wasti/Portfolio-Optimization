# Portfolio-Optimization - Program that uses the Sharpe Ratio to retrun recommendations for an optimized protfolio strategy.

1) Takes as input a list of tickers, the desired satrt date, a list of the weight of each ticker relative to its position in the tickers list, and the total amount invested i USD
2) Optional arguments:
    - End date is predfined to the current day, however can be specified
    - Graph: predefined as False. If True then will return a time series graph for each ticker in the tickers list
    - Verbose: predefined as True and will return Expected Annual returns, Vaolatility, & Volume in addition to the Sharpe Ratio an drecommendations. If False, will only return Sharpe ratio and recommendations.

Pulls data from the av-daily-adjusted API.
