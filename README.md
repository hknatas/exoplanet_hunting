# Exoplanet Hunting in Deep Space: Time Series Classification by Using Deep Neural Networks

In this project, kepler labelled, a univariate hugely imbalanced time series data is used to evaluate the performance of deep neural networks on imbalanced time series data. The data shows the change in flux of several thousand stars. Sudden dimmings in the flux could be an indicator that the star might have an exoplanet. Therefore, the main objective is to be able to find the regular dimmings in these flux changes and determine the stars having exoplanet(s). 

Multilayer Perceptrons (MLPs) and Fully Convolutional Networks (FCNs) are used for classification task. Since the data is quite imbalanced, apart from accuracy, confusion matrix and ROC curve were also used for the sake of measuring the success of the models properly. Also, preprocessing and solving the imbalanced data problem constitutes an important part of this classification task.

## The Data

The .csv files are hosted on [Kaggle](https://www.kaggle.com/keplersmachines/kepler-labelled-time-series-data), where a description of the datasets can also be found.

