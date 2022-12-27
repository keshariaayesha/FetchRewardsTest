# FetchRewardsTest

## Implementation Steps
I created a python file to process the json data files. I performed the below steps in this file:
1) Flattened the JSON data file and stored the processed data in a dataframe
2) Masked device_id and ip columns in such a way where it is easy for data analysts to identify duplicate values in those fields
3) This transformed dataframe is then stored in a postgresql table called user_logins

