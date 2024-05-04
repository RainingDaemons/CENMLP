# Coordinador Eléctrico Nacional Machine Learning Proyect (CENMLP)

<br/>

A proyect developed by:
- <a href="https://github.com/RainingDaemons" target="_blank"/>**RainingDaemons**</a> - Felipe Gutiérrez
- <a href="#" target="_blank"/>**Santaxx1906**</a> - Santiago Salvador

<br/>

---

## What is this?

The project "CENMLP" is a work done during April 2024 for the "CINF104: Machine Learning" course taught at the Andrés Bello University, Chile. 

The objective of the project is to create two learning models and compare their performance to predict the hourly systemic consumption required to supply different electrical substations and meet the demand estimated by the Chilean energy market, this data is publicly collected from the National Electric Coordinator (CEN).

This repository presents all the complementary materials that allow generating the learning models used for this study.

---

## How i can run it?

It is recommended to use Google Collab or configure your preferred software to run Jupyter Notebooks, the present project has the following structure:

`main.ipynb` - This notebook contains all the exploratory analysis performed for the CEN data in addition to generating as output a labeled dataset to facilitate the training of the learning models.

`model1_<sub>.ipynb` - This notebook contains the RNN model created for the `<sub>` substation that allows training and test with the labeled dataset.

`model2_<sub>.ipynb` - This notebook contains the ARIMA model created for the `<sub>` substation that allows training and test with the labeled dataset.

There are also two important documents which are:

`Project 1 ML PPT.pdf` - This document is the presentation shown in classroom based on the results obtained for models 1 and 2 in the different substations.

`Project 1 ML Report.pdf` - This document is the report based on the results obtained for models 1 and 2 in the different substations.
