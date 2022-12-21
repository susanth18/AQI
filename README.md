# AQI

DATA COLLECTION:
The data was collected through webscrapping. Those datasets were combined according to the need of this analysis project. 
The final dataset used will be in the path Data\Real-Data\Real_Combined.csv

Html_script.py contains the code to retrieve the html text of websites from which we will be downloading the data.
Extract_Combine.py contains the code to combine the datasets that we got from retrieved HTML files using Html_script.py

IPYNB files contains the data analysis and model fitting code.
1) LinearRegression.ipynb

2) DecisionTreeRegression.ipynb
3) RandomForestRegressor.ipynb

Pickle files were created which were used for its deployment purpose in Heroku

Heroku Deployment folder contains the files for deployment

