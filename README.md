# Tutorial Setup
1. Install git following instructions for your operating system: https://carpentries.github.io/workshop-template/#git
2. If you have python installed, follow these instructions to install `porder`: https://github.com/samapriya/porder#prerequisites
    - If you don't have python installed, follow the instructions for your operating system to install the anaconda distribution of python: https://carpentries.github.io/workshop-template/#python
    - most OS's come with python nowadays and you can use python 2 for this tutorial. If you don't have a package you can install it with `pip install package-name`. You can check if you have python by opening a terminal and running `python`
3. Download this repository and notebook with the terminal command: `git clone https://github.com/rbavery/porder_tutorial.git`
4. `cd porder_tutorial`
5. `conda create -f environment.yml`
6. `conda activate porder_tutorial`
7. `jupyter lab`


The `conda create` step will set you up with a separate installation/environment of python, porder, and other useful packages for this tutorial. We activate the python environment in the shell with `conda activate`. The environment also contains a speparate installation of jupyter lab, the code editor we will use to go through the tutorial. We start this from the terminal with `jupyter lab`

