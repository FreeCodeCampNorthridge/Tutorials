# Python
Python is one of the easier languages to learn since the syntax is basically pseudocode.

You can basically do anything since there are so many libraries to choose from.

## Installation
* All platforms: https://realpython.com/installing-python/
* or for Ubuntu: https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-programming-environment-on-an-ubuntu-18-04-server

To check if you have python installed, type `python` or `python3.6` or whatever you installed into the command line
This should bring up the python shell where you can try out python code. For example, try: print('Hello World!') and you should see an output.

## Virtual environments
virtual environments are a standard way of having many python environments that don't conflict with one another. This is important since one of the strengths of python is the fact that there are so many python libraries to choose from.
However, some libraries don't work well with others, so it's best to have virtualenvironments.

```
pip install virtualenv
virtualenv -p python my_env
```

## Quick Tutorials:
* https://developers.google.com/edu/python/

## Jupyter notebooks
Jupyter notebooks are a way to code python in your browser. There are many good features for learning: running specific blocks of code, nice markdown options, autocompletion with Shift + Tab, notebook sharing, etc.
Sharing notebooks on github automatically render nicely.

https://jupyter.org/install.html

## Popular libraries:
Here are some popular libraries for python.

* Webframeworks: Flask (microframework), Django (MVT framework)
* Web Scraping: requests, Selenium (General Browser automation), pyppeteer (python's puppeteer)
* Data Analysis: Numpy (if you need math/arrays), Pandas (for tables), Statsmodels (for stats)
* Data Visualization: Matplotlib (non-interactive plots), Plotly (interactive plots, d3 wrapper)
* Machine Learning:
 * General: Scikitlearn, PySpark (Advanced)
 * Deep Learning (Advanced): Keras, Tensorflow
 * Natural Language Processing (if you data is text based): NLTK, Spacy, Gensim
 * Computer Vision: OpenCV or Tensorflow
 * Boosting Algorithms (Advanced): XGBoost, LightGBM, CatBoost
* Task Scheduling: Airflow
