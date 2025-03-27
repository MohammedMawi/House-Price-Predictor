# House Price Predictor
This was one of my first machine learning projects, where I built a regression model to predict house prices using structured housing data. It gave me hands-on experience with cleaning data, feature engineering, working with models like Linear Regression and Random Forest, and understanding how model evaluation works in the real world.

# About the Dataset
The dataset includes information like:

Area of the house

Number of bedrooms and bathrooms

Whether it had a basement, guestroom, AC, etc.

Furnishing status and location preferences

And the target: price

It wasn’t super detailed (e.g., no neighborhood or age info), but it was enough to practice working with structured features and handling categorical data.

# What I Did
Cleaned and prepared the data using Pandas

Combined some features (like bedrooms + bathrooms = total rooms)

Removed outliers using IQR

One-hot encoded categorical columns

Trained two models:

Linear Regression

Random Forest Regressor

Evaluated them using Mean Absolute Error and R² Score

# Results
The best R² I got was around 63%

MAE stayed around 700k, which makes sense considering the wide range of house prices

The model worked decently on higher-end homes, but it struggled with mid-range predictions — mostly due to limited features in the dataset

# What I Learned
How to prepare a dataset for machine learning

The importance of feature engineering

How to evaluate regression models beyond just accuracy

That sometimes your model isn’t “bad” — the data just has limitations

Most importantly: done is better than perfect — and I finished it!

# Tools & Libraries
Python

Pandas

Scikit-learn

Matplotlib / Seaborn

Jupyter Notebook

# What’s Next
I’m thinking about coming back to this project later with a better dataset (maybe one focused on Toronto), adding more meaningful features, and building a web-based version with a simple UI for users to interact with.

