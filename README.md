# Exercise3: Adversarial ML

This project contains experiments in Adversarial ML, particularly Attribute Inference (disclosure) from ML Models as part of the exercise in the Machine Learning course.

## Requirements

* python 3.10
* poetry 

## Structure

* `data/` contains the datasets used in the experiments
* `infer_attribute.ipynb` contains the functions to perform attribute inference from ML models
* `*.ipynb` jupyter notebooks with the experiments  


## Usage

The project can be run by creating a venv using poetry: 

```
poetry run jupyter notebook 
```

Once the venv is created, the notebooks can be run for example in VS code by selecting the venv as the kernel or by opening the notebook in the browser once the kernel is running.