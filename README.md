# Condominium Price Data Wrangling with R
Introduction
This repository contain codes for preparing data specifically to analyze condominium price in Kuala Lumpur. The data was retrieved from kaggle website (https://www.kaggle.com/datasets/dragonduck/property-listings-in-kuala-lumpur).Feel free to customize and expand on this documentation based on the specifics of your project and analysis!

Library used
library(readxl) : For reading excel files
library(dplyr) : For data manipulation

Reading Data
1. The code reads an Excel file KualaLumpurDataset.xlsx containing property data. I use read_excel() instead of read.csv() (which is way more convenient) because i was experimenting something else. Feel free to not use that line of code.
2.  The code use view(KualaLumpurDataset) line to view the contents of the dataframe using a graphical user interface (GUI).

Data Cleaning
