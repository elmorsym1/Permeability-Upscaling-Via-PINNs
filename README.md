# Rapid Permeability Upscaling of Digital Porous Media via Physics-informed Neural Networks

This data repository contains the simulation results and data presented in the paper "Elmorsy et al. Rapid Permeability Upscaling of Digital Porous Media via Physics-informed Neural Networks".

**Data and Scripts:**

- In general, the data included in this repository are,
	- Numerical simulation results for rock samples located at folder: "sim_results"
 	- Digital rock samples include:
		- Benthimer Sandstone
		- Ketton Limestone
		- Berea Sandstone 
 	- Predicted permeability results using the approximate analytical solution, pinn-1 and pinn-2 located at folder: "sim_results_predicted"
  	- Compiled data results for multiple levels (i.e., 0,1 and 2) are generated and stoed at folder: "data"
  	- Compiling scripts for levels 0 & 1: "compile_data_L01.ipynb"
  	- Compiling scripts for levels 1 & 2: "compile_predicted_data_L12.ipynb"
  	- PINN-1 training script: "pinn1_train.ipynb"
  	- PINN-2 training script: "pinn2_train.ipynb"
  	- PINNs inference script for 1st level of permeability upscaling: "pinn_predict_L01.ipynb"
  	- PINNs inference script for 2nd level of permeability upscaling: "pinn_predict_L12.ipynb"
    
- The raw CT rock cores are obtained from the [Imperial Colloge London portal](https://www.imperial.ac.uk/earth-science/research/research-groups/pore-scale-modelling/micro-ct-images-and-networks/).

**Software and Libraries:**

Numerical simulations of the 3D porous media samples were conducted using OpenFOAM®, which is an open-source set of solvers for CFD simulations (Horgue et al., 2015). The analytical solutions are developed using the symbolic computation solver SymPy 1.10.1 in Python 3.9.12. We train the machine learning model using the open-source software interface Keras 2.4.0 and TensorFlow 2.3.1 on NVIDIA GeForce RTX 2080 Ti GPUs. Figures were made with Matplotlib 3.5.1, available under the Matplotlib license at https://matplotlib.org/. 

A patent has been filed to protect the developed algorithm.

This work has been accepted for publishing by the American Geophysical Union flagship journal: Water Rseourses Research.

Paper link: Tobe provided post official publication.

For more information, please contact the repository owner at: elmorsym777@gmail.com
