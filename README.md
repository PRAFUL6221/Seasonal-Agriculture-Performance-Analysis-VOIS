# Seasonal Agriculture Performance Analysis

## Overview
This repository contains a comprehensive Exploratory Data Analysis (EDA) and performance evaluation of agricultural practices across different seasons (**Kharif**, **Rabi**, and **Zaid**). The analysis focuses on understanding variations in crop yield, financial profitability, resource efficiency (water, fertilizers, pesticides), and pest/disease risk dynamics.

This project was developed as part of the **VOIS AICTE Major Project (Batch 1, 2026-2027)** under the **Data Visualization** microcredential track.

---

## Key Features & Insights
* **Seasonal Performance Breakdown**: Evaluates yield and revenue across Kharif (highest profit/yield due to monsoons), Rabi (steady production), and Zaid (high irrigation costs leading to margin squeezes).
* **Irrigation Efficiency Metrics**: Compares Drip, Rainfed, Sprinkler, and Flood irrigation methods in terms of tonnes produced per 1,000 m³ of water.
* **Environmental & Soil Health Analysis**: Analyzes soil pH, NPK (Nitrogen, Phosphorus, Potassium) levels, temperature, and humidity impact on crop output.
* **Risk Modeling Context**: Maps disease and pest risk percentages across varying humidity and seasonal conditions.

---

## Repository File Structure

```text
├── Seasonal_Agriculture_Performance_Analysis.ipynb  # Main Jupyter Notebook with EDA, statistical models & visual charts
├── seasonal_agriculture_performance_dataset.csv     # Dataset containing 4,000 farm records & 28 analytical features
├── Seasonal_Agriculture_Performance_Analysis_Submission.pptx  # 11-slide PowerPoint presentation deck
├── requirements.txt                                 # Python dependencies required to run the project
└── README.md                                        # Project documentation and guide
```

---

## Dataset Schema

The dataset includes **4,000 farm observations** with the following key features:

| Column Name | Type | Description |
| :--- | :--- | :--- |
| `Farm_ID` | String | Unique identification code for each farm |
| `State` / `District` | Categorical | Geographical location of the farm |
| `Crop` | Categorical | Crop type (Wheat, Rice, Maize, Sugarcane, Pulses, Cotton, Groundnut, Chilli) |
| `Season` | Categorical | Kharif, Rabi, or Zaid |
| `Farm_Area_Hectares` | Numeric | Total cultivated area |
| `Rainfall_mm` | Numeric | Seasonal precipitation received (mm) |
| `Avg_Temperature_C` | Numeric | Average seasonal temperature (°C) |
| `Soil_pH` | Numeric | Soil acidity/alkalinity measure |
| `Irrigation_Method` | Categorical | Drip, Flood, Rainfed, or Sprinkler |
| `Yield_Tonnes_Ha` | Numeric | Yield achieved in tonnes per hectare |
| `Profit_INR` | Numeric | Net financial profit or loss (Revenue minus Total Cost) |
| `Water_Efficiency_t_per_1000m3` | Numeric | Water utilization efficiency ratio |
| `Disease_Pest_Risk_pct` | Numeric | Measured pest/disease incidence risk (%) |

---

## Setup & Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/PRAFUL6221/Seasonal-Agriculture-Performance-Analysis.git
   cd Seasonal-Agriculture-Performance-Analysis
   ```

2. **Create a Virtual Environment (Optional but Recommended)**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Notebook**:
   ```bash
   jupyter notebook Seasonal_Agriculture_Performance_Analysis.ipynb
   ```

---

## Requirements

The project requires Python 3.10+ and the following libraries:
* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `jupyter`
* `python-pptx`

---

## Author & Project Info
* **Author**: Praful Patil [cite: 2]
* **Institution**: SSBT's College of Engineering and Technology, Jalgaon [cite: 2]
* **AICTE Student ID**: `STU66bf8a12bc2071723812370` [cite: 2]
* **Program**: VOIS AICTE Major Project - Data Visualization Track [cite: 1, 2]
