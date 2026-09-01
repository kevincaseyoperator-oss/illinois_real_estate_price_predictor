# Illinois Real Estate Price Predictor

A data analysis and machine learning project exploring factors that affect residential real estate prices in Illinois.

## Project Overview

I analyzed Illinois real estate data using Python and pandas to explore how property characteristics and location relate to listed prices. I then built a linear regression model to predict property prices based on features including bedroom count, bathroom count, and property area.

## What I Did

- Cleaned and processed real estate data using pandas
- Performed exploratory data analysis on Illinois properties
- Analyzed price differences across Illinois cities
- Examined relationships between bedrooms, bathrooms, property area, and price
- Visualized real estate price distributions and trends
- Built a linear regression model using scikit-learn to predict property prices
- Evaluated limitations of the model, including the absence of location as a predictive feature

## Technologies

- Python
- pandas
- scikit-learn
- Jupyter Notebook

## Model

The initial model uses:

- Number of bedrooms
- Number of bathrooms
- Property area

to predict listed property price.

One limitation is that location is not currently incorporated into the regression model. The exploratory analysis showed substantial differences in prices between Illinois cities, suggesting that location would be an important feature to incorporate in future versions.
