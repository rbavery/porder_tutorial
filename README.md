# Tutorial Setup
1. Install git following instructions for your operating system: https://carpentries.github.io/workshop-template/#git
2. If you have python installed, follow these instructions to install `porder`: https://github.com/samapriya/porder#prerequisites
    - If you don't have python installed, follow the instructions for your operating system to install the anaconda distribution of python: https://carpentries.github.io/workshop-template/#python
    - most OS's come with python nowadays and you can use python 2 for this tutorial. If you don't have a package you can install it with `pip install package-name`. You can check if you have python by opening a terminal and running `python`
3. Download this repository and notebook with the terminal command: `git clone https://github.com/rbavery/porder_tutorial.git`
4. `cd porder_tutorial`
5. `jupyter lab` or `jupyter notebook`. If you don't have jupyter lab or jupyter notebook installed, install with `pip install jupyterlab`


Note: this tutorial was tested succesfully with python 2.7.15 and python 3. If you have installed python 3 via Anaconda already and would like a self contained environment to test porder, you can follow these instructions after following the anaconda python instructions linked above:

1. `conda create -n porder-env python=3.6` 
2. `conda activate porder-env`
3. `pip install porder datetimerange ipykernel pandas`

This will set you up with a separate installation/environment of python and porder. You can activate the python environment in the shell with `conda activate` and by installing `ipykernel`, you can select to use this python environment from jupyter notebook/lab.

