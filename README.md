# 🏡 Energy Efficiency Dataset

This dataset is designed to support the analysis and modeling of energy efficiency in residential buildings. It contains various attributes of building designs and the resulting energy performance metrics. The dataset is suitable for regression modeling, energy analysis, and machine learning applications in sustainability and smart building design.

## 📁 Dataset Overview

Each row represents a unique simulated building configuration, and the columns contain both input variables (features) and output variables (targets) related to energy efficiency.

### 🔢 Features (Inputs):

- **Relative Compactness**: Ratio of the building's envelope surface to its volume.
- **Surface Area**: Total surface area of the building (m²).
- **Wall Area**: Total wall area (m²).
- **Roof Area**: Total roof area (m²).
- **Overall Height**: Height of the building (m).
- **Orientation**: Categorical variable representing the orientation (2–5).
- **Glazing Area**: Percentage of glazing area (0, 0.1, 0.25, 0.4).
- **Glazing Area Distribution**: Distribution type of glazing (0–5).

### 🎯 Targets (Outputs):

- **Heating Load (Y1)**: Heating energy demand (kWh/m²).
- **Cooling Load (Y2)**: Cooling energy demand (kWh/m²).

## 🧪 Use Cases

- Predict heating and cooling loads using regression models.
- Perform feature importance analysis to understand key factors.
- Train and evaluate machine learning models for sustainable architecture.
- Optimize building parameters for energy efficiency.

## 🧰 Example Usage

```python
import pandas as pd

# Load the dataset
df = pd.read_csv('Energy_Efficiency (1).csv')

# Preview the data
print(df.head())
```

## 📌 Source

This dataset is commonly found in the UCI Machine Learning Repository:  
https://archive.ics.uci.edu/ml/datasets/energy+efficiency

## 🛠️ Recommended Tools

- Python (Pandas, Scikit-learn, Matplotlib)
- Power BI / Tableau (for visualization)
- Jupyter Notebook
- Excel (for basic exploration)

## 📄 License

Free to use for academic and non-commercial purposes. For commercial use, please verify source licensing.
