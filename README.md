# Hospital-Resource-Optimization-Using-Time-Series-Analysis
Developed and evaluated ARIMA and LSTM models to forecast hospital bed occupancy, enabling optimized resource allocation. Delivered actionable insights with data-driven visualizations to support NHS decision-making.


## Project Overview
This project focuses on forecasting hospital bed occupancy to optimize resource allocation. Using ARIMA and LSTM models, the study evaluates predictive analytics for efficient hospital management.

## Objectives
- Analyze patient flow data to predict daily bed occupancy.
- Compare ARIMA and LSTM models for forecasting accuracy.
- Provide actionable insights for resource planning.

## Dataset
- **Demo Data:** A synthetic dataset representing patient admissions and discharges.
- **Features:** Admission and discharge timestamps, daily occupancy trends.

## Methodology
1. **Data Preprocessing:** Calculated daily occupancy and smoothed trends.
2. **Modeling:** Developed ARIMA and LSTM models for time series forecasting.
3. **Evaluation:** Compared models using metrics:
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)
   - Mean Absolute Percentage Error (MAPE).

## Results
| Model            | MAE   | RMSE  | MAPE (%) |
|------------------|-------|-------|----------|
| ARIMA(2, 2, 0)  | 19.69 | 24.07 | 8.72     |
| LSTM             | 20.35 | 25.64 | 12.80    |

**Key Observation:** ARIMA outperformed LSTM in all metrics for this dataset.

## Visualizations
- Plots comparing actual vs predicted values for both ARIMA and LSTM models.
- Overlays highlighting trends and differences.

## Summary and Future Prospects
### Summary:
- ARIMA is better suited for linear patterns and seasonal trends in the demo data.
- Predictive models support decision-making in resource allocation.

### Future Prospects:
- Use real-world datasets for validation and implementation.
- Explore hybrid models combining ARIMA and LSTM for enhanced accuracy.
- Extend predictions to other resource metrics like staffing and equipment.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/aravindarav19/Hospital-Resource-Optimization-Using-Time-Series-Analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook NHS.ipynb
   ```

## Contact
For inquiries or collaborations, please contact: Aravaravind1999@gmail.com
