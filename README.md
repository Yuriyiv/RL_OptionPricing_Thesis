# RL_OptionPricing_Thesis

## Pricing American Options with Reinforcement Learning: A Comparative Analysis with Classical Monte Carlo Methods

This repository demonstrates the use of **Reinforcement Learning (RL)** techniques, particularly **Least-Squares Policy Iteration (LSPI)**, for pricing American options, alongside classical methods like **Least-Squares Monte Carlo (LSMC)**. American options are complex due to the flexibility of early exercise, making accurate pricing essential for traders and financial institutions.

### Features:
- **LSPI Algorithm**: Found in `lspi_new_simple_work.ipynb`, this notebook shows the implementation and working examples of the LSPI algorithm.
- **Classical Methods**: Examples of classical Monte Carlo approaches are implemented in `notebooks/Example.ipynb`.
- **Data Generation**: Python scripts simulate asset prices using stochastic models like Geometric Brownian Motion.

### Objectives:
1. Implement and validate the **LSMC** method.
2. Implement RL algorithms such as **LSPI**, **Fitted Q-Iteration (FQI)**, and explore **Multi-Agent RL**.
3. Perform a comparative analysis between classical and RL approaches in terms of payoff, accuracy, and computational efficiency.

### Structure:
- `notebooks/`: Jupyter notebooks for LSPI and classical methods.
- `src/`: Source code for RL and LSMC implementations and asset price generation.
- `LICENSE`: Licensing information.

### How to Run:
Clone the repository and use Jupyter Notebook to run the examples in `notebooks/`.

### References:
- Longstaff, F. A., & Schwartz, E. S. (2001). *Valuing American options by simulation*.
- Li, Y. et al. (2009). *Learning exercise policies for American options*.
  
For more information, see the author and thesis proposal.
