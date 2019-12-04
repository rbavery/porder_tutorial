# Tutorial Setup
1. Install git following instructions for your operating system: https://carpentries.github.io/workshop-template/#git
2. Install the Anaconda distribution of python 3.7, following the instructions for your operating system (make sure to check the box that says add Anaconda to system path): https://carpentries.github.io/workshop-template/#python
3. Download this repository and notebook with the terminal command: `git clone https://github.com/rbavery/porder_tutorial.git`
4. `cd porder_tutorial`
5. `conda env create -f environment.yml -n porder_tutorial`
6. `conda activate porder_tutorial`
7. `jupyter lab`


The `conda create` step will set you up with a separate installation/environment of python, porder, and other useful packages for this tutorial. We activate the python environment in the shell with `conda activate`. The environment also contains a speparate installation of jupyter lab, the code editor we will use to go through the tutorial. We start this from the terminal with `jupyter lab`

### Notes on installing Anaconda python and the `conda` environment manager:
Most operating systems come with python nowadays, but this is a bare bones installation that doesn't have much power on it's own. Even if your system has python 2 or 3 installed or if you have another program (like ArcGIS) that comes with python, I recommend installing the Anaconda python distribution. It's the most fully featured python distribution for research computing and besides python, comes with many libraries like `pandas` and `matplotlib` that your system python won't have. 

It also comes with a tool called `conda`, which allows you to mange library dependencies in separate python environments. In fact, this repo includes an `environment.yml`, which lists the python packages necessary to run this tutorial and the `conda` tool you'll install allows you to set up this environment in a single line (step 5 above). You can read more about python environments and `conda` here: [Why you need Python environments and how to manage them with Conda](https://protostar.space/why-you-need-python-environments-and-how-to-manage-them-with-conda)

You can check if you have Anaconda python installed by opening a terminal and running `python`:

```bash
$ python            
Python 3.7.3 | packaged by conda-forge | (default, Jul  1 2019, 21:52:21) 
[GCC 7.3.0] :: Anaconda, Inc. on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 
```

If you don't see something like the above (Anaconda, Inc should be there) then you probably need to install the Anaconda distribution, see above.
