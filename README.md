# Anaconda Cheatsheet
This repo contains useful Anaconda resources and commands that I frequently use for data science.

## Environment Template
Included is a `template_env.txt` file that contains all the basic data science packages that are normally required. To used it run
```
conda env create --file template_env.txt
```
The template enviroment contain the following packages and their prerequisites packages:
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
Create a new environment - `conda create --name env-name (python=3.8)`

Get a list of all my environments - `conda env list`

Make exact copy of an environment - `conda create --clone original --name copy`

List all packages and versions installed in active environment - `conda list`

Export environment to a text file - `conda list --explicit > env.txt`

Create environment from a text file - `conda env create --file env.txt`

Delete an environment and everything in it - `conda env remove --name name`

<hr>

Update conda to the current version - `conda update conda`

Update any installed program - `conda update PACKAGENAME`

Update all installed packages - `conda update --all`

Open Jupyter-lab - `jupyter-lab`
