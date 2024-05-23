# My notebooks repository

**I will push here sometimes when I find something interresting that I discovered** 

The used dataset are mentionned on the top cell of each notebooks

## Create an env file

https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#create-env-file-manually

## Conda command for managing environments

```
conda env create -f environment.yml #create an env from a file

conda env remove --name env_name #delete an
env
```

## Add env on jupyter notebook

```
conda activate env_name

python -m ipykernel install --user --name env_name --display-name "Python (env_name)"
```
