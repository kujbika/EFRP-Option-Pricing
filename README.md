# Option pricing methods
*__Marcell Kujbus, Financial Mathematician/Empirical Finance Researcher__* <br>
This folder consists of a GARCH based option pricing code. It was a school team project for the Special Empirical Finance Research progamme: I worked on that with 3 friends of mine. <br>
After downloading an arbitrary asset's price chart based on a ticker, I fit an ARIMA(1,1,1)-GARCH(1,1) model to catch the dynamics of the price process. 
Based on the model's efficiency, 1000 trajectories are getting simulated, and both the call and the put option gets its price according to the expected value pricing formula.
Based on such plots where the option prices get drawn versus the strike price, the empirical method that I implemented is perfectly accurate.
What is the difference between the the price of the estimation and the Black-Scholes price?
What is the reason for this?
