# Prabhsimrat Singh(102317135)-Data-Generation-using-Modelling-and-Simulation-for-Machine-Learning
 Data Generation using Modelling and Simulation for Machine Learning
 
## 1. Physics Simulation

I used Cantera to simulate methane combustion in a constant-pressure reactor.

### Inputs (Randomly Sampled)
- Initial Temperature (900–1500 K)
- Pressure (1–10 atm)
- CH₄ fraction
- O₂ fraction
- N₂ fraction
- Residence time

Generated 1000 simulations which created a dataset of 1000 samples for ML training.

---

## 2. Machine Learning Models

Trained and compared 6 regression models:
- Linear Regression
- Ridge
- Decision Tree
- Random Forest
- SVR
- KNN

---

## 3. Evaluation Metrics

Evaluated models using:
- MSE – Mean Squared Error (lower is better)
- RMSE – Root Mean Squared Error
- R² Score – Variance explained (closer to 1 is better)

---

## Best Model: Random Forest

Combustion is highly nonlinear (temperature–reaction rate coupling), so ensemble models like Random Forest perform best.
