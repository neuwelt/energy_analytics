# Energy_Analytics

### Description
```
Your team has been tasked with forecasting energy production and usage in a smart building equipped with a rooftop PV system, electric vehicle charging infrastructure, and a battery storage system.
The goal is to analyze time series data and compare different forecasting models to  determine which data granularity (minute-based or quarter-hour-based) is better suited for forecasting energy metrics.
```

### Dataset
```
• Time series with measurements taken every 60 seconds, containing 6,737,452 records from January 10, 2023, to April 1, 2023.
• Time series with measurements taken every 15 minutes, containing 531,547 records from January 1, 2023, to April 1, 2023.
• Description of the components in the energy management system, containing 77 records.
```

### Challenges
```
• Data Preparation: Handling the large volume of time series data and dealing with missing values and irregularities.
• Identifying suitable methods for time series analysis.
```

### Tasks
```
• Describe and clean the dataset.
• Choose and train a time series forecasting model.
• Compare model performance using minute-based and quarter-hour-based data.
• Present the findings and steps taken to achieve the goals.
```

### Local Setup
```
1. Clone github repo
    Git clone https://github.com/neuwelt/energy_analytics.git

2. Install ARIMA
    pip install statsmodels

3.  Download csv & pdf files - [Moodel Link](https://moodle.hs-augsburg.de/mod/resource/view.php?id=382079)
    1. Extract files to the root directory
    2. Run section by section of the ipynb file, each section generates file required in the next
```