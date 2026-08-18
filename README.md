# Wind Condition Classification

An index was developed to assess the likelihood of favorable or unfavorable conditions for strong winds in a region. This work has been conducted over the past 16 months (starting August 1st, 2024) under a FAPESP TT-5 Fellowship.

## Business Problem

Wind farms need to forecast wind conditions to optimize operational planning and support decision-making.

## My Role

Climate Data Scientist

Key Contributions:
- **Developed automated methods** to detect 10 weather systems influencing Brazilian wind conditions.
- **Validated detection algorithms** against surface analysis charts from the Brazilian Navy (*Marinha do Brasil*).
- **Compiled a 30-year historical database** by tracking these weather systems across regions.
- **Identified homogeneous regions** based on regional wind patterns.
- **Built an end-to-end Machine Learning pipeline**, covering data preprocessing, feature selection, model training, and validation.
- **Evaluated model performance** using real-world observational data from INMET.
- **Developed an operational inference pipeline** to process incoming weather forecasts, apply a trained machine learning model, and automatically generate the wind index.

## Data 

* **Model Training & Tracking weather systems:** ERA5 reanalysis data (30-year historical dataset).
* **Operational Inference:** Climate Forecast System (CFS) forecast data.
* **Performance Evaluation & Validation:**
  * INMET observational weather station data.
  * Synoptic surface analysis charts from the Brazilian Navy (*Marinha do Brasil*).

## Repository Disclaimer

This repository presents my professional experience from August 1st, 2024, to December 31st, 2025.

No proprietary source code, confidential data, credentials, internal
infrastructure, or company-owned assets are included.
