# ML4Maritime-A-Production-Ready-Pipeline-for-Vessel-Fuel-Prediction


##  Project Overview

FuelCast is a comprehensive data science project aimed at predicting a vessel's **total momentary fuel consumption** (`Consumer_Total_MomentaryFuel`). Using sensor data from the **CPS_Poseidon** vessel, this project goes beyond a simple machine learning script. It provides a full, production-ready pipeline for data understanding, cleaning, feature engineering, and selection.

The core value of this project is its **domain-driven approach**. Instead of applying generic data science methods, each step is grounded in maritime engineering and physics, leading to more robust and interpretable features (e.g., propulsion balance, weather severity indices).

##  Business Problem

Accurate fuel consumption prediction is critical for:
- **Cost Optimization:** Fuel is one of the largest operational expenses for shipping companies.
- **Emissions Reduction:** Better prediction enables route and speed optimization to lower the vessel's carbon footprint.
- **Predictive Maintenance:** Deviations from expected fuel consumption can signal underlying mechanical issues.

##  Dataset

The dataset, sourced from the Hugging Face Hub (`krohnedigital/FuelCast`), contains 105,422 sensor readings from the CPS_Poseidon vessel. It includes over 65 features, such as:
- **Engine Data:** Individual generator power, fuel rates, and rotation speeds.
- **Propulsion Metrics:** Shaft power and torque for port and starboard propellers.
- **Navigation Data:** Ship speed (over ground & through water), heading, and bearing.
- **Environmental Data:** Seafloor depth, wind speed/direction, wave height/period, ocean currents, and solar radiation.


