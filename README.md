# Superstore-Delivery-Performance-Analysis 
     This project explores delivery performance using Superstore-style data. It calculates delivery times (days between order and ship dates), creates useful visuals, and includes a basic model to predict delivery delays.

## Project Structure :
     Delivery Analysis.ipynb : 
        The main Jupyter notebook for cleaning data, analyzing delivery performance, and building a simple predictive model.
     Images : Contains all generated charts:
  - Distribution of delivery days
  - Delivery days by shipping mode
  - Average delivery days by region
  - Monthly trend per shipping mode
  - Late delivery rates by mode and region

## Key Insights :
   Most deliveries take 2–5 days.
   Same Day shipping is the fastest; Standard Class is the slowest and has ~30% of deliveries delayed more than 5 days.
   Central region has the highest late rate (~19%); East performs best.
   Delivery times remain fairly stable over time — no significant improvement or decline month-to-month.

## Next Steps :
   Highlight late deliveries by category or region.
   Improve the model using feature engineering, cross-validation, and explainability tools.
   Make interactive visuals or dashboards (e.g., with Plotly or Streamlit).
