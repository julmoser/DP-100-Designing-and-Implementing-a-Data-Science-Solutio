# Lab Introduction

### The Azure Machine Learning service:  Putting it all together.

In this lab, we introduce our workshop case study which involves training and deploying a predictive model using the Azure Machine Learning service. This lab requires the student have access to the Azure Notebook service and an Azure subscription.

# Workshop Case Study

## Scenario

You've been assigned a new customer, Adventure Works LLC, which sells bicycles and bicycle equipment to its customers.

Adventure Works Cycles is a large multinational manufacturing company. It manufactures and sells bicycles and bicycle components to the North American, European and Asian commercial markets through both an internet channel and a reseller distribution network. Its base operations are in Kirkland, Washington with 290 employees, and there are several regional sales teams located throughout their market base.

Coming off a successful fiscal year, Adventure Works is looking to increase its revenue by targeting additional sales to their existing customers. Although Adventure Works sells bike accessories and components, the majority of business is in bike sales.  A marketing study shows that many customers who bought component and accessories, have never purchased a bike from Adventure Works.  They want to target these customers with bike sale promotions.  Rather than send blanket emails or display generic online ads, they have asked the data science team to create a predictive machine learning model that identifies the type of bike that a customer is most likely to purchase.  The assumption is that based on customer demographics and sales data, it should be feasible to determine the type of bike a customer will buy: Road, Mountain, or, Touring.  Note:  Phase two of this project will build on this model to predict the specific bike model a customer will buy but we want to start slow.

Using customer and sales history, marketing believes you have what you need to create a predictive model.  It is critical that the model be able to scale as needed to support increased usage from multiple applications, i.e. emails, online ads, direct mail, etc.  You need to provide a standard way to score data with your model, i.e. an easy to use an API. Marketing is eager to get this developed and deployed as soon as possible so you are encouraged to find ways to speed things up.

Your objective is to do the following:

- Perform Exploratory Data Analysis (EDA) to determine which historical data will help predict the bike purchased. 
- Based on the outcome of the EDA, create the model features, aka perform feature engineering.
- Determine the type of machine learning model you need.  This will involve trying several models, evaluating their performance, and selecting the best one.
- As part of selecting the best performing model, you need to determine the optimal model hyperparameters. 
- Deploy the trained model to an environment where it can be easily called.
- Test using the model.
- Monitor the model's use.

### Solution

You will be implementing the solution using Azure Machine Learning service.  Azure Notebook provide the interactive development environment (IDE) and Python will be our programming language. Azure Notebook is pre-configured with the Azure Machine Learning software development kits (SDKs) you need and most of the popular Python data science related packages. 

- Using a data extract provided by the data engineer, you will do some exploratory data analysis and create several additional features for the model.

- You will create a completely open source based classification model and evaluating its performance.

- You will extend the model training code you created to leverage the Azure Machine Learning service.

- You want to be though in selecting the best model but do not have time to train and compare numerous types.  To speed things up, you will use Azure Machine Learning service AutoML to select the best model and determine the optimal hyperparameter values. 

- You will register the model and the container image to the Azure Machine Learning service workspace.

- Then you will deploy the model and test it. 

- You will monitor your model via Python.

A starting Azure Notebook in each lab provides the structure of the lab.  More details about the above steps are provided in the lab technical requirements and the Azure notebook.

