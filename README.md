# JASA Reproducibility Materials

This repository contains code to reproduce the results in  
**“Functional Partial Least-Squares: Adaptive Estimation and Inference”**  
by Andrii Babii, Marine Carrasco, and Idriss Tsafack.  
*Journal of the American Statistical Association, Theory and Methods* (forthcoming).

## Contents
1. **data_cleaning.ipynb** — Python notebook to prepare data.  
   - Raw data source (replication package for Schlenker & Roberts, PNAS 2009):  
     https://www.wolfram-schlenker.info/replicationFiles/SchlenkerRoberts2009.zip  
   - We also provide two cleaned CSVs (`corn.csv`, `soybeans.csv`) inside `data.zip`.
2. **empirical_application.ipynb** — Python notebook producing the empirical results using the cleaned data.
3. **simulations.ipynb** — Julia notebook for the Monte Carlo simulations.

## Quick start
1. (Optional) Download and unzip the replication data listed above.  
2. Run `data_cleaning.ipynb` to generate `corn.csv` and `soybeans.csv` (or unzip `data.zip`).  
3. Run `empirical_application.ipynb` for the paper’s empirical results.  
4. Run `simulations.ipynb` for the Monte Carlo experiments.

> Notes: See the first cells of each notebook for required package versions and environment setup.
