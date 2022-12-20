 NBA Clustering
==============================

Using the 2021-2022 NBA regular season data, I utilize unsupervised machine learning models to define new clusters to classify NBA players into.

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── interim        <- Intermediate data that has been transformed.
    │   │    └── nba_stats_cleaned.csv
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   │    ├── nba_stats_scaled.csv
    │   │    ├── nba_train_scaled.csv
    │   │    └── nba_test_scaled.csv
    │   └── raw            <- The original, immutable data dump.
    │        └── NBAStats.csv
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Model metrics
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering)
    │    ├── 1.0-cml-nba-data_wrangling.ipynb
    │    ├── 2.0-cml-nba-eda.ipynb
    │    ├── 3.0-cml-nba-preprocessing_and_training.ipynb
    │    └── 4.0-cml-nba-modeling.ipynb
    │    
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │    ├── NBA_Clustering_Report
    │    └── NBA_Clustering_Presentation
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
