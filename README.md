# Connecting to Mongo DB No SQL repository to extract Shopify data

This program was created with the goal of connecting to a MongoDB repository (NoSQL database) and being able to extract the data using Mongo DB Pipeline/aggregation language, for subsequent manipulation.


## Quick Description
The jupyter notebook connects to Google drive to securely get connection string, then connects to Mongo DB repository, makes a request to get the data and then through the use of Mongo Db pipeling queries the needed that from resulting mongoDB response, finally it converts it to python Data frame.

## Modules used

-pymongo
-pandas
