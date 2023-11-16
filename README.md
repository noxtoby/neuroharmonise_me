# NeuroHarmonise Me

Neil Oxtoby, UCL, November 2023

The code in [`predict_harmonized_values.ipynb`](./predict_harmonized_values.ipynb) includes guidelines for getting this to work.

## 1. First step is to setup your conda environment using `environment_neil.yml`

```
conda env create -f environment_neil.yml
``` 

Activate the environment: 

```
conda activate harmonization_v2_neil_livedemo
```

## 2. Check if jupyter is installed and is in the conda env

```
which jupyter
```

## 3. Add environment to jupyter kernel

```
python -m ipykernel install --user --name=harmonization_v2_neil_livedemo
```

## 4. Run Jupyter

```
jupyter-notebook
```

## 5. Profit