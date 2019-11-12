## Model Evaluation and Validation Project: Predicting Taipei Housing Prices

### Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](https://www.numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)
- [scikit-learn](https://scikit-learn.org/stable/)
- [Jupyter Notebook](https://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](https://www.anaconda.com/download/) distribution of Python, which already has most of the above packages and more included or if you don't want to install a huge number of packages then you can try [Miniconda](https://conda.io/miniconda.html) and then install the above packages.

### Code

Code is in the [Taipei_Housing.ipynb] notebook file. Also required is the included [visuals.py](visuals_md.py) python file which contains some modified code for model visualizations and the [Real estate valuation data set - Taipei.csv] dataset file.

### Run

In a terminal or command window, navigate to the top-level project directory `Taipei-Housing-ML-Project/` (that contains this README) and run one of the following commands:

```bash
jupyter notebook Taipei_Housing.ipynb
```

or

```bash
ipython notebook Taipei_Housing.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Project Report

Report can be viewed at [**https://jsyshin.github.io/Taipei-Housing/**].

### Data

The modified Boston housing dataset consists of 414 data points, with each datapoint having 3 features. This dataset is a modified version of the Taipei Housing dataset found on the [UCI Machine Learning Repository] https://archive.ics.uci.edu/ml/datasets/Real+estate+valuation+data+set

**Features**
X2=the house age (unit: year)
X3=the distance to the nearest MRT station (unit: meter)
X4=the number of convenience stores in the living circle on foot (integer)

**Target Variable**
Y= house price of unit area (10000 New Taiwan Dollar/Ping, where Ping is a local unit, 1 Ping = 3.3 meter squared)

