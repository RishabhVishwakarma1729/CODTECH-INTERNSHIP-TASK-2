California Housing Price Prediction
This project demonstrates a linear regression model applied to the California Housing dataset. The notebook includes steps for importing necessary libraries, loading the dataset, splitting it into training and testing sets, training the linear regression model, making predictions, and evaluating the model's performance using mean squared error and R² score.

Table of Contents
Introduction
Dataset
Installation
Usage
Results
Contributing
License
Introduction
The goal of this project is to predict housing prices in California based on various features such as median income, housing median age, total rooms, total bedrooms, population, households, latitude, and longitude. We use a linear regression model to achieve this.

Dataset
The dataset used in this project is the California Housing dataset, which contains information collected during the 1990 California census. The dataset includes the following features:

MedInc: Median income in block group
HouseAge: Median house age in block group
AveRooms: Average number of rooms per household
AveBedrms: Average number of bedrooms per household
Population: Block group population
AveOccup: Average number of household members
Latitude: Block group latitude
Longitude: Block group longitude
Installation
To run this project, you need to have Python and Jupyter Notebook installed. You can install the required Python packages using the following command:

bash
Download
Copy code
Usage
Clone the repository:
bash
Download
Copy code
Navigate to the project directory:
bash
Download
Copy code
Open the Jupyter Notebook:
bash
Download
Copy code
Run the cells in the notebook to see the analysis and results.
Results
The notebook includes the following steps:

Importing necessary libraries: Import libraries such as pandas, numpy, matplotlib, seaborn, and scikit-learn.
Loading the dataset: Load the California Housing dataset.
Exploratory Data Analysis (EDA): Visualize and understand the data distribution and relationships between features.
Data Preprocessing: Handle missing values, encode categorical variables, and scale numerical features.
Splitting the dataset: Split the dataset into training and testing sets.
Training the model: Train a linear regression model on the training set.
Making predictions: Use the trained model to make predictions on the testing set.
Evaluating the model: Evaluate the model's performance using mean squared error (MSE) and R² score.
Contributing
Contributions are welcome! If you have any suggestions or improvements, please open an issue or submit a pull request.
