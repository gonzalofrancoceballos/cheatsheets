### Python environment

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

- To remove environment from Jypyter
```bash
jupyter kernelspec uninstall my_env_name
```

### R environment

- Create new environment
```bash
conda create -n my_env_name
```

- Install R essentials. They include all necessary dependencies to launch a jupyter notebook:
```bash
conda install -c r r-essentials 
```

- Install main libraries using `conda install`:
```bash
conda install -c conda-forge r-lightgbm 
conda install -c conda-forge r-catboost 
```
- Some packajes need to be installed from directly inside of `R`
```R
install.packages('prophet', type="source")
```

