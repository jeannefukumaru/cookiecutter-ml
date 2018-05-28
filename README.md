Reproducible ML for Minimalists
====================

Pared-down project template for reproducible Machine Learning. Adopted from [Cookiecutter Data Science](https://cookiecutter.readthedocs.io/en/latest/readme.html) and [Mario Krapp](https://blog.mariokrapp.com/Cookiecutter_for_a_more_transparent_and_reproducible_science.html)   

How to Use
-----
First install cookiecutter:
`pip install cookiecutter`

Then initialise a template:

`cookiecutter gh:jeannefukumaru/cookiecutter-ml`

More information on the cookiecutter project can be found [here](https://cookiecutter.readthedocs.io/en/latest/readme.html)

Template Structure 
-----------------

```
.
    ├── AUTHORS.md
    ├── LICENSE
    ├── README.md
    ├── models  <- compiled model .pkl or HDFS or .pb format
    ├── config  <- any configuration files
    ├── data
    │   ├── interim <- data in intermediate processing stage
    │   ├── processed <- data after all preprocessing has been done
    │   └── raw <- original unmodified data acting as source of truth and provenance
    ├── docs  <- usage documentation or reference papers
    ├── notebooks <- jupyter notebooks for exploratory analysis and explanation 
    ├── reports <- generated project artefacts eg. visualisations or tables
    │   └── figures
    └── src
        ├── data-proc <- scripts for processing data eg. transformations, dataset merges etc. 
        ├── viz  <- scripts for visualisation during EDA, modelling, error analysis etc. 
        ├── modeling    <- scripts for generating models
```

