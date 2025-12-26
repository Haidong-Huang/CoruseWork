# CourseWork2 (University of Nottingham Mechanical Engineering)

This is the solution for CourseWork2 of the Mechanical Engineering program at the University of Nottingham. Key information about this project is as follows:


## Topics
1. Gaussian Elimination with Partial Pivoting for solving linear systems.
2. False Position Method for finding roots of equations.


## Environment Setup
Follow these steps to configure the running environment:
1. Create a new conda environment
```bash
conda create -n cw2 python=3.11 -y
2.Activate the environment
conda activate cw2

install dependencies
# (Optional) Check ipykernel version
python -c "import ipykernel; print(ipykernel.__version__)"

# Install numpy and ipykernel
conda install numpy ipykernel -y
Notes
The Kernel environment in Jupyter Notebook may not be consistent with the Terminal environment. If there is an environment mismatch issue, first run this command in PowerShell:
conda init powershell

After execution, restart PowerShell, reactivate the environment, and launch Jupyter Notebook. The Kernel will then be linked to the cw2 environment.
