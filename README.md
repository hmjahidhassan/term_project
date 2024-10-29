OIL PRICE SHOCK ANALYSIS

	Repository Structure
	This repository contains all files related to the Oil Price Shock Analysis project, including the code, data files, project report, and README.

	Files in this Repository
		01. Term Project.py: The main Python file containing all code for the analysis. This script includes:
				a. Data Loading and Preparation: Loads formatted data from Price Data.xlsx, calculates daily returns, and prepares equal-weight indices for analysis.
				b. Regression Analysis: Runs regressions to examine the relationship between oil prices and sector-specific indices.
				c. Visualization: Generates and saves the rolling volatility and cumulative returns charts as .png files in the project directory.
				d. Raw Price Data.xlsx: The Excel file containing raw data collected from the Bloomberg terminal, with historical prices for oil companies, non-oil companies, oil prices, and the SPX index.
		02. Price Data.xlsx: The formatted and cleaned version of the raw data in Raw Price Data.xlsx, structured for direct use in Term Project.py.
		03. Term Project.docx: The Word document containing the full project report, including the objective, methodology, regression analysis results, visualizations, and conclusions.
		04. README.txt: The README file created in Notepad++, providing an overview of the project files and instructions for running the analysis.

	How to Run the Project
		Install Dependencies:
			* Ensure Python is installed on your system.
			* Install required packages by running:
					bash
					pip install pandas matplotlib statsmodels

		Run the Analysis:
			Execute Term Project.py to load data, conduct regression analysis, and generate visualizations. The script outputs regression summaries to the console and saves the figures as .png files in the project directory.
			Usage:
					bash
					python "Term Project.py"
