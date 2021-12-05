# Python Project Template

## Standard Python Dev Tools
* git
* Pipenv
* Pytest

## Initial Setup using pipenv and (optionally) Jupyter
```shell
git clone ...
pip install pipenv
pipenv install pytest
pipenv install...
```

# if using jupyter
```shell
pipenv install ipykernel 
pipenv install ipywidgets 
pipenv shell
python -m ipykernel install --user --name={environment name}
jupyter notebook

# after initial setup
git pull
pipenv run jupyter lab
```

In the notebook, Kernel -> Change Kernel -> {environment name}

#### Some inspriration from here: https://medium.com/red-buffer/python-production-level-coding-practices-4c39246e0233