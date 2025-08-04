
# Power System Fault Detection and Classification

This project focuses on building a machine learning model to detect and classify faults in a power system based on real-world parameters such as voltage, current, power load, temperature, weather, and equipment condition.

## Model Details

- **Tool Used**: IBM Watsonx.ai AutoAI
- **Model**: Random Forest Classifier
- **Pipeline**: P9
- **Best Accuracy Achieved**: ~40%
- **Deployment Status**: Deployed

## Key Observations

- Model shows limited accuracy (~40%) due to likely low feature relevance or data imbalance.
- Dataset may lack sufficient signal for accurate classification.
- Still, deployment and integration are functional, and the pipeline can be reused for future improvements.

## Improvements Required

- Adding more predictive features (e.g., historical faults, real-time sensors)
- Perform manual feature selection or dimensionality reduction
- Trying advanced models (XGBoost, ANN) outside AutoAI

## Author

- **Name**: Ananta sri M H
- **Tool**: IBM Watsonx.ai Studio
- **Date**: August 2025

