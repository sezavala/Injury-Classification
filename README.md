# 🚗 Car Accidents Injury Classification

This project explores whether injury severity in traffic crashes can be predicted based on environmental and crash-related conditions like weather, lighting, and vehicle damage. Using a publicly available dataset from the [Maryland Open Crash Reporting System]( https://data.montgomerycountymd.gov/Public-Safety/Crash-Reporting-Drivers-Data/4mse-ku6q), we build and evaluate machine learning models to classify injury outcomes.

## 📊 Project Goals

- **Predict Injury Severity**: Build ML models to classify injury severity in car crashes.
- **Identify Risk Factors**: Analyze how different conditions (e.g., weather, driver behavior) influence injury risk.
- **Potential Applications**:
  - Help inform safer driving practices.
  - Provide early injury likelihood estimates for concerned family members.
  - Explore data-driven approaches for crash risk assessment.

## 🛠️ Tech Stack

- **Language**: Python (Jupyter Notebook)
- **Libraries**: `pandas`, `matplotlib`, `seaborn`, `scikit-learn`
- **Data Source**: [Crash Reporting – Drivers Data](https://data.montgomerycountymd.gov/Public-Safety/Crash-Reporting-Drivers-Data/4mse-ku6q)

## 📁 Project Structure
├── Injury-Classification.ipynb # Main notebook

├── data/ # Optional directory for datasets

└── README.md # Project overview

## 📈 Key Features

- Extensive EDA and visualization of crash and injury data
- Feature cleaning and reduction (handling categorical imbalance and missing values)
- One-hot encoding and scaling
- Supervised learning models for multi-class injury prediction
- (Optional) Unsupervised learning exploration

## 🔒 Ethics & Considerations

While predictive models can support driver safety and awareness, they should not replace expert crash investigations or medical evaluations. Model outputs are probabilistic and should be used cautiously.

## 👥 Authors

- Dalia Cabrera  
- Ahmed Torki  
- Sergio Zavala
