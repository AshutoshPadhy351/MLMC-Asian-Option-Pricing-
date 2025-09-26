# Multi-Level Monte Carlo for Asian Option Pricing

This project implements and analyzes the Multi-Level Monte Carlo (MLMC) method for pricing arithmetic Asian options. The main notebook (`MLMC_Main_Analysis.ipynb`) demonstrates the superior computational efficiency of MLMC compared to other methods like Standard Monte Carlo, Antithetic Variates, and Quasi-Monte Carlo.

## Project Structure

This repository contains mainly three key notebooks:

1.  **`01_Geometric_Brownian_Motion.ipynb`**: A preliminary notebook exploring the simulation of Geometric Brownian Motion (GBM), the underlying process for the asset price.
2.  **`02_Simple_Asian_MC.ipynb`**: A straightforward implementation of a standard Monte Carlo pricer for the Asian option. This serves as the baseline for performance comparison.
3.  **`MLMC_Main_Analysis.ipynb`**: The core of the project. This notebook contains:
    * A full, memory-efficient implementation of the MLMC algorithm.
    * Rigorous benchmarking against other standard and advanced techniques.
    * Analysis and visualization of the results, proving the efficiency gains of MLMC.

## Key Takeaway

The final analysis shows that MLMC provides a **~5x to 13x speedup** over standard methods for a given level of accuracy, making it a powerful technique for computational finance.

<img width="857" height="552" alt="image" src="https://github.com/user-attachments/assets/44c19c9c-0b27-45fb-8b07-d57c4e74ed59" />

