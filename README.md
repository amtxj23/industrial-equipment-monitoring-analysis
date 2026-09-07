# Industrial Equipment Monitoring & Fault Analysis

> **Exploring industrial equipment behaviour and identifying patterns associated with equipment faults using Python and Pandas.**

## 📌 Overview

Industrial equipment generates large volumes of operational data that can be used to understand equipment behaviour, identify abnormal operating patterns, and support maintenance decision-making.

This project analyses a dataset containing operational measurements and equipment information for **Turbines, Compressors, and Pumps** across multiple locations.

The primary objective is to use **Python and Pandas** to clean, explore, transform and analyse the data, uncovering patterns that can help identify equipment and operating conditions associated with faults.

---

## 🎯 Business Problem

Unplanned equipment faults can affect operational continuity, maintenance planning and overall equipment reliability.

This analysis focuses on answering:

> **Which equipment and operating conditions are most associated with faulty equipment, and where should monitoring and maintenance attention be prioritised?**

The analysis investigates relationships between:

- Temperature
- Pressure
- Vibration
- Humidity
- Equipment type
- Location
- Fault status

---

## 📊 Dataset

| Attribute | Description |
|---|---|
| `temperature` | Recorded equipment temperature |
| `pressure` | Recorded equipment pressure |
| `vibration` | Equipment vibration measurement |
| `humidity` | Recorded environmental humidity |
| `equipment` | Equipment category |
| `location` | Equipment operating location |
| `faulty` | Binary indicator representing equipment fault status |

### Dataset Snapshot

- **Records:** 7,672
- **Features:** 7
- **Equipment Types:** Turbine, Compressor, Pump
- **Locations:** 5
- **Missing Values:** None
- **Target Indicator:** `faulty`

> **Note:** The dataset is treated as a simulated/educational industrial monitoring dataset and should not be interpreted as real plant data.

---

## 🛠️ Tools & Technologies

**Programming & Analysis**
- Python
- Pandas
- NumPy

**Data Visualization**
- Matplotlib
- Seaborn

**Development Environment**
- Jupyter Notebook
- Git & GitHub

---

## 🔍 Analysis Workflow

The project follows a structured data-analysis workflow:

```text
Raw Dataset
     ↓
Data Understanding
     ↓
Data Quality Assessment
     ↓
Data Cleaning
     ↓
Data Transformation
     ↓
Exploratory Data Analysis
     ↓
Equipment & Fault Analysis
     ↓
Pattern Identification
     ↓
Engineering Insights
     ↓
Maintenance Recommendations
