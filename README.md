# Option-pricing-using-Monte-Carlo-Simulation

Option pricing using Monte Carlo simulation involves simulating the underlying asset price multiple times, calculating the option payoff for each simulated price path, and then averaging the payoffs to estimate the option price. The basic steps involved in option pricing using Monte Carlo simulation are as follows:

Define the parameters: Define the parameters of the option contract, including the strike price, time to maturity, and the risk-free interest rate.

Simulate the underlying asset price: Generate multiple simulated price paths for the underlying asset using a stochastic process such as Geometric Brownian Motion. The number of simulated price paths should be large enough to produce a reasonable estimate of the option price.

Calculate the option payoff: Calculate the payoff for each simulated price path using the option pricing formula. The payoff of a call option is max(S_t-K,0), where S_t is the simulated asset price at maturity and K is the strike price. The payoff of a put option is max(K-S_t,0).

Calculate the option price: Calculate the option price by averaging the payoffs of all simulated price paths and discounting the average payoff to its present value using the risk-free interest rate.

Repeat the process: Repeat the process multiple times with different random seeds to ensure the stability of the results.

The accuracy of the Monte Carlo simulation depends on the number of simulated price paths used, the quality of the stochastic process used to simulate the underlying asset price, and the accuracy of the option pricing formula.
