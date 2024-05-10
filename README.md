# Computational Epidemiology of COVID Mutations



UCD Computer Science Project (COMP30170)

by Adam Brennan

The main goal of this project was to create a working ASEIR model in Python and adapt it to allow for mutations to occur. With the proper adjustments made, the model should be able to implement any number of mutations of varying infection rates and be able to accurately present the resulting effects on a population. We hope to gain an understanding of what variables are most critical in the mutation of a virus as it spreads, such as the time between mutations or the chance of infection. 

The notebooks are organised in run order as follows:

Data Preprocessing:
01_COVID_Data_Preprocessing.ipynb - This file contains the code required to import the csv containing global covid statistics, as well as cleaning the data and exporting a processed csv ready for analysis. 

Model:
02_ASEIR_Model_&_Mutations - This file contains all code relevent to the design and use of the ASEIR Model that has been adapted for multiple mutations. It also contains some tests run to determine the functionality of the model and how the variables can affect the graphs produced.

Data Comparison:
03_Analysis - This file contains a series of comparisons between the real world COVID-19 Data and the values produced by the ASEIR Model designed in this project.

Additional Material:
04_ASEIR_Additional_Code - This file contains some steps of the ASEIR Mutations model that were not deemed relevent to the functionality but still may offer some insight into how it was designed. 


All files and cells within should be ran in order.

This project also contains the csv files used in the project:

CONVENIENT_global_confirmed_cases was the file found on Kaggle, the link for which is in the notebook, 01_COVID_Data_Preprocessing.ipynb.

processed_data was the cleaned csv file produced by 01_COVID_Data_Preprocessing.ipynb and was used for analysis in the notebook 03_Analysis. 
