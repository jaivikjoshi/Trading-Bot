# Trading-Bot
A Trading Algorithm I created 


To make this trading bot, I used the breakout trading strategy, which is when you wait for the price to become a new high, then you buy it and then you sell it when it has dropped past a certain point. 
Unfortunately, unlike us humans AI cannot use judgement to choose when to sell the property. So to combat this, we would need to have a set definition for the breakout point and the sell point. 
Ie for the breakout point, we would look at the closing price for the last 3 months and have the highest point be the breakout point. If the price of the instrument ever goes above the breakout point, you would buy the property. 
But 3 months is a very standard amount of time, and it is not going to work for every case. To fix this issue, I choose to implement a dynamic method, which would use the volatility to see how far back it should look for the given property. If it has high volatility it would look back further, then if it was low volatility. 


This project is also showcased on QuantConnect Below:

https://www.quantconnect.com/project/16755692
