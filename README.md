# Supermarket_Sales_Prediction

## Problem Statement -
#### We are opening a new Store at a particular location. Now, Given the Store Location, Area, Size and other params. Predict the overall revenue/Sale generation of the Store.

### Dataset Details- The data has 8523 rows of 12 variables.

## Dataset Description -
#### 1) Variable - Description
#### 2) Item_Identifier- Unique product ID
#### 3) Item_Weight- Weight of product
#### 4) Item_Fat_Content - Whether the product is low fat or not
#### 5) Item_Visibility - The % of total display area of all products in a store allocated to the particular product
#### 6) Item_Type - The category to which the product belongs
#### 7) Item_MRP - Maximum Retail Price (list price) of the product
#### 8) Outlet_Identifier - Unique store ID
#### 9) Outlet_Establishment_Year- The year in which store was established
#### 10) Outlet_Size - The size of the store in terms of ground area covered
#### 11) Outlet_Location_Type- The type of city in which the store is located
#### 12)Outlet_Type- Whether the outlet is just a grocery store or some sort of supermarket
#### Item_Outlet_Sales - Sales of the product in the particulat store. This is the outcome variable to be predicted.

## Models Used for Prediction -
#### 1) Linear Regression (alg1)
#### 2) Ridge Regression (alg2)
#### 3) Decision Tree Regression (alg3)
#### 4) Decision Tree Regression- with Selected features: ['Item_MRP', 'Outlet_Type', 'Outlet', 'Outlet_Years'] (alg4)
