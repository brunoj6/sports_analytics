# Pipeline
TODO: Create a pipeline to follow and visualize it to make it simple

Rough Idea:
- Scrape data from a reliable website (the accuracy and availability of the data will augment reliability in market)
- Transform data to be easily managed 
- Compute some metaheuristics to use as variables in the later objective function
- Choose objective functions to solve for (win/loss prediction, points scored, yards run, etc.)
- Augment old data with new data and update priors (this will start as a regression but we can use ML)

# Web Scraping
We need a large amount of data to make reliable predicitons. The type of data we need at this stage does not matter too much as long as it is well organized, the more data we have the better. 

Some things to consider:
1. Data Availability: 
The more available the data is, the less effective it will be when compared in a market. The exclusivity / difficulty to access data can minutely improve guesses, giving an edge against other models. As the market has grown the data sets become larger and more widely available. This is why Bill Benter was successful in horse racing, stating that the data was a precious commodity but is now a whole new world. 

2. Multicollinearity: 
Some variables used in a prediction are high correlated and can occasionally represent the same information. This problem in collinearity can increase the weight given to identical variables more than the model intended. This phenomenon at scale can output unreliable predictions that care too heavily about a small number of factors. 


## References
The use of machine learning in sport outcome prediction: A review
https://wires.onlinelibrary.wiley.com/doi/abs/10.1002/widm.1380
