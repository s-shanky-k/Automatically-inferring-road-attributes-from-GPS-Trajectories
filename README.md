# Automatically Inferring Road Attributes from GPS Trajectories
A method to automatically derive road attributes by analysing and mining movement trajectories (e.g. GPS trajectories). Movement trajectories can be used to automatically derive attribute data in maps.  

The repositary contains code for deriving the average speed, speed limit and whether the road is one-way or two-way.  
The research paper based of which this code was developed can be found [here](http://doi.org/10.1111/tgis.12186)

## Input
The input is a text file which is in the following format: `id,latitude,longitude,timestamp`   
Timestamp in the format: `yyyy-mm-dd hh:mm:ss+03 angle`  

A sample text file is part of the repositary  
The data used to built the code was from the Chicago taxi data set.

## Running the code
The repositary contains a jupyter notebook as well as a python script.

## Output
The code will output a CSV file which is of the format:
Road Name , 
The dataframe of the same can be viewed in the jupyter note book.
