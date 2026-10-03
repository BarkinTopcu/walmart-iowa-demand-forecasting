# Walmart Iowa Demand Forecasting

A time-series forecasting project using **PyTorch** to predict weekly liquor procurement demand for Walmart stores in Iowa.

## Overview

This project explores historical purchasing patterns and aims to forecast future purchase quantities at the store and product level. The workflow will cover data preparation, exploratory analysis, feature engineering, model training, and evaluation.

**The dataset records purchases made by Walmart stores from Iowa’s liquor distribution system. It does not contain individual customers’ checkout transactions.** Forecasts therefore represent store procurement patterns rather than direct consumer demand.

## Objectives

- Explore purchasing trends across stores, products, and time.
- Build weekly time series from transaction records.
- Establish simple forecasting baselines.
- Develop and evaluate a PyTorch forecasting model.
- Compare predictions with actual purchases and investigate forecast errors.

## Planned Approach

1. **Data preparation:** Merge source files, validate records, and aggregate purchase quantities by week.
2. **Exploratory analysis:** Examine seasonality, purchasing frequency, and differences between stores and products.
3. **Baseline models:** Evaluate seasonal naive and moving-average forecasts.
4. **PyTorch modeling:** Start with an LSTM model using historical purchase sequences.
5. **Evaluation:** Use chronological training, validation, and test splits, with MAE and WAPE as evaluation metrics.

Preprocessing will be fitted on training data only, and model inputs will use information available at the forecast date.

## Technology Stack

- Python
- Pandas and NumPy
- PyTorch
- Scikit-learn
- Matplotlib and Seaborn

## Data Source

**Dataset:** [Iowa Liquor Sales, Wal-Mart](https://data.iowa.gov/catalog/dataset/1083)  
**Publisher:** Iowa Department of Revenue — Alcohol Operations Bureau  
**Data license:** [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/)

The download date, selected date range, and preprocessing changes will be documented alongside the prepared data.

## Project Status

🚧 **In development.** Model implementation, experiments, and evaluation results will be added as the project progresses.

## License

The project’s original source code is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

The source dataset is separately licensed under **CC BY 4.0** and is not covered by the code’s MIT License. Any redistributed data retains its source attribution and applicable license notices.

This is an independent project and is not affiliated with or endorsed by Walmart or the State of Iowa.
