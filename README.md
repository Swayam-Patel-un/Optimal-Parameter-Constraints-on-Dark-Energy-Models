# Optimal Parameter Constraints on Dark Energy Models

This project explores the **puzzling realm of dark energy** and investigates **alternative cosmological models** to uncover the mysteries of the universe's accelerated expansion. The phenomenon, often attributed to **dark energy**, makes up a significant portion of the universe's energy content and challenges the standard cosmological model. 

Our work aims to analyze observational discrepancies in the standard model, which includes the **cosmological constant (ΛCDM)**. These discrepancies call for the exploration of **alternative models** with varying degrees of spatial curvature and dynamic dark energy components. By studying **lower-redshift observations**, the goal is to obtain more accurate constraints on the parameters governing these models.

## Project Overview

### Objective:
To use a combination of **Hubble parameter (H(z))** and **Baryon Acoustic Oscillations (BAO)** data to constrain the parameters of **four distinct cosmological models**. Each model is characterized by different assumptions regarding:
- The flatness or curvature of the universe
- The behavior and dynamics of dark energy over cosmic time

### Approach:
We employ **Markov Chain Monte Carlo (MCMC)** methods using the `emcee` library to derive **optimal parameter constraints** for these cosmological models based on observational data.

### Cosmological Models:
1. **Flat ΛCDM Model**
2. **Non-flat ΛCDM Model**
3. **Flat XCDM Model**
4. **Non-flat XCDM Model**

Each model allows for varying degrees of spatial curvature and dark energy dynamics to better fit the observational data.

## Methodology:
- **Data Sources**: The analysis uses a combination of H(z) and BAO data, which are crucial for probing the expansion history of the universe.
- **MCMC**: We implement the **Markov Chain Monte Carlo** method via the `emcee` library to explore the parameter space and determine the most probable values of the cosmological parameters.
- **Parameter Estimation**: The project focuses on finding the **optimal constraints** for parameters such as the Hubble constant, matter density, curvature, and dark energy parameters.

## Tools & Libraries:
- **Python**
- **emcee**: For MCMC parameter estimation
- **NumPy, SciPy**: For numerical calculations and data analysis
- **Matplotlib**: For visualization of results

## Report:
The accompanying report provides:
- **Theoretical Background**: A detailed explanation of the dark energy models and cosmological framework.
- **Results**: Parameter constraints derived from the MCMC analysis and their implications for understanding the universe’s expansion.

## Conclusion:
This project sheds light on the critical parameters governing the evolution of the universe. By refining our models of dark energy and incorporating new observational data, we aim to advance our understanding of the **accelerated expansion** and the **fate of the cosmos**.
