This is a ML project try to understand the laser machining process for engraving channels on ceramic surface. 

We use laser machining experimental data to train a ML model with the goal to 
find the relevant laser parameters for each target channel engraving.

An overview of the project and steps can be found in `Laser_ML_overview.pdf`. The paper reporting the results titled "Machine Learning-Driven Process of Alumina Ceramics Laser Machining" is under review in the journal of Intelligent Manufacturing. 


Different stages of data analysis in different jupyter notebooks are:

- Data cleaning in notebook `Data_cleaning.ipynb`

- Raw data analysis by looking at the correlation coefficients and pair plot in `RawData_analysis.ipynb`

- Looking at the variable dependence for engraved channel depth in `Depth_IndivParamDep.ipynb` and widths in `Width_IndivParamDep.ipynb`

- Comparing performances of different ML models for prediction channel dimensions in `ML_methods-3pred.ipynb`

- Looking at the feature importance using XGB in `XGB_variableImportance.ipynb`

- Trying different NN structures in `NN_structure.ipynb` and visualizing the chosen model in `NN_Visualization.ipynb`

- Using different methods for optimizing the NN hyperparameters in `Optimization.ipynb`

- Making a grid of parameter combinations to feed to a trained model in `Making_Compbinations.ipynb`

- Making laser combinations using Generative Adversarial Network (GAN) in `GAN_3output_rescale.ipynb`

- Finding the laser parameters for target cut parameters in `Extract_table.ipynb`

- Testing the NN model for some experimental test cases in `NNTesting.ipynb`

- For the purpose of publications, reporting the experimental data in multiple tables and changing the data indexing in `Data_report.ipynb`

 


