# tableau-challenge
 
# Data Pulling and Merging 

Data from all 12 periods in 2020 was pulled from the Citi Bike website. The csvs were read with pandas and created into dataframes. From here, a period column was added, and all of the dataframes were concatenated utilizing pd.concat. This final dataframe was then exported as a csv and inporting into Tableau.   

## Visualizations
### Customer vs Subscriber 
Interested into what prompts folks to purchasing annual vs temp subscriptions 

•	Customer = 24-hour pass or 3-day pass user; Subscriber = Annual Member)
•	Gender (Zero=unknown; 1=male; 2=female)

### Age 
