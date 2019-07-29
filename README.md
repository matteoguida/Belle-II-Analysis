# Belle II analysis &emsp;&emsp;&emsp;&emsp;&emsp; <img src="https://s3.amazonaws.com/keras.io/img/keras-logo-2018-large-1200.png" alt="drawing" width="100"/>  &emsp;&emsp;&emsp;&emsp;&emsp; <img src="https://upload.wikimedia.org/wikipedia/commons/6/69/XGBoost_logo.png" alt="drawing" width="100"/>

### Prerequisites
Python versions supported:

[![](https://img.shields.io/badge/python-3.7-blue.svg)](https://badge.fury.io/py/root_pandas)

### Installing

You can recreate the conda environment used for this analysis with:

```
conda enf create -f environment.yml
```
# Goal
One of the studies carried out with the [Belle II experiment](https://belle2.jp/#) is time-dependent CP asymmetry in the decay channel :

<p align="center">
<img src="http://latex.codecogs.com/gif.latex?\bar{B^0} / B^0 \rightarrow \eta' \left( \eta \left( \gamma \gamma \right) \pi^+ \pi^- \right) K^0_S \left( \pi^+ \pi^- \right)" border="0"/> 
</p> 

We want to train and test a _Deep Neural Network_ (DNN) with Keras and a _Boosted Decision Tree_ with XGBoost on Montecarlo samples with labeled data and use the best models to find our signal in unlabelled data (Data Challenge).

At the end the [branching fraction](https://en.wikipedia.org/wiki/Branching_fraction) for the process is calculated. 

### Authors:

- [Valeria Fioroni](https://github.com/valeriafioroni) (University of Padova)
- [Philipp Zehetner](https://github.com/PhilippZ94) (University of Padova, Ludwig Maximilian University of Munich)
- [Matteo Guida](https://github.com/matteoguida) (University of Padova)

### Supervised by:

- Professor Marco Zanetti (University of Padova, CERN)
- Professor Stefano Lacaprara (University of Padova, BELLE2)

## Useful External Links:
1. [A high-bias, low-variance introduction to Machine Learning for physicists
](https://arxiv.org/abs/1803.08823) - Complete and continuously updated review provided with explanatory Jupyter notebooks.
2. [Scikit-HEP project](http://scikit-hep.org/) - Particle physics data analysis in Python.

