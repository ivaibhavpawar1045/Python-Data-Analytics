# Day 27 — Advanced Pandas II

## Topics Covered

          - apply()
          - map()
          - replace()
          - where()
          - query()
          - Vectorization
          - np.where()

## 1. apply()

          Used a custom function to classify orders based on profit.


## 2. map()

          Mapped delivery risk values into business-friendly labels.

## 3. replace()

          Standardized customer segment labels:

          - Consumer → B2C
          - Corporate → B2B

## 4. where()

          Created a column that preserves positive profit values and replaces losses with 0.

## 5. query()

          Filtered high-value profitable orders using:

          - Sales > 1000
          - Order Profit Per Order > 100

## 6. Vectorization

Compared `apply()` with direct vectorized arithmetic for a 10% discount.



## Industry Application

          - These techniques are useful for:

          - Business rule implementation
          - Data cleaning
          - Feature engineering
          - Customer segmentation
          - Transaction classification
          - KPI preparation
          - Efficient DataFrame transformations