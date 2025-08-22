# Supply Chain Analytics Using Python

# Overview

This project demonstrates advanced analytics and machine learning techniques applied to supply chain management, focusing on demand forecasting and supply chain optimization. Leveraging a large-scale retail dataset and Python-based tools, the project builds predictive models and optimization frameworks to support smarter inventory, logistics, and customer service decisions.

**Repository Structure:**

Masters_Capstone_Supplychain/

/- Elbow Method for optimal k - Contains optimal k value plot

/- README.md - Documentation

/- Supply chain Analytics Python Code.ipynb - Full python code

/- Supply chain Analytics document - Contains full document pdf

# Problem Statement
In highly competitive markets, accurately predicting customer demand is critical to avoid overstocking, stockouts, and unnecessary logistics expenses. Supply chain management faces challenges such as demand volatility, supply risks, and lead times. Applying data-driven forecasting and optimization enables businesses to meet customer needs efficiently while minimizing costs.

# Features

- Data preprocessing and cleansing of extensive retail transaction data.
- Development of demand forecasting models using machine learning (MLP, Random Forest, Gradient Boosting).
- Supply chain optimization using linear programming (PuLP).
- Interactive model training and evaluation with Streamlit.
- Customer segmentation and anomaly detection for enhanced business intelligence.

# Key Insights

- Neural networks (MLP) provide accurate demand forecasts but require significant computational resources.
- Ensemble methods offer robust and stable predictions balancing accuracy and efficiency.
- Optimization models complement ML forecasts by enabling cost-efficient production and shipping decisions.
- Data quality and preprocessing significantly impact model performance and reliability.

# Usage Instructions

- Prepare and clean your supply chain transaction dataset.
- Run the interactive Streamlit app to select features, target variable, and model hyperparameters.
- Train and evaluate forecasting models in real time.
- Utilize optimization outputs to guide logistics and inventory decisions.

# Technologies Used

- Python 3.x

- Pandas, NumPy for data handling

- Scikit-learn for machine learning models

- PuLP for optimization modeling

Limitations and Future Work
Current models rely mostly on historical data and do not incorporate real-time external factors such as economic shifts or supply disruptions. Future enhancements could integrate dynamic market indicators, advanced NLP on textual product data, and real-time anomaly detection feeding back into predictive models.
