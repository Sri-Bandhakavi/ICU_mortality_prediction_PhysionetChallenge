# ICU_mortality_prediction_PhysionetChallenge
Predictions of in-hospital mortality for 4000 patients based on general and acute physiological descriptors available as time-series data

This Jupyter notebook implements the Physionet challenge (https://physionet.org/content/challenge-2012/1.0.0/) to predict mortality of 4000 ICU patients using data collected at time of admission (general descriptors) and over 48 hours on patients (acute physiological descriptors). For a full description of the dataset, challenge, and all predictors, please review the pdf file within repository named as: PhysioNet_Computing in_Cardiology_Challenge_2012.pdf

A final model is presented using 18 predictors - and its performance is shown to be better than a "benchmark" logistic regression model generated using currently standard measuress of mortality (eg: SOFA/SAPS-1 scores).

Note on running this notebook: To run the notebook, ensure you save needed data files ("seta.csv" and "outcomes.csv" provided as separate attachments within email containing this notebook) to the working directory containing this notebook.
