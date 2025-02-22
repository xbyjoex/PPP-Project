# **PPP-Project** (Power-Plant-Predictions)

This repository contains documentation and code developed as part of my bachelor’s thesis.

The project is divided into two main layers:
1. **Data Analysis and Forecast Modeling**: The first layer focuses on exploratory data analysis (EDA), feature engineering, and the development and deployment of a time-series forecasting model for solar power plants using weather data.
2. **Data Streaming and Anomaly Detection**: The second layer involves building a pipeline to stream simulated data from these power plants using AWS services for anomaly detection and predictive maintenance.

The primary focus of the bachelor’s thesis is on MLOps, particularly on how to deploy and manage such tasks in a production environment. Additionally, a proof of concept (PoC) will be implemented to demonstrate the feasibility of the proposed approaches.

Questions:

1. Can we predict the power generation for next couple of days? - this allows for better grid management
2. Can we identify the need for panel cleaning/maintenance?
3. Can we identify faulty or suboptimally performing equipment?


---

1. Try: using [this](https://www.kaggle.com/datasets/anikannal/solar-power-generation-data/data) data -> incorrect data and no exact location
2. Try: using [this](https://data.openei.org/submissions/4568) data -> multiple smaller, private solar plants 
