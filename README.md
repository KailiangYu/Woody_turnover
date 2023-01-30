# Woody_turnover

This repository is generated for the projected ‘Biogeographic pattern of living vegetation carbon turnover time across continents'.

The files include: 1) Data of woody_carbon_turnover_time aggregated at 0.25 degree ('Woody_turnover_time.csv') used to spatially estimate woody carbon turnover time at continent scales by a machine learning approach. The raw inventory data are available upon reasonable request from the corresponding author.

The codes of machine learning used to generate woody carbon turnover time maps were adapted from https://github.com/KailiangYu/Mortality-constraint.

2) The final observational woody carbon turnover time maps (mean and standard deviation, ‘ML_turnover_mean.tif’ and ‘ML_turnover_CV.tif’. The maps were ensemble mean and its uncertainty (coefficient of variation) across continents at 0.25 degree derived from forest plot data using the bootstrapped (100 iterations) approach by randomly sampling 90% plots with replacement. 

For more questions and comments, please contact Kailiang Yu kai86liang@gmail.com
