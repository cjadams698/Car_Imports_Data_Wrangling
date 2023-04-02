# Car_Imports_Data_Wrangling
Use Jupyter notebooks for cleaning and pre-processing of car import data. Utilized Pandas to read into a dataframe which was then cleaned of null values. This involved replacing null values with the average for the column and deleting rows where price was missing (Because we are looking to predict price later on). Also converted data types for columns that loaded as Object when it should have been int or float. Created bins for horsepower and dummy variables for the fuel-type and aspirations columns for later use in regression analysis. Finally saved cleaned data to a CSV. 
