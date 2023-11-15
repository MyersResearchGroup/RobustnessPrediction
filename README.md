# RobustnessPrediction
This repository contains the models and results presented in the paper: Evaluating the Contribution of Model Complexity in Predicting Robustness in Synthetic Genetic Circuits. 

## Reproducibility 

To reproduce the results, first go to https://github.com/MyersResearchGroup/iBioSim and download the current release of iBioSim. Next, open iBioSim and create a new project. If warning appears you can close the message using the OK button. Once the project is created you can see the iBioSim GUI.

Pic 1

From there, navigate to File -> Import -> Archive. In the pop up window select one of the models provided in this repository (i.e. OG_ECC). Now, the GUI shows the content of the project on the left hand side. Selecting the topModel by double clicking opens a tab visualizing the model.

Pic2

To run a simulation, open a simulation environment by selecting one of the transitions or steady state failures by expanding its view by clicking the arrowhead next to it. Clicking the green simulation icon then opens the simulation view. Here, you can simply press the green play button at the top to run the simulation.

Pic3

After the simulation finished, select the TSD graph view. Double click on the canvas to open the edit graph pop op window. There, select Percent Termination, set a checkmark next to Glitch and press okay. Now, you can see probability of the failure over time. 

Pic 4




