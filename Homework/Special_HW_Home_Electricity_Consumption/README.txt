Data Collection:
Collect your home past year electricity data in a CSV File. The data file should follow that of the template which has the following columns:
1. Date in the format of YEAR MONTH
2. Bill Amount
3. Days in Billing Cycle
4. KWH Usage

Filename
The filename should follow the following format each followed by an underscore: 
1. ZIPCODE: 5 digits.
2. Approximate size in square feet rounded to the nearest 100.
3. Type of Heater: GAS or ELECTRIC
4. House Type: Condo, Townhouse, SingleFamily
5. House Usage: Primary or Vacation
For example: 
1. 20871_2400_ELECTRIC_TOWNHOUSE_PRIMARY
2. 20871_NA_Gas_Apartment_Vacation
Note that for values that are not known use NA.

Share via email with instructor. This will be used for an example to show the data science process from data collection to analysis.

Questions:
1. When collecting the data think about possible challenges and limitations. ALso, think about other things that you would have liked this data or the data collection request would have beneficial to have. From other types of data to instructions on collecting the data.
2. Think about what other data could be used to augment the data. For example, data from other sources that could be combined with this one to provide more useful dataset.
3. One of the homeworks during the class we will be combining this data to try to make obtain some insights. At every point think about what you think woudl have been useful to do from the initial data collection. In many cases Data scientist do not get involved in the data collection process as they typically are accessing data that has been collected and exists in some database. However, they have to deal with the limitations of those databases.
4. In the homework we will be exploring the challenges of merging datasets, cleaning the data, transforming the data, deriving data, augmenting the data, exploring the data and using with ML models.
5. In this case we will try to transform the data by adding state and town from another dataset with zipcode/state/town data. We will attempt to augment the data with average monthly temperatures for that zipcode, we will derive data such as the cost of $ per kWh, aggregate by town and mean and compare rates, do various visualizations, and predict the cost of electricity given the forecasted temperature or month.

Potential Data Sources
https://www.weather.gov/
https://www.weather.gov/wrh/climate?wfo=lwx (Can we assume Washington Area in our dataset?)
