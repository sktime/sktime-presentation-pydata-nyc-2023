![](images/team.jpg)

Welcome to the sktime presentation for PyData NYC 2023
======================================================

This presentation is about forecasting with `sktime.`

It discusses different types of forecasting techniques: classical and contemporary techniques can successfully be used in practice, but it is important to understand the tradeoffs inherent to using one technique vs the other.

`sktime` provides a unified interface to use a variety of forecasting methods in composable forecasting pipelines for different types of problems: univariate, multivariate, panel and hierarchical.

`sktime` is easily extensible by anyone, and interoperable with the pydata/numfocus stack.

This presentation has the following parts:

* a general introduction to time series and forecasting
* an overview of what `sktime` is, and how it makes using different forecasting algorithms easier
* common classical forecasting techniques, and how they are commonly used
* machine learning for forecasting, and common data processing steps to make them useful (reduction, pipelines)

[sktime]: https://sktime.net

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sktime/sktime-presentation-pydata-nyc-2023/main?filepath=notebooks) [![!discord](https://img.shields.io/static/v1?logo=discord&label=discord&message=chat&color=lightgreen)](https://discord.com/invite/54ACzaFsn7) [![!slack](https://img.shields.io/static/v1?logo=linkedin&label=LinkedIn&message=news&color=lightblue)](https://www.linkedin.com/company/scikit-time/)

Also check out our notebooks from the [half-day sktime introduction workshop at pydata Prague 2023!](https://github.com/sktime/sktime-workshop-pydata-prague-2023)

## :rocket: How to get started

The slides for this presentation are made from the notebook titled `forecasting.ipynb` 

You have different options how to run the accompanying notebook:

* Run the notebooks in the cloud on [Binder] - for this you don't have to install anything!
* Run the notebooks on your machine. [Clone] this repository, get [conda], install the required packages (`sktime`, `seaborn`, `jupyter`) in an environment, and open the notebooks with that environment. For detail instructions, see below. For troubleshooting, see sktime's more detailed [installation instructions].
* or, use python venv, and/or an editable install of this repo as a package. Instructions below.

[Binder]: https://mybinder.org/v2/gh/sktime/sktime-presentation-pydata-nyc-2023/main?filepath=notebooks
[clone]: https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository
[conda]: https://docs.conda.io/en/latest/
[installation instructions]: https://www.sktime.net/en/latest/installation.html

Please let us know on the [sktime discord](https://discord.com/invite/54ACzaFsn7) if you have any issues during the conference, or join to ask for help anytime.

## :bulb: Description

This presentation is about forecasting with classical and machine learning methods, and how they can be used successfully in different settings.  It's also about how to implement different forecasting techniques with `sktime`, a unified interface for building end-to-end time series solutions.  Forecasting is a domain that's undergone rapid improvements in both technique and theory, and its challenges make it a difficult domain to master.  

What makes forecasting a unique problem for machine learning algorithms?  
Under what circumstances would you expect an ML algorithm to outperform a traditional forecasting algorithm?  
What are common challenges for successfully building forecasting pipelines with complicated datasets?

This presentation is designed to answer these questions in an engaging and informative style that will make it easy to properly implement forecasting solutions in a way that's powerful and effective.

`sktime` not just a package, but also an active community which aims to be welcoming to new joiners.
We invite anyone to get involved as a developer, user, supporter (or any combination of these).

## :movie_camera: Other Tutorials:

- [Europython 2023 - General sktime introduction, half-day workshop](https://github.com/sktime/sktime-tutorial-europython-2023)

- [PyCon Prague 2023 - Forecasting, Advanced Pipelines, Benchmarking](https://github.com/sktime/sktime-workshop-pydata-prague-2023)

- [Pydata Amsterdam 2023 - Probabilistic prediction, forecasting, evaluation](https://github.com/sktime/sktime-tutorial-pydata-Amsterdam-2023)

- [ODSC Europe 2023 - Forecasting, Pipelines, and ML Engineering](https://github.com/sktime/sktime-tutorial-ODSC-Europe-2023/tree/main)

- [Pydata London 2023 - Time Series Classification, Regression, Distances & Kernels](https://github.com/sktime/sktime-tutorial-pydata-london-2023)

- [Pydata Berlin 2022 - Advanced Forecasting Tutorial](https://www.youtube.com/watch?v=4Rf9euAhjNc)

- [Pydata London 2022 - How to implement your own estimator in sktime](https://www.youtube.com/watch?v=S_3ewcvs_pg)

- [Pydata Global 2022 - Feature extraction, Pipelines, Tuning](https://github.com/sktime/sktime-tutorial-pydata-global-2022)


## :wave: How to contribute

If you're interested in contributing to sktime, you can find out more how to get involved [here](https://www.sktime.net/en/latest/get_involved.html).

Any contributions are welcome, not just code!

## Installation instructions for local use

To run the notebooks locally, you will need:

* a local repository clone
* a python environment with required packages installed

### Cloning the repository

To clone the repository locally:

`git clone https://github.com/sktime/sktime-presentation-pydata-nyc-2023.git`

### Using conda env

1. Create a python virtual environment:
`conda create -y -n pydata_nyc_sktime python=3.9`
2. Install required packages:
`conda install -y -n pydata_nyc_sktime pip sktime seaborn jupyter pmdarima statsmodels`
3. Activate your environment:
`conda activate pydata_nyc_sktime
4. If using jupyter: make the environment available in jupyter:
`python -m ipykernel install --user --name=pydata_nyc_sktime`

### Using python venv

1. Create a python virtual environment:
`python -m venv pydata_nyc_sktime`
2. Activate your environment:
`source pydata_nyc_sktime/bin/activate`
3. Install the requirements:
`pip install sktime seaborn jupyter pmdarima statsmodels`
4. If using jupyter: make the environment available in jupyter:
`python -m ipykernel install --user --name=pydata_nyc_sktime`
