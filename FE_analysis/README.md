In this project we are working with Finite Element simulation results. 
- Simulation results are saved in nested folders that are named based on their input variables.
- After data cleaning we conduct an explanatory analysis to find the correlation and outliers.
- After deciding about the outliers for rerunning the simulations or excluding them, it is time to test different ML algorithms to see if they can find the relations between inputs for predicting outputs.
- After finding the most efficient ML algorithm, we make a grid of all the possible combinations of inputs.
- We feed the grid to a trained model, and look at the predicted outputs to find the input combinations corresponding to target outputs. 