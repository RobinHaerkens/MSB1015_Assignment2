# MSB1015_Assignment2
This repository will contain all files required and made for the second assignment of MB1015

For this assignment PLS will be used to predict alkane boiling points based on their chemical structure using the molecule distriptors from the Chemical development Kit.

The repository contains the Assignment_2 file containing all the code.
The data is obtained from wikidata using a sparql query in R, which gives a dataframe as output, which is then further used for quality control of the data and then a pls model is created to predict alkane boiling points based on their SMILES and other molecule descriptors.
Lastly the RMSEP is shown and prediction accuracy plots are mode

Furthermore does the repository contain an Rmarkdown file converted into an HTML page (in Rmarkdown_final folder) called index.html

As a side note: the last plot (prediction of test data vs actual data) may give an error when the code is ran.
I'm unsure how to fix this as the error doesn't always appear and about half of the time the code just runs like intended.

Author that contributed to this assignment 
Robin Haerkens
