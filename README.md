# Wind Condition Classification

An index was developed to assess atmospheric conditions favorable or unfavorable to strong winds. This project was developed between August 2024 and December 2025, supported by a FAPESP TT-5 Fellowship.

## Business Problem

Wind farms need to forecast wind conditions to optimize operational planning and support decision-making.

## My Role

Climate Data Scientist

Key Contributions:
- **Developed automated methods** to detect 10 distinct weather systems influencing Brazilian wind patterns.
- **Validated detection algorithms** against surface analysis charts from the Brazilian Navy (*Marinha do Brasil*).
- **Compiled a 30-year historical database** by tracking these 10 distinct weather systems.
- **Identified homogeneous regions** based on regional wind patterns.
- **Engineered an end-to-end Machine Learning pipeline**, covering data preprocessing, feature selection, model training, and validation.
- **Evaluated model performance** using real-world observational data from INMET.
- **Developed an operational inference pipeline** to process incoming weather forecasts, apply a trained machine learning model, and automatically generate the wind index.

## Data 

* **Model Training & Weather Systems Tracking:** ERA5 reanalysis data (30-year historical dataset).
* **Operational Inference:** Climate Forecast System (CFS) forecast data.
* **Performance Evaluation & Validation:**
  * INMET observational weather station data.
  * Synoptic surface analysis charts from the Brazilian Navy (*Marinha do Brasil*).

## Repository Disclaimer

This repository serves to document my professional experience and highlight my contributions to the project without disclosing proprietary solutions. To respect confidentiality, all implementation details, company-owned source code, credentials, internal infrastructure, and sensitive data have been strictly omitted.
