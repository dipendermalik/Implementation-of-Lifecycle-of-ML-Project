# Implementation of Lifecycle of ML Project

## Overview
This project demonstrates an end-to-end Machine Learning workflow using the **Algerian Forest Fires** dataset. It covers the full lifecycle of an ML project, including:

- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training
- Model Serialization
- Flask Web Application Deployment

The final application allows users to input relevant fire-weather-related variables and get a prediction from the trained machine learning model.

---

## Project Objective
The objective of this project is to build and deploy a machine learning model that can generate predictions based on meteorological and fire index features derived from the Algerian Forest Fires dataset.

This repository is useful for understanding how a machine learning project moves from:
- raw data,
- to data cleaning and analysis,
- to model building,
- to a deployable web application.

---

## Project Structure

```text
Implementation-of-Lifecycle-of-ML-Project/
│
├── Notebook/
│   ├── 2.0-EDA And FE Algerian Forest Fires.ipynb
│   ├── 3.0-Model Training.ipynb
│   ├── Algerian_forest_fires_cleaned_dataset.csv
│   └── Algerian_forest_fires_dataset_UPDATE.csv
│
├── models/
│   ├── ridge.pkl
│   └── scaler.pkl
│
├── templates/
│   ├── index.html
│   └── home.html
│
├── application.py
├── requirements.txt
├── README.md
└── LICENSE
