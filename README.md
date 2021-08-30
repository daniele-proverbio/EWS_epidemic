# EWS_epidemic
Code and data for the analysis of "Performance of early warning signals for disease emergence", Proverbio et al. (2021)

## Navigate files
In EWS_epidemic:
* /src: code files (Jupyter noteboook and Matlab scripts)
  - R_t_EWS: estimates R(t) for all countries
  - Analysis_Reff: analyses the rate of approach to the transition
  - EWS_disease_emergence_figures: includes prevalence data and their analysis. Generates figures for Main Text
  - EWS_disease_emergence_figures_SupMat: completes analysis and generates figures for Supplementary Material
* /data: data for the evaluation of R(t), plus output of ARIMA detrending (files output*.csv)
* /csv: output of R_t_EWS, input for Analysis_Reff
* /R_T_plots: plots produced by R_t_EWS
* /Analysis_Reff_plots: plots produced by Analysis_Reff
* /plots_Main: figures for Main Text, produced by EWS_disease_emergence_figures
* /plots_SupMat: figures for Main Text, produced by EWS_disease_emergence_figures_SupMat
