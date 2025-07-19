# NASA CMAPSS Predictive Maintenance 🚀

## Project Overview

This project implements **Predictive Maintenance using the NASA CMAPSS FD001 dataset** to predict the **Remaining Useful Life (RUL)** of jet engines using **sensor data and Random Forest regression**.

It demonstrates a **data-driven approach to mechanical reliability**, combining **mechanical engineering knowledge and machine learning** for practical predictive maintenance applications.

---

## Dataset

- **NASA CMAPSS FD001 Dataset**: Simulated jet engine degradation under various operational conditions with 21 sensors and operational settings.
- Each row = One engine at one cycle with sensor readings.
- Goal: Predict **RUL (Remaining Useful Life)** for engines before failure.

Download the dataset:  
- [NASA CMAPSS Data](https://data.nasa.gov/d/ff5v-kuh6)
- Use the file: `train_FD001.txt`.

---

## Approach

✅ Data Cleaning and Preprocessing  
✅ Computation of RUL for each cycle as the regression target  
✅ Feature selection using sensor measurements  
✅ Standardization for model stability  
✅ Training a **Random Forest Regressor**  
✅ Evaluation using RMSE and R² metrics  
✅ Visualization of predictions vs. actual RUL

---

## Results

- **RMSE:** ~41 cycles  
- **R² Score:** 0.62

These results are consistent with a **clean baseline using Random Forest** on raw CMAPSS data.

---

## Sample Visualizations

![Predicted vs Actual RUL](https://user-images.githubusercontent.com/yourgithubid/sample-plot.png)

---

## Requirements

- Python 3.x
- pandas, numpy, matplotlib, seaborn
- scikit-learn

Install using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
