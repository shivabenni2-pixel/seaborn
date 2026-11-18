# Seaborn Iris Visualizations

This repository contains a Jupyter notebook for practicing data visualization with Seaborn. It loads the Iris dataset and compares flower measurements across the three species.

## Notebook

`Matplotlib.ipynb` explores the data and demonstrates line, scatter, bar, count, box, violin, strip, swarm, histogram, pair, and correlation heatmap plots.

## Run the notebook

Install Jupyter and the notebook dependencies:

```bash
python -m pip install jupyter "seaborn<0.14"
```

Start Jupyter from the repository folder and open `Matplotlib.ipynb`:

```bash
jupyter notebook
```

Run the cells in order. The notebook downloads the Iris dataset with `sns.load_dataset("iris")`, so an internet connection is needed to fetch the data.

## Seaborn version

The notebook uses `sns.distplot`, which was removed in Seaborn 0.14. The version constraint above keeps that example available. To use a newer Seaborn version, replace those `distplot` examples with `histplot` and/or `kdeplot`.
