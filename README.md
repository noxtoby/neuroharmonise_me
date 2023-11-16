# NeuroHarmonise Me

Neil Oxtoby, UCL, November 2023

The code in [`predict_harmonized_values.ipynb`](./predict_harmonized_values.ipynb) includes guidelines for getting this to work.

## 1. Setup the (mini)conda environment

```
conda env create -f environment_neil.yml
``` 

Activate it: (change the name accordingly if you change the environment name in `environment_neil.yml`)

```
env_name=harmonization_v2_neil_livedemo
conda activate $env_name
```

## 2. Check if jupyter is installed and is in the conda env

```
which jupyter
```

Should output:

```
<path/to>/miniconda/base/envs/harmonization_v2_neil_livedemo/bin/jupyter
```

## 3. Add environment to jupyter kernel

```
python -m ipykernel install --user --name=$env_name
```

## 4. Run Jupyter

```
jupyter notebook
```

## 5. Profit