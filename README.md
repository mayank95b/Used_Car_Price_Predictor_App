# ML Based Used Car Price Predictor App

The objective of the project is to build a Web App to predict the selling price of the used car by using Machine Learning model.

## Description

Implemented linear regression and scikit-learn to make an optimal model for predicting selling prices of used car using the Vehicle dataset from cardekho available at kaggle. https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho

This dataset contains information about used cars listed on www.cardekho.com

This data can be used for a lot of purposes such as price prediction to exemplify the use of linear regression in Machine Learning.
The columns in the given dataset are as follows:

- name
- year
- selling_price
- km_driven
- fuel
- seller_type
- transmission
- Owner


## Software and Libraries

This project uses the following software and Python frameworks/libraries:

- Python
- NumPy
- pandas
- matplotlib
- scikit-learn
- Flask
- Flasgger
- Swagger
- Docker
- Streamlit
    
## Tools/IDE

- Jupyter notebook (IPython)
- Docker
- Atom

## How to use it

    Fork this repository to have your own copy
    Clone your copy on your local system
    Install docker desktop software
    build the docker file using : "sudo docker build -t car_api"
    run the docker using : "docker run -p 8000:8000 car_api"
