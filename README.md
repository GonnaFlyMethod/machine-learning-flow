# machine-learning-flow
A simple machine learning flow

This repository was inspired by [Programming with Mosh](https://www.youtube.com/channel/UCWv7vMbMWH4-V0ZXdmDpPBA) and his [wonderful video](https://www.youtube.com/watch?v=7eh4d6sabA0)

# Installation

### Clone the repository
using https
```
$ git clone https://github.com/GonnaFlyMethod/machine-learning-flow.git
```
or SSH
```
$ git clone git@github.com:GonnaFlyMethod/machine-learning-flow.git
```

### Install poetry  
Poetry is a new dependencies manager for python. It's simple and clever. To install poetry run:

```
$ curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python3 -
```

### Activate poetry env

```
$ source $HOME/.poetry/env
```
then go to the main directory of the project (contains file pyproject.toml) and execute the following command:
```
$ poetry shell
```

### Install dependencies

```
$ poetry install
```

# Running the project
Type
```
$ jupyter-notebook
```

# Explore the ML workflow
Go to example_ml_flow.ipynb and run the sections one by one or run all sections at once

# Visualize
With the help of VS code and Graphviz (dot) language support for Visual Studio Code you can easily visualize the working process of our model.
Just drag and drop music-recommender.dot into VS code. Then click on 3 dots in the upper right corner of VS code and select Open preview to the Side.

![instructions](https://user-images.githubusercontent.com/60840539/135579211-3a4c8df0-020a-4e1f-8d0a-8368ee68eab8.png)

And here the result![tree_vis_exampls](https://user-images.githubusercontent.com/60840539/135579296-0100ad5a-4a51-4f07-9df5-ebb90e91fa61.png)
