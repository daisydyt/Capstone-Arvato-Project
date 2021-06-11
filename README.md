# Capstone-Arvato-Project

This project was designed to understand what population segment(s) the customers of a mail-order company tend to belong to. It further uses this information to predict potential customers in its market campaignes, to increase efficiency. 



##  Installations

This project requires **Python 3.x** and the following Python libraries installed:

- [Numpy](https://www.numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Pandas](http://pandas.pydata.org)
- [scikit-learn](http://scikit-learn.org/stable/)
- [xgboost](https://xgboost.readthedocs.io/en/latest/python/python_intro.html)
- [Boto3](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html)
- [sagemaker](https://sagemaker.readthedocs.io/en/stable/) 


## Summary:
Arvato Financial Solutions provided the original data for the project under Udacity Machine Learning Engineer Nanodegree. The goal of the project is to increase the efficiency of the customer acquisition process of a mail-order company by applying precision marketing. 

The project can be divided into three parts:

- 1.**Customer Segmentation Report**:  In this section, I preprocessed the German population data and the company's customer data. Next, I ran the unsupervised K-Means model on German population data to identify natural segments of the population. I further applied the trained model to the customer data, to understand what population segment(s) its customers tend to belong to. 
- 2.**Supervised Learning Model**:  In this section, I used data from targets of a mail order campaign, along with the information obtained from section one, to train a machine learning model that predicts whether or not an individual will respond to a marketing campaign of the company.
- 3.**Kaggle Competition** : I utilized three machine learning models for the prediction in the Kaggle competition. I finally selected LinearLearner model based on its high ROC-AUC score. 



## Data

- `Udacity_AZDIAS_052018.csv`: Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).
- `Udacity_CUSTOMERS_052018.csv`: Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).
- `Udacity_MAILOUT_052018_TRAIN.csv`: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).
- `Udacity_MAILOUT_052018_TEST.csv`: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).

It is not allowed to publish the data provided by Arvato Financial Services. 

## Author

-   **Daisy Dai** 


## License

This project is licensed under the MIT License - see the [LICENSE.md]LICENSE.md file for details.

## Acknowledgments

I would like to thank [Udacity](https://eu.udacity.com/) for this amazing project, and [Arvato](https://www.arvato.com/)  for providing the data.
