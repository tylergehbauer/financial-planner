# financial-planner
Unit 5 Homework Assignment: API's
----
I completede this assignment over break, so the 'current date' I used was December 31st, 2021.
The current Eth price and Bitcoin price are probably going to be different the date this is graded since the prices are pretty volatile currently.
---
For this assignment I used MCForecastTools.py to run the monte carlo simulations and for analysis.
---
>#Part 1:
Part 1 of the assignment involved fetching current prices for Eth and BTC using the requests library and invovled using Alpaca API to fetch the stock and bond closing prices for SKY and AGG.

Creating the data frames, plots, and the required calculations were all very similar to what we did in the class activities. 
---
>#Part 2:
Part 2 of the assignment involed using the api.get_barset() to create a dataframe of stock and bond data, and using the MCForecastTools.py to run a monte carlo simulation.
The parameters (weights,number of simulations, and number of trading days) were as requested in the assignment instrucitons. 
---
>#Optional Early Retirement:
For the 5 year retirement section all I changed for the monte carlo simulation were the weights. I changed it so that SKY was 70% and AGG was 30%
This resulted in a wrose retirment plan in my opinon than than the one in part 2. 

For the 10 year retirement plan, I used the same framework for the monte carlo simultion as in part 2, however made the inital investment larger.
This resulted in a pretty decent short term retirment plan.

Overall, this assignment was pretty straight forward since many of the tasks were very similar to what we did in class. 

