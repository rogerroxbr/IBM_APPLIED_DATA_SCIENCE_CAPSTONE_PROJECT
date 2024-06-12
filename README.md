# Applied Data Science Capstone Project - IBM
## Description
This repository contains the material developed during the Capstone Project of the Applied Data Science program by IBM. The goal of this project is to apply the knowledge acquired throughout the course to a real-world data science problem, utilizing advanced data analysis, machine learning, and visualization tools and techniques.

## Summary 
This capstone project will ultimately **predict if the Space X Falcon 9 first stage will land successfully**. 

### Context and Business Understanding
- SpaceX launches Falcon 9 rockets at a cost of around $62m. This is considerably cheaper than other providers (which usually cost upwards of $165m), and much of the savings are because SpaceX can land, and then re-use the first stage of the rocket. 

- If we can make predictions on whether the first stage will land, we can determine the cost of a launch, and use this information to assess whether or not an alternate company should bid against SpaceX for a rocket launch.

## 📑 Main Topics 
This project follows these steps:
1. `Data Collection`
    - Making GET requests to the SpaceX REST API
    - Web Scraping
    
2. `Data Wrangling` 
    - Using the `.fillna()` method to remove NaN values
    - Using the `.value_counts()` method to determine the following:
        - Number of launches on each site
        - Number and occurrence of each orbit
        - Number and occurrence of mission outcome per orbit type
    - Creating a landing outcome label that shows the following:
        - 0 when the booster did not land successfully
        - 1 when the booster did land successfully

3. `Exploratory Data Analysis`
    - Using SQL queries to manipulate and evaluate the SpaceX dataset
    - Using Pandas and Matplotlib to visualize relationships between variables, and determine patterns

4. `Interactive Visual Analytics`
    - Geospatial analytics using Folium
    - Creating an interactive dashboard using Plotly Dash

5. `Predictive Analysis` (`Classification`)
    - Using Scikit-Learn to:
        - Pre-process (standardize) the data
        - Split the data into training and testing data using train_test_split
        - Train different classification models
        - Find hyperparameters using GridSearchCV
    - Plotting confusion matrices for each classification model
    - Assessing the accuracy of each classification model


## 🔑 Key Skills Learned/Used 
- Using data science methodologies to define and formulate a real-world business problem
- Using data analysis and data visualisation to load a dataset, clean it, and find out interesting insights from it
- Interactive dashboard development with Plotly Dash
- Interactive map development using Folium
- Using machine learning to build a predictive model to help a business function more efficiently
- Structuring and building a data-findings report

