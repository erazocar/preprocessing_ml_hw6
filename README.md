# Preprocessing, Logistic Regression and SVM
This repo serves for the usage of regularized logistic regression, Support Vecotr Machines and preprocessing approaches.
# Input Files
Please change the name of the path directories in which the data and the models can be saved. This are the variables named "path#". The docs should be found in a local directory called docs.
# Libraries
Please install libraries required for the Python program to run. In case there is a problem, a google colab link has been provided inside the code for usage online. It is linked to an open drive that contains the data used for the analysis. Would require a google account to access it but is open to anyone.
# Code Description
function reader1,2 = reads data from txt files.

function training_LogReg = trains regularized logistic regression.

function training_SVM = trains support vector machines with on different types of kernels.

function c_selectionSVM = find the best c for SVM in different kernel types.

function c_selectionLSVM = finds the best C for linear SVM within 1500 iterations.

function SV_pipeliner: trains a linear SVM given a specific standardization approach.

function class_report: creates a dataframe with the AUC score included.
