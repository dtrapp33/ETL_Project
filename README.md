# ETL_Project

We imported an existing CSV file that contained data surrounding Boats for sale in Europe. Source: https://www.kaggle.com/datasets/karthikbhandary2/boat-sales?resource=download

We then cleaned the data in a variety of ways prepare it for analysis. 
-split out currencies so that currency and price were in separate columns
-created a database for currency conversions based on a static date listed in Dataframe
-converted all prices to Euro's 
-converted from Euro to USD based on a static date listed in Dataframe
-special characters were converted on multiple columns (location, manufacturer)
-split Location column into City and Country for further analysis
-split Type column into Condition and Fuel for further analysis
-reorganized columns for better readability
-converted multiple columns datatypes 

After cleaning the data we then exported the data to a SQlite database. 

##Potential Analysis Questions based on clean Dataset

-Average cost per manufacturer
-Countries with most boats for sale
-type of boats available on market (fuel type, size, condition)
-correlation of boat type and cost 
-average cost based on material and size
-best pricing based on current conversion rates
-correlation of price based on number of views

