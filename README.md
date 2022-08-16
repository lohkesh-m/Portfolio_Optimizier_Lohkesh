## Portfolio Optimizier 

The main aim of this project is to use mathematical techniques like Convex Optimization and Monte Carlo Simulations to optimize a portfolio according to the risk constraints.
Apart from that we add other constraints like long-only, or even sector, single stock, or turnover constraints.
In this implementation I've added sector constraints to the portfolio

### Monte Carlo Simulation
This is the brute force approach to finding the best portfolio, works well if you have lower number of assets, but its computationally heavy.
You can see the pictures of the Efficient Frontier and the maximum sharpe portfolio in the Monte-Carlo Simulation Optimizer

### Convex Optimization
This is the mathematical way where you define a convex optimization problem and then solve it using a CP solver.

### Black Litterman Model
In the Black Litterman Model, the inputs are the expected returns using factor models and then using the above optimizers to optimize the portfolio

### Utility Theory
Here instead of maximizing sharpe or returns, we maximize the expected utility of our portfolio, which is calculated from a certain utility function which relates returns and utility. 
