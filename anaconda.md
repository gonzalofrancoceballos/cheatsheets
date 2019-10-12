### Create conda environment

- Create new environment
```bash
conda create -n my_env_name python=X.X
```

- Install requirements in new environment
```bash
conda activate my_env_name
pip install -r /path/to/project/requirements.txt
```

- Make new environment available to Jupyter
```bash
pip install ipykernel
python -m ipykernel install --user --name=my_env_name --display-name "Python (my_env_name)"
```
