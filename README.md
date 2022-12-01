# NeuralNetworkModel-Predictor

![](https://img.shields.io/badge/scikit_learn-1.0.2-informational?style=plastic&logo=appveyor)
![](https://img.shields.io/badge/tensorflow-2.11.0-informational?style=plastic&logo=appveyor)
![](https://img.shields.io/badge/pandas-1.3.5-informational?style=plastic&logo=appveyor)
![](https://img.shields.io/badge/protobuf-3.19.6-informational?style=plastic&logo=appveyor)

![alt text](https://github.com/LynHJ/NeuralNetWorkMdel-Predictor/blob/9c865eaf09447bb2452a963b95d36a27ef851d48/Image/neural%20network.jpg)


## Background

The non-profit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With knowledge of machine learning and neural networks, I’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.  

In this analtsis, I will use ‘Colab’, one of Google's services to go through the whole process with a dataset which has 11 features.  

This analysis has two parts. First part is using a shallow neural network learning model to test the dataset. Based on the result from the first part, doing further data cleaning and transforming and then building up a for-loop method to target the best combination of classifier model.  


## Pre-Aanalsis

<p align="center"><img src='https://github.com/LynHJ/NeuralNetWorkMdel-Predictor/blob/9c865eaf09447bb2452a963b95d36a27ef851d48/Image/Pre-Aanalsis.png' width= 80% ></p>    

### Sub-Summary:

When I designed the first model, I was trying to simplify the data and apply a shallow deep learning model. For each non-numeric-data column, I categorized them into two categories, a category which has the highest count numbers and the other. After I had executed the whole process, I realized that the way I binned data might confuse the model as the organization did not simply use dichotomy to assess each applicant. 

## Optimized-Aanalsis

<p align="center"><img src='https://github.com/LynHJ/NeuralNetworkModel-Predictor/blob/9c865eaf09447bb2452a963b95d36a27ef851d48/Image/for-loop.png' width= 80% ></p> 
<p align="center"><img src='https://github.com/LynHJ/NeuralNetWorkMdel-Predictor/blob/9c865eaf09447bb2452a963b95d36a27ef851d48/Image/Optimized-Aanalsis.png' width= 80% ></p>  

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















