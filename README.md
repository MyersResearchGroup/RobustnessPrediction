# Robustness Prediction Repository

Welcome to the Robustness Prediction repository! This collection houses the models and outcomes featured in the paper titled "Evaluating the Contribution of Model Complexity in Predicting Robustness in Synthetic Genetic Circuits."  (ADD CITATION LATER)

## Reproducibility Guide

To reproduce the results, follow these steps:

1. **Download iBioSim:**
   - Visit [iBioSim's GitHub](https://github.com/MyersResearchGroup/iBioSim) and download the latest release.
   - Install and open iBioSim and create a new project.

   ![iBioSim GUI](https://github.com/MyersResearchGroup/RobustnessPrediction/blob/main/Media/Pic1.png?raw=true)

2. **Import Model:**
   - If a warning appears, dismiss it with the OK button.
   - Navigate to File -> Import -> Archive within iBioSim.
   - Choose a model from this repository (e.g., OG_ECC).

   ![Import Model](https://github.com/MyersResearchGroup/RobustnessPrediction/blob/main/Media/Pic2.png?raw=true)

3. **Run Simulation:**
   - In the project view, double-click on the topModel to visualize it.
   - Open a simulation environment by selecting a transition or steady state failure.
   - Click the green simulation icon to open the simulation view.
   - Press the green play button to run the simulation.

   ![Run Simulation](https://github.com/MyersResearchGroup/RobustnessPrediction/blob/main/Media/Pic3.png?raw=true)

4. **Analyze Results:**
   - After the simulation, select the TSD graph view.
   - Double-click on the canvas to open the edit graph pop-up window.
   - Choose "Percent Termination," checkmark "Glitch," and press okay.
   - View the probability of failure over time.

   ![Analyze Results](https://github.com/MyersResearchGroup/RobustnessPrediction/blob/main/Media/Pic4.png?raw=true)

Feel free to explore the robustness predictions of all models provided using this repository. If you have any questions or encounter issues, refer to the iBioSim documentation for additional support. Happy simulating!
