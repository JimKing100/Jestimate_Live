# Jestimate_Live
The final live version of Jestimate.

The contents include the following:

data - a data directory

- SF-SFR-Sales-Final.csv - The raw data downloaded from the SF MLS for all single-family home sales in SF 2009-2018.
- Realtor Neighborhoods.geojson - The mapping data downloaded from https://data.sfgov.org/Geographic-Locations-and-Boundaries/Realtor-Neighborhoods/5gzd-g9ns
- display_data.csv - The output from the linear regression model produced by Final_LR.ipynb providing the data for the map.
- nhoods-test.csv - The test data produced by the comparable sale code in Final_LR.ipynb.  The code takes about 2 hours to run so this is simply to save time when running Final_LR.ipynb.
- nhoods-train.csv - The train data produced by the comparable sale code in Final_LR.ipynb.  The code takes about 2 hours to run so this is simply to save time when running Final_LR.ipynb.

Colab Notebooks

The project is split into two parts.  The linear regression is run in Final_LR.ipynb and the final dataframe is output to display_data.csv.  Then Final_SF_Map_Code.ipynb uses display_data.csv to populate and display the interactive map. 

- Final_LR.ipynb - The colab code for running the linear regression model.
- Final_SF_Map_Code.ipynb - The colab mapping code for the interactive SF Real Estate Map.

Heroku Files

- SF_2018_Sales.py - Final executable python code from SF_Map_Code_Final.ipynb
- Procfile
- requirements.txt
