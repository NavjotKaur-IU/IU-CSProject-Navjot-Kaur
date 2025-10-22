# IU-CSProject-Navjot-Kaur

# Predictive Train Delay and Disruption Analysis System (Deutsche Bahn)

# Problem Statement:
Passengers on Deutsche Bahn often face irregular train delays and disruptions because of variety of factors such as weather conditions,track maintenance,platform congestion ,vehicle change and peak hour traffic.Most of the information provided by the available systems is reactive and discriptive. It means that passengers are informed about the delays afterwords rather than before delays happen.This kind of reactive information or strategy effects planning of both passengers and train operators and that result in irritation,missing connection and poor resource management.DEcision makers find it difficult to take measures to prevent them because current tools are not providing precise information abbout why disruptions occur.

# Goal:
- **Predict train delays and disruptions** before they occur using historical and real-time data.  
- **Provide accurate projections** of delay times across various routes and time periods.  
- **Identify main causes** of delays such as bad weather, track maintenance, and traffic congestion.  
- **Use predictive data** to help train operators make better operational choices.  
- **Enhance passenger experience** by delivering reliable travel information and early alerts about delays.  
- **Offer a simple and clear display** for showing train status and prediction results.  
- **Develop a modular AI system** that allows continuous learning, updates, and scalability.  


# Tech Stack:
| Component            | Technology / Library                        | Description                                                                 |
|---------------------|--------------------------------------------|-----------------------------------------------------------------------------|
| **Frontend**         | React.js, Plotly.js                         | User interface for visualizing real-time predictions and analytics.        |
| **Backend API**      | FastAPI, Flask                              | REST APIs for serving predictions, explanations, and handling requests.    |
| **Database**         | PostgreSQL                                  | Store structured data, historical data, and prediction results.            |
| **AI Engine**        | Scikit-learn, XGBoost, SHAP                | Machine learning models and interpretability for predicting delays.        |
| **Data Ingestion**   | Python, Airflow, APIs                        | Collection, cleaning, and preprocessing of live and historical data.       |
| **Integration**      | REST APIs, WebSockets                        | Connecting frontend, backend, and data pipelines for real-time updates.    |
| **Data Sources**     | Deutsche Bahn Open Data API, OpenWeatherMap API, Calendar/Holiday API | Source data for train schedules, weather conditions, and holidays.        |


# Phase Status
1. Conception Phase - Done
2. Development Phase - under progress
