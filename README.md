# project_1_car_insurance

Hypothesis : Understanding the factors that influence the monthly premium for car insurance. 

Team Members: Jinseo, Rachel, Devi , Dhruv and Ardeshir.

Data Aquisition:
1) Kaggle.com (Auto_Insurance.csv)
2) Crash viewer : https://crashviewer.nhtsa.dot.gov/

Navigation : 
1) Main code is in car_insurance.ipynb
2) Output folder contains PNG files of all analysis plots.
3) Resources folder contains CSV file used for analysis. 

Data Cleaning: 
1) Reduced dataframe to include relevant columns required for analysis.
2) Filtered Dataset to remove all rows which had a income of 0.
3) Deleted the first row as it had only numbers and the information was not pertaining to insurance.

Challenges: 
1) One of the main challenges we faced was getting a dataset that was including all the determininants that make the monthly cost. We were able to find multiple datasets but would not have been able to merge them as they had no common keys. 
2) Although we were able to make conclusions with most of our data, there were many analysis that we conducted which were inconclusive and had no impact to monthly car insurance premiums.

Findings: Despite the challenges we persisted with no bias towards our conclusions and were able to make important findings that were impacting car insurances rates. 

Code: 
1) Python 3.12
2) Editors: Jupyter notebook and Visual Studio Code.
3) Packages: Pandas, Matplotlib, Scipy and Numpy

Analysis: 
1) We used Pandas to clean the data and to create dataframes needed to go ahead with our analysis.
2) We used Matplotlib, Pandas and Scipy to plot our findings and make comparisons to understand which elements impact monthly car insurance premiums the most.
3) We used linear regression to determine where there was enough in the data to use for a predictive model with some more insight and advanced techniques.
4) Based on the findings from our analysis we were able to provide some context as to how car insurance rates are set which could help a prospective customer understand how the rates are determined and make an informed decision accordingly.
5) One of the drawbacks that we experienced in our analysis is that our data was not covering all of the elements required to be more precise and thorough with our findings. But it was a valuable experience as we will be better equiped in the future when understanding the data we are to work with.
6) We also assume that insurance companies do not publish datasets on how the rates are determined in detail as that may be considered confidential information by most of them. We have tried our best to understand this with what we retrieved. 
