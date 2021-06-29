[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/vcalderon2009/2021_06_Deep_Learning_tutorial/master)



2021 Deep Learning with Images
==============================

    Tutoriales y notebooks dedicados al aprendizaje de Deep Learning e imágenes.

| | |
|---------------|---------------------------------------------------|
| __Author__    | Victor Calderon [[homepage](http://vcalderon.me)] |
| __Dates__     | June 28 - July 2, 2021                            |
| Documentation | Link |


## Description

El siguiente set de tutoriales forma parte de la 2da semana de cursos del
[Instituto Konrad Lorenz](https://la.konradlorenz.edu.co).

En estos tutoriales, se cubrirán los siguientes temas:

- Introducción a [Pytorch](https://pytorch.org/)
- Como crear un model de Deep Learning orientado a imágines
    1. La estructura de un modelo y como "entrenar" un modelo
    2. Conceptos y estructuras de Pytorch que se usan dentro de un modelo.
- Introducción a *segmentation de imágenes*.
- Introducción a *Transfer Learning*.

También se discutirán prácticas comunes de como lidiar con modelos de Deep
Learning, y sobre mejor prácticas para estructurar la data.

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
