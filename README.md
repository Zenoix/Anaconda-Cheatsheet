# Anaconda Cheatsheet
This repo contains useful Anaconda resources and commands that I frequently use for data science. This is not an exhaustive list of everything Anaconda contains. 

## How to Use Commands
**<< ... >> indicate text to replace**

**( ... ) indicate optional but potentially useful parameters**

## Environment Template
Included is a `template_env.yml` file that contains all the basic data science packages that are normally required. To used it run:
```
conda env create --name <<env name>> --file template_env.yml

conda update --all
```
The template enviroment contains the following packages and their prerequisites packages:
- Jupyter notebook
- Jupyter lab
- Pandas
- Numpy
- Scipy
- Matplotlib
- Seaborn
- Scikit learn


## Useful Commands

### Environment

Create a new environment - `conda create --name <<env name>> (python=3.8)`

Get a list of all my environments - `conda env list`

Make an exact copy of an environment - `conda create --clone original --name copy`

List all packages and versions installed in active environment - `conda list`

Export environment to a text file - `conda list --explicit > <<file name>>.yml`

Create environment from a file - `conda env create --name <<env name>> --file <<text file path>>`

Delete an environment and everything in it - `conda env remove --name <<env name>>`

<hr>

Update conda to the current version - `conda update conda`

Update any installed program - `conda update <<package name>>`

Update all installed packages - `conda update --all`

Open Jupyter-lab - `jupyter-lab`
