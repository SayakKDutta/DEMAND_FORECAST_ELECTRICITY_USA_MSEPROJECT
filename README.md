# Power Generation (USA) Time Series Analysis and Hypothesis Testing

## Project Summary
This project focuses on analyzing unit generation data for the USA from January 1, 1990, to June 1, 2023. The analysis includes time series modeling using ARIMA and SARIMA models for prediction, as well as hypothesis testing using the t-test to compare two groups.

## Dataset Overview
- The dataset contains information on unit generation over time, spanning from January 1, 1990, to June 1, 2023.
- Data analysis involves time series decomposition, visualization, modeling using ARIMA and SARIMA, and hypothesis testing.

## Data Analysis
- Time series decomposition:
  - Decomposition of the time series into trend, seasonal, and residual components using additive and multiplicative models.
  - Visualization of the decomposed components to understand the underlying patterns.

- Auto ARIMA modeling:
  - Automatic selection of ARIMA orders using the pmdarima library.
  - Model fitting and prediction for a specified date range.
  - Visualization of predicted values against actual data for model evaluation.

- SARIMAX modeling:
  - Manual selection of SARIMA orders based on analysis.
  - Model fitting and prediction for a specified date range.
  - Comparison of predicted values with actual data for evaluation.

## Hypothesis Testing
- Null Hypothesis (H0): There is no significant difference in the mean 'Unit Generated' between two groups.
- Alternative Hypothesis (H1): There is a significant difference in the mean 'Unit Generated' between the groups.
- Conducting a t-test to compare the means of the two groups and infer whether there is a statistically significant difference.

## Conclusion
- Time series analysis using ARIMA and SARIMA models provides insights into unit generation patterns and enables forecasting.
- Hypothesis testing helps in understanding differences in unit generation between different groups or periods.
- Further analysis and refinement of models may be necessary to improve prediction accuracy and test hypotheses more effectively.

## Repository Information
- This repository contains code and analysis scripts for conducting time series analysis and hypothesis testing on unit generation data.
- Contributions and feedback are welcome through pull requests and issue submissions.

Acknowledgments
The dataset used in this analysis is sourced from [https://www.eia.gov/electricity/data/state/] and is publicly available.
Contact

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

## Contact
For any questions or feedback, please contact [sayak.kr.dutta1@gmail.com](mailto:sayak.kr.dutta1@gmail.com).
