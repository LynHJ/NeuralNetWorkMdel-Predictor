# NeuralNetworkModel-Predictor

![](https://img.shields.io/badge/scikit_learn-1.0.2-informational?style=plastic&logo=appveyor)
![](https://img.shields.io/badge/tensorflow-2.11.0-informational?style=plastic&logo=appveyor)
![](https://img.shields.io/badge/pandas-1.3.5-informational?style=plastic&logo=appveyor)
![](https://img.shields.io/badge/protobuf-3.19.6-informational?style=plastic&logo=appveyor)

![alt text]()

## Background

The purpose of this project is demonstrate how to use unsupervised machine learning skill to classify a data set regarding to myopia. 

## Pre-Aanalsis

<p align="center"><img src='' width= 80% ></p>   

### Sub-Summary:

When I designed the first model, I was trying to simplify the data and apply a shallow deep learning model. For each non-numeric-data column, I categorized them into two categories, a category which has the highest count numbers and the other. After I had executed the whole process, I realized that the way I binned data might confuse the model as the organization did not simply use dichotomy to assess each applicant. 

## Optimized-Aanalsis
<p align="center"><img src='' width= 80% ></p>

### Summary:

I demonstrated how I optimized my model on page 4~page 6 in the Analysis Report. The final result is shown above.

This dataset is the records about an organization following their existing procedures and established requirements to assess the applicants who can get support or not. However, the deep-learning model is based on supervised machine learning and normally using unstructured data. For example, to classify cats and dogs. 

In my opinion, supervised machine learning might be a better way to create a classifier. As this data set has 10 features and 50 columns after executing the dummy method, applying the “Random Forest Classifier Model” might be a suitable option to build up a classifier.
  

## Content:
```
Project
├── AlphabetSoupCharity.h5
├── AlphabetSoupCharity.ipynb
├── AlphabetSoupCharity_Optimisation.h5
├── AlphabetSoupCharity_Optimisation.ipynb
├── Analysis Report.pdf
├── Image
│   ├── neural network.jpg
│   ├── Optimized-Aanalsis
│   └── Pre-Aanalsis
├── README.md
├── Resources
│   └── charity_data.csv
└── requirements.txt
```

## Installation

pip install -r requirements.txt















