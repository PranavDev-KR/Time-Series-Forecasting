# Temperature Anomaly Forecasting

## Project Overview
This project focuses on analyzing and forecasting deviations in global land temperature anomalies from 1850 to 2023, relative to the average temperatures recorded between 1901 and 2000. The primary objective is to identify an effective ARIMA model to forecast future trends and contribute to climate change mitigation strategies.

## Author
Pranav Dev Kottimukkalur Ramasubramanian

## Project Description
The project employs Auto-Regressive Integrated Moving Average (ARIMA) models to analyze temperature anomalies, assessing patterns that can guide environmental policy and climate change discussions. Our approach includes:
- Loading and analyzing the temperature anomaly data.
- Visualizing time series data.
- Conducting stationarity tests (ADF, PP, and KPSS).
- Selecting and validating the appropriate ARIMA model.
- Forecasting temperature anomalies for the next decade.

## Data Source
The dataset is sourced from the National Centers for Environmental Information (NCEI) and includes monthly Global Land Temperature Anomalies in degrees Celsius. The data extends from 1850 to 2023 and can be found [here](https://www.ncei.noaa.gov/access/monitoring/climate-at-a-glance/global/time-series/globe/land/ytd/12/1850-2023?trend=true&trend_base=10&begtrendyear=1850&endtrendyear=2023).

## Tools and Technologies
- R
- RStudio
- Various R packages: `TSA`, `readr`, `stringr`, `dplyr`, `lubridate`, `ggplot2`, `tseries`, `fUnitRoots`, `lmtest`, `forecast`

## Key Findings
- **Model Selection**: The ARIMA(1,1,3) model was identified as the most suitable for this data, providing a good balance between complexity and predictive accuracy.
- **Forecasting**: The selected model was used to forecast temperature anomalies for the next ten years, indicating a likely increase in global land temperature anomalies.

## Conclusion
The study underscores the importance of using robust statistical methods to predict climate trends. By accurately forecasting temperature anomalies, we can better prepare for and mitigate the effects of climate change. The findings from this research are intended to support policymakers and researchers in their efforts to understand and combat global warming.

## References
- Course materials from RMIT University - Master of Analytics - MATH1318 Time Series Analysis
- `Climate at a Glance | Global Time Series | National Centers for Environmental Information (NCEI)`, viewed 19 May 2024, [Link to Data](https://www.ncei.noaa.gov/access/monitoring/climate-at-a-glance/global/time-series/globe/land/ytd/12/1850-2023?trend=true&trend_base=10&begtrendyear=1850&endtrendyear=2023).

