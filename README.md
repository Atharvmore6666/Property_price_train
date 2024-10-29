# Property_price_train
This property price prediction project leverages machine learning to estimate housing prices based on various property features. Using Linear Regression and XGBoost, the model was trained to maximize prediction accuracy. Key metrics were evaluated to assess model performance, aiming for precision in property valuation.


# Project Overview
This project predicts property prices using a dataset of real estate features. We apply Linear Regression and XGBoost models to optimize prediction accuracy, providing a robust estimate of property values. Performance metrics like R-squared, adjusted R-squared, RMSE, and MAPE guide the model evaluation process.

# Dataset Columns and Data Types
Id - int64
Building_Class - int64
Zoning_Class - object
Lot_Extent - float64
Lot_Size - int64
Road_Type - object
Lane_Type - object
Property_Shape - object
Land_Outline - object
Utility_Type - object
Lot_Configuration - object
Property_Slope - object
Neighborhood - object
Condition1 - object
Condition2 - object
House_Type - object
House_Design - object
Overall_Material - int64
House_Condition - int64
Construction_Year - int64
Remodel_Year - int64
Roof_Design - object
Roof_Quality - object
Exterior1st - object
Exterior2nd - object
Brick_Veneer_Type - object
Brick_Veneer_Area - float64
Exterior_Material - object
Exterior_Condition - object
Foundation_Type - object
Basement_Height - object
Basement_Condition - object
Exposure_Level - object
BsmtFinType1 - object
BsmtFinSF1 - int64
BsmtFinType2 - object
BsmtFinSF2 - int64
BsmtUnfSF - int64
Total_Basement_Area - int64
Heating_Type - object
Heating_Quality - object
Air_Conditioning - object
Electrical_System - object
First_Floor_Area - int64
Second_Floor_Area - int64
LowQualFinSF - int64
Grade_Living_Area - int64
Underground_Full_Bathroom - int64
Underground_Half_Bathroom - int64
Full_Bathroom_Above_Grade - int64
Half_Bathroom_Above_Grade - int64
Bedroom_Above_Grade - int64
Kitchen_Above_Grade - int64
Kitchen_Quality - object
Rooms_Above_Grade - int64
Functional_Rate - object
Fireplaces - int64
Fireplace_Quality - object
Garage - object
Garage_Built_Year - float64
Garage_Finish_Year - object
Garage_Size - int64
Garage_Area - float64
Garage_Quality - object
Garage_Condition - object
Pavedd_Drive - object
W_Deck_Area - float64
Open_Lobby_Area - float64
Enclosed_Lobby_Area - float64
Three_Season_Lobby_Area - int64
Screen_Lobby_Area - int64
Pool_Area - int64
Pool_Quality - object
Fence_Quality - object
Miscellaneous_Feature - object
Miscellaneous_Value - int64
Month_Sold - int64
Year_Sold - int64
Sale_Type - object
Sale_Condition - object
Sale_Price - int64

# Motivation
With real estate prices fluctuating, accurately predicting property values is critical for buyers, sellers, and investors. This project offers a data-driven approach to estimate prices, aiding informed decision-making.

# Methodology
Data Preprocessing: Handling missing values, outliers, and encoding categorical variables.
Feature Engineering: Selecting relevant features, standardizing continuous variables.
Modeling: Implemented Linear Regression and XGBoost models, evaluating metrics such as R-squared, Adjusted R-squared, MSE, RMSE, and MAPE.
Results
## Linear Regression: R-squared: 0.858, Adj. R-squared: 0.848, RMSE: 38,288, MAPE: 11.47%
## XGBoost: R-squared: 0.9999, Adj. R-squared: 0.9999, RMSE: 38,078
# Conclusion
The XGBoost model shows high accuracy for property price predictions, suitable for real estate price estimation. Future work may involve refining features to enhance model robustness and testing across different regions.
