# Energy Project

We are working with the data of UK Power Networks gathered using SmartMeter technology. This dataset is gathered from sample of 5,567 households between November 2011 and February 2014. Readings were taken every half hour. 
Data Columns:
1. Customer/Household Id (LCLid)
2. Household tariff type (stdorToU): Within the data set are two groups of customers. A sub-set of 1,100 customers (Dynamic Time of Use or dToU) were given specific times when their electricity tariff would be higher or lower price than normal – High (67.20p/kWh), Low (3.99p/kWh) or normal (11.76p/kWh). The rest of the sample (around 4,500) were on a flat rate of 14.228p/kWh.
3. DateTime: Reading of every half  hour.
4. KWH/hh: KWH per half hour
5. Accron: Ingore this field
6. Accron_grouped: Customer groups on income.

The full raw data is available to download from this drive folder. 

https://drive.google.com/open?id=12Be8raikn_cKS6qrD2k77lYceG6vgyik

The data folder has 168 csv files, each file contains 1 million data rows. A sample file is also available in main folder. However, at the top of the jupyter notebook you'll find a link to another folder that contains preprocessed/formated data that is later on used when importing data and using it throughout the notebook.
The rest of the details can be found in the Report.
