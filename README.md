# Master Thesis: Using Conformal Prediction for Uncertainty Estimation in Electricity Load Demand

📘 **Author**: Gabriel Pons Fontoira  
🎓 **Program**: Master Degree in Statistics for Data Science (2024–2025)  
🏫 **University**: Universidad Carlos III de Madrid  

---

## 📖 Thesis Summary

This repository contains the code and supporting material for my Master’s Thesis,  
**“Using Conformal Prediction for Uncertainty Estimation in Electricity Load Demand”**.

The thesis explores **probabilistic load forecasting** using data from the Global Energy Forecasting Competition 2014 (GEFCom2014).
The focus is on building **prediction intervals** that quantify uncertainty in electricity demand,  
comparing several state-of-the-art methods:

- **Quantile Regression Forests (QRF)**: a non-parametric tree-based ensemble for conditional quantiles.  
- **Conformalized Quantile Regression (CQR)**: combines quantile regression with conformal calibration  
  to ensure finite-sample validity.  
- **Ensemble Batch Prediction Intervals (EnbPI)**: bootstrap-based intervals adapted for time series.  
- **Adaptive EnbPI**: a variant of EnbPI that dynamically adjusts intervals over time.

---

## 📂 Repository Structure

- `Using Conformal Prediction for Uncertainty Estimation in Electricity Load Demand.pdf` → Final Master Thesis (report).  
- `Preprocessing.ipynb` → Data preprocessing and feature engineering (calendar variables, weather features).  
- `QRF.ipynb` → Implementation and experiments with Quantile Regression Forests.  
- `CQR.ipynb` → Implementation and experiments with Conformalized Quantile Regression, EnbPI and Adaptive EnbPI.  
---

## 📜 License

- Code is released under the **MIT License** (permissive, open-source).  
- The thesis text is released under a  
  **Creative Commons Attribution-NonCommercial (CC BY-NC 4.0) License**.  

---

## 📚 References

- Koenker, R., & Bassett, G. (1978). *Regression quantiles*. Econometrica.  
- Meinshausen, N. (2006). *Quantile regression forests*. JMLR.  
- Shafer, G., & Vovk, V. (2008). *A tutorial on conformal prediction*. JMLR.  
- Romano, Y., Patterson, E., & Candès, E. (2019). *Conformalized quantile regression*. NeurIPS.  
- Xu, C., & Xie, Y. (2021). *Conformal prediction interval for dynamic time-series*. ICML.  
- Hong, T., Pinson, P., Fan, S., Zareipour, H., Troccoli, A., & Hyndman, R. J. (2016). *Probabilistic energy forecasting*. IJF.  
- Gaillard, P., Goude, Y., & Nedellec, R. (2016). *GEFCom2014 probabilistic electric load forecasting*. IJF.  

---

## 🙌 Acknowledgements

This work was supervised by **Prof. Ricardo Aler Mur**,  
Master in Statistics for Data Science, Universidad Carlos III de Madrid.  

Special thanks to the developers of the libraries used:  
- [Zillow Quantile Forest](https://zillow.github.io/quantile-forest/)  
- [PUNCC](https://deel-ai.github.io/puncc/theory_overview.html)  
- [MAPIE](https://mapie.readthedocs.io/en/stable/)  

---

