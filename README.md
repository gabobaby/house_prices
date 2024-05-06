# house_prices

## Project Overview
This project is part of the Kaggle House Prices: Advanced Regression Techniques competition. The goal is to predict the sales prices of houses in Ames, Iowa, based on a comprehensive set of features described in the data set. This model aims to employ various regression techniques to effectively predict the prices.

## Dataset
The dataset used in this project contains 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa. This dataset is provided by Kaggle and can be accessed here: (https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)

## File Descriptions
* train.csv - the training set
* test.csv - the test set
* data_description.txt - full description of each column
* sample_submission.csv - a sample submission file in the correct format

## Libraries Used
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## Installation
To run this project, install the above libraries using pip:
pip install pandas numpy scikit-learn matplotlib seaborn


## Usage
To replicate the findings and run the scripts, execute the Jupyter notebooks in the following order:

1. Data Exploration.ipynb - This notebook includes exploratory data analysis of the dataset.
2. Data Cleaning.ipynb - This notebook handles all the data cleaning and preprocessing tasks.
3. Model Building.ipynb - Various regression models are built and evaluated in this notebook.

## Model Deployment
The final model is deployed as a web service, accessible via a REST API endpoint. Instructions for accessing the endpoint are as follows:
* URL: [Insert URL]
* Method: POST
* Body: { "feature1": value1, "feature2": value2, ... }

## Contributing
Contributions, issues, and feature requests are welcome. Feel free to check issues page if you want to contribute.

## Authors
Gabe Moreno - Initial work - @gabobaby

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgements
* Kaggle for the dataset and descriptions
* Ames Housing dataset documentation
* Inspiration from other Kaggle kernels
