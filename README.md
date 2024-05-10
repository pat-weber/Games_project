<h2 align="center">
  Análise das plataformas de Games
</h2>

---

<p align="center">
  Este projeto foi desenvolvido com o objetivo de analisar vendas das plataformas de videogames nos principais mercados do mundo e treinar habilidades relacionadas às ferramentas de software utilizadas por profissionais de dados. É um projeto realizado dentro do bootcamp de ciência de dados da <a href="https://tripleten.com">TripleTen Brasil</a> </a>
</p>

###  Confira aqui a análise

- [Notebook do projeto](https://github.com/pat-weber/games_project/blob/main/eda.ipynb).
- [Notebook de funções utilizadas](https://github.com/pat-weber/games_project/blob/main/lib.ipynb)


### Confira aqui a base de dados:

- [Games](https://practicum-content.s3.us-west-1.amazonaws.com/datasets/games.csv)


###  Tecnologias 

-  Bibliotecas: Pandas, Matplotlib, numpy, seaborn, scipy, cookiecutter;
-  VS Code.



Organização do projeto
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

Made by Patricia Weber

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
