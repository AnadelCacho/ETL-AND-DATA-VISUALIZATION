# ETL-AND-DATA-VISUALIZATION

Author
Ana María del Cacho Tena

Note: There are two different proyects here, so the BBDD are different:

Project 1: ETL
Project 2: Visualization.


Table of Contents
1.  ETL (project 1) in Jupyter Notebooks using Python
2.  Excel with the data (proyect 1)
3.  Visualization in PowerBI (proyect 1)
4.	Visualization proyect 2 (a Tableau Format Document)
5.	Excel with the Data (proyect 2)

_______________________________________________

Proyect 1:
1. Introduction
You have been hired by an NGO ( a non-governmental organization; you choose the area of work, below you will understand :? ) to enhance their Data Warehouse by incorporating public data from the internet. Your role is to identify, cleanse, and store the relevant data to facilitate better decision-making within the NGO.


2. What are the main objectives in this project?
Cleaning, transforming and organizing the provided CSV file named ETL_project-postal_codes.csv. The resulting table should have the following columns:
id:			An integer starting from 1001.
cp:			Postal code.
provincia:		Province.
ciudad:		City.
provincia_local:	Province name in the local language.
ciudad_local:		City name in the local language.


Observation: The number of columns (features) in the resulting data frame will depend on the data returned by the request. There will be as many columns with years as there is population information for that year.
Important: All columns, without exception, need to be extracted from the JSON file that is returned by a request. 
Hint: The data of interest is labeled with the code "MUN" which can be found as an element within the "Metadata" list.

_____________________________________________

Project 2
Tableau is a data visualization tool that contains functions for cleaning, transforming and working with different types of data. This tool is very complete, as it allows a wide range of options, from creating relationships to providing interactive Dashboards through actions and parameters.
Process difficulties
The biggest difficulty we have found is that there is little documentation compared to PowerBI to perform complex queries, so the investment of hours has been higher than expected. 

