# Two-Period-CARA-Normal-Asset-Pricing-Model
This repository contains an implementation of a two-period asset pricing model with competitive dealers under CARA (constant absolute risk aversion) preferences and normally distributed dividends.

**What This Project Does**
- Sets up a two-date model (t = 0, 1)
- Assumes a risky asset with normally distributed dividend
- Models dealers with exponential (CARA) utility
- Derives optimal demand under mean–variance structure
- Solves for the competitive equilibrium price
- Verifies market clearing numerically

Because the model uses CARA utility and normal uncertainty, the optimization problem simplifies to a tractable mean–variance tradeoff, yielding a closed-form demand function and equilibrium price.

**Economic Intuition**
Dealers are risk-averse and therefore require compensation for holding risk. As a result, the equilibrium price is discounted relative to expected dividends. The size of this risk premium depends on:
- Risk aversion
- Dividend variance
- Aggregate supply

The equilibrium price clears the market by equating aggregate demand to total supply.

**Why This Model?**
The CARA–Normal framework is a benchmark model in asset pricing because it delivers closed-form solutions and cleanly illustrates risk-sharing mechanics. It also highlights how risk aversion shapes prices.

This implementation translates the theoretical structure directly into code, making the model computationally transparent and reproducible.
