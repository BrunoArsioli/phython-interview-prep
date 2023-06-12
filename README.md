# A Journey to Mastering Python Job Interviews: 

**Bridging Academic to Industry Roles in Data Analysis and Machine Learning**

## Introduction

As an astrophysics researcher, I've found Python to be an indispensable tool for modeling and data visualization, seamlessly integrating into my daily workflow.

Despite my familiarity with crafting Python scripts for a range of tasks, a Python Dev job interview feels like uncharted territory. It's a challenge that requires preparation, a process I intend to document and share. This record of my journey could serve as a foundation for others embarking on a similar path. 

## Ongoing Journey: Tune for Updates

Embarking on this journey from academia to industry I will share my insights along the way. As I continue to explore new tools, languages, and methodologies, I plan to regularly come up with updates of my preparation for Python / Code interviews. 

I will also comment on work-flow improvements, that might be interesting for those migrating from the exploratory phase with Google Colaboratory Notebooks, to a more robust organization involving the use of VS Code and Github, with reliable Project Structures, and with a version control approach.  

Whether it's gaining a deeper understanding of Python libraries, diving into the potential of Mojo, or uncovering the nuances of machine learning, I want to chronic my steps. 

It is always an Ongoing Journey for us all,

and I hope to provide valuable perspectives for others navigating similar paths. Please feel free to reach out if you have questions, suggestions, or topics you think would be interesting to consider and to dive into. 

Thank you for joining me in this road!


# Project Organization

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




Project Structure based on the cokiecutter data science project template. 
#cookiecutterdatascience
