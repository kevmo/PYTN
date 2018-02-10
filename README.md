# Identifying Confusion Amongst Python Programmers.

This repository is for a talk at PyTennessee 2018.

## Dependencies

These instructions require the Anaconda distribution of Python.  [Go download the
Anaconda installer you haven't already](https://www.anaconda.com/download/#macos). Anaconda
comes bundled with [Jupyter Notebook](https://jupyter.readthedocs.io). 




## QuickStart

The primary point of this codebase is supporting a Jupyter notebook
that uses an iPython kernel.  To use the Jupyter notebook, do the 
following:

**1. Clone this repository.**

`git clone https://github.com/kevmo/pytn`

(and then `cd pytn`)


**2. Create a virtual environment using `conda`.**

The following command creates a virtual environment named
PYTN.  It makes available the Python v3.6.4 interpreter.
It also installs this repo's dependencies.  From the root directory, run:

`conda create --name PYTN python=3.6.4 --file spec-list.txt`

**3. Activate the environment.**

`source activate PYTN`

**4. Activate Jupyter notebook in the `nbs` directory.**

`cd nbs`

`jupyter notebook`

**5. Go work through the PYTN Jupyter notebook.**

Go to [localhost:8888](http://localhost:8888).  

Cell menu > "Run All"



## Want more?

[Go check out the Resources section](RESOURCES.md).


## Gotcha

If you're having a package import error, try running the following
from within your conda environment: 

```
conda install notebook ipykernel
ipython kernel install --user
```

If you're not on a Mac, you will need to manually install the packages
contained in the notebook.

## Errata

Errata will go here.