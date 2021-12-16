# Introduction to Machine Learning

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/WardLT/machine-learning-intro/HEAD)

The corresponding notebooks to the lecture focus on first learning how to use Scikit-Learn, a widely-used machine learning package in Python, 
and then illustrate how to use it with scientific data that requires pre-processing, using molecular property prediction as an example.

This is a standalone version of the machine learning tutorial from the [ALCF AI Training Series](https://github.com/argonne-lcf/ai-science-training-series/tree/main/01_machineLearning).

## Environment Setup

There are two ways to run the notebooks.

### Binder

Binder will build the enviornment for you and host it on a cloud-hosted instance. Just click: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/WardLT/machine-learning-intro/HEAD)

### Local Installation

The `environment.yml` file provided with this README describes how to build the environment with anaconda.

Once you have anaconda installed, build the environment by calling:

```bash
conda env create --file environment.yml
```

from the command line. Once installed, follow the instructions Anaconda generates to activate the environment and then launch Jupyter:

```bash
jupyter lab
```
