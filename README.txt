Code for TennisMV project:

tennis_output.7z - zip file containing data for all 120 rallies stored in sqlit3. 

cleaning_visualisation_functions.ipynb  - this notebook contains all of the functions I have created
					to be used for processing, cleaning and visualising the data.
					- it is used by both the pitg_extractor_Aggregate_v2.ipynb and TennisModelBuilding.ipynb

pitg_extractor_Aggregate_v2.ipynb - this notebook extracts the data from tennis_output.7z
				  - cleans the data by removing incorrect values and imputes missing values
				  - outputs dataframes allMatches.csv and playerStats.csv

TennisModelBuilding.ipynb	- this notebook takes the dataframes allMatches.csv and playerStats.csv
				- allMatches.csv is used to provide the densityplots
				- playerStats.csv is used to build the logistic regression model


Requirements:

- tennis_ouput.7z needs to be extracted to a folder named "tennis_output" and be located in the same directory as the .ipynb files.
- schema.png is needed for visualisations.
- metaMaster.csv is needed by the pitg_extractor_Aggregate_v2.ipynb