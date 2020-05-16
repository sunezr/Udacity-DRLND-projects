# Udacity DRLND Projects

## Introduction

This repository gather the projects in Udacity DRLND(Deep Reinforcement Learning Nanodegree).

## Getting Started

To set up your python environment to run the code in this repository, follow the instructions below.

1. Create (and activate) a new environment with Python 3.6.

	- __Linux__ or __Mac__: 
	```bash
	conda create --name drlnd python=3.6
	source activate drlnd
	```
	- __Windows__: 
	```bash
	conda create --name drlnd python=3.6 
	activate drlnd
	```
	
2. Install PyTorch 0.4

   You can use the code below to install PyTorch without CUDA or refer to [here](https://pytorch.org/get-started/previous-versions/).

   ```bash
   conda install pytorch=0.4.1 -c pytorch
   ```

3. Clone the repository (if you haven't already!), and navigate to the `python/` folder.  Then, install several dependencies. After install the dependencies,  the installation in each project can be ignored.

```bash
git clone https://github.com/sunezr/Udacity-DRLND-projects.git
cd Udacity-DRLND-projects/python
pip install .
```

4. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `drlnd` environment.  
```bash
python -m ipykernel install --user --name drlnd --display-name "drlnd"
```

5. Before running code in a notebook, change the kernel to match the `drlnd` environment by using the drop-down `Kernel` menu. 







