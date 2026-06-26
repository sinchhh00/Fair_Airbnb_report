# 🏠 Fair Airbnb Pricing Prediction
## Detecting & Mitigating Neighbourhood Income Bias in Berlin

![Python](https://img.shields.io/badge/Python-3.10-blue)
![XGBoost](https://img.shields.io/badge/Model-XGBoost-green)
![Fairness](https://img.shields.io/badge/Fairness-Isotonic%20Calibration-orange)
![Module](https://img.shields.io/badge/Module-M515A%20Ethical%20AI-purple)

## 📋 Project Overview

This project investigates **neighbourhood income bias** in an AI-powered Airbnb pricing 
prediction system for Berlin. Using the Inside Airbnb Berlin dataset, an XGBoost 
classifier is trained to predict whether a listing is **High-Priced** (above median €104) 
or **Low-Priced**. The project detects three types of discrimination against listings in 
low-income Berlin districts and applies **Post-Processing Isotonic Regression Calibration** 
to mitigate the bias.

> **Module:** M515A — Ethical Issues for AI  
> **University:** Gisma University of Applied Sciences  
> **Dataset:** [Inside Airbnb — Berlin](http://insideairbnb.com/get-the-data/)  
> **Sensitive Attribute:** Neighbourhood Income Group (High-Income vs Low-Income)  
