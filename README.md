# business-records-linkage-spark-challenge
Creating a set of data to use for an Apache Spark Challenge event. The point of this event is to try and match a set of records to a master set. The linkage file contains typos and missing data that require some creativity in matching the link file to the master, then cleaning the link file with the correct data.

# Data Sets
We will create three data sets: 
1) Master business record set
2) Training File: Linkage file with typos
3) Test File: Linkage file to test robustness of algorithms created for the training set

## Data Elements
BusinessGUID -- global unique ID
BusinessPIK  -- Personal ID Key -- for linking/masking the GUID
Name -- Business Name
Address -- Business Address (US)
City -- City (US)
State -- State (US)
Zip -- Five digit zip code




