# my-progect
AI progect about covid-19 Data engineer &amp; modeling

🌟 Features
📈 Forecast & Trends: Prophet model forecasting and trend analysis

🌍 World Map: Interactive choropleth map of global COVID-19 cases

📊 Data Table: Detailed tabular view of forecasted data

💡 Insights: Key metrics and analytics with visual indicators

🤖 Model Comparison: Side-by-side comparison of Prophet vs Random Forest models

🎯 Interactive Controls: Country selection dropdown and tab navigation

🛠️ Technologies Used
Backend: Python 3.9+

Web Framework: Plotly Dash

Data Processing: Pandas, NumPy

Visualization: Plotly, Plotly Express

Machine Learning: Prophet, Scikit-learn

📁 Project Structure
covid-19-dashboard/
├── app.py                 # Main Dash application
├── model_utils.py         # Data processing and ML functions
├── requirements.txt       # Python dependencies
├── Dockerfile            # Container configuration
├── README.md             # This file
└── .gitignore           # Git ignore rules

🧠 Machine Learning Models
Prophet
Time series forecasting developed by Facebook

Handles seasonality and trends effectively

Used for 30-day COVID-19 case predictions

Random Forest
Ensemble learning method for regression

Multi-output forecasting capability

Comparative analysis with Prophet

📊 Data Source
Data is fetched from:
https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv

🙏 Acknowledgments
Johns Hopkins University for providing COVID-19 data

Plotly for the Dash framework

Facebook for the Prophet forecasting library

Scikit-learn team for machine learning tools
