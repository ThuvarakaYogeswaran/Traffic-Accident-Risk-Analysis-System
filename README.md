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

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/traffic_accident_analysis.git
cd traffic_accident_analysis

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Generate dataset
python generate_expanded_data.py

# Run the app
streamlit run app.py
