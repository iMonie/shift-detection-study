![Python](https://img.shields.io/badge/Python-3.x-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-Data%20Streams-green)
![Status](https://img.shields.io/badge/Status-Preliminary%20Study-orange)

---

# Exploratory Analysis on Statistical Techniques for Detecting Distribution Shifts in Simulated Data Streams

A preliminary study exploring statistical approaches for identifying distribution changes in simulated streaming data environments.

---

## Overview

In many real-world applications, data distributions evolve over time, which can negatively impact the performance of machine learning models.

This project presents an **exploratory analysis** of statistical techniques for detecting such changes using a simulated data stream.

---

## Purpose of the Study

This work is designed as a **foundational investigation** into the problem of detecting distribution shifts.

It does not aim to provide a complete or production-ready solution, but rather demonstrates key ideas that can support more advanced research in adaptive machine learning systems.

---

## Methodology

The system applies:

- Sliding window analysis  
- Kolmogorov-Smirnov (KS) statistical test  

### Process:

1. Generate a simulated data stream  
2. Divide the stream into consecutive windows  
3. Compare distributions using KS test  
4. Detect shifts when statistical difference exceeds a threshold  

---

## Key Features

- ✅ Detects distribution-level changes (not just mean shifts)  
- 📉 Uses statistical hypothesis testing  
- 📈 Provides visualization of:
  - Data stream behavior  
  - Detected shift points  
  - Drift score (p-values)  
- 🔍 Includes simple filtering to reduce noisy detections  

---

## Experimental Setup

- Initial data: Normal distribution (mean = 0)  
- Shifted data: Modified distribution (mean = 3)  
- Window size: 50  
- Significance level: 0.01  

---

## Observations

- The method effectively identifies major distribution changes  
- Statistical testing provides a reliable signal for detecting shifts  
- Visualization enhances interpretability of drift behavior  

---

## ⚠️ Limitations

- Uses simulated data only  
- Does not support real-time streaming  
- No automated adaptation or retraining  

---

## Future Directions

Potential extensions include:

- Real-time streaming integration  
- Adaptive machine learning systems  
- Advanced drift detection methods (e.g., ADWIN)  
- Evaluation on real-world datasets  

---

## Tech Stack

- Python  
- NumPy  
- Matplotlib  
- SciPy  

---

## 
