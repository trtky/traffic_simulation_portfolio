# 🚗 ML-Based Speed Prediction in SUMO  
Predicting and controlling vehicle speed in SUMO using a Machine Learning model

This project combines **SUMO** (Simulation of Urban Mobility) with **Machine Learning** to predict the speed of a vehicle based on leader–follower dynamics.  

1. automatically launches multiple SUMO simulations  
2. collects driving data (speed, distance and leader speed)  
3. trains an ML model and saves it  
4. evaluates the model (scatter plot + MAE)  

## 🎯 Project Goal

The goal is to develop a model that predicts the **next speed** of a vehicle.  
To achieve this, multiple SUMO runs are executed to generate a robust dataset.

The model learns from:

- current speed  
- distance to the leader  
- leader speed  

## Programs used 

- **SUMO**  
- **Python**  

# Python Libraries used: 
    - **scikit-learn**  
    - **NumPy**
    - **Pandas**  
    - **Matplotlib**
    - **traci**
    