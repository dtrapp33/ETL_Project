![image](https://github.com/dtrapp33/ETL_Project/assets/132303328/d02e3d2d-c12a-43cb-93e2-8ada1c136090)

# ETL_Project

## The ETL project consisted of (2) parts.  
  - Find and clean a dataset. More specifically, not only clean the data, but to try and find something interesting to do on the data.
  - Take clean data and then create a database of our choosing.
  - The potential questions listed below helped guide our thought processs to create a more useable dataset.

# Data Cleaning  
## We imported the following CSV file from the kaggle website that contained Boat data. We then cleaned/inserted data in a variety of ways for better analysis.
  -Source: https://www.kaggle.com/datasets/karthikbhandary2/boat-sales?resource=download.  
  -split out currencies so that currency and price were in separate columns.  
  -created a database for currency conversions based on a static date listed in Dataframe.  
  -converted all prices to Euro's.  
  -converted from Euro to USD based on a static date listed in Dataframe.  
  -special characters were converted on multiple columns (location, manufacturer).  
  -split Location column into City and Country for further analysis.  
  -split Type column into Condition and Fuel for further analysis.  
  -reorganized columns for better readability.  
  -converted multiple columns datatypes.

# DataBase Creation  
## After cleaning the data we then exported the data to a SQlite database.  


## Potential Analysis Questions based on clean Dataset  
-Average cost per manufacturer  
-Countries with most boats for sale  
-type of boats available on market (fuel type, size, condition)  
-correlation of boat type and cost  
-average cost based on material and size  
-best pricing based on current conversion rates  
-correlation of price based on number of views


## References 

https://stackoverflow.com/questions/65375242/pandas-dataframe-converting-between-currencies

