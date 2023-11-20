# Permeability Upscaling Via PINNs

This data repository contains the simulation results and data presented in the paper "Elmorsy et al. Rapid Permeability Upscaling of Digital Porous Media via Physics-informed Neural Networks".

In general, the data included in this repository are:
	- Numerical simulation results for Benthimer Sandstone, Ketton Limestone and Berea Sandstone samples located at folder: "sim_results".
 	- Predicted permeability results using the approximate analytical solution, pinn-1 and pinn-2 located at folder: "sim_results_predicted".
    	- Compiled data results for multiple levels (i.e., 0,1 and 2) are generated and stoed at folder: "data".
    	- Compiling scripts for levels 0 & 1: "compile_data_L01.ipynb".
    	- Compiling scripts for levels 1 & 2: "compile_predicted_data_L12.ipynb".
    	- PINN-1 training script: "pinn1_train.ipynb".
    	- PINN-2 training script: "pinn2_train.ipynb".
    	- PINNs inference script for 1st level of permeability upscaling: "pinn_predict_L01.ipynb".
    	- PINNs inference script for 2nd level of permeability upscaling: "pinn_predict_L12.ipynb".
    
The raw CT rock cores are obtained from the [Imperial Colloge London portal](https://www.imperial.ac.uk/earth-science/research/research-groups/pore-scale-modelling/micro-ct-images-and-networks/).

Paper link: [Rapid Permeability Upscaling of Digital Porous Media via Physics-informed Neural Networks](To be provided after publication).

For more information, please contact the repository owner at: elmorsym777@gmail.com
