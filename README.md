# Interactive Football Pitch Using Jupyter Voila

[Jupyter voila](https://blog.jupyter.org/and-voil%C3%A0-f6a2c08a4a93) allows to serve Jupyter notebooks, and especially ipywidgets, as standalone applications.
This repository contains an example notebook which uses `panel`'s `tabulator` and `sparklines` to create an interactive table widgets with sparkline support.
You can test it live in Binder or run it locally.

## Voila in Binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/seidlr/voila-panel-tabulator-sparklines/master?urlpath=voila%2Frender%2FTabulator-Sparklines.ipynb)

## Notebook in Binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/seidlr/voila-panel-tabulator-sparklines/master?urlpath=lab/tree/Tabulator-Sparklines.ipynb)

## Local installation

To run the example notebook, first create a `conda` environment.

```bash
conda env update
```

This creates an environment `voila-panel-tabulator-sparklines` which can be used in a jupyter notebook.
Next, activate the environment and start the voila server.

```bash
conda activate voila-panel-tabulator-sparklines
```

```bash
voila
```

or run the notebook by

```
voila Tabulator-Sparklines.ipynb
```

## Deployment on Heroku

You can easily deploy the notebook to Heroku following these steps:
First, follow the setup steps on Heroku: [here](https://devcenter.heroku.com/articles/getting-started-with-python)
Then run

```bash
heroku create
git push heroku master
```
