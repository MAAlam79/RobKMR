RobKMR: A robust kernel machine regression towards biomarker selection in multi-omics
datasets of osteoporosis for drug discovery
=====================================

Code for reproducing experiments in ["RobKMR: A robust kernel machine regression towards biomarker selection in multi-omics
datasets of osteoporosis for drug discovery"](https://arxiv.org/abs/2201.05060).


## Prerequisites

- R, kernlab,  SKAT, base, rsvd
- A recent NVIDIA GPU

## Models

Configuration for all models is specified in a list of constants at the top of
the file. 

- `Help_1st.R`: Helper functions for conjugate transpose of RobKMR 
- `Robust_Kernel_2nd.R`: Helper function for robsut certer kernel matrix of RobKMR
- `RobKMR_simulation_withour_outliers.R`: RobKMR function  for Sinulated data without ourliers 
- `RobKMR_simulation_with_5p_outliers.R`: RobKMR function  for simulated data with 5% outliers
- 'RobKMR_real_data.R: Main RobKMR function for real data analysis

 
