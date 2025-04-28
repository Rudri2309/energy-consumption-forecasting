Energy Consumption Forecasting 📈⚡
This project focuses on forecasting the average daily energy consumption using SARIMAX models, weather data, and public holidays, visualized through a dynamic Tableau Dashboard.

📚 Project Structure
Data Cleaning & Merging — Combined raw energy readings, weather, and holiday data.

Feature Engineering — Added moving averages, month, weekday, lag features.

Modeling — Built a SARIMAX model with (1,1,0)x(0,1,0,7) configuration, achieving a validation RMSE of 0.4951.

Visualization — Created interactive Tableau dashboards comparing historic, weather, and future forecast data.

📊 Dashboard Highlights
Historic Energy Consumption Trends

Comparative Analysis (Temperature, Humidity, Energy)

Temperature vs Energy Consumption (with humidity coloring)

Predicted Future Energy Consumption

🛠️ Tools Used
Python (Pandas, Statsmodels, Scikit-learn)

Tableau Public

SARIMAX Time Series Modeling

📁 How to Run
Clone the repo:

bash
Copy
Edit
git clone https://github.com/yourusername/energy-consumption-forecasting.git
Install dependencies:

nginx
Copy
Edit
pip install -r requirements.txt
Open notebooks/ to explore code.

Open tableau_dashboards/energy_forecasting_dashboard.twbx in Tableau Public to see the dashboard.

🔥 Future Improvements
Train LSTM or Prophet models for deeper forecasts.

Live weather API integration for real-time forecasts.

Improve feature engineering based on holiday effects.

