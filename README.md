# AI-Powered Predictive Analytics for Urban Water Supply Management 💧🤖

## Overview  
This project implements a scalable, **AI-powered decision-support system** for urban water demand forecasting and tanker-based supply optimisation. Using **Random Forest models** on simulated + open datasets (population, weather, historical usage), it predicts **zone-wise water demand** and generates **actionable tanker allocation plans**. It primarily uses **synthetic datasets** generated in Python to simulate urban water demand.  
The project supports **UN Sustainable Development Goal 6: Clean Water & Sanitation** by promoting **data-driven, equitable, and efficient water management**.  

## Features  
- 📊 **Zone-wise demand prediction** using Random Forest Regressor  
- 🚚 **Tanker allocation optimisation** with Random Forest Classifier & rule-based constraints  
- 🌦️ **Integration of climate, population, and historical usage data**  
- 🧹 **Preprocessing & feature engineering** for realistic demand simulation  
- 📈 **Visual dashboards** using Matplotlib, Seaborn, Plotly  
- 🌍 **Student-friendly, replicable methodology**  

## Project Workflow  
1. **Data Collection & Integration** – Climate, population, and water consumption data (real + simulated)  
2. **Data Preprocessing & Feature Engineering** – Handling missing values, encoding, scaling, feature interactions  
3. **Model Development**  
   - Demand prediction: Random Forest Regressor  
   - Supply optimisation: Random Forest Classifier + tanker caps  
4. **Visualisation & Dashboarding** – Interactive Gradio UI and plots for real-time insights  

## Tools & Libraries
1. Python, Pandas, NumPy
2. Scikit-learn (Random Forest)
3. Matplotlib, Seaborn, Plotly
4. Gradio (interactive UI)

## Results & Evaluation
- R² Score: 0.9604
- MAE: 42.68 MLD
- RMSE: 57.80 MLD

