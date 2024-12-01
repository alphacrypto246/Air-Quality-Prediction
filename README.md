# Air Pollution Prediction

This project focuses on predicting air pollution levels based on **Date** and **Time** inputs. The dataset used for this project is derived from the Air Quality UCI dataset, and it includes key air quality variables, environmental conditions, and temporal data.

## Dataset Variable Descriptions

### **1. Air Quality Variables**
- **`CO(GT)`**  
  - **Description**: Concentration of Carbon Monoxide (CO) in the air, measured in mg/m³.  
  - **Relevance**: Indicates air pollution caused by combustion processes, such as vehicles and industrial emissions.

- **`NMHC(GT)`**  
  - **Description**: Non-Methane Hydrocarbons concentration in micrograms per cubic meter.  
  - **Relevance**: Associated with industrial emissions and photochemical reactions in the atmosphere.

- **`C6H6(GT)`**  
  - **Description**: Benzene concentration in µg/m³.  
  - **Relevance**: Benzene is a toxic pollutant mainly emitted by vehicle exhaust and industrial processes.

- **`NOx(GT)`**  
  - **Description**: Concentration of Nitrogen Oxides (NOx) in µg/m³.  
  - **Relevance**: NOx is a precursor to smog and acid rain, primarily originating from vehicle and industrial emissions.

- **`NO2(GT)`**  
  - **Description**: Nitrogen Dioxide (NO2) concentration in µg/m³.  
  - **Relevance**: A harmful pollutant linked to respiratory problems, originating from fuel combustion.

---

### **2. Environmental Variables**
- **`T`**  
  - **Description**: Ambient temperature measured in degrees Celsius (°C).  
  - **Relevance**: Affects pollutant dispersion and chemical reactions in the atmosphere.

- **`RH`**  
  - **Description**: Relative Humidity as a percentage (%).  
  - **Relevance**: Indicates moisture in the air, influencing pollutant behavior and perception of air quality.

- **`AH`**  
  - **Description**: Absolute Humidity in g/m³.  
  - **Relevance**: Provides a measure of water vapor content in the air, which can affect sensor performance.

---

### **3. Time Variable**
- **`DateTime`**  
  - **Description**: Combined date and time of the observation (YYYY-MM-DD HH:MM:SS).  
  - **Relevance**: Used to track temporal patterns in air quality and environmental conditions.

---

## Variable Ranges for Air Quality Dataset

| **Variable**       | **Expected Range**      |
|---------------------|-------------------------|
| `CO(GT)`            | 0.1 - 30 ppm           |
| `NMHC(GT)`          | >= 0 mg/m³             |
| `C6H6(GT)`          | 0 - 50 µg/m³           |
| `NOx(GT)`           | 0 - 500 µg/m³          |
| `NO2(GT)`           | 0 - 400 µg/m³          |
| `T` (Temperature)   | -20°C to 50°C          |
| `RH` (Humidity)     | 0% - 100%              |
| `AH` (Absolute Humidity) | 0 - 1 kg/m³      |

---

## Project Overview

This repository contains:
- **Dataset**: Preprocessed data for training and testing the model.
- **Jupyter Notebooks**: Step-by-step analysis and model training processes.
- **Source Code**: Functions and modules for data preprocessing, feature engineering, and model deployment.
- **Results**: Visualizations and evaluation metrics of the predicted pollution levels.

## Technologies Used

The following technologies and tools were used in this project:

- **Python**: Programming language for data analysis, machine learning, and model deployment.
- **Pandas**: Library for data manipulation and analysis.
- **NumPy**: Library for numerical operations and working with arrays.
- **Matplotlib**: Library for data visualization.
- **Seaborn**: Visualization library for creating more advanced statistical graphics.
- **Scikit-learn**: Machine learning library for model building and evaluation.
- **Jupyter Notebook**: Interactive environment for exploring data and running code.
