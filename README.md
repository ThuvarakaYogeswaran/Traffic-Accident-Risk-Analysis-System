# 🚦 Traffic Accident Risk Analysis System

A data-driven web application to analyze traffic accident patterns and predict risk levels across districts in Sri Lanka.

# Features

- **Interactive Dashboard** - View risk maps, statistics, and vehicle correlations
- **ML Predictions** - Predict risk scores using Random Forest & Gradient Boosting
- **Policy Simulator** - Test how changing vehicle counts affects accident risk  
- **Location Analysis** - Deep dive into any district's accident data
- **Urban-Rural Comparison** - Compare patterns between different area types

 # Tech Stack

- Python 3.8+
- Streamlit - Dashboard framework
- Scikit-learn - Machine learning
- Plotly - Interactive visualizations
- Pandas/NumPy - Data processing


# Project Structure


traffic_accident_analysis/
├── app.py                 # Main application
├── models.py              # ML models
├── data_loader.py         # Data loading
├── feature_engineering.py # Risk calculations
├── visualization.py       # Charts & maps
├── utils.py              # Helper functions
└── requirements.txt      # Dependencies

# How It Works

-** Risk Score Formula **-

Risk = (% Vulnerable Vehicles) / (% Heavy Vehicles)

Vulnerable: Motor cycles, Three wheelers, Cycles

Heavy: Lorries, Buses, Articulated vehicles

# ML Models

Classifier: Predicts Low/Medium/High risk (72-85% accuracy)

Regressor: Predicts continuous risk score (R² 0.35-0.55)

# Risk Categories

Low (<1.0): Heavy vehicle dominated

Medium (1.0-3.0): Balanced traffic

High (>3.0): Vulnerable user dominated


# Use Cases

Policy makers - Simulate policy impacts before implementation

Traffic engineers - Identify high-risk districts

Researchers - Analyze vehicle type correlations

# Requirements

streamlit>=1.28.0
pandas>=2.0.0
numpy>=1.24.0
plotly>=5.17.0
scikit-learn>=1.3.0

# Future Improvements

Add real-time weather data

Include road quality metrics

Mobile app version

Export reports as PDF
