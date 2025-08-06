# STAT-Bat Notebooks


This repository contains a collection of Jupyter notebooks supporting the 26S course EMS Bat at HS Kempten held by Prof. Dr. Holger Hesse at University of Applied Sciences Kempten. It is depreciated from a former version beeing set up at Technical University of Munich at the Chair for Electric Storage Technology and contains materials created by Martin Cornejo


## Setup
REMOTE Option:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GIT4Holger/26S_EMSBat/main)


### additional info --- just fro geeks: Local installation w. conda
LOCAL Option:
Install VS-code: https://code.visualstudio.com/
(OPTIONAL: Install python on VS code: https://code.visualstudio.com/docs/python/python-tutorial)
Install conda: https://docs.conda.io/en/latest/miniconda.html

Create the environment from the dependency file.
```
conda env create --file environment.yml
```

### Start Jupyter notebook
Activate the conda environment.
```
conda activate STAT_bat
```

Start the Jupyter-lab session.
```
jupyter lab
```

### Update conda environment

During the course, some new packages might be added or removed from the environment. To update to the latest environment version use the following command:
```
conda env update --name STAT_bat --file environment.yml --prune
```