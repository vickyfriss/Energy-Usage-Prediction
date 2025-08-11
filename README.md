# Energy-Usage-Prediction
# Introduction
In this project, the challenge presented by the "ASHRAE - Great Energy Predictor III" competition is being tackled. The
project focus is on developing a tool to evaluate the value of energy efficiency upgrades in energy savings. This involves
constructing counterfactual models to compare post-upgrade energy consumption against modelled values for the original
building, thereby estimating retrofit savings.
The dataset provided for this project encompasses building metadata, weather data, and energy consumption records. The
main challenge is to develop predictive models capable of forecasting energy usage for multiple buildings.


Project Title: Energy Usage Prediction
Group Number: 21

### FILES ###
DataPrep.ipynb
The notebook with the code to prep the raw Kaggle data for the preprocessing pipeline.
	*requires the raw Kaggle data to run

EDA_Plots.ipynb
The notebook with code to generate all the EDA and some preprocessing plots.
	*requires all the raw Kaggle data to run 

EDA_Weather_Plots.ipynb
The notebook with code to generate all the plots associated with the weather data.
	*requires all the raw Kaggle data to run 

Error_analysis.ipynb
The notebook with code used to run the error analysis.
	*requires predicted data (predicitions.csv) from final-processing-and-model.ipynb to run

final-processing-and-model.ipynb 
The notebook used to run the preprocessing pipeline and final artificial neural network model.
	*requires output (temp_df.csv) from the data_prep.ipynb

Model_ANN_BaseNodes_Activation_Test.ipynb
The notebook used to run the test of all the activation functions on the base model.
	*requires x_train, x_val, y_train, and y_val exported to csv from thfinal-processing-and-model.ipynb to run

Model_ANN_ELU_Nodes_Tests.ipynb
The notebook used to run the test on all the different numbers of node options on the chosen activation function, ELU.
	*requires x_train, x_val, y_train, and y_val exported to csv from final-processing-and-model.ipynb to run

### HOW TO RUN ###
	*requires data from the ASHRAE - Great Energy Predictor III Kaggle competition to run.

1. Run the Data Prep with the data downloaded from Kaggle competition.
2. Run the final_processing_and_model.ipynb to process the data and fit the final chosen model.

For other files to run, see what data is required to run and update paths accordingly.

