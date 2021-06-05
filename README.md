# Machine-Learning-Challenge
![exoplanets](https://user-images.githubusercontent.com/75814760/120879376-84d97500-c588-11eb-920a-dac0c167dd98.jpg)

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, you will create machine learning models capable of classifying candidate exoplanets from the raw dataset.

## Getting Started
1. Create a new repository for this project and give it a name resembling the project.

1. Clone the new repository to your computer.

1. Give each model you choose their own Jupyter notebook, do not use more than one model per notebook.

1. Save your best model to a file.

1. Commit your Jupyter notebooks and model file and push them to GitHub.

## Summary
In this project we will be looking to tune different classification models and compare them against one another. The models that we decided to use were:

* Support Vector Machines (SVM)

* K Nearest Neighbors (KNN)

* Nueral Networks / Deep Learning

Knowing that these are the classification models that we would be using, we will now need to:

### Process the Data

* Preprocess the dataset prior to fitting the model.
* Perform feature selection and remove unnecessary features.
* Use MinMaxScaler to scale the numerical data.
* Separate the data into training and testing data.

### Tune Model Parameters

* Use GridSearch to tune model parameters.

### Compare the models

* Tune and compare the models against one another

## Support Vector Machines (SVM)

![SVM](https://user-images.githubusercontent.com/75814760/120879719-fb777200-c58a-11eb-9431-21030ecb0c69.jpg)


## KNN

![KNN](https://user-images.githubusercontent.com/75814760/120907141-cc154380-c624-11eb-9153-1fa1e47cee85.jpg)

## Neural Network

![neural_network](https://user-images.githubusercontent.com/75814760/120879844-f666f280-c58b-11eb-9612-5e98301e8f72.jpg)

## Deep Neural Network

![deep_neural](https://user-images.githubusercontent.com/75814760/120879850-0383e180-c58c-11eb-858e-02d213de5964.jpg)

## Dataset

* [Kepler Exoplanet Search Results](https://www.kaggle.com/nasa/kepler-exoplanet-search-results)

## Fidnings
All of the models were able to achieve at least an 85% accuracy on the test data. Therefore it may be fair to assume that any of the models would be good enough to predict new exoplanets. As they all shown a high degree of accuracy. However, with an accuracy score of 90.4%, the Deep Neural Network was shown to be the most accurate. The second most accurate model was the Neural Network. This leads me to believe that the more layers that you add to the Neural Network, the more accurate it becomes. We may have been able to achieve a higher accuracy score if we continued to add additional layers.

## Built With

* Pandas
* Jupyter Notebook
* Visual Studio Code

## Languages

* Python

## Author(s)

* Chris Pope

## Contact:

__Email:__ popex107@umn.edu
