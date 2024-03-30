# Linear-Regression-Model-
## California Housing Price Prediction
### Overview
This project aims to predict the housing prices in California using a Linear Regression model. The dataset used for training and evaluation is the California Housing dataset, which contains various features related to housing attributes in different districts of California.

### Dataset
The California Housing dataset used in this project is sourced from the UCI Machine Learning Repository. It consists of 20,640 instances and 8 attributes, including median house value, median income, housing median age, average rooms, average bedrooms, population, households, and geographical coordinates.

### Approach
Data Preprocessing: Exploratory Data Analysis (EDA) was conducted to understand the distribution of features, identify missing values, and handle outliers. Features were scaled to ensure uniformity in the range.

Feature Engineering: Additional features such as population per household, rooms per household, and bedrooms per room were derived to provide more meaningful insights to the model.

Model Training: A Linear Regression model was trained on the preprocessed dataset. Cross-validation techniques were employed to assess the model's performance and ensure generalization.

Evaluation: The model's performance was evaluated using various regression metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

Deployment: The trained model was deployed to predict housing prices for new instances.

### Requirements
Python 3.x
Jupyter Notebook or any Python IDE
Required libraries specified in requirements.txt
Usage
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/california-housing-prediction.git
Navigate to the project directory:

bash
Copy code
cd california-housing-prediction
Install the required libraries:

Copy code
pip install -r requirements.txt
Run the Jupyter Notebook california_housing_prediction.ipynb to train the model and make predictions.

### Results
The trained Linear Regression model achieved satisfactory results with the following performance metrics:

Mean Absolute Error (MAE): [Insert MAE value]
Mean Squared Error (MSE): [Insert MSE value]
Root Mean Squared Error (RMSE): [Insert RMSE value]
