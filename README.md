# surfs_up
## Overview:
### Purpose
This analysis was completed to secure funding for an ice cream and surf shop on the island of Oahu, HI.
### Data Sources and Methodology
Data was used from a sqlite database of Hawaii weather stations and their observations
Sqlalchemy was used the reflect the tables from the sqlite database so we can query the data using Python.
Once the data was queried and converted to a pandas dataframe we can run summary statistics to view the key differences in weather station observation between June and December.

## Results
### Summary Statistics
The results of the June and December weather station temperature observation dataframe summary statistics are shown below:

June Temps Summary:

<img width="151" alt="June_temps_summary" src="https://user-images.githubusercontent.com/95047485/154865267-4284fac5-f4de-4fc6-88ca-901ad4840a09.PNG">

December Temps Summary:

<img width="137" alt="Dec_temps_summary" src="https://user-images.githubusercontent.com/95047485/154865280-d6c299bb-b78f-4aba-9bd1-a2a1d6cc1aa6.PNG">
### Rundown
*The average temps in December are lower than average temps in June
    *This could lead to less ice cream sales, however surfing is better in December so that could make up for the loss in ice cream sales
*While the temperatures are lower in December, they are still well within the range of expecting good ice cream sales
*The max temperatures are only 2 degrees apart

## Summary
With the seasonality of both surfing and icecream, it is the opinion of this analyst that the shop is a good idea. While one activity might be down in participation, the other will be up.
### Additional Queries
It would be useful to append a station ID to each observation then groupby most active stations. Once the most active stations are identified the results can be queried by the most active stations. We could also query precipitation for each weather station. Hawaii can have variable weather depending on the leward or windward side of the island. Perhaps real estate can be found near a station that has generally lower precipitation which may result in more ice cream sales. 




