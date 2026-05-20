# 🎮 GPU Performance & Pricing - Data Analysis Project

## 📊 Project Overview
This project performs an exploratory data analysis (EDA) and statistical study on Graphic Processing Units (GPUs) using Python. 

By looking at technical specs alongside market pricing, the project explores how hardware characteristics (like VRAM and Clock Speeds) influence pricing and power efficiency across different generations and manufacturers (NVIDIA, AMD, Intel).

---

## 📁 Dataset
The dataset used in this project:
* gpu_specs_prices.csv

It contains key hardware attributes including:
* Product Name / Model (e.g., RTX 4070, RX 7800 XT)
* Memory (VRAM) (in GB)
* Core & Boost Clock Speeds (in MHz)
* TDP (Thermal Design Power in Watts)
* Price (Launch Price / Market Price in USD)

---

## 🛠 Tools & Libraries Used
* Python 🐍
* Pandas & NumPy 📊 (Data cleaning, filtering, and matrix manipulation)
* Matplotlib & Seaborn 📈 (Data visualization and distribution plots)
* Scipy / Statsmodels 🧪 (Statistical testing and Z-score normalization)

---

## 📊 Key Statistical Analysis Performed
This project breaks down the data through several analytical steps:
1. Data Cleaning: Handling missing pricing or specification data, and formatting columns.
2. Correlation Analysis: Checking how strongly features like VRAM size or Clock Speed correlate with final pricing.
3. Distribution Analysis: Examining the distribution of TDP (power draw) across different performance tiers.
4. Anomalies & Outlier Detection: Using Z-scores to find "unusual" values—such as GPUs that offer incredibly high clock speeds for an unexpectedly low price point, or over-priced low-spec cards.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ahmed2710s/gpu_dataset/blob/main/GPUData.ipynb)
