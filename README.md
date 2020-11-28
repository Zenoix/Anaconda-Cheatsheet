# Anaconda Cheatsheet
This repo contains useful Anaconda resources and commands that I frequently use for data science.

## Useful Commands

### Environment
Create a new environment - `conda create --name env-name (python=3.8)`
Get a list of all my environments - `conda env list`
Make exact copy of an environment - `conda create --clone original --name copy`
List all packages and versions installed in active environment - `conda list`
Export environment to a text file - `conda list --explicit > env.txt`
Create environment from a text file - `conda env create --file env.txt`
Delete an environment and everything in it - `conda env remove --name name`


Update conda to the current version - `conda update conda`
Update any installed program - `conda update PACKAGENAME`

Open Jupyter-lab - `jupyter-lab`
