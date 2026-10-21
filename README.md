# King County House Sales Prediction

## The Problem or Research Question
How can we accurately predict the market price of a house in King County, USA, based on its physical attributes such as square footage, number of bedrooms, grade, and location? The goal is to provide a reliable regression model for real estate investment decisions.

## Dataset Source and Usage Permissions
The dataset is sourced from Kaggle (House Sales in King County, USA), which is publicly available for educational and analytical purposes. It contains home sales between May 2014 and May 2015.

## Methods and Tools Used
- **Languages & Libraries:** Python, Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib.
- **Methods:** Data Cleaning, Exploratory Data Analysis (EDA), Multiple Linear Regression, Polynomial Transformation, Ridge Regression.

## Key Findings and Limitation
**Key Finding:** Features like `sqft_living` and `grade` are the strongest predictors. Applying a 2nd-order polynomial transformation with Ridge regression significantly improved the model's test R² score compared to standard linear regression.
**Limitation:** The model can suffer from heteroscedasticity and might not generalize well to luxury homes (over $2 million) due to a lack of training samples in that price range.

## Instructions for Running the Analysis
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Open the Jupyter Notebook (`CISC7204 Assgn01 Module 06 - Practice Project...ipynb`) and run all cells.
