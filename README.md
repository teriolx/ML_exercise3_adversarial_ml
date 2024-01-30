# Exercise3: Adversarial ML

This project contains experiments in Adversarial ML, particularly Attribute Inference (disclosure) from ML Models as part of Exercise 3 in the ML course.

## Requirements

* python 3.10
* poetry 

## Structure

* `data/` contains the dataset used in the experiments
* `results/` contains the measured experiment results per model in `.csv` format
* `attribute_inference.ipynb` jupyter notebooks with the experiments and functions to perform attribute inference

## Usage

The project can be run by creating a venv using poetry

```
poetry install
```

and then running

```
poetry run jupyter notebook 
```

withing the venv. The notebook can be run for example in VS code by selecting the venv as the kernel or by opening the notebook in the browser once the jupyter kernel is running.