# Option-Pricing
Project Title: Analyzing the option pricing of NVDA stock
Team Members: Kako Matsumoto 
Tier Level: Beginner

Project Description:  I used Python for this project. Using a mathematical model called Black-Scholes model, I calculated the fair price of option (both call and put option) for NVDA stock. Black-Scholes model theoretically estimates the price of European-style options. It considers factors such as the current stock price, strike price, time to expiration, risk-free interest rate and asset’s volatility to calculate the option’s premium. Using the spot price, current risk free rate and other inputs, I was able to calculate the fair prices of the option. I compared them with the market order data provided through yahoo finance. The Black-Scholes model was very accurate. I concluded we should buy the call option and should not buy the put option given today's market data. At last, I calculated delta and created the graph. Delta tells the probability that the call/put option will finish in-the-money.

Goals：Using Python and Black-Scholes model, I will calculate the fair prices of the call/put option pricing for NVDA and compare them with the market order data provided through yahoo finance in order to make a decision whether we should buy or sell the call/put option.

Challenges:
The biggest challenge was to use a class in Python. It was my first time using the class and I realized its usefulness. A class in Python is a user-defined template for creating objects. It bundles data and functions together, making it easier to manage and use them. Since we need a lot of input variables from a dataset and equation to make Black-Scholes model, the class was very useful. While using class, I also got to know about self. Self represents the instances of the class and we can access the attributes and methods of the class in Python using the “self.” I did not have any problems besides coding skill. 

Learning:
The key concepts were definitely Black-Scholes model and Python. It was the first time for me to combine programming skill and knowledge in finance. Since the financial market data gives a lot of data such as market stock price and interest rate, we can do in-depth data analysis and make investment decisions from it. I was also amazed by the accuracy of Black-Scholes model because the computed number was very close to market price. I am now convinced why many investment bankers use this model for option trading. 

