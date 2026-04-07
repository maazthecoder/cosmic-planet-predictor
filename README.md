# 🌌 Cosmic Planet Predictor

> From cosmic signals to planetary.

A machine learning project that classifies exoplanets based on sensor-derived features such as atmospheric conditions, gravity, radiation, and orbital mechanics.

---

## 🚀 Overview

In a futuristic scenario, planetary classification labels were lost during interstellar data transmission. This project rebuilds those labels using machine learning on structured telemetry data.

The goal is to accurately predict the **planet type (0–9)** using numerical features collected from automated probes.

---

## 🧠 Problem Statement

Given a dataset of ~56,000 planetary observations with physical and environmental attributes, build a model that can classify each planet into one of 10 categories.

---

## 📊 Dataset Features

- Atmospheric Density  
- Surface Temperature  
- Gravity  
- Water Content  
- Mineral Abundance  
- Orbital Period  
- Proximity to Star  
- Magnetic Field Strength  
- Radiation Levels  
- Atmospheric Composition Index  
- Surface Pressure  
- Stellar Luminosity  
- Meteor Impact Rate  
- Moon Count  
- Probe ID  

---

## ⚙️ Approach

- Data Cleaning and Preprocessing  
- Handling Missing Values  
- Feature Transformation and Encoding  
- Train-Validation Split  
- Model Training using Gradient Boosting  
- Performance Evaluation using Accuracy  

---

## 🤖 Model Used

- HistGradientBoostingClassifier (primary model)  
- (Optional) XGBoost for performance comparison  

---

## 📈 Results

- Achieved strong accuracy on validation data  
- Efficient handling of tabular data with minimal preprocessing  
- Scalable pipeline for structured datasets  

---

## 🛠️ Tech Stack

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Google Colab  

---

## 📂 Project Structure
