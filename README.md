# Store-item-demand-forecasting
This project focuses on predicting the demand for various items across multiple stores by analyzing historical sales data. The goal is to build a machine learning model capable of generating accurate forecasts for future sales based on store-item combinations.

### Project Overview:
- **Objective:** Predict future sales for each store-item combination.
- **Dataset:** Historical sales data for multiple items across different stores, split into:
  - **Training Dataset:** Contains complete data with:
    - **Date:** The date of the sales record (in datetime format).
    - **Store:** The ID of the store where the item was sold.
    - **Item:** The ID of the item that was sold.
    - **Sales:** The quantity sold on a specific date at a particular store for the given item.
  - **Test Dataset:** Mirrors the training data structure but does not include sales figures, which need to be predicted.

### Goal:
The goal is to forecast three months of item-level sales data for different store locations.
