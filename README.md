# Causai
Causai is a Python library for doing Causality in Machine Learning. We provide state-of-the-art causal & ML/DL algorithms into decision-making systems.

## Why Causai?
...

## Main Features
*
* 
*  



# Get Started
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/DanielhCarranza/causai/master)

## Installation 
```sh
    pip install causai
```

or 

```sh
git clone https://github.com/DanielhCarranza/causai.git
cd causai
```

## Example
```python
    import causai
    from causai.datasets import load_datasets
    from causai.inference import CausalInference
    from causai.discovery import AutoDiscovery

```





## Codebase

- **`causai`**
    - **`datasets`**: **Logic for downloading, preprocessing, augmenting, and loading data**
    - **`models`: Models wrap networks and add functionality like loss functions. saving, loading, and training**
    - **`networks` : Code for constructing ML model, neural net or bayesian net (dumb input | output mappings)**
    - **`tests`: Regression tests for the models code. Make sure a trained model performs well on important examples.**
    - **`metrics`**
    - **`estimator`**
    - `predictor.py`: **wrapper for model that allows you to do inference in the api**
    - `utils.py`

**`notebooks`:** **Examples, Tutorials, Explore and visualize data** 

**`tasks`** : **Scripts for running frequent tests and training commands**
**`training`**: **Logic for the training itself**
**`api`**: **Serve predictions. (Contains DockerFiles, Unit Tests, Flask, etc.)** 

**`evaluation`**: **Run the validation tests** 

**`experiment_manager`**: **Settings of your experiment manager (**p.e. wandb, tensorboard**)**

**`data`**: **use it for data versioning, storing data examples and metadata of your datasets. During training use it to store your raw and processed data but don't push or save the datasets into the repo.** 


