# 🚀 PhysX-TFT: Physics-Regularised Temporal Fusion Transformer for Spacecraft Telemetry

A physics-informed, uncertainty-aware deep learning framework for **anomaly detection and decision support in spacecraft telemetry systems**.

---

## 📌 Overview

Modern spacecraft generate high-dimensional telemetry data that must be continuously monitored to ensure mission safety. Traditional machine learning and deep learning approaches often lack:

- Physical consistency  
- Reliability (uncertainty awareness)  
- Interpretability for decision-making  

This project introduces **PhysX-TFT**, a novel framework that integrates:

- ✅ Temporal Fusion Transformer (TFT)  
- ✅ Physics-Informed Learning  
- ✅ Uncertainty Quantification (MC Dropout)  
- ✅ Decision Support System  



**Key Contributions**

- Physics-regularised loss function enforcing domain constraints  
- Uncertainty-aware anomaly detection using Monte Carlo Dropout  
- Variable Selection Network (VSN) for feature importance  
- Decision-support module for actionable insights  
- Real-time capable system (<100 ms inference)  



**Physics-Informed Loss**

The model integrates physical consistency through:

\[
L_{total} = L_{task} + \lambda L_{phys}
\]

\[
L_{phys} = |P - (V \times I)|
\]

- λ is constrained (λ ≥ 0)  
- Ensures physically valid predictions  
- Prevents unrealistic model outputs  

---

## 🏗️ Architecture Overview
