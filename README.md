# Derivatives Pricing Models
- This notebook functions as a bit of an introduction to the underlying theory of options pricing, introducing some concepts like the blackscholes model, implied volatility, brownian motion, geometric brownian motion, (vanilla and exotic) options, and monte carlo techniques.
 - Naturally, the accompanying code which implements the introduced theory follows the theoretical introduction in each section
Additionally, some analysis is given to the computational benefits of vectorising particular operations in options pricing depending on the underlying assumptions / option- which can yield significantly quicker results with just small changes in the underlying code


## TABLE OF CONTENTS
- Introduction to blackscholes model & assumptions
- Implied Volatility
- Tree pricing methods for vanilla options (American / European)
- Introduction to Monte Carlo & Brownian Motion
- Extension to Geometric Brownian Motion
- Monte Carlo supporting math and theory breakdown
- Applications of MC pricing: Exotic Options
- Variance Reduction techniques in MC pricing
