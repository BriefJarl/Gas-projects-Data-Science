Run instructions:
1) Open gas_forecast.ipynb in Jupyter (or upload to Colab).
2) Run all cells (Kernel → Restart & Run All).
3) Use estimate_price('YYYY-MM-DD') to get an estimate for any date.
Files included:
- gas_prices.csv : input monthly data
- gas_forecast.ipynb : notebook (analysis + model)
- timeseries_forecast.png : time-series plot
- seasonality_by_month.png : seasonality plot
Author: Bhumika
Notes: Model is linear+fourier seasonality. Use with caution for shocks.
