# Tableau Challenge
 
## Data Pulling and Merging 

Data from all 12 periods in 2020 was pulled from the Citi Bike website. The csvs were read with pandas and created into dataframes. From here, a period column was added, and all of the dataframes were concatenated utilizing pd.concat. This final dataframe was then exported as a csv. The csv was opened in Microsoft Excel and the start time and end time columns were reformated. The csv was then imported into Tableau Public.   

## Visualizations

### Customer vs Subscriber 
#### The first phenomeneon I looked into was information about customers and Subscribers. Customers are poeple who puchase a 24-hour pass or 3-day pass, while Subscribers are people who purchase an annual membership. The visualization made show that: 
- Bikes are rented out more by subscribers than customers. 
- However, customers have a higher average trip duration than subscribers across all months of the year.
- There are more male customers and subscribers than there are female customers and subscribers, espcially for the subscriber user type.


### Age 
####  The second phenomena I wanted to look at was information around different age groups. What I found was that: 
- The majority of bike rentals were made by folks aged 31 - 35 years old, followed by 51 - 55 year olds and 26 - 30 year olds. 
- Though overall there are more male than female users, female users tend to have a higher trip duration than males across all age groups.
- For all age groups, the majority of bike rentals were made in September.

### Maps 
Finally, two maps were made highlighting the most popular start stations and end stations. The larger and darker the bubbles, the higher the usage of the station.