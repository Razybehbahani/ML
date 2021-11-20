This is a ML project to understand the laser machnining process for engraving channels on ceramic surface. 
We use laser machining experimental data to train a ML model with the goal to 
find the relevent laser parameters for each target channel engraving

Different stages of data alnalysis in different jupyter notebooks are:
- Data cleaning
- Raw data analysis by looking at the correlation coefficients and pair plot in "RawData_analysis.ipynb"
- Looking at the variable dependence for engraved channel depth in "Depth_Indiv_param_dep.ipynb" and widths in "Width_indiv_param_dep.ipynb"
- Looking at performance of different ML models for prediction channel dimentions in "ML_methods-3pred.ipynb"
- Looking at the feature importance in XGB in "XGB_variableImportance.ipynb"
- Trying different nn structures in "NN_structure.ipynb" and visualizing it in "NN_Visualization.ipynb"
- Using different methods for optimizing nn hyperparameters in "Optimization.ipynb"
- Making a grid of parameter combinations to feed to a trained model in "Making_Compbinations.ipynb"
- Making laser combinations using Generative Adversarial Network (GAN) in "GAN_3output_rescale.ipynb"
- Finding the laser parameters for target cut parameters in "Extract_table.ipynb"
- Testing the nn model for some experimental test cases in "ModelTesting.ipynb"

