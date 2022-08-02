# Building Energy Prediction

This is a Python ipynb notebook I created for my final year ComSci degree project, which processes/visualises several public datasets and builds/trains a [long short-term memory recurrent neural network (LSTM RNN)](https://en.wikipedia.org/wiki/Long_short-term_memory) to create a predictor model for the electricity consumption of building based on its neighbours, weather and other building factors.

The original purpose was to demonstrate that an LSTM RNN is suitable for the task above. The code was supposed to use past building data to predict the same building's future consumption, but a data shaping mistake meant it used neighbouring buildings instead. Consequently, accuracy of predictions is not optimal, but was invaluable in helping me learn through the project.

Because this repo is intended to stay as-is from the time it was originally completed, it's been marked as archived.

## Dependancies
- [Python](https://www.python.org/downloads/) 3.6+
- [Matplotlib](https://matplotlib.org/)
- [Numpy](https://numpy.org/install/)
- [Pandas](https://pandas.pydata.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Statsmodels](https://www.statsmodels.org/stable/index.html)
- [Scikit-learn](https://scikit-learn.org/stable/)
- [Tensorflow](https://www.tensorflow.org/) 2
- [Keras](https://keras.io/)

## Data
The public datasets used for this project can be found [here](https://www.kaggle.com/c/ashrae-energy-prediction/data).

## Compatibility
The notebook was built and ran via [Google Colab](https://colab.research.google.com/) on both a CPU and GPU based runtime. TPU runtimes weren't tested.
