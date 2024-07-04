# ML_for_drug_discovery
Using machine learning to identify potential drug candidates for acetylcholinesterase

* In Part 1, I have collected bioactivity data from the chEMBL database, performed pre-processing like remove missing datapoints, remove duplicates, and labelled compounds based on their bioactivity threshold.
* In Part 2, I have performed exploratory data analysis which includes cleaning the SMILES notation, removing salt molecules from the structure, calculate lipinski descriptors and perform EDA by plotting graphs like boxplot, scatterplot, etc
* In Part 3, I performed calculations for additional descriptors using PADEL like creating the input for generating the PADEL descriptor and using them to create fingerprints for the compounds.
* In Part 4, I have built a RandomForest model to predict the pIC50 values for the compounds. Before that, I removed low variance features and split the data for training and testing.
* In Part 5, I compared several ML models to figure out which is best suited for the task at hand.
* In the last part, I have written a script so that the user can provide the input molecule and the model would return back its bioactivity score that can be used to determine if it is a potential drug target.
