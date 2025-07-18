🚗 EV Adoption Forecasting
📖 Project Overview
Forecast future electric vehicle (EV) adoption by county in Washington State. This regression-based approach leverages historical monthly DOL registration data (2017–2024) to guide infrastructure planning, especially charging-station needs.

🧩 Problem Statement
Rapid EV growth demands proactive planning. This project builds a regression model to forecast EV adoption (BEVs & PHEVs) by county and time—empowering planners to anticipate demand and deploy charging infrastructure strategically.

🎯 Objectives
Predict the number of registered EVs (BEVs, PHEVs, total) per county per month/year.

Analyze growth trends and county-level adoption patterns.

Evaluate model performance and feature contributions.

Provide actionable insights—e.g., high-growth counties, predicted EV % share.

📂 Dataset
Source: Washington State DOL (monthly vehicle registrations by county, 2017–2024).

Columns:

Date (month-end)

County, State

Vehicle Primary Use (e.g., passenger, truck)

BEVs, PHEVs, EV_Total, NonEV_Total, Total_Vehicles, Percent_EV

Download link: Kaggle dataset

💡 Suggest adding data/, with raw/ and processed/ subfolders; add .gitignore for large files or keys.


📊 Visualization: Matplotlib, Seaborn, Folium/GeoPandas (optional)

📈 Evaluation: MAE, RMSE, R², time-series cross-validation

