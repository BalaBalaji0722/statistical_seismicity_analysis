# Statistical Analysis of Earthquake Magnitude and Depth Distribution
Statistical analysis of earthquake magnitude-frequency distribution, depth classification, and temporal seismicity patterns over the Indian tectonic plate using Python-based scientific computing workflows.

## Overview

This project presents a statistical seismology workflow for analyzing earthquake catalog data associated with the Indian tectonic plate region.

The notebook includes:

- Earthquake magnitude-frequency analysis
- Earthquake depth distribution analysis
- Temporal earthquake catalogue filtering
- High-magnitude earthquake extraction
- Statistical seismicity characterization
- Data preprocessing for seismic analysis

The workflow is designed for:

- Seismic hazard assessment
- Seismotectonic investigations
- Statistical seismicity analysis
- Earthquake forecasting studies
- Machine learning preprocessing pipelines

---

# Project Workflow

## Step 1 — Load Earthquake Catalogue

The earthquake catalogue is imported using Pandas for statistical analysis and preprocessing.

The dataset includes:

- Magnitude
- Depth
- Longitude
- Latitude
- Decimal Year
- Event Information

---

## Step 2 — Data Preprocessing

The workflow performs:

- Missing value handling
- Column standardization
- Magnitude column renaming
- Dataset cleaning

This preprocessing stage ensures compatibility for subsequent statistical analysis.

---

# Magnitude Distribution Analysis

Earthquake events are classified into different magnitude ranges to understand regional seismicity behavior.

The notebook computes:

- Frequency of low-magnitude earthquakes
- Moderate earthquake occurrence
- Major earthquake occurrence
- Magnitude-frequency distribution

### Magnitude Classes

| Magnitude Range | Description |
|---|---|
| 1 ≤ Mw < 2 | Minor |
| 2 ≤ Mw < 3 | Very Light |
| 3 ≤ Mw < 4 | Light |
| 4 ≤ Mw < 5 | Moderate |
| 5 ≤ Mw < 6 | Strong |
| 6 ≤ Mw < 7 | Major |
| 7 ≤ Mw < 8 | Great |
| Mw ≥ 8 | Mega Earthquakes |

---

# Earthquake Magnitude Distribution

<img width="1028" height="578" alt="download" src="https://github.com/user-attachments/assets/e857c19a-1eb9-4032-8e6e-cbe54449d7a1" />

*Statistical distribution of earthquake magnitudes within the study region.*

---

# Depth Distribution Analysis

Earthquakes are classified based on focal depth into:

- Shallow-focus earthquakes
- Intermediate-focus earthquakes
- Deep-focus earthquakes

### Depth Classes

| Depth Range | Classification |
|---|---|
| D < 70 km | Shallow |
| 70 ≤ D < 300 km | Intermediate |
| D ≥ 300 km | Deep |

---

# Earthquake Depth Distribution

<img width="873" height="477" alt="download (1)" src="https://github.com/user-attachments/assets/61672bd5-e2a8-4f78-bc65-f8e668d999ae" />

*Depth-wise statistical distribution of earthquake events.*

---

# Temporal Earthquake Catalogue Filtering

The workflow filters earthquake events occurring after the year 1960 to create a declustered and temporally consistent earthquake catalogue for advanced analysis.

This filtered catalogue can be used for:

- Seismic hazard studies
- Earthquake forecasting
- Seismic energy analysis
- Machine learning applications

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

# Applications

This workflow can be applied in:

- Statistical seismology
- Seismic hazard analysis
- Earthquake recurrence studies
- Seismotectonic investigations
- Spatial-temporal seismicity analysis
- Machine learning preprocessing
- Regional seismicity characterization

---

# Research Publications Using Similar Methodology

1. Yarramsetty, B. B., & Baladhandapani, K. (2026). *Machine Learning Models for Seismic Energy Forecasting and Spatial Correlation Analysis for the Himalayan and Indo-Burmese Regions*. Natural Hazards Review, 27(3). https://doi.org/10.1061/NHREFO.NHENG-2647

2. Yarramsetty, B. B., & Baladhandapani, K. (2026). *Data-driven prediction of global annual seismic energy using machine learning models*. Journal of Earth System Science, 135(2), 60. https://doi.org/10.1007/s12040-026-02788-2

3. Bala Balaji, Y., Hema Sundara, R. V., & Kavitha, B. (2025). *Spatial Variation of Seismic Energy Release of Himachal Pradesh*. Disaster Advances, 3(19), 15. https://doi.org/10.25303/193da15023

4. Yarramsetty, B. B., & Kavitha, B. (2025). *Statistical Study on Seismicity of the Indian Tectonic Plate Interactions*. Disaster Advances, 10(18), 12. https://doi.org/10.25303/1810da012021

---

# References

1. Hanks, T. C., & Kanamori, H. (1979). *A moment magnitude scale*. Journal of Geophysical Research, 84(B5), 2348–2350.

2. Choy, G. L., & Boatwright, J. (1995). *Global patterns of radiated seismic energy and apparent stress*. Journal of Geophysical Research, 100(B9), 18205–18228.

---

# Future Improvements

Potential future extensions include:

- Gutenberg-Richter parameter estimation
- Seismic energy integration
- Earthquake clustering analysis
- Machine learning-based seismic forecasting
- GIS-based seismicity mapping
- Real-time earthquake statistics dashboard

---

# Conclusion

This notebook successfully demonstrates:

- Earthquake magnitude-frequency analysis
- Depth classification of seismic events
- Temporal earthquake catalogue filtering
- High-magnitude earthquake extraction
- Statistical seismicity characterization

The developed workflow provides a strong foundation for advanced seismic hazard assessment and AI-driven seismicity analysis.

---

# Author

**Bala Balaji Yarramsetty**  
Department of Civil Engineering  
National Institute of Technology Warangal  
India
