# Salary Prediction 2023

This repository contains code for a machine learning project that analyzes survey data and predicts salaries based on various features. The project utilizes Python and several libraries, including pandas, matplotlib, plotly, geopandas, and scikit-learn. Additionally, it includes an implementation of a Streamlit web application for interactive exploration and prediction.

## Project Overview

The project focuses on analyzing survey data from a CSV file and predicting salaries based on different features. The main steps of the project include:

1. Importing the necessary libraries and loading the CSV file using pandas.
2. Data cleaning and preprocessing, including selecting specific columns, renaming columns, and filtering out rows with missing values.
3. Exploratory data analysis (EDA) to gain insights into the dataset, such as counting occurrences of unique values in the "Country" column and visualizing salary distributions by country.
4. Geospatial visualization using geopandas and plotly to display survey respondents by country on a world map.
5. Cleaning and transforming categorical columns, such as "YearsCodePro" and "EdLevel," to numerical representations using LabelEncoder.
6. Building and evaluating regression models, including Linear Regression, Decision Tree Regression, and Random Forest Regression, to predict salaries based on the selected features.
7. Saving the trained model and the LabelEncoder objects using pickle for future use.
8. Implementing a Streamlit web application for interactive exploration and prediction. The application allows users to choose between exploring the data and making salary predictions.

## Usage

To use this project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies listed in the `requirements.txt` file using `pip install -r requirements.txt`.
3. Run the Streamlit application using the command `streamlit run app.py`.
4. In the Streamlit web application, select either the "Predict" or "Explore" option from the sidebar.
   - "Predict" allows you to make salary predictions based on selected features.
   - "Explore" provides visualizations and insights into the dataset.
5. Follow the instructions provided in the web application to interact with the features and obtain the desired results.

## Project Structure

The project structure is organized as follows:

- `app.py`: Main file that implements the Streamlit web application and handles the different pages for prediction and exploration.
- `predict_page.py`: Module that defines the functionality for the prediction page in the Streamlit application.
- `explore_page.py`: Module that defines the functionality for the exploration page in the Streamlit application.
- `saved_steps.pkl`: File containing the saved model and LabelEncoder objects for loading and using the trained model.

## Conclusion

This machine learning project provides an example of how to analyze survey data, predict salaries, and implement a web application using Streamlit. It showcases various data cleaning, preprocessing, visualization, and modeling techniques. Feel free to explore the code, modify it according to your needs, and adapt it to your own datasets.

If you have any questions or feedback, please don't hesitate to reach out.

Happy exploring and predicting!
