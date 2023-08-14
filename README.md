# Rental Price Predictions Project By GuviOfficial

![Static Badge](https://img.shields.io/badge/Linear_Regression-Supervised_Machine_Learning-blue)

## <div id=0>Problem Statement</div>

The goal of this project is to develop a data-driven model that predicts the rental price of
residential properties based on relevant features. By analyzing historical rental data and
property attributes, the model aims to provide accurate and reliable rent predictions.

## Dataset Description

There are 25 attributes in each case of the dataset which are:

1. **id** : A unique identifier for each property listing.
2. **type** : The type of property, such as BHK1, BHK2, RK1, etc.
3. **locality** : The specific neighborhood or area where the property is located.
4. **activation_date** : The date when the property listing was activated or made available for
   rent.
5. **latitude** : The geographic latitude coordinate of the property's location.
6. **longitude** : The geographic longitude coordinate of the property's location.
7. **lease_type** : The type of lease, such as FAMILY or BACHELOR, or ANYONE
8. **gym** : Indicates whether the property has a gym or fitness facility.
9. **lift** : Indicates whether the property has an elevator or lift.
10. **swimming_pool** : Indicates whether the property has a swimming pool.

11. **negotiable** : Indicates whether the rent price is negotiable.
12. **furnishing** : Describes the level of furnishing, e.g., fully furnished, partially furnished,
    unfurnished.
13. **parking** : Specifies the availability of parking facilities.
14. **property_size** : The size of the property in terms of square footage or square meters.
15. **property_age** : The age of the property since construction.
16. **bathroom** : The number of bathrooms available in the property.
17. **facing** : The direction in which the property faces, e.g., north, south, east, west.
18. **cup_board** : Indicates the presence of cupboards or storage units.
19. **floor** : The floor number on which the property is located.
20. **total_floor** : The total number of floors in the building.
21. **amenities** : Additional amenities or features provided with the property.
22. **water_supply** : The type and availability of water supply.
23. **building_type** : The architectural style or type of building, e.g.,Apartment, Individual
    House
24. **balconies** : The number of balconies or outdoor spaces.
25. **rent** : The target variable, representing the rental price for the property.

## Aim

- Develop a data-centric framework with the goal of predicting residential property rental costs based on relevant features.
- Anticipate rental prices by analyzing significant property attributes and characteristics.
- Utilize historical rental data and property details to enhance the accuracy of predictions.
- Strive to provide reliable and precise rent forecasts using the developed model.

## Technologies

Technologies that were used while creating this project were -

- **<span style="color:red">Cleansing</span>** : Data cleansing was indispensable to eliminate inconsistencies, errors, and outliers from the rental dataset.
- **<span style="color:red">EDA</span>** : Through visualizations, statistical summaries, and pattern recognition, EDA enabled the identification of trends, correlations, and potential hidden insights among the rental-related attributes.
- **<span style="color:red">Visualization</span>** : Visual representations of data distributions, trends, and geographical patterns aided in presenting a clear and coherent narrative regarding the factors influencing rental prices. This not only fostered better understanding among project participants but also guided informed decisions on feature engineering and model design.
- **<span style="color:red">ML</span>** : By using ML techniques, the model was able to learn from historical rental data and attribute relationships discovered during the EDA phase. This enabled the model to generalize patterns, predict rental prices for new instances, and adapt to changing rental market dynamics over time.

The culmination of these technologies ensured that the predictive model achieved the desired accuracy, robustness, and applicability in forecasting rental prices for residential properties.

## Requirements

- Python3 and pip

## Libraries

- **Matplotlib** : It is the basic plotting library in Python. It provides tools for making plots.
- **Pandas** : It provides tools for data storage, manipulation and analysis tasks.
- **Seaborn** : Used in making statistical graphics
- **json** : It allows you to encode and decode custom objects by using JSON encoder and decoder classes.
- **numpy** : It provides a fast numerical array structure and operating functions.
- **sklearn** : It provides a selection of efficient tools for machine learning and statistical modeling.

## Data Cleaning

### Type: 1 - Unnecessary Data

- id
- locality : Data within this column spans over a wide range.
- activation_date

### Type: 2 - Boolean Data

- gym
- swimming_pool
- lift
- negotiable

### Type: 3 - Categorical Data

- type
- lease_type
- furnishing
- parking
- facing
- water_supply
- building_type

### Type: 4 - Numerical Data - No preprocessing required

- lattitude
- longitude
- property_size
- property_age
- bathroom
- cup_board
- floor
- total_floor
- balconies

### Type: 5 - String Object Data

- amenities

## References

The concepts in this project have been refered from the following websites -

- https://en.wikipedia.org/wiki/Linear_regression
- https://en.wikipedia.org/wiki/Root-mean-square_deviation
