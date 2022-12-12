# Synthetic-Data-Generation
This repository contains the code and paper that was written in terms of synthetic data generation. 

## Introduction
The project focuses on generating synthetic data by using the statistcial 
distributions and features from the original dataset. For this project 5 datasets were
considerd in which 4 datasets fall under the category of SINGLE TABULAR DATASET whereas the 
5th dataset is the RELATIONAL DATASET.  <br>

The classification of these datasets are as follows:<br>
* Project - Creating Synthetic Data to Handle Class Imbalance -> Single Tabular -> 38_Sick, 185_Baseball, LI0_1487_Ozone_Level_8hr, UKDA-8722 <br>
* Project - Creating Synthetic Data to Handle Class Imbalance -> Relational ->  32_Wikiqa <br>	

## Platform & Necessary Package Packages
The code for this project is written on python and can be run on GOOGLE COLAB or JUPYTER NOTEBOOK but before executing the code
some necessary packages needs to be istalled which can be accompalished by using the "pip" script command. The list of these packages are: <br>
					
					1. 'pandas' -> This library is for working with dataframes. 
					2. 'numpy' ->  To work with arrays. 
					3. 'matplotlib' -> To generate histograms.
					4. 'warnings' -> To remove the warning messages. 
				  5. 'pickel' -> To handle serialization.
					6. 'tabulate' -> To generate tables in the output. 
					7. 'seaborn' -> To generate count plot. 
					8. 'SDV' -> To use the functions that are generating & evaluating synthetic data.
          
## Data Storage Structure
For this project, the data storage structure needs to be stored according to the directory structure diagram below: <br>
1. Single Tabular <br>
  * Data/ Single Tabular/ 38 Sick
  * Data/ Single Tabular/ 185 Baseball
  * Data/ Single Tabular/ Ozone
  * Data/ Single Tabular/ UKDA - 8722
  
2. Relational <br>
  * Data / Relational / 32 
  
## Saved Models
For this project the saved models are stores as per the directory structure below: <br>
1. Single Tabular <br>
  * Saved Models/ Single Tabular/ 38 Sick 
  * Saved Models/ Single Tabular/ 185 Baseball
  * Saved Models/ Single Tabular/ Ozone
  * Saved Models/ Single Tabular/ UKDA - 8722
    
2. Relational <br>
  * Saved Models / Relational / 32 
