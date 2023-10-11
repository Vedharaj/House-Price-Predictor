# House Price Preditor

[![Author Vedharaj](https://img.shields.io/badge/Author-Vedharaj-d62828)](https://www.linkedin.com/in/ebaneshar-vedharaj-422566214)

>This is my initial Python machine learning project, and I am constantly working on it.




## Introduction
Beginner's machine practice program. Determine the cost of a house using **linear Regression** techniques. If you begin the adventure of machine learning, it can be quite helpful.

## Usage

Download this respo using git

```
git clone https://github.com/Vedharaj/House-Price-Predictor.git
```

go to directory

```
cd House-Price-Predictor
```

install the requirements libary using pip

```
pip install -r requirements.txt
```
## feature Usage

This model was trained with **62 columns**, **1462 rows**, and one independent variable (SalePrice) to predict the house price (responce).
- SalePrice - the property's sale price in dollars.
- MSSubClass: The building class
- MSZoning: The general zoning classification
- LotFrontage: Linear feet of street connected to property
- LotArea: Lot size in square feet
- Street: Type of road access etc..,

## model performance

- R2 score - 6.2/10
- MAE: 23745.76
- MSE: 2522874086.973

## export the model

```
import pickle
with open("model.pkl", "wb") as f:
    pickle.dump(mod, f)
```
## License

MIT
